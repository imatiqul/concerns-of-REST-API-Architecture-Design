# Concerns of REST API Architecture Design
### While designing architecture of REST API, we need to consider following areas
| Areas	| .NET	| Node.js	|
| ----- | ----- | -----	| 
| API	Security	|	JWT Authentication	| Nestjs JwtModule	|	 
| API Versioning	|	Microsoft AspNetCore Versioning	| Nestjs URL Versioning |
| API Validation	|	FluentValidation	|	Nestjs ValidationPipe |
| API Documentation	|	NSwag	| Nestjs OpenApi |
| Using DTOs (Object to Object Mapper)	|	AutoMapper	|	TypeORM |
| CORS Policy	|	CORS with named policy and middleware	|	Nestjs CORS |
| Health Check	|	Health Checks Middleware and Use watchdogs	|	Healthchecks (Terminus) |
| Dependency Injection	|	Built-in service container	|	Built-in DI |
| Logging	|	Opentelemetry.NET	| Nestjs-OpenTelemetry	 |
| ORM	|	EF Core	|	TypeORM |
| CQRS pattern	|	MassTransit or MediatR	| Nestjs CQRS	 |
| JSON Serialization	|	System.Text.Json or Json.NET	|	class-transformer |
| Cross-cutting API calls	|	Refit	|	Nestjs ClientProxy |
| Handle Errors Globally	| 	Exception Handling Middleware	|	useGlobalFilters |
| Keep common code paths fast	|	Middleware components	|	Middleware |
| Caching	|	IDistributedCache interface	|	Nestjs Caching |
| Data Protection	|	Data Protection extensions	|	Nestjs Security |
| Avoid blocking calls	|	Asynchronous APIs	| Asynchronous providers	|
| Complete long-running Tasks outside of HTTP requests	|	Job Scheduler (like Hangfire/Quartz.NET/SignalR/etc.)	| Nestjs Schedule	|



