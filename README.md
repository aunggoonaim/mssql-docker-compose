# PERMISSION ERROR ?

`mkdir mssqldata && sudo chown 10001 ./mssqldata`

## ALTER COLATION ?

`ALTER DATABASE plesscube SET SINGLE_USER WITH ROLLBACK IMMEDIATE;`
`ALTER DATABASE plesscube COLLATE THAI_CS_AS;`

## COPY BACKUP

`docker cp C:/AIM/Database/SMARTPM_QAS_080422_0025.bak eb2:/var/opt/mssql`
