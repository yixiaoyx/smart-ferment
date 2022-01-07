# Smart Fermentation Box

Smart Fermentation Box built with [Home Assistant](https://www.home-assistant.io/) running on Raspberry Pi.

It is being used to ferment yoghurt, kombucha, sourdough bread, sauerkraut, etc. The smart temperature control (and humidity control to come) with monitoring and alerting solves the greatest challenge in any kind of fermentation, and makes it a breeze to produce good, consistent fermentation results every time. The digital and wireless nature of the solution minimizes wiring and the risk of physical damage (such as circuit issues caused by humidity), and is more portable and flexible than the conventional analog way, while still being affordable for home use.

Note that if the desired temperature is colder than the environment, the temperature can no longer be controlled digitally, and requires the use of ice packs. However the smart monitoring and alerting still comes in handy, which not only provides observability but is also helpful for determining the right amount of ice packs to minimize human intervention.

## Hardware specs
- Raspberry Pi 4 Model B with 4GB RAM
- Micro SD card A2 128GB
- Bluetooth hygrometer & thermometer (IBS-TH1 Plus)
- Seedling heating mat 20W, 10" x 20.75"
- Wifi & bluetooth smart plug (PC191HA)
- Plastic cooler box and ice packs

## Home Assistant integrations required
- [rospogrigio/localtuya](https://github.com/rospogrigio/localtuya/)
- [yixiaoyx/home-assistant_inkbird](https://github.com/yixiaoyx/home-assistant_inkbird)

## Features
- [x] Temperature and humidity monitoring
- [x] Temperature control via heating mat
- [x] Configurable temperature range on the UI
- [x] Alerting when temperature goes out of range
- [ ] Humidity control via humidifier
- [ ] Configurable humidity range on the UI
- [ ] Alerting when humidity goes out of range

More features to come...

