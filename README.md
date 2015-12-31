# Bible: XML and JSON
Do you want to create a Bible based app? What about an API for Bible verses search? Now you can do this... using sources in your very own language! The main objective of this project is to allow people to create Bible related apps using XML and JSON sources in multiple Bible versions.

## Methodology
The source files were generated using a Python based crawler. Therefore, these files may contain minor issues related to encoding and syntax.

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
