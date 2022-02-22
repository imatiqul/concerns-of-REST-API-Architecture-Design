# Concerns of REST API Architecture Design
### While designing architecture of REST API, we need to consider following areas
| Areas	| Node.js	| .NET	|
| ----- | ----- | -----	| 
| API	Security	|	Nestjs JwtModule	|	 JWT Authentication	| 
| API Versioning	|	Nestjs URL Versioning | Microsoft AspNetCore Versioning	| 
| API Validation	|	Nestjs ValidationPipe | FluentValidation	|	
| API Documentation	|	Nestjs OpenApi | NSwag	|
| Using DTOs (Object to Object Mapper)	|		TypeORM | AutoMapper	|
| CORS Policy	|	Nestjs CORS | CORS with named policy and middleware	|
| Health Check	|	Healthchecks (Terminus) |	Health Checks Middleware and Use watchdogs	|
| Dependency Injection	|	Built-in DI | Built-in service container	|
| Logging	| Nestjs-OpenTelemetry |	Opentelemetry.NET	|
| ORM	|	TypeORM |	EF Core	|
| CQRS pattern	|	 Nestjs CQRS | MassTransit or MediatR	|
| JSON Serialization	|	class-transformer |	System.Text.Json or Json.NET	|
| Cross-cutting API calls	|	Nestjs ClientProxy |	Refit	|
| Handle Errors Globally	|	useGlobalFilters |	Exception Handling Middleware	|
| Keep common code paths fast	|	Middleware |	Middleware components	|
| Caching	|	Nestjs Caching |	IDistributedCache interface	|
| Data Protection	|	Nestjs Security |	Data Protection extensions	|
| Avoid blocking calls	| Asynchronous providers	|	Asynchronous APIs	|
| Complete long-running Tasks outside of HTTP requests	| Nestjs Schedule	|	Job Scheduler (like Hangfire/Quartz.NET/SignalR/etc.)	|



