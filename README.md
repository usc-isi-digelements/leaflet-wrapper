# leaflet-wrapper

A Polymer Element that wraps a [leaflet-map](https://github.com/DigElements/leaflet-map).

### Example
```js
var data = [{
  latitude: 38.882222,
  longitude: -77.171111,
  text: 'Falls Church, VA'
}, {
  latitude: 39.203611,
  longitude: -76.856944,
  text: "Columbia, MD"
}];
```

```html
<leaflet-wrapper data="[[data]]"></leaflet-wrapper>
```

### Dependencies

Dependencies are installed using [Bower](http://bower.io/):

    npm install -g bower
    bower install

### Testing

Tests are run using [web-component-tester](https://github.com/Polymer/web-component-tester):

    npm install -g web-component-tester
    wct

### Demonstration & Documentation

Demonstration and documentation are viewed using [polyserve](https://github.com/PolymerLabs/polyserve):

    npm install -g polyserve
    polyserve

