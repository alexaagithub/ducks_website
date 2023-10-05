## README

Website created to showcase how to create a website with [Hugo](https://gohugo.io/) from the [Vex theme](https://github.com/themefisher/vex-hugo) and host it on GitHub pages.

## Install
```bash
$ git clone https://github.com/alexaagithub/ducks_website.git

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

$ mv -f ducks_website/public/* ducks_website/

$ cd ducks_website/

$ git add .

$ git commit -am "change"

$ git push