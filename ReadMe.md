# Pi-Hole Setup with BalenaCloud

Quick and easy way to manage a fleet of Pi-Hole deployments.

This stack contains:

- [Pi-hole](https://pi-hole.net)
- [Unbound](https://gitlab.com/klutchell/unbound)

## Getting Started

Follow the BalenaCloud getting started [tutorial](https://www.balena.io/docs/learn/getting-started)

## Deployment

Set the following variables at the application level or device level:

- `TZ`
- `WEBPASSWORD`

Set `ServerIP` per device to the static IP that is assigned to the device.

Deploy the code to your BalenaCloud application.
