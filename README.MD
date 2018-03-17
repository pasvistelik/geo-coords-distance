# geo-coords-distance
Module for (fast but approximate) distances calculation on the Earth between two points.

## Installing:
```sh
npm install geo-coords-distance
```

## Usage exsample:
```javascript
import distance from 'geo-coords-distance';

const firstPoint = {lat: 53.6847, lng: 23.8402}, secondPoint = {lat: 53.9271, lng: 27.5252};

const result = distance(firstPoint, secondPoint);
```
