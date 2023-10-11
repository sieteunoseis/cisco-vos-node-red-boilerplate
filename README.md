# Node-Red Cisco VOS Boilerplate

Simple boilerplate to get you up and running on Node-Red via Docker with the Cisco VOS packages included.

Node-Red information can be found at [nodered.org](https://nodered.org/).

Included packages:

 - [Cisco AXL](https://www.npmjs.com/package/cisco-axl)
 - [Cisco Perfmon](https://www.npmjs.com/package/cisco-perfmon)
 - [Cisco Risport](https://www.npmjs.com/package/cisco-risport)
 - [Cisco DIME](https://www.npmjs.com/package/cisco-dime)
 - [FlowFuse Dashboard 2.0](https://github.com/FlowFuse/node-red-dashboard)

## Installation

Using Docker Compose:

```
git clone https://github.com/sieteunoseis/cisco-vos-nodered-bolierplate.git
cd cisco-vos-nodered-bolierplate
docker-compose up -d
```

Access Node-Red at http://localhost:1880, once up and running.

## Notes 

Using Node version 18. This includes the Fetch function which is required for the Cisco VOS packages.

## Giving Back

If you would like to support my work and the time I put in creating the code, you can click the image below to get me a coffee. I would really appreciate it (but is not required).

<a href="https://www.buymeacoffee.com/automatebldrs" target="_blank"><img src="https://cdn.buymeacoffee.com/buttons/default-orange.png" alt="Buy Me A Coffee" height="41" width="174"></a>