
```Javascript

const options = {
	authProvider,
};

const client = Client.init(options);

let res = await client.api('/users')
	.select('displayName,givenName,postalCode')
	.get();

```