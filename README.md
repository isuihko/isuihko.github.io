# isuihko.github.io

Shakin vahvuusluvun laskenta, IE-selaimella suoritettava versio

<PRE>
Ohjelmointikieli: C#/.NET
Käyttöliittymä: WPF/XAML

Vaatimukset:
    Microsoft Windows 7 ja uudemmat
    .NET Framework
    Internet Explorer -selain eli IE
</PRE>

Avaa IE-selaimella osoite:
    https://isuihko.github.io
ja klikkaa Selolaskuri (XAML Browser Application)

Tai valitse ohjelman osoite suoraan:
    https://isuihko.github.io/Selolaskuri.xbap

Tietoa xbap-sovelluksista:
https://en.wikipedia.org/wiki/XAML_Browser_Applications

Ohjelman käynnistämisestä tulee ilmoitus:
<PRE>
    Sivusto yrittää avata verkkosisältöä tällä tietokoneen ohjelmalla
    Nimi: PresentationHost.exe
    Julkaisija: Microsoft Corporation
</PRE>
tai
<PRE>
    A Website wants to open web content using this program on your computer
    Name: PresentationHost.exe
    Publisher: Microsoft Corporation
</PRE>
    
PresentationHost.exe on Windowsin oma ohjelma:
https://docs.microsoft.com/en-us/dotnet/framework/wpf/app-development/wpf-host-presentationhost-exe


Valitse Salli (Allow)

Tulee ilmoitus:
<PRE>
    Virhe käytettävässä sovelluksessa
    Mahdolliset toimintatavat
    Käynnistä sovellus uudestaan.
    Napsauta alla "Enemmän tietoja" - linkkiä, niin saat tarkempia tietoja virheestä.
</PRE>
tai
<PRE>
    An error occurred in the application you were using
    You can try the following:
    Restart the application. 
    Click the "More Information" link below for details about this error. 
</PRE>    

Klikkaa IE:n oikeasta yläkulmasta ratasta eli Asetukset.
Valitse: Internet-asetukset -> Suojaus -> Luotetut sivustot (Internet Options -> Security -> Trusted sites)
Klikkaa Sivustot (Sites)

Osoite-kentässä näkyy:  https://isuihko.github.io
Klikkaa Lisää, Sulje ja OK (Add, Close, OK)

Käynnistä ohjelma uudestaan em. linkistä.

Tulee ilmoitus:
<PRE>
    Julkaisijaa ei voitu vahvistaa
    Haluatko varmasti suorittaa tämän sovelluksen?
</PRE>    
tai
<PRE>
    Publisher cannot be verified.
    Are you sure you want to run this application?
</PRE>

Valitse Suorita (Run).

Tästä eteenpäin ohjelma toimii tietokoneessasi IE:llä.

-----

Ohjelmassa on leikekirjan käytön valikkotoiminnot pois päältä, koska suojauksien takia ei leikekirjaa voida käyttää.
Myös ohjelman lopetus valikosta on pois päältä. Ohjelma lopetetaan sulkemalla ikkuna.

Ohjelmalla toimii vain selaimessa, eikä sillä ole käyttöoikeuksia oikein mihinkään, koska edes leikekirjaa ei voitu käyttää.
Eli käyttö on turvallista.

Luotu Visual Studio 2017:lla XAML Browser Application -sovellus käyttämällä seuraavia lähdekoodeja (muutokset käyttöliittymässä: Edit-menu cut/copy/paste pois päältä, Menu->Sulje pois päältä, ikkuna on leveämpi):
https://github.com/isuihko/SelolaskuriWPF
Lähdekoodeista voidaan myös kääntää Windowsissa toimiva työpöytäsovellus: lataa koko paketti ja avaa & käännä Visual Studiolla.