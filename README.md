# simpler-way-iot-central-demo



rename TemperatureController\Properties\launchSettings-sample.json to launchSettings.json

fill in environment variables
```
      "environmentVariables": {
        "IOTHUB_DEVICE_DPS_ID_SCOPE": "",
        "IOTHUB_DEVICE_DPS_ENDPOINT": "",
        "IOTHUB_DEVICE_SECURITY_TYPE": "",
        "IOTHUB_DEVICE_DPS_DEVICE_ID": "",
        "IOTHUB_DEVICE_DPS_DEVICE_KEY": ""
      }
```

```
> cd TemperaturController
> dotnet build
> dotnet run
```

