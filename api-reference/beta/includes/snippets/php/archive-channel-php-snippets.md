---
description: "Automatically generated file. DO NOT MODIFY"
---

```php

<?php


$graphServiceClient = new GraphServiceClient($tokenRequestContext, $scopes);


$graphServiceClient->teams()->byTeamId('team-id')->channels()->byChannelId('channel-id')->archive()->post()->wait();

```