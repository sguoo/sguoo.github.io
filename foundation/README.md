# Foundation 작성 규칙

## Path Define

- default : https://sguoo.github.io/foundation
- major : **default/data** - major:selected.toLowerCase()
- chapter : **default/major/data.json** - chapter:selected.toLowerCase()
- test : **default/major/data.json** - test:selected.toLowerCase()
- type : **default/major/data.json** - type (lowercase required)

## Route Path

{dafault}/{major}/data/{chapter}.{type}

로 이루어진다.

major, chapter 디렉터리는 소문자로 이루어져야 하며, type는 [ html | md | web ]의 범위를 지닌다.

TYPE

- html : open chapter.html
- md : open chapter.md
- web : open webview of url in chapter.txt

## Test Path

{default}/{major}/test/{test}.json

로 이루어진다.

major, test 디렉터리는 소문자로 이루어져야 하며, data.json에 question과 answer를 지닌다.
