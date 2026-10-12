# <img src="https://raw.githubusercontent.com/i41-eu/.github/main/profile/logo-square.svg" width="40" height="40" alt="" align="absmiddle"> i41

An open-source home platform: local first, privacy first.

i41 runs your robots, devices and apps at home, on your own network. The online part is only a
hub: it helps you set things up and reach them from away, and it cannot read what it carries.
The first device is a Stackchan, a small desk robot (M5Stack's StackChan) with our Embody Mode
firmware: one robot, the body of many apps.

## Websites

- [i41.eu](https://i41.eu): the platform's page.
- [s.i41.eu](https://s.i41.eu): the Stackchan robot and its apps, a page per app, and how to set one up.
- [s.i41.eu/s3d/](https://s.i41.eu/s3d/): the robot in 3D in your browser: its sensors and actuators, and what each app does with them.
- [m.i41.eu](https://m.i41.eu): the manager: one sign-in for all your devices; set a robot up over USB in Chrome, choose its apps, switch them from anywhere.
- [raw.q41.eu](https://raw.q41.eu): Raw data: every sensor and command of your robot in the browser.
- [pet.q41.eu](https://pet.q41.eu): Pet: a Tamagotchi for kids; the pet lives on the server, the robot is its body.
- [focus.q41.eu](https://focus.q41.eu): Focus: a focus timer; the robot is the timer, a phone optional.
- [dev.q41.eu](https://dev.q41.eu): Dev: your robot for your own programs and AI agents (HTTP, MCP).

Each app has an address of its own, so your browser keeps them apart; you sign in to them with
the manager.

## Repositories

### The platform

| Repository | What it is |
| --- | --- |
| [i41eu-arch](https://github.com/i41-eu/i41eu-arch) | The i41 home platform: vision, use cases, principles, architecture, the wire protocol and end-to-end encryption |
| [i41eu-manager](https://github.com/i41-eu/i41eu-manager) | The home manager for Stackchan robots: setup over USB, a live line, apps and a token per robot per app |
| [i41eu-web](https://github.com/i41-eu/i41eu-web) | The page at i41.eu: the i41 home platform, local first, privacy first |
| [i41eu-assets](https://github.com/i41-eu/i41eu-assets) | The Stackchan robot in 3D (robot3d, in Go) and the robot pictures of the i41 home platform |
| [i41eu-s3d](https://github.com/i41-eu/i41eu-s3d) | The Stackchan robot in 3D in the browser (s.i41.eu/s3d/): its sensors and actuators, and what each app does with them |
| [i41eu-StackChan](https://github.com/i41-eu/i41eu-StackChan) | The robot's firmware: M5Stack's StackChan with Embody Mode (a fork of [m5stack/StackChan](https://github.com/m5stack/StackChan), branch `embody`) |
| [i41eu-tpbot-ble](https://github.com/i41-eu/i41eu-tpbot-ble) | BLE control for an ELECFREAKS TPBot car with a micro:bit V2: firmware, a laptop tool, a bridge |

### The apps

| Repository | What it is |
| --- | --- |
| [q41eu-raw](https://github.com/i41-eu/q41eu-raw) | Raw data (raw.q41.eu): a Stackchan robot's every sensor and command in the browser, and the Go packages the i41 apps share |
| [q41eu-pet](https://github.com/i41-eu/q41eu-pet) | Pet: a Tamagotchi for kids on a Stackchan robot; the pet lives on the server, the robot is its body |
| [q41eu-focus](https://github.com/i41-eu/q41eu-focus) | Focus: a focus timer on a Stackchan robot; the robot is the timer, a phone optional |
| [q41eu-dev](https://github.com/i41-eu/q41eu-dev) | Dev: your Stackchan robot for your own programs and AI agents (HTTP, MCP), and a Go kit for robot apps |
| [q41eu-sbot](https://github.com/i41-eu/q41eu-sbot) | sbot: the cockpit for a Stackchan robot and the devices with it (a TPBot car) |

## Status

A proof of concept: written with AI agents and tested at home, not yet reviewed by humans.

Stack-chan was created by Shinya Ishikawa and the Stack-chan community
([github.com/stack-chan/stack-chan](https://github.com/stack-chan/stack-chan)); this project is
independent of it and of M5Stack.
