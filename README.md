# Bible: XML and JSON

Do you want to create a Bible based app? What about an API for Bible
verses search? Now you can do this, using sources in your very own
language! The main objective of this project is to allow people to
create Bible related apps using XML and JSON. Do you like this idea?
Help us to go even further. **Support this project! :)**

<a href="https://www.paypal.com/cgi-bin/webscr?cmd=_donations&business=A9FM66AQT672L&lc=US&item_name=Bible%20Sources&currency_code=USD&bn=PP%2dDonationsBF%3abtn_donateCC_LG%2egif%3aNonHosted"><img src="assets/paypal-donate-button.png" alt="Donate" width="400"></a>

## How were the files built?

The source files were generated using a Python based crawler. Therefore,
these files may contain minor issues related to encoding and syntax.

## Which languages and versions are covered by the project?

| Language | Version | Files | Notes |
|---|---|---|---|
| 🇸🇦 Arabic | Ketab El Hayat Majani | `ar_kehm` | |
| 🇨🇳 Chinese | Chinese Union Version (New Punctuation, Shen Edition) | `zh_cunpss-shen` | |
| 🇨🇳 Chinese | New Chinese Version | `zh_cnvs` | |
| 🇩🇪 German | Schlachter 1951 | `de_sch1951` | |
| 🇬🇷 Greek | Modern Greek (Demotic) | `el_fpb` | |
| 🇬🇧 English | Basic English | `en_bbe` | |
| 🇬🇧 English | King James Version | `en_kjv` | |
| 🌍 Esperanto | La Sankta Biblio 1926 | `eo_esp` | |
| 🇪🇸 Spanish | Reina Valera 1960 | `es_rvr1960` | |
| 🇫🇮 Finnish | Kirkkoraamattu 1933/38 | `fi_fb38` | |
| 🇫🇷 French | Le Bible de I'Épée | `fr_apee` | |
| 🇰🇷 Korean | Korean Revised | `ko_krv` | |
| 🇧🇷 Brazilian Portuguese | Almeida Revisada Imprensa Bíblica | `pt_aa` | |
| 🇧🇷 Brazilian Portuguese | Almeida Corrigida e Revisada Fiel | `pt_acf` | |
| 🇧🇷 Brazilian Portuguese | Almeida Revista e Atualizada | `pt_ara` | |
| 🇧🇷 Brazilian Portuguese | Nova Versão Internacional | `pt_nvi` | |
| 🇷🇴 Romanian | Versiunea Dumitru Cornilescu | `ro_vdc` | |
| 🇷🇺 Russian | Синодальный перевод (Synodal Translation) | `ru_synod` | Incomplete, 64 of 66 books — see [Known gaps](#known-gaps) |
| 🇻🇳 Vietnamese | Tiếng Việt | `vi_vie` | |

Each entry's files are `json/<code>.json` and `xml/<code>.xml` (e.g.
`json/pt_nvi.json`, `xml/pt_nvi.xml`). `json/index.json` lists this same
catalog in machine-readable form.

## Known gaps

* **Russian (`ru_synod`)**: the Book of Esther and the Book of Daniel
  are missing. The upstream data source does not publish standalone
  texts for these two books in this particular translation; both are
  traditionally presented within an expanded Greek text (interleaved
  with deuterocanonical additions) rather than as independently
  addressable books, and that alternate text does not fit this
  project's per-book chapter/verse structure. This is the only
  Russian-language translation available from the source, so no
  substitute could be used. See `json/ru_synod.disclaimer.txt` /
  `xml/ru_synod.disclaimer.txt` for details.
* **English, Basic English (`en_bbe`)** and **French, Le Bible de
  l'Épée (`fr_apee`)** are kept as previously published, unchanged in
  this update — the source used to refresh the other versions no longer
  offers these two translations.
* A few versions were refreshed from their closest currently available
  equivalent, since the previous edition is no longer published by the
  source: **Arabic** (`ar_svd` → `ar_kehm`), **Chinese Union Version**
  (`zh_cuv` → `zh_cunpss-shen`, New Punctuation, Shen Edition),
  **Spanish** (`es_rvr` → `es_rvr1960`), **German** (`de_schlachter` →
  `de_sch1951`), **Korean** (`ko_ko` → `ko_krv`), **Esperanto**
  (`eo_esperanto` → `eo_esp`), **Finnish** (`fi_finnish` + `fi_pr` →
  a single `fi_fb38`, since both old codes referred to the same
  edition), **Romanian** (`ro_cornilescu` → `ro_vdc`), **Russian**
  (`ru_synodal` → `ru_synod`), **Vietnamese** (`vi_vietnamese` →
  `vi_vie`), and **Modern Greek** (`el_greek` → `el_fpb`, chosen because
  it is the only current Greek edition that includes the Book of Esther
  as a standalone book).

## How the files are structured?

### XML

The XML files are encoded using UTF-8 and built in the following
structure:

```xml
<bible>
  <b id="abbrev" n="Book Name">
    <c n="1">
      <v n="1">Verse text</v>
    </c>
  </b>
</bible>
```

### JSON

The JSON files are also encoded using UTF-8 and built in the following
structure:

```javascript
[
	{
	"abbrev": "abbrev",
	"name": "Book Name",
	"chapters":
		[
			["Verse 1", "Verse 2", "Verse 3", "..."],
			["Verse 1", "Verse 2", "Verse 3", "..."],
			["Verse 1", "Verse 2", "Verse 3", "..."]
		]
	}
]
```

You can get the number of the chapter and verse using the array index.

### What about the license and the copyrights?

This project's code and data are distributed under the [MIT
License](LICENSE). All the Bible versions are property of their
respective owners. All rights reserved to the owners.

### How can I help the project?

You can review the code, enhance the structures or work on new
versions. Every help is welcome! :)

### Can I donate to the project?

Yes, you can! You can give a volunteer donation by
[PayPal](https://www.paypal.com/cgi-bin/webscr?cmd=_donations&business=A9FM66AQT672L&lc=US&item_name=Bible%20Sources&currency_code=USD&bn=PP%2dDonationsBF%3abtn_donateCC_LG%2egif%3aNonHosted).

<a href="https://www.paypal.com/cgi-bin/webscr?cmd=_donations&business=A9FM66AQT672L&lc=US&item_name=Bible%20Sources&currency_code=USD&bn=PP%2dDonationsBF%3abtn_donateCC_LG%2egif%3aNonHosted"><img src="assets/paypal-donate-button.png" alt="Donate" width="400"></a>
