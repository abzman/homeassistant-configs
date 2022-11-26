# Directory Contents
## Generic config files
In the `packages` directory, there are configs for base components (ota, api, wifi, etc.), general purpose sensors (uptime, wifi signal, etc), and particular boards. For the most part, including one of the board files and `esp_home_components.yaml` will give you a minimally functional device. Usually you only need these files for custom devices. For everything else see below.

## Hardware configs
There are templates for a variety of hardware in this directory. Mostly named `[hardware]_[function].yaml`. For example `sonoff_basic_light.yaml` gives you a light entity in Home Assistant, while `sonoff_basic_switch.yaml` gives you a switch. There's probably a way to do this better since the two files are almost identical, but meh.
