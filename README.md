🟨2* ***Autohotkey v1.1 scripts***

🟩1* ***Useful software for Win7. 🟦 PORTABLE - official or with the help of 🟦 7-Zip***
<br/>
```What's new``` - PeaZip (Jun 2, 2024), AccessEnum (Jun 8, 2024), tableManager (Sep 1, 2024), SmartSteamEmu (Oct 15, 2024), FAT32 Format GUI (Nov 1, 2024), SCURLed (Nov 15, 2024), WinSetView (Dec 15, 2024), Gamma Panel (Apr 15, 2025)

***[📥 Win```7``` Epyc Bloatware List (services/tasks/processes/drivers/devices/installations) + 4th mouse button AHK + NirSoft apps for comparing system via TXT/HTML + some REG files](https://github.com/hornster02/hornster02/raw/main/win-bloatware.rar)***
<br/>
<img width="960" alt="win" src="https://github.com/user-attachments/assets/398697e5-a06a-4dd1-9d30-4d446a29f778" />

[***📥 android Epyc Bloatware List + 🟦 ADB AppControl presets***](https://github.com/hornster02/hornster02/raw/main/android.rar)
<br/>
```Question``` What is the purpose of this list?
<br/>
```Answer``` Bootloop free phone... I hope. Nothing less nothing more
<br/>
Remaining SYS Apps ```10``` ```16``` ```16``` (android ```4``` ```7``` ```9```)
<img width="720" alt="4+9" src="https://github.com/user-attachments/assets/6a59c170-fbd6-46d3-abf2-8a66e8118f92" />

***[↗️ Češtiny do her (2014 a starší)](https://github.com/hornster02?tab=repositories&q=&type=template&language=&sort=name)***. Nejsem a nebudu autor překladů. Naprostá většina češtin pochází z dávno neprodávaných fyzických nosičů (a české digitální obchody reálně nikdy neexistovaly) a jejich shánění je i v době ukončování "pirátských" úložišť pořád obtížnější. Některé hry se dají pořád koupit v bazarech, ale jejich ceny budou kvůli omezené nabídce a životnosti médií jen a jen absurdnější. A vytvářet/stahovat celé ISO soubory nedává pro běžného uživatele smysl = problémy s kompatibilitou a kvůli velikosti i s archivací/nahráváním/přenosem dat. Navíc instalátory po sobě často nechávají v lepším případě spoušť (instalací s hrou nesouvisejícím SW - ovladače/zápisy do registru/...) v horším - dokud nedojde k ručnímu smazání SYS ovladačů protipirátských ochran (starforce) - i "znefunkčnění" systému (bluescreen). A opravdu málokdo používá takové zabezpečení a SW, aby k ničemu takovému nedocházelo. Zahraničních abandonware archivů/repack/rip/portable existuje, a vždy bude, spousta... Neopravuji překlady pokud dojde k vydání patche/remasteru

***[📥 Ultimátní seznamy CZ+SK překladů včetně odkazů a dalších podrobností (2024-12). 10 000+ překladů z 33 serverů](https://github.com/hornster02/hornster02/raw/main/_cz+sk-seznam.rar)***
![cz+sk](https://github.com/user-attachments/assets/31c8472b-8d21-49a4-bdaf-a24b187d9b10)

Podle Googlu byl v 2025-01 na ***[komunitni-preklady.org](https://komunitni-preklady.org/ostatni-cestiny)***  uveřejněn nástupce mého seznamu překladů, který na CZ/SK scéně také nemá obdoby (ale nefunguje offline = omezená životnost). V 2025-03 obsahuje 3200+ překladů z ~15 serverů. Ochrany proti kopírování - ```1``` tabulka načte+zobrazí pouze část která je zrovna viditelná, ```2``` stahovací odkazy pod tlačítky v sloupci "Odkaz" jsou skryté (po kliknutí se spouští JS event, neznámé odkazy = bezpečnostní riziko) ```3``` na archive.org je pár záznamů serveru, ale nezobrazí se ani písmeno. Ochrana ```1``` se dá snadno obejít nastavením stylu stránky na "bez stylu" a následným uložením (dojde i k uložení stylů ale samozřejmě JS soubory pro filtrování budou nefunkční). Za ochranu ```2``` jeden VELKÝ 👎 . Překlady od ```Mrazíka``` se v roce 2025 přesunuly na tento server, bohužel spousta z nich je nefunkční (umělé překážky v podobě kontroly registru, případně dat i když zřejmě nedochází k patchování = např. původní Alice instalátor je 12,3x větší než portable verze bez podmínek) - nevím zda existuje univerzální extraktor, ale dotazované cesty se mohou vyčíst z ```Process Monitor```.
<br/>
Přepnutí jakékoli stránky na "bez stylu" obejde většinu nesmyslných překážek - i "tzv. behaviorální biometrii" u mBank zavedenou v 2024 kdy je pro platbu nutné přepisovat náhodné texty (funkce vložit je "zakázána") - ale psát=vložit se může i automaticky AHK skriptem (CTRL+SHIFT+V) ```^+v::SendRaw %clipboard%```. Citace banky "Dokážeme si totiž porovnat rychlost zadávání znaků na klávesnici s jinými transakcemi, které jste provedli v minulosti. Pokud nám to nebude sedět, platbu neprovedeme." Moje doporučení použití skriptu má přesnost ~1ms
![cz+sk-kp](https://github.com/user-attachments/assets/22885706-03e1-477b-9f64-91a15adf928c)

***Total Uninstall*** - sken systému (před/po spuštění/nainstalování aplikace) a zobrazení změn (soubory/složky/registr), export změn registru do REG souboru pro od/instalaci. Doporučuji odstranit výchozí vyjímky - velmi užitečné (záruka čistého systému, který není nutné desítky let přeinstalovávat) a zároveň destrukční pokud člověk neví co dělá

***🟦 Inno Setup XDELTA Patch Maker*** - ideální třeba pro vytvoření patche s češtinou do hry, ze které "nejde" překlad vytáhnout (chybějící nástroje a různě chráněná herní data nebo překlad ve spouštěcích souborech atd.) - velikost takového patche je běžně o 70-99% menší než celá "warez" verze hry (a sdílení takového patche je pochopitelně i daleko jednodušší a méně ošemetné = nesourodé útržky dat nejsou warez). Pokud překlad vyžaduje i svoje konkrétní DLL+EXE+... soubory a vytvářený patch bude zamýšlený pro digitálně prodávanou hru, tak je dobré tyto soubory z cíle (např. STEAM verze) dočasně odebrat (tím při patchování dojde k obyčejnému zkopírování zdrojových souborů do cíle bez ohledu na jejich verzi = výsledný patch může být kompatibilní i s jinými verzemi typu GOG,MYABANDONWARE,...) = tyto soubory mají běžně velikost maximálně pár desítek MB a jdou dobře komprimovat, takže "patch" způsob by celkově přinesl úsporu dat pouze v rámci jednotek MB, ale pokud by se v cílové verzi v budoucnu změnil jediný bit (a že je to u digitálních produktů daleko pravděpodobnější/jednodušší než že dojde k úpravě samotných velkých herních dat), tak bude celý patch nefunkční. Pokud hra obsahuje stejné typy souborů lišící se v názvu nebo pokud jsou uložená v jiných složkách, tak pokud se tyto věci ručně sjednotí, tak výsledná velikost patche bude menší = nedojde pouze ke komprimaci celých dat, ale ke komprimaci rozdílných částí dat. Vytvořený patch bych zkusil aplikovat a pak porovnal data podle obsahu třeba v Total Commander (původní CZ verze/updatovaná EN-CZ verze) kvůli případné HW/SW chybě a tím pádem změněným=poškozeným datům (ale i před vytvářením patche je nejjistější metoda dvou nezávislých instalací stejné verze hry a porovnání dat). Spuštěný ISXPM vypadá strašně složitě, ale ve skutečnosti může patch vytvořit i naprostý laik (jediná menší komplikace ve vyjímečných případech může být nutnost CZ aktivovat přes nějaký klíč v registru nebo souborem mimo herní data) který si vystačí klidně i jen s řádky "Old version" a "Final version" - výše napsaná doporučení nejsou až tak důležitá, pokud člověk nelpí na univerzálnosti a co nejmenší velikosti patche
<br/>
***[📥 Přednastavený konfigurační soubor](https://github.com/hornster02/hornster02/raw/main/_ISXPM-2.6.4.3-CONFIG-2024-03.rar)*** (stačí ho jen načíst přes "LOAD PROJECT") zaměřený na ještě menší velikost patche (rozdíl může být až v desítkách %). Využití RAM paměti bude běžně mezi 10-20GB (nezáleží na počtu souborů, ale čím větší je soubor tím vyšší bude spotřeba RAM = 1GB soubor na obou stranách=cca 6GB RAM) - v případě nároků na RAM převyšující možnosti systému se může proces zpomalit a zároveň zachovat vysokou kompresi snížením počtu "Generating cores". "Compression" v sekci "Patch Options" je vypnutá - komprimuje nezpracované ne-XDELTA soubory (ISXPM v tomto ohledu zřejmě nepodporuje větší možnosti nastavení a ani ta nejvyšší "lzma2/ultra64" není dostatečně dobrá = vyšší komprese se dosáhne zabalením celého patche přes 7-Zip)

V roce 2024 vznikla jakási česká alternativa ISXPM [```🟦 CZMaker```](https://lokalizace.net/aplikace-ke-stazeni) (navzdory nepodpoře funguje i ve Win7). Provedl jsem malý benchmark s [```těmito```](https://get.videolan.org/vlc/2.2.0/win32/vlc-2.2.0-win32.exe) [```soubory```](https://get.videolan.org/vlc/3.0.18/win32/vlc-3.0.18-win32.exe). EXE soubory byly přes 7-Zip rozbaleny a všechna data kromě rozdílných byla smazána = zaměřil jsem se čistě na patch+kompresní funkcionalitu (je úplný nesmysl 😉 místo "zazipování" dat která se pouze kopírují vytvářet EXE instalátor s češtinou - z hlediska bezpečnosti/univerzálnosti/velikosti/...). Výsledný patch byl oproti ISXPM o 24% větší (při druhém pokusu u EN/CZ verzí "Data1.fbz" hry Shadowgrounds byl nárůst 75%, třetí pokus by byl zbytečný). Nepovažuji za šťastné rozhodnutí nutnost přejmenování přípon souborů a nasypání všech dat dohromady = ani prase se v tom nevyzná a data nejde mezi sebou porovnávat či je normálně používat... A také se zdá, že CZMaker neumí vytvořit instalátor (v případě ISXPM se jedná o 1MB dat). Je možné, že je to kvůli vnucení další "naprosto nezbytné" aplikace ```CZ Manager```? (který narozdíl od ISXPM vyžaduje i ```.NET Desktop Runtime 8``` a ```přístup k internetu``` - umožnění offline instalace češtin je prý zvrácená myšlenka... Zřejmě se jedná o jakousi formu DRM pro překlady - i když samozřejmě že všechny jdou ripnout do více future-proof a komprimovanějšího offline formátu). A ano, ISXPM umí bájnou metodu patch/insert. A ne, ani samotné stažené soubory by vám nebyly k ničemu, protože aplikace patche je možná i ručně přes CMD bez ISXPM - pro [***🟦 HDiffPatch***](https://github.com/sisong/HDiffPatch) se může použít příkaz ```hdiffz-x64.exe -f --patch "a:\Stary\0.txt" "a:\Patch\0.txt.xdelta" "a:\Novy\0.txt"```. Proces je možné částečně automatizovat. ```1``` TotalCmd - vygenerovat seznam "Patch" souborů včetně cest do TXT + někam zkopírovat "Patch" data bez souborů čímž se vytvoří podsložky které poslouží jako cíl "Novy". ```2``` Notepad++ - vytvořit (ze seznamu "Patch" souborů) "Stary" "Novy" cesty (najít/nahradit +regulární výrazy pro přidání uvozovek). ```3``` ***🟦 LibreOffice Calc*** - výsledný polotovar se stejným počtem řádků a o 4 částech (EXE,Stary,Patch,Novy) dát vedle sebe do sloupců a pak vykopírovat zpět do TXT/BAT (pozor před uvozovkami - sloupci - má být pouze klasická mezera).
<br/>
[```[2/3] CZMaker (Jak dělat balíčky pro manager)```](https://youtu.be/fBQSt8eEe2Y) (Pozor! Obsahuje dezinformace)

<img width="941" alt="Inno Setup XDELTA Patch Maker" src="https://github.com/hornster02/hornster02/assets/127822397/91d7745e-6dd3-4c06-a382-794fbe422488">
<br/>
<img width="349" alt="czmaker" src="https://github.com/hornster02/hornster02/assets/127822397/9c3e97e2-88fd-45c1-a04f-8d9ac375eeba">

***Universal Extractor, Dragon UnPACKer, Game Extractor, https://aluigi.altervista.org/quickbms.htm https://oezmen.eu/gameresources/ https://www.gildor.org/***
<br/>
<br/>
<br/>

***🟦 ISO Directory v0.5***(Michel) - vytvoření mini-image CD/DVD (velikost pár kB) - pokud pro českou verzi hry neexistuje crack a hra trvá na vloženém fyzickém médiu v mechanice

***🟦 BikMod v0.3e (Beta) + 🟦 bink2-libass*** - modifikovaná "binkw32.dll" knihovna, pomocí které se mohou načíst externí SRT titulky. ***🟦 RADTools*** - úprava BIK/SMK video souborů

***MSI Afterburner+RTSS*** - překrytí obrazu - čas, HW monitoring, limit FPS/Frametime (klávesové zkratky), Scanline Sync, tray ikony. Omezením FPS se v některých hrách značně prodlouží nahrávací časy (Painkiller/...)

***🟦 dgVoodoo2*** - DX11/12 rendering (wrapper) pro DX1-9 hry, možnost zvětšení rozhraní her při vysokých rozlišeních (rozlišení ve hře je 1280x720 a přes dgVoodoo2 se nastaví 1920x1080 = rozhraní bude velké jako v 720p, ale rozlišení bude 1080p) a vnutit hře nepodporovaná rozlišení, obnovovací frekvenci, limit FPS, AF filtrování textur... Pravý klik myší zpřístupní pokročilé možnosti. Pro zapnutí wrapperu se musí potřebné DLL soubory z podsložky dgVoodoo2 nakopírovat k (hlavnímu) EXE souboru hry a pak nakonfigurovat (dgVoodooCpl.exe) čímž se u EXE souboru hry vytvoří "dgVoodoo.conf". Příklad pro zachování ostrého (ne pixelovatého a ne rozmazaného přes AA) obrazu ve hrách s fixním/omezeným rozlišením - ```General``` Scaling mode (Stretched, keep Aspect Ratio), ```DirectX``` Resolution (2x), ```GeneralExt``` Resampling (Bilinear), ale vzhledem k tomu, že i bez dgV má většina her rozmazaný obraz i v nativním rozlišení - Bilinear - , tak se může hodit vynucení Lanczos-3

***🟦 4GB Patch*** - prolomení 2GB RAM limitu u 32-bit aplikací. Užitečné třeba u některých her kdy se úpravou EXE souboru zvýší minimální FPS, o něco se zrychlí nahrávací časy a také při delším hraní nebude hrozit pád aplikace

***ArgusMonitor, Speedfan*** - regulace otáček ventilátorů CPU+GPU+skříně a jejich křivky+vypínání

***🟦 ClickMonitorDDC*** - změna jasu/kontrastu/hlasitosti/zapnutí/vypnutí ```monitoru```, tray ikony; profily - klávesové zkratky. Funguje i ve hrách

***🟦 Gamma Panel*** - ```softwarová``` změna jasu/kontrastu/gammy - profily - klávesové zkratky. Funguje i ve hrách (bezproblémový windowed/borderless, ale ve fullscreen některé hry změny neumožňují - ale třeba v ```dgVoodoo2``` se tyto změny mohou vynutit - Output API / Inherit Color Profile...). Problémy s AHK - klávesu ALT poslanou (fyzicky nestisknutou) přes AHK Gamma Panel neakceptuje = při nepoužívání přepínačů (více funkcí na jedné klávese) to nemusí být problém protože Gamma Panel zkratky zřejmě bez omezení podporuje. Druhý problém je "nemožnost" spustit Gamma Panel (EXE,LNK) přes AHK protože nebude načten "gapa.ini" (obejde se to spuštěním přes BAT - první řádek ```cd /d c:\```, cmd.exe nechat automaticky zavřít). ***[📥 PowerStrip](https://github.com/hornster02/hornster02/raw/main/_PowerStrip_3.9-key.rar)*** https://entechtaiwan.com/util/ps.shtm

***🟦 Custom Resolution Utility*** - vytvoření vlastního rozlišení a obnovovací frekvence monitoru. Ideální také pro obejití limitu maximálního rozlišení u starých GPU snížením obnovovací frekvence - 2560x1080x54Hz na Radeon HD 4670 (2008 - 1920x1200x60Hz). Nebo pokud Win při změně rozlišení nastavuje nižší Hz než monitor podporuje, tak pokud se v CRU u nativního rozlišení nastaví maximální podporovaná obnovovací frekvence, tak by i nižší rozlišení měly být automaticky nastavovány s maximální obnovovací frekvencí (zapnutý ```GPU Scaling``` v Radeon Bloatware💩 může funkčnost narušit). Další možnost vynucení vlastní obnovovací frekvence v DirectX aplikacích je v ```HKLM\SOFTWARE\Wow6432Node\Microsoft\DirectDraw``` a ```HKLM\SOFTWARE\Microsoft\DirectDraw``` vytvořit DWORLD hodnotu ```ForceRefreshRate``` a napsat konkrétní číslo v Hz (restart není nutný, změny se aktivují ihned). Zaplnění všech "Detailed resolutions" slotů může vypnout Freesync v Radeon Bloatware💩

***🟦 RefreshLock*** - asi nejuniverzálnější způsob vynucení nejvyšší podporované obnovovací frekvence monitoru. Funguje i v DirectX/Vulkan/OpenGL

***🟦 OverdriveNTool, 🟦 AMD GPU Clock Tool*** - napětí/frekvence pro Radeon - profily - klávesové zkratky/zástupce

***🟦 AmdMsrTweaker, 🟦 ZenStates, 🟦 PhenomMsrTweaker, 🟦 BrazosTweaker*** - AMD K8 (2003) až Zen 4 CPU - napětí/frekvence/násobič - profily - klávesové zkratky/zástupce

ATI/AMD GPU Bios - ***🟦 GPU-Z, 🟦 RBE - Radeon BIOS Editor, 🟦 VBE7, 🟦 Polaris Bios Editor PBE + 🟦 AMDVBFlash / ATI ATIFlash + 🟦 AMD/ATI Pixel Clock Patcher*** - podepsání Radeon ovladačů po úpravě biosu GPU  (přejmenovat na "atikmdag-patcher-bios.exe")

***🟦 RadeonMod,ATI Tray Tools*** (legacy) - náhrada za ATI/AMD Catalyst / Radeon Bloatware💩

Přepínání ***Schéma napájení*** (ovládací panely) přes klávesové zkratky/zástupce. Cesta v registru ```HKLM\SYSTEM\ControlSet001\Control\Power\User\PowerSchemes``` příkaz ve formátu
<br/>
```C:\Windows\System32\powercfg.exe -setactive XXX``` místo XXX se napíše název potřebného klíče

***Equalizer APO+Peace*** - ekvalizér zvuku - přepsáním konfiguračních souborů (i přes klávesové zkratky/zástupce) je možné v reálném čase přepínat profily bez spouštění programu

***🟦 Raw Accel*** - detailní nastavení myši, různá citlivost os atd. Profily jde přepínat i přes klávesové zkratky/zástupce ```c:\RawAccel\writer.exe c:\RawAccel\settings.json``` - změna kurzoru při přepnutí se dá zakázat jejich sjednocením v ovládacích panelech (normální výběr/práce na pozadí)

***🟦 hidusbf*** - úprava taktů myši (polling rate - Hz, vyšší takt = vyšší plynulost kurzoru). Ideální pokud stará hra funguje jenom na některých myších. Pokud se nedaří přes "Setup.exe" nainstalovat ovladač (Install Service) a v kontextové nabídce u INF souboru není možnost instalace, tak další způsob instalace je příkaz ```RUNDLL32.EXE SETUPAPI.DLL,InstallHinfSection DefaultInstall 132 c:\hidusbf\hidusbf\DRIVER\HIDUSBF.INF```

***🟦 DIMR (Direct Input Mouse Rate)*** - ukazatel taktů myši

***🟦 Mouse Settings Changer*** - přepínání citlivosti myši/touchpadu (ovládací panely) třeba i klávesovou zkratkou - pro skrytí vyskakovacího okna při přepnutí profilu se může použít AHK - AltGr+F7
<br/>
```VKA5 & F7::Run, C:\MouseSC_x64.exe /Speed:6, , Hide```

***🟦 XInput Plus*** - detailní nastavení gamepadu

***Comfort On-Screen Keyboard Pro*** - SW klávesnice

***🟦 NirCmd+🟦 DevManView*** - změna rozlišení+frekvence, zapínání/vypínání HW+SW zařízení, ... - ovládání i přes klávesové zkratky/zástupce

***🟦 IObit Unlocker*** - odemknutí (NTFS zabezpečení nebo běžící proces) souborů/složek

```🚫update``` ***EXE Radar Pro v3 (Beta)*** - při spuštění spustitelného souboru (exe/msi/bat/...) se zobrazí okno s dotazem zda ho spustit nebo ukončit (uživatelem definovaný Command-Line/whitelist/blacklist probíhá automaticky v pozadí systému). Ověření přes kontrolní součet. Doporučuji odstranit výchozí vyjímky (systémové/MS/... soubory)

🚫***Easy File Locker*** - zakázání čtení/zápisu/mazání/ skrytí souborů/složek. Zamknutí funguje jen když je spuštěný Windows+SYS ovladač EFL (dá se zapínat/vypínat přes zástupce/klávesové zkratky bez nutnosti spouštět EFL - NirCmd). Pokud nějaký program obchází ochranu, tak za to můžou NTFS linky (nezamknuté všechny cesty)

🚫Vytvoření souboru místo složky, mazání klidně i systémových EXE/... souborů - tyto klasické metody nikdy nezklamou

🚫***Firewall***  - Outpost/TinyWall/Firewall App Blocker. Výchozí Win firewall má pravidla uložená zde
<br/>
```HKLM\SYSTEM\ControlSet\services\SharedAccess\Parameters\FirewallPolicy\FirewallRules```
<br/>
```HKLM\SYSTEM\ControlSet001\services\SharedAccess\Parameters\FirewallPolicy\FirewallRules```
<br/>
```HKLM\SYSTEM\ControlSet002\services\SharedAccess\Parameters\FirewallPolicy\FirewallRules```
<br/>
a zákaz svévolného přidávání vyjímek se snadno provede přidáním a úpravou oprávnění pro "Everyone" 

🚫***🟦 Autoruns*** - automaticky spouštěné aplikace/knihovny/ovladače

🚫***🟦 NSudo*** - spouštění aplikací s nejvyššími právy. V kombinaci i s Autoruns je snadné se zbavit veškerého MS bloatwaru (aktualizace/služby/plánovače úloh/Defender/Edge/OneDrive/Slutana/StartMenu/...)

❶***🟦 BootICE*** - vytvoření bootovacího média bez formátování a ztráty dat (MBR/PBR pro HDD/SSD/USB), úprava Windows souborů BCD/UEFI (multiboot, změna systémové partition, ...), skrytí/aktivace partition

❷***🟦 Gandalf’s Windows*** (Win7-11) - spustitelný (bez formátování a ztráty dat⬆️) z USB (i z telefonu - pokud podporuje boot z "biosu") s možností internetu, instalování programů/ovladačů. Víceméně plnohodnotný systém - po restartu se ale vrací do výchozího nastavení

❸***🟦 WinNTSetup*** - instalace/záloha/obnovení Windows bez formátování a ztráty dat a vytváření bootovacího instalačního média (přeskočení věčně chybového/nebezpečného MS instalačního procesu = po nakopírování dat a restartu PC se spouští systém). Iso/wim/swm/vhd (dají se používat i v 7-Zip)+možnost přidání ovladačů/tweaků. Proces není závislý na konkrétní HW, takže třeba obnovení zálohy systému jde provést na jakékoli PC. Jde instalovat i na USB disky a minimálně Win11 z nich jde bez dalších úprav spustit (potřebné ovladače se načítají při bootu, takže nezáleží na jakém PC se bude spouštět) - jeho nesmyslné požadavky jsou ignorovány (UEFI/TPM/...) "Boot drive+Installation drive" může být stejný oddíl jednoho disku (WinNTSetup je pro běžného uživatele přednastavený - stačí vybrat edici Windows, kliknout na "Setup+OK" a proces začíná - na konci se automaticky vytvoří Bios+UEFI boot a poté v případě MBR disku doporučuji zkontrolovat zda je zelená tečka u BOOT PART). Záloha se provádí přes "Local Windows Installations/Capture Wim" - vyjímky se mohou přidat do "WimScript.ini". Možné řešení chyb
<br/>
-vložené ISO hlásí "No Windows Source Detected" nebo "Windows Source invalid" (rozbalit ISO a vložit instalační soubor - měl by se jmenovat "install" a být ve složce "sources" - zbývající obsah ISO je pro instalaci zbytečný a stejně nebude použit)
<br/>
-test (7-Zip) nově vytvořené zálohy najde chyby (HDD - poškozené sektory), (CPU+RAM - vypnout kompresi při vytváření zálohy)
<br/>
-obnova systému se může provést i rozbalením na disk (7-Zip) a nakonec případně opravit boot (BootICE)

Záloha systému se ale může provést i přes WinRAR (jsou to data jako každá jiná, jen ⚠️pozor na NTFS zabezpečení a linky), výhody jsou
<br/>
-nezávislost na obskurních zálohovacích softwarech, univerzálnost
<br/>
-okamžitý přístup k datům, možnost obnovit třeba jen 1 soubor
<br/>
-malý balíček dat díky vysoké kompresi (v mém případě je poměr 21% = 30,8GB systém / 6,5GB záloha)
<br/>
⓿🚫***🟦 NTFS Permissions Tools + 🟦 AccessEnum*** - správa zabezpečení dat, záložky pro rychlý přístup

***USB boot*** - BootDriverFlags, 0x14 ```HKLM\SYSTEM\HardwareConfig\XXX``` - změna pořadí načítaných ovladačů při bootu Win10+ = jeden systém se všemi programy+nastavením, který jde spustit na "jakémkoli" PC přes interní i externí disk (chybějící USB ovladače nebo IDE/AHCI mód atd. můžou být problém i když ne neřešitelný)

***Změna písmen disků přes registr*** ```HKLM\SYSTEM\MountedDevices```

***🟦 GImageX*** - tvorba WIM image (Windows v jednom komprimovaném souboru - bootovací nebo pro kompletní zálohu systému). Capture/Apply/Mount

***Link Shell Extension+🟦 NTFSLinksView*** - NTFS linky a přesměrování nastavení programů do vlastních složek. Ovládání přes kontextovou nabídku - vybrat zdroj (nové umístění) / vložit jako (původní umístění)

***🟦 Driver Booster for Steam*** - aktualizace ovladačů

***🟦 Display Driver Uninstaller*** - odinstalování audio/video ovladačů, ***Device Remover*** - možné zásadní zrychlení spuštění "Správce zařízení" (záleží kolika PC/komponenty systém prošel)

***🟦 7+ Taskbar Tweaker+WinaeroTweaker+ExplorerPatcher+🟦 WinPaletter+🟦 Classic Color Panel*** - úprava uživatelského rozhraní Windows

***🟦 Pazera Free Audio Extractor, 🟦 MKVToolNix*** - úprava videosouborů bez nutnosti konverze.  Odstraňování/extrahování audiostop, podrobné informace o audio/video souborech, ...

***🟦 Subtitle Edit*** - úprava titulků

***🟦 Video-subtitle-extractor (VSE)*** - OCR metoda automatického vytvoření titulků

***🟦 UniFlash*** (MS-DOS, Rainbow Software) - uložení/obnovení CMOS paměti biosu (nastavení) do souboru. Na novějším HW možná už nefunkční (AM3+ +)

***🟦 NetSpeedMonitor*** - monitoring rychlosti a objemu stažených dat+historie, tray

***🟦 AIDA64*** - podrobné informace o PC

***🟦 Prime95+Furmark*** - test životnosti+stability PC (power virus)

***🟦 WinRAR*** - archivace dat. Výhody oproti 7-Zip
<br/>
-záznam na opravu dat = poškozené archívy není nutné vícekrát stahovat či se smířit se ztrátou dat. Bez této základní funkce jsou všechny ostatní archivátory nepoužitelné

-profily s různým nastavením. Automatizace (vybráním profilu se může okamžitě automaticky vytvořit třeba zašifrovaný archiv s aktuálním datem a konkrétními daty na předem určené místo)

-nastavení ve složce programu = může plnohodnotně fungovat jako portable ```WinRAR.ini``` Global\AppData=0
<br/>
-velikost souborů v hlavním okně se nezobrazuje v nepřehledných/matoucích bytech
<br/>
-v hlavním okně je možné řadit data podle typu 😮
<br/>
-lepší "solid" komprese (násobně rychlejší a přesto může být výsledná velikost archivu klidně i o 50+% menší)
<br/>
-možnost vyloučit určité soubory/složky při vytváření archivů
<br/>
-možnost nekomprimovat určité soubory a tím urychlit proces

-je možné, že 7z nepodporuje NTFS souborový systém a neumí archivovat komplexnější data obsahující různá zabezpečení a symbolické odkazy? Jak docílit archivace odkazu a ne dat na která se odkazuje a tím mimo jiné nerozbít datovou strukturu?

-co tedy zbývá 7-Zip? Celkově lepší komprese (ale horší než ***🟦 PeaZip***) a hlavně DALEKO širší podpora formátů (často jenom read-only, což ale není vůbec málo). Být zdarma (to ale může být WinRAR také a případná vyskakovací okna se mohou automaticky zavírat pomocí skriptu) je v této podobě asi nutnost...

***🟦 WizTree*** - analýza místa na disku

***ImDisk Toolkit*** - ramdisk

***Primo Ramdisk*** - možnost stránkovacího souboru v ramdisku nebo využít nepřístupnou část RAM paměti (Invisible Memory) - 32-Bit Win má limit ~4GB, Win11 Home 128GB (stejný limit jako u WinXP)

***🟦 Mem Reduct*** - uvolnění RAM paměti bez ukončení procesů klávesovou zkratkou nebo klikem na tray ikonu. Může ale docházet k většímu zápisu do stránkovacího souboru = opotřebení SSD*1

***RimhillEx*** - omezení rychlosti čtení CD/DVD

***🟦 PortableWinCDEmu*** - virtuální mechanika

***🟦 FAT32 Format GUI*** - prolomení 32GB limitu při formátování

***🟦 Hard Disk Sentinel*** - monitoring disků+historie, S.M.A.R.T. testy, regulace hlučnosti (AAM), tray ikony (zdraví), možnost zakázání vypínání HDD při nečinnosti (aut. přístupem nebo APM)

***HDD Regenerator*** - oprava poškozených sektorů na HDD bez ztráty dat (Win/MS-DOS)

***🟦 Total Commander*** - rychlá/efektivní náhrada Průzkumníka/Plochy/NabídkyStart se spoustou funkcí navíc (vnitřní přidružení souborů včetně ikon, porovnání souborů podle obsahu, změna atributů, kopírování cest k datům do schránky, zobrazit/skrýt určité soubory/složky, kopírování souborů jenom s určitým datem se zachováním adresářové struktury, ověření nakopírovaných dat kvůli jejich případnému poškození, ... = nižší stovky klávesových zkratek). Pár užitečných "wincmd.ini" tweaků (první 2 jsou velmi důležité a moc nechápu, že TotalCMD tak není nastaven v základu - první zrychlí/zpřehlední vyhledávání dat tím, že ignoruje NTFS linky = vyhledává data jak jsou zapsaná na disku a neukazuje "falešné duplikáty". Druhý kopíruje/přesunuje NTFS linky jako linky a ne jako složky - bohužel to [```nefunguje u souborů```](https://www.ghisler.ch/board/viewtopic.php?t=40835) u kterých je pro manipulaci nutné použít třeba WinRAR
<br/>
```IgnoreLinks=8```
```CopyLinks=1```
```DriveBarHide=DC```
```RestrictInterface=3```
```EditWaitTime=-1```
```UseIniInProgramDir=1```
```pluginbasedir=%COMMANDER_PATH%\plugins```
```AlwaysCopyInBackground=1```
<br/>
S doplňkem ***DiskDir Extended***  se dá vytvářet katalog dat (funkce komprimovat - LST soubor se prochází jako archiv a dá se v něm vyhledávat)
<br/>
-hromadné přejmenování - odstranění znaků (počet) od začátku ```[N2-]``` od konce ```[N1--2]```
<br/>
-hromadné odstranění diakritiky (najít/nahradit)
<br/>
```á|č|ď|é|ě|í|ň|ó|ř|š|ť|ú|ů|ý|ž|Á|Č|Ď|É|Ě|Í|Ň|Ó|Ř|Š|Ť|Ú|Ů|Ý|Ž```
<br/>
```a|c|d|e|e|i|n|o|r|s|t|u|u|y|z|A|C|D|E|E|I|N|O|R|S|T|U|U|Y|Z```
<br/>
-najít CSS soubor který má někde v názvu TAB - ```*tab*.css```

***System Explorer*** - náhrada "Správce úloh" - možnost uložit prioritu/afinitu aplikací pro jejich automatické nastavení při dalším spuštění. ***🟦 Process Hacker*** 

***🟦 Battle Encoder Shirasé*** - omezení (throttling) procesů - až 99%. Možnost používat přes Command-Line bez UI - příklad 90% a 10% omezení pro 2 EXE soubory = BES v pozadí systému bude hledat spuštěné procesy a automaticky je omezí
<br/>
```c:\BES\BES.exe -J "C:\FileActivityWatch\FileActivityWatch.exe" 90 -m "c:\Deus Ex\System\DeusEx.exe" 10 -m```

***🟦 Registry Workshop*** - pokročilá náhrada výchozího "Regedit". Load Hive slouží pro načtení externího registru - je možné ho upravovat. Integrace s Total Uninstall se v jeho nastavení provede příkazem - ```"c:\Registry Workshop\RegWorkshopX64.exe" /g```

***🟦 Notepad++*** - hromadné označení vybraných řádků záložkami a jejich odstranění/zachování, hromadné odstranění řádků obsahující prázdné/žádné znaky, výběr bloku textu ```ALT+levé tlačítko```, ... Regulární výrazy -
<br/>
-odstranit všechny znaky na řádcích pokud jich je 4 a méně ```^.{0,4}$```
<br/>
-odstranit první 4 znaky na řádcích ```^.{4}(.*)$``` ```$1```
<br/>
-odstranit 4 a 4 a vše mezi tím ```4.*?4```
<br/>
-najít 4 a vložit prázdný řádek ```(?-s)4.*``` ```$0\r\n```
<br/>
-vložit 4 na prázdný řádek ```^$``` ```4```
<br/>
-vložit 4 na začátek řádku ```^``` ```4```
<br/>
-vložit 4 na konec řádku ```$``` ```4```

***🟦 HEXelon Max 6*** - kalkulačka se třemi nezávislými "panely"

***🟦 FastStone Image Viewer*** - jednoduchý/rychlý prohlížeč obrázků

***🟦 SumatraPDF*** - rychlý prohlížeč PDF. Možnost skrytí veškerého UI

***🟦 Screen Ruler*** (Bluegrams) - pravítko

***🟦 NAPS2*** - skenování, export do PDF, OCR

***🟦 Ultimate Icon Converter*** - tvorba ikon

***🟦 ATI GPU Scaling Fix***(legacy), ***🟦 HDD Low Level Format Tool*** a desítky aplikací od 🟦 NirSoft (***OpenedFilesView/AppReadWriteCounter/ProcessActivityView/FileAccessErrorView/LiveTcpUdpWatch/CurrPorts/AdvancedRun/AppAudioConfig/DriveLetterView/FileTypesMan/GUIPropView/InstalledCodec/InstalledPackagesView/KeyboardStateView/AppCrashView/BlueScreenView/ShellExView/ShellMenuView/OpenWithView/SpecialFoldersView/EventLogSourcesView/FullEventLogView/MyEventViewer/ EventLogChannelsView*** ⚠️ nevinné pozapínání ve výchozím stavu vypnutých kanálů může zásadně nabořit systém znefunkčněním minimálně služeb eventlog+schedule = největší problém je, že bez nich nefunguje EventLogChannelsView a není možné přes něj kanály zase povypínat = opravit takový systém bez následků a použití Total Uninstall zvládnou jen opravdoví mistři)

***VMware Workstation*** (15) - možnost používat např. Steam klient při spuštěném Win7 (od roku 2024 hrozí obecně umělý zákaz přístupu z tohoto "nebezpečného" systému - viz některé banky, možné řešení=responzivní mód v prohlížeči) ve virtuálním stroji s novějším systémem (třeba Win11). Podpora připojení (přemostění) k internetu (router může vyřešit případné problémy s připojením) a možnost sdílení složek - host/guest (např. pro přímé stahování her z Win11 do Win7). Pro plnou funkčnost je třeba po instalaci systému (běžné ISO) v VMware připojit na virtuální mechaniku ISO s ovladači (VMware Tools) a nainstalovat je. 7-Zip umí otevřít VMDK soubor se systémem

***🟦 Process Monitor+🟦 FileActivityWatch*** - aktivity spuštěných procesů - detailní seznam přístupů na SSD/registru/sítě

***KernelEX/One-Core-API/Extended Kernel for Windows Vista/VxKex*** - možnost spustit novější aplikace v nepodporovaném systému (compatibility layer). Třeba Firefox 2025 ve WinXP 2001 

***🟦 HxD+CFF Explorer+🟦 Resource Hacker*** - úpravy spustitelných souborů a jiné

***GodMode.{ED7BA470-8E54-465E-825C-99712043E01C}*** - vytvoření složky s tímto názvem a její otevření přes Průzkumník otevře okno s veškerými ovládacími panely

***Microsoft Management Console*** (MMC) - přidání vlastních modulů do jedné MMC konzole. Postup - spustit/mmc/přidat nebo odebrat moduly snap-in/vybrat moduly/uložit

```c:\Windows\System32\Robocopy.exe "c:\1" "e:\1" /E /PURGE /w:0 /r:0 /MOT:10```
<br/>
Automatická synchronizace dvou složek. ```c:\1``` je zdrojová složka a ```e:\1``` je záloha. Pokud dojde ve zdrojové složce k vytvoření/změně souboru/složky, tak se nakopíruje do zálohy. Pokud dojde ve zdrojové složce ke smazání souboru/složky, tak se smaže ze zálohy. "MOT:10" označuje 10 minut čekání a poté následuje synchronizace. Jedná se o synchronizaci (porovnání) a ne "smazat celou zálohu/nakopírovat celý zdroj", takže mimo jiné nesnižuje životnost SSD zbytečnými zápisy. Malá nevýhoda je, že nedochází k porovnání souborů podle obsahu, ale pouze pomocí atributů+velikostí (rychlé/nenáročné). Je možné zavřít okno konzole ukončením procesu "conhost.exe" a nechat zapnutý pouze "ROBOCOPY.exe" (automatická synchronizace v pozadí systému). Užitečné v kombinaci s NTFS linky pro automatické zálohování SAVEGAME

***🟦 T-Clock*** - pokročilá náhrada výchozích tray hodin. Program s desítky let dlouhou historií a několika autory = možnosti nastavení a rozsah funkcí (které ani s hodinami nesouvisí) je nebývalý

***🟦 Desktop VLocker*** - uzamčení systému

***[🟦 tableManager](https://github.com/pietrantonio91/tablemanager)*** - HTML tabulky, možnost řazení a filtrování ve vybraných sloupcích

***🟦 SmartSteamEmu*** - nenáročná alternativa Steam klienta bez nutnosti aktualizací (Game Booster). V mém případě se jedná o 1 vs. 60+ vteřin pro start a 40MB vs. 1,5GB (bez přístupu k internetu pro ```steamwebhelper.exe``` jinak by se jednalo o 2,5-3GB) spotřebované V+RAM

***🟦 SCURLed*** - hromadná úprava LNK/URL zástupců

***🟦 WinSetView*** - globální úpravy průzkumníku💩 Windows - může snížit spotřebu RAM o desítky MB (explorer.exe)

***🟦 PortableApps.com*** - příklady nastavení
<br/>
-vypnout logo - ```Data\soffice.ini``` Logo=0
<br/>
-spustit minimalizovaně do tray bez (G)UI - ```Run, c:\uTorrentPortable.exe,,hide``` (AHK) + ```App\AppInfo\Launcher\uTorrentPortable.ini``` (```[Launch]``` ```ProgramExecutable=uTorrent\uTorrent.exe``` ```CommandLineArguments=/MINIMIZED```)
<br/>
-*Portable.exe nemusí být nutně v pozadí systému spuštěný

***🟦 uTorrent*** (doporučení pro tvorbu, které mi ale selským rozumem nedává smysl) - předpoklad dlouhého fungování [```1 torrentu```](https://sktorrent.eu/torrent/details.php?id=3adcdc3e45bd26ce481a6a03bb9875c50eaeffd9) se zvýší, pokud obsahuje pouze 1 archiv (RAR/ISO/MKV/...) a nic navíc. Torrent se dá přirovnat k RARu rozděleném na několik částí (většinou 16kb až 16MB). Zbytné soubory (části torrentu) se mohou časem u uživatelů poztrácet čímž zanikne jejich status "seeder" (100%). [```Příklad 99,8% (99,9% ISO) torrentu```](https://sktorrent.eu/torrent/details.php?id=ac3580f12b3fcfea20e1f119f95a0aa53187d0cf) (rozdělen po 8MB částech) - roky chybějící 2 obrázky o velikosti 5MB (stažených 766 částí z 767) = z 61% prázdný 5MB soubor ```Manual_pol.pdf``` (matematicky zřejmě jediný a čirou náhodou pro instalaci/užívání nedůležitý)

***🟦 ADB Explorer, 🟦 APK-Info, 🟦 Audacity, 🟦 Avidemux, 🟦 CPU-Z, DAEMON Tools Lite, 🟦 Error Lookup, 🟦 FastStone Capture, 🟦 HTTrack Website Copier, 🟦 HWiNFO, 🟦 InnoSetup Uninstall Log Reader, 🟦 Kaspersky Virus Removal Tool, 🟦 PHP, 🟦 Python, 🟦 qBittorrent, 🟦 Recuva, 🟦 VLC, 🟦 x64dbg, 🟦 XnViewMP***

***Ovladače*** - Visual C++ Redistributable 2005-2022, .NET Framework3.5+4.8, .NET Desktop Runtime 5-8, DirectX End-User Runtimes, Edge WebView2 Runtime, (Legacy)PhysX, OpenAL, K-Lite Codec Pack, 🟦 Xliveless

<br/>
<br/>
<br/>
<br/>
<br/>
<br/>

🟩1* English

***Total Uninstall*** - system scan (before/after app launch/installation) and display changes (files/folders/registry), export registry changes to REG file for un/install. I recommend removing default exceptions - very useful (guaranteeing a clean system that doesn't need to be reinstalled for decades) and destructive if one doesn't know what he's doing

***🟦 Inno Setup XDELTA Patch Maker*** - create a patch

***🟦 ISO Directory v0.5***(Michel) - create a mini-image (crack) CD/DVD (size a few kB)

***🟦 BikMod v0.3e (Beta) + 🟦 bink2-libass*** - modified "binkw32.dll" library, which can be used to load external SRT subtitles. 🟦 RADTools - modification of BIK/SMK video files

***MSI Afterburner+RTSS*** - screen overlay - time, HW monitoring, FPS/Frametime limit (hotkeys), Scanline Sync, tray icons. Limiting FPS will significantly increase loading times in some games (Painkiller/...)

***🟦 dgVoodoo2*** - DX11/12 rendering (wrapper) for DX1-9 games, option to enlarge interface of games at high resolutions (resolution in game is 1280x720 and through app it is set to 1920x1080 = interface will be big as in 720p, but resolution will be 1080p) and force unsupported resolution into the game (+refresh rate/FPS limit/AF texture filtering/...). Right mouse click opens advanced options. To enable wrapper, the necessary DLL files from dgVoodoo2 subfolder must be copied to (main) EXE file of the game and then configured (dgVoodooCpl.exe) = "dgVoodoo.conf" will be created. An example for keeping image sharp (not pixelated and not blurred through AA) in fixed/limited resolution games - ```General``` Scaling mode (Stretched, keep Aspect Ratio), ```DirectX``` Resolution (2x), ```GeneralExt``` Resampling (Bilinear)

***🟦 4GB Patch*** - 2GB RAM limit workaround for 32-bit apps. Useful for some games where modifying EXE file increase minimum FPS, speed up loading times and also prevent app from crashing when playing for a longer time

***ArgusMonitor, Speedfan*** - regulation of CPU+GPU+case fans speed and their curves+switching off

***🟦 ClickMonitorDDC*** - ```change monitor``` brightness/contrast/volume/on/off, tray icons; profiles - hotkeys. Works in games too

***🟦 Gamma Panel*** - ```software change``` brightness/contrast/gamma - profiles - hotkeys. Works in games too (windowed/borderless seamless, but in fullscreen some games don't allow changes - but for example in ```dgVoodoo2``` these changes can be forced - Output API / Inherit Color Profile...). Issues with AHK - ALT key sent (not physically pressed) via AHK is not accepted by Gamma Panel = when not using switches (multiple functions on one key) this may not be a problem because Gamma Panel supports hotkeys apparently without limitations. The second issue is “ inability ” to run Gamma Panel (EXE,LNK) via AHK because the “gapa.ini” will not be loaded (workaround is to run via BAT - first line ```cd /d c:\```, let cmd.exe close automatically). ***[📥 PowerStrip](https://github.com/hornster02/hornster02/raw/main/_PowerStrip_3.9-key.rar)*** https://entechtaiwan.com/util/ps.shtm

***🟦 Custom Resolution Utility*** - create a custom resolution and refresh rate for monitor. Also ideal for workaround maximum resolution limit on old GPUs by lowering refresh rate - 2560x1080x54Hz on Radeon HD 4670 (2008 - 1920x1200x60Hz). Or if Win sets a lower Hz than monitor supports, then if the maximum supported refresh rate is set in CRU for native resolution, then even lower resolutions should be automatically set with maximum refresh rate (```GPU Scaling``` in Radeon Bloatware💩 can break functionality). Another option to force a custom refresh rate in DirectX apps is to create a DWORLD value ```ForceRefreshRate``` in ```HKLM\SOFTWARE\Wow6432Node\Microsoft\DirectDraw``` and ```HKLM\SOFTWARE\Microsoft\DirectDraw``` and write a specific number in Hz (restart is not necessary, changes are activated immediately). Filling up all "Detailed resolutions" slots can turn off Freesync in Radeon Bloatware💩

***🟦 RefreshLock*** - probably the most universal way to force highest supported monitor refresh rate. It also works in DirectX/Vulkan/OpenGL

***🟦 OverdriveNTool, 🟦 AMD GPU Clock Tool*** - voltage/frequency for Radeon - profiles - shortcuts/hotkeys

***🟦 AmdMsrTweaker, 🟦 ZenStates, 🟦 PhenomMsrTweaker, 🟦 BrazosTweaker*** - AMD K8 (2003) to Zen 4 CPUs - voltage/frequency/multiplier - profiles - shortcuts/hotkeys

ATI/AMD GPU Bios - ***🟦 GPU-Z, 🟦 RBE - Radeon BIOS Editor, 🟦 VBE7, 🟦 Polaris Bios Editor PBE + 🟦 AMDVBFlash / ATI ATIFlash + 🟦 AMD/ATI Pixel Clock Patcher*** - sign Radeon drivers after modifying GPU bios (rename to "atikmdag-patcher-bios.exe")

***🟦 RadeonMod,ATI Tray Tools*** (legacy) - ATI/AMD Catalyst / Radeon Bloatware💩 replacement

Switching ***Power Scheme*** (control panels) via hotkeys/shortcuts. Registry path ```HKLM\SYSTEM\ControlSet001\Control\Power\User\PowerSchemes``` command ```C:\Windows\System32\powercfg.exe -setactive XXX``` instead of XXX, write name of required key

***Equalizer APO+Peace*** - sound equalizer - by overwriting configuration files (also via hotkeys/shortcuts) it is possible to switch profiles in real time without starting app

***🟦 Raw Accel*** - detailed mouse settings, different axis sensitivity, etc. Profiles can also be switched via hotkeys/shortcuts ```c:\RawAccel\writer.exe c:\RawAccel\settings.json``` - changing the cursor when switching can be disabled by unifying them in Control panels (normal selection/background work)

***🟦 hidusbf*** - mouse polling rate adjustment (Hz, higher clock = higher cursor smoothness). Ideal if an old game works only on some mice. If you can't install driver via "Setup.exe" (Install Service) and there is no installation option in context menu (INF), the other way to install is command ```RUNDLL32.EXE SETUPAPI.DLL,InstallHinfSection DefaultInstall 132 c:\hidusbf\hidusbf\DRIVER\HIDUSBF.INF```

***🟦 DIMR (Direct Input Mouse Rate)*** - mouse polling rate (Hz) monitor

***🟦 Mouse Settings Changer*** - switching mouse/touchpad sensitivity (control panels) even with a hotkeys - AHK can be used to hide popup window when switching profile - AltGr+F7
<br/>
```VKA5 & F7::Run, C:\MouseSC_x64.exe /Speed:6, , Hide```

***🟦 XInput Plus*** - detailed gamepad settings

***Comfort On-Screen Keyboard Pro*** - SW keyboard

***🟦 NirCmd+🟦 DevManView*** - change resolution+frequency, turn on/off HW+SW devices, ... - control via hotkeys/shortcuts

***🟦 IObit Unlocker*** - unlock (NTFS security or running process) files/folders

```🚫update``` ***EXE Radar Pro v3 (Beta)*** - when running an executable file (exe/msi/bat/...) a window will appear asking whether to run or exit it (user-defined Command-Line/whitelist/blacklist runs automatically in background of the system). Verification via checksum. I recommend removing default exceptions (system/MS/... files)

🚫***Easy File Locker*** - disable reading/writing/deleting/hiding files/folders. Locking only works when Windows+SYS driver running (can be turned on/off via hotkeys/shortcuts without starting app - NirCmd). If some app bypasses protection, it's NTFS links

🚫Create a file instead of a folder, deleting even system EXE/... files - these classic methods never fail

🚫***Firewall*** - Outpost/TinyWall/Firewall App Blocker. Default Win firewall has rules stored here
<br/>
```HKLM\SYSTEM\ControlSet\services\SharedAccess\Parameters\FirewallPolicy\FirewallRules```
<br/>
```HKLM\SYSTEM\ControlSet001\services\SharedAccess\Parameters\FirewallPolicy\FirewallRules```
<br/>
```HKLM\SYSTEM\ControlSet002\services\SharedAccess\Parameters\FirewallPolicy\FirewallRules```
<br/>
and forbidding of arbitrarily adding exceptions is easily done by adding and modifying permissions for "Everyone"

🚫***🟦 Autoruns*** - automatically launched apps/libraries/drivers

🚫***🟦 NSudo*** - run apps with highest privileges. Combined with Autoruns it is easy to get rid of all MS bloatware (updates/services/task schedulers/Defender/Edge/OneDrive/Slutana/StartMenu/...)

❶***🟦 BootICE*** - create bootable media without formatting and data loss (MBR/PBR for HDD/SSD/USB), modify Windows BCD/UEFI files (multiboot, change system partition, ...), hide/activate partition

❷***🟦 Gandalf's Windows*** (Win7-11) - bootable (without formatting and losing data⬆️) from USB (even from phone - if supports boot from "bios") with internet capability, installing programs/drivers. More or less full system - but after reboot it returns to default settings

❸***🟦 WinNTSetup*** - install/backup/restore Windows without formatting and data loss and creating a bootable installation media (skipping constantly erroneous/dangerous MS installation process = after copying data and restarting PC, system starts). Iso/wim/swm/vhd (can also be used in 7-Zip)+option to add drivers/tweaks. Process is not dependent on specific HW, so for example restoring a system backup can be done on any PC. It can also be installed on USB drives and at least Win11 can be started from them without any further modifications (necessary drivers are loaded at boot, so it does not matter which PC it will be started on) - its meaningless requirements are ignored (UEFI/TPM/...) "Boot drive+Installation drive" can be the same partition of one disk (app is preset for a regular user - just select Windows edition, click "Setup+OK" and then process starts - at the end Bios+UEFI boot is automatically created and then in case of MBR disk I recommend checking if there is a green dot at BOOT PART). Backup is done via "Local Windows Installations/Capture Wim" - exceptions can be added to "WimScript.ini". Possible bug fixes
<br/>
-inserted ISO reports "No Windows Source Detected" or "Windows Source invalid" (unzip ISO and insert installation file - it should be called "install" and be in "sources" folder - rest of ISO content is useless for installation and will not be used anyway)
<br/>
-test (7-Zip) of newly created backup finds errors (HDD - damaged sectors), (CPU+RAM - turn off compression when creating a backup)
<br/>
-system recovery can also be done by extracting it to a disk (7-Zip) and finally repairing boot if necessary (BootICE)

System backup can also be done via WinRAR (it's data like any other, just ⚠️watch out for NTFS security and links), benefits are
<br/>
-independence on obscure backup software, universality
<br/>
-immediate access to data, possibility to restore, for example, only 1 file
<br/>
-small data package thanks to high compression (in my case ratio is 21% = 30.8GB system / 6.5GB backup)
<br/>
⓿🚫***🟦 NTFS Permissions Tools + 🟦 AccessEnum*** - data security management, bookmarks for quick access

***USB boot*** - BootDriverFlags, 0x14 ```HKLM\SYSTEM\HardwareConfig\XXX``` - change order of loaded drivers at boot Win10+ = one system with all programs + settings, which can be run on "any" PC via internal or external disk (missing USB drivers or IDE/AHCI mode, etc. can be a problem, although not unsolvable)

***Changing drive letters via registry*** ```HKLM\SYSTEM\MountedDevices```

***🟦 GImageX*** - create WIM image (Windows in one compressed file - bootable or for complete system backup). Capture/Apply/Mount

***Link Shell Extension+🟦 NTFSLinksView*** - NTFS links and redirecting apps settings to custom folders. Control via context menu - pick link source (new location) / drop as (original location)

***🟦 Driver Booster for Steam*** - update drivers

***🟦 Display Driver Uninstaller*** - uninstall audio/video drivers, ***Device Remover*** - possible major speed up of "Device Manager" startup (depends on how many PCs/components the system has gone through)

***🟦 7+ Taskbar Tweaker+WinaeroTweaker+ExplorerPatcher+🟦 WinPaletter+🟦 Classic Color Panel*** - modifying Windows user interface

***🟦 Pazera Free Audio Extractor, 🟦 MKVToolNix*** - editing video files without conversion.  Removing/extracting audio tracks, detailed information about audio/video files, ...

***🟦 Subtitle Edit*** - edit subtitles

***🟦 Video-subtitle-extractor (VSE)*** - OCR method of automatic subtitles creation

***🟦 UniFlash*** (MS-DOS, Rainbow Software) - save/restore CMOS bios memory (settings) to a file. May not work on newer HW (AM3+ +)

***🟦 NetSpeedMonitor*** - monitoring of download/upload speed and data amount+history, tray

***🟦 AIDA64*** - detailed information about SW/HW

***🟦 Prime95+Furmark*** - PC lifetime+stability test (power virus)

***🟦 WinRAR*** - data archiving. Advantages over 7-Zip
<br/>
-recovery record = no need to download damaged archives multiple times or accept data loss

-profiles with different settings. Automation (by selecting a profile, for example, an encrypted archive with current date and specific data can be automatically created to a predefined location)

-settings in app folder = can fully work as a portable app ```WinRAR.ini``` Global\AppData=0
<br/>
-file sizes in main window are not displayed in confusing bytes
<br/>
-in main window it is possible to sort data by type 😮
<br/>
-better "solid" compression (many times faster and yet resulting archive size can be 50+% smaller)
<br/>
-option to exclude certain files/folders when creating archives
<br/>
-option to uncompress certain files to speed up process

-is it possible that 7z doesn't support NTFS file system and can't archive more complex data that contains various security and symbolic links? How to achieve archiving link and not data it references and thus not break data structure, among other things?

-7-Zip has overall better compression (but worse than ***🟦 PeaZip***) and, most importantly, FAR wider format support (often read-only, but that's no small thing at all). Being free in this form is probably a necessity...

***🟦 WizTree*** - disk space analysis

***ImDisk Toolkit*** - ramdisk

***Primo Ramdisk*** - option to page files in ramdisk or use inaccessible part of RAM (Invisible Memory) - 32-Bit Win has a limit of ~4GB, Win11 Home 128GB (same limit as WinXP)

***🟦 Mem Reduct*** - free RAM memory (without terminating processes) by hotkey or clicking on tray icon. However, there may be more writing to paging file = reduced lifetime of SSD*1

***RimhillEx*** - CD/DVD read speed limitation

***🟦 PortableWinCDEmu*** - virtual drive

***🟦 FAT32 Format GUI*** - 32GB limit workaround

***🟦 Hard Disk Sentinel*** - disk monitoring+history, S.M.A.R.T. tests, noise control (AAM), tray icons (health), option to disable HDD shutdown when idle (auto access or APM)

***HDD Regenerator*** - repair corrupted sectors on HDD without data loss (Win/MS-DOS)

***🟦 Total Commander*** - fast/efficient replacement of Explorer/Desktop/Start Menu with lots of extra features (internal file association including icons, file comparison by content, change attributes, copy data paths to clipboard, show/hide certain files/folders, copying files with certain date while preserving directory structure, verifying copied data for possible damage, ... = lower hundreds of hotkeys). A few useful "wincmd.ini" tweaks (first 2 are very important and I don't understand that the app is not set up that way in base - first one speeds up/transparent data search by ignoring NTFS links = searches for data as written on disk and doesn't show "false duplicates". Second copies/moves NTFS links as links and not as folders - unfortunately this [```does not work for files```](https://www.ghisler.ch/board/viewtopic.php?t=40835), where for manipulation you need use for example WinRAR
<br/>
```IgnoreLinks=8```
```CopyLinks=1```
```DriveBarHide=DC```
```RestrictInterface=3```
```EditWaitTime=-1```
```UseIniInProgramDir=1```
```pluginbasedir=%COMMANDER_PATH%\plugins```
```AlwaysCopyInBackground=1```
<br/>
With add-on ***DiskDir Extended*** you can create a data catalog ("pack files" function - LST file is like an archive and can be searched in it)
<br/>
-bulk renaming - remove characters (number) from start ```[N2-]``` from end ```[N1--2]```
<br/>
-mass removal of diacritics (find/replace)
<br/>
```á|č|ď|é|ě|í|ň|ó|ř|š|ť|ú|ů|ý|ž|Á|Č|Ď|É|Ě|Í|Ň|Ó|Ř|Š|Ť|Ú|Ů|Ý|Ž```
<br/>
```a|c|d|e|e|i|n|o|r|s|t|u|u|y|z|A|C|D|E|E|I|N|O|R|S|T|U|U|Y|Z```
<br/>
-find a CSS file that has somewhere in name TAB - ```*tab*.css```

***System Explorer*** - replacement of "Task Manager" - possibility to save priority/affinity of apps for their automatic setting at next startup. ***🟦 Process Hacker*** 

***🟦 Battle Encoder Shirasé*** - process throttling - up to 99%. Ability to use via Command-Line without UI - example 90% and 10% restriction for 2 EXE files = BES will look for running processes in background and automatically restrict them
<br/>
```c:\BES\BES.exe -J "C:\FileActivityWatch\FileActivityWatch.exe" 90 -m "c:\Deus Ex\System\DeusEx.exe" 10 -m```

***🟦 Registry Workshop*** - advanced replacement of default "Regedit". "Load Hive" can be used to load and edit an external registry. To integrate with Total Uninstall, use following command in its settings - ```"c:\Registry Workshop\RegWorkshopX64.exe" /g```

***🟦 Notepad++*** - bulk marking of selected rows with bookmarks and their removal/retention, bulk removal of rows containing empty/no characters, select text block ```ALT+left button```, regular expressions -
<br/>
-remove all characters on lines if there are 4 or less ```^.{0,4}$```
<br/>
-remove first 4 characters on lines ```^.{4}(.*)$``` ```$1```
<br/>
-remove 4 and 4 and everything between ```4.*?4```
<br/>
-find 4 and insert empty line ```(?-s)4.*``` ```$0\r\n```
<br/>
-insert 4 on empty line ```^$``` ```4```
<br/>
-insert 4 at beginning of line ```^``` ```4```
<br/>
-insert 4 at end of line ```$``` ```4```

***🟦 HEXelon Max 6*** - calculator with three independent "panels"

***🟦 FastStone Image Viewer*** - simple/fast image viewer

***🟦 SumatraPDF*** - fast PDF viewer. Option to hide all UI

***🟦 Screen Ruler*** (Bluegrams) - ruler

***🟦 NAPS2*** - scan, export to PDF, OCR

***🟦 Ultimate Icon Converter*** - icon creator

***🟦 ATI GPU Scaling Fix***(legacy), ***🟦 HDD Low Level Format Tool*** and dozens of apps from 🟦 NirSoft (***OpenedFilesView/AppReadWriteCounter/ProcessActivityView/FileAccessErrorView/LiveTcpUdpWatch/CurrPorts/AdvancedRun/AppAudioConfig/DriveLetterView/FileTypesMan/GUIPropView/InstalledCodec/InstalledPackagesView/KeyboardStateView/AppCrashView/BlueScreenView/ShellExView/ShellMenuView/OpenWithView/SpecialFoldersView/EventLogSourcesView/FullEventLogView/MyEventViewer/ EventLogChannelsView***)

***VMware Workstation*** (15) - possibility to use e.g. Steam client while running Win7 (from 2024 there is a threat of arbitrary banning of access from this "dangerous" system - see some banks, possible solution=responsive mode in browser) in a virtual machine with a newer system (Win11). Support for internet connection (bridging) (router can solve possible connection problems) and possibility of sharing folders - host/guest (e.g. for direct downloading of games from Win11 to Win7). For full functionality, after installing system (regular ISO) in VMware, ISO with drivers (VMware Tools) must be mounted to virtual drive and installed. 7-Zip can open a VMDK file with system

***🟦 Process Monitor+🟦 FileActivityWatch*** - activities of running processes - detailed list of accesses on SSD/registry/network

***KernelEX/One-Core-API/Extended Kernel for Windows Vista/VxKex*** - ability to run newer apps on an unsupported system (compatibility layer). For example Firefox 2025 in WinXP 2001

***🟦 HxD+CFF Explorer+Resource Hacker*** - editing executables and more

***GodMode.{ED7BA470-8E54-465E-825C-99712043E01C}*** - creating a folder with this name and opening it via Explorer opens a window with all control panels

***Microsoft Management Console*** (MMC) - add custom modules to a single MMC console. Procedure - run/mmc/add or remove snap-in modules/select modules/save

```c:\Windows\System32\Robocopy.exe "c:\1" "e:\1" /E /PURGE /w:0 /r:0 /MOT:10```
<br/>
Automatic synchronization of two folders. ```c:\1``` is source folder and ```e:\1``` is backup. If a file/folder is created/changed in source folder, it is copied to backup. If a file/folder is deleted in source folder, it will be deleted from backup. "MOT:10" indicates 10 minutes of waiting and then synchronization. Is it synchronization (comparison) and not "delete entire backup/copy entire resource", so it does not reduce lifetime of SSD with unnecessary writes, among other things. A small drawback is that there is no comparison of files by content, but only by attributes+size (fast/non-demanding). It is possible to close console window by terminating "conhost.exe" process and leave only "ROBOCOPY.exe" (automatic synchronization in background of system) on. Useful in combination with NTFS links for automatic SAVEGAME backup

***🟦 T-Clock*** - advanced replacement of default tray clock. App with decades of history and several authors = possibilities of settings and range of functions (not even related to clock) is unprecedented

***🟦 Desktop VLocker*** - computer lock

***[🟦 tableManager](https://github.com/pietrantonio91/tablemanager)*** - HTML tables, option of sorting and filtering in selected columns

***🟦 SmartSteamEmu*** - a lightweight alternative to Steam client with no updates required (Game Booster). In my case it is 1 vs. 60+ seconds for starting app and 40MB vs. 1,5GB (without internet access for ```steamwebhelper.exe``` otherwise it would be 2,5-3GB) used V+RAM

***🟦 SCURLed*** - mass editing of LNK/URL shortcuts

***🟦 WinSetView*** - Windows explorer💩 global customizations - can reduce RAM usage by tens of MB (explorer.exe)

***🟦 PortableApps.com*** - setting examples
<br/>
-disable logo - ```Data\soffice.ini``` Logo=0
<br/>
-run minimized in tray without (G)UI - ```Run, c:\uTorrentPortable.exe,,hide``` (AHK) + ```App\AppInfo\Launcher\uTorrentPortable.ini``` (```[Launch]``` ```ProgramExecutable=uTorrent\uTorrent.exe``` ```CommandLineArguments=/MINIMIZED```)
<br/>
-*Portable.exe is not necessarily required to be running in system background

***🟦 ADB Explorer, 🟦 APK-Info, 🟦 Audacity, 🟦 Avidemux, 🟦 CPU-Z, DAEMON Tools Lite, 🟦 Error Lookup, 🟦 FastStone Capture, 🟦 HTTrack Website Copier, 🟦 HWiNFO, 🟦 InnoSetup Uninstall Log Reader, 🟦 Kaspersky Virus Removal Tool, 🟦 PHP, 🟦 Python, 🟦 qBittorrent, 🟦 Recuva, 🟦 uTorrent, 🟦 VLC, 🟦 x64dbg, 🟦 XnViewMP***

***Drivers*** - Visual C++ Redistributable 2005-2022, .NET Framework3.5+4.8, .NET Desktop Runtime 5-8, DirectX End-User Runtimes, Edge WebView2 Runtime, (Legacy)PhysX, OpenAL, K-Lite Codec Pack, 🟦 Xliveless

<br/>
<br/>
<br/>
<br/>
<br/>
<br/>
<br/>
<br/>
<br/>

🟨2*  ***[📥 Autohotkey v1.1 script](https://github.com/hornster02/hornster02/raw/main/_Autohotkey_AHK-2023.rar)*** (čeština ⬇️)

-IMPORTANT - AHK file probably needs to be run via "AutoHotkeyU64.exe" and not via default "AutoHotkey.exe" (error)

AHK file in archive can be opened in Notepad (or if Autohotkey is installed on PC, it can be run as a regular EXE file). Script has no user interface (apart from "WindowSpy" function). AHK contains a few functional scripts such as

hold ```F12``` on/off borderless fullscreen (useful for games)

hold ```F11``` prevents mouse cursor from moving outside active window - switch (useful for games)

hold ```F10``` pause/resume (suspend) foreground processes. Useful in case of running app with high demands on PC performance - there will be a significant reduction in power consumption/temperature/noise. 98% of programs/games should work without issue - for rest you can expect various errors or crashes. Script can be useful for example when playing games on battery = 1 key completely stops game at 0FPS and there is no need to turn it off. Perhaps a better alternative is "Battle Encoder Shirasé" app which solves possible problems by limiting up to 99%. 100% (suspend) does not bring anything extra in real use (except for complete stop of SSD/network activity). Other 3 options (disabled by default) are (hold F10 = pause foreground process / 2x press resume process) and (hold F10 = pause listed processes - background or foreground / 2x press resume processes) and (hold F10 = pause/resume listed processes - background or foreground)

Control Mouse with Keyboard ```Num Lock``` - movement including angled```1235```, left+middle+right button including drag and drop and double click```789```, wheeldown+up```46```, cursor movement to three specified positions```0```, 4th mouse button```.``` Easy speed and acceleration adjustment

```left+middle mouse button``` - dragging mouse (anywhere in window, not just over title bar) moves window that is not maximized. No need to hold middle button all the time. ESC returns window to its original position. Many programs can be moved even in "fullscreen" mode (virtual PCs, image viewers, video players, ...)

```LWin``` key (CTRL+F). Hold (show taskbar without Start menu - must be set to autohide). Double (hide taskbar)

```menu key``` (CTRL+C) , hold (CTRL+V) , double (CTRL+A)

```pause key``` (ALT+F4) if "SC" and "VK" numbers correspond to your keyboard, then even games that have these keys "disabled" can be ended. Holding key down for 2 seconds restarts PC as standard (but regardless of current work) Shutdown, 6 = "force"

```ALT+Shift``` shrink active window to half screen and align it right or left or maximize it

```ALT+Ctrl``` show desktop

```CTRL+ALT+INS``` exit AutoHotkey processes

```ScrollLock``` AUTOHOTKEY-WindowSpy. Hold (activate window to foreground). ```ESC``` hide AutoHotkeyU64.exe. When working with "WindowSpy" another "AutoHotkey.exe" process is not used

***And disabled features serving more as a template***

holding ```ě``` key inserts "@" . Dozens of additional keys can easily be added, eliminating need for time consuming keyboard shortcuts

change gamma/contrast/brightness/volume/mute/unmute/power plan/frequencies/voltages/mouse sensitivity/resolution/network/..., crouch+aim toggles for games (search for *01), holding Printscreen key saves image to SSD = usually requires external programs
<br/>
<br/>
<br/>
***ČEŠTINA***

-DŮLEŽITÉ - AHK soubor je zřejmě potřeba spustit přes "AutoHotkeyU64.exe" a ne přes výchozí "AutoHotkey.exe" (error)

AHK soubor v archivu se dá otevřít v poznámkovém bloku (nebo pokud je Autohotkey v PC nainstalován, tak rovnou spustit jako obyčejný EXE soubor). Skript nemá - kromě funkce "WindowSpy" - žádné uživatelské rozhraní. AHK obsahuje návod pro začátečníky (globální zkratky, nebo několik funkcí na jedné klávese v rámci jednoho programu pomocí class a window title) a pár funkčních skriptů jako jsou

podržení ```F12``` zapne/vypne fullscreen - přepínač (užitečné pro hry)

podržení ```F11``` zabrání kurzoru myši pohyb mimo aktivní okno - přepínač (užitečné pro hry)

podržení ```F10``` pozastavení/pokračování (suspend) procesů v popředí. Užitečné v případě zapnutého programu s vysokými nároky na výkon PC - dojde k zásadnímu snížení spotřeby/teplot/hlučnosti. 98% programů/her by mělo fungovat bez problému - u zbytku se dá očekávat různá chybovost nebo rovnou pády. Skript se může hodit třeba při hraní na baterii = 1 klávesou se hra úplně zastaví na 0FPS a není nutné ji vypínat. Možná lepší alternativa je program "Battle Encoder Shirasé" který případné problémy řeší omezením do 99%. 100% (suspend) v reálu (kromě úplného zastavení SSD/síťové aktivity) nic navíc nepřináší. Další 3 varianty (ve výchozím stavu vypnuté) jsou (držet F10 = pozastavit proces v popředí / 2x stisknutí vrátí proces do chodu) a (držet F10 = pozastavit vypsané procesy - v pozadí nebo popředí / 2x stisknutí vrátí procesy do chodu) a (držet F10 = pozastavit/spustit vypsané procesy - v pozadí nebo popředí)

ovládání myši klávesnicí ```Num Lock``` - pohyb včetně šikmého```1235```, levé+prostřední+pravé tlačítko včetně možnosti Drag and drop a dvojkliku```789```, kolečko dolu+nahoru```46```, pohyb kurzoru do tří určených pozic```0```, 4-té tlačítko myši```.``` Snadná úprava rychlosti a akcelerace

```levé+prostřední tlačítko myši``` - tažením myši (kdekoli v okně, ne jenom přes title bar) se přesunuje okno které není maximalizované. Prostřední tlačítko se nemusí držet celou dobu. ESC vrátí okno na původní pozici. Spousta programů i ve "fullscreen" režimu může být přesunováno (virtuální PC, prohlížeče obrázků, přehrávače videí, ...)

```LWin``` (CTRL+F). Držet (zobrazit hlavní panel bez nabídky Start - musí být nastavený na autohide). 2x stisknutí (skrýt hlavní panel)

```menu``` (CTRL+C). Držet (CTRL+V). 2x stisknutí (CTRL+A)

```pause``` (ALT+F4) - pokud "SC" a "VK" čísla odpovídají vaší klávesnici, tak půjdou vypnout i hry, které mají tyto klávesy "zablokované". Podržení klávesy na 2 vteřiny standartně restartuje PC (ale bez ohledu na rozdělanou práci). Shutdown, 6 = "na sílu"

```ALT+Shift``` zmenšit aktivní okno na polovinu obrazovky a zarovnat ho vpravo nebo vlevo nebo ho maximalizovat

```ALT+Ctrl``` zobrazit plochu

```CTRL+ALT+INS``` vypnout procesy AutoHotkey

```ScrollLock``` AUTOHOTKEY-WindowSpy. Držet (aktivovat do popředí). ```ESC``` zavřít AutoHotkeyU64.exe

***A vypnuté funkce sloužící spíše jako vzor***

podržení klávesy ```ě``` napíše "@" . Snadno se dají přidat desítky dalších kláves a díky tomu odpadne nutnost používat zdržující klávesové zkratky

změnit gamma/kontrast/jas/hlasitost+zap+vyp/schéma napájení/frekvence/napětí/citlivost myši/rozlišení/síť/..., a také přepínače skrčení+míření pro hry (vyhledej *01), držení printscreen uloží obrázek na SSD = většinou vyžaduje externí programy

***[📥 Font Contrast HTML - option to change font color by HEX/slider/system dialog (Firefox29) or HEX only (9)](https://github.com/hornster02/hornster02/raw/main/_FontContrastHTML.rar)***
![font](https://github.com/user-attachments/assets/40807f87-8f6e-4713-8faa-80d69be6f4fb)
