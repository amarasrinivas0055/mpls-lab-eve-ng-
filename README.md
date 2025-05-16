MPLS Layer 3 VPN Lab (EVE-NG)

This project contains a hands-on **MPLS L3 VPN lab** designed and tested on **EVE-NG**, using core service provider technologies including OSPF, MPLS, and BGP with multihop.

## 🧪 Lab Overview

- ✅ OSPF as IGP (loopbacks + transit links only)
- ✅ MPLS with LDP enabled on core links
- ✅ iBGP multihop between PE1 and PE2 (not directly connected)
- ✅ LAN prefixes not advertised into OSPF or placed on P routers
- ✅ End-to-end connectivity verified using source-based ping

> Successfully reached LAN destination **55.1.1.1** from **11.1.1.1** via MPLS VPN — without involving core routers in customer routing.

## 🖼️ Topology

![MPLS Topology](topology.png)

## 📁 Device Configs

Configs for:
- PE1
- PE2
- P1
- P2

(see `/configs` folder)

## 🔧 Technologies Used

- EVE-NG (virtual lab)
- Cisco IOS
- OSPF (IGP)
- MPLS (LDP)
- BGP (with multihop)
- VRFs (if applied)

## 🎯 Learning Focus

- MPLS forwarding logic
- Route separation between customer and provider
- Multihop BGP neighbor establishment
- VPNv4 route distribution

---

🧠 Feel free to clone, learn, and expand this lab for your own CCNP/SP journey!![MPLS Forwarding tables of PE1,P1,P2,PE2](https://github.com/user-attachments/assets/dd4d744c-8d94-49bc-83bd-f23e40dab700)
![Provider router ip route output](https://github.com/user-attachments/assets/15781ec0-d217-4fe9-855f-2928dc6b3a03)
![MY MPLS FIRST LAB](https://github.com/user-attachments/assets/6de23678-da3d-459e-978a-1b7e6bba1123)
