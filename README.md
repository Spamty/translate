# Translations

This is the translation for the spamty.eu website.

Translation is done with .po files located in `/translate/LANG_LANG/LC_MESSAGES/spamty.po`.
The .mo files are generated automatically.


## Languages

Spamty is currently available in:

|Language |Status |details |URL suffix |Language Code |
|---|---|---|---|---|
|Arabic |:interrobang: |experimental (rtl) |ar |ar_AE |
|German |:white_check_mark: |100% |de |de_DE |
|English |:white_check_mark: |100%, primary |en |en_EN |
|Spanish |:x: |Google translator |es |es_ES |
|French |:bangbang: |needs review |fr |fr_FR |
|Hindi |:x: |Incomplete |hi |hi_IN |
|Italian |:x: |Incomplete |it |it_IT |
|Japanese |:x: |Incomplete |jp |ja_JP |
|Portuguese |:x: |Incomplete |pt |pt_PT |
|Russian |:x: |Incomplete |ru |ru_RU |
|Turkish |:x: |Incomplete |tr |tr_TR |
|Chinese |:x: |Incomplete |zh |zh_CN |
|Upside down English |:heavy_minus_sign: | |up |en_NG |
|Emoji English |:heavy_minus_sign: | |ej |en_IN |


For URLs we prefer to use *ISO 639-1 codes* <https://en.wikipedia.org/wiki/List_of_ISO_639-1_codes>.



# Server configuration

_Only internal information_

The languages have to be installed on the server. Check which ones are installed with `locale -a`.
In Debian uncomment the required languages in `/etc/locale.gen`. Then run `locale-gen`.

# Website configuration

_Only internal information_

PHP config is in `ws-head.php` file.

The language setting is stored in cookie named *lang*.
Set cookie with chosen language (with Javascript) by clicking on flag icon.
If no cookie is set use browser language or it will be set to currently viewed language.
