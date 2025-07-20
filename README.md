![random photo i found online](https://miro.medium.com/v2/resize:fit:1100/format:webp/1*toFCSMywGTmH_x5_GcOlBw.jpeg)
## 📖 Prologue
I was cleaning my basement when i found an old computer that belonged to my brother ages ago. Instead of throwing it away, I looked into what I could do with it and came across the concept of home servers.
## 🤔 what is an home server
A home server is essentially a dedicated computer in your house that runs continuously to provide services to all your other devices. Think of it as the central hub of your home network. Instead of relying on various cloud services, you can use your own server for things like:

* Centralized storage: Storing all your family photos, videos, and documents in one place.

* Media streaming: Running a media server like [Plex](https://www.plex.tv/) or [Jellyfin](https://jellyfin.org/) to stream your movies and music to any screen.

* Home lab: Managing your smart lights, speakers, and other devices.

By using a home server, you gain more control, privacy, and flexibility over your data and services.

## 🛠️ Setting up the server
i decide to go with [UBUNTU SERVER](https://ubuntu.com/download/server), as it seemed like the most convenient and well-supported option. 
I followed [this guide](https://youtu.be/TPtgeFzQTrk) to get everything set up and running.

## 🔧 what i use it for
This server is now the backbone of my home network, providing several key services.

### 📺 Media Streaming with Jellyfin
I've deployed Plex on the server to manage and stream my entire media library. 
This allows me to access my movies and TV shows from any device connected to my network.

### 💾 Storage:
The server acts as my personal network-attached storage (NAS). 
I've configured it to be accessible remotely using Tailscale VPN, which creates a secure, private network between all my devices. 
This ensures I can access my files from anywhere without compromising my data.

### (﹙˓ 🖨️ ˒﹚) wireless printing:
To give new life to an old printer, I connected it to the server using [CUPS](https://openprinting.github.io/cups/).
By setting up the server as a print server, I can now use the printer wirelessly from any computer on my home network.



