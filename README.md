# M5StickC Plus

## Introduction
Example ESP32 project to showcase how you can pull temperature, humidity and pressure data from the ENV III sensor paired with the M5 StickC Plus.

In this project, you have a configuration file ```config.h``` where you can configure your WiFi credentials, as well as your Grafana Cloud credentials. Data is written to Grafana Cloud using the Influx proxy, where the metrics will then be converted to Prometheus format for querying and visualisation. 

## Handy Links for the workshop
* Download the latest Arduino IDE:
```
https://www.arduino.cc/en/software
```

* Board Manager links:
```
https://m5stack.oss-cn-shenzhen.aliyuncs.com/resource/arduino/package_m5stack_index.json
https://raw.githubusercontent.com/espressif/arduino-esp32/gh-pages/package_esp32_index.json
```


## Grafana Dashboard
There is an example dashboard that you can use inside Grafana for this project, by importing ```17782```. 

Alternatively you can also grab the example dashboard from Grafana itself: https://grafana.com/grafana/dashboards/17782-m5stickc-plus/

![image](https://user-images.githubusercontent.com/1435796/210529949-2c301a6d-2f37-4e90-9fb9-1150d137b6ac.png)
