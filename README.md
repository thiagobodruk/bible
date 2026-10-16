# Bible: XML and JSON

[![Stars](https://badgen.net/github/stars/thiagobodruk/bible?color=orange)](https://github.com/thiagobodruk/bible/stargazers)
[![Languages](https://img.shields.io/badge/dynamic/json?url=https://raw.githubusercontent.com/thiagobodruk/bible/master/json/index.json&query=$.length&label=languages)](#)
![Versions](https://img.shields.io/badge/versions-122-blue)
[![License: MIT](https://img.shields.io/github/license/thiagobodruk/bible)](LICENSE)
![Formats](https://img.shields.io/badge/formats-JSON%20%7C%20XML-blue)

> "And this gospel of the kingdom shall be preached in all the world
> for a witness unto all nations; and then shall the end come."
> — Matthew 24:14 (KJV)

## 122 Bible versions in 67 languages 🇧🇷 🇬🇧 🇪🇸 🇨🇳 🇸🇦 🇫🇷 🇩🇪

Read this doc in **English** · [Português (Brasil)](README.pt-br.md) · [Español](README.es.md) · [Français](README.fr.md) · [Italiano](README.it.md) · [Deutsch](README.de.md) · [日本語](README.ja.md) · [简体中文](README.zh-cn.md)

---

### 🤖 AI / LLM-ready

Clean, per-verse structured JSON and XML — no HTML, no markup noise, no
scraping artifacts. The same canonical book abbreviations are used
across every language and version, so verses align out of the box for
embeddings, RAG pipelines, fine-tuning, and cross-lingual alignment
tasks. MIT-licensed code with permissively-sourced text, ready to feed
straight into a dataset or a context window.

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
| 🇬🇭 Akan | Akuapem Twi Contemporary Bible | `ak_wakna` |  |
| 🇦🇱 Albanian | Bibla Shqip 1994 | `sq_albb` |  |
| 🇸🇦 Arabic | Ketab El Hayat Majani | `ar_kehm` | |
| 🇮🇳 Assamese | Indian Revised Version (IRV) Assamese 2019 | `as_irvasm` |  |
| 🇧🇾 Belarusian | Bíblia (tradução de V. Semukha) | `be_bbl` | |
| 🇧🇩 Bengali | Indian Revised Version (IRV) Bengali | `bn_irvben` | |
| 🇧🇷 Brazilian Portuguese | Almeida Revisada Imprensa Bíblica | `pt_aa` | |
| 🇧🇷 Brazilian Portuguese | Almeida Corrigida e Revisada Fiel | `pt_acf` | |
| 🇧🇷 Brazilian Portuguese | Almeida Revista e Atualizada | `pt_ara` | |
| 🇧🇷 Brazilian Portuguese | Almeida Revista e Corrigida | `pt_arc` | |
| 🇧🇷 Brazilian Portuguese | Almeida Revista e Corrigida 1969 | `pt_rc69` | |
| 🇧🇷 Brazilian Portuguese | Almeida Século 21 | `pt_a21` | |
| 🇧🇷 Brazilian Portuguese | Bíblia para Todos | `pt_bpt09` | |
| 🇧🇷 Brazilian Portuguese | Bíblia Sagrada Ave-Maria | `pt_avm` | Malachi has 3 chapters instead of 4 in this edition |
| 🇧🇷 Brazilian Portuguese | Bíblia Sagrada: Versão Fácil de Ler | `pt_vfl` | |
| 🇧🇷 Brazilian Portuguese | Edição Pastoral | `pt_pastoral` | Malachi has 3 chapters instead of 4 in this edition |
| 🇧🇷 Brazilian Portuguese | King James Atualizada | `pt_kja` | |
| 🇧🇷 Brazilian Portuguese | King James Fiel | `pt_bkj` | |
| 🇧🇷 Brazilian Portuguese | Nova Almeida Atualizada | `pt_naa` | |
| 🇧🇷 Brazilian Portuguese | Nova Bíblia Viva 2007 | `pt_nbv` | |
| 🇧🇷 Brazilian Portuguese | Nova Tradução na Linguagem de Hoje | `pt_ntlh` | |
| 🇧🇷 Brazilian Portuguese | Nova Versão Internacional | `pt_nvi` | |
| 🇧🇷 Brazilian Portuguese | Nova Versão Internacional 2011 | `pt_nvi2011` | |
| 🇧🇷 Brazilian Portuguese | Nova Versão Transformadora | `pt_nvt` | |
| 🇧🇷 Brazilian Portuguese | O Livro | `pt_ol` | |
| 🇧🇷 Brazilian Portuguese | Tradução Brasileira | `pt_tb` | |
| 🇧🇷 Brazilian Portuguese | Tradução do Pe. Matos Soares | `pt_matos` | Malachi has 3 chapters instead of 4 in this edition |
| 🇧🇬 Bulgarian | Veren | `bg_vbg` | |
| 🇲🇲 Burmese | Judson Bible | `my_jbmle` |  |
| 🇦🇩 Catalan | Bíblia Catalana Interconfessional | `ca_bci` | Malachi has 3 chapters instead of 4 in this edition |
| 🇮🇶 Central Kurdish | Kurdi Sorani Standard Version | `ckb_okss` |  |
| 🇨🇳 Chinese | Chinese Union Version (New Punctuation, Shen Edition) | `zh_cunpss-shen` | |
| 🇨🇳 Chinese | New Chinese Version | `zh_cnvs` | |
| 🇨🇿 Czech | Bible Kralická 1613 | `cs_bkr` | |
| 🇬🇧 English | American Standard Version 1901 | `en_asv` | |
| 🇬🇧 English | Amplified Bible | `en_amp` | |
| 🇬🇧 English | Basic English | `en_bbe` | |
| 🇬🇧 English | Berean Standard Bible | `en_bsb` | |
| 🇬🇧 English | Christian Standard Bible | `en_csb` | |
| 🇬🇧 English | Contemporary English Version | `en_cev` | |
| 🇬🇧 English | Darby's Translation 1890 | `en_darby` | |
| 🇬🇧 English | Douay-Rheims American 1899 | `en_dra` | |
| 🇬🇧 English | English Standard Version | `en_esv` | |
| 🇬🇧 English | Free Bible Version | `en_fbv` | |
| 🇬🇧 English | Geneva Bible | `en_gnv` | |
| 🇬🇧 English | Good News Translation | `en_gnt` | |
| 🇬🇧 English | Jubilee Bible | `en_jub` | |
| 🇬🇧 English | King James Version | `en_kjv` | |
| 🇬🇧 English | King James Version with Apocrypha | `en_kjva` | |
| 🇬🇧 English | Lexham English Bible | `en_leb` | |
| 🇬🇧 English | Literal Standard Version | `en_lsv` | |
| 🇬🇧 English | Majority Standard Bible | `en_mbsb` | |
| 🇬🇧 English | New American Standard Bible 2020 | `en_nasb` | |
| 🇬🇧 English | New International Version | `en_niv` | |
| 🇬🇧 English | New King James Version | `en_nkjv` | |
| 🇬🇧 English | New Living Translation | `en_nlt` | |
| 🇬🇧 English | New Messianic Version Bible | `en_nmv` | |
| 🇬🇧 English | Revised Version 1885 | `en_engrv` | |
| 🇬🇧 English | The Cambridge Paragraph Bible of the Authorized English Version | `en_kjvcpb` | |
| 🇬🇧 English | The Orthodox Jewish Bible | `en_tojb2011` | Malachi has 3 chapters instead of 4 in this edition |
| 🇬🇧 English | A Translation for Translators | `en_t4t` | |
| 🇬🇧 English | World English Bible (American Edition) | `en_web` | |
| 🇬🇧 English | World English Bible Updated | `en_webu` | |
| 🇬🇧 English | World English Bible (British Edition) | `en_webbe` | |
| 🇬🇧 English | World English Bible, American English Edition, without Strong's numbers | `en_webus` | |
| 🇬🇧 English | World Messianic Bible (American English) | `en_wmb` | |
| 🇬🇧 English | World Messianic Bible (British Edition) | `en_wmbbe` | |
| 🇬🇧 English | Wycliffe's Bible with Modern Spelling | `en_wbms` | |
| 🇬🇧 English | Young's Literal Translation 1898 | `en_ylt98` | |
| 🌍 Esperanto | La Sankta Biblio 1926 | `eo_esp` | |
| 🇬🇭 Ewe | Ewe Contemporary Scriptures | `ee_oal` |  |
| 🇵🇭 Filipino | Ang Biblia 1905 | `tl_abtag` | |
| 🇫🇮 Finnish | Kirkkoraamattu 1933/38 | `fi_fb38` | |
| 🇫🇷 French | Le Bible de I'Épée | `fr_apee` | |
| 🇩🇪 German | Schlachter 1951 | `de_sch1951` | |
| 🇬🇷 Greek | Modern Greek (Demotic) | `el_fpb` | |
| 🇮🇳 Gujarati | Indian Revised Version (IRV) Gujarati 2019 | `gu_irvguj` |  |
| 🇭🇹 Haitian Creole | Bib Sen An: Kreyòl Ayisyen | `ht_bsa` |  |
| 🇳🇬 Hausa | Hausa Contemporary Bible | `ha_bsrk` |  |
| 🇮🇳 Hindi | Indian Revised Version (IRV) Hindi 2019 | `hi_irvhin` | |
| 🇭🇺 Hungarian | Károli 1908 | `hu_hunk` | |
| 🇳🇬 Igbo | Igbo Contemporary Bible | `ig_biuo` |  |
| 🇮🇹 Italian | Sacra Bibbia Versione Riveduta 2020 | `it_irb20` | |
| 🇯🇵 Japanese | 聖書 新共同訳 (Shinkyodoyaku) | `ja_jniv` | Malachi has 3 chapters instead of 4 in this edition |
| 🇮🇳 Kannada | Indian Revised Version (IRV) Kannada 2019 | `kn_irvkan` |  |
| 🇰🇿 Kazakh | Киелі кітап | `kk_qazbi` |  |
| 🇰🇪 Kikuyu | Kiugo Gĩtheru Kĩa Ngai Kĩhingũre | `ki_kgnk` |  |
| 🇧🇮 Kirundi | Kirundi Contemporary Bible | `rn_obkc` |  |
| 🇰🇷 Korean | Korean Revised | `ko_krv` | |
| 🇻🇦 Latin | Vulgata Latina | `la_vulg` |  |
| 🇱🇻 Latvian | Glika Bībele | `lv_lg8` |  |
| 🇨🇩 Lingala | Lingala Contemporary Bible | `ln_smnb` | Malachi has 3 chapters instead of 4 in this edition |
| 🇺🇬 Luganda | Bayibuli Entukuvu | `lg_olcb` |  |
| 🇲🇾 Malay | Alkitab Berita Baik | `ms_tmvr` |  |
| 🇮🇳 Malayalam | Indian Revised Version (IRV) Malayalam | `ml_irvmal` |  |
| 🇳🇿 Maori | Paipera Tapu 2012 | `mi_mri2012` |  |
| 🇮🇳 Marathi | Indian Revised Version (IRV) Marathi | `mr_irvmar` | |
| 🇳🇵 Nepali | Open Nepali Contemporary Version | `ne_oncv` |  |
| 🇿🇼 Northern Ndebele | Ndebele Contemporary Bible | `nd_oben` |  |
| 🇳🇴 Norwegian (Bokmål) | Bibel 2011 | `nb_bibel2011` | |
| 🇲🇼 Nyanja | Chichewa Contemporary Version | `ny_tccl` |  |
| 🇮🇳 Odia | Indian Revised Version (IRV) Odia | `or_irvory` |  |
| 🇪🇹 Oromo | New Oromo Contemporary Version | `om_onocv` |  |
| 🇮🇷 Persian | Persian Contemporary Bible 2022 | `fa_opcb` | |
| 🇵🇱 Polish | Uwspółcześniona Biblia Gdańska | `pl_ubg` | |
| 🇮🇳 Punjabi | Indian Revised Version (IRV) Punjabi | `pa_irvpun` | |
| 🇷🇴 Romanian | Versiunea Dumitru Cornilescu | `ro_vdc` | |
| 🇷🇺 Russian | Синодальный перевод (Synodal Translation) | `ru_synod` | Incomplete, 64 of 66 books (Esther and Daniel missing) — see `json/ru_synod.disclaimer.txt` |
| 🏴󠁧󠁢󠁳󠁣󠁴󠁿 Scottish Gaelic | Am Bìoball Gàidhlig 1992 | `gd_abg1992` |  |
| 🇷🇸 Serbian | Daničić-Karadžić | `sr_dk` | |
| 🇿🇼 Shona | Shona Contemporary Bible 2017 | `sn_bdrsc` |  |
| 🇪🇸 Spanish | Reina Valera 1960 | `es_rvr1960` | |
| 🇰🇪 Swahili | Swahili Revised Union Version | `sw_sruv` | |
| 🇸🇪 Swedish | Svenska Folkbibeln 2015 | `sv_sfb15` | |
| 🇮🇳 Tamil | Indian Revised Version (IRV) Tamil | `ta_irvtam` | |
| 🇮🇳 Telugu | Indian Revised Version (IRV) Telugu 2019 | `te_irvtel` | |
| 🇹🇭 Thai | Thai KJV | `th_kjvthai` | |
| 🇹🇴 Tongan | Ko e Tohi Tapu Kātoa | `to_rwv` |  |
| 🇹🇷 Turkish | Yorumsuz Türkçe Çeviri | `tr_ytc` | |
| 🇵🇰 Urdu | Indian Revised Version (IRV) Urdu 2019 | `ur_irvurd` | Text is in Devanagari script rather than Perso-Arabic — this is how the source itself publishes this edition, aimed at Urdu speakers who read Devanagari |
| 🇻🇳 Vietnamese | Tiếng Việt | `vi_vie` | |
| 🇳🇬 Yoruba | Yoruba Contemporary Bible | `yo_oycb` |  |

Each entry's files are `json/<code>.json` and `xml/<code>.xml` (e.g.
`json/pt_nvi.json`, `xml/pt_nvi.xml`). `json/index.json` lists this same
catalog in machine-readable form.

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
