# CBArray
A (very crude) Netbeans/Java work in progress to develop fonts for SSD1780/SSD1306
displays, currently being used on displays connected to ESP8266 (ESP-09).

Mostly working, but only [Next] button detects changes.

For now, to use, click [Ins Rec] and add records until you are done, then click a final
[Next Rec] to save last record, and finally, click [Save File] to save. [Open File] will
allow you to 're-load' and edit this file.

Resulting file (using [Save File]) creates _most_ of a header file for use with above displays.
To be complete, file must have something like 'const char myFontxxx[][xx] PROGMEM = {' prepended,
and '};' appended. See reference below

See [https://github.com/costonisp/ESP8266-I2C-OLED/blob/master/ESP_Messenger_v1.0]
