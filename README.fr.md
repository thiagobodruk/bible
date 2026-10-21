**Français** · [English](README.md) · [Português (Brasil)](README.pt-br.md) · [Español](README.es.md) · [Italiano](README.it.md) · [Deutsch](README.de.md) · [日本語](README.ja.md) · [简体中文](README.zh-cn.md)

# Bible: XML and JSON

**141 versions de la Bible en 85 langues 🇧🇷 🇬🇧 🇪🇸 🇨🇳 🇸🇦 🇫🇷 🇩🇪**

JSON et XML propres et structurés pour les applications bibliques, la recherche de versets et les jeux de données NLP/IA.

[![Stars](https://badgen.net/github/stars/thiagobodruk/bible?color=yellow)](https://github.com/thiagobodruk/bible/stargazers)
[![Languages](https://img.shields.io/badge/dynamic/json?url=https://raw.githubusercontent.com/thiagobodruk/bible/master/json/index.json&query=$.length&label=languages)](#)
![Versions](https://img.shields.io/badge/versions-141-blue)
[![License: MIT](https://img.shields.io/github/license/thiagobodruk/bible)](LICENSE)
![Formats](https://img.shields.io/badge/formats-JSON%20%7C%20XML-red)

[Versions](#quelles-langues-et-versions-le-projet-couvre-t-il-) · [Format des fichiers](#comment-les-fichiers-sont-ils-structurés-) · [Prêt pour l'IA / les LLM](#-prêt-pour-lia--les-llm) · [Wiki](https://github.com/thiagobodruk/bible/wiki) · [Discussions](https://github.com/thiagobodruk/bible/discussions)

---

> "Et cet Évangile de la Souveraineté de Dieu sera prêché par toute la terre, pour servir de témoignage à toutes les nations; et alors la fin arrivera."
> — Matthieu 24:14 (Bible de l'Épée)

### 🤖 Prêt pour l'IA / les LLM

Du JSON et du XML propres, structurés verset par verset — sans HTML, sans bruit de balisage, sans artefacts de scraping. Les mêmes abréviations canoniques des livres sont utilisées pour toutes les langues et toutes les versions : les versets s'alignent donc immédiatement pour les embeddings, les pipelines RAG, le fine-tuning et les tâches d'alignement multilingue. Code sous licence MIT et textes issus de sources permissives, prêts à alimenter un jeu de données ou une fenêtre de contexte.

Vous voulez créer une application biblique ? Pourquoi pas une API de recherche de versets ? Vous pouvez désormais le faire avec des sources dans votre propre langue ! L'objectif principal de ce projet est de permettre aux gens de créer des applications liées à la Bible en XML et JSON. Cette idée vous plaît ? Aidez-nous à aller encore plus loin. **Soutenez ce projet ! :)**

<a href="https://www.paypal.com/cgi-bin/webscr?cmd=_donations&business=A9FM66AQT672L&lc=US&item_name=Bible%20Sources&currency_code=USD&bn=PP%2dDonationsBF%3abtn_donateCC_LG%2egif%3aNonHosted"><img src="assets/paypal-donate-button.png" alt="Donate" width="400"></a>

## Comment les fichiers ont-ils été générés ?

Les fichiers sources ont été générés par un crawler écrit en Python. Ils peuvent donc contenir de petits problèmes d'encodage et de syntaxe.

## Quelles langues et versions le projet couvre-t-il ?

| Langue | Version | Fichiers | Remarques |
|---|---|---|---|
| 🇿🇦 Afrikaans | Afrikaans 1933/1953 | `af_afr53` |  |
| 🇬🇭 Akan | Akuapem Twi Contemporary Bible | `ak_wakna` | |
| 🇦🇱 Albanian | Bibla Shqip 1994 | `sq_albb` | |
| 🇬🇷 Ancient Greek | Textus Receptus (Η Καινή Διαθήκη) | `grc_grctr` | Nouveau Testament uniquement (27 livres) |
| 🇬🇷 Ancient Greek | Septuagint, Brenton (μετάφραση των εβδομήκοντα) | `grc_grcbrent` | Ancien Testament uniquement (36 livres), Septante grecque ; Proverbes 30 est vide dans la numérotation de cette édition; Malachie compte 3 chapitres au lieu de 4 dans cette édition |
| 🇸🇦 Arabic | Ketab El Hayat Majani | `ar_kehm` | |
| 🇦🇲 Armenian | Նոր Էջմիածին Աստվածաշունչ (New Etchmiadzin Bible) | `hy_neb` | Incomplète, 64 livres sur 66 (Esther et Daniel manquent); Malachie compte 3 chapitres au lieu de 4 dans cette édition |
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
| 🇧🇷 Brazilian Portuguese | Bíblia Sagrada Ave-Maria | `pt_avm` | Malachie compte 3 chapitres au lieu de 4 dans cette édition |
| 🇧🇷 Brazilian Portuguese | Bíblia Sagrada: Versão Fácil de Ler | `pt_vfl` | |
| 🇧🇷 Brazilian Portuguese | Edição Pastoral | `pt_pastoral` | Malachie compte 3 chapitres au lieu de 4 dans cette édition |
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
| 🇧🇷 Brazilian Portuguese | Tradução do Pe. Matos Soares | `pt_matos` | Malachie compte 3 chapitres au lieu de 4 dans cette édition |
| 🇧🇬 Bulgarian | Veren | `bg_vbg` | |
| 🇲🇲 Burmese | Judson Bible | `my_jbmle` | |
| 🇦🇩 Catalan | Bíblia Catalana Interconfessional | `ca_bci` | Malachie compte 3 chapitres au lieu de 4 dans cette édition |
| 🇵🇭 Cebuano | Ang Pulong sa Dios | `ceb_oapd` |  |
| 🇮🇶 Central Kurdish | Kurdi Sorani Standard Version | `ckb_okss` | |
| 🇨🇳 Chinese | Chinese Union Version (New Punctuation, Shen Edition) | `zh_cunpss-shen` | |
| 🇨🇳 Chinese | New Chinese Version | `zh_cnvs` | |
| 🇭🇷 Croatian | Knjiga o Kristu | `hr_okok` | Nouveau Testament uniquement (27 livres) |
| 🇨🇿 Czech | Bible Kralická 1613 | `cs_bkr` | |
| 🇳🇱 Dutch | De Heilige Schrift, Petrus Canisiusvertaling, 1939 | `nl_nld1939` | Incomplète, 64 livres sur 66 (Esther et Daniel manquent) |
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
| 🇬🇧 English | The Orthodox Jewish Bible | `en_tojb2011` | Malachie compte 3 chapitres au lieu de 4 dans cette édition |
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
| 🇪🇪 Estonian | Vaba kasutusega Uus Testament, Pühakiri kaasaegses eesti keeles | `et_opkek` | Nouveau Testament uniquement (27 livres) |
| 🇬🇭 Ewe | Ewe Contemporary Scriptures | `ee_oal` | |
| 🇵🇭 Filipino | Ang Biblia 1905 | `tl_abtag` | |
| 🇫🇮 Finnish | Kirkkoraamattu 1933/38 | `fi_fb38` | |
| 🇫🇷 French | Le Bible de I'Épée | `fr_apee` | |
| 🇩🇪 German | Schlachter 1951 | `de_sch1951` | |
| 🇬🇷 Greek | Modern Greek (Demotic) | `el_fpb` | |
| 🇮🇳 Gujarati | Indian Revised Version (IRV) Gujarati 2019 | `gu_irvguj` | |
| 🇭🇹 Haitian Creole | Bib Sen An: Kreyòl Ayisyen | `ht_bsa` | |
| 🇳🇬 Hausa | Hausa Contemporary Bible | `ha_bsrk` | |
| 🇮🇱 Hebrew | Westminster Leningrad Codex (WLC) | `he_wlc` | Ancien Testament uniquement (39 livres), avec voyelles et signes de cantillation; Malachie compte 3 chapitres au lieu de 4 dans cette édition |
| 🇮🇳 Hindi | Indian Revised Version (IRV) Hindi 2019 | `hi_irvhin` | |
| 🇭🇺 Hungarian | Károli 1908 | `hu_hunk` | |
| 🇮🇸 Icelandic | Opna Lifandi Orð: Nýja testamentið og Sálmarnir | `is_olo` | Nouveau Testament et Psaumes uniquement (28 livres) |
| 🇳🇬 Igbo | Igbo Contemporary Bible | `ig_biuo` | |
| 🇮🇩 Indonesian | Alkitab Terjemahan Sederhana Indonesia, Edisi Ketiga (TSI) | `id_tsi` | Incomplète, 48 livres sur 66 (21 livres de l'Ancien Testament et le Nouveau Testament complet) |
| 🇮🇹 Italian | Sacra Bibbia Versione Riveduta 2020 | `it_irb20` | |
| 🇯🇵 Japanese | 聖書 新共同訳 (Shinkyodoyaku) | `ja_jniv` | Malachie compte 3 chapitres au lieu de 4 dans cette édition |
| 🇮🇳 Kannada | Indian Revised Version (IRV) Kannada 2019 | `kn_irvkan` | |
| 🇰🇿 Kazakh | Киелі кітап | `kk_qazbi` | |
| 🇰🇪 Kikuyu | Kiugo Gĩtheru Kĩa Ngai Kĩhingũre | `ki_kgnk` | |
| 🇷🇼 Kinyarwanda | Rufumbira New Testament | `rw_ruf` | Nouveau Testament uniquement (27 livres) |
| 🇧🇮 Kirundi | Kirundi Contemporary Bible | `rn_obkc` | |
| 🇰🇷 Korean | Korean Revised | `ko_krv` | |
| 🇻🇦 Latin | Vulgata Latina | `la_vulg` | |
| 🇱🇻 Latvian | Glika Bībele | `lv_lg8` | |
| 🇨🇩 Lingala | Lingala Contemporary Bible | `ln_smnb` | Malachie compte 3 chapitres au lieu de 4 dans cette édition |
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
| 🇷🇺 Russian | Синодальный перевод (Synodal Translation) | `ru_synod` | Incomplète, 64 livres sur 66 (Esther et Daniel manquent) — voir `json/ru_synod.disclaimer.txt` |
| 🇮🇳 Sanskrit | Sanskrit Bible (सत्यवेदः) | `sa_san-dn` | Nouveau Testament uniquement (27 livres), en écriture devanagari |
| 🏴󠁧󠁢󠁳󠁣󠁴󠁿 Scottish Gaelic | Am Bìoball Gàidhlig 1992 | `gd_abg1992` | |
| 🇷🇸 Serbian | Daničić-Karadžić | `sr_dk` | |
| 🇿🇼 Shona | Shona Contemporary Bible 2017 | `sn_bdrsc` | |
| 🇸🇰 Slovak | Nádej pre každého | `sk_onpk` | Nouveau Testament uniquement (27 livres) |
| 🇪🇸 Spanish | Reina Valera 1960 | `es_rvr1960` | |
| 🇰🇪 Swahili | Swahili Revised Union Version | `sw_sruv` | |
| 🇸🇪 Swedish | Svenska Folkbibeln 2015 | `sv_sfb15` | |
| 🇮🇳 Tamil | Indian Revised Version (IRV) Tamil | `ta_irvtam` | |
| 🇮🇳 Telugu | Indian Revised Version (IRV) Telugu 2019 | `te_irvtel` | |
| 🇹🇭 Thai | Thai KJV | `th_kjvthai` | |
| 🇹🇴 Tongan | Ko e Tohi Tapu Kātoa | `to_rwv` | |
| 🇧🇼 Tswana | Lefoko: La Botshelo Kgolagano e Ntsha | `tn_olef` | Nouveau Testament uniquement (27 livres) |
| 🇹🇷 Turkish | Yorumsuz Türkçe Çeviri | `tr_ytc` | |
| 🇺🇦 Ukrainian | Бібліка Відкрита Новий Переклад Українською (Biblica Open New Ukrainian Translation) | `uk_vnpu` | Nouveau Testament et Psaumes uniquement (28 livres) |
| 🇵🇰 Urdu | Indian Revised Version (IRV) Urdu 2019 | `ur_irvurd` | Le texte est en écriture dévanagari et non en perso-arabe — c'est ainsi que la source elle-même publie cette édition, destinée aux locuteurs d'ourdou qui lisent le dévanagari |
| 🇻🇳 Vietnamese | Tiếng Việt | `vi_vie` | |
| 🇮🇱 Yiddish | Orthodox Yiddish Tanakh (ארטאדאקסישע יידישע תּנ״ך) | `yi_oytanakh` | Ancien Testament uniquement (39 livres); Malachie compte 3 chapitres au lieu de 4 dans cette édition |
| 🇳🇬 Yoruba | Yoruba Contemporary Bible | `yo_oycb` | |

Les fichiers de chaque entrée sont `json/<code>.json` et `xml/<code>.xml` (par exemple `json/pt_nvi.json` et `xml/pt_nvi.xml`). `json/index.json` liste ce même catalogue sous forme lisible par machine.

## Comment les fichiers sont-ils structurés ?

> **Noms des livres :** depuis la v3.0, `name` (JSON) et `n` (XML) contiennent le nom du livre dans la langue de chaque version — par exemple `Genesis` dans `en_kjv` et `創世記` dans `ja_jniv`. Jusqu'à la v2.3, presque tous les fichiers portaient le nom en portugais. `abbrev` est l'identifiant stable entre les langues, et [`json/book_names.json`](json/book_names.json) liste les noms de toutes les versions. `sa_san-dn` et `fr_apee` conservent des noms en anglais.

### XML

Les fichiers XML sont encodés en UTF-8 et construits selon la structure suivante :

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

Les fichiers JSON sont eux aussi encodés en UTF-8 et construits selon la structure suivante :

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

Le numéro du chapitre et du verset s'obtient à partir de l'index du tableau.

### Et la licence et les droits d'auteur ?

Le code et les données de ce projet sont distribués sous la [licence MIT](LICENSE). Toutes les versions de la Bible appartiennent à leurs propriétaires respectifs. Tous droits réservés à leurs propriétaires.

### Comment puis-je aider le projet ?

Vous pouvez relire le code, améliorer les structures ou travailler sur de nouvelles versions. Toute aide est la bienvenue ! :)

### Puis-je faire un don au projet ?

Oui ! Vous pouvez faire un don volontaire via [PayPal](https://www.paypal.com/cgi-bin/webscr?cmd=_donations&business=A9FM66AQT672L&lc=US&item_name=Bible%20Sources&currency_code=USD&bn=PP%2dDonationsBF%3abtn_donateCC_LG%2egif%3aNonHosted).

<a href="https://www.paypal.com/cgi-bin/webscr?cmd=_donations&business=A9FM66AQT672L&lc=US&item_name=Bible%20Sources&currency_code=USD&bn=PP%2dDonationsBF%3abtn_donateCC_LG%2egif%3aNonHosted"><img src="assets/paypal-donate-button.png" alt="Donate" width="400"></a>
