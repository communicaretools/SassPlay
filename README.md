# SassPlay
Walking through various features of sass(Scss)
Sette opp for Scss (Sass v.3+)

Last ned Ruby 2.2.2 fra https://www.ruby-lang.org/en/documentation/installation/
Åpne "Start Command promt with Ruby
skriv "gem install sass"
skriv "gem install compass" 
skriv "gem install css_parser" for statistikk om css klasser osv

for å sette opp compass til å følge med på riktige filer må du legge ved en config.rb i prosjektet du jobber med.
Noe ala:
	http_path = "/"
	css_dir = "css/css"
	sass_dir = "/css/scss"

Når det er gjort er det bare å skrive "compass watch" der config-filen befinner seg og det hele er oppe og kjører.

Plassering kan også spesifiseres, men husk da at compass vil ta utgangspunkt i hvor kommandoen kjøres fra noe som betyr at config-filen nødvendigvis må ta høyde for dette.

Om du benytter deg av sublimer er Syntax Highlighting for Sass flott å ha

http://alistapart.com/article/getting-started-with-sass

https://scotch.io/tutorials/getting-started-with-sass
