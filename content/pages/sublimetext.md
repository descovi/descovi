## Tema

Tema: (Soda Theme)[https://github.com/buymeasoda/soda-theme]

Colore: (Tomorrow-Theme)[https://github.com/ChrisKempson/Tomorrow-Theme]


## Sublime a Linea di comando

/bin contiene gli alias del sistema

La seguente procedura mette l'alias verso sublime text
http://www.sublimetext.com/docs/2/osx_command_line.html

ln -s "/Applications/Sublime Text 2.app/Contents/SharedSupport/bin/subl" ~/bin/subl

Ci sono varie difficoltà che si possono incontrare:

che ad esempio ~/bin/subl anche con sudo davanti faccia riferimento a una fantomatica cartella bin presente nella home dello user.

La soluzione semplice e fare uno stupido alias. Nulla più.
Un cazzo di alias e buttarlo bella cartella bin dentro la root del computer. Cazzo.

## Le mie attuali Preferenze

{
  "color_scheme": "Packages/Solarized Color Scheme/Solarized (dark).tmTheme",
  "font_size": 14.0,
  "ignored_packages":
  [
    ""
  ],
  "tab_size": 2,
  "theme": "Soda Dark.sublime-theme",
  "translate_tabs_to_spaces": true
}