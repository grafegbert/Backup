Dieses repo enthält meine backupconfiguration mit rsync


die datei crontab wurde mit dem befehl `crontab -e` angelegt und editiert.
um sie im git repo aufzunehmen wurde folgender befehl verwendet:

```sh
ln /var/spool/cron/crontabs/$USER Crontab
```

um das backup aus deisem repo wieder neu aufzusetzten kann folgender befehl verwendet werden: 

```sh
ln Crontab /var/spool/cron/crontabs/$USER
```
