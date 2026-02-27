# SlideShow Digital Signage System - localizations and translations

This repository contains localization files for SlideShow app.

## How to contribute

If you would like to fix an existing translation or add a new language, you can:
- Create a pull request
- Open an issue
- Contact us directly (<slideshow@slideshow.digital>)

We’ll gladly review your contribution and include it in the next SlideShow release.

## Localization structure

Localization is divided into two parts (see folders in this repository):

- **backend**
   - One file per language
   - Format: key=value 
   - The file `localization.xlsx` contains all languages in a single table for reference
- **web-interface**
   - One file containing all languages
   - JavaScript format:
     ```
	 localization.lang["key"] = "value";
	 ```

:warning: Please update both parts. Otherwise, we may need to rely on machine translation, which can reduce quality.

All files must use UTF-8 encoding.

## Translation quality guidelines

If you use machine translation (e.g., Google Translate):
- Review translations manually
- Verify formatting and placeholders
- Ensure natural phrasing and accuracy

Machine translation alone is usually insufficient without manual review.

## Current languages

- Chinese (thanks to evin792)
- Croatian (thanks to Josip Papić)
- Czech (thanks to Aleš Obst)
- Dutch (thanks to Jule Hintzbergen)
- English
- French (thanks to Ahmed Karboubi)
- German (thanks to Stefan Preitschaft)
- Italian (thanks to Michele Fioretti & Nicola Pinto)
- Japanese (thanks to Takashi Yamaguchi)
- Korean (thanks to Seok Gyo Seo)
- Polish (thanks to Piotr Bujalski)
- Portuguese (thanks to Jorge Soares)
- Russian (thanks to Sergej Karpovič)
- Slovak
- Slovenian (thanks to @AdmiralStipe)
- Spanish (thanks to Rafael García)
- Turkish (thanks to İlker Berberler)

## About SlideShow

SlideShow is a free digital signage system for Android.

Learn more or download the app:
- <https://slideshow.digital/>
- <https://slideshow.digital/how-to-get-it/>
