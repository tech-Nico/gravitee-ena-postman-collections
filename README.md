# APIM Postman collection

## Why these collections? 

Gravitee is building a new event-native APIM that fully supports both synchronous and asynchronous APIs. There is a [beta release based on the v4 API definition and management API](http://docs.gravitee.io/apim/3.x/event_native_apim_introduction.html). There isn't yet a GUI, so we are sharing these collections in order to help you discover the new functionality.

## What is in these collections? 

In these collections, you will find : 
- an environment collection: to reference your gateway, management API, credentials, etc.
- an API Management collection : to discover all the new use cases (such as Websocket, SSE, Webhook, Kafka, MQTT5) and how to create APIs (sync & Async) using the new v4 M-API and the nex v4 api_definition.


## How do I run these collections? 

In order to properly run these collections, you will need to set 4 variables:
- management_host (ex: http://localhost:8083)
- management_username (ex: admin)
- management_password (ex: xxxxxxxxx )
- gateway_host (ex: http://localhost:8082)

## Can I send feedback to you?

We are always keen to hear from you, especially on the huge topic of event-native API management. Please [contact us](https://www.gravitee.io/contact-us) if you have any feedback!
