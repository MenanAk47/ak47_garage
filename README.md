# Advanced Garage System Fivem ESX/QB/QBX Framework

**The ultimate garage and vehicle management system for FiveM servers.** This script completely revamps vehicle storage, impound, and parking with a sleek 3D showroom interface, physical RealParking, world vehicle persistence, an in-game 3D garage builder, and seamless housing integration. Powered by `ak47_lib`, it delivers full multi-framework compatibility, high performance, and deep roleplay immersion.

---

## 🎥 [Showcase](https://youtu.be/1IWmrUWzqaM)
<img width="1920" height="1080" alt="thumbnail" src="https://github.com/user-attachments/assets/6d0a4f02-e360-4f7c-9e20-bb53e0423671" />

---

## 🔥 Key Features

Designed to elevate roleplay immersion, vehicle management, and server economy:

### 🏎️ Modern 3D Showroom & Live Vehicle Analytics

* **Cinematic 3D Showroom:** Smooth camera transitions, lighting effects, running engines, and smart FOV scaling tailored to vehicle dimensions and classes.
* **Live Performance & Rarity:** Automatic real-time calculations of top speed, 0-100 acceleration, handling index, braking power, drive layout (AWD/RWD/FWD), horsepower, weight, and rarity tiers (*COMMON*, *UNCOMMON*, *RARE*, *EPIC*).
* **Studio Photography:** Built-in studio photo room integrated with FiveManage API and `screenshot-basic` to capture high-quality vehicle preview thumbnails. Includes an in-game live camera debugger (`/photodebug`).

### 🅿️ Physical RealParking & Visual Dummies

* **Physical Parking Spots:** Parked vehicles appear physically in the world with a smooth opacity fade-in.
* **Direct Unpark Interaction:** Walk up to your parked vehicle and enter the driver seat to pay fees and drive away instantly.
* **Time-Based Parking Fees:** Configurable hourly parking fee rates with optional maximum fee caps.

### 🌐 Persistent Vehicles System

* **World Persistence:** Player-owned vehicles remain in the world across server restarts and dynamic distance streaming.
* **Full State Preservation:** Saves exact coordinates, engine/body health, door/window damage, tire bursts, fuel level, engine status, headlights/indicators, handbrake, convertible roof state, dirt level, radio stations, and door lock states.
* **Smart Auto-Impound:** Automatically moves submerged, drowned, or destroyed vehicles to impound. Inactive vehicles untouched for X hours are auto-impounded with configurable fines.

### 🏗️ In-Game 3D Garage Creator Wizard

* **Interactive Setup:** Admin commands (`/creategarage`, `/garagesetting`, `/deletegarage`) with a step-by-step checklist wizard and free-flying noclip camera.
* **Multi-Category Garages:** Create Car, Boat, Helicopter, and Plane garages with ease.
* **Trailer & Respawn Points:** Set dedicated truck & trailer spots and pedestrian water exit locations.

### 🚨 Impound, Rescue & GPS Tracker

* **Rescue Service:** Request emergency vehicle rescue from impound lots with configurable countdown timers or instant delivery.
* **GPS Locator:** Mark the live GPS coordinates of your active vehicle directly on the minimap for a small fee.
* **Fee & Fine Management:** Full breakdown for standard impound fees, time-based fines, and depot costs.

### 🔄 Ownership Transfer & Housing Integration

* **In-Menu Ownership Transfer:** Transfer permanent ownership to any nearby player by Server ID with built-in model, category, and plate blacklists.
* **Discord Audit Webhooks:** Detailed logging of sender, receiver, and vehicle information.
* **Housing Integration:** Native events for housing and property scripts (`ps-housing`, `qb-houses`, `ox_property`, etc.) with customizable vehicle capacity limits.

---

## 💻 Framework:

* ESX, QB, QBX

---

## ⚙️ Dependencies:

* ak47_lib: https://github.com/MenanAk47/ak47_lib/releases/latest
* ak47_map_garageroom: Included in package

---

## ⚙️ How To Install:

* Download `ak47_garage` from your Cfx.re Keymaster portal.
* Place `ak47_garage` and `ak47_map_garageroom` in your server's `resources` folder.
* Import the SQL table from `INSTALL ME FIRST` for your framework (`esx.sql`, `qb.sql`, or `qbx.sql`).
* Configure your preferences in `config.lua` and set your `Config.FiveManageImageToken`.
* Ensure `ak47_lib` and dependencies start before `ak47_garage` in your `server.cfg`.
* Restart the server.

---

## 🔗 Links & Support:

* **📖 Documentation:** [https://docs.menanak47.com/multi-framework/ak47_garage](https://docs.menanak47.com/multi-framework/ak47_garage)
* **🛒 Buy Now (Tebex):** [https://menanak47.tebex.io/package/6099640](https://menanak47.tebex.io/package/6099640)
* **💬 Discord Support:** [https://discord.gg/menanak47](https://discord.gg/menanak47)
