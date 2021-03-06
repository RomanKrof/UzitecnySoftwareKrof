# Save & Meet aplikace
## Verze 1

Roman Krof <br/>
krof.roman.2018@skola.ssps.cz <br/>
16. 5. 2021

* Úvod
  * Účel dokumentu
    * Dokument slouží k rychlému seznámení se systémem a jeho vlastnostmi
  * Konvence dokumentu
    * Důležitost - 1 nejvyšší, 3 nejnižší
    * Všechny kritické požadavky budou tučně
  * Kontakty
    * Roman Krof krof.roman.2018@skola.ssps.cz, tel. 999 888 777, Facebook: Roman Krof
* Celkový popis
  * Funkce
    * Funkce programu jsou prosté: snadná správa Vašich schůzek a konferencí skrze přidání nových a úpravu nebo odstranění stávajících pomocí tlačítek, lze si také vybrat mezi soukromými a pracovními schůzkami
  * Uživatelské skupiny
    * Uživatelé, kteří nejsou sběhlí v IT, například podnikatelé a sekretáři/ky
  * Omezení návrhu a implementace
    * Najednou může být uloženo pouze 20 schůzek
* Požadavky na rozhraní
  * Uživatelská rozhraní
    * **WPF**
  * Softwarová rozhraní
    * **Windows**
* Vlastnosti systému
  1. **Přidání položky**
    * Důležitost: 1
    * Vstup: název položky a dílčí informace: místo, čas a datum, kdo se zůčastní, důležitost schůzky, o čem se bude jednat, poznámka
    * Akce: přidání položky s informacemi do seznamu
    * Výstup: přidána nová položka do seznamu
  2. **Úprava položky**
    * Důležitost: 2
    * Vstup: přepsané informace dané položky
    * Akce: přepsání daných informací položky
    * Výstup: určená položka byla upravena
  3. **Odstranění položky**
    * Důležitost: 3
    * Vstup: odstranění určené položky
    * Akce: odstranění určené položky
    * Výstup: určená položka byla odstraněna
  4. **Uložení seznamu**
    * Důležitost: 1
    * Vstup: kliknutí na tlačítko uložit
    * Akce: list s položkami a informacemi se uloží na zařízení
    * Výstup: položky s informacemi se uloží
  5. **Výběr soukromých nebo pracovních schůzek**
    * Důležitost: 3
    * Vstup: kliknutí na záložku
    * Akce: přepnutí listu s položkami
    * Výstup: přepnutí listu s položkami
* Nefunkční požadavky
  * Odezva
    * Program bude přepisovat a přidávat informace do 2s
  * Spolehlivost
    * Program při správném použití ve více jak v 99% případů správně aktualizuje informace nebo přidá další informace
  * Bezpečnost
    * Program pracuje pouze s daty, která se zadají do programu
