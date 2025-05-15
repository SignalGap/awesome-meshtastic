# Awesome Meshtastic List [![Awesome List Badge](./media/awesome-list-badge.svg)](https://awesome.re)

![Awesome Meshtastic List Logo](media/awesome-meshtastic-list-logo.svg)

This is a curated list of useful resources, tools, tutorials, projects, and community contributions related to the Meshtastic open-source mesh communication project. Whether you're a beginner or advanced user, this list helps you explore and get the most out of your Meshtastic devices.

## Table of Contents

- [Official Source Code Repositories](#official-source-code-repositories)
  - [Core Repositories](#core-repositories)
  - [Mobile, Web and Desktop Clients](#mobile-web-and-desktop-clients)
  - [Device Interaction and Integrations](#device-interaction-and-integrations)
  - [Tools & Utilities](#tools--utilities)
  - [Hardware and Sensors](#hardware-and-sensors)
- [Applications](#applications)
  - [Official Apps](#official-apps)
  - [Community Apps](#community-apps)
- [Hardware Stores](#hardware-stores)
- [Software Projects](#software-projects)
- [Hardware Projects](#hardware-projects)
  - [Solar Powered Hardware Projects](#solar-powered-hardware-projects)
  - [Fun Hardware Projects](#fun-hardware-projects)
  - [Inspiring Hardware Projects](#inspiring-hardware-projects)
- [Communities](#communities)
  - [Official Community](#official-community)
  - [Unofficial Communities](#unofficial-communities)
- [Local Groups](#local-groups)
  - 🇦🇷 [Argentina](#argentina)
  - 🇦🇺 [Australia](#australia)
  - 🇧🇷 [Brazil](#brazil)
  - 🇧🇬 [Bulgaria](#bulgaria)
  - 🇨🇦 [Canada](#canada)
  - 🇨🇳 [China](#china)
  - 🇨🇴 [Colombia](#colombia)
  - 🇩🇰 [Denmark](#denmark)
  - 🇫🇮 [Finland](#finland)
  - 🇫🇷 [France](#france)
  - 🇩🇪 [Germany](#germany)
  - 🇮🇳 [India](#india)
  - 🇮🇱 [Israel](#israel)
  - 🇮🇹 [Italy](#italy)
  - 🇯🇵 [Japan](#japan)
  - 🇱🇻 [Latvia](#latvia)
  - 🇱🇹 [Lithuania](#lithuania)
  - 🇲🇽 [Mexico](#mexico)
  - 🇳🇱 [Netherlands](#netherlands)
  - 🇳🇿 [New Zealand](#new-zealand)
  - 🇵🇱 [Poland](#poland)
  - 🇸🇮 [Slovenia](#slovenia)
  - 🇿🇦 [South Africa](#south-africa)
  - 🇪🇸 [Spain](#spain)
  - 🇸🇪 [Sweden](#sweden)
  - 🇹🇼 [Taiwan](#taiwan)
  - 🇹🇷 [Türkiye](#türkiye)
  - 🇺🇦 [Ukraine](#ukraine)
  - 🇬🇧 [United Kingdom](#united-kingdom)
  - 🇺🇸 [United States](#united-states)
- [Contribute](#contribute)
- [Legal Notice](#legal-notice)
- [License](#license)

## Official Source Code Repositories

### Core Repositories

These repositories are at the heart of the Meshtastic project, containing firmware, APIs, and other essential code.

- [firmware](https://github.com/meshtastic/firmware) - Meshtastic device firmware
- [protobufs](https://github.com/meshtastic/protobufs) - Protobuf definitions for Meshtastic
- [web-flasher](https://github.com/meshtastic/web-flasher) - Online flasher for Meshtastic device firmware
- [meshtastic](https://github.com/meshtastic/meshtastic) - Meshtastic project website and documentation
- [api](https://github.com/meshtastic/api) - Meshtastic Website API

⇡ [<sub><sup>Table of Contents</sup></sub>](#table-of-contents)

### Mobile, Web and Desktop Clients

These repositories offer various client applications for different platforms.

- [web](https://github.com/meshtastic/web) - Meshtastic Web Client
- [Meshtastic-Apple](https://github.com/meshtastic/Meshtastic-Apple) - iOS, iPadOS & macOS Clients for Meshtastic
- [Meshtastic-Android](https://github.com/meshtastic/Meshtastic-Android) - Android app for Meshtastic
- [network-management-client](https://github.com/meshtastic/network-management-client) - Desktop client for offline deployment and mesh network management

⇡ [<sub><sup>Table of Contents</sup></sub>](#table-of-contents)

### Device Interaction and Integrations

Repositories related to firmware, device configuration, interactions and integrations

- [home-assistant](https://github.com/meshtastic/home-assistant) - Home Assistant integration for Meshtastic
- [python](https://github.com/meshtastic/python) - Python CLI and API for interacting with Meshtastic devices
- [node-red-contrib-meshtastic](https://github.com/meshtastic/node-red-contrib-meshtastic) - Node-RED integration for Meshtastic
- [Meshtastic-arduino](https://github.com/meshtastic/Meshtastic-arduino) - Arduino drivers for interfacing with Meshtastic nodes over WiFi and Serial
- [firmware-ota-wifi](https://github.com/meshtastic/firmware-ota-wifi) - WiFi-based OTA (Over The Air) firmware updates for Meshtastic devices
- [nrf52_factory_erase](https://github.com/meshtastic/nrf52_factory_erase) - Firmware for factory erasing the nRF52 chips used in Meshtastic devices
- [firmware-ota](https://github.com/meshtastic/firmware-ota) - BLE-OTA Mini firmware for Meshtastic devices
- [rust](https://github.com/meshtastic/rust) - A Rust library for interacting with Meshtastic radios
- [c-sharp](https://github.com/meshtastic/c-sharp) - C#/.NET command-line interface and library for Meshtastic

⇡ [<sub><sup>Table of Contents</sup></sub>](#table-of-contents)

### Tools & Utilities

For managing, simulating, and testing Meshtastic networks and devices.

- [meshtasticator](https://github.com/meshtastic/meshtasticator) - Simulator for Meshtastic, supporting discrete-event and interactive simulations
- [meshTestic](https://github.com/meshtastic/meshTestic) - End-to-end test suite for Meshtastic devices
- [meshtastic-site-planner](https://github.com/meshtastic/meshtastic-site-planner) - Site planning tool based on RF analysis using SPLAT! software
- [mqtt](https://github.com/meshtastic/mqtt) - MQTT broker boilerplate designed for Meshtastic’s native packet-aware MQTT support
- [RadioHead](https://github.com/meshtastic/RadioHead) - A fork of the RadioHead library, with custom fixes for Meshtastic devices

⇡ [<sub><sup>Table of Contents</sup></sub>](#table-of-contents)

### Hardware and Sensors

Repos related to the hardware components and sensor integration for Meshtastic.

- [antenna-reports](https://github.com/meshtastic/antenna-reports) - Community-contributed antenna testing reports and evaluations for Meshtastic devices
- [enclosures](https://github.com/meshtastic/enclosures) - 3D models for enclosures used in Meshtastic devices
- [i2c-sensor](https://github.com/meshtastic/i2c-sensor) - Arduino boilerplate for creating custom I2C sensors for Meshtastic
- [ETHClass2](https://github.com/meshtastic/ETHClass2) - Provides ETHClass2 integration for Meshtastic, originally from LilyGO T-ETH series

⇡ [<sub><sup>Table of Contents</sup></sub>](#table-of-contents)

## Applications

⇡ [<sub><sup>Table of Contents</sup></sub>](#table-of-contents)

### Official Apps

 Official **Android** application allows you to connect to your Meshtastic device from your Apple tablet and phone via Bluetooth, Wi-Fi (if on the same network) or USB On-The-Go (OTG).

- [Official Android App on Google Play](https://play.google.com/store/apps/details?id=com.geeksville.mesh)
- [Official Android App on F-Droid](https://f-droid.org/packages/com.geeksville.mesh/)
- [Official Android App Sideloading via Github](https://github.com/meshtastic/Meshtastic-Android/releases/latest)

Official **MacOS, iPhone, and iPad** application allows you to connect to your Meshtastic device from your Apple desktop, laptop, tablet and phone via Bluetooth, Wi-Fi (if on the same network) or USB On-The-Go (OTG).

- [Official iOS and MacOS App on Apple App Store](https://apps.apple.com/us/app/meshtastic/id1586432531)

Official **Web Client** is a browser-based interface that allows users to manage and configure their Meshtastic devices, offering functionalities such as messaging, device settings, and location tracking, all without the need for a mobile app.

- [Official hosted version](https://client.meshtastic.org)
- [Served directly from an ESP32 based node](http://meshtastic.local)
- [The source code for the Web client](https://github.com/meshtastic/web)

⇡ [<sub><sup>Table of Contents</sup></sub>](#table-of-contents)

### Community Apps

**Mesh-Tac-Toe** is the world's first Tic-Tac-Toe game designed for the open Meshtastic network.

- [Mesh-Tac-Toe on Google Play](https://play.google.com/store/apps/details?id=com.specfive.meshtactoe)

**CheckTastic** is a checkers game designed for the open Meshtastic network, showcasing how low-bandwidth, long-range LoRa technology can enable multiplayer gaming beyond traditional messaging.

- [CheckTastic on Google Play](https://play.google.com/store/apps/details?id=com.specfive.checkers)

**MeshChess** is a chess game designed for the open Meshtastic network, utilizing low-bandwidth, long-range LoRa technology to enable off-grid multiplayer gameplay.

- [MeshChess on Google Play](https://play.google.com/store/apps/details?id=com.specfive.chess)

⇡ [<sub><sup>Table of Contents</sup></sub>](#table-of-contents)

## Hardware Stores

Reputable stores known for offering high-quality hardware, organized alphabetically.

- [AT Labs](https://at-labs.tech) - <sub><sup>(Jonesborough, Tennessee, USA)</sup></sub> Specializes in developing rugged Mobile Ad Hoc Network (MANET) radios, including their flagship RM-1 series, designed for resilient off-grid communication.

- [B&Q Consulting](https://shop.uniteng.com) - <sub><sup>(Shenzhen, Guangdong, China)</sup></sub> Personal R&D lab and documentation hub by Neil Hao, focusing on embedded systems, RF design, and open-source hardware projects like Meshtastic mesh devices and smart home technologies.

- [Canary Radio](https://canaryradio.io) - <sub><sup>(Portland, Oregon, USA)</sup></sub> Specializes in rugged, ready-to-use Meshtastic-compatible communication devices like the CanaryOne, designed for reliable off-grid networking in austere environments.

- [HELTEC®](https://heltec.org) - <sub><sup>(Wan Chai, Hong Kong SAR, China)</sup></sub> Specializes in designing and manufacturing IoT hardware solutions, including LoRa, LoRaWAN, and Wi-Fi HaLow devices, catering to both makers and industrial automation sectors with products like development boards, gateways, and sensors.

- [LILYGO®](https://lilygo.cc) - <sub><sup>(Shenzhen, Guangdong, China)</sup></sub> Specializes in the development, manufacturing, and distribution of IoT (Internet of Things) products.

- [RAK®](https://store.rakwireless.com) - <sub><sup>(Wan Chai, Hong Kong SAR, China)</sup></sub> Specializing in modular, easy-to-deploy hardware and software for Mestastic, LoRaWAN®, 5G, and edge computing applications. 

- [Rokland Technologies](https://store.rokland.com) - <sub><sup>(Gainesville, Florida, USA)</sup></sub> Specializes in Meshtastic, LoRaWAN, Wi-Fi, and 4G/5G solutions, and is North America's largest authorized distributor for ALFA Network and RAKwireless products. 

- [Seeed Studio®](https://www.seeedstudio.com) - <sub><sup>(Shenzhen, Guangdong, China)</sup></sub> Specializes in IoT hardware, open-source modules, edge computing devices, and agile manufacturing services

- [Spec<sup>5</sup>](https://specfive.com) - <sub><sup>(Florence, Texas, USA)</sup></sub> Specializes in advanced off-grid communication solutions, offering Meshtastic-enabled devices and mesh networking tools

- [Yeti Wurks](https://www.yetiwurks.com) - <sub><sup>(Blaine, Minnesota, USA)</sup></sub> Specializes in custom firearm accessories for platforms like the CZ Scorpion Evo III, and has recently expanded into off-grid communication solutions with Meshtastic-compatible devices.

⇡ [<sub><sup>Table of Contents</sup></sub>](#table-of-contents)

## Software Projects

- [How to Visualize Meshtastic Telemetry on Grafana](https://hackaday.io/project/202156-how-to-visualize-meshtastic-telemetry-on-grafana) - Integrates Meshtastic telemetry data with Grafana through Telemetry Harbor, enabling real-time visualization and analysis of device metrics and location data.

- [MultiMesh](https://github.com/paulocode/multimesh) - The source code for a cross-platform Meshtastic mobile app for iOS and Android, built using Flutter.

- [MeshLink (Beta)](https://github.com/Murturtle/MeshLinkBeta) - A Python-based tool that bridges Meshtastic and Discord, offering messaging, mesh data sharing, and plugin-driven mesh-only features like weather, ping, and HF condition checks.

⇡ [<sub><sup>Table of Contents</sup></sub>](#table-of-contents)

## Hardware Projects

- [A Major Solution to a Miner Problem](https://meshtastic.org/blog/a-major-solution-to-a-miner-problem/) - How to repurpose an unused LoRa-based cryptocurrency mining device into functional Meshtastic node.

⇡ [<sub><sup>Table of Contents</sup></sub>](#table-of-contents)

### Solar Powered Hardware Projects

- [Harbor Breeze Mesh Node Hack](https://hackaday.io/project/194509-harbor-breeze-mesh-node-hack) - Repurposes a $15 Harbor Breeze solar LED light as a waterproof enclosure to create a solar-powered, weatherproof Meshtastic LoRa node using a WisBlock-based development board.

- [Meshtastic or Helium Ultrasonic WX Station](https://hackaday.io/project/196990-meshtastic-or-helium-ultrasonic-wx-station) - Transforms the Ecowitt WS85 weather station into a Meshtastic-enabled device by modifying its hardware to output serial data, enabling it to transmit weather telemetry over a LoRa mesh network.

- [Meshtastic Solar Buoy](https://www.instructables.com/Meshtastic-Solar-Buoy/) - Converts a waterproof solar fishing buoy lamp into a rugged, solar-powered Meshtastic node for long-range mesh communication.

### Fun Hardware Projects

- [MeshTIEstick: The Wearable LoRa Meshtastic Node](https://www.youtube.com/watch?v=2Wf6BcZS3AY) - Turning a necktie into a fully functional mesh node.

⇡ [<sub><sup>Table of Contents</sup></sub>](#table-of-contents)

### Inspiring Hardware Projects

These aren't directly related to Meshtastic but may inspire you.

- [ARMAWATCH & ARMACHAT - long range radio messengers](https://hackaday.io/project/171790-armawatch-armachat-long-range-radio-messengers) - Long-range radio communicator featuring a QWERTY keyboard, LoRa connectivity, and a color display, designed for off-grid messaging and disaster resilience.

⇡ [<sub><sup>Table of Contents</sup></sub>](#table-of-contents)

## Communities

⇡ [<sub><sup>Table of Contents</sup></sub>](#table-of-contents)

### Official Community

- [Official Discord Server](https://discord.com/invite/ktMAKGBnBs)
- [Official Github Discussions](https://github.com/orgs/meshtastic/discussions)
- [Official Subreddit](https://www.reddit.com/r/meshtastic/)
- [Official Telegram](https://t.me/meshint)

⇡ [<sub><sup>Table of Contents</sup></sub>](#table-of-contents)

### Unofficial Communities

- [Meshtastic - English](https://t.me/meshtastic_eng) - <sub><sup>(Telegram)</sup></sub>
- [Official Discord Server](https://discord.com/invite/ktMAKGBnBs)
- [Official Subreddit](https://www.reddit.com/r/meshtastic/)

⇡ [<sub><sup>Table of Contents</sup></sub>](#table-of-contents)

## Local Groups

A list of groups that have been actively setting up Meshtastic networks in their respective regions. For the official list of local groups, visit: [Meshtastic Local Groups](https://meshtastic.org/docs/community/local-groups/).

⇡ [<sub><sup>Table of Contents</sup></sub>](#table-of-contents)

### 🇦🇷Argentina

- [Meshtastic Argentina Community](https://github.com/Meshtastic-Argentina/) - <sub><sup>(Github)</sup></sub>
- [Meshtastic Argentina Community](https://t.me/meshtastic_argentina) - <sub><sup>(Telegram)</sup></sub>

⇡ [<sub><sup>Table of Contents</sup></sub>](#table-of-contents)

### 🇦🇺Australia

- [Meshtastic Australia](https://meshtastic.au) - <sub><sup>(Website)</sup></sub>
- Australian Capital Territory
  - [Canberra Meshtastic Community](https://www.meshcanberra.com/) - <sub><sup>(Website)</sup></sub>
  - [Canberra Meshtastic Community](https://discord.com/invite/4QgFsuaC3Z) - <sub><sup>(Discord)</sup></sub>
- New South Wales
  - [Meshtastic & Meshcore Sydney Community](https://www.facebook.com/groups/1041534027106861) - <sub><sup>(Facebook)</sup></sub>
  - [Sydney and Greater NSW Community](https://github.com/orgs/meshtastic/discussions/10) - <sub><sup>(Github Discussions)</sup></sub>
- Queensland
  - [Meshtastic Brisbane User Group](https://discord.com/invite/rN66wEedMY) - <sub><sup>(Discord)</sup></sub>
- Tasmania
  - [Meshtastic User Group Tasmania](https://www.facebook.com/groups/1556630645195649) - <sub><sup>(Facebook)</sup></sub>
- Victoria
  - [Melbourne Meshtastic Users, Australia](https://github.com/orgs/meshtastic/discussions/7) - <sub><sup>(Github Discussions)</sup></sub>
  - [Meshtastic Victoria](https://www.facebook.com/groups/meshtasticvictoria) - <sub><sup>(Facebook)</sup></sub>
  - [VicMesh - r/VicMesh](https://www.reddit.com/r/VicMesh/) - <sub><sup>(Reddit)</sup></sub>

⇡ [<sub><sup>Table of Contents</sup></sub>](#table-of-contents)

### 🇧🇷Brazil

- [Meshtastic Community Brazil](https://t.me/meshtastic_br) - <sub><sup>(Telegram)</sup></sub>

⇡ [<sub><sup>Table of Contents</sup></sub>](#table-of-contents)

### 🇧🇬Bulgaria

- [Meshtastic Community Bulgaria](https://facebook.com/groups/meshtasticbulgaria) - <sub><sup>(Facebook)</sup></sub>
- [Burgas Mesh](https://discord.gg/Kbs233rmq3) - <sub><sup>(Discord)</sup></sub>

⇡ [<sub><sup>Table of Contents</sup></sub>](#table-of-contents)

### 🇨🇦Canada

- [Canadaverse Mesh Wiki](https://wiki.mt.gt/) - <sub><sup>(Website)</sup></sub>
- [Mesh Canada](https://t.me/meshtastic_canada) - <sub><sup>(Telegram)</sup></sub>
- [r/meshtasticCanada](https://www.reddit.com/r/meshtasticCanada/) - <sub><sup>(Reddit)</sup></sub>
- Alberta
  - [Mesht Alberta](https://t.me/meshtAlta) - <sub><sup>(Telegram)</sup></sub>
  - [Mesht Calgary](https://t.me/meshtcalgary) - <sub><sup>(Telegram)</sup></sub>
  - [Meshtastic Calgary](https://t.me/+LzO9qeIC7Ok2YTVh) - <sub><sup>(Telegram)</sup></sub>
  - [YYC Mesh](https://yycmesh.com/) - <sub><sup>(Website)</sup></sub>
- British Columbia
  - [Meshtastic BC users group](https://matrix.to/#/!kKfPDGFNasdKxwulZL:matrix.org?via=matrix.org) - <sub><sup>(Matrix)</sup></sub>
  - [Meshtastic BC users group](https://t.me/Mesh_BC) - <sub><sup>(Telegram)</sup></sub>
  - [Meshtastic Dawson Creek BC users group](https://t.me/Mesh_BC_Dawson_Creek) - <sub><sup>(Telegram)</sup></sub>
- Manitoba
  - [Mesht Manitoba](https://t.me/MeshtManitoba) - <sub><sup>(Telegram)</sup></sub>
- New Brunswick
  - [Mesht New Brunswick](https://t.me/MeshtNB) - <sub><sup>(Telegram)</sup></sub>
- Newfoundland and Labrador
  - [Mesht Newfoundland](https://t.me/MeshtNewfoundland) - <sub><sup>(Telegram)</sup></sub>
- Northwest Territories, Yukon and Nunavut
  - [Mesht NWT - YT - NU](https://t.me/MeshtNWT) - <sub><sup>(Telegram)</sup></sub>
- Nova Scotia
  - [Mesht Nova Scotia](https://t.me/MeshtNovaScotia) - <sub><sup>(Telegram)</sup></sub>
- Ontario
  - [Greater Ottawa Meshtastic Enthusiasts](https://discord.com/invite/THXwXWDRyT) - <sub><sup>(Discord)</sup></sub>
  - [GTA+ Meshtastic Community](https://discord.com/invite/snYp3ghCXC) - <sub><sup>(Discord)</sup></sub>
  - [Mesht Ontario](https://t.me/meshtOnt) - <sub><sup>(Telegram)</sup></sub>
- Prince Edward Island
  - [Mesht PEI](https://t.me/MeshtPEI) - <sub><sup>(Telegram)</sup></sub>
- Quebec
  - [Mesht Quebec](https://t.me/meshtQuebec) - <sub><sup>(Telegram)</sup></sub>
- Saskatchewan
  - [Mesht Saskatchewan](https://t.me/MeshtSaska) - <sub><sup>(Telegram)</sup></sub>
  - [Meshtastic Saskatoon](https://www.facebook.com/groups/1870643856678060/) - <sub><sup>(Facebook)</sup></sub>

⇡ [<sub><sup>Table of Contents</sup></sub>](#table-of-contents)

### 🇨🇳China

- [Meshtastic 中国社区](https://meshcn.net)

⇡ [<sub><sup>Table of Contents</sup></sub>](#table-of-contents)

### 🇨🇴Colombia

- [Meshtastic Users Colombia](https://t.me/meshtasticco) - <sub><sup>(Telegram)</sup></sub>

⇡ [<sub><sup>Table of Contents</sup></sub>](#table-of-contents)

### Denmark

- [Danske Meshtastic Brugere](https://discord.gg/EXWWwDmfBN)

⇡ [<sub><sup>Table of Contents</sup></sub>](#table-of-contents)

### 🇫🇮Finland

- [Mesh Finland](https://discord.com/invite/GHnaVAjqed) - <sub><sup>(Discord)</sup></sub>
- [Mesh Finland](https://mesh-finland.github.io) - <sub><sup>(Website)</sup></sub>
- [MeshAbout](https://www.meshabout.fi/) - <sub><sup>(Discord)</sup></sub>

⇡ [<sub><sup>Table of Contents</sup></sub>](#table-of-contents)

### 🇫🇷France

- [Autour de Meshtastic](https://t.me/+EYBkU17mlcU2MWI8) - <sub><sup>(Telegram)</sup></sub>
- [Collectif Meshtastic France](https://www.facebook.com/groups/meshtastic.france) - <sub><sup>(Facebook)</sup></sub>
- [Réseau Gaulix](https://t.me/+bkCEaiI-i-Q2ZTBk) - <sub><sup>(Telegram)</sup></sub>

⇡ [<sub><sup>Table of Contents</sup></sub>](#table-of-contents)

### 🇩🇪Germany

- [Meshtastic Users D-A-CH](https://t.me/meshtasticgermany) - <sub><sup>(Telegram)</sup></sub>
- [Meshtastic Users Germany](https://www.facebook.com/share/o6CZ9E35UmDKjp9U/) - <sub><sup>(Facebook)</sup></sub>
- [Mesh Hessen](https://meshhessen.de/) - <sub><sup>(Website)</sup></sub>
- [Mesh Hessen](https://t.me/Mesh_Hessen) - <sub><sup>(Telegram)</sup></sub>
- [Meshtastic Users Hannover](https://discord.gg/eEnDkQKEFJ) - <sub><sup>(Discord)</sup></sub>

⇡ [<sub><sup>Table of Contents</sup></sub>](#table-of-contents)

### 🇮🇳India

- [Bir Paragliding Community](https://bircom.in)

⇡ [<sub><sup>Table of Contents</sup></sub>](#table-of-contents)

### 🇮🇱Israel

- [Israel Meshtastic Club](https://www.mesh-il.com)

⇡ [<sub><sup>Table of Contents</sup></sub>](#table-of-contents)

### 🇮🇹Italy

- [Meshtastic Italia Community](https://t.me/meshtastic_italia_community) - <sub><sup>(Telegram)</sup></sub>
- [Mesh_ITA](https://discord.gg/ETFmtyzbFT) - <sub><sup>(Discord)</sup></sub>

⇡ [<sub><sup>Table of Contents</sup></sub>](#table-of-contents)

### 🇯🇵Japan

- [Meshtastic Japan Community](https://www.facebook.com/share/g/BQCGxZhw9SxFQja8/?mibextid=K35XfP) - <sub><sup>(Facebook)</sup></sub>
⇡ [<sub><sup>Table of Contents</sup></sub>](#table-of-contents)

### 🇱🇻Latvia

- ~~Meshtastic Latvija~~ [Archived](https://web.archive.org/web/20250125044231/https://mesh.dodies.lv/)
- [Meshtastic Latvija Matrix Space](https://matrix.to/#/#meshtastic-lv:matrix.org)

⇡ [<sub><sup>Table of Contents</sup></sub>](#table-of-contents)

### 🇱🇹Lithuania

- [Meshtastic Lietuva](https://www.facebook.com/groups/1122509422249414) - <sub><sup>(Facebook)</sup></sub>
- [LithMesh Signal Group](https://signal.group/#CjQKIBScbOkXSG2bkFh_omdxjOM-XqYIU4eERDmGEDrm3jjmEhDyZhh-EeCLSfjfV-DoPvEQ)

⇡ [<sub><sup>Table of Contents</sup></sub>](#table-of-contents)

### 🇲🇽Mexico

- [Meshtastic Mexico Community](https://radioaficionados.mx/meshtastic)
- [Meshtastic User Group Mexico (MUG-Mexico)](https://t.me/meshtastic_mexico) - <sub><sup>(Telegram)</sup></sub>

⇡ [<sub><sup>Table of Contents</sup></sub>](#table-of-contents)

### 🇳🇱Netherlands

- [MeshNet Meshtastic Community](https://www.meshnet.nl/) - <sub><sup>(Website)</sup></sub>
- [Meshtastic Netherlands](https://t.me/meshtastic_nl) - <sub><sup>(Telegram)</sup></sub>

⇡ [<sub><sup>Table of Contents</sup></sub>](#table-of-contents)

### 🇳🇿New Zealand

- [New Zealand Meshtastic Community](https://discord.gg/xb9bBZJUpz) - <sub><sup>(Discord)</sup></sub>

⇡ [<sub><sup>Table of Contents</sup></sub>](#table-of-contents)

### 🇵🇱Poland

- [Meshtastic Polska](https://matrix.to/#/#meshtasticpl:matrix.org) - <sub><sup>(Matrix)</sup></sub>
- Warsaw
  - [Meshtastic Warszawa](https://signal.group/#CjQKIH6ht6sTWQDyjV7FMBAU4ko6xHVTRjIp1Eo-q44ZHVxYEhBuR--ztVU0JCa-196WxJmV) - <sub><sup>(Signal)</sup></sub>
  - [Meshtastic Warszawa](https://wiki.868.band/Home) - <sub><sup>(Website)</sup></sub>

⇡ [<sub><sup>Table of Contents</sup></sub>](#table-of-contents)

### 🇸🇮Slovenia

- [MeshNet.si](https://meshnet.si)
- [Slovenian Amateur Radio](https://discord.gg/uHDDE734DD) - <sub><sup>(Discord)</sup></sub>

⇡ [<sub><sup>Table of Contents</sup></sub>](#table-of-contents)

### 🇿🇦South Africa

- [Meshtastic ZA](https://discord.gg/tKGFwFYvsT) - <sub><sup>(Discord)</sup></sub>
- [ZA Mesh](https://mesh.zr1rf.za.net/)

⇡ [<sub><sup>Table of Contents</sup></sub>](#table-of-contents)

### 🇪🇸Spain

- [Meshtastic Spanish Community](https://t.me/meshtastic_esp) - <sub><sup>(Telegram)</sup></sub>

⇡ [<sub><sup>Table of Contents</sup></sub>](#table-of-contents)

### 🇸🇪Sweden

- [STHLM-MESH](https://discord.gg/gchSzHkPGG) - <sub><sup>(Discord)</sup></sub>
- [STHLM-MESH](https://sthlm-mesh.se) - <sub><sup>(Website)</sup></sub>

⇡ [<sub><sup>Table of Contents</sup></sub>](#table-of-contents)

### 🇹🇼Taiwan

- [Meshtastic Taiwan Community 臺灣鏈網](https://www.facebook.com/groups/413628121046386) - <sub><sup>(Facebook)</sup></sub>
- [Meshtastic Taiwan Community 臺灣鏈網](https://discord.gg/2vZkuckp8E) - <sub><sup>(Discord)</sup></sub>

⇡ [<sub><sup>Table of Contents</sup></sub>](#table-of-contents)

### 🇹🇷Türkiye

- [Meshtastic Türkiye Community](https://t.me/trmesh) - <sub><sup>(Telegram)</sup></sub>
- [Meshtastic Türkiye Community](https://discord.gg/7TGnZSSA) - <sub><sup>(Discord)</sup></sub>
- ~~Meshtastic Türkiye Community - Web~~ - [Archived](https://web.archive.org/web/20241207225721/http://trmesh.org/)

⇡ [<sub><sup>Table of Contents</sup></sub>](#table-of-contents)

### 🇺🇦Ukraine

- ~~WiKi Meshtastic UA~~ - [Archived](https://web.archive.org/web/20241012101501/https://wikimesh.pp.ua/uk/home)

⇡ [<sub><sup>Table of Contents</sup></sub>](#table-of-contents)

### 🇬🇧United Kingdom

- [UK Meshtastic Kent / South East](https://www.facebook.com/groups/ukmeshtastickent/) - <sub><sup>(Facebook)</sup></sub>
- [UK Meshtastic Brighton](https://www.facebook.com/groups/3696312513946679/) - <sub><sup>(Facebook)</sup></sub>
- [UK Meshtastic North East England](https://www.facebook.com/groups/meshtasticnortheastengland/) - <sub><sup>(Facebook)</sup></sub>
- [Swansea Meshtastic Group / Meshtastic Wales](https://swansea.localmesh.org/)
- [UK Meshtastic Berkshire](https://www.facebook.com/groups/1083395923209693) - <sub><sup>(Facebook)</sup></sub>

⇡ [<sub><sup>Table of Contents</sup></sub>](#table-of-contents)

### 🇺🇸United States

- [Meshtastic USA Community](https://www.facebook.com/groups/meshtasticusa/) - <sub><sup>(Facebook)</sup></sub>
- [Midwest Mesh](https://discord.gg/wYwD56K439) - <sub><sup>(Discord)</sup></sub>
- [Mountain Mesh (North GA / East TN)](https://mtnme.sh)
- [DMV (DC-MD-VA) Mesh](https://www.reddit.com/r/Meshtastic_DMV_Users/)
- Alabama
  - [Birmingham Mesh](https://birminghammesh.org/)
- Arizona
  - [Tucson Meshtastic Community](https://discord.gg/7MzbMMd2kg) - <sub><sup>(Discord)</sup></sub>
  - [Arizona Meshtastic Community](https://azmsh.net)
- Arkansas
  - [Central Arkansas](https://lrme.sh)
  - [Fort Smith Mesh](https://discord.com/invite/nwsvcXeqMX) - <sub><sup>(Discord)</sup></sub>
- California
  - [SoCal Mesh](https://socalmesh.org)
  - [Laguna Mesh](https://lagunamesh.com)
  - [Mission Viejo Mesh](https://missionviejomesh.org/)
  - [Meshtastic Bay Area Group](https://bayme.sh/)
  - [MontereyBayMesh](https://mrymesh.net/)
  - [San Diego Mesh](https://discord.gg/k8RputgWgD) - <sub><sup>(Discord)</sup></sub>
  - [Antelope Valley Mesh](https://www.avmesh.org/)
  - ~~AltaMesh~~ - [Archived](https://web.archive.org/web/20250122193410/https://altamesh.net/)
  - [Central Valley](https://centralvalleymesh.net/)
  - [Sac Valley Mesh](http://www.sacvalleymesh.com)
  - [Inter-Canyon Mesh - Orange County Canyons](https://icmesh.com)
  - [Meshtastic Santa Cruz County](https://groups.io/g/Meshtastic-Santa-Cruz)
- Colorado
  - [Denver Mesh](https://denvermesh.org)
  - [Colorado Springs Meshtastic Network](https://www.facebook.com/groups/cosmeshtastic) - <sub><sup>(Facebook)</sup></sub>
- Connecticut
  - [CT Mesh](https://ctmesh.org)
- Florida
  - [Space Coast Mesh](https://scmesh.org/)
  - [JAXMesh](https://jaxmesh.com/)
  - [Florida Mesh](https://areyoumeshingwith.us/) - <sub><sup>(Website)</sup></sub>
  - [Florida Mesh](https://github.com/flmesh) - <sub><sup>(Github)</sup></sub>
  - [Florida Mesh](https://discord.com/invite/JUc8N9nUa8) - <sub><sup>(Discord)</sup></sub>
  - [Meshtastic Florida](https://www.reddit.com/r/Meshtastic_Florida/) - <sub><sup>(Reddit)</sup></sub>
- Georgia
  - [CSRA Mesh - Augusta, GA/North Augusta, SC Area](https://discord.gg/rQSTQDZKgs) - <sub><sup>(Discord)</sup></sub>
- Hawaii
  - [Hawaii Meshnet](https://www.hawaiimesh.net/)
- Illinois
  - [Chicagoland Mesh](https://chicagolandmesh.org)
  - [Clark County Illinois Meshtastic Network](https://clarkcountyill.localmesh.org/)
- Iowa
  - [Iowa Mesh](https://iowamesh.org)
- Kansas
  - [SecKC Amateur Radio Club of Kansas City and Surrounding Cities for Amateur Radio](https://ks3ckc.radio/home)
- Maine
  - [Maine Mesh](https://github.com/JFRHorton/MaineMesh)
- Massachusetts
  - [Boston Meshnet](https://github.com/Darachnid/Boston-Meshnet)
  - [SouthCoast Mesh](https://southcoastmesh.com)
- Michigan
  - [Michigan Meshtastic Network](https://discord.gg/3A5RREcBcc) - <sub><sup>(Discord)</sup></sub>
- Missouri
  - [Kansas City Meshtastic Group](https://www.facebook.com/share/XZ9jnhxy1YT4wWqC/) - <sub><sup>(Facebook)</sup></sub>
  - [MeshSTL - St. Louis](https://discord.gg/QYxUdKZpBd) - <sub><sup>(Discord)</sup></sub>
  - [CMRG Mesh - Jefferson City](https://www.mo-mesh.com)
- Nevada
  - [VegasMesh](https://discord.gg/vUmWuZxYPh) - <sub><sup>(Discord)</sup></sub>
- New Hampshire
  - [NHMesh](https://discord.gg/PkbHWSEXBv) - <sub><sup>(Discord)</sup></sub>
- New Mexico
  - [Albuquerque Mesh](https://www.abqm.net)
- North Carolina
  - [North Carolina Mesh](https://ncmesh.net/)
- Ohio
  - [Cincy Mesh](https://www.cincymesh.org)
  - [Dayton Mesh](https://daytonmesh.org/)
  - [Central Ohio (Columbus Metro Area) Mesh](https://meshcolumb.us/)
- Oklahoma
  - [Oklahoma Meshtastic Group](https://www.facebook.com/groups/942404880478488) - <sub><sup>(Facebook)</sup></sub>
- Oregon
  - [Southern Oregon Meshtastic Community](https://sites.google.com/view/someshtastic/home)
  - [PDXMesh for Portland & SW Washington](https://pdxmesh.com)
  - [Willamette Valley Mesh Eugene / Springfield](https://discord.gg/gf4mShtJz4) - <sub><sup>(Discord)</sup></sub>
- Pennsylvania
  - [Philly Radio & Meshtastic](https://discord.gg/MWWbAkRR9v) - <sub><sup>(Discord)</sup></sub>
- Tennessee
  - [Nashville Meshville](https://meshville.org/)
- Texas
  - [Austin Mesh](https://austinmesh.org/) - <sub><sup>(Website)</sup></sub>
  - [Austin Mesh](https://www.instagram.com/austinmesh/) - <sub><sup>(Instagram)</sup></sub>
  - [Austin Mesh](https://discord.com/invite/6a5Sv2s9bG) - <sub><sup>(Discord)</sup></sub>
  - [Austin Mesh](https://www.youtube.com/@austinmesh) - <sub><sup>(YouTube)</sup></sub>
  - [Cypress, Texas Meshtastic Club](https://discord.gg/KzuwNRwE6q) - <sub><sup>(Discord)</sup></sub>
  - [DFW / North Texas Mesh (NTX Mesh)](https://ntxmesh.com/) - <sub><sup>(Website)</sup></sub>
  - [DFW / North Texas Mesh (NTX Mesh)](https://discord.com/invite/nGeQ8cbSM3) - <sub><sup>(Discord)</sup></sub>
- Virginia
  - [MadisonMesh](https://madisonmesh.com/)
  - [Albemarle Mesh](https://albemarlemesh.com/)
  - ~~Shenandoah Valley Mesh~~ - [Archived](https://web.archive.org/web/20250216025925/https://svmesh.org/)
  - [Northern Virginia Meshtastic](https://groups.io/g/NoVa-Meshtastic)
- Wisconsin
  - [Meshconsin](https://meshconsin.org)
- Washington
  - [Puget Mesh](https://pugetmesh.org)
  - [Tacoma.localmesh](https://tacoma.localmesh.org)
- Washington DC
  - [DC Mesh](https://dcmesh.org)

⇡ [<sub><sup>Table of Contents</sup></sub>](#table-of-contents)

## 🤝Contribute

Contributions welcome! Read the [contribution guidelines](contributing.md) first.

⇡ [<sub><sup>Table of Contents</sup></sub>](#table-of-contents)

## 📝License

This Awesome Meshtastic List is licensed under the [Creative Commons Zero (CC0) 1.0 Universal License](https://creativecommons.org/publicdomain/zero/1.0/).

You are free to copy, modify, and distribute this list, even for commercial purposes, without asking permission.

⇡ [<sub><sup>Table of Contents</sup></sub>](#table-of-contents)

## ⚖️Legal Notice

Meshtastic&reg; is a registered trademark of Meshtastic LLC. This project is in no way affiliated with, endorsed, or sponsored by the trademark holder. No infringement is intended.

⇡ [<sub><sup>Table of Contents</sup></sub>](#table-of-contents)
