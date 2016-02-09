# Upcoming hackathons in Germany

This repository tracks [upcoming hackathons within Germany][hackathon-map].


## Contributions

To add a hackathon to this list, please submit a clean **pull request**.
Keep hackathons organized by start date and then alphabetically.


### Format

All that is needed for a new hackathon item to be added is a proper GeoJSON
feature block such as this one:

``` json
{
    "geometry": {
        "coordinates": [
            13.33,
            52.44
        ],
        "type": "Point"
    },
    "properties": {
        "location": "Berlin, Secret hacker space",
        "title": "Secret hackathon",
        "url": "https://example.com/hackathon",
        "when": "2015-12-31 - 2016-01-01"
    },
    "type": "Feature"
}
```

Please lookup geographic coordinates for the location address. Make sure, coordinates
are in the right order for being rendered. You can check the preview at GitHub.


## Reference

Inspired by the [Hackathon-Calendar][hackathon-calendar] repository.



[hackathon-calendar]: https://github.com/japacible/Hackathon-Calendar
[hackathon-map]: https://github.com/johnjohndoe/awesome-hackathons-in-germany/blob/master/hackathons.geojson
