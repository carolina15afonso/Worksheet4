# FleetCheck – Build Systems Lab

This project is intentionally incomplete. Follow the worksheet in the order given.

Expected final application output:

```
FleetCheck 1.0
Vehicles loaded: 4
Vehicles requiring service: 2
Average mileage: 37000 km
```

Do not copy the solution POM. The objective is to observe how each build change alters the result.

1
[ERROR] /C:/Users/carol/Desktop/Faculdade/3ºano/QualidadeSoftware/worksheet4/FleetCheck_Starter/src/main/java/pt/upt/fleetcheck/App.java:[11,9] cannot find symbol
  symbol:   class ObjectMapper
  location: class pt.upt.fleetcheck.App

O erro é causado pelo seguinte import no App.java: import com.fasterxml.jackson.databind.ObjectMapper;
