# Lelylan. Open Source Internet of Things

Lelylan is an iot cloud platform based on a lightweight microservices architecture.

Lelylan platform is both hardware-agnostic and platform-agnostic. This means you can connect any hardware, from the ESP8622 to the most professional embedded hardware solution and everything in between - and it can run on any public cloud or in your own private datacenter, or even a hybrid environment, whether virtualized or on bare metal.

[![Lelylan Logo](https://raw.githubusercontent.com/lelylan/lelylan/master/public/logo-lelylan.png)](http://lelylan.com)

### Why Lelylan

Research in the Internet of Things is global and growing fast, but lacks standard tools. Many companies are building their own solution. By sharing what we have learned during the years, we want to create a shared code base for the Internet of Things. To see Lelylan in action checkout the [tuturials](http://dev.lelylan.com/#overview-tutorials) in the dev center. 

### Resources

* [Architecture](http://dev.lelylan.com/architecture) (request life cycle)
* [Internet of Things API](http://dev.lelylan.com/api) (how it works)
* [Blog](http://lelylan.com) (latest from the community)



# Getting Started

### Requirements

Lelylan is tested against

* Ruby MRI ~1.9.3
* Node ~0.8.8
* MongoDB ~2.6
* Redis ~2.6


## Setup

* [Install MongoDB](https://docs.mongodb.org/manual/installation/)
* [Install Redis](http://redis.io/download)


## Installation

Lelylan is composed by different microservices and each of them needs to be up and running to run the Lelylan platform.
Clone and follow the detailed installation guidelines for the repositories below.

| Microservice  | Descripotion |
| ------------- | ------------- |
| [Devices API](https://github.com/lelylan/devices)  | Device monitoring and control |
| [Types API](https://github.com/lelylan/types) | Device type structure |
| [Subscriptions API](https://github.com/lelylan/subscriptions) | Realtime subscription |
| [Profiles API](https://github.com/lelylan/profiles) | Profile information |
| [OAuth 2.0](https://github.com/lelylan/people) | User authentication and authorization  |
| [Physical Proxy](https://github.com/lelylan/physicals) | Forward requests to the physical world |
| [MQTT Node](https://github.com/lelylan/nodes) | Forward and receive MQTT requests |
| [MQTT Server](https://github.com/lelylan/mqtt) | Realtime HTTP notification |
| [Webhooks](https://github.com/lelylan/webhooks) | MQTT server/broker |
| [Websockets](https://github.com/lelylan/websockets) | Full-duplex communication over TCP |
| [API Proxy](https://github.com/lelylan/api-proxy) | Proxy API |

Your [API]((http://dev.lelylan.com/api)) is now accessible at the address `http://localhost:3000`.


## Deployment

We are studying solutions like Docker, Mesos, and Ansible to simplify the installation process. If you are experimenting in the same area get in touch with [lelylan team](http://dev.lelylan.com/api).


## Roadmap

Checkout the [roadmap](/ROADMAP.md) to see our near future goals.


## Contributing to Lelylan

If you want to contribute and hack on Lelylan we have [instructions](/CONTRIBUTING.md) to help you get started.


## Support

Use the available [communication channels](http://dev.lelylan.com/support) to communicate your ideas, problems or suggestions.


## License

Lelylan is licensed under the [Apache License, Version 2.0](http://www.apache.org/licenses/LICENSE-2.0).


