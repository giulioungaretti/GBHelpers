# GBHelpers
Basic scripts to activate/deactivate  gb project.

[![forthebadge](http://forthebadge.com/images/badges/fuck-it-ship-it.svg)](http://forthebadge.com)
[![forthebadge](http://forthebadge.com/images/badges/built-by-hipsters.svg)](http://forthebadge.com)


The idea is to mock the anaconda activate venv scrpits.
We have two commands agb (ActivateGB), and dgb (DeactivateGB).

They will export a gopath and some nice env variables to make your prompt look pretty and make sure the standard go tooling works inside any editor.

PS1 format: gb:$name of your package. 

THe path of your proeject $GOPATH/src/$projectname/src/$projectname is exported as src, to make it easyer and shiny. 

![screenshot](https://raw.githubusercontent.com/giulioungaretti/GBHelpers/master/shot.png)

**OFC** It's way better to use gb build , instead of go build. But vet/lint/oracle don't digest gb architecture.

