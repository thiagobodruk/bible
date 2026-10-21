**Deutsch** · [English](README.md) · [Português (Brasil)](README.pt-br.md) · [Español](README.es.md) · [Français](README.fr.md) · [Italiano](README.it.md) · [日本語](README.ja.md) · [简体中文](README.zh-cn.md)

# Bible: XML and JSON

**141 Bibelversionen in 85 Sprachen 🇧🇷 🇬🇧 🇪🇸 🇨🇳 🇸🇦 🇫🇷 🇩🇪**

Saubere, strukturierte JSON- und XML-Dateien für Bibel-Apps, Versesuchen und NLP-/KI-Datensätze.

[![Stars](https://badgen.net/github/stars/thiagobodruk/bible?color=yellow)](https://github.com/thiagobodruk/bible/stargazers)
[![Languages](https://img.shields.io/badge/dynamic/json?url=https://raw.githubusercontent.com/thiagobodruk/bible/master/json/index.json&query=$.length&label=languages)](#)
![Versions](https://img.shields.io/badge/versions-141-blue)
[![License: MIT](https://img.shields.io/github/license/thiagobodruk/bible)](LICENSE)
![Formats](https://img.shields.io/badge/formats-JSON%20%7C%20XML-red)

[Versionen](#welche-sprachen-und-versionen-deckt-das-projekt-ab) · [Dateiformat](#wie-sind-die-dateien-aufgebaut) · [KI- / LLM-bereit](#-ki---llm-bereit) · [Wiki](https://github.com/thiagobodruk/bible/wiki) · [Diskussionen](https://github.com/thiagobodruk/bible/discussions)

---

> "Und dieses Evangelium vom Reich wird in der ganzen Welt gepredigt werden, zum Zeugnis allen Völkern, und dann wird das Ende kommen."
> — Matthäus 24,14 (Schlachter 1951)

### 🤖 KI- / LLM-bereit

Saubere, vers-weise strukturierte JSON- und XML-Dateien — ohne HTML, ohne Markup-Rauschen, ohne Scraping-Artefakte. Für alle Sprachen und Versionen werden dieselben kanonischen Buchkürzel verwendet, sodass sich die Verse sofort für Embeddings, RAG-Pipelines, Fine-Tuning und sprachübergreifende Alignment-Aufgaben abgleichen lassen. MIT-lizenzierter Code mit Texten aus permissiven Quellen, bereit für ein Dataset oder ein Kontextfenster.

Möchtest du eine Bibel-App entwickeln? Oder eine API für die Versesuche? Jetzt geht das mit Quellen in deiner eigenen Sprache! Das Hauptziel dieses Projekts ist es, Menschen die Entwicklung bibelbezogener Apps mit XML und JSON zu ermöglichen. Gefällt dir die Idee? Hilf uns, noch weiterzugehen. **Unterstütze dieses Projekt! :)**

<a href="https://www.paypal.com/cgi-bin/webscr?cmd=_donations&business=A9FM66AQT672L&lc=US&item_name=Bible%20Sources&currency_code=USD&bn=PP%2dDonationsBF%3abtn_donateCC_LG%2egif%3aNonHosted"><img src="assets/paypal-donate-button.png" alt="Donate" width="400"></a>

## Wie wurden die Dateien erstellt?

Die Quelldateien wurden mit einem in Python geschriebenen Crawler erzeugt. Daher können sie kleinere Probleme bei Kodierung und Syntax enthalten.

## Welche Sprachen und Versionen deckt das Projekt ab?

| Sprache | Version | Dateien | Hinweise |
|---|---|---|---|
| 🇿🇦 Afrikaans | Afrikaans 1933/1953 | `af_afr53` |  |
| 🇬🇭 Akan | Akuapem Twi Contemporary Bible | `ak_wakna` | |
| 🇦🇱 Albanian | Bibla Shqip 1994 | `sq_albb` | |
| 🇬🇷 Ancient Greek | Textus Receptus (Η Καινή Διαθήκη) | `grc_grctr` | Nur das Neue Testament (27 Bücher) |
| 🇬🇷 Ancient Greek | Septuagint, Brenton (μετάφραση των εβδομήκοντα) | `grc_grcbrent` | Nur das Alte Testament (36 Bücher), griechische Septuaginta; Sprüche 30 ist in der Nummerierung dieser Ausgabe leer; Maleachi hat in dieser Ausgabe 3 statt 4 Kapitel |
| 🇸🇦 Arabic | Ketab El Hayat Majani | `ar_kehm` | |
| 🇦🇲 Armenian | Նոր Էջմիածին Աստվածաշունչ (New Etchmiadzin Bible) | `hy_neb` | Unvollständig, 64 von 66 Büchern (Ester und Daniel fehlen); Maleachi hat in dieser Ausgabe 3 statt 4 Kapitel |
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
| 🇧🇷 Brazilian Portuguese | Bíblia Sagrada Ave-Maria | `pt_avm` | Maleachi hat in dieser Ausgabe 3 statt 4 Kapitel |
| 🇧🇷 Brazilian Portuguese | Bíblia Sagrada: Versão Fácil de Ler | `pt_vfl` | |
| 🇧🇷 Brazilian Portuguese | Edição Pastoral | `pt_pastoral` | Maleachi hat in dieser Ausgabe 3 statt 4 Kapitel |
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
| 🇧🇷 Brazilian Portuguese | Tradução do Pe. Matos Soares | `pt_matos` | Maleachi hat in dieser Ausgabe 3 statt 4 Kapitel |
| 🇧🇬 Bulgarian | Veren | `bg_vbg` | |
| 🇲🇲 Burmese | Judson Bible | `my_jbmle` | |
| 🇦🇩 Catalan | Bíblia Catalana Interconfessional | `ca_bci` | Maleachi hat in dieser Ausgabe 3 statt 4 Kapitel |
| 🇵🇭 Cebuano | Ang Pulong sa Dios | `ceb_oapd` |  |
| 🇮🇶 Central Kurdish | Kurdi Sorani Standard Version | `ckb_okss` | |
| 🇨🇳 Chinese | Chinese Union Version (New Punctuation, Shen Edition) | `zh_cunpss-shen` | |
| 🇨🇳 Chinese | New Chinese Version | `zh_cnvs` | |
| 🇭🇷 Croatian | Knjiga o Kristu | `hr_okok` | Nur das Neue Testament (27 Bücher) |
| 🇨🇿 Czech | Bible Kralická 1613 | `cs_bkr` | |
| 🇳🇱 Dutch | De Heilige Schrift, Petrus Canisiusvertaling, 1939 | `nl_nld1939` | Unvollständig, 64 von 66 Büchern (Ester und Daniel fehlen) |
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
| 🇬🇧 English | The Orthodox Jewish Bible | `en_tojb2011` | Maleachi hat in dieser Ausgabe 3 statt 4 Kapitel |
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
| 🇪🇪 Estonian | Vaba kasutusega Uus Testament, Pühakiri kaasaegses eesti keeles | `et_opkek` | Nur das Neue Testament (27 Bücher) |
| 🇬🇭 Ewe | Ewe Contemporary Scriptures | `ee_oal` | |
| 🇵🇭 Filipino | Ang Biblia 1905 | `tl_abtag` | |
| 🇫🇮 Finnish | Kirkkoraamattu 1933/38 | `fi_fb38` | |
| 🇫🇷 French | Le Bible de I'Épée | `fr_apee` | |
| 🇩🇪 German | Schlachter 1951 | `de_sch1951` | |
| 🇬🇷 Greek | Modern Greek (Demotic) | `el_fpb` | |
| 🇮🇳 Gujarati | Indian Revised Version (IRV) Gujarati 2019 | `gu_irvguj` | |
| 🇭🇹 Haitian Creole | Bib Sen An: Kreyòl Ayisyen | `ht_bsa` | |
| 🇳🇬 Hausa | Hausa Contemporary Bible | `ha_bsrk` | |
| 🇮🇱 Hebrew | Westminster Leningrad Codex (WLC) | `he_wlc` | Nur das Alte Testament (39 Bücher), mit Vokal- und Kantillationszeichen; Maleachi hat in dieser Ausgabe 3 statt 4 Kapitel |
| 🇮🇳 Hindi | Indian Revised Version (IRV) Hindi 2019 | `hi_irvhin` | |
| 🇭🇺 Hungarian | Károli 1908 | `hu_hunk` | |
| 🇮🇸 Icelandic | Opna Lifandi Orð: Nýja testamentið og Sálmarnir | `is_olo` | Nur das Neue Testament und die Psalmen (28 Bücher) |
| 🇳🇬 Igbo | Igbo Contemporary Bible | `ig_biuo` | |
| 🇮🇩 Indonesian | Alkitab Terjemahan Sederhana Indonesia, Edisi Ketiga (TSI) | `id_tsi` | Unvollständig, 48 von 66 Büchern (21 Bücher des Alten Testaments und das vollständige Neue Testament) |
| 🇮🇹 Italian | Sacra Bibbia Versione Riveduta 2020 | `it_irb20` | |
| 🇯🇵 Japanese | 聖書 新共同訳 (Shinkyodoyaku) | `ja_jniv` | Maleachi hat in dieser Ausgabe 3 statt 4 Kapitel |
| 🇮🇳 Kannada | Indian Revised Version (IRV) Kannada 2019 | `kn_irvkan` | |
| 🇰🇿 Kazakh | Киелі кітап | `kk_qazbi` | |
| 🇰🇪 Kikuyu | Kiugo Gĩtheru Kĩa Ngai Kĩhingũre | `ki_kgnk` | |
| 🇷🇼 Kinyarwanda | Rufumbira New Testament | `rw_ruf` | Nur das Neue Testament (27 Bücher) |
| 🇧🇮 Kirundi | Kirundi Contemporary Bible | `rn_obkc` | |
| 🇰🇷 Korean | Korean Revised | `ko_krv` | |
| 🇻🇦 Latin | Vulgata Latina | `la_vulg` | |
| 🇱🇻 Latvian | Glika Bībele | `lv_lg8` | |
| 🇨🇩 Lingala | Lingala Contemporary Bible | `ln_smnb` | Maleachi hat in dieser Ausgabe 3 statt 4 Kapitel |
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
| 🇷🇺 Russian | Синодальный перевод (Synodal Translation) | `ru_synod` | Unvollständig, 64 von 66 Büchern (Ester und Daniel fehlen) — siehe `json/ru_synod.disclaimer.txt` |
| 🇮🇳 Sanskrit | Sanskrit Bible (सत्यवेदः) | `sa_san-dn` | Nur das Neue Testament (27 Bücher), in Devanagari-Schrift |
| 🏴󠁧󠁢󠁳󠁣󠁴󠁿 Scottish Gaelic | Am Bìoball Gàidhlig 1992 | `gd_abg1992` | |
| 🇷🇸 Serbian | Daničić-Karadžić | `sr_dk` | |
| 🇿🇼 Shona | Shona Contemporary Bible 2017 | `sn_bdrsc` | |
| 🇸🇰 Slovak | Nádej pre každého | `sk_onpk` | Nur das Neue Testament (27 Bücher) |
| 🇪🇸 Spanish | Reina Valera 1960 | `es_rvr1960` | |
| 🇰🇪 Swahili | Swahili Revised Union Version | `sw_sruv` | |
| 🇸🇪 Swedish | Svenska Folkbibeln 2015 | `sv_sfb15` | |
| 🇮🇳 Tamil | Indian Revised Version (IRV) Tamil | `ta_irvtam` | |
| 🇮🇳 Telugu | Indian Revised Version (IRV) Telugu 2019 | `te_irvtel` | |
| 🇹🇭 Thai | Thai KJV | `th_kjvthai` | |
| 🇹🇴 Tongan | Ko e Tohi Tapu Kātoa | `to_rwv` | |
| 🇧🇼 Tswana | Lefoko: La Botshelo Kgolagano e Ntsha | `tn_olef` | Nur das Neue Testament (27 Bücher) |
| 🇹🇷 Turkish | Yorumsuz Türkçe Çeviri | `tr_ytc` | |
| 🇺🇦 Ukrainian | Бібліка Відкрита Новий Переклад Українською (Biblica Open New Ukrainian Translation) | `uk_vnpu` | Nur das Neue Testament und die Psalmen (28 Bücher) |
| 🇵🇰 Urdu | Indian Revised Version (IRV) Urdu 2019 | `ur_irvurd` | Der Text steht in Devanagari-Schrift statt in persisch-arabischer Schrift — so veröffentlicht die Quelle selbst diese Ausgabe, die sich an Urdu-Sprecher richtet, die Devanagari lesen |
| 🇻🇳 Vietnamese | Tiếng Việt | `vi_vie` | |
| 🇮🇱 Yiddish | Orthodox Yiddish Tanakh (ארטאדאקסישע יידישע תּנ״ך) | `yi_oytanakh` | Nur das Alte Testament (39 Bücher); Maleachi hat in dieser Ausgabe 3 statt 4 Kapitel |
| 🇳🇬 Yoruba | Yoruba Contemporary Bible | `yo_oycb` | |

Die Dateien jedes Eintrags sind `json/<code>.json` und `xml/<code>.xml` (z. B. `json/pt_nvi.json` und `xml/pt_nvi.xml`). `json/index.json` listet denselben Katalog in maschinenlesbarer Form auf.

## Wie sind die Dateien aufgebaut?

> **Buchnamen:** Seit v3.0 enthalten `name` (JSON) und `n` (XML) den Buchnamen in der Sprache der jeweiligen Version — zum Beispiel `Genesis` in `en_kjv` und `創世記` in `ja_jniv`. Bis v2.3 trugen fast alle Dateien den portugiesischen Namen. `abbrev` ist der stabile Bezeichner über Sprachen hinweg, und [`json/book_names.json`](json/book_names.json) listet die Namen aller Versionen auf. `sa_san-dn` und `fr_apee` behalten englische Buchnamen.
>
> Einige Namen werden genau so beibehalten, wie die jeweilige Ausgabe sie veröffentlicht, und wirken womöglich ungewöhnlich: `tr_ytc` (Türkisch) hat das punktlose `ı` und einige Akzente verloren („Yaratiliş“ statt „Yaratılış“); `el_fpb` und die `grc_*`-Ausgaben haben keine Akzente und verwenden `σ` statt des Schluss-`ς`; `nl_nld1939` nennt die Offenbarung „Apokalyps“; `kk_qazbi` (Kasachisch) verwendet abgekürzte Namen; `lv_lg8` (Lettisch) verwendet Formen wie „Mateja ev.“; und zwei Namen in `om_onocv` (Oromo, Genesis und Psalmen) könnten zweifelhafte Transliterationen sein.

### XML

Die XML-Dateien sind UTF-8-kodiert und wie folgt aufgebaut:

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

Auch die JSON-Dateien sind UTF-8-kodiert und wie folgt aufgebaut:

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

Die Nummer von Kapitel und Vers ergibt sich aus dem Array-Index.

### Und was ist mit Lizenz und Urheberrecht?

Der Code und die Daten dieses Projekts stehen unter der [MIT-Lizenz](LICENSE). Alle Bibelversionen sind Eigentum ihrer jeweiligen Rechteinhaber. Alle Rechte liegen bei den Rechteinhabern.

### Wie kann ich das Projekt unterstützen?

Du kannst den Code prüfen, die Strukturen verbessern oder an neuen Versionen arbeiten. Jede Hilfe ist willkommen! :)

### Kann ich für das Projekt spenden?

Ja, gerne! Du kannst freiwillig über [PayPal](https://www.paypal.com/cgi-bin/webscr?cmd=_donations&business=A9FM66AQT672L&lc=US&item_name=Bible%20Sources&currency_code=USD&bn=PP%2dDonationsBF%3abtn_donateCC_LG%2egif%3aNonHosted) spenden.

<a href="https://www.paypal.com/cgi-bin/webscr?cmd=_donations&business=A9FM66AQT672L&lc=US&item_name=Bible%20Sources&currency_code=USD&bn=PP%2dDonationsBF%3abtn_donateCC_LG%2egif%3aNonHosted"><img src="assets/paypal-donate-button.png" alt="Donate" width="400"></a>
