*** Topics to cover ***
1. ConfigModule from @nestjs/config
2. Versioning in DB Schemas
3. DI in NestJS
   - Why some services we inject as 
   ```@Inject(...) private readonly service```
   and others just like private readonly ...
4. Pino Logger
*** Useful notes ***
NestJS CLI Commands:
### This is going to generate some boilerplate you want
1. nest g resource {name_of_resource} 
2. Containers in docker can talk to each other by the name of the service