---
description: "Automatically generated file. DO NOT MODIFY"
---

```javascript

const options = {
	authProvider,
};

const client = Client.init(options);

let listItem = await client.api('/sites/contoso.sharepoint.com,2C712604-1370-44E7-A1F5-426573FDA80A,2D2244C3-251A-49EA-93A8-39E1C3A060FE/lists/22e03ef3-6ef4-424d-a1d3-92a337807c30/items/delta?token=latest')
	.get();

```