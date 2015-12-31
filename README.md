# Bible: XML and JSON
Do you want to create a Bible based app? What about an API for Bible verses search? Now you can do this... using sources in your very own language! The main objective of this project is to allow people to create Bible related apps using XML and JSON sources in multiple Bible versions.

## Methodology
The source files were generated using a Python based crawler. Therefore, these files may contain minor issues related to encoding and syntax.

## Versions
#### Arabic
* The Arabic Bible (ar_svd) 

#### Chinese
* Chinese Union Version (zh_cuv)
* New Chinese Version (zh_ncv) 

#### German
* Schlachter (de_schlachter)

#### Greek
* Modern Greek (el_greek)

#### English
* Basic English (en_bbe)
* King James Version (en_kjv) 

#### Esperanto
* Esperanto (eo_esperanto)

#### Spanish
* Reina Valera (es_rvr)

#### Finnish
* Finnish Bible (fi_finnish)
* Pyhä Raamattu (fi_pr)

#### French
* Le Bible de I'Épée (fr_apee)

#### Korean
* Korean Version (ko_ko)

#### Portuguese
* Almeida Revisada Imprensa Bíblica (pt_aa) 
* Almeida Corrigida e Revisada Fiel (pt_acf) 
* Nova Versão Internacional (pt_nvi) 

#### Romanian
* Versiunea Dumitru Cornilescu (ro_cornilescu)

#### Russian
* Синодальный перевод (ru_synodal)

#### Vietnamese
* Tiếng Việt (vi_vietnamese)

## Structure
### XML
The XML files are encoded using UTF-8 and built in the following structure:
```xml
<book>
  <chapter>
    <verse>Texto</verse>
  </chapter>
</book>
```

### JSON
The JSON files are also encoded using UTF-8 and built in the following structure:
```json
(
	{
	"abbrev" : "abbrev"
	"book" : "name"
	"chapters": 
		(
			{"1": {"1": "...", "2": "..."}}, {"2": {"1": "...", "2": "..."}},
			{"2": {"1": "...", "2": "..."}}, {"2": {"1": "...", "2": "..."}},
			{"3": {"1": "...", "2": "..."}}, {"2": {"1": "...", "2": "..."}}
		)
	}
)
```

### License
This project is distributed under the [Creative Commons BY-NC](https://creativecommons.org/licenses/by-nc/2.0/br/) license. All the Bible versions are property of their respective owners. All rights reserved to the owners.
