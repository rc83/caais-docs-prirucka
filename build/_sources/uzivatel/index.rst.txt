==========================
Příručka běžního uživatele
==========================

Pokud přistupujete do CAAIS jako běžný uživatel, byl vám pravděpodobně zaslán email z **noreply-test-ext@caais.gov.cz** s předmnětem „Byl vám založen nový účet v CAAIS IdP“, případně s předmětem „Byl vám založen profil v CAAIS“. Tento email obsahuje postup, podle kterého je potřeba provést první přihlášení a aktivaci vašeho uživatelského účtu. Pokud jste žádný email neobdrželi, pravděpodobně nemáte účet v CAAIS IdP, ani profil v CAAIS. V takovém případě kontaktujte vašeho lokálního administrátora.

Přehled celého procesu:

.. figure:: ../images/CAAIS_BU.jpg
    :alt: CAAIS pro běžné uživatele
    :width: 1000px

Založení účtu
=============

O založení vašeho uživatelského účtu se již postaral `lokální administrátor <https://docs.caais.gov.cz/prirucka-wip/lokalni-administrator/index.html>`_. Abyste mohli CAAIS používat pro přihlašování do agendových informačních systémů, je potřeba účet ještě aktivovat. Nejedná se o nic složitého.

Kdo je lokálním administrátorem?
--------------------------------

Jak zjistím, kdo je můj `lokální administrátor <https://docs.caais.gov.cz/prirucka-wip/lokalni-administrator/index.html>`_? Po přihlášení najdete kontakt v patičce stránky ve sloupci lokální administrátoři po rozkliknutí textu KONTAKTNÍ ÚDAJE.

.. figure:: ../images/data-image-3.jpg
    :alt: Kdo je lokálním administrátorem?
    :width: 1000px

Jaké informace mu předat.

Byl vám založen nový účet v CAAIS IdP
=====================================

Jakmile vám lokální administrátor účet založí, budete o tom informováni prostřednictvím e-mailové zprávy. V této zprávě s předmětem „Byl vám založen nový účet v CAAIS IdP“ naleznete své uživatelské jméno spolu s odkazem na přihlašovací stránky, kde je nejprve nutné (1) nastavit heslo a následně (2) registrovat autentizační certifikát. Pokud jste připojeni v uzavřené síti CMS, můžete si alternativně (1) nastavit heslo v síti CMS a následně (2) registrovat autentizační certifikát v síti CMS. Nezapomeňte, že odkazy mají omezenou platnost.

.. admonition:: Poznámka
   :class: note
   
   Zpráva přijde na adresu, která byla do systému zadána během vaší registrace. Pokud víte, že vám byl účet zřízen, ale v doručené poště e-mail nevidíte, zkontrolujte složku „nevyžádaná pošta / spam“, případně kontaktujte lokálního administrátora.

CAAIS lze plnohodnotně využívat, i pokud se budete autentizovat pomocí Identity občana (NIA). Pak výše uvedené nastavení hesla a registraci certifikátu nemusíte provádět. Interní předpisy vašeho úřadu však přesto mohou vyžadovat, abyste si účet v CAAIS IdP zřídili.

.. admonition:: Poznámka
   :class: note

   Jestliže vám přišel pouze odkaz pro tzv. doztotožnění, znamená to, že již aktivní účet v CAAIS máte a tímto vám byl zřízen jen nový profil. Pro dokončení nastavení tohoto nového profilu proveďte prosím požadovanou akci (více se dozvíte v textu o samoztotožnění).

Aktivace účtu
-------------

1. Odkaz z e-mailu vás přesměruje na stránku „První přihlášení do CAAIS IdP“ a vyzve k vyplnění uživatelského jména. Jakmile jej vyplníte, klikněte na tlačítko POKRAČOVAT.

.. figure:: ../images/BU_CAAIS-IdP_Au-1.png
    :alt: První přihlášení do CAAIS IdP
    :width: 1000px

2. Pro ověření shody potvrďte volbu zaslání na e-mail, případně SMS (v případě, že systém zná vaše mobilní telefonní číslo) a na další stránce jednorázový kód přepište do příslušného pole.

.. figure:: ../images/BU_CAAIS-IdP_Au-2.png
    :alt: První přihlášení do CAAIS IdP
    :width: 1000px

3. Dalším krokem je vytvoření hesla. Systém vyžaduje heslo o minimálně 10 znacích a obsahující alespoň jedno velké písmeno. Pro kontrolu heslo zopakujte a klikněte na POKRAČOVAT.

.. figure:: ../images/BU_CAAIS-IdP_Au-3.png
    :alt: První přihlášení do CAAIS IdP
    :width: 1000px

4. Jestliže všechny kroky proběhly správně, objeví se v horní části stránky zelený proužek potvrzující úspěšné založení účtu v CAAIS. Pokračujte volbou K PŘIHLÁŠENÍ.

.. figure:: ../images/BU_CAAIS-IdP_Au-4.png
    :alt: První přihlášení do CAAIS IdP
    :width: 1000px

První nahrání certifikátu do CAAIS
----------------------------------

Systém CAAIS umožňuje všem uživatelům přístup do administračního prostředí, kde mohou spravovat své osobní údaje. Pro jejich úpravu je nutné se do systému přihlásit pod ověřenou identitou. Identita se ověřuje na základě osobního komerčního certifikátu nebo prostřednictvím přihlášení přes Identitu občana / Národní identitní autoritu (NIA).

.. attention::

   Pozor, následující kroky předpokládají, že máte v počítači nainstalovaný certifikát nebo disponujete účtem NIA ID.

Pro nahrání certifikátu je nutné se do systému CAAIS přihlásit pod svým účtem. Lze zvolit z následujících možností přihlášení:

- první přihlášení prostřednictvím CAAIS IdP,
- první přihlášení Identitou občana / NIA.

První přihlášení prostřednictvím CAAIS IdP
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Pokud zvolíte přihlášení prostřednictvím CAAIS IdP, certifikát nahrajete následujícím způsobem:

1. Pod přihlašovacím formulářem najděte text + CERTIFIKÁT. Klikněte na něj.

.. figure:: ../images/BU_CAAIS-IdP_PncdCAAIS-1.jpg
    :alt: První přihlášení do CAAIS IdP
    :width: 1000px

2. V dalším kroku vyplntě své uživatelské jméno a heslo a následně klikněte na NASTAVIT CERTIFIKÁT.

.. figure:: ../images/BU_CAAIS-IdP_PncdCAAIS-2.png
    :alt: První přihlášení do CAAIS IdP
    :width: 1000px

3. Systém vám pošle e-mail nebo SMS s ověřovacím kódem.

.. figure:: ../images/BU_CAAIS-IdP_PncdCAAIS-3.png
    :alt: První přihlášení do CAAIS IdP
    :width: 1000px

4. Na následující stránce zadejte obdržený kód do příslušného pole a klikněte na tlačítko NAHRÁT. V počítači vyskočí okno s nabídkou certifikátů, které v něm máte nainstalované. Vyberte správný certifikát a potvrďte.

Objeví se zelený proužek: „Certifikát jsme úspěšně nahráli do CAAIS. Teď se můžete přihlásit“.

.. figure:: ../images/BU_CAAIS-IdP_PncdCAAIS-5.png
    :alt: První přihlášení do CAAIS IdP
    :width: 1000px

Nyní se můžete do svého účtu v systému CAAIS přihlašovat prostřednictvím jména, hesla a certifikátu a zároveň používat účet CAAIS pro přihlašování do agendových informačních systémů vyžadující značnou mírou zabezpečení.

Certifikát za vás mohl do CAAIS nahrát i lokální administrátor. V takovém případě nebudete k nahrávání certifikátu vyzváni a přecházíte rovnou k přihlášení.

První přihlášení Identitou občana / NIA
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Jestliže se do účtu přihlásíte prostřednictvím Identity občana, CAAIS vás rozpozná na základě informací poskytnutých NIA. V takovém případě je možné nahrát certifikát přímo v administračním prostředí CAAIS skrze volbu „Správa certifikátů“.

Pro detailní návod přejděte prosím do článku „Správa vlastního účtu - Certifikáty“.

Nápovědu k NIA ID naleznete na stránce info.identitaobcana.cz/


Pokud se budete přihlašovat výhradně prostřednictvím NIA, nahrání certifikátu není nutné. V takovém případě ale přijdete o možnost používat CAAIS IdP, tedy přihlášení prostřednictvím jména, hesla a certifikátu.

Byl vám založen profil v CAAIS
==============================

Pokud lokální administrátor při zakládání vašeho účtu neměl k dispozici údaje nutné pro ověření vaší totožnosti, naleznete ve své e-mailové schránce zprávu s předmětem „Byl vám založen profil v CAAIS“, ale pouze s odkazem pro ztotožnění svého profilu v CAAIS. Pokud jste připojeni v uzavřené síti CMS, můžete místo toho alternativně ztotožnit svůj profil v CAAIS v síti CMS.

Po ztotožnění profilu se budete moci v CAAIS autentizovat prostřednictvím Identity občana (NIA) nebo si budete moci (1) nastavit heslo a následně (2) registrovat autentizační certifikát.

Aktivace účtu s nutností ověření totožnosti uživatelem
1

Po kliknutí na odkaz v e-mailu vás systém přesměruje na stránku „Jak se chcete ztotožnit“, kde si zvolíte způsob, kterým chcete svou totožnost ověřit. Máte na výběr z několika možností:


1. Identita občana / NIA

Totožnost ověříte prostřednictvím přihlášení se k Identitě občana. Systém CAAIS vás ověří na základě informací poskytnutých NIA.


2. Doklad totožnosti

Po zvolení této možnosti vás systém vyzve, abyste vybrali druh dokladu, který chcete pro ověření totožnosti použít a uvedli jeho číslo. Pokračujte kliknutím na tlačítko ZTOTOŽNIT.


3. Přihlášení prostřednictvím CAAIS

Lze využít v případě, kdy už jeden aktivní (tzv. přihlašovací) účet v CAAIS máte a disponujete i tzv. CAAIS IdP.

2

Po úspěšném ověření totožnosti pokračujte na stránku „První přihlášení”.


Jestliže se vám nedaří ověřit svou totožnost ani například prostřednictvím jiného dokladu, kontaktujte svého lokálního administrátora.

Nemám účet v CAAIS IdP, ani profil v CAAIS
==========================================

Nejste si jistí, zda máte v CAAIS účet? Zkuste využít možnost ZAPOMENUTÉ UŽIVATELSKÉ JMÉNO. Do políčka vyplňte svůj pracovní e-mail. Pokud účet v CAAIS máte, přijde vám v odpovědi vaše uživatelské jméno. Na jeho základě si můžete požádat i o nové heslo a po přihlášení již jméno lokálního administrátora zjistíte výše uvedeným způsobem.

.. figure:: ../images/data-image-4.jpg
    :alt: Zapomenuté uživatelské jméno CAAIS IdP
    :width: 500px
    :align: center

Jestliže se vám nepodařilo přihlásit a domníváte se, že účet v CAAIS nemáte, doporučujeme kontaktovat pracovníka, který vám nastavuje přístupy v JIP/KAAS, případně vydává komerční a kvalifikované certifikáty. Pokud se vám lokálního administrátora žádným uvedeným způsobem nepovede najít, kontaktujte technickou podporu: portal.szrcr.cz

Samoztotožnění
==============

E-mail. Odkaz Internet versus CMS.


Před prvním přihlášením
=======================

NIA
---

CAAIS IdP
---------

Nastavení hesla a certifikátu. Odkazy i zde.


Ověření, že vše funguje
=======================
