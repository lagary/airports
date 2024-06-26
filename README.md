# World Airport List


**Airport data has been taken from [OurAirports](https://ourairports.com/) and converted to json.**

**for bugs and updates please [open an issue](https://github.com/segecey/airports/issues/new) or report to [OurAirports](https://ourairports.com/)**


## Airport JSON Structure

```json
{
    "id": 317457, // OutAirports ID
    "ident": "LTFM", // ICAO Code or IDENT
    "type": "large_airport",
    "name": "İstanbul Airport",
    "latitude": 41.261297,
    "longitude": 28.741951,
    "elevation": "325",
    "continent": "EU",
    "iso_country": "TR",
    "iso_region": "TR-34",
    "municipality": "Arnavutköy, Istanbul",
    "scheduled_service": "yes",
    "gps_code": "LTFM",
    "iata_code": "IST",
    "local_code": "",
    "home_link": "http://www.igairport.com/en",
    "wikipedia_link": "https://en.wikipedia.org/wiki/Istanbul_Airport",
    "keywords": ""
}
```

## Airport Frequency JSON Structure

```json
{
    "id": 333707,
    "airport_ref": 317457,
    "airport_ident": "LTFM",
    "type": "Clearance",
    "description": "Istanbul Clearance Delivery",
    "frequency": 121.7
}
```

## Runway JSON Structure

```json
{
    "id": 329986,
    "airport_ref": 317457,
    "airport_ident": "LTFM",
    "length": 12303, // ft
    "width": 147, // ft
    "surface": "ASP",
    "lighted": true,
    "closed": false,
    "le_ident": "16L",
    "le_latitude": 41.29859924316406,
    "le_longitude": 28.709199905395508,
    "le_elevation": 218, // ft
    "le_heading": 174, // deg
    "le_displaced_threshold": 0, // ft
    "he_ident": "34R",
    "he_latitude": 41.26490020751953,
    "he_longitude": 28.70989990234375,
    "he_elevation": 325, // ft
    "he_heading": 354, // deg
    "he_displaced_threshold": 0 // ft
}
```