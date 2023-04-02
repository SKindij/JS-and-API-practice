# Marvel Comics
&emsp; _Marvel Comics API allows to access information about Marvel's vast library of comics—from what's coming up, to 70 years ago._

> ``cd marvel``\
> ``npm start`` 
___

### Request URL
``https://gateway.marvel.com:443/v1/public/characters?``
> _Fetches lists of comic characters with optional filters._

Response Class (Response Body)
```JSON
  {
    "code": 200, "status": "Ok", "copyright": "© 2023 MARVEL",
    "attributionText": "Data provided by Marvel. © 2023 MARVEL",
    "attributionHTML": "<a href=\"http://marvel.com\">Data provided by Marvel. © 2023 MARVEL</a>",
    "data": {
      "offset": 210, "limit": 9, "total": 1562, "count": 9,
      "results": [
        {
          "id": 1009225, "name": "Captain Stacy",
          "description": "NYPD Captain George Stacy was the father of one-time Peter Parker girlfriend Gwen Stacy.",
          "modified": "1969-12-31T19:00:00-0500",
          "thumbnail": { "path": "http://i.annihil.us/u/prod/marvel/i/mg/2/a0/4c00407752be2", "extension": "jpg" },
          "resourceURI": "http://gateway.marvel.com/v1/public/characters/1009225",
          "comics": {
              "available": 10, "collectionURI": "http://gateway.marvel.com/v1/public/characters/1009225/comics",
              "items": [
                {
                  "resourceURI": "http://gateway.marvel.com/v1/public/comics/1879",
                  "name": "MARVEL MASTERWORKS: THE AMAZING SPIDER-MAN VOL. 7 HC (Hardcover)"
                },
                {
                  "resourceURI": " ... ",
                  "name": " ... "
                {
                  "resourceURI": "http://gateway.marvel.com/v1/public/comics/6913",
                  "name": "The Amazing Spider-Man (1963) #90"
                }
              ],
              "returned": 10
          },
          "series": {
              "available": 4, "collectionURI": "http://gateway.marvel.com/v1/public/characters/1009225/series",
              "items": [
               {
                  "resourceURI": "http://gateway.marvel.com/v1/public/series/454",
                  "name": "Amazing Spider-Man (1999 - 2013)"
                },
                {
                  "resourceURI": " ... ",
                  "name": " ...  "
                },
                {
                  "resourceURI": "http://gateway.marvel.com/v1/public/series/1987",
                  "name": "The Amazing Spider-Man (1963 - 1998)"
               }
             ],
              "returned": 4
          },
          "stories": {
              "available": 8, "collectionURI": "http://gateway.marvel.com/v1/public/characters/1009225/stories",
              "items": [
                {
                  "resourceURI": "http://gateway.marvel.com/v1/public/stories/14355",
                  "name": "Escape Impossible!",
                  "type": "cover"
                },
                {
                  "resourceURI": " ... ",
                  "name": " ... ",
                  "type": " ... "
                },
                {
                  "resourceURI": "http://gateway.marvel.com/v1/public/stories/106037",
                  "name": "Amazing Spider-Man (1999) #12",
                  "type": "cover"
                }
              ],
              "returned": 8
          },
          "events": {
              "available": 0, "collectionURI": "http://gateway.marvel.com/v1/public/characters/1009225/events",
              "items": [],
              "returned": 0
          },
          "urls": [
              {
                "type": "detail",
                "url": "http://marvel.com/characters/390/captain_stacy?utm_campaign=apiRef&utm_source=7021a063d0296193d0fe45e71f4cd3a1"
              },
              {
                "type": "wiki",
                "url": "http://marvel.com/universe/Stacy%2C_George?utm_campaign=apiRef&utm_source=7021a063d0296193d0fe45e71f4cd3a1"
              },
              {
                "type": "comiclink",
                "url": "http://marvel.com/comics/characters/1009225/captain_stacy?utm_campaign=apiRef&utm_source=7021a063d0296193d0fe45e71f4cd3a1"
              }
            ]
        }
      ]
    }
  }
```

___

&emsp; This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

&emsp; Open [http://localhost:3000](http://localhost:3000) to view it in your browser.
