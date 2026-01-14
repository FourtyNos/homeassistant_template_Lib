# An Template which tells you in which position your Windows ist
![Siegenia_Handle](siegenia_smart_handle.webp)

Create in Helpers > template > Sensor



then copy the code in: [`SIEGENIA_Smart_Window_Handle.yaml`](./SIEGENIA_Smart_Window_Handle.yaml)

and change in the
('') with your sensors.
```yaml
{% set sense1 = states('binary_sensor."yourhandle"_tur') %}
{% set sense2 = states('binary_sensor."yourhandle"_tur_2') %}
```
