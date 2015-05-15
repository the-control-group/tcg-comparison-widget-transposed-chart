# tcg-comparison-widget-transposed-chart

This is a re-usable Polymer 0.5.* comparison element that can be used to display a chart for the comparison widget when
it is transposed.

### How to install

```
bower install --save tcg-comparison-widget-transposed-chart
```

## How to use
###Include the element in your page

```
<link rel="import" href="/bower_components/tcg-comparison-widget-transposed-chart/tcg-comparison-widget-transposed-chart.html">
```

###Then use the element in your page

```
<tcg-comparison-widget-transposed-chart
  chart-title="Test"
  chart-data-series="[{'data': [ [1422748800000, 500], [1422835200000, 1000], [1422921600000, 3000], [1423008000000, 4000], [1423094400000, 3000], [1423180800000, 2000], [1423267200000, 1700] ]}]"
  chart-data-closable="true">
</tcg-comparison-widget-transposed-chart>
```
