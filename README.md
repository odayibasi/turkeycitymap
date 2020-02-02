# Turkey City Heatmap Visualization
Turkey City Visualization With D3.js  [Demo](http://onurdayibasi.com.s3-website-eu-west-1.amazonaws.com/turkeycitymap/)
- You can see city population with heatmap graph. Color scale generate with linear interpolation.
```javascript
var color = d3.scale.linear().domain([0, 4113072]).range(["#e8e8e8", "#d62728"]);
```

![TurkeyCityHeatmap](/docs/images/turkeyheatmap.png)


- You can see details of city __Zoom in__ with click mouse to city also __Zoomo out__ clicking again 


![Ankara HeatMap Details](/docs/images/ankaraheatmap_details.png)
