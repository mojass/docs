---
title: Production enviroment
description: When you are ready for production please us the following steps to get access
weight: 25
---

1. **Apply for access to the Sdir API production scopes**<br>
Send a email to apsinfo@sdir.no and request access to the Sdir API production scope.
2. **Maskinport intergration**<br>
Create Maskinport intergration for production in the [Samarbeidsportalen](https://samarbeid.digdir.no/) to the Sdir API scopes. Take a note of the integration id.
1. **API subscription**<br>
Sign up for the [production enviroment](https://api.developer.sdir.no/signin) and the select the product (API endpoints) you what to subscribe for. 
Take a note of the subscripton key, which is needed in the HTTP requests.


{{% panel %}}
**Settings** <br><br>

*API url*:https://api.sdir.no<br>
*ClientId*:[your production integration id]<br>
*MaskinportenBaseAddress*:https://maskinporten.no/<br>
{{% /panel %}}
