# Examples
In this section, some of the results and simulations obtained using the library are shown, comparing where possible with results from simulations such as EnergyPlus. In particular, below are shown the values of the simulations obtained from the best-test 600 building, using the same epw weather file (Denver-Stapleton).

<br>

<html>
<body >
    <div id="5f604bee6a0e49ca91e1e8b3032c5984" class="chart-container" style="width:1200px; height:600px; "></div>
    <script>
        var chart_5f604bee6a0e49ca91e1e8b3032c5984 = echarts.init(
            document.getElementById('5f604bee6a0e49ca91e1e8b3032c5984'), 'shine', {renderer: 'canvas'});
        var option_5f604bee6a0e49ca91e1e8b3032c5984 = {
    "animation": true,
    "animationThreshold": 2000,
    "animationDuration": 1000,
    "animationEasing": "cubicOut",
    "animationDelay": 0,
    "animationDurationUpdate": 300,
    "animationEasingUpdate": "cubicOut",
    "animationDelayUpdate": 0,
    "aria": {
        "enabled": false
    },
    "series": [
        {
            "type": "bar",
            "name": "Q_H",
            "legendHoverLink": true,
            "data": [
                26.59,
                22.29,
                12.73,
                9.6,
                4.15,
                0.49,
                0.03,
                0.3,
                1.18,
                9.13,
                16.33,
                26.77
            ],
            "realtimeSort": false,
            "showBackground": false,
            "stackStrategy": "samesign",
            "cursor": "pointer",
            "barMinHeight": 0,
            "barCategoryGap": "20%",
            "barGap": "30%",
            "large": false,
            "largeThreshold": 400,
            "seriesLayoutBy": "column",
            "datasetIndex": 0,
            "clip": true,
            "zlevel": 0,
            "z": 2,
            "label": {
                "show": true,
                "margin": 8
            }
        },
        {
            "type": "bar",
            "name": "Q_H EnergyPlus",
            "legendHoverLink": true,
            "data": [
                20.69,
                20.09,
                8.67,
                9.63,
                4.17,
                1.12,
                0.13,
                0.83,
                1.94,
                8.06,
                14.37,
                20.54
            ],
            "realtimeSort": false,
            "showBackground": false,
            "stackStrategy": "samesign",
            "cursor": "pointer",
            "barMinHeight": 0,
            "barCategoryGap": "20%",
            "barGap": "30%",
            "large": false,
            "largeThreshold": 400,
            "seriesLayoutBy": "column",
            "datasetIndex": 0,
            "clip": true,
            "zlevel": 0,
            "z": 2,
            "label": {
                "show": true,
                "margin": 8
            }
        },
        {
            "type": "bar",
            "name": "Q_C",
            "legendHoverLink": true,
            "data": [
                6.46,
                7.94,
                11.16,
                8.25,
                8.51,
                12.29,
                18.12,
                16.25,
                22.0,
                17.25,
                11.32,
                6.13
            ],
            "realtimeSort": false,
            "showBackground": false,
            "stackStrategy": "samesign",
            "cursor": "pointer",
            "barMinHeight": 0,
            "barCategoryGap": "20%",
            "barGap": "30%",
            "large": false,
            "largeThreshold": 400,
            "seriesLayoutBy": "column",
            "datasetIndex": 0,
            "clip": true,
            "zlevel": 0,
            "z": 2,
            "label": {
                "show": true,
                "margin": 8
            }
        },
        {
            "type": "bar",
            "name": "Q_C EnergyPlus",
            "legendHoverLink": true,
            "data": [
                7.6,
                9.76,
                10.53,
                7.07,
                6.72,
                9.62,
                12.68,
                12.76,
                19.43,
                16.09,
                12.84,
                7.26
            ],
            "realtimeSort": false,
            "showBackground": false,
            "stackStrategy": "samesign",
            "cursor": "pointer",
            "barMinHeight": 0,
            "barCategoryGap": "20%",
            "barGap": "30%",
            "large": false,
            "largeThreshold": 400,
            "seriesLayoutBy": "column",
            "datasetIndex": 0,
            "clip": true,
            "zlevel": 0,
            "z": 2,
            "label": {
                "show": true,
                "margin": 8
            }
        }
    ],
    "legend": [
        {
            "data": [
                "Q_H",
                "Q_H EnergyPlus",
                "Q_C",
                "Q_C EnergyPlus"
            ],
            "selected": {},
            "show": true,
            "padding": 5,
            "itemGap": 10,
            "itemWidth": 25,
            "itemHeight": 14,
            "backgroundColor": "transparent",
            "borderColor": "#ccc",
            "borderWidth": 1,
            "borderRadius": 0,
            "pageButtonItemGap": 5,
            "pageButtonPosition": "end",
            "pageFormatter": "{current}/{total}",
            "pageIconColor": "#2f4554",
            "pageIconInactiveColor": "#aaa",
            "pageIconSize": 15,
            "animationDurationUpdate": 800,
            "selector": false,
            "selectorPosition": "auto",
            "selectorItemGap": 7,
            "selectorButtonGap": 10
        }
    ],
    "tooltip": {
        "show": true,
        "trigger": "axis",
        "triggerOn": "mousemove|click",
        "axisPointer": {
            "type": "line"
        },
        "showContent": true,
        "alwaysShowContent": false,
        "showDelay": 0,
        "hideDelay": 100,
        "enterable": false,
        "confine": false,
        "appendToBody": false,
        "transitionDuration": 0.4,
        "textStyle": {
            "fontSize": 14
        },
        "borderWidth": 0,
        "padding": 5,
        "order": "seriesAsc"
    },
    "xAxis": [
        {
            "show": true,
            "scale": false,
            "nameLocation": "end",
            "nameGap": 15,
            "gridIndex": 0,
            "inverse": false,
            "offset": 0,
            "splitNumber": 5,
            "minInterval": 0,
            "splitLine": {
                "show": true,
                "lineStyle": {
                    "show": true,
                    "width": 1,
                    "opacity": 1,
                    "curveness": 0,
                    "type": "solid"
                }
            },
            "data": [
                "Jan",
                "Feb",
                "Mar",
                "Apr",
                "May",
                "Jun",
                "Jul",
                "Aug",
                "Sep",
                "Oct",
                "Nov",
                "Dec"
            ]
        }
    ],
    "yAxis": [
        {
            "show": true,
            "scale": false,
            "nameLocation": "end",
            "nameGap": 15,
            "gridIndex": 0,
            "inverse": false,
            "offset": 0,
            "splitNumber": 5,
            "minInterval": 0,
            "splitLine": {
                "show": true,
                "lineStyle": {
                    "show": true,
                    "width": 1,
                    "opacity": 1,
                    "curveness": 0,
                    "type": "solid"
                }
            }
        }
    ],
    "title": [
        {
            "show": true,
            "text": "Monthly consumption",
            "target": "blank",
            "subtarget": "blank",
            "padding": 5,
            "itemGap": 10,
            "textAlign": "auto",
            "textVerticalAlign": "auto",
            "triggerEvent": false
        }
    ],
    "toolbox": {
        "show": true,
        "orient": "horizontal",
        "itemSize": 15,
        "itemGap": 10,
        "left": "80%",
        "feature": {
            "saveAsImage": {
                "type": "png",
                "backgroundColor": "auto",
                "connectedBackgroundColor": "#fff",
                "show": true,
                "title": "Download as Image",
                "pixelRatio": 1
            },
            "restore": {
                "show": true,
                "title": "Restore"
            },
            "dataView": {
                "show": true,
                "title": "View Data",
                "readOnly": false,
                "lang": [
                    "Data View",
                    "Close",
                    "Refresh"
                ],
                "backgroundColor": "#fff",
                "textareaColor": "#fff",
                "textareaBorderColor": "#333",
                "textColor": "#000",
                "buttonColor": "#c23531",
                "buttonTextColor": "#fff"
            },
            "dataZoom": {
                "show": true,
                "title": {
                    "zoom": "Zoom In",
                    "back": "Zoom Out"
                },
                "icon": {},
                "filterMode": "filter"
            },
            "magicType": {
                "show": false,
                "type": [
                    "line",
                    "bar",
                    "stack",
                    "tiled"
                ],
                "title": {
                    "line": "\u5207\u6362\u4e3a\u6298\u7ebf\u56fe",
                    "bar": "\u5207\u6362\u4e3a\u67f1\u72b6\u56fe",
                    "stack": "\u5207\u6362\u4e3a\u5806\u53e0",
                    "tiled": "\u5207\u6362\u4e3a\u5e73\u94fa"
                },
                "icon": {}
            }
        }
    },
    "dataZoom": [
        {
            "show": true,
            "type": "slider",
            "showDetail": true,
            "showDataShadow": true,
            "realtime": true,
            "start": 0,
            "end": 100,
            "orient": "horizontal",
            "zoomLock": false,
            "filterMode": "filter"
        },
        {
            "show": true,
            "type": "inside",
            "showDetail": true,
            "showDataShadow": true,
            "realtime": true,
            "start": 20,
            "end": 80,
            "orient": "horizontal",
            "zoomLock": false,
            "filterMode": "filter"
        }
    ]
};
        chart_5f604bee6a0e49ca91e1e8b3032c5984.setOption(option_5f604bee6a0e49ca91e1e8b3032c5984);
    </script>
</body>
</html>