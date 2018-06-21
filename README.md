[![Deploy](https://cdn.wedeploy.com/images/deploy.svg)](https://console.wedeploy.com/deploy?repo=https://github.com/wedeploy-examples/react-example)

# Rabbitmq

An example of [Rabbitmq](https://www.rabbitmq.com/) and [Nginx](https://www.nginx.com/) on [WeDeploy](https://wedeploy.com/).

## Instructions

1. Install the [WeDeploy CLI](https://wedeploy.com/docs/intro/using-the-command-line/).
2. Clone this repository.
3. Open the project with your command line and run `we deploy -p yourproject`.

## Note

All requests made to `/management/` will be passed to the [Rabbitmq Management Plugin](https://www.rabbitmq.com/management.html). Any other request will be passed to the queue port.

## License

[BSD-3-Clause](./LICENSE.md), © Liferay, Inc.
