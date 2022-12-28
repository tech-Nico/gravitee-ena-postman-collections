# APIM Postman collection

## Why these collections ? 

Gravitee is building a new Event-Native APIM in order to fully support Sync & Async APIs. We've been releasing first capabilities (link to doc) based on the v4 api_definition and management API. With an API first approach, these new capabilities doesn't come yet with a UI so we are sharing these collections in order to help our users discover this new beta capabilities.

## What to discover in these collections ? 

In these collections, you will find : 
- an environment collection : to reference your gateway, M-API, credentials etc..
- an API Management collection : to discover all the new use cases (such as Websocket, SSE, Webhook, Kafka, MQTT5) and how to create APIs (sync & Async) using the new v4 M-API and the nex v4 api_definition.


## How to run these collections ? 

In order to properly run these collections, you'll need 4 variables to be set :
- management_host (ex: http://localhost:8083)
- management_username (ex: admin)
- management_password (ex: xxxxxxxxx )
- gateway_host (ex: http://localhost:8082)

## Can I send feedback to you?

We are always keen to hear from you, especially on the huge topic of event-native API management. Please [contact us](https://www.gravitee.io/contact-us) if you have any feedback!
