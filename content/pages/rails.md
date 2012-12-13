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
