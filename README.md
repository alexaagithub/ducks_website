## README

Website created for the Digital Experience Course from [Miles in The Sky](https://milesinthesky.education/). Built with [Hugo](https://gohugo.io/) from the [Vex theme](https://github.com/themefisher/vex-hugo).

## Install
```bash
$ git clone https://github.com/alexaagithub/quackers.git

$ hugo server
```
(opens http://localhost:1313/ on browser)

## Changing page content 
```bash
$ cd content/'page_to_modify'

$ open _index.md
```
## Publish changes
```bash
$ hugo 

$ cd ..

$ mv -f quackers/public/* quackers/

$ cd quackers/

$ git add .

$ git commit -am "change"

$ git push