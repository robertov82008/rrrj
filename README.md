# RRRJ Overlay

## Install Overlay

`root # layman -o https://raw.githubusercontent.com/robertov82008/rrrj/master/repositories.xml f -a rrrj`
`root # layman -a rrrj`
`root # layman-updater -R`


### update

`root # emerge --sync`
`root # layman -S`
`root # eix-sync -q`


## Create your overlay

`$ git clone project-overlay`

#### Sets your changes

`project-overlay $ git add . && git commit -m 'init`
`project-overlay- $ git push`

`root # layman-overlay-maker`