# mapbox-gl-pitch-toggle-control
Simple pitch on/off button in Mapbox GL JS style. 

![demo](https://i.imgur.com/iW7CQ23.gif)

```javascript
map.addControl(new PitchToggle({minpitchzoom: 11})); 
```

Options (optional):

*   *bearing*: Bearing for 3d mode. Default is -20.
*   *pitch*: Pitch for 3D mode. Default it 70.
*   *minpitchzoom*: Minimum zoom level for 3D mode, so you don't have flying polygons gouging out eyeballs. Default it null (i.e. stays at same zoom).

Note that the control is as an ES6 class, so running it through something like Babel is necessary.
