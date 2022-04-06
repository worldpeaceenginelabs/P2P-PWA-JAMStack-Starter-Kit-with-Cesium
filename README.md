# COMMUNITY CHALLENGE
#### Does this repository sound like a dream to you?
You can make this dream come true.

Help us coding to get the Starter Kit to the community of developers out there ASAP.

This project is just some adapters away from reality.
<br><br>

### 1. Code more arms (Dencentralize adapters)
Developer friendly API coming (see further down)
<br><br><br>

# True P2P with Decentralize (status: see issues section)

#### A community-driven P2P-PWA-JAMStack Starter Kit with Cesium and Decentralize for your next decentralized/serverless, location-based project (p2p website, app ,client, server, api)
#### Decentralize brings all decentralized networks together...
Use the Starterkit for your already existing, yet centralized projects or start a new project, serverless right from the start.
<br><br><br>

## [Lets redecentralize the web](https://redecentralize.org/) - The Revolution Will Not Be Televised

If you ever thought about how the Evernet will look. It seems like, it is an ever-fallback-net.

[Decentralize](https://github.com/draeder/decentralize) is the result of a really cool, days long conversation of Dreader and me.

He had already something similar in mind for some time, so great we found each other.

My special thanks to him for sharing his whole decentralization experience into a yet simple concept.
<br><br><br>

![image](https://user-images.githubusercontent.com/67427045/160407233-aa734253-8616-48f1-ad91-7264183039f4.png)
<br><br><br>

# How to add arms?
Developer friendly API that can enable anyone to easily create Decentralize adapters for other p2p tech is on its way!

Stay tuned on the original repository [Decentralize](https://github.com/draeder/decentralize) 

# Which arms are working already?
- GUN
- Hyperswarm-Web
- Bugout
<br><br><br>

# Decentralize
Transmit messages between peers regardless of underlying decentralization technology they are connected with.

Decentralize aims to provide a simple API for rapid development of adapters that can integrate disparate p2p stacks with each other. Most decentralization stacks have things in common. They all emit and listen for events. Many announce a 'topic' or some kind of swarm identifier. Some have end-to-end security built in, some don't.

Decentralize accepts a custom initialization function and corresponding desired methods object for each stack. Then, it lets developers map the APIs together and does the work to relay data between stacks automatically.

![image](https://user-images.githubusercontent.com/67427045/161437648-40c15259-3a41-4218-8cdf-47fa21253b50.png)

# True P2P CLIENT CONCEPT
This is a high level abstraction of a true P2P client, which is basically your existing or next website/app and [Decentralize](https://github.com/draeder/decentralize) with all the listed adapters installed.

![image](https://user-images.githubusercontent.com/67427045/160401140-db2439e0-f7b4-45a4-9679-7cffffc4ba48.png)
<br><br><br>

# Offline capabilities out of the box
### Just by adding manifest.json - There are presets (serviceworker) for different offline behaviours, which you are able to combine for your needs.
Use [PWA Builder](https://www.pwabuilder.com/) for your PWA to get ready customized scripts with a mouseclick.
![image](https://user-images.githubusercontent.com/67427045/160479929-9ce46d89-eca9-4caa-8227-bbf1c931d502.png)

A Progressive Web App is a website which runs like a full installed application on any browser ergo any device, can be installed like an app, and is able to get uploaded to all three stores.

If your domain is offline, your website/app/client/server/api is still running on your users device. Like an installed PC application, what makes it kind of decentralized already. 

Why PWA? Deep insight into the realm of PWA - The future of the internet and apps
Progressive Web Apps - PWA Roadshow: https://youtu.be/z2JgN6Ae-Bo
<br><br><br>

# What is JAMStack? https://jamstack.wtf
short: static HTML, javascript, hydrated with API

# Front-End Deployment (static HTML, javascript, hydrated with API)

Use whatever you want!!! Works for every of your favorite stacks.

#### For instance
- [Lit](https://lit.dev/) -npm i lit (web components, future-ready)
- Svelte -npm install svelte
- React -npm install create-react-app

#### Free hosting and 1.8ms global responsetime via CDN network included
Simply store your website/app/client/server/api sourcecodes on Github. Github serves to Cloudflare Pages ultra fast CDN's. Lightspeed fast, the lowest vulnerabilities, easy to maintain, for zero cost.

JAMStack Rocks!!!

# Back-end Deployment (P2P Graph, Database, API, Auth, etc.)

Just by intregrating this repository in your website/app as soon as its finished.

-npm install p2p-pwa-jamstack-starter-kit-with-cesium (coming)

Extend the capabilities by adding arms (Decentralize adapter) and storage adapters.
There are for instance Gun storage adapters available at https://gun.eco/docs/Awesome-GUN making your app run with your yet centralized stack, for instance MongoDB.

# Signaling
The more arms (adapter) get added by the community, the more direct signaling options and decentralized and centralized fallbacks will come into play automatically.

A settingsfile will handle priorities, timeouts and if-then-else conditions between strategies for finetuning your swarm/swarms.
<br><br>

A huge, free signaling infrastructure is coming up from Cloudflare.
Stay tuned on their blog https://blog.cloudflare.com/announcing-our-real-time-communications-platform/

<br><br><br>

# My definition of True P2P
"A swarm of P2P clients, independent of any dedicated servers, not even dedicated signaling servers" (but using everything available is allowed, like nanites would do)

or different said: "Todays systems are centralized instances, connecting peers. This will not change, but as soon as the swarm is online, centralized instances are becoming the fallback only. Thats the difference!"

"Kind of, in the past we used candles only. Today, we only use candles, when the light is off, to find the switch in the dark, to get the light back on. So candles are still neccessary, but we do not depend on them anymore." (candles are not even neccessary anymore, we have flashlights and bright mobile screens today, but we were only able to figure this technologies out, because we were not sticking to candles anymore)

# The goals
To provide you with a P2P-PWA JAM template (P2P-PWA JAM? 😅 which could be the next standard stack for decentralized webapps maybe?) for your next decentralized/serverless project (p2p website/app/client/server/api)

The technical goal is to connect peers through multiple protocols, no matter what.
At the end, its just all about reconnecting.

These beasts (clients) pretty much crawling their options for connections.

### The finish will be a set of adapters in a priority list with timeout and if-then-else conditions.
Which keeps it super simple, but highly customizable.

1. direct connection via WebRTC
2. if that doesnt work, reconnect via Gun
3. if that doesnt work, reconnect via Bugout
4. if that doesnt work, reconnect via Bittorrent/Webtorrent
5. if that doesnt work, reconnect via IPFS
6. if that doesnt work, reconnect via Hypercore Protocol
7. if that doesnt work, reconnect via Hyperswarm
8. if that doesnt work, reconnect via AXE
9. if that doesnt work, reconnect via updated lists of free stun and turn servers
10. if that doesnt work, reconnect via DHT lists, saved everywhere its possible (websites, blogs, github, social media, forums, etc.), without stressing free tiers
11. if that doesnt work, reconnect via DYNDNS
12. if that doesnt work, reconnect via AD HOC (same LAN, same WIFI, Bluetooth, Direct Wifi, QR-Code) https://berty.tech/blog/bluetooth-low-energy/
13. if that doesnt work, reconnect via Instant Message from a friend who uses the app too.
14. if that doesnt work, reconnect via free hosted website with updated DHT list (last Fallback)
<br><br><br>

# Paving the way to True P2P
My goal is independent or minimum quasi independant P2P.

Which means, not dependant on one single network infrastructure, not my own, not a foreign one, but allowed to use every chance to connect as a fallback to reconnect. 

In turn using different, already existing network infrastructures as needed.
Because at the end of the day, we want the connection to the swarm, to update our DHT tracker list/peertracker list/peer list, to STAY connected)
