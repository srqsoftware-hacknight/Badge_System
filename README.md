
## About RFID
RFID access control system.
For our purpose, there are basically 2 styles:
  1) "old" uses 125 KHz low frequency unique serial#.
  2) "new" uses 13.56MHz with some with DES encryption key exchange termed "MIFARE RC522"
Recommend using the "new 13M" MIFARE RC522 style.
The lab has a kit of reader + 2 tags to play with.
BTW, I have a "old" 125 KHz reader (TTL output), and few 125K tags we can play with if desired.

## Reasons to choose MRF522
 - There are lots of Arduino libraries and development kits for the "new" 13M tags:
 - More modern, larger keys, more security features.
 - In theory people could tie other tags to their account (Disney "Magic Band", etc.)

## About MIFARE RC522
**General info about MIFARE RC522 capability**
(Learning MRC522) [http://playground.arduino.cc/Learning/MFRC522]
(MRC522 Reference datasheet)  [http://www.nxp.com/documents/data_sheet/MFRC522.pdf]

### Projects with MRC522
 - https://github.com/ondryaso/pi-rc522
 - https://hackaday.io/project/8584-esp8266-rfid-reader
 - https://github.com/Jorgen-VikingGod/ESP8266-MFRC522
 - http://forum.arduino.cc/index.php?topic=256260
 - https://github.com/omersiar/RFID522-Door-Unlock

### Hacking MRC522
 - (Extending the range of MRC522) [http://forum.arduino.cc/index.php?topic=199983]
 - (MRC522 tool kit) [https://github.com/nfc-tools/mfcuk]


