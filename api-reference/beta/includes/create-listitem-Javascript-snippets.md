
```Javascript

const options = {
	authProvider,
};

const client = Client.init(options);

const fieldValueSet = {
    Color: "Fuchsia",
    Quantity: 934
};

let res = await client.api('/sites/{site-id}/lists/{list-id}/items/{item-id}/fields')
	.version('beta')
	.update({fieldValueSet : fieldValueSet});

```