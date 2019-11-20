# GalaxyGeometry
Galaxy Geometry for THREE js

## Usage

```javascript
var geometry = new THREE.GalaxyGeometry();
var material = new THREE.PointsMaterial();
var galaxy = new THREE.Points(geometry, material);
scene.add(galaxy);
```

## Parameters

* radius

## Note

Please note that this type of geometry only have vertices (haven't faces, and uvs), so you can only use it for THREE.Points!
