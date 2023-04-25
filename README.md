# .NET Angular Test Apps
Example apps with Angular front end / .NET backend
# HANDY .NET COMMANDS

### Get general SDK info:

 	dotnet —info

### Restore .NET (when installing or removing packages):

    donet restore

### Run .NET app:

    donet run

Run .NET app in dev:

    donet watch run

Find all templates that can be created:

    dotnet new list

Create new template (note -n <name> is not needed and will default to directory name):
	
	dotnet new <template> -n <name>

All commands for a specific template:
	
	dotnet <template> -h

All projects connected to a template:

	dotnet <template> list

Clean SSLs for Localhost

	code ~/.aspnet/dev-certs/https
    // (Delete all of the files in this directory)
	sudo dotnet dev-certs https --clean
	dotnet dev-certs https --clean
	dotnet dev-certs https
	dotnet dev-certs https --trust
	dotnet dev-certs https --check --trust
