# Dragon-Nest-Ex95

File Server Dragon Nest Semi Official 95EX(old)
========================
Bahan-Bahan

1.DataBase : https://bit.ly/2zWeKsO

2.Client : https://bit.ly/2QtxV2A

3.Server : https://bit.ly/2PhAOU5

4.Key : https://bit.ly/2C1j0cb

5.web : https://bit.ly/2RsrfmK

guide instal server

guide by me

1.instal SQL 2014

2.Restore 3 DB

3.instal query


if not exists (select * from master.dbo.syslogins where name = 'DragonNest') 
begin 
exec sp_addlogin 'DragonNest', 'skQmsgozj!*sha' 
end

use DNMembership_80EX
go
EXEC sp_change_users_login 'Update_One', 'DragonNest', 'DragonNest'
go
use DNServerLog
go
EXEC sp_change_users_login 'Update_One', 'DragonNest', 'DragonNest'
go
use DNWorld
go
EXEC sp_change_users_login 'Update_One', 'DragonNest', 'DragonNest'
go

4.change port

5.install loopback ip=10.6.11.11

6.install phpstudy > extract patch to folder www

7.edit host

8.start NetLauncherD

9.ServiceManagerExD

10.enjoy :D
