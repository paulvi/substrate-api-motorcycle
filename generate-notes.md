

--package-name generated8 \
Has no effect

--invoker-package bcd.polkadot.motocycle.client \
--api-package bcd.polkadot.motocycle.api \
--model-package bcd.polkadot.motocycle.model \
Defaults are 
org.openapitools.client
org.openapitools.client.api
org.openapitools.client.model
That is api and model under client, but these 2 are actually shared by server and client, 
besides subpackage `client.auth` should not be on the same level as `api` and `model`.
In the end, exact import path is not exactly visible within Java class, 
just import statement above, that should be consistent and hint to how to find project.
