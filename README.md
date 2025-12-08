# BlessedOS

## Zanim coś Ci się nie spodoba przeczytaj uważnie README dwa razy!

Fork wszystkim dobrze znanego oraz w pewnych kręgach lubianego systemu opracyjnego. 
Mowa oczywiście o M$ VV1nd0vvs. Z racji tego, że dziwnym trafem system ten należy do firmy, która posiada również
GitHub'a z wiadomych względów nie będe bezpośrednio używał słowa na W. Nie jest to modyfikacja pojedyńczej wersji
lecz cała seria moich modów a zawarte są w niej: XP'ek, 7, 8.1, 10 i 11. Poniżej bardziej szczegółowy opis każdej z wersji.
Kontakt z autorem (i naszym team'em): https://discord.gg/UgVxsKqZ

# BlessedOS 11
## Info od autora: póki 10 działa absolutnie kurvva odradzam używania 11 xD
Opis: Modyfikacja bzaująca na VV11 LT$C 2024 x64. System aktywuje się OFFLINE podczas instalacji przy użyciu skryptu od MA$$GRAVE.
Jako jest to wersja LT$C to już sama w sobie jest dosyć czysta. System otrzymuje tylko i wyłącznie aktualizacje bezpieczeństwa oraz krytyczne aktualizacje systemu i to Ty decydujesz czy i kiedy je zainstalować. Do systemu zintegrowałem parę przydatnych rzeczy, o których Bill zapomniał tj.: .NET Framework 3.5, Winget i kilka przydatnych skrótów na pulpicie. Dodałem także OpenShell czyli klasyczne menu start przypominające to z W7. System nie wymusza konta M$. Instalator z 11 zastąpiony tym z 10. Ma to na celu obejście sztucznych wymagań systemowych narzuconych przez M$ (TPM 2.0, 4GB RAM, 60GB HDD, UEFI). Jeśli instalujesz system na KVM/QEMU z listy dostępnych systemów wybierz W10. Systemu można spokojnie używać jak zwykłej 11 tyle tylko że jego instalacja nie jest upierdliwa i nie wymaga żadnych hack'ów. Standardowo polecam instalacje systemu na kompie niepodłączonym do neta.
## Wycięte/wyłączone:
* Tyle telemetrii ile tylko się dało,
* Wszystkie języki i układy klawiatur za wyjątkiem pl_PL oraz en_US (inne języki można łatwo dograć z poziomu ustawień),
* Superfetch - na dyskach HDD się sprawdzał, ale SSD niepotrzebnie żyłuje,
* Wyłączono "pagefile" - ten sam powód co wyżej,
* Rozmaite pliki cache, których i tak nie powinno być w czystym systemie, a które w razie potrzeby i tak się odbudują.
Dodatkowo w wersji Lite:
* Xbox,
* SFC,
* Update,
* Defender.

# Blessed 10
OpisL Mod bazujący na VV10 LT$C 2021 x64. Poza tym w większości to samo co 11 poza specyficznymi tweak'ami typowo dla 10. Jeśli chcesz korzystać z któregoś z tych modów na codzień to zalecam własnie tą wersję. Ja osobiście używam BlessedOS'a 10 Lite na dualboocie z pingwinem.
## Wycięte/wyłączone:
* Wszystko to co 11,
* Copilot.
Dodatkowo wersja Lite:
* Też to co w 11,
* Centrtum akcji (wyskakujące powiadomienia),
* Recovery.

# Blessed 8.1
Opis: Bazaowany na VV8.1 PRO x64 oraz x32. Wiadomo aktówka na OFFLINE z MA$$GRAVE'm. Zintegrowane wszystkie aktualizajce aż do zakończenia wsparcia oraz NET Framework 3.5. Klasyczne menu start przypominające to z W7.
## Wycięte/wyłączone:
* To samo co wcześniejsze systemy,
* Popup’y o aktualizacji do nowszej wersji systemu,

# Blessed 7
Opis: Baza - VV7 Profe$$ional x64 oraz x32. Zintegrowane wszystkie aktualizajce aż do zakończenia wsparcia oraz NET Framework 3.5. Przy instalacji wersji x32 wyskakuje jeden błąd nie mający wpływu na instalacje i należy go zignorować.
## Wycięte/wyłączone:
* I znowu to samo co w poprzednikach xD

# Blessed XP
Opis: Baza - VV XP Profe$$ional SP3 wersja 32bit'owa (x86). Zaimportowane wszystkie aktualizacje z wersji "Embedded POSReady", która była wspierana do 2019 roku. Nic nie wycinane - w XP'eku można wszystko powyłączać z poziomu systemu. Instalator z W7 więc można boot'ować z Ventoy'a czy Rufus'a.System podczas instalacji zrestartuje się kilka razy. Nic nie ruszać aż do pierwszego wprowadzenia! NETFX_4.8 wymaga doinstalowania OneCore API: https://github.com/shorthorn-project/One-Core-API-Binaries/releases/latest/download/one-core-api-pack-x86.zip
## Zintegrowane:
* Aktualizacje do 9 kwietnia 2019 r.
* .Net Framework 1.1-4.0 + pakiety językowe.
* Visual C++ 2005-2019 (aktualizacja 15.01.2021).
* DirectX 9c (aktualizacja czerwiec 2010).
* Internet Explorer 8.
* Media Player 11.
* Adobe Flash Player.
* Sterowniki dla AHCI/SATA.
* Certyfikaty główne zintegrowane do sierpnia 2022 r.
* Kilka tapet do jakości HD i dodano kilka oficjalnych motywów.
* Łatka kernela, która umożliwia wykrywanie RAM'u aż do 128GB.
