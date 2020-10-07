# Localazy Shields API

## URL

`https://connect.localazy.com/status/[project-id]/data?content=[content]&title=[title]&logo=[true|rrggbb]`

Returned format is compatible with [shields.io/endpoint](https://shields.io/endpoint) JSON.


## Variables:

- **[project-id]** - The project ID or slug on Localazy. _Required._

- **[content]** - The content of the right part. 
  - **all** - show the overal progres and the number of languages
  - **progress** - show only the overal progress
  - **langs** - show only the number of languages
  - **locale-code** (e.g. en, fr_FR, zh_TW_Hans) - show the progress for the given locale

- **[title]** - The content of the left part.
  - **default** - Use **lang-code** for locale-specific shield, otherwise use **localazy**.
  - **localazy** - Left part: Localazy
  - **translated** - Left part: translated
  - **localized** - Left part: localized
  - **localization** - Left part: localization
  - **translation** - Left part: translation
  - **lang-loc-name** - Left part: _localized language name_
  - **lang-name** - Left part: _English language name_
  - **lang-code** - Left part: _ locale code_
  
- **[logo]** - Add the logo image and optionally change its color.
  - **true** - Show the logo in the default white color.
  - **RRGGBB** - Show the logo in color given by HEX RRGGBB code.
  
  
## Demos

It's possible to check these (and some other variants) in [README.md](README.md).




