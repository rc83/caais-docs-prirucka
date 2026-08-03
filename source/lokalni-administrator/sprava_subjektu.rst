================================
Příručka lokálního administátora
================================

Správa subjektu
===============

Lokální administrátor může pro svůj subjekt ve vertikální záložce **Detail subjektu** a následně v horizontální záložce **Ostatní údaje** nastavit vlastní šablonu pokynů, která bude uživateli zobrazena a zaslána při využití `funkce „Zjisti mého lokálního administrátora CAAIS“ <https://caais.gov.cz/la-contact>`_. Současně zde může definovat také povolené e-mailové domény, které určují, z jakých e-mailových domén lze o zaslání těchto pokynů požádat.

**Pokyny k založení uživatelského účtu** jsou definovány jako textová šablona podporující formátování pomocí HTML. Lokální administrátor může vytvořit vlastní šablonu, která nahradí výchozí šablonu spravovanou národním administrátorem, nebo ponechat výchozí nastavení. Šablona podporuje použití zástupného symbolu `[[seznam_la]]`, který bude při odeslání e-mailu automaticky nahrazen seznamem lokálních administrátorů daného subjektu.

.. dropdown:: Při konfiguraci Povolených e-mailových domén je potřeba dodržet následující pravidla:

   1. **Zadejte alespoň jednu e-mailovou doménu** –
      Přidejte e-mailovou doménu, ze které budou uživatelé oprávněni požádat o zaslání pokynů. Další domény lze přidat pomocí tlačítka **+**, odebrání domény je možné pomocí ikony koše.

   2. **Lze použít pouze povolené domény** –
      Přidávat lze pouze takové domény, které nejsou vedeny na seznamu blokovaných e-mailových domén subjektu.

   3. **Pro více subdomén lze využít zástupný znak (wildcard)** –
      Pokud mají být stejné pokyny dostupné pro více subdomén, lze použít zástupný znak `*`. Například zápis `*.organizace.cz` umožní využití pokynů uživatelům s e-mailovými adresami na všech subdoménách organizace.

.. Níže je uvedena ukázka výchozí šablony spravované národním administrátorem, její HTML podoby v administraci CAAIS a výsledného e-mailu, který obdrží uživatel po využití funkce **Zjisti mého lokálního administrátora CAAIS**.