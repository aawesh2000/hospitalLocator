
This project is created to locate all the hospitals on the map with the availability of the beds and get directions to navigate to it. Site hosted at [resuceplus.netlify.app](https://resuceplus.netlify.app/)

Idea is to bring all hospitals on the map so that any one quickly search nearby hospitals or search hospitals near to an address. And be able to navigate to it using the directions.

## Built With
- [Leaflet](https://leafletjs.com/)
- [OpenStreetMap](https://openstreetmap.org)
- [ReactJS](https://react-leaflet.js.org/)
- [MapQuest](https://www.mapquest.com/)

## Features:
- Explore nearby hospitals using current device location
- Search address to look at hospitals around that.
- See hospitals contact details like phone, address along with beds availability
- Get directions to navigate to hospital location

## Source of data
Hospital location, and beds information is being collected and created by [covidhospitals/datacollector](https://github.com/covidhospitals/datacollector)

Currently hospital location, and beds information is being collected for AP, and Delhi states. Feel free to volunteer to contribute the data adhering the JSON format.  

| State or Locality | Site | Normalized data |
| ------------- |-------------| ---- |
| Andhra Pradesh      | [http://dashboard.covid19.ap.gov.in/](http://dashboard.covid19.ap.gov.in/) | [https://api.npoint.io/4594de00c3f1d76a08ec](https://api.npoint.io/4594de00c3f1d76a08ec)|
| Delhi      | [https://coronabeds.jantasamvad.org/](https://coronabeds.jantasamvad.org/) | [https://api.npoint.io/4d61424b0910b4a2b692](https://api.npoint.io/4d61424b0910b4a2b692)|

Please feel make changes to this, or add more data sources. And raise a PR.
## Credits
- A big thanks [Netlify](https://netlify.com/) for hosting the [resuceplus.netlify.app](https://resuceplus.netlify.app/)
- Thanks to [npoint.io](https://npoint.io) for hosting the AP hospital location data.
