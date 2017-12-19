# Translations

This is the translation for the spamty.eu website.

Translation is done with .po files located in `/translate/LANG_LANG/LC_MESSAGES/spamty.po`.
The .mo files are generated automatically.


## Languages

Spamty is currently available in:

|Language |Status |URL suffix |Language Code |
|---|---|---|---|
|Arabic |experimental (rtl) |ar |ar_AE |
|German |100% |de |de_DE |
|English |100% primary |en |en_EN |



 * **Arabic** (experimental): URL `ar`; Language Code `ar_AE`
 * **German** (100% complete): URL `de`; Language Code `de_DE`
 * **English** (primary language): URL `en`; Language Code `en_EN`
 * **Spanish** (Google translator): URL `es`; Language Code `es_ES`
 * **French** (bad quality): URL `fr`; Language Code `fr_FR`
 * **Hindi** (Google translator): URL `hi`; Language Code `????`
 * **Italian** (bad quality): URL `it`; Language Code `????`
 * **Japanese** (Google translator): URL `jp`; Language Code `????`
 * **Portuguese** (Google translator): URL `pt`; Language Code `????`
 * **Russian** (Google translator): URL `ru`; Language Code `????`
 * **Turkish** (Google translator): URL `tr`; Language Code `????`
 * **Chinese** (Google translator): URL `zh`; Language Code `zh_CN`

 * **Upside down English** (not finished): URL `up`; Language Code `en_NG`
 * **Emoji English** (not finished): URL `ej`; Language Code `en_IN`

For URLs we use *ISO 639-1 codes* <https://en.wikipedia.org/wiki/List_of_ISO_639-1_codes>.




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
