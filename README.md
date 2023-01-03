# skinet
sve se radi na projektu Infrastucture
Drop-Database
Remove-Migration
Add-Migration InitialCreate -outputDir Infrastracture/Data
Update-Database
Add-Migration IdentityInitial -outputDir Identity/Migrations -context AppIdentityDbContext
Add-Migration InitialCreate -outputDir Data/Migrations -context StoreContext
