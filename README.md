# Pull backup #

This script uses rsync and copy with hard links to create efficient differential backup over SSH.

# configuration #

Edit the file /etc/backup_plan.conf

```
ip:folder,folder,folder
```

For example:

```
gw:/etc,/home
```
 
# Running #

```
./pull_backup.py -c /etc/backup_plan.py
```

