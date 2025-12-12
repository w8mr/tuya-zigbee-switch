# Supported devices

### Quick-picks
- **modules:** AVATTO, Aubess, iHseno
- **switches:** Moes 1-3gang (any design)

Support new devices: [contribute/porting.md](/docs/contribute/porting.md)  

### Legend

| Symbol | Meaning  |                    |                      |                    |                |           |
| :----: | ---------| ------------------ | -------------------- | ------------------ | -------------- | ----------|
|   🚧   | Status   | 🟩 Fully supported | 🟨 Mostly supported  | 🟧 In progress     | 🟥 Unsupported |           |
|   📦   | Build    | ✔️ Available       | ❌ Unavailable       |                    |                |           |
|   💡   | Category | 🇲 Module          | 🇸 Switch            | 🇴  Outlet         | 🇷 Remote      | 🇧  Board |
|   ⚡   | Power    | 🔌 Mains           | 🔋 Battery           | 🔱 USB             |                |           |
|   📲   | Install  | 🛜 Wireless        | ➿ By wire           | ❓ Some by wire    |                |           |
|   🏭   | MCU      | `TL` Telink        | `SL` Silicon Labs    |                    |                |           |
|   🅰    | Variant  | 🅰                  | 🅱                    | 🅲                  | 🅳              | 🅴         |

<!-------------------------------------------------------------------
  `supported.md` is generated. 
  
  Do not edit it directly! Instead, edit:
  - `device_db.yaml`             - add or edit devices
  - `supported_devices.md.jinja` - update the template
  - `make_supported_devices.py`  - update generation script

  Generate with: `make tools/update_supported_devices`
-------------------------------------------------------------------->

> [!IMPORTANT]  
> Identify your device by **Zigbee Manufacturer** and linked threads/stores!  
> *Z2M pages are sometimes generic.*

### Device list

| 🚧 | 📦 | 💡 | ⚡ | 📲 | 🏭 | Zb&nbsp;Manufacturer <br> Zb&nbsp;Model | Name <br> Z2M&nbsp;page&nbsp;🔗 | Store | Threads | Status |
| -- | -- | -- | -- | -- | -- | :-------------------------------------- | :------------------------------ | ----: | ------: | :----- |
| 🟩 | ✔️ | 🇲 | 🔌 | 🛜 | **TL** | `_TZ3000_ju82pu2b` <br> `TS0003` | [iHseno 3-gang switch](https://www.zigbee2mqtt.io/devices/TW-03.html) | [`AlEx`](https://www.aliexpress.com/item/1005008107698143.html) |   | Supported | 

Data from [`device_db.yaml`](/device_db.yaml)
