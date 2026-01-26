.. _prenos_dat:

Přenos dat z JIP/KAAS do CAAIS
==============================

Přenos dat mezi systémy JIP / KAAS a CAAIS provádí :ref:`lokální administrátor (LA) <la_prirucka>` vašeho subjektu. Tento proces zahrnuje přenesení uživatelských účtů a jejich rolí z původního systému do CAAIS.

**Než se pustíte do přenosu dat, doporučujeme provést v JIP/KAAS revizi uživatelů.** Zneplatněte (zablokujte) uživatele, které do CAAIS z jakéhokoli důvodu přenášet nepotřebujete (např. již ve vašem subjektu nepracují). U aktivních účtů zkontrolujte, zda mají vyplněnou tzv. oficiální e-mailovou adresu. Právě na ni uživatelům přijde notifikační e-mail, v němž budou vyzváni k ověření totožnosti, a kam jim posléze přijde i zpráva s pokyny k aktivaci účtu.

.. admonition:: Poznámka
   :class: note
   
   Doporučujeme, abyste před spuštěním ostrého přenosu informovali uživatele, že obdrží uvítací e-mail, protože unikátní odkaz s výzvou ke ztotožnění má omezenou platnost 30 dnů.

Zahájení přenosu
----------------

Přenos uživatelských dat z JIP/KAAS je možné provést v simulovaném i ostrém režimu. V obou případech se musíte do CAAIS přihlásit s právy :ref:`lokálního administrátora (LA) <la_prirucka>` a mít příslušná práva i v systému JIP/KAAS.

.. dropdown:: Postup pro zahájení přenosu dat z JIP/KAAS do CAAIS

   1. V levém menu vyberte volbu **Přenos dat**.

   .. figure:: ../images/prenos_dat-1.png
      :alt: Postup pro zahájení přenosu dat z JIP/KAAS do CAAIS 1
      :width: 1000px

   2. Systém vás přesměruje do prostředí pro migraci dat z JIP/KAAS, na záložku Uživatelé. Jakmile nějaké přenosy provedete, najdete zde jejich seznam. Pro zahájení nového klikněte na **+ PŘENOS**.

   .. figure:: ../images/prenos_dat-2.png
      :alt: Postup pro zahájení přenosu dat z JIP/KAAS do CAAIS 2
      :width: 1000px

   3. Na další stránce *„Nový přenos uživatelů“* vyplňte své přihlašovací údaje (jméno a heslo) do JIP/KAAS a zvolte, zda chcete přenášet data z produkční nebo testovací verze JIP/KAAS. Pole *„Zkratka přenášeného subjektu ve zvolené verzi JIP“* už bude přednastavená, není potřeba ji měnit. Nakonec určete, zda chcete provést simulaci přenosu (*„Chci vyzkoušet přenos nanečisto“*), nebo jste připraveni na ostrý režim. Pokračujte tlačítkem **PŘENÉST UŽIVATELE**.

   .. admonition:: Poznámka
      :class: note
   
      V případě simulace proběhne přenos na úplně stejném principu jako ten ostrý, tzn. budou uloženy všechny logy, seznam uživatelů i chyb. **Jediným rozdílem je, že se data do CAAIS neuloží.**

   .. figure:: ../images/prenos_dat-3.png
      :alt: Postup pro zahájení přenosu dat z JIP/KAAS do CAAIS 3
      :width: 1000px

   4. Po potvrzení přenosu vás systém pošle zpět na seznam provedených migrací, kde uvidíte i právě založený požadavek. Aktuální přenos bude mít příznak **„Podáno“**. Jakmile systém začne úlohu zpracovávat, stav migrace se nastaví na **„Probíhá“**. Aplikace pro přenos dat přetáhne z JIP/KAAS do CAAIS detaily jednotlivých aktivních uživatelů v rozsahu *uživatelské jméno, jméno, příjmení, tzv. oficiální e-mail, telefonní čísla a seznam přidělených přístupových a činnostních rolí a agend*.

Proces přenosu dat
------------------

Nový profil
^^^^^^^^^^^

Nástroj během přenosu prohledává seznam uživatelů v JIP/KAAS. Pokud uživatelský profil s daným uživatelským jménem v systému CAAIS neexistuje, je automaticky založen.

Dále jsou z JIP/KAAS dotaženy uživatelské údaje a přístupové a činnostní role vázané na uživatelský účet. Ovšem pouze role, které v CAAIS existují a které má subjekt, jež přenos dat provádí, přiřazené. Synchronizace rolí přitom probíhá na základě zkratky pro přístupové, resp. kódu pro činnostní role.

Jakmile je migrace uživatelského účtu dokončena, zapíše se k němu stav „Založeno".

S účtem propojená fyzická osoba ovšem musí být před vstupem do systému ztotožněna. Proto, ačkoli je k jejím účtu přiřazen stav „Aktivní", její status je „Před ztotožněním" a atribut „Osoba evidována v ROB" nastaven na NE.

Přeskočení účtu
^^^^^^^^^^^^^^^

Nástroj pro přenos dat je koncipovaný jako jednorázový. Jakmile narazí na uživatelské jméno, které je již v CAAIS zaregistrováno, zápis přeskočí. To znamená, že pokud jste mezi jednotlivými přenosy provedli v JIP/KAAS na daném uživateli nějakou změnu, tato se do CAAIS nepropíše! Do logu se zapíše stav „Přeskočeno".

Chyba během přenosu uživatele
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Pokud dojde během přenosu uživatelů k nějaké chybě při ukládání, je konkrétní účet přeskočen. Za chybový účet, který není možné přenést, je považován například ten, který nemá v JIP vyplněn „oficiální" e-mail, neboť ten je v systému CAAIS povinný. Do logu se zapíše stav „Chyba" a její popis naleznete v detailu přenosu uživatele.

Obecná chyba během přenosu
^^^^^^^^^^^^^^^^^^^^^^^^^^

Pokud během přenosu dojde k nějaké chybě, kvůli níž není možné přenos jako takový dokončit, získá záznam o migraci stav „Chyba“. Její popis naleznete v detailu záznamu.

Ukončení přenosu
^^^^^^^^^^^^^^^^

Pokud nedošlo ani u jednoho uživatele vedeného v JIP k chybě, po zpracování posledního uživatele se nastaví stav celé migrace na „Dokončeno".

Záznam přenosu
^^^^^^^^^^^^^^

Záznam o přenosu se vygeneruje pro ostrou i simulovanou migraci uživatelů a najdete ho v přehledu Přenos dat. V tabulce naleznete seznam všech provedených přenosů s informacemi o času založení požadavku, s jakým atributem byl proveden (chyba/dokončeno), počet přenesených uživatelů, počet přeskočených uživatelů a počet uživatelů, u nichž se vyskytla chyba. Je zde i označení, zda se jednalo o simulaci, nebo ostrý přenos. Kliknutím přejdete na detail záznamu, kde je navíc čas ukončení přenosu a případně popis chyby, kvůli níž byla celá migrace přerušena.

Záznam přenosu uživatelských účtů
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Záznam o přenosu jednotlivých uživatelských účtů je v detailu přenosu dat v záložce Uživatelé. V tabulce naleznete seznam všech účtů, kterých se migrace týká s informacemi o tom, s jakým atributem byl daný účet zpracován (vytvořeno/přeskočeno/s chybou). Po kliknutí na konkrétní řádek přejdete na detail záznamu, kde naleznete podrobnosti o případné chybě.

Dokončení přesunu z JIP/KAAS
^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Opravdu dokončená migrace jako taková, tedy ukončení celého procesu přenosu všech uživatelů z JIP/KAAS do CAAIS, je provedená, až když jsou všechny uživatelské účty přeneseny s výsledkem „Založeno“ nebo „Přeskočeno“. Poté je zaznamenán datum a čas poslední migrace a atribut „Migrace provedena“ se změní na „Ano". Po dokončení se vám již nabídka Přenosu uživatelů nebude zobrazovat. Pokud byste potřebovali v budoucnu akci opakovat, požádejte nás o odblokování cestou Service Desk.

Zahájení přenosu zřizovaných organizací
---------------------------------------

Proces přenosu dat při migraci zřizovaných organizací
-----------------------------------------------------