# Localazy Shields

Share the localization progress of your app or project publicly with your contributors, volunteers and translators. And get more of them :wink:. 

Example: 

[![](https://connect.localazy.com/status/floating-apps)](https://localazy.com/p/floating-apps)

## Format

The basic URL is:

`https://connect.localazy.com/status/[project-id]`

There are four parameters that allows you to override texts, look and feel:

- **content** - changes the generated information
- **title** - changes the informative title
- **style** - changes the style of the shield
- **logo** - adds logo and allow to colorize it

The full URL looks like:

`https://connect.localazy.com/status/[project-id]?title=...&content=...&style=...&logo=...`


## Content

You can use the shield to show overal project progress, number of languages or progress for defined language.
 
Usage: `![](https://connect.localazy.com/status/floating-apps?content=[value])`
 
| Value | Demo | Description |
| --- | --- | --- |
| all | [![](https://connect.localazy.com/status/floating-apps?content=all)](https://localazy.com/p/floating-apps) | The overal project progress and the number of langs. |
| progress | [![](https://connect.localazy.com/status/floating-apps?content=progress)](https://localazy.com/p/floating-apps) | The overal project progress. |
| langs | [![](https://connect.localazy.com/status/floating-apps?content=langs)](https://localazy.com/p/floating-apps) | The number of langs including text. |
| langs-count | [![](https://connect.localazy.com/status/floating-apps?content=langs-count)](https://localazy.com/p/floating-apps) | Only the number of langs. |
| *locale code* | [![](https://connect.localazy.com/status/floating-apps?content=fr_CA)](https://localazy.com/p/floating-apps) | The progress for the given language. The valid format for locale code is described below. |

## Title

You can change the shown title to one of the available variants. There are also specific variants for locale-specific shields.

Usage: `![](https://connect.localazy.com/status/floating-apps?title=[value])`

| Value |  Demo | Description |
| --- | --- | --- |
| default | - | Use `lang-code` for locale-specific shield, otherwise use `localazy`. |
| localazy | [![](https://connect.localazy.com/status/floating-apps?title=localazy)](https://localazy.com/p/floating-apps) | |
| translated | [![](https://connect.localazy.com/status/floating-apps?title=translated)](https://localazy.com/p/floating-apps) | |
| localized | [![](https://connect.localazy.com/status/floating-apps?title=localized)](https://localazy.com/p/floating-apps) | |
| localization | [![](https://connect.localazy.com/status/floating-apps?title=localization)](https://localazy.com/p/floating-apps) | |
| translation | [![](https://connect.localazy.com/status/floating-apps?title=translation)](https://localazy.com/p/floating-apps) | |
| lang-loc-name | [![](https://connect.localazy.com/status/floating-apps?title=lang-loc-name&content=fr_CA)](https://localazy.com/p/floating-apps) | The localized name. |
| lang-name | [![](https://connect.localazy.com/status/floating-apps?title=lang-name&content=fr_CA)](https://localazy.com/p/floating-apps) | The English name. |
| lang-code | [![](https://connect.localazy.com/status/floating-apps?title=lang-code&content=fr_CA)](https://localazy.com/p/floating-apps) | The locale code. |

## Logo

Add Localazy logo and optionally change its color.

Usage: `![](https://connect.localazy.com/status/floating-apps?logo=[true|RRGGBB])`

| Value |  Demo | Description |
| --- | --- | --- |
| true | [![](https://connect.localazy.com/status/floating-apps?logo=true)](https://localazy.com/p/floating-apps) | Just use the logo with the default white color.  |
| RRGGBB | [![](https://connect.localazy.com/status/floating-apps?logo=ff0000)](https://localazy.com/p/floating-apps) | Change the color if necessary. The color code is provided in HEX RRGGBB format. |

## Style

All styles from [shields.io](https://shields.io) are supported. 

Usage: `![](https://connect.localazy.com/status/floating-apps?style=[value])`

| Value |  Demo | 
| --- | --- | 
| plastic | [![](https://connect.localazy.com/status/floating-apps?style=plastic)](https://localazy.com/p/floating-apps) |
| flat | [![](https://connect.localazy.com/status/floating-apps?style=flat)](https://localazy.com/p/floating-apps) |
| flat-square | [![](https://connect.localazy.com/status/floating-apps?style=flat-square)](https://localazy.com/p/floating-apps) |
| for-the-badge | [![](https://connect.localazy.com/status/floating-apps?style=for-the-badge)](https://localazy.com/p/floating-apps) |
| social | [![](https://connect.localazy.com/status/floating-apps?style=social)](https://localazy.com/p/floating-apps) |

## Locale Code Format

Any of these formats is recognized as valid locale code:

* **ll**
* **ll_RR**
* **ll-RR**
* **ll+RR**
* **ll_Scrp**
* **ll-Scrp**
* **ll+Scrp**
* **ll#Scrp**
* **ll_RR_Scrp**
* **ll_Scrp_RR**
* **ll_RR#Scrp**
* **ll-RR-Scrp**
* **ll-Scrp-RR**
* **ll-RR#Scrp**
* **ll+RR+Scrp**
* **ll+Scrp+RR**
   
Where:
- **ll** is language code
- **RR** is region code
- **Scrp** is script code 
