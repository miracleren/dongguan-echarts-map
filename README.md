# dongguan-echarts-map
基于echarts生成的东莞区域图表及广东图表

# 地图上图片数据具体参考echarts,数据结构也是。
```javascript
myChart.setOption(option = {
                            visualMap: {
                                left: 'right',
                                min: 0,
                                max: 10000,
                                inRange: {
                                    color: ['#313695', '#4575b4', '#74add1', '#abd9e9', '#e0f3f8', '#ffffbf', '#fee090', '#fdae61', '#f46d43', '#d73027', '#a50026']
                                },
                                text:['High','Low'],           // 文本，默认为数值文本
                                calculable: true
                            },
                            series: [
                                {

                                    type: 'map',
                                    roam: true,
                                    map: 'DG', 
                                    itemStyle:{
                                        normal:{label:{show:true}},
                                        emphasis:{label:{show:true}}
                                    },
                                    data:newData
                                    
                                }
                            ]
                        });
```

# 地图坐标是自己抓取生成的，坐标细化度不大，边角相对多

# 东莞地图2D版热力图
![image](https://github.com/miracleren/dongguan-echarts-map/blob/master/pic/pic1.png)

# 东莞地图3D版柱状图
![image](https://github.com/miracleren/dongguan-echarts-map/blob/master/pic/pic2.png)

# 广东地图2D版热力图
![image](https://github.com/miracleren/dongguan-echarts-map/blob/master/pic/pic3.png)
