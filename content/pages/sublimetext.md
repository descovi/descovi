## Tema

* Tema: (Soda Theme)[https://github.com/buymeasoda/soda-theme]
* Colore: (Tomorrow-Theme)[https://github.com/ChrisKempson/Tomorrow-Theme]


## Sublime a Linea di comando

La seguente procedura mette l'alias verso sublime text
http://www.sublimetext.com/docs/2/osx_command_line.html

/bin contiene gli alias del sistema

ln -s "/Applications/Sublime Text 2.app/Contents/SharedSupport/bin/subl" ~/bin/subl

~/bin/subl anche con sudo potrebbe riferirsi ad una fantomatica cartella bin presente nella home dello user.

La soluzione semplice e consiste nello fare uno stupido alias che rimanda all'eseguibile di Sublime. 
Nulla più. Un cazzo di alias e buttarlo bella cartella bin dentro la root del computer. Cazzo.


## Le mie attuali Preferenze

{
  "color_scheme": "Packages/Color Scheme - Default/Tomorrow-Night-Eighties.tmTheme",
  "font_face": "Meslo LG L DZ",
  "font_size": 15.0,
  "tab_size": 2,
  "theme": "Soda Dark.sublime-theme",
  "translate_tabs_to_spaces": true
}


## I plugin che uso

* Sftp
* Package control
* Theme soda
* Solarized color scheme
* Coffescript