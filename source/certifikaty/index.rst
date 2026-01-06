=======================
Certifikáty v CAAIS IdP
=======================

Uživatelský certifikát představuje jednu z možností ověření identity při přihlašování do CAAIS. Certifikát musí být vydán podporovanou certifikační autoritou a dostupný webovému prohlížeči na zařízení, ze kterého se uživatel přihlašuje.

      Pro přihlášení do CAAIS prostřednictvím NIA nejsou uživatelské certifikáty nutné.
      Tato stránka je určena uživatelům, kteří se přihlašují pomocí autentizačního certifikátu.

Certifikáty podporované CAAIS
=============================

CAAIS podporuje uživatelské autentizační certifikáty vydané certifikačními autoritami uznávanými v rámci nařízení eIDAS. Certifikát může být uložen jako soubor (např. PKCS#12) nebo na fyzickém nosiči (USB token, čipová karta).

Typy certifikátů
----------------

Autentizační certifikát
    Slouží k ověření identity uživatele při přihlašování do informačních systémů. Tento typ certifikátu je pro přihlášení do CAAIS podporován.

Kvalifikovaný certifikát pro elektronický podpis
    Slouží výhradně k vytváření kvalifikovaných elektronických podpisů a nelze jej použít k autentizaci do CAAIS ani jiných systémů.

      Kvalifikovaný podpisový certifikát nelze použít k přihlášení do CAAIS.
      V některých případech je však spolu s ním vydáván i samostatný autentizační certifikát,
      který použít lze.

Podporované certifikační autority
---------------------------------

  Interní certifikační autority jednotlivých úřadů nejsou z důvodu zvolené bezpečnostní politiky podporovány.

Aktuálně CAAIS podporuje autentizační certifikáty vydané následujícími certifikačními autoritami:

`Národní certifikační autorita (NCA) <https://www.narodni-ca.cz/>`_
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Národní certifikační autorita je kvalifikovaný poskytovatel služeb vytvářejících důvěru, provozovaný Správou základních registrů (SZR). Vydávání certifikátů je upraveno nařízením EU eIDAS a zákonem č. 297/2016 Sb.

NCA vydává certifikáty především pro potřeby veřejné správy. Držitelem certifikátu může být fyzická osoba působící ve veřejné instituci zapojené do projektu NCA. Certifikáty jsou vydávány ve standardu X.509 v3.

Při využití certifikátů v CAAIS je nutné ověřit, že se jedná o autentizační certifikát. Kvalifikované certifikáty určené výhradně pro elektronický podpis nelze k přihlašování použít.

`eIdentity <https://www.eidentity.cz/>`_
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

eIdentity je komerční certifikační autorita poskytující kvalifikované i nekvalifikované certifikáty pro fyzické osoby. Proces pořízení certifikátu probíhá prostřednictvím zákaznického účtu na webu poskytovatele.

Žádost o certifikát se podává online a zahrnuje vyplnění osobních údajů, ověření identity a následnou návštěvu registračního místa (v závislosti na typu certifikátu). Vydaný certifikát je následně k dispozici v elektronické podobě.

Pro přihlášení do CAAIS je nutné zvolit autentizační certifikát. Kvalifikovaný certifikát pro elektronický podpis slouží pouze k podepisování dokumentů a nelze jej použít k autentizaci.

`I.CA <https://www.ica.cz/>`_
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

I.CA je zavedená certifikační autorita poskytující certifikáty pro elektronický podpis, šifrování i autentizaci. Žádost o certifikát lze podat online prostřednictvím průvodce na webu poskytovatele.

Součástí procesu je ověření identity žadatele, které může proběhnout online nebo osobně na registrační autoritě. Certifikát lze uložit do počítače, na čipovou kartu nebo jiný podporovaný nosič.

CAAIS podporuje autentizační certifikáty vydané I.CA. Při výběru certifikátu je nutné ověřit, že je určen pro přihlašování (autentizaci), nikoli pouze pro elektronický podpis.

`PostSignum <https://www.postsignum.cz/>`_
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

PostSignum je certifikační autorita provozovaná Českou poštou. Nabízí možnost získání certifikátu jak online, tak osobně na pobočkách České pošty (Czech POINT).

Certifikát lze získat vzdáleně například pomocí eObčanky s aktivovaným čipem nebo prostřednictvím účtu MojeID s vysokou úrovní ověření. Alternativně je možné absolvovat proces osobně na vybraných pobočkách České pošty.

Pro použití v CAAIS je nutné zvolit autentizační certifikát. Certifikáty určené výhradně pro elektronický podpis nejsou pro přihlášení do systému použitelné.

Jak certifikát získám
---------------------

Konkrétní postup získání certifikátu se liší podle zvolené certifikační autority. Obecně však proces zahrnuje následující kroky:

  Výběr certifikační autority.

  Podání žádosti o autentizační certifikát.

  Ověření totožnosti žadatele (online nebo osobně).

  Získání certifikátu ve formě souboru nebo na fyzickém nosiči.


Při žádosti vždy ověřte, že se jedná o autentizační certifikát, nikoli o certifikát určený výhradně pro elektronický podpis.

Jak přidám certifikáty do prohlížeče
====================================

Aby mohl být certifikát použit pro přihlášení do CAAIS, musí být nejprve dostupný webovému prohlížeči. Postup se liší podle operačního systému a typu prohlížeče.

Windows
-------

V operačním systému Windows využívají webové prohlížeče jednotné systémové úložiště certifikátů. Certifikát je nutné nejprve importovat do tohoto uložiště a ověřit, že je v prohlížeči dostupný.

Taby pro Chromium, Firefox a Edge


Linux
-----

V systému GNU/Linux je zpravidla nutné certifikát importovat přímo do konkrétního webového prohlížeče. Postup se může lišit v závislosti na použité distribuci a prohlížeči.

macOS
-----

V systému macOS se certifikáty spravují prostřednictvím systémové aplikace Klíčenka. Certifikát musí být uložen v příslušném úložišti, aby jej mohl prohlížeč použít.
