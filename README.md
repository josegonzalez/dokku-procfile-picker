# dokku-procfile-picker

## requirements

- dokku 0.4.x+
- docker 1.8.x

## installation

```shell
# on 0.4.x+
sudo dokku plugin:install https://github.com/josegonzalez/dokku-procfile-picker.git dokku-procfile-picker
```

## usage

```shell
# replace APP_NAME with your application's name
dokku config:set APP_NAME DOKKU_PROCFILE=Procfile.api
```

And then deploy!
