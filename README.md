Teca
====

A simple static -and configurable- image gallery generator.

DISCLAIMER
==========
IT'S A F**KIN' ALPHA, SO IT COULD DIVIDE BY ZERO AND DESTROY THE LIFE AS WE KNOW IT.
also, Teca code could be heavily modified very fast.
I told ya man, keep an eye on what you're doing.

Installation and Usage
===
```sh
git clone https://github.com/alfateam123/Teca.git
cd Teca
python teca.py $screenshots_folder
echo "Thank you for using Teca"
```

Remove the gallery
==
```sh
python clean.py $screenshots_folders
echo "Thank you for using Teca"
```

Configuration
===
it's all in the cfg.json file.
See Configuration.md file for every information you may need.

Dependencies
===
* Jinja2 (from the Cheese Shop or github)
* optparse (stdlib)

In order to generate thumbnails, you can choose between
* Pillow (from the Cheese Shop or github)
* PIL (from PythonWare website)
In 29 dec 2013 Teca officially supported Pillow: now both PIL and Pillow can be used.
In the log, you can read why:
```
<Robertof> alfateam123
<Robertof> :: Vuoi sostituire python2-imaging con community/python2-pillow? [S/n] s
<Robertof> io faccio y
<alfateam123> Robertof: massì, prova
<alfateam123> sostituisci
<Robertof> già fatto alfateam123
<alfateam123> lol
```

TODO
===
* refactor Teca
* [STARTED] write configuration documentation
* do a stylesheet. or at least, build a better UI.
* [DONE] Support UTF-8
