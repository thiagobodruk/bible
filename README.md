# Bible: XML and JSON
Do you want to create a Bible based app? What about an API for Bible verses search? Now you can do this... using sources in your very own language! The main objective of this project is to allow people to create Bible related apps using XML and JSON sources in multiple Bible versions.

## Methodology
The source files were generated using a Python based crawler. Therefore, these files may contain minor issues related to encoding and syntax.

## Versions
### Arabic
* [ar_svd] The Arabic Bible

### Chinese
* [zh_cuv] Chinese Union Version
* [zh_ncv] New Chinese Version

### German
* [de_schlachter] Schlachter

### Greek
* [el_greek] Modern Greek

### English
* [en_bbe] Basic English
* [en_kjv] King James Version

### Esperanto
* [eo_esperanto] Esperanto

### Spanish
* [es_rvr] Reina Valera

### Finnish
* [fi_finnish] Finnish Bible
* [fi_pr] Pyhä Raamattu

### French
* [fr_apee] Le Bible de I'Épée

### Korean
* [ko_ko] Korean Version

### Portuguese
* [pt_aa] Almeida Revisada Imprensa Bíblica
* [pt_acf] Almeida Corrigida e Revisada Fiel
* [pt_nvi] Nova Versão Internacional

### Romanian
* [ro_cornilescu] Versiunea Dumitru Cornilescu

### Russian
* [ru_synodal] Синодальный перевод

### Vietnamese
* [vi_vietnamese] Tiếng Việt

## Structure
### XML
The XML files are encoded using UTF-8 and built in the following structure:
```
<book>
  <chapter>
    <verse>Texto</verse>
  </chapter>
</book>
```

### JSON
The JSON files are also encoded using UTF-8 and built in the following structure:
```
[
	{
	"abbrev" : "abbrev"
	"book" : "name"
	"chapters": 
		[
			{"1": {"1": "...", "2": "..."}}, {"2": {"1": "...", "2": "..."}},
			{"2": {"1": "...", "2": "..."}}, {"2": {"1": "...", "2": "..."}},
			{"3": {"1": "...", "2": "..."}}, {"2": {"1": "...", "2": "..."}}
		]
	}
]
```

### License
This project is distributed under the Creative Commons BY-NC license. All the Bible versions are property of their respective owners. All rights reserved to the owners.
