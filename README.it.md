**Italiano** · [English](README.md) · [Português (Brasil)](README.pt-br.md) · [Español](README.es.md) · [Français](README.fr.md) · [Deutsch](README.de.md) · [日本語](README.ja.md) · [简体中文](README.zh-cn.md)

# Bible: XML and JSON

**141 versioni della Bibbia in 85 lingue 🇧🇷 🇬🇧 🇪🇸 🇨🇳 🇸🇦 🇫🇷 🇩🇪**

JSON e XML puliti e strutturati per app bibliche, ricerca di versetti e dataset NLP/IA.

📖 **Vuoi solo leggere?** Prova **[Open Bible](https://thiagobodruk.github.io/open-bible/)**, un lettore della Bibbia gratuito basato su questi dati. Funziona offline, si installa come app e non richiede un account. ([codice sorgente](https://github.com/thiagobodruk/open-bible))

[![Stars](https://badgen.net/github/stars/thiagobodruk/bible?color=yellow)](https://github.com/thiagobodruk/bible/stargazers)
[![Languages](https://img.shields.io/badge/dynamic/json?url=https://raw.githubusercontent.com/thiagobodruk/bible/master/json/index.json&query=$.length&label=languages)](#)
![Versions](https://img.shields.io/badge/versions-141-blue)
[![License: MIT](https://img.shields.io/github/license/thiagobodruk/bible)](LICENSE)
![Formats](https://img.shields.io/badge/formats-JSON%20%7C%20XML-red)

[Versioni](#quali-lingue-e-versioni-copre-il-progetto) · [Formato dei file](#come-sono-strutturati-i-file) · [Pronto per IA / LLM](#-pronto-per-ia--llm) · [Wiki](https://github.com/thiagobodruk/bible/wiki) · [Discussioni](https://github.com/thiagobodruk/bible/discussions)

---

> "E questo evangelo del regno sarà predicato per tutto il mondo, affinché ne sia resa testimonianza a tutte le genti; allora verrà la fine."
> — Matteo 24:14 (IRB20)

### 🤖 Pronto per IA / LLM

JSON e XML puliti e strutturati per versetto — niente HTML, niente rumore di markup, niente artefatti di scraping. Le stesse abbreviazioni canoniche dei libri sono usate in tutte le lingue e versioni, quindi i versetti si allineano subito per embedding, pipeline RAG, fine-tuning e attività di allineamento multilingue. Codice con licenza MIT e testi da fonti permissive, pronti per entrare in un dataset o in una finestra di contesto.

Vuoi creare un'app biblica? E che ne dici di un'API per la ricerca dei versetti? Ora puoi farlo con fonti nella tua lingua! L'obiettivo principale di questo progetto è permettere alle persone di creare app legate alla Bibbia usando XML e JSON. Ti piace l'idea? Aiutaci ad andare ancora più lontano. **Sostieni questo progetto! :)**

<a href="https://www.paypal.com/cgi-bin/webscr?cmd=_donations&business=A9FM66AQT672L&lc=US&item_name=Bible%20Sources&currency_code=USD&bn=PP%2dDonationsBF%3abtn_donateCC_LG%2egif%3aNonHosted"><img src="assets/paypal-donate-button.png" alt="Donate" width="400"></a>

## Come sono stati generati i file?

I file sorgente sono stati generati con un crawler scritto in Python. Per questo possono contenere piccoli problemi di codifica e di sintassi.

## Quali lingue e versioni copre il progetto?

| Lingua | Versione | File | Note |
|---|---|---|---|
| 🇿🇦 Afrikaans | Afrikaans 1933/1953 | `af_afr53` |  |
| 🇬🇭 Akan | Akuapem Twi Contemporary Bible | `ak_wakna` | |
| 🇦🇱 Albanian | Bibla Shqip 1994 | `sq_albb` | |
| 🇬🇷 Ancient Greek | Textus Receptus (Η Καινή Διαθήκη) | `grc_grctr` | Solo il Nuovo Testamento (27 libri) |
| 🇬🇷 Ancient Greek | Septuagint, Brenton (μετάφραση των εβδομήκοντα) | `grc_grcbrent` | Solo l'Antico Testamento (36 libri), Settanta greca; Proverbi 30 è vuoto nella numerazione di questa edizione; Malachia ha 3 capitoli invece di 4 in questa edizione |
| 🇸🇦 Arabic | Ketab El Hayat Majani | `ar_kehm` | |
| 🇦🇲 Armenian | Նոր Էջմիածին Աստվածաշունչ (New Etchmiadzin Bible) | `hy_neb` | Incompleta, 64 libri su 66 (mancano Ester e Daniele); Malachia ha 3 capitoli invece di 4 in questa edizione |
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
| 🇧🇷 Brazilian Portuguese | Bíblia Sagrada Ave-Maria | `pt_avm` | Malachia ha 3 capitoli invece di 4 in questa edizione |
| 🇧🇷 Brazilian Portuguese | Bíblia Sagrada: Versão Fácil de Ler | `pt_vfl` | |
| 🇧🇷 Brazilian Portuguese | Edição Pastoral | `pt_pastoral` | Malachia ha 3 capitoli invece di 4 in questa edizione |
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
| 🇧🇷 Brazilian Portuguese | Tradução do Pe. Matos Soares | `pt_matos` | Malachia ha 3 capitoli invece di 4 in questa edizione |
| 🇧🇬 Bulgarian | Veren | `bg_vbg` | |
| 🇲🇲 Burmese | Judson Bible | `my_jbmle` | |
| 🇦🇩 Catalan | Bíblia Catalana Interconfessional | `ca_bci` | Malachia ha 3 capitoli invece di 4 in questa edizione |
| 🇵🇭 Cebuano | Ang Pulong sa Dios | `ceb_oapd` |  |
| 🇮🇶 Central Kurdish | Kurdi Sorani Standard Version | `ckb_okss` | |
| 🇨🇳 Chinese | Chinese Union Version (New Punctuation, Shen Edition) | `zh_cunpss-shen` | |
| 🇨🇳 Chinese | New Chinese Version | `zh_cnvs` | |
| 🇭🇷 Croatian | Knjiga o Kristu | `hr_okok` | Solo il Nuovo Testamento (27 libri) |
| 🇨🇿 Czech | Bible Kralická 1613 | `cs_bkr` | |
| 🇳🇱 Dutch | De Heilige Schrift, Petrus Canisiusvertaling, 1939 | `nl_nld1939` | Incompleta, 64 libri su 66 (mancano Ester e Daniele) |
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
| 🇬🇧 English | The Orthodox Jewish Bible | `en_tojb2011` | Malachia ha 3 capitoli invece di 4 in questa edizione |
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
| 🇪🇪 Estonian | Vaba kasutusega Uus Testament, Pühakiri kaasaegses eesti keeles | `et_opkek` | Solo il Nuovo Testamento (27 libri) |
| 🇬🇭 Ewe | Ewe Contemporary Scriptures | `ee_oal` | |
| 🇵🇭 Filipino | Ang Biblia 1905 | `tl_abtag` | |
| 🇫🇮 Finnish | Kirkkoraamattu 1933/38 | `fi_fb38` | |
| 🇫🇷 French | Le Bible de I'Épée | `fr_apee` | |
| 🇩🇪 German | Schlachter 1951 | `de_sch1951` | |
| 🇬🇷 Greek | Modern Greek (Demotic) | `el_fpb` | |
| 🇮🇳 Gujarati | Indian Revised Version (IRV) Gujarati 2019 | `gu_irvguj` | |
| 🇭🇹 Haitian Creole | Bib Sen An: Kreyòl Ayisyen | `ht_bsa` | |
| 🇳🇬 Hausa | Hausa Contemporary Bible | `ha_bsrk` | |
| 🇮🇱 Hebrew | Westminster Leningrad Codex (WLC) | `he_wlc` | Solo l'Antico Testamento (39 libri), con vocali e segni di cantillazione; Malachia ha 3 capitoli invece di 4 in questa edizione |
| 🇮🇳 Hindi | Indian Revised Version (IRV) Hindi 2019 | `hi_irvhin` | |
| 🇭🇺 Hungarian | Károli 1908 | `hu_hunk` | |
| 🇮🇸 Icelandic | Opna Lifandi Orð: Nýja testamentið og Sálmarnir | `is_olo` | Solo il Nuovo Testamento e i Salmi (28 libri) |
| 🇳🇬 Igbo | Igbo Contemporary Bible | `ig_biuo` | |
| 🇮🇩 Indonesian | Alkitab Terjemahan Sederhana Indonesia, Edisi Ketiga (TSI) | `id_tsi` | Incompleta, 48 libri su 66 (21 libri dell'Antico Testamento e il Nuovo Testamento completo) |
| 🇮🇹 Italian | Sacra Bibbia Versione Riveduta 2020 | `it_irb20` | |
| 🇯🇵 Japanese | 聖書 新共同訳 (Shinkyodoyaku) | `ja_jniv` | Malachia ha 3 capitoli invece di 4 in questa edizione |
| 🇮🇳 Kannada | Indian Revised Version (IRV) Kannada 2019 | `kn_irvkan` | |
| 🇰🇿 Kazakh | Киелі кітап | `kk_qazbi` | |
| 🇰🇪 Kikuyu | Kiugo Gĩtheru Kĩa Ngai Kĩhingũre | `ki_kgnk` | |
| 🇷🇼 Kinyarwanda | Rufumbira New Testament | `rw_ruf` | Solo il Nuovo Testamento (27 libri) |
| 🇧🇮 Kirundi | Kirundi Contemporary Bible | `rn_obkc` | |
| 🇰🇷 Korean | Korean Revised | `ko_krv` | |
| 🇻🇦 Latin | Vulgata Latina | `la_vulg` | |
| 🇱🇻 Latvian | Glika Bībele | `lv_lg8` | |
| 🇨🇩 Lingala | Lingala Contemporary Bible | `ln_smnb` | Malachia ha 3 capitoli invece di 4 in questa edizione |
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
| 🇷🇺 Russian | Синодальный перевод (Synodal Translation) | `ru_synod` | Incompleta, 64 libri su 66 (mancano Ester e Daniele) — vedi `json/ru_synod.disclaimer.txt` |
| 🇮🇳 Sanskrit | Sanskrit Bible (सत्यवेदः) | `sa_san-dn` | Solo il Nuovo Testamento (27 libri), in scrittura devanagari |
| 🏴󠁧󠁢󠁳󠁣󠁴󠁿 Scottish Gaelic | Am Bìoball Gàidhlig 1992 | `gd_abg1992` | |
| 🇷🇸 Serbian | Daničić-Karadžić | `sr_dk` | |
| 🇿🇼 Shona | Shona Contemporary Bible 2017 | `sn_bdrsc` | |
| 🇸🇰 Slovak | Nádej pre každého | `sk_onpk` | Solo il Nuovo Testamento (27 libri) |
| 🇪🇸 Spanish | Reina Valera 1960 | `es_rvr1960` | |
| 🇰🇪 Swahili | Swahili Revised Union Version | `sw_sruv` | |
| 🇸🇪 Swedish | Svenska Folkbibeln 2015 | `sv_sfb15` | |
| 🇮🇳 Tamil | Indian Revised Version (IRV) Tamil | `ta_irvtam` | |
| 🇮🇳 Telugu | Indian Revised Version (IRV) Telugu 2019 | `te_irvtel` | |
| 🇹🇭 Thai | Thai KJV | `th_kjvthai` | |
| 🇹🇴 Tongan | Ko e Tohi Tapu Kātoa | `to_rwv` | |
| 🇧🇼 Tswana | Lefoko: La Botshelo Kgolagano e Ntsha | `tn_olef` | Solo il Nuovo Testamento (27 libri) |
| 🇹🇷 Turkish | Yorumsuz Türkçe Çeviri | `tr_ytc` | |
| 🇺🇦 Ukrainian | Бібліка Відкрита Новий Переклад Українською (Biblica Open New Ukrainian Translation) | `uk_vnpu` | Solo il Nuovo Testamento e i Salmi (28 libri) |
| 🇵🇰 Urdu | Indian Revised Version (IRV) Urdu 2019 | `ur_irvurd` | Il testo è in scrittura devanagari e non perso-araba — è così che la fonte stessa pubblica questa edizione, destinata ai parlanti di urdu che leggono il devanagari |
| 🇻🇳 Vietnamese | Tiếng Việt | `vi_vie` | |
| 🇮🇱 Yiddish | Orthodox Yiddish Tanakh (ארטאדאקסישע יידישע תּנ״ך) | `yi_oytanakh` | Solo l'Antico Testamento (39 libri); Malachia ha 3 capitoli invece di 4 in questa edizione |
| 🇳🇬 Yoruba | Yoruba Contemporary Bible | `yo_oycb` | |

I file di ogni voce sono `json/<code>.json` e `xml/<code>.xml` (ad esempio `json/pt_nvi.json` e `xml/pt_nvi.xml`). `json/index.json` elenca lo stesso catalogo in forma leggibile da macchina.

## Come sono strutturati i file?

> **Nomi dei libri:** dalla v3.0, `name` (JSON) e `n` (XML) contengono il nome del libro nella lingua di ciascuna versione — ad esempio `Genesis` in `en_kjv` e `創世記` in `ja_jniv`. Fino alla v2.3, quasi tutti i file riportavano il nome in portoghese. `abbrev` è l'identificatore stabile tra le lingue, e [`json/book_names.json`](json/book_names.json) elenca i nomi di tutte le versioni. `sa_san-dn` e `fr_apee` mantengono nomi in inglese.
>
> Alcuni nomi sono mantenuti esattamente come li pubblica ciascuna edizione e possono sembrare insoliti: `tr_ytc` (turco) ha perso la `ı` senza punto e alcuni accenti ("Yaratiliş" invece di "Yaratılış"); `el_fpb` e le edizioni `grc_*` non hanno accenti e usano `σ` al posto della `ς` finale; `nl_nld1939` chiama l'Apocalisse "Apokalyps"; `kk_qazbi` (kazako) usa nomi abbreviati; `lv_lg8` (lettone) usa forme come "Mateja ev."; e due nomi di `om_onocv` (oromo, Genesi e Salmi) potrebbero essere traslitterazioni dubbie.

### XML

I file XML sono codificati in UTF-8 e hanno la seguente struttura:

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

Anche i file JSON sono codificati in UTF-8 e hanno la seguente struttura:

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

Il numero del capitolo e del versetto si ricava dall'indice dell'array.

### E la licenza e il diritto d'autore?

Il codice e i dati di questo progetto sono distribuiti con la [Licenza MIT](LICENSE). Tutte le versioni della Bibbia sono di proprietà dei rispettivi titolari. Tutti i diritti riservati ai titolari.

### Come posso aiutare il progetto?

Puoi rivedere il codice, migliorare le strutture o lavorare su nuove versioni. Ogni aiuto è benvenuto! :)

### Posso donare al progetto?

Sì! Puoi fare una donazione volontaria tramite [PayPal](https://www.paypal.com/cgi-bin/webscr?cmd=_donations&business=A9FM66AQT672L&lc=US&item_name=Bible%20Sources&currency_code=USD&bn=PP%2dDonationsBF%3abtn_donateCC_LG%2egif%3aNonHosted).

<a href="https://www.paypal.com/cgi-bin/webscr?cmd=_donations&business=A9FM66AQT672L&lc=US&item_name=Bible%20Sources&currency_code=USD&bn=PP%2dDonationsBF%3abtn_donateCC_LG%2egif%3aNonHosted"><img src="assets/paypal-donate-button.png" alt="Donate" width="400"></a>
