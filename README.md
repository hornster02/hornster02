***Češtiny do her (2014 a starší)*** https://github.com/hornster02?tab=repositories&q=&type=template&language=&sort=name
<br/>
<br/>
<br/>

🟨2* ***Autohotkey scripts***

<br/>
<br/>
<br/>

🟩1* ***Software for Windows. 🟦 PORTABLE - official or with the help of 🟦 7-Zip***

***Total Uninstall*** - sken systému (před/po spuštení/nainstalování aplikace) a zobrazení změn (soubory/složky/registr), export změn registru do REG souboru pro od/instalaci

***🟦 Inno Setup XDELTA Patch Maker, Patch Maker*** (Clickteam, zastaralé) - ideální třeba pro vytvoření patche s češtinou do hry, ze které "nejde" překlad vytáhnout (chybějící nástroje a různě chráněná herní data nebo překlad ve spouštěcích souborech atd.) - velikost takového patche je běžně o 70-99% menší než celá "warez" verze hry (a sdílení takového patche je pochopitelně i daleko jednodušší a méně ošemetné = nesourodé útržky dat nejsou warez). Pokud překlad vyžaduje i svoje konkrétní DLL+EXE+... soubory a vytvářený patch bude zamýšlený pro digitálně prodávanou hru, tak je dobré tyto soubory z cíle (např. STEAM verze) dočasně odebrat (tím při patchování dojde k obyčejnému zkopírování zdrojových souborů do cíle bez ohledu na jejich verzi = výsledný patch může být kompatibilní i s jinými verzemi typu GOG,MYABANDONWARE,...) = tyto soubory mají běžně velikost maximálně pár desítek MB a jdou dobře komprimovat, takže "patch" způsob by celkově přinesl úsporu dat pouze v rámci jednotek MB, ale pokud by se v cílové verzi v budoucnu změnil jediný bit (a že je to u digitálních produktů daleko pravděpodobnější/jednodušší než že dojde k úpravě samotných velkých herních dat), tak bude celý patch nefunkční. Pokud hra obsahuje stejné typy souborů lišící se v názvu nebo pokud jsou uložená v jiných složkách, tak pokud se tyto věci ručně sjednotí, tak výsledná velikost patche bude menší = nedojde pouze ke komprimaci celých dat, ale ke komprimaci rozdílných částí dat. Vytvořený patch bych zkusil aplikovat a pak porovnal data podle obsahu třeba v Total Commander (původní CZ verze/updatovaná EN-CZ verze) kvůli případné HW/SW chybě a tím pádem změněným=poškozeným datům (ale i před vytvářením patche je nejjistější metoda dvou nezávislých instalací stejné verze hry a porovnání dat). Spuštěný ISXPM vypadá strašně složitě, ale ve skutečnosti může patch vytvořit i naprostý laik (jediná menší komplikace ve vyjímečných případech může být nutnost CZ aktivovat přes nějaký klíč v registru nebo souborem mimo herní data) který si vystačí klidně i jen s řádky "Old version" a "Final version" - výše napsaná doporučení nejsou až tak důležitá, pokud člověk nelpí na univerzálnosti a co nejmenší velikosti patche
<br/>
***https://github.com/hornster02/hornster02/raw/main/_ISXPM-2.6.4.3-CONFIG-2024-03.rar*** - mnou nastavený konfigurační soubor (stačí ho jen načíst přes "LOAD PROJECT") zaměřený na ještě menší velikost patche oproti výchozímu nastavení (rozdíl může být až v desítkách %). Využití RAM paměti bude běžně mezi 10-20GB (nezáleží na počtu souborů, ale čím větší je soubor tím vyšší bude spotřeba RAM = 1GB soubor na obou stranách=cca 6GB RAM) - v případě nároků na RAM převyšující možnosti systému se může proces zpomalit a zároveň zachovat vysokou kompresi snížením počtu "Generating cores". "Compression" v sekci "Patch Options" je vypnutá - komprimuje nezpracované ne-XDELTA soubory (ISXPM v tomto ohledu zřejmě nepodporuje větší možnosti nastavení a ani ta nejvyšší "lzma2/ultra64" není dostatečně dobrá = vyšší komprese se dosáhne zabalením celého patche přes 7-Zip)
<img width="941" alt="Inno Setup XDELTA Patch Maker" src="https://github.com/hornster02/hornster02/assets/127822397/91d7745e-6dd3-4c06-a382-794fbe422488">


***🟦 ISO Directory v0.5***(Michel) - vytvoření mini-image CD/DVD (velikost pár kB) - např. pokud pro českou verzi hry neexistuje crack a hra trvá na vloženém fyzickém médiu v mechanice

***🟦 BikMod v0.3e (Beta) + 🟦 bink2-libass*** - modifikovaná "binkw32.dll" knihovna, pomocí které se mohou načíst externí SRT titulky. ***🟦 RADTools*** - úprava BIK/SMK video souborů

***MSI Afterburner+RTSS*** - překrytí obrazu - čas, HW monitoring, limit FPS/Frametime (klávesové zkratky), Scanline Sync, tray ikony. Omezením FPS se v některých hrách značně prodlouží nahrávací časy (jeden z nejhorších příkladů může být třeba Painkiller)

***🟦 dgVoodoo2*** - DX11/12 rendering (wrapper) pro DX1-9 hry, možnost zvětšení rozhraní her při vysokých rozlišeních (např. rozlišení ve hře je 1280x720 a přes program se nastaví 1920x1080 = rozhraní bude velké jako v 720p, ale rozlišení bude 1080p) a vnutit hře nepodporovaná rozlišení. Od verze 2.55+ (2018+) v kombinaci s DX11+Radeon může nastat bug v podobě bílých textur (u novějších verzí z roku 2023+ je problém zřejmě už vyřešený). Pravý klik myší zpřístupní pokročilé možnosti. Pro zapnutí wrapperu se musí potřebné DLL soubory z podsložky dgVoodoo2 nakopírovat k (hlavnímu) EXE souboru hry a pak nakonfigurovat (dgVoodooCpl.exe) čímž se u EXE souboru hry vytvoří "dgVoodoo.conf"

***🟦 4GB Patch*** - prolomení 2GB RAM limitu u 32-bit aplikací. Užitečné třeba u některých her (např. Gothic 3, který na limit narazí asi po 10-ti minutách) kdy se úpravou EXE souboru zvýší minimální FPS, o něco se zrychlí nahrávací časy a také při delším hraní nebude hrozit pád aplikace

***ArgusMonitor, Speedfan*** - regulace otáček ventilátorů CPU+GPU+skříně a jejich křivky+vypínání

***🟦 ClickMonitorDDC*** - změna jasu/kontrastu/hlasitosti/zapnutí/vypnutí monitoru, tray ikony; profily - klávesové zkratky. Funguje i ve hrách

***PowerStrip*** - softwarová změna jasu/kontrastu/gammy - profily - klávesové zkratky. Funguje i ve hrách (bezproblémový windowed/borderless, ale ve fullscreen některé hry změny neumožňují)
<br/>
https://entechtaiwan.com/util/ps.shtm
<br/>
https://github.com/hornster02/hornster02/raw/main/_PowerStrip_3.9-key.rar

***🟦 Custom Resolution Utility*** - vytvoření vlastního rozlišení a obnovovací frekvence monitoru. Ideální také pro obejití limitu maximálního rozlišení u starých GPU snížením obnovovací frekvence - např. 2560x1080x54Hz na Radeon HD 4670 (2008 - 1920x1200x60Hz). Nebo pokud Win při změně rozlišení nastavuje nižší Hz než monitor podporuje, tak pokud se v CRU u nativního rozlišení nastaví maximální podporovaná obnovovací frekvence, tak by i nižší rozlišení měli být automaticky nastavovány s maximální obnovovací frekvencí

***🟦 OverdriveNTool, 🟦 AMD GPU Clock Tool*** - napětí/frekvence pro Radeon - profily - klávesové zkratky/zástupce

***🟦 AmdMsrTweaker, 🟦 ZenStates, 🟦 PhenomMsrTweaker, 🟦 BrazosTweaker*** - AMD K8 (2003) až Zen 4 CPU - napětí/frekvence/násobič - profily - klávesové zkratky/zástupce

ATI/AMD GPU Bios - ***🟦 GPU-Z, 🟦 RBE - Radeon BIOS Editor, 🟦 VBE7, 🟦 Polaris Bios Editor PBE + 🟦 AMDVBFlash / ATI ATIFlash + 🟦 AMD/ATI Pixel Clock Patcher*** - podepsání Radeon ovladačů po úpravě biosu GPU  (přejmenovat na "atikmdag-patcher-bios.exe")

***🟦 RadeonMod,ATI Tray Tools*** (legacy) - náhrada za ATI/AMD Catalyst / Radeon Bloatware💩

Přepínání ***Schéma napájení*** (ovládací panely) přes klávesové zkratky/zástupce. Cesta v registru ```HKLM\SYSTEM\ControlSet001\Control\Power\User\PowerSchemes``` příkaz ve formátu
<br/>
```C:\Windows\System32\powercfg.exe -setactive XXX```
<br/>
místo XXX se napíše název potřebného klíče

***Equalizer APO+Peace*** - ekvalizér zvuku - přepsáním konfiguračních souborů (i přes klávesové zkratky/zástupce) je možné v reálném čase přepínat profily bez spouštění programu. MS Visual C++ 2015-2022 může vyřešit případnou chybu při spuštění "Configurator.exe"

***🟦 Raw Accel*** - detailní nastavení myši, různá citlivost os atd. Profily jde přepínat i přes klávesové zkratky/zástupce ```c:\RawAccel\writer.exe c:\RawAccel\settings.json``` - změna kurzoru při přepnutí se dá zakázat jejich sjednocením v ovládacích panelech (normální výběr/práce na pozadí)

***🟦 hidusbf*** - úprava taktů myši (polling rate - Hz) - přetaktování/podtaktování. Ideální pokud např. stará obskurní hra funguje jenom na některých myších. Pokud se nedaří přes "Setup.exe" nainstalovat ovladač (Install Service) a v kontextové nabídce u INF souboru není možnost instalace, tak další způsob instalace je tento příkaz (upravit cestu k INF)
<br/>
```RUNDLL32.EXE SETUPAPI.DLL,InstallHinfSection DefaultInstall 132 c:\hidusbf\hidusbf\DRIVER\HIDUSBF.INF```

***🟦 DIMR (Direct Input Mouse Rate)*** - ukazatel taktů myši

***🟦 Mouse Settings Changer*** - přepínání citlivosti myši/touchpadu (ovládací panely) třeba i klávesovou zkratkou - pro skrytí vyskakovacího okna při přepnutí profilu se může použít Autohotkey - příklad pro AltGr+F7
<br/>
```VKA5 & F7::Run, C:\MouseSC_x64.exe /Speed:6, , Hide```

***🟦 XInput Plus*** - detailní nastavení gamepadu

***Comfort On-Screen Keyboard Pro*** - SW klávesnice

***🟦 NirCmd+🟦 DevManView*** - změna rozlišení+frekvence, zapínání/vypínání HW+SW zařízení, ... - ovládání i přes klávesové zkratky/zástupce

***🟦 IObit Unlocker*** - odemknutí (NTFS zabezpečení nebo běžící proces) souborů/složek

🚫update***EXE Radar Pro v3 (Beta)*** - při spuštění spustitelného souboru (exe/msi/bat/...) se zobrazí okno s dotazem zda ho spustit nebo ukončit (uživatelem definovaný Command-Line/whitelist/blacklist probíhá automaticky v pozadí systému). Ověření přes kontrolní součet

🚫***Easy File Locker*** - zakázání čtení/zápisu/mazání/ skrytí souborů/složek. Zamknutí funguje jen když je spuštěný Windows+SYS ovladač programu (dá se zapínat/vypínat přes zástupce/klávesové zkratky bez nutnosti spouštět program - NirCmd). Pokud nějaký program obchází ochranu, tak za to můžou NTFS linky*0 (nezamknuté všechny cesty)

🚫***🟦 NTFS Permissions Tools*** (DBC Studio) - správa zabezpečení dat, záložky pro rychlý přístup

🚫Vytvoření souboru místo složky

🚫***Firewall***  - Outpost/TinyWall/Firewall App Blocker. Výchozí Win firewall má pravidla uložená zde
<br/>
```HKLM\SYSTEM\ControlSet\services\SharedAccess\Parameters\FirewallPolicy\FirewallRules```
<br/>
```HKLM\SYSTEM\ControlSet001\services\SharedAccess\Parameters\FirewallPolicy\FirewallRules```
<br/>
```HKLM\SYSTEM\ControlSet002\services\SharedAccess\Parameters\FirewallPolicy\FirewallRules```
<br/>
a zákaz svévolného přidávání vyjímek se snadno provede přidáním a úpravou oprávnění pro "Everyone" 

🚫***🟦 NSudo*** - spouštění aplikací s nejvyššími právy. V kombinaci i s programem Autoruns je snadné se zbavit veškerého MS bloatwaru (aktualizace/služby/plánovače úloh/Defender/Edge/OneDrive/Slutana/...)

***🟦 Autoruns*** - automaticky spouštěné aplikace/knihovny/ovladače

❶***🟦 BootICE*** - vytvoření bootovacího média bez formátování a ztráty dat (MBR/PBR pro HDD/SSD/USB), úprava Windows souborů BCD/UEFI (multiboot, změna systémové partition, ...), skrytí/aktivace partition

❷***🟦 Gandalf’s Windows*** (Win7-11) - spustitelný (bez formátování a ztráty dat⬆️) z USB (i z telefonu - pokud podporuje boot z "biosu") s možností internetu, instalování programů/ovladačů. Víceméně plnohodnotný systém - po restartu se ale vrací do výchozího nastavení

❸***🟦 WinNTSetup*** - instalace/záloha/obnovení Windows bez formátování a ztráty dat a vytváření bootovacího instalačního média (přeskočení věčně chybového/nebezpečného MS instalačního procesu = po nakopírování dat a restartu PC se spouští systém). Iso/wim/swm/vhd (dají se používat i v ***7-Zip*** )+možnost přidání ovladačů/tweaků. Proces není závislý na konkrétní HW, takže třeba obnovení zálohy systému jde provést na jakékoli PC. Jde instalovat i na USB disky a minimálně Win11 z nich jde bez dalších úprav spustit (potřebné ovladače se načítají při bootu, takže nezáleží na jakém PC se bude spouštět) - jeho nesmyslné požadavky jsou ignorovány (UEFI/TPM/...) "Boot drive+Installation drive" může být stejný oddíl jednoho disku (program je pro běžného uživatele přednastavený - stačí vybrat edici Windows, kliknout na "Setup+OK" a proces začíná - na konci se automaticky vytvoří Bios+UEFI boot a poté v případě MBR disku doporučuji zkontrolovat zda je zelená tečka u BOOT PART). Záloha se provádí přes "Local Windows Installations/Capture Wim" - vyjímky se mohou přidat do "WimScript.ini". Možné řešení chyb
<br/>
-vložené ISO hlásí "No Windows Source Detected" nebo "Windows Source invalid" (rozbalit ISO a vložit instalační soubor - měl by se jmenovat "install" a být ve složce "sources" - zbývající obsah ISO je pro instalaci zbytečný a stejně nebude použit)
<br/>
-test (7-Zip) nově vytvořené zálohy najde chyby (HDD - poškozené sektory), (CPU+RAM - vypnout kompresi při vytváření zálohy)
<br/>
-obnova systému se může provést i rozbalením na disk (7-Zip) a nakonec případně opravit boot 
(BootICE)

***WinToUSB*** - tweak (v programu je to nazvané jako "konverze", ale jedná se jen o drobnou změnu v registru čímž se změní pořadí načítaných ovladačů při bootu) Win10+ díky kterému se dá systém spouštět i z externích médií přes USB = jeden systém se všemi programy+nastavením, který jde spustit na "jakémkoli" PC přes interní i externí disk (chybějící USB ovladače nebo IDE/AHCI mód atd. můžou být problém i když ne neřešitelný). Alternativa WinToUSB je úprava "BootDriverFlags" ```HKLM\SYSTEM\HardwareConfig\XXX``` na 0x14

***🟦 GImageX*** - tvorba WIM image (Windows v jednom komprimovaném souboru - bootovací nebo pro kompletní zálohu systému). Capture/Apply/Mount

***Link Shell Extension+🟦 NTFSLinksView*** - NTFS linky*0 a přesměrování např. nastavení programů do vlastních složek. Ovládání přes kontextovou nabídku - vybrat zdroj (nové umístění) / vložit jako (původní umístění)

***🟦 Driver Booster for Steam*** - aktualizace ovladačů

***🟦 Display Driver Uninstaller*** - odinstalování audio/video ovladačů, ***Device Remover*** - možné zásadní zrychlení spuštění "Správce zařízení" (záleží kolika PC/komponenty systém prošel)

***🟦 7+ Taskbar Tweaker+WinaeroTweaker+ExplorerPatcher+🟦 WinPaletter+🟦 Classic Color Panel*** ```HKCU\Control Panel\Colors``` - úprava uživatelského rozhraní Windows

***🟦 Pazera Free Audio Extractor, 🟦 MKVToolNix*** - úprava videosouborů bez nutnosti konverze.  Odstraňování/extrahování audiostop, podrobné informace o audio/video souborech, ...

***🟦 Subtitle Edit*** - úprava titulků

***🟦 Video-subtitle-extractor (VSE)*** - OCR metoda automatického vytvoření titulků

***🟦 UniFlash*** (Rainbow Software) - MS-DOS program na uložení/obnovení CMOS paměti biosu (nastavení) do souboru. Na novějším HW možná už nefunkční (AM3+ +)

***🟦 NetSpeedMonitor*** - monitoring rychlosti a objemu stažených dat+historie, tray

***🟦 AIDA64*** - podrobné informace o PC

***🟦 Prime95+Furmark*** - test životnosti+stability PC (power virus)

***🟦 WinRAR*** - archivace dat s možností přidání záznamu na jejich opravu

***🟦 WizTree*** - analýza místa na disku

***ImDisk Toolkit*** - ramdisk

***Primo Ramdisk*** - možnost stránkovacího souboru v ramdisku nebo využít nepřístupnou část RAM paměti (Invisible Memory) - např. 32-Bit Win má limit ~4GB, Win11 Home 128GB

***🟦 Mem Reduct*** - uvolnění RAM paměti bez ukončení procesů klávesovou zkratkou nebo klikem na tray ikonu. Může ale docházet k většímu zápisu do stránkovacího souboru = opotřebení SSD*1

***RimhillEx*** - omezení rychlosti čtení CD/DVD

***🟦 PortableWinCDEmu*** - virtuální mechanika

***🟦 MiniTool Partition Wizard*** - může se hodit k FAT32 zformátování exFAT mSDXC karty (pokud je např. starý telefon nepodporuje)

***🟦 Hard Disk Sentinel*** - monitoring disků+historie, S.M.A.R.T. testy, regulace hlučnosti (AAM), tray ikony (zdraví), možnost zakázání vypínání HDD při nečinnosti (aut. přístupem nebo APM)

***HDD Regenerator*** - oprava poškozených sektorů na HDD bez ztráty dat (Win/MS-DOS)

***ISOBuster*** - záchrana dat

***🟦 Total Commander*** - rychlá/efektivní náhrada Průzkumníka/Plochy/NabídkyStart se spoustou funkcí navíc (vnitřní přidružení souborů včetně ikon, porovnání souborů podle obsahu, změna atributů, kopírování cest k datům do schránky, zobrazit/skrýt určité soubory/složky, kopírování souborů jenom s určitým datem se zachováním adresářové struktury, ověření nakopírovaných dat kvůli jejich případnému poškození, ... = nižší stovky klávesových zkratek). Pár užitečných "wincmd.ini" tweaků (první 2 jsou velmi důležité a moc nechápu, že program tak není nastaven v základu - první zrychlí/zpřehlední např. vyhledávání dat tím, že ignoruje NTFS linky = vyhledává data jak jsou zapsaná na disku a neukazuje "falešné duplikáty". Druhý kopíruje/přesunuje NTFS linky jako linky a ne jako soubory/složky)
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

***System Explorer*** - náhrada "Správce úloh" - možnost uložit prioritu/afinitu aplikací pro jejich automatické nastavení při dalším spuštění. ***🟦 Process Hacker*** 

***🟦 Battle Encoder Shirasé*** - omezení (throttling) procesů - až 99%. Možnost používat přes Command-Line bez UI - příklad 90% a 10% omezení pro 2 EXE soubory = BES v pozadí systému bude hledat spuštěné procesy a automaticky je omezí
<br/>
```c:\BES\BES.exe -J "C:\FileActivityWatch\FileActivityWatch.exe" 90 -m "c:\Deus Ex\System\DeusEx.exe" 10 -m```

***🟦 Registry Workshop*** - pokročilá náhrada výchozího "Regedit". Load Hive slouží pro načtení externího registru - je možné ho upravovat. Integrace s programem ***Total Uninstall*** se v jeho nastavení provede tímto příkazem (příklad) -
<br/>
```"c:\Registry Workshop\RegWorkshopX64.exe" /g```

***🟦 Notepad++*** - pokročilý poznámkový blok

***🟦 HEXelon Max 6*** - kalkulačka se třemi nezávislými "panely"

***🟦 FastStone Image Viewer*** - jednoduchý/rychlý prohlížeč obrázků

***🟦 SumatraPDF*** - rychlý prohlížeč PDF. Možnost skrytí veškerého UI

***🟦 Screen Ruler*** (Bluegrams) - pravítko

***🟦 NAPS2*** - skenování, export do PDF, OCR

***🟦 ATI GPU Scaling Fix(legacy), 🟦 HDD Low Level Format Tool*** a desítky aplikací od 🟦 NirSoft (***AppCrashView/BlueScreenView/Wireless Network Watcher/WifiInfoView/CurrPorts/FullEventLogView/ShellExView/ShellMenuView/OpenWithView/LoadedDllsView/DiskCountersView*** *1)

***VMware Workstation*** (15) - možnost používat např. Steam klient při spuštěném Win7 (od roku 2024 hrozí obecně umělý zákaz přístupu z tohoto "nebezpečného" systému - viz některé banky, možné řešení=responzivní mód v prohlížeči) ve virtuálním stroji s novějším systémem (třeba Win11). Podpora připojení (přemostění) k internetu (router může vyřešit případné problémy s připojením) a možnost sdílení složek - host/guest (např. pro přímé stahování her z Win11 do Win7). Pro plnou funkčnost je třeba po instalaci systému (běžné ISO) v VMware připojit na virtuální mechaniku ISO s ovladači (VMware Tools) a nainstalovat je. 7-Zip umí otevřít VMDK soubor se systémem

***🟦 Process Monitor+🟦 FileActivityWatch*** - aktivity spuštěných procesů - detailní seznam přístupů na SSD/registru/sítě

***KernelEX/One-Core-API/Extended Kernel for Windows Vista/VxKex*** - možnost spustit novější aplikace v nepodporovaném systému (compatiblity layer). Třeba Firefox 52 (2017) ve Win98 

***🟦 HxD+CFF Explorer+🟦 Resource Hacker*** - úpravy spustitelných souborů a jiné

***Změna písmen disků přes registr*** ```HKLM\SYSTEM\MountedDevices```

***GodMode.{ED7BA470-8E54-465E-825C-99712043E01C}*** - vytvoření složky s tímto názvem a její otevření přes Průzkumník otevře okno s veškerými ovládacími panely

***Microsoft Management Console*** (MMC) - přidání vlastních modulů do jedné MMC konzole. Postup - spustit/mmc/přidat nebo odebrat moduly snap-in/vybrat moduly/uložit

```c:\Windows\System32\Robocopy.exe "c:\1" "e:\1" /E /PURGE /w:0 /r:0 /MOT:10```
<br/>
Automatická synchronizace dvou složek. ```c:\1``` je zdrojová složka a ```e:\1``` je záloha. Pokud dojde ve zdrojové složce k vytvoření/změně souboru/složky, tak se nakopíruje do zálohy. Pokud dojde ve zdrojové složce ke smazání souboru/složky, tak se smaže ze zálohy. "MOT:10" označuje 10 minut čekání a poté následuje synchronizace. Jedná se o synchronizaci (porovnání) a ne "smazat celou zálohu/nakopírovat celý zdroj", takže mimo jiné nesnižuje životnost SSD zbytečnými zápisy. Malá nevýhoda je, že nedochází k porovnání souborů podle obsahu, ale pouze pomocí atributů+velikostí (rychlé/nenáročné). Je možné zavřít okno konzole ukončením procesu "conhost.exe" a nechat zapnutý pouze "ROBOCOPY.exe" (automatická synchronizace v pozadí systému). Užitečné v kombinaci s NTFS linky pro automatické zálohování SAVEGAME

***🟦 T-Clock*** - pokročilá náhrada výchozích tray hodin. Program s desítky let dlouhou historií a několika autory = možnosti nastavení a rozsah funkcí (které ani s hodinami nesouvisí) je nebývalý

***🟦 Desktop VLocker*** - uzamčení systému

Android - ***🟦 ADB AppControl, 🟦 ADB Explorer, ***🟦 APK-Info***
<br/>
<br/>
<br/>
<br/>
<br/>
<br/>

🟩1* English

***Total Uninstall*** - system scan (before/after application launch/installation) and display changes (files/folders/registry), export registry changes to REG file for un/install

***🟦 Inno Setup XDELTA Patch Maker, Patch Maker*** (Clickteam) - create a patch

***🟦 ISO Directory v0.5***(Michel) - create a mini-image (crack) CD/DVD (size a few kB)

***🟦 BikMod v0.3e (Beta) + 🟦 bink2-libass*** - modified "binkw32.dll" library, which can be used to load external SRT subtitles. 🟦 RADTools - modification of BIK/SMK video files

***MSI Afterburner+RTSS*** - screen overlay - time, HW monitoring, FPS/Frametime limit (hotkeys), Scanline Sync, tray icons. Limiting FPS will significantly increase loading times in some games (Painkiller being one of the worst examples)

***🟦 dgVoodoo2*** - DX11/12 rendering (wrapper) for DX1-9 games, possibility to enlarge the interface of games at high resolutions (e.g. the resolution in the game is 1280x720 and through the program it is set to 1920x1080 = the interface will be as big as in 720p, but the resolution will be 1080p) and force unsupported resolutions into the game. Since version 2.55+ (2018+) in combination with DX11+Radeon, a bug in the form of white textures may occur (since 2023+ versions the problem seems to have been solved). Right mouse click will access advanced options. To enable the wrapper, the necessary DLL files from the dgVoodoo2 subfolder must be copied to the (main) EXE file of the game and then configured (dgVoodooCpl.exe) to create a "dgVoodoo.conf" for the EXE file of the game

***🟦 4GB Patch*** - breaking the 2GB RAM limit for 32-bit applications. Useful for some games (e.g. Gothic 3, which hits the limit after about 10 minutes) where modifying the EXE file will increase the minimum FPS, speed up loading times and also prevent the application from crashing when playing for a longer time

***ArgusMonitor, Speedfan*** - regulation of CPU+GPU+case fans speed and their curves+switching off

***🟦 ClickMonitorDDC*** - change monitor brightness/contrast/volume/on/off, tray icons; profiles - hotkeys. Works in games too

***PowerStrip*** - software change brightness/contrast/gamma - profiles - hotkeys. Works in games too (windowed/borderless seamless, but in fullscreen some games don't allow changes)
<br/>
https://entechtaiwan.com/util/ps.shtm
<br/>
https://github.com/hornster02/hornster02/raw/main/_PowerStrip_3.9-key.rar

***🟦 Custom Resolution Utility*** - create a custom resolution and refresh rate for the monitor. Also ideal for bypassing the maximum resolution limit on old GPUs by lowering the refresh rate - e.g. 2560x1080x54Hz on Radeon HD 4670 (2008 - 1920x1200x60Hz). Or if Win sets a lower Hz than the monitor supports (when changing the resolution), then if the maximum supported refresh rate is set in CRU for the native resolution, then even lower resolutions should be automatically set with the maximum refresh rate

***🟦 OverdriveNTool, 🟦 AMD GPU Clock Tool*** - voltage/frequency for Radeon - profiles - shortcuts/hotkeys

***🟦 AmdMsrTweaker, 🟦 ZenStates, 🟦 PhenomMsrTweaker, 🟦 BrazosTweaker*** - AMD K8 (2003) to Zen 4 CPUs - voltage/frequency/multiplier - profiles - shortcuts/hotkeys

ATI/AMD GPU Bios - ***🟦 GPU-Z, 🟦 RBE - Radeon BIOS Editor, 🟦 VBE7, 🟦 Polaris Bios Editor PBE + 🟦 AMDVBFlash / ATI ATIFlash + 🟦 AMD/ATI Pixel Clock Patcher*** - sign Radeon drivers after modifying GPU bios (rename to "atikmdag-patcher-bios.exe")

***🟦 RadeonMod,ATI Tray Tools*** (legacy) - ATI/AMD Catalyst / Radeon Bloatware💩 replacement

Switching ***Power Scheme*** (control panels) via hotkeys/shortcuts. Registry path ```HKLM\SYSTEM\ControlSet001\Control\Power\User\PowerSchemes``` command
<br/>
```C:\Windows\System32\powercfg.exe -setactive XXX```
<br/>
instead of XXX, write the name of the required key

***Equalizer APO+Peace*** - sound equalizer - by overwriting configuration files (also via hotkeys/shortcuts) it is possible to switch profiles in real time without starting the program. MS Visual C++ 2015-2022 can resolve a possible error when running "Configurator.exe"

***🟦 Raw Accel*** - detailed mouse settings, different axis sensitivity, etc. Profiles can also be switched via hotkeys/shortcuts ```c:\RawAccel\writer.exe c:\RawAccel\settings.json``` - changing the cursor when switching can be disabled by unifying them in the control panels (normal selection/background work)

***🟦 hidusbf*** - mouse polling rate (Hz) adjustment - overclocking/underclocking. Ideal if e.g. an old obscure game works only on some mice. If you can't install the driver via "Setup.exe" (Install Service) and there is no installation option in the context menu of the INF file, the other way to install is this command (edit INF path)
<br/>
```RUNDLL32.EXE SETUPAPI.DLL,InstallHinfSection DefaultInstall 132 c:\hidusbf\hidusbf\DRIVER\HIDUSBF.INF```

***🟦 DIMR (Direct Input Mouse Rate)*** - mouse polling rate (Hz) monitor

***🟦 Mouse Settings Changer*** - switching mouse/touchpad sensitivity (control panels) even with a hotkeys - Autohotkey can be used to hide the popup window when switching profile - example for AltGr+F7
<br/>
```VKA5 & F7::Run, C:\MouseSC_x64.exe /Speed:6, , Hide```

***🟦 XInput Plus*** - detailed gamepad settings

***Comfort On-Screen Keyboard Pro*** - SW keyboard

***🟦 NirCmd+🟦 DevManView*** - change resolution+frequency, turn on/off HW+SW devices, ... - control via hotkeys/shortcuts

***🟦 IObit Unlocker*** - unlock (NTFS security or running process) files/folders

🚫update***EXE Radar Pro v3 (Beta)*** - when running an executable file (exe/msi/bat/...) a window will appear asking whether to run or exit it (user-defined Command-Line/whitelist/blacklist runs automatically in the background of the system). Verification via checksum

🚫***Easy File Locker*** - disable reading/writing/deleting/hiding files/folders. Locking only works when Windows+SYS driver program is running (can be turned on/off via hotkeys/shortcuts without running the program - NirCmd). If a program bypasses protection, it's NTFS links*0 (some paths unlocked)

🚫***🟦 NTFS Permissions Tools*** (DBC Studio) - data security management, bookmarks for quick access

🚫Create a file instead of a folder

🚫***Firewall*** - Outpost/TinyWall/Firewall App Blocker. The default Win firewall has rules stored here
<br/>
```HKLM\SYSTEM\ControlSet\services\SharedAccess\Parameters\FirewallPolicy\FirewallRules```
<br/>
```HKLM\SYSTEM\ControlSet001\services\SharedAccess\Parameters\FirewallPolicy\FirewallRules```
<br/>
```HKLM\SYSTEM\ControlSet002\services\SharedAccess\Parameters\FirewallPolicy\FirewallRules```
<br/>
and the forbidding of arbitrarily adding exceptions is easily done by adding and modifying the permissions for "Everyone"

🚫***🟦 NSudo*** - run apps with the highest privileges. Combined with Autoruns it is easy to get rid of all MS bloatware (updates/services/task schedulers/Defender/Edge/OneDrive/Slutana/...) 

***🟦 Autoruns*** - automatically launched applications/libraries/drivers

❶***🟦 BootICE*** - create bootable media without formatting and data loss (MBR/PBR for HDD/SSD/USB), modify Windows BCD/UEFI files (multiboot, change system partition, ...), hide/activate partition

❷***🟦 Gandalf's Windows*** (Win7-11) - bootable (without formatting and losing data⬆️) from USB (even from phone - if supports boot from "bios") with internet capability, installing programs/drivers. More or less full system - but after reboot it returns to default settings

❸***🟦 WinNTSetup*** - install/backup/restore Windows without formatting and data loss and creating a bootable installation media (skipping the constantly erroneous/dangerous MS installation process = after copying the data and restarting the PC, the system starts). Iso/wim/swm/vhd (can also be used in ***7-Zip*** )+option to add drivers/tweaks. The process is not dependent on specific HW, so for example restoring a system backup can be done on any PC. It can also be installed on USB drives and at least Win11 can be started from them without any further modifications (the necessary drivers are loaded at boot, so it does not matter which PC it will be started on) - its meaningless requirements are ignored (UEFI/TPM/...) "Boot drive+Installation drive" can be the same partition of one disk (the program is preset for a regular user - just select the Windows edition, click "Setup+OK" and the process starts - at the end Bios+UEFI boot is automatically created and then in case of MBR disk I recommend checking if there is a green dot at BOOT PART). Backup is done via "Local Windows Installations/Capture Wim" - exceptions can be added to "WimScript.ini". Possible bug fixes
<br/>
-inserted ISO reports "No Windows Source Detected" or "Windows Source invalid" (unzip the ISO and insert the installation file - it should be called "install" and be in the "sources" folder - the rest of the ISO content is useless for installation and will not be used anyway)
<br/>
-test (7-Zip) of the newly created backup finds errors (HDD - damaged sectors), (CPU+RAM - turn off compression when creating a backup)
<br/>
-system recovery can also be done by extracting it to a disk (7-Zip) and finally repairing the boot if necessary
(BootICE)

***WinToUSB*** - tweak (in the program it's called "conversion", but it's just a small change in the registry, which changes the order of loaded drivers at boot) Win10+, thanks to which the system can be booted from external media via USB = one system with all programs + settings, which can be run on "any" PC via internal or external disk (missing USB drivers or IDE/AHCI mode, etc. can be a problem, although not unsolvable). An alternative to WinToUSB is to change "BootDriverFlags" ```HKLM\SYSTEM\HardwareConfig\XXX``` to 0x14

***🟦 GImageX*** - create WIM image (Windows in one compressed file - bootable or for complete system backup). Capture/Apply/Mount

***Link Shell Extension+🟦 NTFSLinksView*** - NTFS links*0 and redirecting e.g. program settings to custom folders. Control via context menu - pick link source (new location) / drop as (original location)

***🟦 Driver Booster for Steam*** - update drivers

***🟦 Display Driver Uninstaller*** - uninstall audio/video drivers, ***Device Remover*** - possible major speed up of "Device Manager" startup (depends on how many PCs/components the system has gone through)

***🟦 7+ Taskbar Tweaker+WinaeroTweaker+ExplorerPatcher+🟦 WinPaletter+🟦 Classic Color Panel*** ```HKCU\Control Panel\Colors``` - modifying the Windows user interface

***🟦 Pazera Free Audio Extractor, 🟦 MKVToolNix*** - editing video files without conversion.  Removing/extracting audio tracks, detailed information about audio/video files, ...

***🟦 Subtitle Edit*** - edit subtitles

***🟦 Video-subtitle-extractor (VSE)*** - OCR method of automatic subtitles creation

***🟦 UniFlash*** (Rainbow Software) - MS-DOS program to save/restore CMOS bios memory (settings) to a file. May not work on newer HW (AM3+ +)

***🟦 NetSpeedMonitor*** - monitoring of download/upload speed and data amount+history, tray

***🟦 AIDA64*** - detailed information about SW/HW

***🟦 Prime95+Furmark*** - PC lifetime+stability test (power virus)

***🟦 WinRAR*** - data archiving with the possibility of adding a "recovery record"

***🟦 WizTree*** - disk space analysis

***ImDisk Toolkit*** - ramdisk

***Primo Ramdisk*** - option to page files in ramdisk or use inaccessible part of RAM (Invisible Memory) - e.g. 32-Bit Win has a limit of ~4GB, Win11 Home 128GB

***🟦 Mem Reduct*** - free RAM memory (without terminating processes) by hotkey or clicking on the tray icon. However, there may be more writing to the paging file = reduced lifetime of SSD*1

***RimhillEx*** - CD/DVD read speed limitation

***🟦 PortableWinCDEmu*** - virtual drive

***🟦 MiniTool Partition Wizard*** - may be useful for FAT32 formatting of exFAT mSDXC cards (if e.g. old phone does not support them)

***🟦 Hard Disk Sentinel*** - disk monitoring+history, S.M.A.R.T. tests, noise control (AAM), tray icons (health), option to disable HDD shutdown when idle (auto access or APM)

***HDD Regenerator*** - repair corrupted sectors on HDD without data loss (Win/MS-DOS)

***ISOBuster*** - data rescue

***🟦 Total Commander*** - fast/efficient replacement of Explorer/Desktop/Start Menu with lots of extra features (internal file association including icons, file comparison by content, change attributes, copy data paths to clipboard, show/hide certain files/folders, copying files with certain date while preserving the directory structure, verifying the copied data for possible damage, ... = lower hundreds of hotkeys). A few useful "wincmd.ini" tweaks (the first 2 are very important and I don't understand that the program is not set up that way in the base - the first one speeds up/transparent e.g. data search by ignoring NTFS links = searches for data as written on the disk and doesn't show "false duplicates". The second copies/moves NTFS links as links and not as files/folders)
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
With the add-on ***DiskDir Extended*** you can create a data catalog ("pack files" function - the LST file is like an archive and can be searched in it)
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

***System Explorer*** - replacement of "Task Manager" - possibility to save priority/affinity of applications for their automatic setting at next startup. ***🟦 Process Hacker*** 

***🟦 Battle Encoder Shirasé*** - process throttling - up to 99%. Ability to use via Command-Line without UI - example 90% and 10% restriction for 2 EXE files = BES will look for running processes in the background and automatically restrict them
<br/>
```c:\BES\BES.exe -J "C:\FileActivityWatch\FileActivityWatch.exe" 90 -m "c:\Deus Ex\System\DeusEx.exe" 10 -m```

***🟦 Registry Workshop*** - advanced replacement of the default "Regedit". "Load Hive" can be used to load and edit an external registry. To integrate with ***Total Uninstall***, use the following command in its settings (example) -
<br/>
```"c:\Registry Workshop\RegWorkshopX64.exe" /g```

***🟦 Notepad++*** - advanced notepad

***🟦 HEXelon Max 6*** - calculator with three independent "panels"

***🟦 FastStone Image Viewer*** - simple/fast image viewer

***🟦 SumatraPDF*** - fast PDF viewer. Option to hide all UI

***🟦 Screen Ruler*** (Bluegrams) - ruler

***🟦 NAPS2*** - scan, export to PDF, OCR

***🟦 ATI GPU Scaling Fix(legacy), 🟦 HDD Low Level Format Tool*** and dozens of apps from 🟦 NirSoft (***AppCrashView/BlueScreenView/Wireless Network Watcher/WifiInfoView/CurrPorts/FullEventLogView/ShellExView/ShellMenuView/OpenWithView/LoadedDllsView/DiskCountersView*** *1)

***VMware Workstation*** (15) - possibility to use e.g. Steam client while running Win7 (from 2024 there is a threat of arbitrary banning of access from this "dangerous" system - see some banks, possible solution=responsive mode in browser) in a virtual machine with a newer system (e.g. Win11). Support for internet connection (bridging) (router can solve possible connection problems) and the possibility of sharing folders - host/guest (e.g. for direct downloading of games from Win11 to Win7). For full functionality, after installing the system (regular ISO) in VMware, the ISO with drivers (VMware Tools) must be mounted on the virtual drive and installed. 7-Zip can open a VMDK file with the system

***🟦 Process Monitor+🟦 FileActivityWatch*** - activities of running processes - detailed list of accesses on SSD/registry/network

***KernelEX/One-Core-API/Extended Kernel for Windows Vista/VxKex*** - ability to run newer applications on an unsupported system (compatiblity layer). For example Firefox 52 (2017) in Win98

***🟦 HxD+CFF Explorer+Resource Hacker*** - editing executables and more

***Changing drive letters via registry*** ```HKLM\SYSTEM\MountedDevices```

***GodMode.{ED7BA470-8E54-465E-825C-99712043E01C}*** - creating a folder with this name and opening it via Explorer opens a window with all control panels

***Microsoft Management Console*** (MMC) - add custom modules to a single MMC console. Procedure - run/mmc/add or remove snap-in modules/select modules/save

```c:\Windows\System32\Robocopy.exe "c:\1" "e:\1" /E /PURGE /w:0 /r:0 /MOT:10```
<br/>
Automatic synchronization of two folders. ```c:\1``` is the source folder and ```e:\1``` is the backup. If a file/folder is created/changed in the source folder, it is copied to the backup. If a file/folder is deleted in the source folder, it will be deleted from the backup. "MOT:10" indicates 10 minutes of waiting and then synchronization. Is it synchronization (comparison) and not "delete the entire backup/copy the entire resource", so it does not reduce the lifetime of the SSD with unnecessary writes, among other things. A small drawback is that there is no comparison of files by content, but only by attributes+size (fast/non-demanding). It is possible to close the console window by terminating the "conhost.exe" process and leave only "ROBOCOPY.exe" (automatic synchronization in the background of the system) on. Useful in combination with NTFS links for automatic SAVEGAME backup

***🟦 T-Clock*** - advanced replacement of the default tray clock. A program with decades of history and several authors = the possibilities of settings and range of functions (not even related to the clock) is unprecedented

***🟦 Desktop VLocker***

Android - ***🟦 ADB AppControl, 🟦 ADB Explorer, ***🟦 APK-Info***
<br/>
<br/>
<br/>
<br/>
<br/>
<br/>
<br/>
<br/>
<br/>

🟨2* ***Autohotkey scripts https://github.com/hornster02/hornster02/raw/main/_Autohotkey_AHK-2023.rar***

AutoHotkey v1.1

-IMPORTANT - AHK file probably needs to be run via "AutoHotkeyU64.exe" and not via the default "AutoHotkey.exe" (error)

The AHK file in the archive can be opened in Notepad (or if Autohotkey is installed on the PC, it can be run as a regular EXE file). The script has no user interface (apart from the "WindowSpy" function). AHK contains a few functional scripts such as

-hold F12 - on/off borderless fullscreen (useful for games)

-hold F11 - prevents mouse cursor from moving outside the active window - switch (useful for games)

-hold F10 - pause/resume (suspend) foreground processes. Useful in case of running a program with high demands on PC performance - there will be a significant reduction in power consumption/temperature/noise. 98% of programs/games should work without issue - for the rest you can expect various errors or crashes. The script can be useful for example when playing games on battery = 1 key completely stops the game at 0FPS and there is no need to turn it off. Perhaps a better alternative is the "Battle Encoder Shirasé" program which solves possible problems by limiting up to 99%. 100% (suspend) does not bring anything extra in real use (except for complete stop of SSD/network activity). The other 3 options (disabled by default) are (hold F10 = pause foreground process / 2x press resume process) and (hold F10 = pause listed processes - background or foreground / 2x press resume process) and (hold F10 = pause/resume listed processes - background or foreground)

-Control Mouse with Keyboard (Num Lock) - movement including angled (1235), left+middle+right button including drag and drop and double click (789), wheeldown+up (46), cursor movement to three specified positions (0), 4th mouse button (.). Easy speed and acceleration adjustment

-left+middle mouse button - dragging the mouse (anywhere in the window, not just over the title bar) moves the window that is not maximized. No need to hold the middle button all the time. ESC returns the window to its original position. Many programs can be moved even in "fullscreen" mode (virtual PCs, image viewers, video players, ...)

-the "LWin" key (CTRL+F), hold shows the taskbar without the Start menu (must be set to autohide), double hides the taskbar

-menu key (CTRL+C) , hold (CTRL+V) , double (CTRL+A)

-pause key (ALT+F4) - if the "SC" and "VK" numbers correspond to your keyboard, then even games that have these keys "disabled" can be ended. Holding the key down for 2 seconds restarts the PC as standard (but regardless of the current work) Shutdown, 6 = "force"

-ALT+Shift - shrink the active window to half the screen and align it right or left or maximize it

-ALT+Ctrl - show desktop

-CTRL+ALT+INS - exit AutoHotkey processes

-ScrollLock - AUTOHOTKEY-WindowSpy. Hold ScrollLock (activate window to foreground), ESC (hide - AutoHotkeyU64.exe). When working with "WindowSpy" another "AutoHotkey.exe" process is not used

And disabled features serving more as a template

-0.3 second long hold "ě" key inserts "@" . Dozens of additional keys can easily be added, eliminating the need for time-consuming keyboard shortcuts

-change gamma/contrast/brightness/volume/mute/unmute/power plan/frequencies/voltages/mouse sensitivity/resolution/network/... Crouch+aim toggles for games (search for ```*01```). And also holding Printscreen key saves image to SSD. May require external programs - NirCmd/DevManView/MSIAfterburner/OverdriveNTool/RawAccel/MouseSettingsChanger/PowerStrip/ClickMonitorDDC/...

***ČEŠTINA***

AutoHotkey v1.1

-DŮLEŽITÉ - AHK soubor je zřejmě potřeba spustit přes "AutoHotkeyU64.exe" a ne přes výchozí "AutoHotkey.exe" (error)

AHK soubor v archivu se dá otevřít v poznámkovém bloku (nebo pokud je Autohotkey v PC nainstalován, tak rovnou spustit jako obyčejný EXE soubor). Skript nemá - kromě funkce "WindowSpy" - žádné uživatelské rozhraní. AHK obsahuje pár funkčních skriptů jako jsou

-podržení F12 zapne/vypne fullscreen - přepínač (užitečné pro hry)

-podržení F11 - zabrání kurzoru myši pohyb mimo aktivní okno - přepínač (užitečné pro hry)

-podržení F10 - pozastavení/pokračování (suspend) procesů v popředí. Užitečné v případě zapnutého programu s vysokými nároky na výkon PC - dojde k zásadnímu snížení spotřeby/teplot/hlučnosti. 98% programů/her by mělo fungovat bez problému - u zbytku se dá očekávat různá chybovost nebo rovnou pády. Skript se může hodit třeba při hraní na baterii = 1 klávesou se hra úplně zastaví na 0FPS a není nutné ji vypínat. Možná lepší alternativa je program "Battle Encoder Shirasé" který případné problémy řeší omezením do 99%. 100% (suspend) v reálu (kromě úplného zastavení SSD/síťové aktivity) nic navíc nepřináší. Další 3 varianty (ve výchozím stavu vypnuté) jsou (držet F10 = pozastavit proces v popředí / 2x stisknutí vrátí proces do chodu) a (držet F10 = pozastavit vypsané procesy - v pozadí nebo popředí / 2x stisknutí vrátí procesy do chodu) a (držet F10 = pozastavit/spustit vypsané procesy - v pozadí nebo popředí)

-ovládání myši klávesnicí (vypnout numerickou klávesnici) - pohyb včetně šikmého (1235), levé+prostřední+pravé tlačítko včetně možnosti Drag and drop a dvojkliku (789), kolečko dolu+nahoru (46), pohyb kurzoru do tří určených pozic (0), 4-té tlačítko myši (.). Snadná úprava rychlosti a akcelerace

-levé+prostřední tlačítko myši - tažením myši (kdekoli v okně, ne jenom přes title bar) se přesunuje okno které není maximalizované. Prostřední tlačítko se nemusí držet celou dobu. ESC vrátí okno na původní pozici. Spousta programů i ve "fullscreen" režimu může být přesunováno (virtuální PC, prohlížeče obrázků, přehrávače videí, ...)

-klávesa "LWin" provede "CTRL+F", dlouhé podržení zobrazí hlavní panel (taskbar) bez nabídky Start (musí být nastavený na autohide), dvojité stisknutí hlavní panel (taskbar) skryje

-klávesa menu (kontextové menu) provede "CTRL+C" , podržení provede "CTRL+V" , 2x stisknutí provede "CTRL+A"

-klávesa "pause" provede "ALT+F4" - pokud "SC" a "VK" čísla odpovídají vaší klávesnici, tak půjdou vypnout např. i hry, které mají tyto klávesy "zablokované". Podržení klávesy na 2 vteřiny standartně restartuje PC (ale bez ohledu na rozdělanou práci). Shutdown, 6 = "na sílu"

-ALT+Shift - zmenšit aktivní okno na polovinu obrazovky a zarovnat ho vpravo nebo vlevo nebo ho maximalizovat

-ALT+Ctrl - zobrazit plochu

-CTRL+ALT+INS - vypnout procesy AutoHotkey

-ScrollLock - AUTOHOTKEY-WindowSpy. Aktivovat okno do popředí držet "ScrollLock", zavřít "ESC" (AutoHotkeyU64.exe)

A vypnuté funkce sloužící spíše jako vzor

-0,3 vteřiny dlouhé podržení "ě" napíše "@" . Snadno se dají přidat desítky dalších kláves a díky tomu odpadne nutnost používat zdržující klávesové zkratky

-změnit gamma/kontrast/jas/hlasitost+zap+vyp/schéma napájení/frekvence/napětí/citlivost myši/rozlišení/síť/... A také přepínače skrčení+míření pro hry (vyhledej ```*01```). Držení printscreen uloží obrázek na SSD. Může vyžadovat externí programy - NirCmd/DevManView/MSIAfterburner/OverdriveNTool/RawAccel/MouseSettingsChanger/PowerStrip/ClickMonitorDDC/...
