# isuihko.github.io

Shakin vahvuusluvun laskenta

Ohjelmointikieli: C#/.NET
Käyttöliittymä: WPF/XAML

Vaatimukset:
    Microsoft Windows
    .NET Framework
    Internet Explorer -selain

Avaa osoite:
    https://isuihko.github.io/index.html
ja klikkaa Selolaskuri (XAML Browser Application)

Tai valitse ohjelman osoite suoraan:
    https://isuihko.github.io/Selolaskuri.xbap

Ohjelman käynnistämisestä tulee ilmoitus:
    Sivusto yrittää avata verkkosisältöä tällä tietokoneen ohjelmalla
    Nimi: PresentationHost.exe
    Julkaisija: Microsoft Corporation
tai
    A Website wants to open web content using this program on your computer
    Name: PresentationHost.exe
    Publisher: Microsoft Corporation
    
PresentationHost.exe on Windowsin oma ohjelma:
https://docs.microsoft.com/en-us/dotnet/framework/wpf/app-development/wpf-host-presentationhost-exe

Valitse Salli (Allow)

Tulee ilmoitus:
    Virhe käytettävässä sovelluksessa
    Mahdolliset toimintatavat
    Käynnistä sovellus uudestaan.
    Napsauta alla "Enemmän tietoja" - linkkiä, niin saat tarkempia tietoja virheestä.
tai
    An error occurred in the application you were using
    You can try the following:
    Restart the application. 
    Click the "More Information" link below for details about this error. 

Klikkaa IE:n oikeasta yläkulmasta ratasta eli Asetukset.
Valitse: Internet-asetukset -> Suojaus -> Luotetut sivustot (Internet Options -> Security -> Trusted sites)
Klikkaa Sivustot (Sites)

Osoite-kentässä näkyy:  https://isuihko.github.io
Klikkaa Lisää, Sulje ja OK (Add, Close, OK)

Käynnistä ohjelma uudestaan linkistä.

Tulee ilmoitus:
    Julkaisijaa ei voitu vahvistaa
    Haluatko varmasti suorittaa tämän sovelluksen?
tai
    Publisher cannot be verified.
    Are you sure you want to run this application?

Valitse Suorita (Run).

Tästä eteenpäin ohjelma toimii IE:llä.

-----

Ohjelmassa on leikekirjan käytön valikkotoiminnot pois päältä, koska suojauksien takia ei leikekirjaa voida käyttää.
Myös ohjelman lopetus valikosta on pois päältä. Ohjelma lopetetaan sulkemalla ikkuna.

Ohjelmalla ei ole käyttöoikeuksia oikein mihinkään, koska edes leikekirjaa ei voitu käyttää. Eli käyttö on turvallista.
