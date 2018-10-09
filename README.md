[![Build status](https://ci.appveyor.com/api/projects/status/ldk031dvcn2no51g?svg=true)](https://ci.appveyor.com/project/Xabaril/aspnetcore-diagnostics-healthchecks) 

[![Build history](https://buildstats.info/appveyor/chart/xabaril/aspnetcore-diagnostics-healthchecks)](https://ci.appveyor.com/project/xabaril/aspnetcore-diagnostics-healthchecks/history)


# AspNetCore.Diagnostics.HealthChecks

This project is a [BeatPulse](http://github.com/xabaril/beatpulse) liveness and UI port to new *Microsoft Health Checks* feature included on **ASP.NET Core 2.2**.

## Included Health Checks

HealthChecks packages include health checks for Sql Server, MySql, Oracle, Sqlite, Postgres, RabbitMQ, Redis, System: Disk Storage, Private Memory, Virtual Memory, Azure Service Bus: EventHub, Queue and Topics, Azure Storage: Blob, Queue and Table, Azure DocumentDb, Amazon DynamoDb, Network: Ftp, SFtp, Dns, Tcp port, Smtp, Impa, Mongo, Kafka, Identity Server and Uri: single uri and uri groups

``` PowerShell
Install-Package HealthChecks.System
Install-Package HealthChecks.Network
Install-Package HealthChecks.SqlServer
Install-Package HealthChecks.MongoDb
Install-Package HealthChecks.Npgsql
Install-Package HealthChecks.Redis
Install-Package HealthChecks.AzureStorage
Install-Package HealthChecks.AzureServiceBus
Install-Package HealthChecks.MySql
Install-Package HealthChecks.DocumentDb
Install-Package HealthChecks.SqLite
Install-Package HealthChecks.Kafka
Install-Package HealthChecks.RabbitMQ
Install-Package HealthChecks.IdSvr
Install-Package HealthChecks.DynamoDB
Install-Package HealthChecks.Oracle
Install-Package HealthChecks.Uris
```

## Health Check UI and Fail notifications

** TODO ** 

## Contributing

AspNetCore.Diagnostics.HealthChecks  wouldn't be possible without the time and effort of its contributors. The team is made up of Unai Zorrilla Castro @unaizorrilla, Luis Ruiz Pavón @lurumad, Carlos Landeras @carloslanderas and Eduard Tomás @eiximenis.

*Our valued committers are*: Hugo Biarge @hbiarge, Matt Channer @mattchanner, Luis Fraile @lfraile, Bradley Grainger @bgrainger.

If you want to contribute to a project and make it better, your help is very welcome. You can contribute with helpful bug reports, feature request and also new features with pull requests.

1. Read and follow the [Don't push your pull requests](https://www.igvita.com/2011/12/19/dont-push-your-pull-requests/)
2. Build.ps1 is working on local and AppVeyor.
3. Follow the code guidelines and conventions.
4. New features are not only code, tests and documentation are also mandatory.
