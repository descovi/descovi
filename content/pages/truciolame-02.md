# Riflessioni generali
Google crea canali basati sulle parole.
Le parole chiavi di zero calcare
http://www.zerocalcare.it/2013/01/16/il-duro-mondo-della-sintesi-giornalistica/
Si tratta di colonizzare le parole

---

http://danneu.com/about-me

ma soprattutto:
http://www.getskeleton.com/

https://github.com/viseztrance/rails-sitemap




# git
## Mostrare i log di oggi
git log --since="6am"


## Mostrare i colori di git nella shell
source
http://stackoverflow.com/questions/5113425/how-to-make-git-log-show-all-of-todays-commit
strare i colori di git nella shell
git config --global color.ui true

---

#bashrc

##Personalizzare il bashrc.

Gli \e identificano lo stile ed il colore

export PS1="\e[00;33m\W \[\e[0m\]"

fonte
http://jamiedubs.com/ps1-collection-customize-your-bash-prompt
http://www.thegeekstuff.com/2008/09/bash-shell-ps1-10-examples-to-make-your-linux-prompt-like-angelina-jolie/

## Mark otto a volte mi legge nel pensiero

(Percorso e branch di git)[http://markdotto.com/2012/10/18/terminal-hotness/]

---

# Rails common tools

## asset_path

Restituisce il percorso delle immagini.

erb
<img src="<%= asset_path %>immagine.png">

haml
%img{ src = "#{asset_path}immagine.png" }


source:
* http://guides.rubyonrails.org/asset_pipeline.html
* http://apidock.com/rails/v3.2.1/Sprockets/Helpers/RailsHelper/asset_path

## http_status
http://www.codyfauser.com/2008/7/4/rails-http-status-code-to-symbol-mapping
