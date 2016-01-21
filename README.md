# ![NOKO](http://www.nikolairadke.de/NOKO/noko_klein.png) NOKO

*Anythin sourcode-related, the circut diagrams and comments on how to compile are written in english, the building documentation is in german. Feel free to ask me for translatation, if you need help. NOKO itself speaks and writes in german. However, someday, he may learn english... contribute!
Requirements: The [Arduino IDE 1.6.6](https://www.arduino.cc/en/Main/OldSoftwareReleases#previous), i am planning to switch to 1.6.7 soon. Put The Folder NOKO_Arduino_NOKO/ into your sketch folder. Right now, NOKO.ino won't compile without changing the local platform.txt. See [HOWTO compile](https://github.com/NikolaiRadke/NOKO/tree/master/HOWTO_Compile) and change the file. Now NOKO.ino should compile.*

Das **NOKO Monster** zum Nachbauen und gern haben. Beschreibung und Anleitungen dazu im [Wiki](https://github.com/NikolaiRadke/NOKO/wiki). Jeder, der Lust hat, darf sich gerne beteiligen, ich bin für Vorschläge stets (Quell-)offen.

### Verzeichnisse

```
NOKO/
├── HOWTO_Compile/
|   Hinweise und angepasste plattform.txt für die Kompilierung in der Arduino IDE
├── MP3/
|   Sprachdateien für NOKO
├── NOKO/
|   Arduino-Quelltext mit allen Bibliotheken.
├── NOKO_Disk1/
|   Arduino-Sketch zum Beschreiben des 24LC256-EEPROMs.
│   ├── TTY/
|       Hilfsprogramm, um die Textdatei über die serielle Verbindung an den Arduino zu senden.
├── NOKO_EEPROM_Disk0/
|   Arduino-Sketch zum Schreiben der Grundeinstellungen in das Arduino-EEPROM und 
│   zum Stellen der Echtzeituhr. Optional zum Beschrieben des AH24C32-EEPROMs auf dem Modul der Echtzeituhr.
|   ├── TTY/
|       Hilfsprogramm, um die Textdatei über die serielle Verbindung an den Arduino zu senden.
├── Schaltplan/
|    Schaltpläne der NOKO-Module. 
|   ├── geda/
|   Rohe Schaltpläne für gEDA
├── WIKI/
    Bilddateien, um öde, textlastige NOKO-WIKIs zu verschönern und veraunschaulichen. 

```

WEITERE DATEIEN FOLGEN IN KÜRZE.
