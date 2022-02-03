# Pelotrak Translations

Help make Pelotrak better by providing translations.


## How It Works

By default, English will be used. This is also the case if no translation is available.

There are two types of data sections:

1. **In-App Strings:** Those are all the small little words and sentences in the app.
2. **Markdown Pages:** These are longer pieces of text explaining aspects of the app.

If you would like to contribute, please open a Pull Request and let Oskar know. Help is very much appreciated.


## In-App Strings

All In-App Strings can be found in the `en.yaml` file. Translations must be placed in a new, country-code specific file (eg `de.yaml`) and must match the structure exactly.

Anything in `{}` are variables that are required, must show up in the translated text, but must not be translated themselves. For example:

```yaml
found: 'Zone targets by {source}'
```

Would be translated to German as

```yaml
found: 'Zonenvorgaben von {source}'
```


## Markdown Pages

The English source files can be found in the `markdown_pages` folder. To translate into a new language, create a subfolder with the corresponding country code, eg `markdown_pages/de` and place the translated files with the exact same name as the source files in there.

Note that the Markdown capabilities are very limited in the app. Some guidance:

* Do not use H1 header (`# ...`). The header for a page should be H2 (`## ...`), subsections should be H3 (`### ...`). H4 or beyond are not supported.
* Only use "Strong" wraps for emphasis, ie using double asterisks: `hello **world**`
* Only use bullets (`* `) for lists
* The table support is minimal.


## Got Problems?

Feel free to email Oskar anytime (email address in the app).