# dotnet-angular-test-app
Creating an app with angular front end / dotnet backend
# HANDY DOTNET COMMANDS

### Get general SDK info:

 	<code>dotnet —info</code>

### Restore dotnet (when installing or removing packages):

    <code>donet restore</code>

### Run dotnet app:

    <code>donet run</code>

Run dotnet app in dev:

    <code>donet watch run</code>

Find all templates that can be created:

    <code>dotnet new list</code>

Create new template (note -n <name> is not needed and will default to directory name):
	
	<code>dotnet new <template> -n <name></code>

All commands for a specific template:
	
	<code>dotnet <template> -h</code>

All projects connected to a template:

	<code>dotnet <template> list</code>

Clean SSLs for Localhost
<code>
code ~/.aspnet/dev-certs/https
(Delete all of the files in this directory)
sudo dotnet dev-certs https --clean
dotnet dev-certs https --clean
dotnet dev-certs https
dotnet dev-certs https --trust
dotnet dev-certs https --check --trust
</code>