#### Arrow functions shorthand
<br>

```
var materials = [
  'Hydrogen',
  'Helium',
  'Lithium',
  'Beryllium'
];

var materialsLength = materials.map(function(material) { 
  return material.length;
});

var materialsLength = materials.map((material) => {
  return material.length;
});

var materialsLength = materials.map(material => material.length);

```