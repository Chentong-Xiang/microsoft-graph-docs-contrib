---
description: "Automatically generated file. DO NOT MODIFY"
---

```php

<?php


$graphServiceClient = new GraphServiceClient($tokenRequestContext, $scopes);


$result = $graphServiceClient->security()->attackSimulation()->trainingCampaigns()->byTrainingCampaignId('trainingCampaign-id')->get()->wait();

```