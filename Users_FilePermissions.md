# 
## Check user id and group id 
```
id
```

## Check UID and GID of a specific user
```
id developer1
```

## Change the owner of a file by using sudo (getting some privileges as a root user)
```
sudo chown -R :sales-team /Finance/Sales-Reports
```

## View the properties of a directory (instead of listing contents of a directory)
```
ls -dl /Finance/Sales-Reports
```