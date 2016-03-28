# community.fsharp.org Speakers Program

> All content is curated by the F# Software Community, and does not constitute an official endorsement by the F# Software Foundation.

The [Speakers Program](http://community.fsharp.org/speakers) map and list are based off data stored here.  If you perform talks on F# related topics, and are a member of the F# Software Foundation, you are encouraged to add yourself to the list managed by the F# Software Foundation.

The data is stored in a JSONP document at [https://github.com/fsharp/community.fsharp.org/blob/gh-pages/speakers/speakers.jsonp](https://github.com/fsharp/community.fsharp.org/blob/gh-pages/speakers/speakers.jsonp).  Pull requests against this data are welcome, though you may also email your information to [speakers@fsharp.org](mailto:speakers@fsharp.org) to have yourself listed.

Please follow these guidelines when submitting a pull request:

- List yourself alphabetically _by full name_
- Fill in all information, following the format of existing entries
- For "member", please use your F# Software Foundation username.
    - To find your username, login to [http://foundation.fsharp.org](http://foundation.fsharp.org), and click on the gear icon in the upper right.
    - Your username will be on the left, labeled "User name"
- Latitude and Longitude values are used to place the speaker using the Google Maps API.  
    - Google Maps is recommended to determine coordinate.
    - Visit [Google Maps](https://www.google.com/maps), Zoom to your location, and click on the map where you live or work.
    - Copy latitude and longtiude from white box at the bottom of the screen.
- "twitter" is optional, and only used to display a picture. Leave entry out if you don't want a picture.
- For "travel-zone", enter a plain text description of the region where you will travel to speak ("Northern France")
- For "travel-distance", enter the approximate distance (in _km_) you are willing to travel.
- Please keep your biography brief.
- For talks and tags, enter 0-5 options.  Use an empty array `[ ]` if you don't want to include this.
- Please verify that resulting data follows all JSON rules, including correctly handling (or avoiding) embedded quotation marks in the description, etc.


Here is an example entry (showing portions of the entry before and after):

```javascript
    "tags": [ "machine-learning", "hands-on" ]
},
{
    "name":"Reed Copsey",
    "member": "reedcopsey",
    "twitter": "reedcopsey",    
    "location": "Bellingham, WA, United States",
    "lat": 48.7482375,
    "lng": -122.4792122,
    "travel-zone": "United States Northwest",
    "travel-distance": 200,
    "bio": "Executive Director of the F# Software Foundation, CTO of C Tech Development Corporation.",
    "talks": [ "How F# made me a better C# and C++ developer" ],
    "tags": [ "ui" ]
},
{
    "name":"Riccardo Terrell",
```

Please duplicate this formatting style in your own speaker entry.
