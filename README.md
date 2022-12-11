# skinet
Drop-Database
Remove-Migration
Add-Migration InitialCreate -outputDir Infrastracture/Data
Update-Database
Add-Migration IdentityInitial -outputDir Identity/Migrations -context AppIdentityDbContext
