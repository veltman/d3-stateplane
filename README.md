# d3-stateplane

[1983 State Plane projections](https://en.wikipedia.org/wiki/State_Plane_Coordinate_System) in `d3.geo` format. These don't incorporate scale/translate, so you probably want to [autoscale your projection](http://bl.ocks.org/mbostock/4707858).  The list is also missing Alaska Zone 1's Oblique Mercator projection.

See also: [New Jersey State Plane](https://bl.ocks.org/mbostock/5126418), [Ohio North State Plane](https://bl.ocks.org/mbostock/5349951)

### NAD83 / Alabama East (EPSG:26929)

```js
var projection = d3.geo.transverseMercator()
  .rotate([85 + 50 / 60, -30 - 30 / 60]);
```

### NAD83 / Alabama West (EPSG:26930)

```js
var projection = d3.geo.transverseMercator()
  .rotate([87 + 30 / 60, -30]);
```

### NAD83 / Alaska Zone 2 (EPSG:26932)

```js
var projection = d3.geo.transverseMercator()
  .rotate([142, -54]);
```

### NAD83 / Alaska Zone 3 (EPSG:26933)

```js
var projection = d3.geo.transverseMercator()
  .rotate([146, -54]);
```

### NAD83 / Alaska Zone 4 (EPSG:26934)

```js
var projection = d3.geo.transverseMercator()
  .rotate([150, -54]);
```

### NAD83 / Alaska Zone 5 (EPSG:26935)

```js
var projection = d3.geo.transverseMercator()
  .rotate([154, -54]);
```

### NAD83 / Alaska Zone 6 (EPSG:26936)

```js
var projection = d3.geo.transverseMercator()
  .rotate([158, -54]);
```

### NAD83 / Alaska Zone 7 (EPSG:26937)

```js
var projection = d3.geo.transverseMercator()
  .rotate([162, -54]);
```

### NAD83 / Alaska Zone 8 (EPSG:26938)

```js
var projection = d3.geo.transverseMercator()
  .rotate([166, -54]);
```

### NAD83 / Alaska Zone 9 (EPSG:26939)

```js
var projection = d3.geo.transverseMercator()
  .rotate([170, -54]);
```

### NAD83 / Alaska Zone 10 (EPSG:26940)

```js
var projection = d3.geo.conicConformal()
  .parallels([51 + 50 / 60, 53 + 50 / 60])
  .rotate([176, -51]);
```

### NAD83 / Arizona East (EPSG:26948)

```js
var projection = d3.geo.transverseMercator()
  .rotate([110 + 10 / 60, -31]);
```

### NAD83 / Arizona Central (EPSG:26949)

```js
var projection = d3.geo.transverseMercator()
  .rotate([111 + 55 / 60, -31]);
```

### NAD83 / Arizona West (EPSG:26950)

```js
var projection = d3.geo.transverseMercator()
  .rotate([113 + 45 / 60, -31]);
```

### NAD83 / Arkansas North (EPSG:26951)

```js
var projection = d3.geo.conicConformal()
  .parallels([34 + 56 / 60, 36 + 14 / 60])
  .rotate([92, -34 - 20 / 60]);
```

### NAD83 / Arkansas South (EPSG:26952)

```js
var projection = d3.geo.conicConformal()
  .parallels([33 + 18 / 60, 34 + 46 / 60])
  .rotate([92, -32 - 40 / 60]);
```

### NAD83 / California Zone 1 (EPSG:26941)

```js
var projection = d3.geo.conicConformal()
  .parallels([40, 41 + 40 / 60])
  .rotate([122, -39 - 20 / 60]);
```

### NAD83 / California Zone 2 (EPSG:26942)

```js
var projection = d3.geo.conicConformal()
  .parallels([38 + 20 / 60, 39 + 50 / 60])
  .rotate([122, -37 - 40 / 60]);
```

### NAD83 / California Zone 3 (EPSG:26943)

```js
var projection = d3.geo.conicConformal()
  .parallels([37 + 4 / 60, 38 + 26 / 60])
  .rotate([120 + 30 / 60, -36 - 30 / 60]);
```

### NAD83 / California Zone 4 (EPSG:26944)

```js
var projection = d3.geo.conicConformal()
  .parallels([36, 37 + 15 / 60])
  .rotate([119, -35 - 20 / 60]);
```

### NAD83 / California Zone 5 (EPSG:26945)

```js
var projection = d3.geo.conicConformal()
  .parallels([34 + 2 / 60, 35 + 28 / 60])
  .rotate([118, -33 - 30 / 60]);
```

### NAD83 / California Zone 6 (EPSG:26946)

```js
var projection = d3.geo.conicConformal()
  .parallels([32 + 47 / 60, 33 + 53 / 60])
  .rotate([116 + 15 / 60, -32 - 10 / 60]);
```

### NAD83 / Colorado North (EPSG:26953)

```js
var projection = d3.geo.conicConformal()
  .parallels([39 + 43 / 60, 40 + 47 / 60])
  .rotate([105 + 30 / 60, -39 - 20 / 60]);
```

### NAD83 / Colorado Central (EPSG:26954)

```js
var projection = d3.geo.conicConformal()
  .parallels([38 + 27 / 60, 39 + 45 / 60])
  .rotate([105 + 30 / 60, -37 - 50 / 60]);
```

### NAD83 / Colorado South (EPSG:26955)

```js
var projection = d3.geo.conicConformal()
  .parallels([37 + 14 / 60, 38 + 26 / 60])
  .rotate([105 + 30 / 60, -36 - 40 / 60]);
```

### NAD83 / Connecticut (EPSG:26956)

```js
var projection = d3.geo.conicConformal()
  .parallels([41 + 12 / 60, 41 + 52 / 60])
  .rotate([72 + 45 / 60, -40 - 50 / 60]);
```

### NAD83 / Delaware (EPSG:26957)

```js
var projection = d3.geo.transverseMercator()
  .rotate([75 + 25 / 60, -38]);
```

### NAD83 / Florida East (EPSG:26958)

```js
var projection = d3.geo.transverseMercator()
  .rotate([81, -24 - 20 / 60]);
```

### NAD83 / Florida West (EPSG:26959)

```js
var projection = d3.geo.transverseMercator()
  .rotate([82, -24 - 20 / 60]);
```

### NAD83 / Florida North (EPSG:26960)

```js
var projection = d3.geo.conicConformal()
  .parallels([29 + 35 / 60, 30 + 45 / 60])
  .rotate([84 + 30 / 60, -29]);
```

### NAD83 / Georgia East (EPSG:26966)

```js
var projection = d3.geo.transverseMercator()
  .rotate([82 + 10 / 60, -30]);
```

### NAD83 / Georgia West (EPSG:26967)

```js
var projection = d3.geo.transverseMercator()
  .rotate([84 + 10 / 60, -30]);
```

### NAD83 / Hawaii Zone 1 (EPSG:26961)

```js
var projection = d3.geo.transverseMercator()
  .rotate([155 + 30 / 60, -18 - 50 / 60]);
```

### NAD83 / Hawaii Zone 2 (EPSG:26962)

```js
var projection = d3.geo.transverseMercator()
  .rotate([156 + 40 / 60, -20 - 20 / 60]);
```

### NAD83 / Hawaii Zone 3 (EPSG:26963)

```js
var projection = d3.geo.transverseMercator()
  .rotate([158, -21 - 10 / 60]);
```

### NAD83 / Hawaii Zone 4 (EPSG:26964)

```js
var projection = d3.geo.transverseMercator()
  .rotate([159 + 30 / 60, -21 - 50 / 60]);
```

### NAD83 / Hawaii Zone 5 (EPSG:26965)

```js
var projection = d3.geo.transverseMercator()
  .rotate([160 + 10 / 60, -21 - 40 / 60]);
```

### NAD83 / Idaho East (EPSG:26968)

```js
var projection = d3.geo.transverseMercator()
  .rotate([112 + 10 / 60, -41 - 40 / 60]);
```

### NAD83 / Idaho Central (EPSG:26969)

```js
var projection = d3.geo.transverseMercator()
  .rotate([114, -41 - 40 / 60]);
```

### NAD83 / Idaho West (EPSG:26970)

```js
var projection = d3.geo.transverseMercator()
  .rotate([115 + 45 / 60, -41 - 40 / 60]);
```

### NAD83 / Illinois East (EPSG:26971)

```js
var projection = d3.geo.transverseMercator()
  .rotate([88 + 20 / 60, -36 - 40 / 60]);
```

### NAD83 / Illinois West (EPSG:26972)

```js
var projection = d3.geo.transverseMercator()
  .rotate([90 + 10 / 60, -36 - 40 / 60]);
```

### NAD83 / Indiana East (EPSG:26973)

```js
var projection = d3.geo.transverseMercator()
  .rotate([85 + 40 / 60, -37 - 30 / 60]);
```

### NAD83 / Indiana West (EPSG:26974)

```js
var projection = d3.geo.transverseMercator()
  .rotate([87 + 5 / 60, -37 - 30 / 60]);
```

### NAD83 / Iowa North (EPSG:26975)

```js
var projection = d3.geo.conicConformal()
  .parallels([42 + 4 / 60, 43 + 16 / 60])
  .rotate([93 + 30 / 60, -41 - 30 / 60]);
```

### NAD83 / Iowa South (EPSG:26976)

```js
var projection = d3.geo.conicConformal()
  .parallels([40 + 37 / 60, 41 + 47 / 60])
  .rotate([93 + 30 / 60, -40]);
```

### NAD83 / Kansas North (EPSG:26977)

```js
var projection = d3.geo.conicConformal()
  .parallels([38 + 43 / 60, 39 + 47 / 60])
  .rotate([98, -38 - 20 / 60]);
```

### NAD83 / Kansas South (EPSG:26978)

```js
var projection = d3.geo.conicConformal()
  .parallels([37 + 16 / 60, 38 + 34 / 60])
  .rotate([98 + 30 / 60, -36 - 40 / 60]);
```

### NAD83 / Kentucky North (EPSG:02205)

```js
var projection = d3.geo.conicConformal()
  .parallels([37 + 58 / 60, 38 + 58 / 60])
  .rotate([84 + 15 / 60, -37 - 30 / 60]);
```

### NAD83 / Kentucky South (EPSG:26980)

```js
var projection = d3.geo.conicConformal()
  .parallels([36 + 44 / 60, 37 + 56 / 60])
  .rotate([85 + 45 / 60, -36 - 20 / 60]);
```

### NAD83 / Louisiana North (EPSG:26981)

```js
var projection = d3.geo.conicConformal()
  .parallels([31 + 10 / 60, 32 + 40 / 60])
  .rotate([92 + 30 / 60, -30 - 30 / 60]);
```

### NAD83 / Louisiana South (EPSG:26982)

```js
var projection = d3.geo.conicConformal()
  .parallels([29 + 18 / 60, 30 + 42 / 60])
  .rotate([91 + 20 / 60, -28 - 30 / 60]);
```

### NAD83 / Louisiana Offshore (EPSG:32199)

```js
var projection = d3.geo.conicConformal()
  .parallels([26 + 10 / 60, 27 + 50 / 60])
  .rotate([91 + 20 / 60, -25 - 30 / 60]);
```

### NAD83 / Maine East (EPSG:26983)

```js
var projection = d3.geo.transverseMercator()
  .rotate([68 + 30 / 60, -43 - 40 / 60]);
```

### NAD83 / Maine West (EPSG:26984)

```js
var projection = d3.geo.transverseMercator()
  .rotate([70 + 10 / 60, -42 - 50 / 60]);
```

### NAD83 / Maryland (EPSG:26985)

```js
var projection = d3.geo.conicConformal()
  .parallels([38 + 18 / 60, 39 + 27 / 60])
  .rotate([77, -37 - 40 / 60]);
```

### NAD83 / Massachusetts Mainland (EPSG:26986)

```js
var projection = d3.geo.conicConformal()
  .parallels([41 + 43 / 60, 42 + 41 / 60])
  .rotate([71 + 30 / 60, -41]);
```

### NAD83 / Massachusetts Island (EPSG:26987)

```js
var projection = d3.geo.conicConformal()
  .parallels([41 + 17 / 60, 41 + 29 / 60])
  .rotate([70 + 30 / 60, -41]);
```

### NAD83 / Michigan North (EPSG:26988)

```js
var projection = d3.geo.conicConformal()
  .parallels([45 + 29 / 60, 47 + 5 / 60])
  .rotate([87, -44 - 47 / 60]);
```

### NAD83 / Michigan Central (EPSG:26989)

```js
var projection = d3.geo.conicConformal()
  .parallels([44 + 11 / 60, 45 + 42 / 60])
  .rotate([84 + 22 / 60, -43 - 19 / 60]);
```

### NAD83 / Michigan South (EPSG:26990)

```js
var projection = d3.geo.conicConformal()
  .parallels([42 + 6 / 60, 43 + 40 / 60])
  .rotate([84 + 22 / 60, -41 - 30 / 60]);
```

### NAD83 / Minnesota North (EPSG:26991)

```js
var projection = d3.geo.conicConformal()
  .parallels([47 + 2 / 60, 48 + 38 / 60])
  .rotate([93 + 6 / 60, -46 - 30 / 60]);
```

### NAD83 / Minnesota Central (EPSG:26992)

```js
var projection = d3.geo.conicConformal()
  .parallels([45 + 37 / 60, 47 + 3 / 60])
  .rotate([94 + 15 / 60, -45]);
```

### NAD83 / Minnesota South (EPSG:26993)

```js
var projection = d3.geo.conicConformal()
  .parallels([43 + 47 / 60, 45 + 13 / 60])
  .rotate([94, -43]);
```

### NAD83 / Mississippi East (EPSG:26994)

```js
var projection = d3.geo.transverseMercator()
  .rotate([88 + 50 / 60, -29 - 30 / 60]);
```

### NAD83 / Mississippi West (EPSG:26995)

```js
var projection = d3.geo.transverseMercator()
  .rotate([90 + 20 / 60, -29 - 30 / 60]);
```

### NAD83 / Missouri East (EPSG:26996)

```js
var projection = d3.geo.transverseMercator()
  .rotate([90 + 30 / 60, -35 - 50 / 60]);
```

### NAD83 / Missouri Central (EPSG:26997)

```js
var projection = d3.geo.transverseMercator()
  .rotate([92 + 30 / 60, -35 - 50 / 60]);
```

### NAD83 / Missouri West (EPSG:26998)

```js
var projection = d3.geo.transverseMercator()
  .rotate([94 + 30 / 60, -36 - 10 / 60]);
```

### NAD83 / Montana (EPSG:32100)

```js
var projection = d3.geo.conicConformal()
  .parallels([45, 49])
  .rotate([109 + 30 / 60, -44 - 15 / 60]);
```

### NAD83 / Nebraska (EPSG:32104)

```js
var projection = d3.geo.conicConformal()
  .parallels([40, 43])
  .rotate([100, -39 - 50 / 60]);
```

### NAD83 / Nevada East (EPSG:32107)

```js
var projection = d3.geo.transverseMercator()
  .rotate([115 + 35 / 60, -34 - 45 / 60]);
```

### NAD83 / Nevada Central (EPSG:32108)

```js
var projection = d3.geo.transverseMercator()
  .rotate([116 + 40 / 60, -34 - 45 / 60]);
```

### NAD83 / Nevada West (EPSG:32109)

```js
var projection = d3.geo.transverseMercator()
  .rotate([118 + 35 / 60, -34 - 45 / 60]);
```

### NAD83 / New Hampshire (EPSG:32110)

```js
var projection = d3.geo.transverseMercator()
  .rotate([71 + 40 / 60, -42 - 30 / 60]);
```

### NAD83 / New Jersey (EPSG:32111)

```js
var projection = d3.geo.transverseMercator()
  .rotate([74 + 30 / 60, -38 - 50 / 60]);
```

### NAD83 / New Mexico East (EPSG:32112)

```js
var projection = d3.geo.transverseMercator()
  .rotate([104 + 20 / 60, -31]);
```

### NAD83 / New Mexico Central (EPSG:32113)

```js
var projection = d3.geo.transverseMercator()
  .rotate([106 + 15 / 60, -31]);
```

### NAD83 / New Mexico West (EPSG:32114)

```js
var projection = d3.geo.transverseMercator()
  .rotate([107 + 50 / 60, -31]);
```

### NAD83 / New York East (EPSG:32115)

```js
var projection = d3.geo.transverseMercator()
  .rotate([74 + 30 / 60, -38 - 50 / 60]);
```

### NAD83 / New York Central (EPSG:32116)

```js
var projection = d3.geo.transverseMercator()
  .rotate([76 + 35 / 60, -40]);
```

### NAD83 / New York West (EPSG:32117)

```js
var projection = d3.geo.transverseMercator()
  .rotate([78 + 35 / 60, -40]);
```

### NAD83 / New York Long Island (EPSG:32118)

```js
var projection = d3.geo.conicConformal()
  .parallels([40 + 40 / 60, 41 + 2 / 60])
  .rotate([74, -40 - 10 / 60]);
```

### NAD83 / North Carolina (EPSG:32119)

```js
var projection = d3.geo.conicConformal()
  .parallels([34 + 20 / 60, 36 + 10 / 60])
  .rotate([79, -33 - 45 / 60]);
```

### NAD83 / North Dakota North (EPSG:32120)

```js
var projection = d3.geo.conicConformal()
  .parallels([47 + 26 / 60, 48 + 44 / 60])
  .rotate([100 + 30 / 60, -47]);
```

### NAD83 / North Dakota South (EPSG:32121)

```js
var projection = d3.geo.conicConformal()
  .parallels([46 + 11 / 60, 47 + 29 / 60])
  .rotate([100 + 30 / 60, -45 - 40 / 60]);
```

### NAD83 / Ohio North (EPSG:32122)

```js
var projection = d3.geo.conicConformal()
  .parallels([40 + 26 / 60, 41 + 42 / 60])
  .rotate([82 + 30 / 60, -39 - 40 / 60]);
```

### NAD83 / Ohio South (EPSG:32123)

```js
var projection = d3.geo.conicConformal()
  .parallels([38 + 44 / 60, 40 + 2 / 60])
  .rotate([82 + 30 / 60, -38]);
```

### NAD83 / Oklahoma North (EPSG:32124)

```js
var projection = d3.geo.conicConformal()
  .parallels([35 + 34 / 60, 36 + 46 / 60])
  .rotate([98, -35]);
```

### NAD83 / Oklahoma South (EPSG:32125)

```js
var projection = d3.geo.conicConformal()
  .parallels([33 + 56 / 60, 35 + 14 / 60])
  .rotate([98, -33 - 20 / 60]);
```

### NAD83 / Oregon North (EPSG:32126)

```js
var projection = d3.geo.conicConformal()
  .parallels([44 + 20 / 60, 46])
  .rotate([120 + 30 / 60, -43 - 40 / 60]);
```

### NAD83 / Oregon South (EPSG:32127)

```js
var projection = d3.geo.conicConformal()
  .parallels([42 + 20 / 60, 44])
  .rotate([120 + 30 / 60, -41 - 40 / 60]);
```

### NAD83 / Pennsylvania North (EPSG:32128)

```js
var projection = d3.geo.conicConformal()
  .parallels([40 + 53 / 60, 41 + 57 / 60])
  .rotate([77 + 45 / 60, -40 - 10 / 60]);
```

### NAD83 / Pennsylvania South (EPSG:32129)

```js
var projection = d3.geo.conicConformal()
  .parallels([39 + 56 / 60, 40 + 58 / 60])
  .rotate([77 + 45 / 60, -39 - 20 / 60]);
```

### NAD83 / Rhode Island (EPSG:32130)

```js
var projection = d3.geo.transverseMercator()
  .rotate([71 + 30 / 60, -41 - 5 / 60]);
```

### NAD83 / South Carolina (EPSG:32133)

```js
var projection = d3.geo.conicConformal()
  .parallels([32 + 30 / 60, 34 + 50 / 60])
  .rotate([81, -31 - 50 / 60]);
```

### NAD83 / South Dakota North (EPSG:32134)

```js
var projection = d3.geo.conicConformal()
  .parallels([44 + 25 / 60, 45 + 41 / 60])
  .rotate([100, -43 - 50 / 60]);
```

### NAD83 / South Dakota South (EPSG:32135)

```js
var projection = d3.geo.conicConformal()
  .parallels([42 + 50 / 60, 44 + 24 / 60])
  .rotate([100 + 20 / 60, -42 - 20 / 60]);
```

### NAD83 / Tennessee (EPSG:32136)

```js
var projection = d3.geo.conicConformal()
  .parallels([35 + 15 / 60, 36 + 25 / 60])
  .rotate([86, -34 - 20 / 60]);
```

### NAD83 / Texas North (EPSG:32137)

```js
var projection = d3.geo.conicConformal()
  .parallels([34 + 39 / 60, 36 + 11 / 60])
  .rotate([101 + 30 / 60, -34]);
```

### NAD83 / Texas North Central (EPSG:32138)

```js
var projection = d3.geo.conicConformal()
  .parallels([32 + 8 / 60, 33 + 58 / 60])
  .rotate([98 + 30 / 60, -31 - 40 / 60]);
```

### NAD83 / Texas Central (EPSG:32139)

```js
var projection = d3.geo.conicConformal()
  .parallels([30 + 7 / 60, 31 + 53 / 60])
  .rotate([100 + 20 / 60, -29 - 40 / 60]);
```

### NAD83 / Texas South Central (EPSG:32140)

```js
var projection = d3.geo.conicConformal()
  .parallels([28 + 23 / 60, 30 + 17 / 60])
  .rotate([99, -27 - 50 / 60]);
```

### NAD83 / Texas South (EPSG:32141)

```js
var projection = d3.geo.conicConformal()
  .parallels([26 + 10 / 60, 27 + 50 / 60])
  .rotate([98 + 30 / 60, -25 - 40 / 60]);
```

### NAD83 / Utah North (EPSG:32142)

```js
var projection = d3.geo.conicConformal()
  .parallels([40 + 43 / 60, 41 + 47 / 60])
  .rotate([111 + 30 / 60, -40 - 20 / 60]);
```

### NAD83 / Utah Central (EPSG:32143)

```js
var projection = d3.geo.conicConformal()
  .parallels([39 + 1 / 60, 40 + 39 / 60])
  .rotate([111 + 30 / 60, -38 - 20 / 60]);
```

### NAD83 / Utah South (EPSG:32144)

```js
var projection = d3.geo.conicConformal()
  .parallels([37 + 13 / 60, 38 + 21 / 60])
  .rotate([111 + 30 / 60, -36 - 40 / 60]);
```

### NAD83 / Vermont (EPSG:32145)

```js
var projection = d3.geo.transverseMercator()
  .rotate([72 + 30 / 60, -42 - 30 / 60]);
```

### NAD83 / Virginia North (EPSG:32146)

```js
var projection = d3.geo.conicConformal()
  .parallels([38 + 2 / 60, 39 + 12 / 60])
  .rotate([78 + 30 / 60, -37 - 40 / 60]);
```

### NAD83 / Virginia South (EPSG:32147)

```js
var projection = d3.geo.conicConformal()
  .parallels([36 + 46 / 60, 37 + 58 / 60])
  .rotate([78 + 30 / 60, -36 - 20 / 60]);
```

### NAD83 / Washington North (EPSG:32148)

```js
var projection = d3.geo.conicConformal()
  .parallels([47 + 30 / 60, 48 + 44 / 60])
  .rotate([120 + 50 / 60, -47]);
```

### NAD83 / Washington South (EPSG:32149)

```js
var projection = d3.geo.conicConformal()
  .parallels([45 + 50 / 60, 47 + 20 / 60])
  .rotate([120 + 30 / 60, -45 - 20 / 60]);
```

### NAD83 / West Virginia North (EPSG:32150)

```js
var projection = d3.geo.conicConformal()
  .parallels([39, 40 + 15 / 60])
  .rotate([79 + 30 / 60, -38 - 30 / 60]);
```

### NAD83 / West Virginia South (EPSG:32151)

```js
var projection = d3.geo.conicConformal()
  .parallels([37 + 29 / 60, 38 + 53 / 60])
  .rotate([81, -37]);
```

### NAD83 / Wisconsin North (EPSG:32152)

```js
var projection = d3.geo.conicConformal()
  .parallels([45 + 34 / 60, 46 + 46 / 60])
  .rotate([90, -45 - 10 / 60]);
```

### NAD83 / Wisconsin Central (EPSG:32153)

```js
var projection = d3.geo.conicConformal()
  .parallels([44 + 15 / 60, 45 + 30 / 60])
  .rotate([90, -43 - 50 / 60]);
```

### NAD83 / Wisconsin South (EPSG:32154)

```js
var projection = d3.geo.conicConformal()
  .parallels([42 + 44 / 60, 44 + 4 / 60])
  .rotate([90, -42]);
```

### NAD83 / Wyoming East (EPSG:32155)

```js
var projection = d3.geo.transverseMercator()
  .rotate([105 + 10 / 60, -40 - 30 / 60]);
```

### NAD83 / Wyoming East Central (EPSG:32156)

```js
var projection = d3.geo.transverseMercator()
  .rotate([107 + 20 / 60, -40 - 30 / 60]);
```

### NAD83 / Wyoming West Central (EPSG:32157)

```js
var projection = d3.geo.transverseMercator()
  .rotate([108 + 45 / 60, -40 - 30 / 60]);
```

### NAD83 / Wyoming West (EPSG:32158)

```js
var projection = d3.geo.transverseMercator()
  .rotate([110 + 5 / 60, -40 - 30 / 60]);
```

### NAD83 / Puerto Rico (EPSG:32161)

```js
var projection = d3.geo.conicConformal()
  .parallels([18 + 2 / 60, 18 + 26 / 60])
  .rotate([66 + 26 / 60, -17 - 50 / 60]);
```
