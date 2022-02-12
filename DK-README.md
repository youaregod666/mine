Danish

## Mine Standalone has released!

Hej igen, kære ven. Tak fordi du er med os og støtter vores ideer gennem den lange udviklingscyklus. MineOS har endelig nået udgivelsesstadiet: nu er det et fuldstændig uafhængigt operativsystem med sit eget udviklings-API og vidunderlige [illustreret wiki](https://github.com/IgorTimofeev/MineOS/wiki) af dets brug.
Mine er et GUI-baseret operativsystem til Open Computers Minecraft-mod. Det har omfattende og kraftfulde tilpasningsevner samt et app-marked til at udgive dine kreationer blandt OS-fællesskabet.
Her er en liste over nogle få funktioner:

- Multitasking
- Dobbelt bufferet grafisk brugergrænseflade
- Sprogpakker og softwarelokalisering
- Flere brugerprofiler med adgangskodegodkendelse
- Egen EEPROM-firmware med funktioner til valg/formatering/omdøbning af bootvolumen og internetgendannelsestilstand
- Fildeling over det lokale netværk via modemer
- Klientforbindelser til rigtige FTP-servere
- En intern IDE med syntaksfremhævning og debugger
- Integreret applikation og bibliotek App Market med mulighed for at udgive dine egne scripts og programmer for hver Mine-bruger
- Fejlrapporteringssystem med mulighed for at sende information til udviklere
- Animationer, wallpapers, pauseskærme, farveskemaer og enorme tilpasningsmuligheder
- Open source system API og detaljeret illustreret dokumentation
- 
## hvordan installer man det?

Den nemmeste måde er at bruge standard **pastebin** script. Indsæt en OpenOS-diskette i computeren, indsæt et internetkort, tænd computeren og skriv følgende til konsollen for at installere Mine:

	pastebin run PnprU5XD

Du kan indsætte den på konsollen ved at bruge den midterste museknap eller indsæt-tasten (som standard). Hvis pastebin-metoden af en eller anden grund ikke er tilgængelig for dig (for eksempel er den sortlistet på spilserveren eller blokeret af internetudbyderen), skal du bruge en alternativ kommando til at downloade installationsprogrammet direkte fra Github-siden:

	wget -f https://raw.githubusercontent.com/youaregod666/mine/master/Installer/BIOS.lua /tmp/bios.lua && flash -q /tmp/bios.lua && reboot

Efter et øjeblik vil et godt systeminstallationsprogram blive vist. Du bliver bedt om at vælge dit foretrukne sprog, bootvolumen (kan formateres om nødvendigt), oprette en brugerprofil og tilpasse nogle indstillinger

## How to create applications and work with API?

[Wiki by IgorTimofeev](https://github.com/IgorTimofeev/MineOS/wiki)
