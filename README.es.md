**Español** · [English](README.md) · [Português (Brasil)](README.pt-br.md) · [Français](README.fr.md) · [Italiano](README.it.md) · [Deutsch](README.de.md) · [日本語](README.ja.md) · [简体中文](README.zh-cn.md)

# Bible: XML and JSON

**141 versiones de la Biblia en 85 idiomas 🇧🇷 🇬🇧 🇪🇸 🇨🇳 🇸🇦 🇫🇷 🇩🇪**

JSON y XML limpios y estructurados para apps bíblicas, búsqueda de versículos y datasets de NLP/IA.

📖 **¿Solo quieres leer?** Prueba **[Open Bible](https://thiagobodruk.github.io/open-bible/)**, un lector de la Biblia gratuito creado con estos datos. Funciona sin conexión, se instala como app y no requiere cuenta. ([código fuente](https://github.com/thiagobodruk/open-bible))

[![Stars](https://badgen.net/github/stars/thiagobodruk/bible?color=yellow)](https://github.com/thiagobodruk/bible/stargazers)
[![Languages](https://img.shields.io/badge/dynamic/json?url=https://raw.githubusercontent.com/thiagobodruk/bible/master/json/index.json&query=$.length&label=languages)](#)
![Versions](https://img.shields.io/badge/versions-141-blue)
[![License: MIT](https://img.shields.io/github/license/thiagobodruk/bible)](LICENSE)
![Formats](https://img.shields.io/badge/formats-JSON%20%7C%20XML-red)

[Versiones](#qué-idiomas-y-versiones-cubre-el-proyecto) · [Formato de archivos](#cómo-están-estructurados-los-archivos) · [Listo para IA / LLM](#-listo-para-ia--llm) · [Wiki](https://github.com/thiagobodruk/bible/wiki) · [Discusiones](https://github.com/thiagobodruk/bible/discussions)

---

> "Y será predicado este evangelio del reino en todo el mundo, para testimonio a todas las naciones; y entonces vendrá el fin."
> — Mateo 24:14 (RVR1960)

### 🤖 Listo para IA / LLM

JSON y XML limpios y estructurados por versículo — sin HTML, sin ruido de marcado y sin artefactos de scraping. Se usan las mismas abreviaturas canónicas de los libros en todos los idiomas y versiones, de modo que los versículos se alinean de inmediato para embeddings, pipelines de RAG, fine-tuning y tareas de alineación multilingüe. Código con licencia MIT y textos de fuentes permisivas, listos para incorporarse a un dataset o a una ventana de contexto.

¿Quieres crear una app bíblica? ¿Qué tal una API de búsqueda de versículos? ¡Ahora puedes hacerlo con fuentes en tu propio idioma! El objetivo principal de este proyecto es permitir que las personas creen apps relacionadas con la Biblia usando XML y JSON. ¿Te gusta la idea? Ayúdanos a llegar aún más lejos. **¡Apoya este proyecto! :)**

<a href="https://www.paypal.com/cgi-bin/webscr?cmd=_donations&business=A9FM66AQT672L&lc=US&item_name=Bible%20Sources&currency_code=USD&bn=PP%2dDonationsBF%3abtn_donateCC_LG%2egif%3aNonHosted"><img src="assets/paypal-donate-button.png" alt="Donate" width="400"></a>

## ¿Cómo se generaron los archivos?

Los archivos fuente se generaron con un crawler escrito en Python. Por eso, pueden contener pequeños problemas de codificación y sintaxis.

## ¿Qué idiomas y versiones cubre el proyecto?

| Idioma | Versión | Archivos | Notas |
|---|---|---|---|
| 🇿🇦 Afrikaans | Afrikaans 1933/1953 | `af_afr53` |  |
| 🇬🇭 Akan | Akuapem Twi Contemporary Bible | `ak_wakna` | |
| 🇦🇱 Albanian | Bibla Shqip 1994 | `sq_albb` | |
| 🇬🇷 Ancient Greek | Textus Receptus (Η Καινή Διαθήκη) | `grc_grctr` | Solo el Nuevo Testamento (27 libros) |
| 🇬🇷 Ancient Greek | Septuagint, Brenton (μετάφραση των εβδομήκοντα) | `grc_grcbrent` | Solo el Antiguo Testamento (36 libros), Septuaginta griega; Proverbios 30 está vacío en la numeración de esta edición; Malaquías tiene 3 capítulos en lugar de 4 en esta edición |
| 🇸🇦 Arabic | Ketab El Hayat Majani | `ar_kehm` | |
| 🇦🇲 Armenian | Նոր Էջմիածին Աստվածաշունչ (New Etchmiadzin Bible) | `hy_neb` | Incompleta, 64 de 66 libros (faltan Ester y Daniel); Malaquías tiene 3 capítulos en lugar de 4 en esta edición |
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
| 🇧🇷 Brazilian Portuguese | Bíblia Sagrada Ave-Maria | `pt_avm` | Malaquías tiene 3 capítulos en lugar de 4 en esta edición |
| 🇧🇷 Brazilian Portuguese | Bíblia Sagrada: Versão Fácil de Ler | `pt_vfl` | |
| 🇧🇷 Brazilian Portuguese | Edição Pastoral | `pt_pastoral` | Malaquías tiene 3 capítulos en lugar de 4 en esta edición |
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
| 🇧🇷 Brazilian Portuguese | Tradução do Pe. Matos Soares | `pt_matos` | Malaquías tiene 3 capítulos en lugar de 4 en esta edición |
| 🇧🇬 Bulgarian | Veren | `bg_vbg` | |
| 🇲🇲 Burmese | Judson Bible | `my_jbmle` | |
| 🇦🇩 Catalan | Bíblia Catalana Interconfessional | `ca_bci` | Malaquías tiene 3 capítulos en lugar de 4 en esta edición |
| 🇵🇭 Cebuano | Ang Pulong sa Dios | `ceb_oapd` |  |
| 🇮🇶 Central Kurdish | Kurdi Sorani Standard Version | `ckb_okss` | |
| 🇨🇳 Chinese | Chinese Union Version (New Punctuation, Shen Edition) | `zh_cunpss-shen` | |
| 🇨🇳 Chinese | New Chinese Version | `zh_cnvs` | |
| 🇭🇷 Croatian | Knjiga o Kristu | `hr_okok` | Solo el Nuevo Testamento (27 libros) |
| 🇨🇿 Czech | Bible Kralická 1613 | `cs_bkr` | |
| 🇳🇱 Dutch | De Heilige Schrift, Petrus Canisiusvertaling, 1939 | `nl_nld1939` | Incompleta, 64 de 66 libros (faltan Ester y Daniel) |
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
| 🇬🇧 English | The Orthodox Jewish Bible | `en_tojb2011` | Malaquías tiene 3 capítulos en lugar de 4 en esta edición |
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
| 🇪🇪 Estonian | Vaba kasutusega Uus Testament, Pühakiri kaasaegses eesti keeles | `et_opkek` | Solo el Nuevo Testamento (27 libros) |
| 🇬🇭 Ewe | Ewe Contemporary Scriptures | `ee_oal` | |
| 🇵🇭 Filipino | Ang Biblia 1905 | `tl_abtag` | |
| 🇫🇮 Finnish | Kirkkoraamattu 1933/38 | `fi_fb38` | |
| 🇫🇷 French | Le Bible de I'Épée | `fr_apee` | |
| 🇩🇪 German | Schlachter 1951 | `de_sch1951` | |
| 🇬🇷 Greek | Modern Greek (Demotic) | `el_fpb` | |
| 🇮🇳 Gujarati | Indian Revised Version (IRV) Gujarati 2019 | `gu_irvguj` | |
| 🇭🇹 Haitian Creole | Bib Sen An: Kreyòl Ayisyen | `ht_bsa` | |
| 🇳🇬 Hausa | Hausa Contemporary Bible | `ha_bsrk` | |
| 🇮🇱 Hebrew | Westminster Leningrad Codex (WLC) | `he_wlc` | Solo el Antiguo Testamento (39 libros), con vocalización y signos de cantilación; Malaquías tiene 3 capítulos en lugar de 4 en esta edición |
| 🇮🇳 Hindi | Indian Revised Version (IRV) Hindi 2019 | `hi_irvhin` | |
| 🇭🇺 Hungarian | Károli 1908 | `hu_hunk` | |
| 🇮🇸 Icelandic | Opna Lifandi Orð: Nýja testamentið og Sálmarnir | `is_olo` | Solo el Nuevo Testamento y los Salmos (28 libros) |
| 🇳🇬 Igbo | Igbo Contemporary Bible | `ig_biuo` | |
| 🇮🇩 Indonesian | Alkitab Terjemahan Sederhana Indonesia, Edisi Ketiga (TSI) | `id_tsi` | Incompleta, 48 de 66 libros (21 libros del Antiguo Testamento y el Nuevo Testamento completo) |
| 🇮🇹 Italian | Sacra Bibbia Versione Riveduta 2020 | `it_irb20` | |
| 🇯🇵 Japanese | 聖書 新共同訳 (Shinkyodoyaku) | `ja_jniv` | Malaquías tiene 3 capítulos en lugar de 4 en esta edición |
| 🇮🇳 Kannada | Indian Revised Version (IRV) Kannada 2019 | `kn_irvkan` | |
| 🇰🇿 Kazakh | Киелі кітап | `kk_qazbi` | |
| 🇰🇪 Kikuyu | Kiugo Gĩtheru Kĩa Ngai Kĩhingũre | `ki_kgnk` | |
| 🇷🇼 Kinyarwanda | Rufumbira New Testament | `rw_ruf` | Solo el Nuevo Testamento (27 libros) |
| 🇧🇮 Kirundi | Kirundi Contemporary Bible | `rn_obkc` | |
| 🇰🇷 Korean | Korean Revised | `ko_krv` | |
| 🇻🇦 Latin | Vulgata Latina | `la_vulg` | |
| 🇱🇻 Latvian | Glika Bībele | `lv_lg8` | |
| 🇨🇩 Lingala | Lingala Contemporary Bible | `ln_smnb` | Malaquías tiene 3 capítulos en lugar de 4 en esta edición |
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
| 🇷🇺 Russian | Синодальный перевод (Synodal Translation) | `ru_synod` | Incompleta, 64 de 66 libros (faltan Ester y Daniel) — véase `json/ru_synod.disclaimer.txt` |
| 🇮🇳 Sanskrit | Sanskrit Bible (सत्यवेदः) | `sa_san-dn` | Solo el Nuevo Testamento (27 libros), en escritura devanagari |
| 🏴󠁧󠁢󠁳󠁣󠁴󠁿 Scottish Gaelic | Am Bìoball Gàidhlig 1992 | `gd_abg1992` | |
| 🇷🇸 Serbian | Daničić-Karadžić | `sr_dk` | |
| 🇿🇼 Shona | Shona Contemporary Bible 2017 | `sn_bdrsc` | |
| 🇸🇰 Slovak | Nádej pre každého | `sk_onpk` | Solo el Nuevo Testamento (27 libros) |
| 🇪🇸 Spanish | Reina Valera 1960 | `es_rvr1960` | |
| 🇰🇪 Swahili | Swahili Revised Union Version | `sw_sruv` | |
| 🇸🇪 Swedish | Svenska Folkbibeln 2015 | `sv_sfb15` | |
| 🇮🇳 Tamil | Indian Revised Version (IRV) Tamil | `ta_irvtam` | |
| 🇮🇳 Telugu | Indian Revised Version (IRV) Telugu 2019 | `te_irvtel` | |
| 🇹🇭 Thai | Thai KJV | `th_kjvthai` | |
| 🇹🇴 Tongan | Ko e Tohi Tapu Kātoa | `to_rwv` | |
| 🇧🇼 Tswana | Lefoko: La Botshelo Kgolagano e Ntsha | `tn_olef` | Solo el Nuevo Testamento (27 libros) |
| 🇹🇷 Turkish | Yorumsuz Türkçe Çeviri | `tr_ytc` | |
| 🇺🇦 Ukrainian | Бібліка Відкрита Новий Переклад Українською (Biblica Open New Ukrainian Translation) | `uk_vnpu` | Solo el Nuevo Testamento y los Salmos (28 libros) |
| 🇵🇰 Urdu | Indian Revised Version (IRV) Urdu 2019 | `ur_irvurd` | El texto está en escritura devanagari y no en perso-árabe — así es como la propia fuente publica esta edición, dirigida a hablantes de urdu que leen devanagari |
| 🇻🇳 Vietnamese | Tiếng Việt | `vi_vie` | |
| 🇮🇱 Yiddish | Orthodox Yiddish Tanakh (ארטאדאקסישע יידישע תּנ״ך) | `yi_oytanakh` | Solo el Antiguo Testamento (39 libros); Malaquías tiene 3 capítulos en lugar de 4 en esta edición |
| 🇳🇬 Yoruba | Yoruba Contemporary Bible | `yo_oycb` | |

Los archivos de cada entrada son `json/<code>.json` y `xml/<code>.xml` (por ejemplo, `json/pt_nvi.json` y `xml/pt_nvi.xml`). `json/index.json` lista este mismo catálogo en formato legible por máquina.

## ¿Cómo están estructurados los archivos?

> **Nombres de los libros:** desde la v3.0, `name` (JSON) y `n` (XML) contienen el nombre del libro en el idioma de cada versión — por ejemplo, `Genesis` en `en_kjv` y `創世記` en `ja_jniv`. Hasta la v2.3, casi todos los archivos traían el nombre en portugués. `abbrev` es el identificador estable entre idiomas, y [`json/book_names.json`](json/book_names.json) enumera los nombres de todas las versiones. `sa_san-dn` y `fr_apee` conservan nombres en inglés.
>
> Algunos nombres se mantienen tal como los publica cada edición y pueden parecer extraños: `tr_ytc` (turco) perdió la `ı` sin punto y algunos acentos ("Yaratiliş" en lugar de "Yaratılış"); `el_fpb` y las ediciones `grc_*` no tienen acentos y usan `σ` en lugar de la `ς` final; `nl_nld1939` llama al Apocalipsis "Apokalyps"; `kk_qazbi` (kazajo) usa nombres abreviados; `lv_lg8` (letón) usa formas como "Mateja ev."; y dos nombres de `om_onocv` (oromo, Génesis y Salmos) podrían ser transliteraciones dudosas.

### XML

Los archivos XML usan codificación UTF-8 y tienen la siguiente estructura:

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

Los archivos JSON también usan UTF-8 y tienen la siguiente estructura:

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

El número de capítulo y de versículo se obtiene a partir del índice del array.

### ¿Y la licencia y los derechos de autor?

El código y los datos de este proyecto se distribuyen bajo la [Licencia MIT](LICENSE). Todas las versiones de la Biblia son propiedad de sus respectivos dueños. Todos los derechos reservados a sus dueños.

### ¿Cómo puedo ayudar al proyecto?

Puedes revisar el código, mejorar las estructuras o trabajar en nuevas versiones. ¡Toda ayuda es bienvenida! :)

### ¿Puedo donar al proyecto?

¡Sí! Puedes hacer una donación voluntaria por [PayPal](https://www.paypal.com/cgi-bin/webscr?cmd=_donations&business=A9FM66AQT672L&lc=US&item_name=Bible%20Sources&currency_code=USD&bn=PP%2dDonationsBF%3abtn_donateCC_LG%2egif%3aNonHosted).

<a href="https://www.paypal.com/cgi-bin/webscr?cmd=_donations&business=A9FM66AQT672L&lc=US&item_name=Bible%20Sources&currency_code=USD&bn=PP%2dDonationsBF%3abtn_donateCC_LG%2egif%3aNonHosted"><img src="assets/paypal-donate-button.png" alt="Donate" width="400"></a>
