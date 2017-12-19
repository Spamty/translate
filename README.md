# Translations

Translation is done with .po and .mo files located in `/translate/LANG_LANG/LC_MESSAGES/spamty.xx`.

(For configuration in PHP see `/includes/ws-head.php`.)

## Languages

Spamty is currently available in:
 * **Arabic** (experimental): URL `ar`; Language Code `ar_AE`
 * **German** (100% complete): URL `de`; Language Code `de_DE`
 * **English** (primary language): URL `en`; Language Code `en_EN`
 * **Spanish** (bad quality): URL `es`; Language Code `es_ES`
 * **French** (not good quality): URL `fr`; Language Code `fr_FR`
 * **Chinese** (bad quality and not finished): URL `zh`; Language Code `zh_CN`
 * **Upside down English** (not finished): URL `up`; Language Code `en_NG`
 * **Emoji English** (not finished): URL `ej`; Language Code `en_IN`

For URLs we use *ISO 639-1 codes* <https://en.wikipedia.org/wiki/List_of_ISO_639-1_codes>.



# Server

The languages have to be installed on the server. Check which ones are installed with `locale -a`.

## Install languages

In Debian uncomment the required languages in `/etc/locale.gen`. Then run `locale-gen`.



# Language Cookies on website

The language setting is stored in cookie named *lang*.

## Set Cookie

### Click on flag icon
Set cookie with chosen language (with Javascript).

### Cookie not set
Set to currently viewed language.

## Select language

### View email address
Use language from cookie, if not set use browser language.
