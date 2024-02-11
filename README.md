# iocage-tom60-plugins
[Tom60](https://github.com/Tom60chat) iocage plugins for [TrueNAS CORE](http://www.truenas.com)

When a plugin is made 'official' it should be added to the INDEX json and
it will appear in iocage's plugin listing

# Installing Plugins

## Using Local File
```
iocage fetch -P /the/path/to/plugin.json -n plugin
```

## Pulling from Internet
```
iocage fetch --plugins --name "plugin"
```