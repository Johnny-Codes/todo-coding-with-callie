[Microsoft Tutorial](https://learn.microsoft.com/en-us/aspnet/core/tutorials/first-web-api?view=aspnetcore-8.0&tabs=visual-studio-code)

run: `dotnet run --launch-profile https`

scaffold a controller. creates the controller with all 5 api end points (2x get, put, post, delete):

```csharp
dotnet aspnet-codegenerator controller -name <TodoItemsController> -async -api -m <TodoItem> -dc <TodoContext> -outDir Controllers
```

**Steps to adding a new Model:**

- Create Model Class
- Add Database Context
- Register the Database Context (in Program.cs)
