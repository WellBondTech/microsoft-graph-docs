
```Javascript

const options = {
	authProvider,
};

const client = Client.init(options);

const Stream = The contents of the file goes here.;

let res = await client.api('/me/drive/items/{item-id}/content')
	.version('beta')
	.put({Stream : Stream});

```