# kontena-mongodb-pannu

A simple development grade MongoDB for Kontena. The word "pannu" is Finnish and used by oldschool system administrators who hug their servers. This is about just as reliable as those servers.

```
kontena app deploy -p mongodb
```

## Good commands

```
kontena service show mongodb-pannu
kontena service containers mongodb-pannu
kontena container exec mongodb-pannu-1 'mongo --version'
mongo mongodb-pannu.GRID.kontena.local
```
