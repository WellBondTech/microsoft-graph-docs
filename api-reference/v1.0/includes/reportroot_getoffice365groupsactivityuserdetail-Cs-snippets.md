
```Cs

GraphServiceClient graphClient = new GraphServiceClient( authProvider );

var report = await graphClient.Reports.GetOffice365GroupsActivityDetail('D7')
	.Request()
	.GetAsync();

```