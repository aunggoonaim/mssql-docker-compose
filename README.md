# PERMISSION ERROR ?

`mkdir mssqldata && sudo chown 10001 ./mssqldata`

## ALTER COLATION ?

`ALTER DATABASE plesscube SET SINGLE_USER WITH ROLLBACK IMMEDIATE;`
`ALTER DATABASE plesscube COLLATE THAI_CS_AS;`

## COPY BACKUP

`docker cp C:/AIM/Database/SMARTPM_QAS_080422_0025.bak 760:/var/opt/mssql/data`

`docker exec -it 760 rm /var/opt/mssql/data/SMARTPM_QAS_080422_0025.bak`

## BACK UP

`BACKUP DATABASE [SMARTPM] TO DISK = N'/var/opt/mssql/data/SMARTPM_QAS_080422_0025.bak' WITH FORMAT, INIT, COMPRESSION,STATS = 10`