# An Template which tells you the absolut/true humidity.

Create in Helpers > template > Sensor

then copy the code in: [`absolut_humidity.yaml`](./absolut_humidity.yaml)

and change in the
('') with your sensors.
```yaml
{% set T  = states('sensor.weather_temperature')   | float(0) %}
{% set RH = states('sensor.weather_humidity') | float(0) %}
```
