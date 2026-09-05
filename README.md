# Bitje's Lampjeslab

Een speelse oefenomgeving voor binaire getallen, gemaakt voor kinderen uit groep 4 en 5.
Robot Bitje spreekt alleen in lampjes (aan of uit) en daagt je uit om getallen te lezen,
te maken, geheime boodschappen te kraken, pixelplaatjes te bouwen en op je vingers tot 31 te tellen.

## Hoe het spel zich aanpast

- Acht levels, van 3 tot 8 lampjes. Vanaf level 4 zijn de getallen onder de lampjes af en toe verstopt.
- Vier vragen achter elkaar in één keer goed: een level omhoog.
- Twee keer mis binnen drie vragen: een stapje terug, met een bemoedigend berichtje.
- Eerste fout op een vraag: een hint. Tweede fout: de uitwerking, en het spel gaat verder.
- Elke ronde van zes vragen eindigt met een weetje over waar computers binaire getallen voor gebruiken.
- Sterren leveren stickers op (pixel-art, zelf ook binair opgeslagen).

## Opslag

Als artifact op claude.ai gebruikt de pagina de ingebouwde database om spelersprofielen,
levels, sterren en statistieken te bewaren. Los geopend valt hij terug op de opslag van de browser.

`index.html` is het hele spel: geen build, geen afhankelijkheden.
