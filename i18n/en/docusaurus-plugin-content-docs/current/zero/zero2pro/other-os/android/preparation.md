---
sidebar_position: 1
---

# Preparation

<Tabs queryString="prepare_items">
<TabItem value="Must">

### Power Supply

ZERO 2 PRO is powered by Type-C connector with 5V input voltage, recommended to use a power adapter with a rated maximum current greater than 2A.  
We recommend using the official [Radxa Power PD 30W](../accessories/pd-30w). <img src="/img/accessories/pd-30w.webp" alt="Radxa Power PD 30W" width="300" />

### Boot Media

Onboard eMMC or sd-card  
If the board doesn't have an onboard eMMC([The eMMC is located on the back of the board](../hardware-design/hardware-interface#interface-overview)) you need to prepare a sd card with at least 8GB.  
If you need to install an image with desktop environment, please use a sd card with at least 16GB, 32GB is recommended.

### microSD card reader

For flashing the system image.

</TabItem>

<TabItem value="Optional">

### Monitor

The Radxa ZERO 2 PRO has a micro HDMI video output port on board, which requires a micro HDMI to standard HDMI cable to connect to the monitor.  
The resolution of the HDMI output depends on the monitor, and the Radxa ZERO 2 PRO will adjust to the optimal display resolution according to the monitor.

### Networking

ZERO 2 PRO has an ap6212/ap6256/aw-cm256sm WiFi/BT module on board.

### Type-C Hub

The Radxa ZERO 2 PRO has an onboard [Type-C USB3.0](../hardware-design/hardware-interface#interface-overview). This interface supports Type-A ports and wired networks via the USB Type-C hub (if the hub supports it), but does not have video out.

### USB Mouse and Keyboard

The Radxa ZERO 2 PRO can be controlled by a keyboard and mouse connected to the USB Hub.

### USB to TTL Serial Cable

- ZERO 2 PRO outputs a dedicated serial console for the CPU to access low level debug messages.
- Recommended Radxa USB to TTL Cable <img src="/img/accessories/usb-ttl.webp" alt="USB to TTL Cable" width="500" />.

</TabItem>
</Tabs>
