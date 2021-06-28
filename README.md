# Weather Data
This Github repository contains weather data for NFL games 2000 - 2020. 

## File Descriptions

 `stadium_coordinates.csv`

- `StadiumName`: name of stadium.
- `RoofType`: whether the stadium is indoor, outdoor or has a retractable roof.
- `Longitude`: longitude of the stadium.
- `Latitude`: latitude of the stadium.
- `StadiumAzimuthAngle`: azimuth angle of the field (0 is North, 90 is East, 180 is South, 270 is West).



`games.csv`

- `game_id`: id corresponding to game.
- `Season`: season game takes place.
- `StadiumName`: name of stadium.
- `TimeStartGame`: date and time game started in local timezone.
- `TimeEndGame`: date and time game ended in local timezone.
- `TZOffset`: hours offset from local timezone of game to UTC timezone.




`games_weather.csv`

- `game_id`: id corresponding to game.
- `Source`: source of weather data (meteostat or Wunderground).
- `DistanceToStation`: distance from stadium to station in miles.
- `TimeMeasure`: date and time weather was measured in local timezone.
- `Temperature`: temperature in Fahrenheight.
- `DewPoint`: dew point in Fahrenheight.
- `Humidity`: humidity in percentage.
- `Precipitation`: precipitation in inches.
- `WindSpeed`: speed of wind in miles per hour.
- `WindDirection`: azimuth angle of the direction of wind (0 is North, 90 is East, 180 is South, 270 is West).
- `Pressure`: pressure in inches of mercury.
