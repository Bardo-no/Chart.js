<h1>my Chart.js Fork</h1>
<p>This is a chart.js fork where i have added some functionality to implement on a test project. Two options have been added and will be described below </p>

<h3>hoverExtraBorderColor</b></h3>
<p>for the line controller dataset the option hoverExtraBorderColor its available for for the default point style, it will add an extra ring below the fill and stroke of the original point using the specified hex color.
</p>


```javascript
const datasets:ChartDataSets[] = [
      {
        label: 'test',
        data: [1,2,3,4],
        backgroundColor: '#4c4cd8a1',
        borderColor: '#4c4cd8a1',
        pointHoverBackgroundColor : '#4C4CD8',
        pointHoverBorderColor : '#4c4cd8a1',
        //setting color for extra ring when hovering
        hoverExtraBorderColor: '#4c4cd880',
      }
```

<h3>hoverColor</h3>
<p>for the ticks options on the scales there is the hoverColor option wich will replace the color of the ticks for the specified hex color when there is an active hovered element</p>

```javascript
const options : ChartOptions = {
	scales : {
        xAxes : [
          {
            ticks : {
              fontColor : '#EBEBEBa1',
              //setting color when hovering on a point in range
              hoverColor: '#F8CB1C',
            },
          },
        ],
```

<p>original readme below.</p>


<p align="center">
    <img src="https://www.chartjs.org/media/logo-title.svg"><br/>
    Simple yet flexible JavaScript charting for designers & developers
</p>

<p align="center">
    <a href="https://www.chartjs.org/docs/latest/getting-started/installation.html"><img src="https://img.shields.io/github/release/chartjs/Chart.js.svg?style=flat-square&maxAge=600" alt="Downloads"></a>
    <a href="https://travis-ci.org/chartjs/Chart.js"><img src="https://img.shields.io/travis/chartjs/Chart.js.svg?style=flat-square&maxAge=600" alt="Builds"></a>
    <a href="https://coveralls.io/github/chartjs/Chart.js?branch=master"><img src="https://img.shields.io/coveralls/chartjs/Chart.js.svg?style=flat-square&maxAge=600" alt="Coverage"></a>
    <a href="https://github.com/chartjs/awesome"><img src="https://awesome.re/badge-flat2.svg" alt="Awesome"></a>
    <a href="https://chartjs-slack.herokuapp.com/"><img src="https://img.shields.io/badge/slack-chartjs-blue.svg?style=flat-square&maxAge=3600" alt="Slack"></a>
</p>

## Documentation

- [Introduction](https://www.chartjs.org/docs/latest/)
- [Getting Started](https://www.chartjs.org/docs/latest/getting-started/)
- [General](https://www.chartjs.org/docs/latest/general/)
- [Configuration](https://www.chartjs.org/docs/latest/configuration/)
- [Charts](https://www.chartjs.org/docs/latest/charts/)
- [Axes](https://www.chartjs.org/docs/latest/axes/)
- [Developers](https://www.chartjs.org/docs/latest/developers/)
- [Popular Extensions](https://github.com/chartjs/awesome)
- [Samples](https://www.chartjs.org/samples/)

## Contributing

Instructions on building and testing Chart.js can be found in [the documentation](https://github.com/chartjs/Chart.js/blob/master/docs/developers/contributing.md#building-and-testing). Before submitting an issue or a pull request, please take a moment to look over the [contributing guidelines](https://github.com/chartjs/Chart.js/blob/master/docs/developers/contributing.md) first. For support, please post questions on [Stack Overflow](https://stackoverflow.com/questions/tagged/chartjs) with the `chartjs` tag.

## License

Chart.js is available under the [MIT license](https://opensource.org/licenses/MIT).
