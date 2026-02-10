.. _onboarding:

Onboarding
==========

1. Statutární zástupce založí lokálního administrátora v systému CAAIS
----------------------------------------------------------------------

.. dropdown:: Založení lokálního administrátora datovou zprávou
    :open:

    O vytvoření profilu a přidělení role :ref:`lokálního administrátora <la_prirucka>` můžete požádat prostřednictvím `formuláře „Založení lokálního administrátora datovou schránkou“ <https://caais.gov.cz/la-create>`_ a odesláním jeho výstupu datovou schránkou.

    .. figure:: ../images/SZ_zalozeni_LA_DS-1.png
        :alt: Založení lokálního administrátora datovou schránkou 1
        :width: 1000px

    1. Do formuláře vyplňte všechna pole označená hvězdičkou.

    .. figure:: ../images/SZ_zalozeni_LA_DS-2.png
        :alt: Založení lokálního administrátora datovou schránkou 2
        :width: 1000px

    2. V případě potřeby lze založit i několik lokálních administrátorů najednou. Stačí kliknout na **„+ Lokální administrátor“** a ve formuláři se zobrazí další pole. Pokud si založení dalšího administrátora rozmyslíte, stačí kliknout na ikonu popelnice.

    .. admonition:: Upozornění
        :class: warning
    
        **Nezapomeňte, že všichni takto založení uživatelé budou mít v systému CAAIS roli lokálního administrátora a budou moci spravovat váš subjekt i jeho uživatele.**

    .. figure:: ../images/SZ_zalozeni_LA_DS-3.png
        :alt: Založení lokálního administrátora datovou schránkou 3
        :width: 1000px

    3. Po vyplnění všech údajů klikněte na **„Generovat XML“**. Do počítače se vám stáhne XML soubor, který odešlete z datové schránky vašeho subjektu (organizace) do datové schránky systému CAAIS **ejmm527** (touto datovou zprávou zasíláte pouze XML soubor, žádný další text popř. průvodní dopis není potřeba).

    .. figure:: ../images/SZ_zalozeni_LA_DS-4.png
        :alt: Založení lokálního administrátora datovou schránkou 4
        :width: 1000px

    4. Úřad obdrží vyrozumění o zpracování žádosti do datové schránky během několika minut.

2. Lokální administrátor se ztotožní v systému CAAIS
----------------------------------------------------

A. Akcivace účtu Identitou občana / NIA
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. dropdown:: První přihlášení Identitou občana / NIA
    :open:

    Pokud se budete přihlašovat výhradně prostřednictvím NIA, nahrání certifikátu není nutné. V takovém případě ale přijdete o možnost používat CAAIS IdP, tedy přihlášení prostřednictvím jména, hesla a certifikátu.

B. Akcivace účtu v CAAIS IdP (jméno, heslo, certifikát)
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. dropdown:: Postup aktivace účtu v CAAIS IdP

    1. Odkaz z e-mailu vás přesměruje na stránku **„První přihlášení do CAAIS IdP“** a vyzve k vyplnění uživatelského jména. Jakmile jej vyplníte, klikněte na tlačítko **POKRAČOVAT**.

    .. figure:: ../images/BU_CAAIS-IdP_Au-1.png
        :alt: První přihlášení do CAAIS IdP
        :width: 1000px

    2. Pro ověření shody potvrďte volbu zaslání na e-mail, případně SMS (v případě, že systém zná vaše mobilní telefonní číslo) a na další stránce jednorázový kód přepište do příslušného pole.

    .. figure:: ../images/BU_CAAIS-IdP_Au-2.png
        :alt: První přihlášení do CAAIS IdP
        :width: 1000px

    3. Dalším krokem je vytvoření hesla. Systém vyžaduje heslo o minimálně 10 znacích a obsahující alespoň jedno velké písmeno. Pro kontrolu heslo zopakujte a klikněte na **POKRAČOVAT**.

    .. figure:: ../images/BU_CAAIS-IdP_Au-3.png
        :alt: První přihlášení do CAAIS IdP
        :width: 1000px

    4. Jestliže všechny kroky proběhly správně, pokračujte volbou **K PŘIHLÁŠENÍ**.

    .. figure:: ../images/BU_CAAIS-IdP_Au-4.png
        :alt: První přihlášení do CAAIS IdP
        :width: 1000px

    5. Pod přihlašovacím formulářem najděte text **+ CERTIFIKÁT**.

    .. figure:: ../images/BU_CAAIS-IdP_PncdCAAIS-1.png
        :alt: První přihlášení do CAAIS IdP
        :width: 1000px

    6. V dalším kroku vyplntě své uživatelské jméno a heslo a následně klikněte na **NASTAVIT CERTIFIKÁT**.

    .. figure:: ../images/BU_CAAIS-IdP_PncdCAAIS-2.png
        :alt: První přihlášení do CAAIS IdP
        :width: 1000px

    7. Systém vám pošle e-mail nebo SMS s ověřovacím kódem.

    8. Na následující stránce zadejte obdržený kód do příslušného pole a klikněte na tlačítko **NAHRÁT**. V počítači vyskočí okno s nabídkou certifikátů, které v něm máte nainstalované. Vyberte správný certifikát a potvrďte.

    .. figure:: ../images/BU_CAAIS-IdP_PncdCAAIS-3.png
        :alt: První přihlášení do CAAIS IdP
        :width: 1000px

    Nyní se můžete do svého účtu v systému CAAIS přihlašovat prostřednictvím jména, hesla a certifikátu a zároveň používat účet CAAIS pro přihlašování do agendových informačních systémů vyžadující značnou mírou zabezpečení.

3. Lokální administrátor založí uživatele v CAAIS
--------------------------------------------------

.. dropdown:: Přenos dat uživatelů
    :open:

    1. Pro založení nového uživatele klikněte na položku **Uživatelé**. Zobrazí se seznam všech již existujících uživatelů. Pokračujte kliknutím na **+UŽIVATEL**.

    .. figure:: ../images/LA_CAAIS-1.png
        :alt: Postup pro založení nového uživatele v CAAIS 1
        :width: 1000px
    
    2. Budete přesměrováni na formulář, kde vyplníte základní údaje o uživateli.

    .. figure:: ../images/LA_CAAIS-2.png
        :alt: Postup pro založení nového uživatele v CAAIS 2
        :width: 1000px
    
    3. Dalším krokem je kontrola ztotožnění uživatele. Ztotožnění je možné provést několika způsoby Preferovaná varianta je že se **Uživatel se ztotožní sám**. Uživateli přijde e-mail s předmnětem :ref:`„Byl vám založen profil v CAAIS“ <email_CAAIS>` (a je potřeba se doztotožnit). 

    .. figure:: ../images/LA_CAAIS-3.png
        :alt: Postup pro založení nového uživatele v CAAIS 3
        :width: 1000px

    4. Objeví se hláška o úspěšném založení profilu a uživateli je zároveň poslán e-mail s odkazem na stránku, na níž ztotožnění dokončí. Pozor, odkaz má omezenou platnost. (platnost je 30 dní!)

    .. figure:: ../images/LA_CAAIS-7.png
        :alt: Postup pro založení nového uživatele v CAAIS 7
        :width: 1000px

.. dropdown:: Přiřazení rolí
    :open:

    Úkolem lokálního administrátora je také přiřazení rolí uživatelům, aby se mohli přihlásit do konkrétních informačních systémů. V záložce **Správa rolí** v detailu uživatele kontrolujete, případně přidáváte a odebíráte konkrétnímu uživateli příslušné role.

    .. figure:: ../images/LA_CAAIS_role-1.png
      :alt: Přiřazení role v detailu uživatele
      :width: 1000px

..
    3. Lokální administrátor převede uživatele z JIP / KAAS do CAAIS
    -----------------------------------------------------------------

    .. dropdown:: Přenos dat uživatelů
        :open:
        
        1. V levém menu vyberte volbu **Přenos dat**.

        .. figure:: ../images/prenos_dat-1.png
            :alt: Postup pro zahájení přenosu dat z JIP/KAAS do CAAIS 1
            :width: 1000px

        2. Systém vás přesměruje do prostředí pro migraci dat z JIP/KAAS, na záložku Uživatelé. Jakmile nějaké přenosy provedete, najdete zde jejich seznam. Pro zahájení nového klikněte na **+ PŘENOS**.

        .. figure:: ../images/prenos_dat-2.png
            :alt: Postup pro zahájení přenosu dat z JIP/KAAS do CAAIS 2
            :width: 1000px

        3. Na další stránce *„Nový přenos uživatelů“* vyplňte své přihlašovací údaje (jméno a heslo) do JIP/KAAS. Pole *„Zkratka přenášeného subjektu ve zvolené verzi JIP“* už bude přednastavená, není potřeba ji měnit. Pokračujte tlačítkem **PŘENÉST UŽIVATELE**.

        .. figure:: ../images/prenos_dat-3.png
            :alt: Postup pro zahájení přenosu dat z JIP/KAAS do CAAIS 3
            :width: 1000px

        4. Po potvrzení přenosu vás systém pošle zpět na seznam provedených migrací, kde uvidíte i právě založený požadavek. Aktuální přenos bude mít příznak **„Podáno“**. Jakmile systém začne úlohu zpracovávat, stav migrace se nastaví na **„Probíhá“**. Aplikace pro přenos dat přetáhne z JIP/KAAS do CAAIS detaily jednotlivých aktivních uživatelů v rozsahu *uživatelské jméno, jméno, příjmení, tzv. oficiální e-mail, telefonní čísla a seznam přidělených přístupových a činnostních rolí a agend*.


4. Běžný uživatel ztotožní svuj účet v systému CAAIS
----------------------------------------------------

.. dropdown:: Aktivace účtu běžného uživatele
    :open:

    Běžný uživatel nalezne ve své e-mailové schránce zprávu s předmětem **„Byl vám založen profil v CAAIS“** s odkazem pro ztotožnění svého profilu v CAAIS.

    1. Po kliknutí na odkaz v e-mailu vás systém přesměruje na stránku **„Jak se chcete ztotožnit“**, kde si zvolíte způsob, kterým chcete svou totožnost ověřit. Máte na výběr z několika možností z nichž nejjednodušší je vybrat jednu z následujících možností:

    - **Identita občana / NIA** - Totožnost ověříte prostřednictvím přihlášení se k Identitě občana. Systém CAAIS vás ověří na základě informací poskytnutých NIA.

    - **Doklad totožnosti** - Po zvolení této možnosti vás systém vyzve, abyste vybrali druh dokladu, který chcete pro ověření totožnosti použít a uvedli jeho číslo. Pokračujte kliknutím na tlačítko ZTOTOŽNIT.

    .. figure:: ../images/CAAIS_samoztotozneni.png
        :alt: Možnosti ztotožnění uživatelského proflilu v CAAIS
        :width: 1000px

    2. Po úspěšném ověření totožnosti pokračujte na stránku **„První přihlášení”**.

    **Uživatel je tímto krokem ztotožněn a může se přihlašovat k agendovým informačním systémům pomocí CAAIS.**