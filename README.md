# BlessedOS - work in progress

## Zanim coś Ci się nie spodoba przeczytaj uważnie README dwa razy!

Fork wszystkim dobrze znanego oraz w pewnych kręgach lubianego systemu opracyjnego. 
Mowa oczywiście o M$ VV1nd0vvs. Z racji tego, że dziwnym trafem system ten należy do firmy, która posiada również
GitHub'a - słowo na W będzie zastąpione słowem 'Binbows' z wiadomych względów. Nie jest to modyfikacja pojedyńczej wersji
lecz cała seria moich modów a zawarte są w niej: XP'ek, 7, 8.1, 10 i 11. Poniżej bardziej szczegółowy opis każdej z wersji.

# BlessedOS 11
Opis: Modyfikacja bzaująca na VV11 LT$C 2024. System aktywuje się OFFLINE podczas instalacji przy użyciu skryptu od MA$$GRAVE.
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
