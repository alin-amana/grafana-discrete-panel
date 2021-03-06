## Discrete Panel

This panel shows discrete values in a horizontal graph.  This lets show state transitions clearly.  It is a good
choice to display string or boolean data


### Screenshots

![example](https://raw.githubusercontent.com/NatelEnergy/grafana-discrete-panel/master/src/img/screenshot-single-1.png)
![example](https://raw.githubusercontent.com/NatelEnergy/grafana-discrete-panel/master/src/img/screenshot-single-2.png)
![example](https://raw.githubusercontent.com/NatelEnergy/grafana-discrete-panel/master/src/img/screenshot-single-3.png)
![example](https://raw.githubusercontent.com/NatelEnergy/grafana-discrete-panel/master/src/img/screenshot-single-4.png)
![example](https://raw.githubusercontent.com/NatelEnergy/grafana-discrete-panel/master/src/img/screenshot-multiple.png)
![options](https://raw.githubusercontent.com/NatelEnergy/grafana-discrete-panel/master/src/img/screenshot-options-1.png)
![options](https://raw.githubusercontent.com/NatelEnergy/grafana-discrete-panel/master/src/img/screenshot-options-2.png)

#### Changelog


##### v0.0.6
... not yet released ...
- Add option to show results as a stacked bar chart rather than timeline


##### v0.0.5

- Support results from the table format
- Support results in ascending or decending order
- Configure legend percentage decimal points
- Legend can show transition count and distinct value count
- Clamp percentage stats within the query time window
- Changed the grafana dependency version to 4.x.x, since 3.x.x was not really supported
- Fixed issues with tooltip hover position
- Option to expand 'from' query so the inital state can avoid 'null'


##### v0.0.4

- Support shared tooltips (not just crosshair)


##### v0.0.3

- Configure more colors (retzkek)
- Fix tooltips (retzkek)
- Configure Text Size
- Support shared crosshair


##### v0.0.2

- Use the panel time shift.


##### v0.0.1

- First working version

