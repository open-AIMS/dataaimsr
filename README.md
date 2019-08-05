
AIMS DataPlatform R Client
==========================

This R package intends to provide easy access to scientific data provided in the AIMS DataPlatform.

The DataPlatform R Client library can be used like this:

```
library(aimsdataplatform)

client <- dataplatformclient()

dataFrame <- dataplatform(client, '10.25845/5b4eb0f9bb848', filters=list("site-name"="Davies Reef"))

print(dataFrame)

```

This library is provided for use under the Creative Commons by Attribution license [here](https://creativecommons.org/licenses/by/3.0/au/legalcode)

