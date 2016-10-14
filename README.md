#Vehicle Identification Number (VIN) Generator
A VIN is used by a vehicle manufacturer to uniquely identify vehicles.
This library is designed to generate random VINs for use in testing applications which either display or validate VINs.
It is a javascript port of the python library created by [yanigisawa](https://github.com/yanigisawa/VinGenerator).

##Usage

```js
var vinGenerator = require('vin-generator');

var randomVin = vinGenerator.generateVin();
```

