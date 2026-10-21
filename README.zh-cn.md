**简体中文** · [English](README.md) · [Português (Brasil)](README.pt-br.md) · [Español](README.es.md) · [Français](README.fr.md) · [Italiano](README.it.md) · [Deutsch](README.de.md) · [日本語](README.ja.md)

# Bible: XML and JSON

**85 种语言，141 个圣经版本 🇧🇷 🇬🇧 🇪🇸 🇨🇳 🇸🇦 🇫🇷 🇩🇪**

干净、结构化的 JSON 和 XML，适用于圣经应用、经文搜索和 NLP/AI 数据集。

[![Stars](https://badgen.net/github/stars/thiagobodruk/bible?color=yellow)](https://github.com/thiagobodruk/bible/stargazers)
[![Languages](https://img.shields.io/badge/dynamic/json?url=https://raw.githubusercontent.com/thiagobodruk/bible/master/json/index.json&query=$.length&label=languages)](#)
![Versions](https://img.shields.io/badge/versions-141-blue)
[![License: MIT](https://img.shields.io/github/license/thiagobodruk/bible)](LICENSE)
![Formats](https://img.shields.io/badge/formats-JSON%20%7C%20XML-red)

[版本列表](#本项目涵盖哪些语言和版本) · [文件格式](#文件是如何组织的) · [适用于 AI / LLM](#-为-ai--llm-而生) · [Wiki](https://github.com/thiagobodruk/bible/wiki) · [讨论](https://github.com/thiagobodruk/bible/discussions)

---

> 这天国的福音要传遍天下，向万民作见证，然后结局才来到。
> — 马太福音 24:14（新译本）

### 🤖 为 AI / LLM 而生

按节组织的干净 JSON 和 XML——没有 HTML，没有标记噪音，也没有爬取留下的杂质。所有语言和版本都使用相同的标准书卷缩写，因此经文可以直接对齐，开箱即用于 embedding、RAG 流水线、微调以及跨语言对齐任务。代码采用 MIT 许可证，文本来自许可宽松的来源，可直接放入数据集或上下文窗口。

想开发一款圣经应用吗？想做一个经文搜索 API 吗？现在，你可以使用自己母语的资源来实现！本项目的主要目标，是让大家能够使用 XML 和 JSON 开发与圣经相关的应用。喜欢这个想法吗？请帮助我们走得更远。**支持本项目！ :)**

<a href="https://www.paypal.com/cgi-bin/webscr?cmd=_donations&business=A9FM66AQT672L&lc=US&item_name=Bible%20Sources&currency_code=USD&bn=PP%2dDonationsBF%3abtn_donateCC_LG%2egif%3aNonHosted"><img src="assets/paypal-donate-button.png" alt="Donate" width="400"></a>

## 这些文件是如何生成的？

源文件由一个基于 Python 的爬虫生成，因此可能存在一些与编码和语法有关的小问题。

## 本项目涵盖哪些语言和版本？

| 语言 | 版本 | 文件 | 备注 |
|---|---|---|---|
| 🇿🇦 Afrikaans | Afrikaans 1933/1953 | `af_afr53` |  |
| 🇬🇭 Akan | Akuapem Twi Contemporary Bible | `ak_wakna` | |
| 🇦🇱 Albanian | Bibla Shqip 1994 | `sq_albb` | |
| 🇬🇷 Ancient Greek | Textus Receptus (Η Καινή Διαθήκη) | `grc_grctr` | 仅含新约（27 卷） |
| 🇬🇷 Ancient Greek | Septuagint, Brenton (μετάφραση των εβδομήκοντα) | `grc_grcbrent` | 仅含旧约（36 卷），希腊文七十士译本；此版本编号中箴言第 30 章为空; 此版本中玛拉基书为 3 章，而非 4 章 |
| 🇸🇦 Arabic | Ketab El Hayat Majani | `ar_kehm` | |
| 🇦🇲 Armenian | Նոր Էջմիածին Աստվածաշունչ (New Etchmiadzin Bible) | `hy_neb` | 不完整，66 卷中的 64 卷（缺少以斯帖记和但以理书）; 此版本中玛拉基书为 3 章，而非 4 章 |
| 🇮🇳 Assamese | Indian Revised Version (IRV) Assamese 2019 | `as_irvasm` | |
| 🇪🇸 Basque | Navarro-Labourdin Basque Bible | `eu_bhnt` |  |
| 🇧🇾 Belarusian | Bíblia (tradução de V. Semukha) | `be_bbl` | |
| 🇧🇩 Bengali | Indian Revised Version (IRV) Bengali | `bn_irvben` | |
| 🇻🇺 Bislama | Open Bislama Bible Revised | `bi_obbr` |  |
| 🇧🇷 Brazilian Portuguese | Almeida Revisada Imprensa Bíblica | `pt_aa` | |
| 🇧🇷 Brazilian Portuguese | Almeida Corrigida e Revisada Fiel | `pt_acf` | |
| 🇧🇷 Brazilian Portuguese | Almeida Revista e Atualizada | `pt_ara` | |
| 🇧🇷 Brazilian Portuguese | Almeida Revista e Corrigida | `pt_arc` | |
| 🇧🇷 Brazilian Portuguese | Almeida Revista e Corrigida 1969 | `pt_rc69` | |
| 🇧🇷 Brazilian Portuguese | Almeida Século 21 | `pt_a21` | |
| 🇧🇷 Brazilian Portuguese | Bíblia para Todos | `pt_bpt09` | |
| 🇧🇷 Brazilian Portuguese | Bíblia Sagrada Ave-Maria | `pt_avm` | 此版本中玛拉基书为 3 章，而非 4 章 |
| 🇧🇷 Brazilian Portuguese | Bíblia Sagrada: Versão Fácil de Ler | `pt_vfl` | |
| 🇧🇷 Brazilian Portuguese | Edição Pastoral | `pt_pastoral` | 此版本中玛拉基书为 3 章，而非 4 章 |
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
| 🇧🇷 Brazilian Portuguese | Tradução do Pe. Matos Soares | `pt_matos` | 此版本中玛拉基书为 3 章，而非 4 章 |
| 🇧🇬 Bulgarian | Veren | `bg_vbg` | |
| 🇲🇲 Burmese | Judson Bible | `my_jbmle` | |
| 🇦🇩 Catalan | Bíblia Catalana Interconfessional | `ca_bci` | 此版本中玛拉基书为 3 章，而非 4 章 |
| 🇵🇭 Cebuano | Ang Pulong sa Dios | `ceb_oapd` |  |
| 🇮🇶 Central Kurdish | Kurdi Sorani Standard Version | `ckb_okss` | |
| 🇨🇳 Chinese | Chinese Union Version (New Punctuation, Shen Edition) | `zh_cunpss-shen` | |
| 🇨🇳 Chinese | New Chinese Version | `zh_cnvs` | |
| 🇭🇷 Croatian | Knjiga o Kristu | `hr_okok` | 仅含新约（27 卷） |
| 🇨🇿 Czech | Bible Kralická 1613 | `cs_bkr` | |
| 🇳🇱 Dutch | De Heilige Schrift, Petrus Canisiusvertaling, 1939 | `nl_nld1939` | 不完整，66 卷中的 64 卷（缺少以斯帖记和但以理书） |
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
| 🇬🇧 English | The Orthodox Jewish Bible | `en_tojb2011` | 此版本中玛拉基书为 3 章，而非 4 章 |
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
| 🇪🇪 Estonian | Vaba kasutusega Uus Testament, Pühakiri kaasaegses eesti keeles | `et_opkek` | 仅含新约（27 卷） |
| 🇬🇭 Ewe | Ewe Contemporary Scriptures | `ee_oal` | |
| 🇵🇭 Filipino | Ang Biblia 1905 | `tl_abtag` | |
| 🇫🇮 Finnish | Kirkkoraamattu 1933/38 | `fi_fb38` | |
| 🇫🇷 French | Le Bible de I'Épée | `fr_apee` | |
| 🇩🇪 German | Schlachter 1951 | `de_sch1951` | |
| 🇬🇷 Greek | Modern Greek (Demotic) | `el_fpb` | |
| 🇮🇳 Gujarati | Indian Revised Version (IRV) Gujarati 2019 | `gu_irvguj` | |
| 🇭🇹 Haitian Creole | Bib Sen An: Kreyòl Ayisyen | `ht_bsa` | |
| 🇳🇬 Hausa | Hausa Contemporary Bible | `ha_bsrk` | |
| 🇮🇱 Hebrew | Westminster Leningrad Codex (WLC) | `he_wlc` | 仅含旧约（39 卷）, 带元音符号和吟诵符号; 此版本中玛拉基书为 3 章，而非 4 章 |
| 🇮🇳 Hindi | Indian Revised Version (IRV) Hindi 2019 | `hi_irvhin` | |
| 🇭🇺 Hungarian | Károli 1908 | `hu_hunk` | |
| 🇮🇸 Icelandic | Opna Lifandi Orð: Nýja testamentið og Sálmarnir | `is_olo` | 仅含新约和诗篇（28 卷） |
| 🇳🇬 Igbo | Igbo Contemporary Bible | `ig_biuo` | |
| 🇮🇩 Indonesian | Alkitab Terjemahan Sederhana Indonesia, Edisi Ketiga (TSI) | `id_tsi` | 不完整，66 卷中的 48 卷（21 卷旧约和完整新约） |
| 🇮🇹 Italian | Sacra Bibbia Versione Riveduta 2020 | `it_irb20` | |
| 🇯🇵 Japanese | 聖書 新共同訳 (Shinkyodoyaku) | `ja_jniv` | 此版本中玛拉基书为 3 章，而非 4 章 |
| 🇮🇳 Kannada | Indian Revised Version (IRV) Kannada 2019 | `kn_irvkan` | |
| 🇰🇿 Kazakh | Киелі кітап | `kk_qazbi` | |
| 🇰🇪 Kikuyu | Kiugo Gĩtheru Kĩa Ngai Kĩhingũre | `ki_kgnk` | |
| 🇷🇼 Kinyarwanda | Rufumbira New Testament | `rw_ruf` | 仅含新约（27 卷） |
| 🇧🇮 Kirundi | Kirundi Contemporary Bible | `rn_obkc` | |
| 🇰🇷 Korean | Korean Revised | `ko_krv` | |
| 🇻🇦 Latin | Vulgata Latina | `la_vulg` | |
| 🇱🇻 Latvian | Glika Bībele | `lv_lg8` | |
| 🇨🇩 Lingala | Lingala Contemporary Bible | `ln_smnb` | 此版本中玛拉基书为 3 章，而非 4 章 |
| 🇺🇬 Luganda | Bayibuli Entukuvu | `lg_olcb` | |
| 🇲🇾 Malay | Alkitab Berita Baik | `ms_tmvr` | |
| 🇮🇳 Malayalam | Indian Revised Version (IRV) Malayalam | `ml_irvmal` | |
| 🇳🇿 Maori | Paipera Tapu 2012 | `mi_mri2012` | |
| 🇮🇳 Marathi | Indian Revised Version (IRV) Marathi | `mr_irvmar` | |
| 🇳🇵 Nepali | Open Nepali Contemporary Version | `ne_oncv` | |
| 🇿🇼 Northern Ndebele | Ndebele Contemporary Bible | `nd_oben` | |
| 🇳🇴 Norwegian (Bokmål) | Bibel 2011 | `nb_bibel2011` | |
| 🇲🇼 Nyanja | Chichewa Contemporary Version | `ny_tccl` | |
| 🇮🇳 Odia | Indian Revised Version (IRV) Odia | `or_irvory` | |
| 🇪🇹 Oromo | New Oromo Contemporary Version | `om_onocv` | |
| 🇮🇷 Persian | Persian Contemporary Bible 2022 | `fa_opcb` | |
| 🇵🇱 Polish | Uwspółcześniona Biblia Gdańska | `pl_ubg` | |
| 🇮🇳 Punjabi | Indian Revised Version (IRV) Punjabi | `pa_irvpun` | |
| 🇷🇴 Romanian | Versiunea Dumitru Cornilescu | `ro_vdc` | |
| 🇷🇺 Russian | Синодальный перевод (Synodal Translation) | `ru_synod` | 不完整，66 卷中缺 2 卷（缺少以斯帖记和但以理书）——参见 `json/ru_synod.disclaimer.txt` |
| 🇮🇳 Sanskrit | Sanskrit Bible (सत्यवेदः) | `sa_san-dn` | 仅含新约（27 卷）, 天城体文字 |
| 🏴󠁧󠁢󠁳󠁣󠁴󠁿 Scottish Gaelic | Am Bìoball Gàidhlig 1992 | `gd_abg1992` | |
| 🇷🇸 Serbian | Daničić-Karadžić | `sr_dk` | |
| 🇿🇼 Shona | Shona Contemporary Bible 2017 | `sn_bdrsc` | |
| 🇸🇰 Slovak | Nádej pre každého | `sk_onpk` | 仅含新约（27 卷） |
| 🇪🇸 Spanish | Reina Valera 1960 | `es_rvr1960` | |
| 🇰🇪 Swahili | Swahili Revised Union Version | `sw_sruv` | |
| 🇸🇪 Swedish | Svenska Folkbibeln 2015 | `sv_sfb15` | |
| 🇮🇳 Tamil | Indian Revised Version (IRV) Tamil | `ta_irvtam` | |
| 🇮🇳 Telugu | Indian Revised Version (IRV) Telugu 2019 | `te_irvtel` | |
| 🇹🇭 Thai | Thai KJV | `th_kjvthai` | |
| 🇹🇴 Tongan | Ko e Tohi Tapu Kātoa | `to_rwv` | |
| 🇧🇼 Tswana | Lefoko: La Botshelo Kgolagano e Ntsha | `tn_olef` | 仅含新约（27 卷） |
| 🇹🇷 Turkish | Yorumsuz Türkçe Çeviri | `tr_ytc` | |
| 🇺🇦 Ukrainian | Бібліка Відкрита Новий Переклад Українською (Biblica Open New Ukrainian Translation) | `uk_vnpu` | 仅含新约和诗篇（28 卷） |
| 🇵🇰 Urdu | Indian Revised Version (IRV) Urdu 2019 | `ur_irvurd` | 文本使用天城文，而非波斯-阿拉伯文——这是数据源本身发布该版本的方式，面向阅读天城文的乌尔都语使用者 |
| 🇻🇳 Vietnamese | Tiếng Việt | `vi_vie` | |
| 🇮🇱 Yiddish | Orthodox Yiddish Tanakh (ארטאדאקסישע יידישע תּנ״ך) | `yi_oytanakh` | 仅含旧约（39 卷）; 此版本中玛拉基书为 3 章，而非 4 章 |
| 🇳🇬 Yoruba | Yoruba Contemporary Bible | `yo_oycb` | |

每个条目的文件为 `json/<code>.json` 和 `xml/<code>.xml`（例如 `json/pt_nvi.json`、`xml/pt_nvi.xml`）。`json/index.json` 以机器可读的形式列出了同一份目录。

## 文件是如何组织的？

> **书名：** 自 v3.0 起，`name`（JSON）和 `n`（XML）为各版本所用语言的书名，例如 `en_kjv` 中为 `Genesis`，`ja_jniv` 中为 `創世記`。v2.3 及之前，几乎所有文件都使用葡萄牙语书名。`abbrev` 是跨语言的稳定标识符，[`json/book_names.json`](json/book_names.json) 列出了所有版本的书名。`sa_san-dn` 和 `fr_apee` 仍使用英文书名。
>
> 部分书名按各版本的原样保留，可能看起来不太寻常：`tr_ytc`（土耳其语）丢失了无点的 `ı` 和部分重音符号（写作 "Yaratiliş" 而非 "Yaratılış"）；`el_fpb` 和各 `grc_*` 版本没有重音符号，并以 `σ` 代替词尾的 `ς`；`nl_nld1939` 将启示录写作 "Apokalyps"；`kk_qazbi`（哈萨克语）使用缩写书名；`lv_lg8`（拉脱维亚语）使用 "Mateja ev." 之类的形式；`om_onocv`（奥罗莫语）有两个书名（创世记和诗篇）的音译可能存疑。

### XML

XML 文件采用 UTF-8 编码，结构如下：

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

JSON 文件同样采用 UTF-8 编码，结构如下：

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

章和节的编号可以通过数组下标获得。

### 许可证和版权呢？

本项目的代码和数据依据 [MIT 许可证](LICENSE) 发布。所有圣经版本均归其各自所有者所有，所有权利归所有者保留。

### 我如何帮助这个项目？

你可以审阅代码、改进数据结构，或参与新版本的制作。欢迎任何形式的帮助！ :)

### 我可以向项目捐款吗？

当然可以！你可以通过 [PayPal](https://www.paypal.com/cgi-bin/webscr?cmd=_donations&business=A9FM66AQT672L&lc=US&item_name=Bible%20Sources&currency_code=USD&bn=PP%2dDonationsBF%3abtn_donateCC_LG%2egif%3aNonHosted) 自愿捐款。

<a href="https://www.paypal.com/cgi-bin/webscr?cmd=_donations&business=A9FM66AQT672L&lc=US&item_name=Bible%20Sources&currency_code=USD&bn=PP%2dDonationsBF%3abtn_donateCC_LG%2egif%3aNonHosted"><img src="assets/paypal-donate-button.png" alt="Donate" width="400"></a>
