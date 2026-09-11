SEW | IP Address Lookup

## User Story 1
*As an interested user, I want to know where the location of a server is, so that I know where my data is stored.*

### Acceptance Criteria
- An VueJS app for displaying information about a domain is available.
- An input field for entering the URL is available.
- Once the input exceeds three characters, the search functionality is triggered.
- The following information is displayed:
  - the first IP address of that host-name,
  - the country, city and geo-coordinates of the IP address,
  - the local time, timezone, sunrise, and sunset info for that place,
  - current weather information for that place
- Possible errors are handled in a meaningful and user-friendly way.
- All API keys and Base-URLs are stored in an .env file.

### Some Services (feel free to also use any other service)
- [IP-Adresse, Ort und Zeitzone eines Hosts](https://ip-api.com/docs/api:json)
- [Sonnenauf- und -untergangszeit](https://sunrise-sunset.org/api)
- [Wetter](https://open-meteo.com/)
- [GeoNames (Volltextsuche, Orte, PLZ, Reverse Geocoding u.v.m.)](http://www.geonames.org/export/)
- [Zeitzone](https://timezonedb.com/api)
- [DNS-Abfrage](http://www.dns-lg.com/documentation/)

## Skill(s)
- [JavaScript Promises & async/await](https://my.skilldisplay.eu/en/skill/2990/0)
- [Consume a REST API with Axios](https://my.skilldisplay.eu/en/skill/1693/0)
