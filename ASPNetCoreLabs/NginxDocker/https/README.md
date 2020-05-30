# Create SSL Certificate

[document](https://docs.microsoft.com/en-us/aspnet/core/security/docker-compose-https)

## Windows using Linux containers

Generate certificate and configure local machine:

```bash
# in the current folder
dotnet dev-certs https -ep aspnetapp.pfx -p mypassword123
dotnet dev-certs https --trust
```