
```Javascript

const options = {
	authProvider,
};

const client = Client.init(options);

let res = await client.api('/users/{id|userPrincipalName}/photo')
	.version('beta')
	.delete();

```