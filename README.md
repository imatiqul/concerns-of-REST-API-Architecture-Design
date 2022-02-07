# Concerns of REST API Architecture Design
### While designing architecture of REST API, we need to consider following areas
| Areas	| .NET	| Node.js	|
| ----- | ----- | -----	| 
| API	Security	|	JWT Authentication	|	|	 
| API Versioning	|	Microsoft AspNetCore Versioning	| |
| API Validation	|	FluentValidation	|	 |
| API Documentation	|	NSwag	| 	 |
| Using DTOs (Object to Object Mapper)	|	AutoMapper	|	 |
| CORS Policy	|	CORS with named policy and middleware	|	 |
| Health Check	|	Health Checks Middleware and Use watchdogs	|	 |
| Dependency Injection	|	Built-in service container	|	 |
| Logging	|	Opentelemetry.NET	|	 |
| ORM	|	EF Core	|	 |
| CQRS pattern	|	MassTransit or MediatR	|	 |
| JSON Serialization	|	System.Text.Json or Json.NET	|	 |
| Cross-cutting API calls	|	Refit	|	 |
| Handle Errors Globally	| 	Exception Handling Middleware	|	 |
| Keep common code paths fast	|	Middleware components	|	 |
| Caching	|	IDistributedCache interface	|	 |
| Data Protection	|	Data Protection extensions	|	 |
| Avoid blocking calls	|	Asynchronous APIs	|	|
| Complete long-running Tasks outside of HTTP requests	|	Job Scheduler (like Hangfire/Quartz.NET/SignalR/etc.)	|	|



