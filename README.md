# Bible: XML and JSON
Do you want to create a Bible based app? What about an API for Bible verses search? Now you can do this, using sources in your very own language! The main objective of this project is to allow people to create Bible related apps using XML and JSON. Do you like this idea? Help us to go even further. **Support this project! :)**

[![Donate](https://www.paypalobjects.com/en_US/i/btn/btn_donateCC_LG.gif)](https://www.paypal.com/cgi-bin/webscr?cmd=_donations&business=A9FM66AQT672L&lc=US&item_name=Bible%20Sources&currency_code=USD&bn=PP%2dDonationsBF%3abtn_donateCC_LG%2egif%3aNonHosted)

## How were the files built?
The source files were generated using a Python based crawler. Therefore, these files may contain minor issues related to encoding and syntax.

## Which languages and versions are covered by the project?
What about adding multiple bible versons Catholic (American, English translation of Catholic Hebrew, Ethiopian Christian, etc.... so a the users can collect and see the differences between the verious branches of the "Faith" given we are all Christian and it would be nice to see both the similarities and any differences (which ny my very old sxhool evangelical Mamaw after two hours at age 99.5 called out chapter and verse to me and we sat together and compared her Bible to the American Catholic Bible, after which she declared "they are the same". We found more then 5 bibles in different stages of fallong apart wnd all annotated in the margins. She would go to Bible study while in a living care apartment building with nurses and helpers but they all had their own little apartments with kitchens and a cafeteria. She had a collection or books my Mom wouod bring her all the new current literature and she had a little library for all the other folks. She xoul5d have taught the Bible study as she knew her Bible verbatim. She like so many think thier is a big difference between hers and the Catholic bible and thought them to be a "cult" but after comparing the most important verses to her, she decided at 99.5 years old they were the same and signed my Catholic Bible. She was one of the first if not THE first woman in Eastern Kentucky to get a Master Degree when my Pop came back from WWII. He let her go to the nearest University to their home in Eastern Kentucky which was in Western Virginia. She was a career Educator. Ended up head of the School District and is in the Greenup County High School Hall or Fame. She keot her mind and good spirits up for her whole life and was a constant learner. I was happy she came to that conclusion on her own and signed my Bible. I still have it next to my bed. 

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

## How the files are structured?
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
```javascript
[
	{
	"abbrev" : "abbrev"
	"book" : "name"
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
This project is distributed under the [Creative Commons BY-NC](https://creativecommons.org/licenses/by-nc/2.0/br/) license. All the Bible versions are property of their respective owners. All rights reserved to the owners.

### How can I help the project?
You can review the code, enhance the structures or work on new versions. Every help is welcome! :)

### Can I donate to the project?
Yes, you can! You can give a volunteer donation by [PayPal](https://www.paypal.com/cgi-bin/webscr?cmd=_donations&business=A9FM66AQT672L&lc=US&item_name=Bible%20Sources&currency_code=USD&bn=PP%2dDonationsBF%3abtn_donateCC_LG%2egif%3aNonHosted).

[![Donate](https://www.paypalobjects.com/en_US/i/btn/btn_donateCC_LG.gif)](https://www.paypal.com/cgi-bin/webscr?cmd=_donations&business=A9FM66AQT672L&lc=US&item_name=Bible%20Sources&currency_code=USD&bn=PP%2dDonationsBF%3abtn_donateCC_LG%2egif%3aNonHosted)
