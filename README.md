# FAVR Navbars

Custom Header-Fragmente fuer FAVR-Optiker-Produktseiten.

## Struktur

```
favr-navbars/
|-- _template/
|   +-- fragment.html     <- Vorlage fuer neue Optiker
|-- hensler/
|   |-- fragment.html     <- Fertig fuer Agentur
|   +-- logo.webp
```

## Verwendung

Die `fragment.html` wird von der Agentur als Web Component eingebettet.
Alle Links zeigen auf die Original-Website des Optikers.
Logo ist als Base64 data-URI eingebettet (keine externen Abhaengigkeiten).

## Neuen Optiker anlegen

1. `_template/fragment.html` kopieren
2. Neuen Ordner `optiker-name/` anlegen
3. Logo, Farben, Links anpassen
4. Fragment an Agentur uebergeben
