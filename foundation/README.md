# Foundation 작성 규칙

## Path Define

- default : **https://sguoo.github.io/foundation**
- major : **default/data.json** - major:selected.toLowerCase()
- chapter : **default/major/data.json** - chapter:selected.toLowerCase()
- test : **default/major/data.json** - test:selected.toLowerCase()
- type : **default/major/data.json** - type.toLowerCase()

## Route Path
### chapter
{dafault}

└{major}

 └data
 
  └{chapter}.{type}
  
 └test
 
  └{test}.json

lowercase required : dir(major, chapter, test) domain : type [ html | md | web ]

DIR
- major : Each element of a major that can be selected from root
- chapter : Each content element that can be selected from the major
- test : Each test element selectable in the major

TYPE
- html : open chapter.html
- md : open chapter.md
- web : open webview of url in chapter.txt
