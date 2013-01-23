mysql_export_users
==================

Export MySQL Users

###OPTIONS:
> -u      User
>
> -p      Password
>
>>   --password=...
>
> -s      Selects a specific user
>
> -h      Host

###Examples:

> ./mysql_export_users -u myUser -h myHost -s filterUser -p
>
> ./mysql_export_users -u myUser --password='myPassword'
