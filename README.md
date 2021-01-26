# A note for those who are curious

👋 Hi

You might be wondering why my commit history is very sparse on GitHub, why a lot of my
repositories here are archived, or maybe why this repo even exists. To put it short I tend to not
use GitHub as my primary git provider and instead do all of my operations within
[GitLab](https://gitlab.com).

I now use GitHub mainly to fork other projects and contribute to them easily but if its a home
grown project then you will likely find it on GitLab instead.

If you are looking for any of the projects I am currently working on then my [GitLab Profile](https://gitlab.com/CarbonCollins) should contain an index of all my active projects there. I have also
included links to some projects that I have done but I may not always keep it up to date here!

## Projects

### hQ

The [hQ project](https://gitlab.com/hq-smarthome) encompases many smaller projects that are within
where I live (`hQ` being the name of the home). This includes my home server, hardware projects, and
other random things I wanted codified. 

#### Home Lab

For a full repository list visit the [hQ - Home Lab Project Page](https://gitlab.com/hq-smarthome/home-lab)

Most repositories listed here are Nomad jobs and service configs which get automatically deployed
into my home lab 

- [Home Automation](https://gitlab.com/hq-smarthome/home-lab/home-automation)
- [Media Streaming](https://gitlab.com/hq-smarthome/home-lab/media-streaming)
- [Network DNS](https://gitlab.com/hq-smarthome/home-lab/network-dns)
- [Network Management](https://gitlab.com/hq-smarthome/home-lab/network-management)
- [Network Proxy](https://gitlab.com/hq-smarthome/home-lab/network-proxy)
- [Network VPN](https://gitlab.com/hq-smarthome/home-lab/network-vpn)
- [ZigBee management](https://gitlab.com/hq-smarthome/home-lab/zigbee-management)

#### MQTT Devices

For a full repository list visit the [hQ - MQTT Project Page](https://gitlab.com/hq-smarthome/mqtt)

- [Drawer Sense](https://gitlab.com/hq-smarthome/mqtt/drawer-sense) - publishing an IKEA draw status
to an MQTT broker
- [Home Assistant Dashboard](https://gitlab.com/hq-smarthome/mqtt/ha-dashboard) - small dashboard by
the hQ entrance
- [UPS Sense](https://gitlab.com/hq-smarthome/mqtt/ups-sense) - publishing UPS metrics to an MQTT
broker

#### LXC (Deprecated)

This group of repositories has been deprecated/archived as my previous
[Proxmox](https://www.proxmox.com/en/) home lab setup has been replaced with a
[HashiCorp Nomad](https://www.nomadproject.io/) one. To see repositories relating to the new setup
please have a look at any of them listed under [Home Lab](#home-lab)

### Plattform33

The [Plattform33 project](https://gitlab.com/plattform33) is currently private, this will change in
the future though.

### OpenRail

The [OpenRail project](https://gitlab.com/openrail) is a set of long running repositories and NPM
packages used for accessing data from publically available rail information sources. The
repositories here are in various states of being maintained/preparing to be archived. Most of this
code was to keep me busy while on my long morning commutes where I would mess arround with rail data
and ended up publishing the code so other could use it if they had a use for it.

I have two seperate sub groups for this project as I originally started when I lived in the
United Kingdom, however, I have since moved to Sweden so I also created packaged for the Swedish
rail network.

#### UK

For a full list of repositories visit the [OpenRail - UK Project Page](https://gitlab.com/openrail/uk)

- [common-nodejs](https://gitlab.com/openrail/uk/common-nodejs)
- [darwin-nodejs](https://gitlab.com/openrail/uk/darwin-nodejs)
- [referencedata-nodejs](https://gitlab.com/openrail/uk/referencedata-nodejs)
- [stomp-client-nodejs](https://gitlab.com/openrail/uk/stomp-client-nodejs)
- [tlf-unified-api-nodejs](https://gitlab.com/openrail/uk/tfl-unified-api-nodejs)
- [trust-nodejs](https://gitlab.com/openrail/uk/trust-nodejs)


#### SE

For a full list of repositories visit the [OpenRail - SE Project Page](https://gitlab.com/openrail/se)

- [trafikverket-nodejs](https://gitlab.com/openrail/se/trafikverket-nodejs)

### Nomad USB Device Plugin

Currently being developed to allow Nomad to fingerprint available USB devices on a node and to allow
jobs to require specific USB devices to be available for mounting.

- [Nomad USB Device Plugin](https://gitlab.com/CarbonCollins/nomad-usb-device-plugin)

### Civo Cloud

While I was beta testing for [Civo Cloud](https://www.civo.com/) I ended up making an API wrapper
in Node.JS to be able to automate some portions of my civo account. This got published as an NPM
package as there was not an existing package for this availabe. I have not been activly maintaining
this package but it is still accessible.

- [civocloud-nodejs](https://gitlab.com/CarbonCollins/civocloud-nodejs)

### iOS Mobile Config

A Node.JS package for generating iOS profiles which I used to create automated profiles for
connecting to WiFi, distributing internal SSL/TLS certificates, and ocnnecting to my custom
multi-room airplay speakers

- [mobileconfig](https://gitlab.com/CarbonCollins/mobileconfig)
