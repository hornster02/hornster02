🟧0* GAMES-JINE

Software for Windows
<br/>
🟩1* English deepl.com translation below (last edit 12/2023)
<br/>

***Total Uninstall*** - sken systému (před/po spuštení/nainstalování aplikace) a zobrazení změn (soubory/složky/registr), export změn registru do REG souboru pro od/instalaci

***MSI Afterburner+RTSS*** - překrytí obrazu - čas, HW monitoring, limit FPS/Frametime (klávesové zkratky), Scanline Sync, tray ikony

***dgVoodoo2*** - DX11/12 rendering (wrapper) pro DX1-9 hry, možnost zvětšení rozhraní her při vysokých rozlišeních (např. rozlišení ve hře je 1280x720 a přes program se nastaví 1920x1080 = rozhraní bude velké jako v 720p, ale rozlišení bude 1080p) a vnutit hře nepodporovaná rozlišení. Od verze 2.55+ (2018+) v kombinaci s DX11+Radeon může nastat bug v podobě bílých textur (u novějších verzí z roku 2023+ je problém zřejmě už vyřešený). Pravý klik myší zpřístupní pokročilé možnosti. Pro zapnutí wrapperu se musí potřebné DLL soubory z podsložky dgVoodoo2 nakopírovat k (hlavnímu) EXE souboru hry a pak nakonfigurovat (dgVoodooCpl.exe) čímž se u EXE souboru hry vytvoří "dgVoodoo.conf"

***ArgusMonitor, Speedfan*** - regulace otáček ventilátorů CPU+GPU+skříně a jejich křivky+vypínání

***AutoHotkey*** - automatizace/přepínače/skripty, vlastní klávesové zkratky, dvojité/krátké/dlouhé podržení klávesy/tlačítka... Na jednu klávesu/tlačítko mohou být napsané stovky různých funkcí pro každý program zvlášť (nebo jeho konkrétní okno - class/WinTitle) nebo jedna funkce globálně pro všechny

***ClickMonitorDDC*** - změna jasu/kontrastu/hlasitosti/zapnutí/vypnutí monitoru, tray ikony; profily - klávesové zkratky. Funguje i ve hrách

***PowerStrip*** - softwarová změna jasu/kontrastu/gammy - profily - klávesové zkratky. Funguje i ve hrách (bezproblémový windowed/borderless, ale ve fullscreen některé hry změny neumožňují)

***Custom Resolution Utility*** - vytvoření vlastního rozlišení a obnovovací frekvence monitoru. Ideální také pro obejití limitu maximálního rozlišení u starých GPU snížením obnovovací frekvence - např. 2560x1080x54Hz na Radeon HD 4670 (2008 - 1920x1200x60Hz)

***OverdriveNTool, AMD GPU Clock Tool*** - napětí/frekvence pro Radeon - profily - klávesové zkratky/zástupce

***AmdMsrTweaker, ZenStates, PhenomMsrTweaker, BrazosTweaker*** - AMD K8 až Zen 2 CPU ( 2003-2019) - napětí/frekvence/násobič - profily - klávesové zkratky/zástupce

***AMD/ATI Pixel Clock Patcher*** - podepsání Radeon ovladačů po úpravě biosu GPU  (přejmenovat na "atikmdag-patcher-bios.exe")

Přepínání ***Schéma napájení*** (ovládací panely) přes klávesové zkratky/zástupce. Cesta v registru ```HKLM\SYSTEM\ControlSet001\Control\Power\User\PowerSchemes``` příkaz ve formátu
<br/>
```C:\Windows\System32\powercfg.exe -setactive XXX```
<br/>
místo XXX se napíše název potřebného klíče

***Equalizer APO+Peace*** - ekvalizér zvuku - přepsáním konfiguračních souborů (i přes klávesové zkratky/zástupce) je možné v reálném čase přepínat profily bez spouštění programu. MS Visual C++ 2015-2022 může vyřešit případnou chybu při spuštění "Configurator.exe"

***Raw Accel*** - detailní nastavení myši, různá citlivost os atd. Profily jde přepínat i přes klávesové zkratky/zástupce ```c:\RawAccel\writer.exe c:\RawAccel\settings.json``` - změna kurzoru při přepnutí se dá zakázat jejich sjednocením v ovládacích panelech (normální výběr/práce na pozadí)

***Mouse Settings Changer*** - přepínání citlivosti myši/touchpadu (ovládací panely) třeba i klávesovou zkratkou - pro skrytí vyskakovacího okna při přepnutí profilu se může použít Autohotkey - příklad pro AltGr+F7
<br/>
```VKA5 & F7::Run, C:\MouseSC_x64.exe /Speed:6, , Hide```

***XInput Plus*** - detailní nastavení gamepadu

***Comfort On-Screen Keyboard Pro*** - SW klávesnice

***NirCmd+DevManView*** - změna rozlišení+frekvence, zapínání/vypínání HW+SW zařízení, ... - ovládání i přes klávesové zkratky/zástupce

***IObit Unlocker*** - odemknutí (NTFS zabezpečení nebo běžící proces) souborů/složek

🚫update***EXE Radar Pro v3 (Beta)*** - při spuštění spustitelného souboru (exe/msi/bat/...) se zobrazí okno s dotazem zda ho spustit nebo ukončit (uživatelem definovaný Command-Line/whitelist/blacklist probíhá automaticky v pozadí systému). Ověření přes kontrolní součet

🚫***Easy File Locker*** - zakázání čtení/zápisu/mazání/ skrytí souborů/složek. Zamknutí funguje jen když je spuštěný Windows+SYS ovladač programu (dá se zapínat/vypínat přes zástupce/klávesové zkratky bez nutnosti spouštět program - NirCmd). Pokud nějaký program obchází ochranu, tak za to můžou NTFS linky*0 (nezamknuté všechny cesty)

🚫***NTFS Permissions Tools*** (DBC Studio) - správa zabezpečení dat, záložky pro rychlý přístup

🚫 Vytvoření souboru místo složky

🚫***Firewall***  - Outpost/TinyWall/Firewall App Blocker

🚫***NSudo*** - spouštění aplikací s nejvyššími právy. V kombinaci i s programem Autoruns je snadné se zbavit veškerého MS bloatwaru (služby/plánovače úloh/Defender/Edge/OneDrive/Slutana/...) ***ADB AppControl*** 

***Autoruns*** - automaticky spouštěné aplikace/knihovny/ovladače

❶***BootICE*** - vytvoření bootovacího média bez formátování a ztráty dat (MBR/PBR pro HDD/SSD/USB), úprava Windows souborů BCD/UEFI (multiboot, změna systémové partition, ...), skrytí/aktivace partition

❷***Gandalf’s Windows*** (Win7-11) - spustitelný (bez formátování a ztráty dat⬆️) z USB (i z telefonu - pokud podporuje boot z "biosu") s možností internetu, instalování programů/ovladačů. Víceméně plnohodnotný systém - po restartu se ale vrací do výchozího nastavení

❸***WinNTSetup*** - instalace/záloha/obnovení Windows bez formátování a ztráty dat a vytváření bootovacího instalačního média (přeskočení věčně chybového/nebezpečného MS instalačního procesu = po nakopírování dat a restartu PC se spouští systém). Iso/wim/swm/vhd (dají se používat i v ***7-Zip*** )+možnost přidání ovladačů/tweaků. Proces není závislý na konkrétní HW, takže třeba obnovení zálohy systému jde provést na jakékoli PC. Jde instalovat i na USB disky a minimálně Win11 z nich jde bez dalších úprav spustit (potřebné ovladače se načítají při bootu, takže nezáleží na jakém PC se bude spouštět) - jeho nesmyslné požadavky jsou ignorovány (UEFI/TPM/...) "Boot drive+Installation drive" může být stejný oddíl jednoho disku (program je pro běžného uživatele přednastavený - stačí vybrat edici Windows, kliknout na "Setup+OK" a proces začíná - na konci se automaticky vytvoří Bios+UEFI boot a poté v případě MBR disku doporučuji zkontrolovat zda je zelená tečka u BOOT PART). Záloha se provádí přes "Local Windows Installations/Capture Wim" - vyjímky se mohou přidat do "WimScript.ini". Možné řešení chyb
<br/>
-vložené ISO hlásí "No Windows Source Detected" nebo "Windows Source invalid" (rozbalit ISO a vložit instalační soubor - měl by se jmenovat "install" a být ve složce "sources" - zbývající obsah ISO je pro instalaci zbytečný a stejně nebude použit)
<br/>
-test (7-Zip) nově vytvořené zálohy najde chyby (HDD - poškozené sektory), (CPU+RAM - vypnout kompresi při vytváření zálohy)
<br/>
-obnova systému se může provést i rozbalením na disk (7-Zip) a nakonec případně opravit boot 
(BootICE)

***WinToUSB*** - tweak (v programu je to nazvané jako "konverze", ale jedná se jen o drobnou změnu v registru čímž se změní pořadí načítaných ovladačů při bootu) Win10+ díky kterému se dá systém spouštět i z externích médií přes USB = jeden systém se všemi programy+nastavením, který jde spustit na "jakémkoli" PC přes interní i externí disk (chybějící USB ovladače nebo IDE/AHCI mód atd. můžou být problém i když ne neřešitelný). Alternativa WinToUSB je úprava "BootDriverFlags" ```HKLM\SYSTEM\HardwareConfig\XXX``` na 0x14

***GImageX*** - tvorba WIM image (Windows v jednom komprimovaném souboru - bootovací nebo pro kompletní zálohu systému). Capture/Apply/Mount

***Link Shell Extension+NTFSLinksView*** - NTFS linky*0 a přesměrování např. nastavení programů do vlastních složek. Ovládání přes kontextovou nabídku - vybrat zdroj (nové umístění) / vložit jako (původní umístění)

***Driver Booster for Steam*** - aktualizace ovladačů

***Display Driver Uninstaller*** - odinstalování audio/video ovladačů, ***Device Remover*** - možné zásadní zrychlení spuštění "Správce zařízení" (záleží kolika PC/komponenty systém prošel)

***7+ Taskbar Tweaker+WinaeroTweaker+ExplorerPatcher+WinPaletter+Classic Color Panel*** ```HKCU\Control Panel\Colors``` - úprava uživatelského rozhraní Windows

***Pazera Free Audio Extractor, MKVToolNix*** - úprava videosouborů bez nutnosti konverze.  Odstraňování/extrahování audiostop, podrobné informace o audio/video souborech, ...

***Subtitle Edit*** - úprava titulků

***UniFlash*** (Rainbow Software) - MS-DOS program na uložení/obnovení CMOS paměti biosu (nastavení) do souboru. Na novějším HW možná už nefunkční (AM3+ +)

***NetSpeedMonitor*** - monitoring rychlosti a objemu stažených dat+historie, tray

***AIDA64*** - podrobné informace o PC

***Prime95+Furmark*** - test životnosti+stability PC (power virus)

***WinRAR*** - archivace dat s možností přidání záznamu na jejich opravu

***Inno Setup XDELTA Patch Maker, Patch Maker*** (Clickteam) - ideální třeba pro vytvoření patche s češtinou do hry, ze které "nejde" překlad vytáhnout (chybějící nástroje a různě chráněná herní data nebo překlad ve spouštěcích souborech atd.) - velikost takového patche je běžně o 70-99% menší než celá "warez" verze hry (a sdílení takového patche je pochopitelně i daleko jednodušší a méně ošemetné). Pokud překlad vyžaduje i svoje konkrétní DLL+EXE+... soubory a vytvářený patch bude zamýšlený pro digitálně prodávanou hru, tak je dobré tyto soubory z cíle (např. STEAM verze) dočasně odebrat (tím při patchování dojde k obyčejnému zkopírování zdrojových souborů do cíle bez ohledu na jejich verzi) = tyto soubory mají běžně velikost maximálně pár desítek MB a jdou dobře komprimovat, takže "patch" způsob by celkově přinesl úsporu dat pouze v rámci jednotek MB, ale pokud by se v cílové verzi v budoucnu změnil jediný bit (a že je to u digitálních produktů daleko pravděpodobnější/jednodušší než že dojde k úpravě samotných velkých herních dat), tak bude celý patch nefunkční

***WizTree*** - analýza místa na disku

***ImDisk Toolkit*** - ramdisk

***Primo Ramdisk*** - možnost stránkovacího souboru v ramdisku nebo využít nepřístupnou část RAM paměti (Invisible Memory) - např. 32-Bit Win má limit ~4GB

***Mem Reduct*** - uvolnění RAM paměti bez ukončení procesů klávesovou zkratkou nebo klikem na tray ikonu. Může ale docházet k většímu zápisu do stránkovacího souboru = opotřebení SSD*1

***RimhillEx*** - omezení rychlosti čtení CD/DVD

***PortableWinCDEmu*** - virtuální mechanika

***MiniTool Partition Wizard*** - může se hodit k FAT32 zformátování exFAT mSDXC karty (pokud je např. starý telefon nepodporuje)

***Hard Disk Sentinel*** - monitoring disků+historie, S.M.A.R.T. testy, regulace hlučnosti (AAM), tray ikony (zdraví), možnost zakázání vypínání HDD při nečinnosti (aut. přístupem nebo APM)

***HDD Regenerator*** - oprava poškozených sektorů na HDD bez ztráty dat (Win/MS-DOS)

***ISOBuster*** - záchrana dat

***Total Commander*** - rychlá/efektivní náhrada Průzkumníka/Plochy/NabídkyStart se spoustou funkcí navíc (vnitřní přidružení souborů včetně ikon, porovnání souborů podle obsahu, změna atributů, kopírování cest k datům do schránky, zobrazit/skrýt určité soubory/složky, kopírování souborů jenom s určitým datem se zachováním adresářové struktury, ověření nakopírovaných dat kvůli jejich případnému poškození, ... = nižší stovky klávesových zkratek). Pár užitečných "wincmd.ini" tweaků (první 2 jsou velmi důležité a moc nechápu, že program tak není nastaven v základu - první zrychlí/zpřehlední např. vyhledávání dat tím, že ignoruje NTFS linky = vyhledává data jak jsou zapsaná na disku a neukazuje "falešné duplikáty". Druhý kopíruje/přesunuje NTFS linky jako linky a ne jako soubory/složky)
<br/>
```IgnoreLinks=8```
<br/>
```CopyLinks=1```
<br/>
```DriveBarHide=DC```
<br/>
```RestrictInterface=3```
<br/>
```EditWaitTime=-1```
<br/>
```UseIniInProgramDir=1```
<br/>
```pluginbasedir=%COMMANDER_PATH%\plugins```
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

***System Explorer*** - náhrada "Správce úloh" - možnost uložit prioritu/afinitu aplikací pro jejich automatické nastavení při dalším spuštění. ***Process Hacker*** 

***Battle Encoder Shirasé*** - omezení (throttling) procesů - až 99%. Možnost používat přes Command-Line bez UI

***Registry Workshop*** - pokročilá náhrada výchozího "Regedit". Load Hive slouží pro načtení externího registru - je možné ho upravovat. Integrace s programem ***Total Uninstall*** se v jeho nastavení provede tímto příkazem (příklad) -
<br/>
```"c:\Registry Workshop\RegWorkshopX64.exe" /g```

***Notepad++*** - pokročilý poznámkový blok

***HEXelon Max 6*** - kalkulačka se třemi nezávislými "panely"

***FastStone Image Viewer*** - jednoduchý/rychlý prohlížeč obrázků

***SumatraPDF*** - rychlý prohlížeč PDF. Možnost skrytí veškerého UI

***Screen Ruler*** (Bluegrams) - pravítko

***NAPS2*** - skenování, export do PDF, OCR

***ATI GPU Scaling Fix, RadeonMod, HDD Low Level Format Tool, KMPlayer***  (32bit - kvůli asi nejlepší normalizaci hlasitosti a 64 bit)+desítky aplikací od NirSoft (***AppCrashView/BlueScreenView/Wireless Network Watcher/WifiInfoView/CurrPorts/FullEventLogView/ShellExView/ShellMenuView/OpenWithView/LoadedDllsView/DiskCountersView*** *1)

***VMware Workstation*** (15) - možnost používat např. Steam klient při spuštěném Win7 (od roku 2024 hrozí obecně umělý zákaz přístupu z tohoto "nebezpečného" systému - viz některé banky, možné řešení=responzivní mód v prohlížeči) ve virtuálním stroji s novějším systémem (třeba Win11). Podpora připojení (přemostění) k internetu (router může vyřešit případné problémy s připojením) a možnost sdílení složek - host/guest (např. pro přímé stahování her z Win11 do Win7). Pro plnou funkčnost je třeba po instalaci systému (běžné ISO) v VMware připojit na virtuální mechaniku ISO s ovladači (VMware Tools) a nainstalovat je. 7-Zip umí otevřít VMDK soubor se systémem

***Process Monitor+FileActivityWatch*** - aktivity spuštěných procesů - detailní seznam přístupů na SSD/registru/sítě

***KernelEX/One-Core-API/Extended Kernel for Windows Vista/VxKex*** - možnost spustit novější aplikace v nepodporovaném systému (compatiblity layer). Třeba Firefox 52 (2017) ve Win98 

***HxD+CFF Explorer+Resource Hacker*** - úpravy spustitelných souborů a jiné

***Změna písmen disků přes registr*** ```HKLM\SYSTEM\MountedDevices```

***GodMode.{ED7BA470-8E54-465E-825C-99712043E01C}*** - vytvoření složky s tímto názvem a její otevření přes Průzkumník otevře okno s veškerými ovládacími panely

***Microsoft Management Console*** (MMC) - přidání vlastních modulů do jedné MMC konzole. Postup - spustit/mmc/přidat nebo odebrat moduly snap-in/vybrat moduly/uložit

```c:\Windows\System32\Robocopy.exe "c:\1" "e:\1" /E /PURGE /w:0 /r:0 /MOT:10```
<br/>
Automatická synchronizace dvou složek. ```c:\1``` je zdrojová složka a ```e:\1``` je záloha. Pokud dojde ve zdrojové složce k vytvoření/změně souboru/složky, tak se nakopíruje do zálohy. Pokud dojde ve zdrojové složce ke smazání souboru/složky, tak se smaže ze zálohy. "MOT:10" označuje 10 minut čekání a poté následuje synchronizace. Jedná se o synchronizaci (porovnání) a ne "smazat celou zálohu/nakopírovat celý zdroj", takže mimo jiné nesnižuje životnost SSD zbytečnými zápisy. Malá nevýhoda je, že nedochází k porovnání souborů podle obsahu, ale pouze pomocí atributů+velikostí (rychlé/nenáročné). Je možné zavřít okno konzole ukončením procesu "conhost.exe" a nechat zapnutý pouze "ROBOCOPY.exe" (automatická synchronizace v pozadí systému). Užitečné v kombinaci s NTFS linky pro automatické zálohování SAVEGAME

***T-Clock*** - pokročilá náhrada výchozích tray hodin. Program s desítky let dlouhou historií a několika autory = možnosti nastavení a rozsah funkcí (které ani s hodinami nesouvisí) je nebývalý

⚠️

Vynucené (Please use EA App to continue) nahrazení aplikace ***Origin Bloatware*** jejím nástupcem ***EA App Malware***. Manuál pro instalaci/spuštění v roce 2023 (Win7)
<br/>
-nic neříkající chyba INST-14-12029 - instalátor se nemůže připojit k internetu - aneb proč použít ke stahování dat hlavní spouštěcí soubor (který si whitelistnu ve firewallu), když může potají rozbalit spoustu jiných v pozadí. A nabídnout offline instalátor je samozřejmě úplný nesmysl
<br/>
-po vyřešení následuje nic neříkající chyba INST-14-5 - v mém případě instalátor vyžaduje přístup do run/runonce klíčů v registru - zřejmě aby tam potají přidal hodnotu na formátování SSD při dalším spuštění PC
<br/>
-po vyřešení následuje nic neříkající chyba INST-21-32 - EA instalátor (hádám že ne samotný MSI instalátor stažený "někam" na SSD) odmítá rozbalit data do ramdisku (do výchozích i když trošku upravených TEMP/TMP cest)
<br/>
-po vyřešení a konečně už spuštění EA App Malware následuje nic neříkající černá obrazovka v knihovně vlastněných her (nemožnost cokoli instalovat) a vzkaz, že prý mám vydržet a problém se pokusí vyřešit. Ten vzkaz jsem vůbec nechápal a tak místo čekání na boží zásah jsem musel smazat složku "Origin" v "Users"
<br/>
Problémů ale může být o mnoho více a toto je jen malá ukázka

🟩1* English

***Total Uninstall*** - system scan (before/after application launch/installation) and display changes (files/folders/register), export registry changes to REG file for uninstallation

***MSI Afterburner+RTSS*** - screen overlay - time, HW monitoring, FPS/Frametime limit (hotkeys), Scanline Sync, tray icons

***dgVoodoo2*** - DX11/12 rendering (wrapper) for DX1-9 games, possibility to enlarge the interface of games at high resolutions (e.g. the resolution in the game is 1280x720 and through the program it is set to 1920x1080 = the interface will be as big as in 720p, but the resolution will be 1080p) and to force unsupported resolutions on the game. Since version 2.55+ (2018+) in combination with DX11+Radeon, a bug in the form of white textures may occur (since 2023+ versions the problem seems to have been solved). Right mouse click will access advanced options. To enable the wrapper, the necessary DLL files from the dgVoodoo2 subfolder must be copied to the (main) EXE file of the game and then configured (dgVoodooCpl.exe) to create a "dgVoodoo.conf" for the EXE file of the game

***ArgusMonitor, Speedfan*** - regulation of CPU+GPU+case fans speed and their curves+switching off

***AutoHotkey*** - automation/switches/scripts, custom hotkeys, double/short/long key/button press... One key/button can have hundreds of different functions written for each program individually (or its specific window - class/WinTitle) or one function globally for all

***ClickMonitorDDC*** - change monitor brightness/contrast/volume/on/off, tray icons; profiles - hotkeys. Works in games too

***PowerStrip*** - software change brightness/contrast/gamma - profiles - hotkeys. Works in games too (windowed/borderless seamless, but in fullscreen some games don't allow changes)

***Custom Resolution Utility*** - create a custom resolution and refresh rate for the monitor. Also ideal for bypassing the maximum resolution limit on old GPUs by lowering the refresh rate - e.g. 2560x1080x54Hz on Radeon HD 4670 (2008 - 1920x1200x60Hz)

***OverdriveNTool, AMD GPU Clock Tool*** - voltage/frequency for Radeon - profiles - shortcuts/hotkeys

***AmdMsrTweaker, ZenStates, PhenomMsrTweaker, BrazosTweaker*** - AMD K8 to Zen 2 CPUs ( 2003-2019) - voltage/frequency/multiplier - profiles - shortcuts/hotkeys

***AMD/ATI Pixel Clock Patcher*** - sign Radeon drivers after modifying GPU bios (rename to "atikmdag-patcher-bios.exe")

Switching ***Power Scheme*** (control panels) via hotkeys/shortcuts. Registry path ```HKLM\SYSTEM\ControlSet001\Control\Power\User\PowerSchemes``` command
<br/>
```C:\Windows\System32\powercfg.exe -setactive XXX```
<br/>
instead of XXX, write the name of the required key

***Equalizer APO+Peace*** - sound equalizer - by overwriting configuration files (also via hotkeys/shortcuts) it is possible to switch profiles in real time without starting the program. MS Visual C++ 2015-2022 can resolve a possible error when running "Configurator.exe"

***Raw Accel*** - detailed mouse settings, different axis sensitivity, etc. Profiles can also be switched via hotkeys/shortcuts ```c:\RawAccel\writer.exe c:\RawAccel\settings.json``` - changing the cursor when switching can be disabled by unifying them in the control panels (normal selection/background work)

***Mouse Settings Changer*** - switching mouse/touchpad sensitivity (control panels) even with a hotkeys - Autohotkey can be used to hide the popup window when switching profile - example for AltGr+F7
<br/>
```VKA5 & F7::Run, C:\MouseSC_x64.exe /Speed:6, , Hide```

***XInput Plus*** - detailed gamepad settings

***Comfort On-Screen Keyboard Pro*** - SW keyboard

***NirCmd+DevManView*** - change resolution+frequency, turn on/off HW+SW devices, ... - control via hotkeys/shortcuts

***IObit Unlocker*** - unlock (NTFS security or running process) files/folders

🚫update***EXE Radar Pro v3 (Beta)*** - when running an executable file (exe/msi/bat/...) a window will appear asking whether to run or exit it (user-defined Command-Line/whitelist/blacklist runs automatically in the background of the system). Verification via checksum

🚫***Easy File Locker*** - disable reading/writing/deleting/hiding files/folders. Locking only works when Windows+SYS driver program is running (can be turned on/off via hotkeys/shortcuts without running the program - NirCmd). If a program bypasses protection, it's NTFS links*0 (some paths unlocked)

🚫***NTFS Permissions Tools*** (DBC Studio) - data security management, bookmarks for quick access

🚫 Create a file instead of a folder

🚫***Firewall*** - Outpost/TinyWall/Firewall App Blocker

🚫***NSudo*** - run apps with the highest privileges. Combined with Autoruns it is easy to get rid of all MS bloatware (services/task schedulers/Defender/Edge/OneDrive/Slutana/...) ***ADB AppControl*** 

***Autoruns*** - automatically launched applications/libraries/drivers

❶***BootICE*** - create bootable media without formatting and data loss (MBR/PBR for HDD/SSD/USB), modify Windows BCD/UEFI files (multiboot, change system partition, ...), hide/activate partition

❷***Gandalf's Windows*** (Win7-11) - bootable (without formatting and losing data⬆️) from USB (even from phone - if supports boot from "bios") with internet capability, installing programs/drivers. More or less full system - but after reboot it returns to default settings

❸***WinNTSetup*** - install/backup/restore Windows without formatting and data loss and creating a bootable installation media (skipping the constantly erroneous/dangerous MS installation process = after copying the data and restarting the PC, the system starts). Iso/wim/swm/vhd (can also be used in ***7-Zip*** )+option to add drivers/tweaks. The process is not dependent on specific HW, so for example restoring a system backup can be done on any PC. It can also be installed on USB drives and at least Win11 can be started from them without any further modifications (the necessary drivers are loaded at boot, so it does not matter which PC it will be started on) - its meaningless requirements are ignored (UEFI/TPM/...) "Boot drive+Installation drive" can be the same partition of one disk (the program is preset for a regular user - just select the Windows edition, click "Setup+OK" and the process starts - at the end Bios+UEFI boot is automatically created and then in case of MBR disk I recommend checking if there is a green dot at BOOT PART). Backup is done via "Local Windows Installations/Capture Wim" - exceptions can be added to "WimScript.ini". Possible bug fixes
<br/>
-inserted ISO reports "No Windows Source Detected" or "Windows Source invalid" (unzip the ISO and insert the installation file - it should be called "install" and be in the "sources" folder - the rest of the ISO content is useless for installation and will not be used anyway)
<br/>
-test (7-Zip) of the newly created backup finds errors (HDD - damaged sectors), (CPU+RAM - turn off compression when creating a backup)
<br/>
-system recovery can also be done by extracting it to a disk (7-Zip) and finally repairing the boot if necessary
(BootICE)

***WinToUSB*** - tweak (in the program it's called "conversion", but it's just a small change in the registry, which changes the order of loaded drivers at boot) Win10+, thanks to which the system can be booted from external media via USB = one system with all programs + settings, which can be run on "any" PC via internal or external disk (missing USB drivers or IDE/AHCI mode, etc. can be a problem, although not unsolvable). An alternative to WinToUSB is to change "BootDriverFlags" ```HKLM\SYSTEM\HardwareConfig\XXX``` to 0x14

***GImageX*** - create WIM image (Windows in one compressed file - bootable or for complete system backup). Capture/Apply/Mount

***Link Shell Extension+NTFSLinksView*** - NTFS links*0 and redirecting e.g. program settings to custom folders. Control via context menu - select source (new location) / paste as (original location)

***Driver Booster for Steam*** - update drivers

***Display Driver Uninstaller*** - uninstall audio/video drivers, ***Device Remover*** - possible major speed up of "Device Manager" startup (depends on how many PCs/components the system has gone through)

***7+ Taskbar Tweaker+WinaeroTweaker+ExplorerPatcher+WinPaletter+Classic Color Panel*** ```HKCU\Control Panel\Colors``` - modifying the Windows user interface

***Pazera Free Audio Extractor, MKVToolNix*** - editing video files without conversion.  Removing/extracting audio tracks, detailed information about audio/video files, ...

***Subtitle Edit*** - edit subtitles

***UniFlash*** (Rainbow Software) - MS-DOS program to save/restore CMOS bios memory (settings) to a file. May not work on newer HW (AM3+ +)

***NetSpeedMonitor*** - monitoring of download/upload speed and data amount+history, tray

***AIDA64*** - detailed information about PC

***Prime95+Furmark*** - PC lifetime+stability test (power virus)

***WinRAR*** - data archiving with the possibility of adding a record to repair it

***Inno Setup XDELTA Patch Maker, Patch Maker*** (Clickteam) - create update files

***WizTree*** - disk space analysis

***ImDisk Toolkit*** - ramdisk

***Primo Ramdisk*** - option to page files in ramdisk or use inaccessible part of RAM (Invisible Memory) - e.g. 32-Bit Win has a limit of ~4GB

***Mem Reduct*** - free RAM memory without terminating processes by hotkey or clicking on the tray icon. However, there may be more writing to the paging file = reduced lifetime of SSD*1

***RimhillEx*** - CD/DVD read speed limitation

***PortableWinCDEmu*** - virtual drive

***MiniTool Partition Wizard*** - may be useful for FAT32 formatting of exFAT mSDXC cards (if e.g. old phone does not support them)

***Hard Disk Sentinel*** - disk monitoring+history, S.M.A.R.T. tests, noise control (AAM), tray icons (health), option to disable HDD shutdown when idle (auto access or APM)

***HDD Regenerator*** - repair corrupted sectors on HDD without data loss (Win/MS-DOS)

***ISOBuster*** - data rescue

***Total Commander*** - fast/efficient replacement of Explorer/Desktop/Start Menu with lots of extra features (internal file association including icons, file comparison by content, change attributes, copy data paths to clipboard, show/hide certain files/folders, copying files with certain date while preserving the directory structure, verifying the copied data for possible damage, ... = lower hundreds of hotkeys). A few useful "wincmd.ini" tweaks (the first 2 are very important and I don't understand that the program is not set up that way in the base - the first one speeds up/transparent e.g. data search by ignoring NTFS links = searches for data as written on the disk and doesn't show "false duplicates". The second copies/moves NTFS links as links and not as files/folders)
<br/>
```IgnoreLinks=8```
<br/>
```CopyLinks=1```
<br/>
```DriveBarHide=DC```
<br/>
```RestrictInterface=3```
<br/>
```EditWaitTime=-1```
<br/>
```UseIniInProgramDir=1```
<br/>
```pluginbasedir=%COMMANDER_PATH%\plugins```
<br/>
With the add-on ***DiskDir Extended*** you can create a data catalog (compress function - the LST file is like an archive and can be searched in it)
<br/>
-bulk renaming - remove characters (number) from start ```[N2-]``` from end ```[N1--2]```
<br/>
-mass removal of diacritics (find/replace)
<br/>
```á|č|ď|é|ě|í|ň|ó|ř|š|ť|ú|ů|ý|ž|Á|Č|Ď|É|Ě|Í|Ň|Ó|Ř|Š|Ť|Ú|Ů|Ý|Ž```
<br/>
```a|c|d|e|e|i|n|o|r|s|t|u|u|y|z|A|C|D|E|E|I|N|O|R|S|T|U|U|Y|Z```
<br/>
-find a CSS file that has somewhere in the name TAB - ```*tab*.css```

***System Explorer*** - replacement of "Task Manager" - possibility to save priority/affinity of applications for their automatic setting at next startup. ***Process Hacker*** 

***Battle Encoder Shirasé*** - process throttling - up to 99%. Ability to use via Command-Line without UI

***Registry Workshop*** - advanced replacement of the default "Regedit". Load Hive used to load external registry - can be edited. To integrate with ***Total Uninstall***, use the following command in its settings (example) -
<br/>
```"c:\Registry Workshop\RegWorkshopX64.exe" /g```

***Notepad++*** - advanced notepad

***HEXelon Max 6*** - calculator with three independent "panels"

***FastStone Image Viewer*** - simple/fast image viewer

***SumatraPDF*** - fast PDF viewer. Option to hide all UI

***Screen Ruler*** (Bluegrams) - ruler

***NAPS2*** - scan, export to PDF, OCR

***ATI GPU Scaling Fix, RadeonMod, HDD Low Level Format Tool, KMPlayer*** (32bit - due to probably the best volume normalization and 64 bit)+dozens of apps from NirSoft (***AppCrashView/BlueScreenView/Wireless Network Watcher/WifiInfoView/CurrPorts/FullEventLogView/ShellExView/ShellMenuView/OpenWithView/LoadedDllsView/DiskCountersView*** *1)

***VMware Workstation*** (15) - possibility to use e.g. Steam client while running Win7 (from 2024 there is a threat of arbitrary banning of access from this "dangerous" system - see some banks, possible solution=responsive mode in browser) in a virtual machine with a newer system (e.g. Win11). Support for internet connection (bridging) (router can solve possible connection problems) and the possibility of sharing folders - host/guest (e.g. for direct downloading of games from Win11 to Win7). For full functionality, after installing the system (regular ISO) in VMware, the ISO with drivers (VMware Tools) must be mounted on the virtual drive and installed.

***Process Monitor+FileActivityWatch*** - activities of running processes - detailed list of accesses on SSD/registry/network

***KernelEX/One-Core-API/Extended Kernel for Windows Vista/VxKex*** - ability to run newer applications on an unsupported system (compatiblity layer). For example Firefox 52 (2017) in Win98

***HxD+CFF Explorer+Resource Hacker*** - editing executables and more

***Changing drive letters via registry*** ```HKLM\SYSTEM\MountedDevices```

***GodMode.{ED7BA470-8E54-465E-825C-99712043E01C}*** - creating a folder with this name and opening it via Explorer opens a window with all control panels

***Microsoft Management Console*** (MMC) - add custom modules to a single MMC console. Procedure - run/mmc/add or remove snap-in modules/select modules/save

```c:\Windows\System32\Robocopy.exe "c:\1" "e:\1" /E /PURGE /w:0 /r:0 /MOT:10```
<br/>
Automatic synchronization of two folders. ```c:\1``` is the source folder and ```e:\1``` is the backup. If a file/folder is created/changed in the source folder, it is copied to the backup. If a file/folder is deleted in the source folder, it will be deleted from the backup. "MOT:10" indicates 10 minutes of waiting and then synchronization. Is it synchronization (comparison) and not "delete the entire backup/copy the entire resource", so it does not reduce the lifetime of the SSD with unnecessary writes, among other things. A small drawback is that there is no comparison of files by content, but only by attributes+size (fast/non-demanding). It is possible to close the console window by terminating the "conhost.exe" process and leave only "ROBOCOPY.exe" (automatic synchronization in the background of the system) on. Useful in combination with NTFS links for automatic SAVEGAME backup

***T-Clock*** - advanced replacement of the default tray clock. A program with decades of history and several authors = the possibilities of settings and range of functions (not even related to the clock) is unprecedented
<br/>
<br/>
<br/>
<br/>
<br/>
<br/>
<br/>
<br/>
<br/>
<br/>
🟧0* GAMES-JINE
<br/>
***Blood 2 - 1998*** - patch - 16:9 HOR+ widescreen, DX11/12 (2023-08 STEAM)
<br/>
https://github.com/hornster02/hornster02/raw/main/Blood_2_1998_patch.rar

***Cold War - 2005*** - cz crack - 16:9 widescreen (2018-08 Score 168)
<br/>
https://github.com/hornster02/hornster02/raw/main/Cold_War_2005_cz_crack_16-9_widescreen.rar

***Dusk 12 - 2007*** - patch (2023-07 STEAM)
<br/>
dusk.exe (při nastavení rozlišení 640x480 se hra spustí v 1920x1080 HOR+)
<br/>
audiere.dll (zřejmě vyřeší problém nespuštění hry - černá obrazovka - při zapnuté hudbě)
<br/>
hra.ahk (x-přepínač skrčení / CTRL+ALT+INS okamžitě ukončí hru) - Autohotkey
<br/>
https://github.com/hornster02/hornster02/raw/main/Dusk_12_2007_patch.rar

***Chaser - 2003*** - 21:9 widescreen (2020-07 STEAM)
<br/>
https://github.com/hornster02/hornster02/raw/main/Chaser_2003_21-9_widescreen.rar

***ToCA Race Driver 3 - 2006*** - 21:9 widescreen (2021-06 DVD)
<br/>
https://github.com/hornster02/hornster02/raw/main/ToCA_Race_Driver_3_2006_21-9_widescreen.rar

***UberSoldier - 2006*** - 21:9 widescreen (2020-03 Level 156)
<br/>
https://github.com/hornster02/hornster02/raw/main/UberSoldier_2006_21-9_widescreen.rar

***Vietcong 1+2 - 2003-2004-2005*** - 21:9 widescreen (2021-08 DVD)
<br/>
https://github.com/hornster02/hornster02/raw/main/Vietcong_1+2_2003-2004-2005_21-9_widescreen.rar

***You Are Empty - 2006*** - AMD postprocess fix (2017-11 Score 189)
<br/>
https://github.com/hornster02/hornster02/raw/main/You_Are_Empty_2006_AMD_postprocess_fix.rar

