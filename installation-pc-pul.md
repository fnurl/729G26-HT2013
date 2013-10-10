# Förberedelse av verktyg m.m. i PC-pul

Nedan följer den del instruktioner som hjälper er att få igång er programmeringsmiljö för denna kurs.

En del finns installerat pga att ni inte har möjlighet att installera det själva, men i så stor utsträckning som möjligt så måste ni ordna er egen milö. Anledningen är att programmering är mer än att öppna ett förinstallerat program, och sätta igång med att programmera.

När ni kommer ut i verkligheten kommer ni själva att behöva installera de verktyg som ni behöver för att göra ert jobb. En hantverkare kan sina verktyg, var man köper dem och hur man tar hand om dem.

# Texteditorn - det viktigaste verktyget i en programmerares verktygslåda

## Sublime Text 2

### Package Controll - installera plugins

Package Controll är ett paket till Sublime Text 2 som gör det lättare att installera ytteligare paket i Sublime Text 2. Installera Package kontroll genom att klistra in följande kod i Console som du når via `View -> Show Console`.

    import urllib2,os; pf='Package Control.sublime-package'; ipp = sublime.installed_packages_path(); os.makedirs( ipp ) if not os.path.exists(ipp) else None; urllib2.install_opener( urllib2.build_opener( urllib2.ProxyHandler( ))); open( os.path.join( ipp, pf), 'wb' ).write( urllib2.urlopen( 'http://sublime.wbond.net/' +pf.replace( ' ','%20' )).read()); print( 'Please restart Sublime Text to finish installation')

Starta om Sublime Text 2 och sen kan du installera packet genom att anropa pakethanteraren på följande sätt:

1. Tryck CTRL+Shift+p
2. Skriv in ordet install - det bör då stå "Package Controll: Install Package", tryck enter.
3. Installera paket genom att söka efter dem (börja skriva in deras namn) och trycka enter när du hittat det du vill ha.

Installera följande paket:

* Emmet - hjälper dig skriva kod mycket snabbare
* jQuery - hjälper dig skriva jQuery snabbare
* JsFormat - hjälper dig formattera javascriptkod fint 
* SublimeLinter - hjälper dig hitta syntaxfel m.m. i din kod
* Sublime CodeIntel
* Bracket Highlighter

# Analys och debugverktyg i webbläsaren - utan detta är du en snickare utan tumstock

Det finns utvecklarverktyg till de flesta webbläsare. Vissa är bättre på vissa saker, andra är bättre på andra saker. I denns kurs kommer det bara att finnas instruktioner för Firefox, men det är fritt fram att använda andra webbläsare och tillägg.

## Firebug till Firefox

# Versionshantering - med detta är du snickaren som kan återställa väggar som plockats bort av misstag

