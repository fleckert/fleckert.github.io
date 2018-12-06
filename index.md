AzureServiceTokenProvider

```CSharp
var astp = new AzureServiceTokenProvider(connectionString: "RunAs=Developer;DeveloperTool=VisualStudio;")
```

```CSharp
var astp = new AzureServiceTokenProvider(connectionString: $"RunAs=App; TenantId={tenantId}; AppId={clientId}; AppKey={clientSecret}")
```
