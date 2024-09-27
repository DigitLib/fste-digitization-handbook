# fste-digitization-handbook
From Shelf to Europeana Digitization Handbook - A handbook with a FLOSS directory which can help CH Institutions to start digitization and share their content to Europeana. The Handbook covers all steps in a process of Digitization.

Handbook is available on this link\
<a href="https://europeana.github.io/fste-digitization-handbook">europeana.github.io/fste-digitization-handbook</a>

### Update
Added Serbian translation\
<a href="https://europeana.github.io/fste-digitization-handbook/sr/">europeana.github.io/fste-digitization-handbook/sr</a>

## Translation the Handbook
If you want to translate this Handbook to your native language and help us to spread it in your community, follow this steps:

* Join to EuropeanaTech Community (if you are not a member)
<a href="https://pro.europeana.eu/page/europeanatech" targert="_blank">pro.europeana.eu/page/europeanatech</a>
* Join us to our TasckForce <a href="https://pro.europeana.eu/project/workflow-from-shelf-to-europeana" target="_blank">pro.europeana.eu/project/workflow-from-shelf-to-europeana</a>
* Fork this repo

Create new Lang folder in /src/content/docs/ (Serbian is sr) more on language codes <a href="https://en.wikipedia.org/wiki/List_of_ISO_639_language_codes"> Lang Codes ISO</a>

Add new lang in file astro.config.mjs after sr, (for example Dutch):
```js
locales: {
  root: {
    label: "English",
    lang: "en", // lang is required for root locales
  },
  sr: {
    label: "Српски",
    lang: "sr",
  },
  nl: {
    label: "Dutch",
    lang: "nl",
  },
},
```
Use your native language name for label.

The new language option shows automatic on menu.

For docs content translate also the chapters label in same file:
```js
sidebar: [
  {
    label: "Before you start",
    translations: {
      sr: "Пре почетка",
    },
```
**Add new language code in translations under the sr: in all sidebar section.**

After the translation is finished create a PR to merge it to the Hanbook.

Spread it with your community.
