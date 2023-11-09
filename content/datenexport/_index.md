---
description: "Stimmungskompass verwendet das GeoJSON-Format und gewährleistet so eine umfassende Kompatibilität und unbegrenzte Bearbeitung."
title: "Datenexport"
paige:
  alert: "Laden Sie <a href=\"#\" class=\"alert-link\">hier</a> die Beispieldatei herunter."
---
<div class="text-center h7">Die Daten können durch einfaches Scripting leicht bearbeitet werden.</div>


<div class="text-center h4">Beispiel für einen Pin Export (GeoJSON):</div>




```yaml
{
    "type": "FeatureCollection",
    "features": [
        {
            "type": "Feature",
            "geometry": {
                "type": "Point",
                "coordinates": [
                    15.596417878745223,
                    48.40990066440067
                ]
            },
            "properties": {
                "pin_type": "ff5c00",
                "description": "Das Steiner Tor ist einfach sch\u00f6n!",
                "molen_id": "M051078322",
                "highlight_id": "HH64993909"
            }
        },
        {
            "type": "Feature",
            "geometry": {
                "type": "Point",
                "coordinates": [
                    15.599824832125599,
                    48.411485233318146
                ]
            },
            "properties": {
                "pin_type": "ff5c00",
                "description": "Der Markt am Samstagvormittag ist immer ein Erlebnis!",
                "molen_id": "M847567157",
                "highlight_id": "MVEKI5B8WO"
            }
        },
        {
            "type": "Feature",
            "geometry": {
                "type": "Point",
                "coordinates": [
                    15.599486281851181,
                    48.412542772064526
                ]
            },
            "properties": {
                "pin_type": "ff5c00",
                "description": "Sch\u00f6ner Ausblick \u00fcber die Altstadt!",
                "molen_id": "M002297219",
                "highlight_id": null
            }
        }
    ]
}
```