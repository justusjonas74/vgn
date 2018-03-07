# 🚏VGN

This is a list of API endpoints, libraries, apps, tools and anything else that's available to access data in the [Verkehrsverbund Großraum Nürnberg](https://www.vgn.de/) network. This includes the [VAG Verkehrs-Aktiengesellschaft Nürnberg ](https://www.vag.de/).

This document is heavily inspired by [derhuerst/vbb-modules](https://github.com/derhuerst/vbb-modules) and [kiliankoe/vvo](https://github.com/kiliankoe/vvo).

Got any more info, details, links? Please don't hesitate to open an issue and/or PR 🙃

## Static Data

* [VGN: GTFS](https://www.vgn.de/web-entwickler/open-data/) - Official VGN [GTFS](https://developers.google.com/transit/gtfs/) feed
* [opendata.vag.de](https://opendata.vag.de) - Offical VAG Open Data portal platform. Actually offered data:
  * [Haltestellen: IDs und Geodaten](https://opendata.vag.de/dataset/haltestellen-id-geodaten) - List of all VAG stops including geolocation and corresponding IDs
  * [Infrastruktur | Tram: Ausstattung der Haltestellen](https://opendata.vag.de/dataset/haltestellen-tram) - Tram stop facilities
  * [Infrastruktur | U-Bahn](https://opendata.vag.de/dataset/bahnhoefe-u-bahn) - Subway station facilities
  * [Infrastruktur | U-Bahn: Aufzüge](https://opendata.vag.de/dataset/u-bahn-aufzuege) - Subway station elevators
  * [Infrastruktur | Tram: Steighöhen](https://opendata.vag.de/dataset/steighoehen-tram) - Entry heights of tram stops
  * [Fuhrpark | Bus](https://opendata.vag.de/dataset/fuhrpark-bus-ausstattung) - Technical data about buses
  * [Fuhrpark | Tram](https://opendata.vag.de/dataset/fahrzeugtypen-tram) - Technical data about trams
  * [Fuhrpark | U-Bahn](https://opendata.vag.de/dataset/fuhrpark-ubahn) - Technical data about metro trains
  * [Fuhrpark](https://opendata.vag.de/dataset/fuhrpark) - General information about vehicle fleet
  * [Taxis in Nürnberg](https://opendata.vag.de/dataset/geokoordinaten-taxi-warteplatze) - Geolocations of Taxi stands in Nuremberg. Offical data (Excel file)
* [de-stops/vgn-stops](https://github.com/de-stops/vgn-stops) - Simple script to download all VGN stops as GTFS-compatible CSV

## APIs

* [VAG Echtzeitabfahrtsmonitor](https://opendata.vag.de/dataset/api-echtzeitauskunft) - Official REST-API to query stops and trips served by VAG Nürnberg and get (real time) departures

## Libraries
* [vagquery](https://github.com/derphilipp/vagquery) - A python library for generating and executing queries for the VAG public transport system start.vag.de

## Apps

* [VGN Fahrplan & Tickets](https://www.vgn.de/service/app/) - Official real time journey planner and mobile ticketing app (iOS, Andriod)
* __VAG Mitfahrer App__ - Official App to offer somebody a lift on your multi-person ticket for free ([Android](https://play.google.com/store/apps/details?id=de.vag.mitfahrer.app) / [iOS](https://itunes.apple.com/de/app/vag-mitfahrer-app/id1321958643?mt=8))
* [FahrInfo Nürnberg](https://itunes.apple.com/de/app/fahrinfo-n%C3%BCrnberg/id582623425?mt=8) - Journey planner
* [jomaway/VGN-Semesterticket-Viewer](https://github.com/jomaway/VGN-Semesterticket-Viewer) - Unofficial Open Source Android application to display the VGN-Semesterticket on the device
* [Abfahrzeiten Nürnberg](https://itunes.apple.com/us/app/abfahrzeiten-n%C3%BCrnberg/id1335328862?mt=80) - Unofficial iOS App to display departures

## Tools, UIs & Experiments

* [VGN Widget](https://www.vgn.de/web-entwickler/fahrplanauskunft-fuer-ihre-website/) - Embed VGN journey planner to your website  
* [VAG Profi-Widget](https://opendata.vag.de/dataset/widget-echtzeitauskunft) - Windows client to display departures
* [VAG Departures](https://github.com/justusjonas74/vag-departures) - Simple React based Progressive Web App consuming [VAG Echtzeitabfahrtsmonitor API](#apis)
* [vlewin/vgn-departures-ionic](https://github.com/vlewin/vgn-departures-ionic) - VGN Nürnberg live transport arrivals build with awesome Ionic framework 
