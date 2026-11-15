<!-- ERZEUGT von tools/gen_wiki.py aus den Skin-Daten - nicht von Hand bearbeiten -->

# Bereiche und Startseite

Das Hauptmenü besteht aus Bereichen. Jeder Bereich hat Unterpunkte (zweite Zeile im Menü oben bzw. zweite Spalte im Seitenmenü) und bis zu sechs Inhaltszeilen auf der Startseite. Welche Bereiche im Menü stehen, legst du im **Menü-Editor** fest, die Zeilen im **Widget-Editor**.

## Start

Unterpunkte: Favoriten, Menü bearbeiten, Bibliothek aktualisieren, Bibliothek bereinigen, Widgets bearbeiten

Zeilen (Standard): Filme fortsetzen, Begonnene Serien, Zuletzt hinzugefügte Episoden, Zuletzt hinzugefügte Filme, Zuletzt hinzugefügte Alben, Zuletzt gesehene Sender

## Filme

*Nur sichtbar, wenn vorhanden* (`Library.HasContent(movies)`).

Unterpunkte: Alle Filme, Filmreihen, Dateien, Videodatenbank aktualisieren, Widgets bearbeiten

Zeilen (Standard): Filme fortsetzen, Neu und ungesehen, Zufällige Filme, Genres

## Serien

*Nur sichtbar, wenn vorhanden* (`Library.HasContent(tvshows)`).

Unterpunkte: Alle Serien, Begonnene Serien, Zuletzt hinzugefügte Serien, Dateien, Videodatenbank aktualisieren, Widgets bearbeiten

Zeilen (Standard): Begonnene Serien, Neue Folgen, Ungesehene Serien, Genres, Nächste Folgen

## TV

*Nur sichtbar, wenn vorhanden* (`System.HasPVRAddon`).

Unterpunkte: Sender, TV-Programm, Aufnahmen, Timer, Timer-Regeln, Anbieter, TV-Tipps, Serienplaner, Widgets bearbeiten

Zeilen (Standard): Zuletzt gesehene Sender, Neue Aufnahmen, Timer, TV-Sendergruppen, Alle TV-Sender

## Radio

*Nur sichtbar, wenn vorhanden* (`System.HasPVRAddon`).

Unterpunkte: Sender, TV-Programm, Aufnahmen, Timer, Timer-Regeln, Anbieter, Suchen, Widgets bearbeiten

Zeilen (Standard): Zuletzt gehörte Sender, Neue Aufnahmen, Radiosendergruppen, Alle Radiosender

## Musik

Unterpunkte: Interpreten, Alben, Titel, Wiedergabelisten, Dateien, Partymodus, Bibliothek aktualisieren, Widgets bearbeiten

Zeilen (Standard): Zuletzt hinzugefügte Alben, Zuletzt gehörte Alben, Zufällige Alben, Genres, Zufällige Interpreten, Top 100 Alben

## Musikvideos

*Nur sichtbar, wenn vorhanden* (`Library.HasContent(musicvideos)`).

Unterpunkte: Alle Musikvideos, Interpreten, Alben, Genres, Jahre, Studios, Widgets bearbeiten

Zeilen (Standard): Zuletzt hinzugefügte Musikvideos, Ungesehene Musikvideos, Zufällige Musikvideos

## Videos

Unterpunkte: Bibliothek, Dateien, Wiedergabelisten, Video-Addons, Bibliothek aktualisieren, Widgets bearbeiten

Zeilen (Standard): Video-Addons, Medienquellen

## Bilder

Unterpunkte: Dateien, Bild-Addons, Widgets bearbeiten

Zeilen (Standard): Medienquellen, Bild-Addons

## Spiele

*Nur sichtbar, wenn vorhanden* (`System.GetBool(gamesgeneral.enable)`).

Unterpunkte: Spiele, Spiele-Addons, Controller, Widgets bearbeiten

Zeilen (Standard): Spiele-Addons

## Addons

Unterpunkte: Video-Addons, Musik-Addons, Bild-Addons, Programm-Addons, Updates, Aus Repository installieren, Widgets bearbeiten

Zeilen (Standard): Video-Addons, Musik-Addons, Programm-Addons

## Wetter

*Nur sichtbar, wenn vorhanden* (`!String.IsEmpty(Weather.Plugin)`).

Unterpunkte: Wetter, Aktualisieren, Ort wechseln, Wetter-Hintergründe, Einstellungen, Widgets bearbeiten

Zeilen (Standard): Wettervorhersage

## Zentrale

Unterpunkte: Systeminformationen, Ereignisprotokoll, Favoriten, Smart Home, Wake on LAN, Dateibrowser, Skin-Einstellungen, Widgets bearbeiten

Zeilen (Standard): Favoriten, Smart Home, Timer

## Favoriten

Unterpunkte: Widgets bearbeiten

Zeilen (Standard): Favoriten

## Disc abspielen

*Nur sichtbar, wenn vorhanden* (`System.HasMediadVDRom`).

Unterpunkte: Disc abspielen, Auswerfen


## Einstellungen

Unterpunkte: Skin-Einstellungen, Menü bearbeiten, Dateimanager, Systeminformationen, Profile, Ereignisprotokoll


## Inhalte für die Zeilen (Widget-Katalog)

| Inhalt | Darstellung | Voraussetzung |
|---|---|---|
| Zuletzt hinzugefügte Filme | Poster | – |
| Zuletzt hinzugefügte Episoden | Querformat | – |
| Nächste Folgen | Querformat | Addon service.library.data.provider |
| Zuletzt hinzugefügte Alben | Quadrat | – |
| Filme fortsetzen | Querformat | – |
| Neu und ungesehen | Poster | – |
| Ungesehene Filme | Poster | – |
| Zufällige Filme | Poster | – |
| Genres | Kacheln | – |
| Filmreihen | Poster | – |
| Begonnene Serien | Poster | – |
| Neue Folgen | Querformat | – |
| Ungesehene Serien | Poster | – |
| Genres | Kacheln | – |
| Zuletzt gehörte Alben | Quadrat | – |
| Zufällige Alben | Quadrat | – |
| Zufällige Interpreten | Quadrat | – |
| Ungehörte Alben | Quadrat | – |
| Meistgehörte Alben | Quadrat | – |
| Genres | Kacheln | – |
| Zuletzt gehörte Lieder | Quadrat | – |
| Top 100 Lieder | Quadrat | – |
| Top 100 Alben | Quadrat | – |
| Alle Interpreten | Quadrat | – |
| Musik-Playlists | Kacheln | – |
| Zuletzt hinzugefügte Musikvideos | Querformat | – |
| Ungesehene Musikvideos | Querformat | – |
| Zufällige Musikvideos | Querformat | – |
| Zuletzt gesehene Sender | Quadrat | – |
| Neue Aufnahmen | Querformat | – |
| Timer | Quadrat | – |
| Wettervorhersage | weather | !String.IsEmpty(Weather.Plugin |
| Wetter stündlich | weather | !String.IsEmpty(Weather.Plugin + !String.IsEmpty(Window(Weather.Property(Hourly.1.Time |
| Wetter im Detail | weather | !String.IsEmpty(Weather.Plugin + !String.IsEmpty(Window(Weather.Property(Current.Humidity |
| TV-Tipps | Querformat | Addon script.service.gto |
| Smart Home | Kacheln | Addon script.program.fritzact |
| TV-Sendergruppen | Kacheln | – |
| Alle TV-Sender | Quadrat | – |
| Zuletzt gehörte Sender | Quadrat | – |
| Neue Aufnahmen | Quadrat | – |
| Radiosendergruppen | Kacheln | – |
| Alle Radiosender | Quadrat | – |
| Radio-Timer | Quadrat | – |
| Video-Addons | Kacheln | – |
| Musik-Addons | Kacheln | – |
| Bild-Addons | Kacheln | – |
| Programm-Addons | Kacheln | – |
| Spiele-Addons | Kacheln | – |
| Medienquellen | Kacheln | – |
| Medienquellen | Kacheln | – |
| Favoriten | Kacheln | – |
| Filme im Trend (TMDb) | Poster | – |
| Serien im Trend (TMDb) | Poster | – |
| Beliebte Filme (TMDb) | Poster | – |
| Demnächst im Kino (TMDb) | Poster | – |

---

[← Zur Übersicht](README.md)
