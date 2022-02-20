# MqttAssistant

## Run server
```
python -m mqttassistant
```

### Run tests
```
python -m unittest
tox
```

### Test coverage
```
coverage run -m unittest && coverage report --skip-covered
coverage html
```

### Ui develpment
```
cd ui
flutter run --web-port 8080 -d chrome
```
