
```Javascript

const options = {
	authProvider,
};

const client = Client.init(options);

let res = await client.api('/domains/contoso.com/domainNameReferences')
	.version('beta')
	.get();

```