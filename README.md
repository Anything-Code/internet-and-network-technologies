# Internet & Network Technologies

## Standards

- Standards declared by **Cisco** are reliable.
- IPv4 founded 1981

### Active components

- LTW
- PoE injector

### Passive components

- Cable (30-35 cts per meter) [Cat7]
- Antenna
- Jack
- Power outlet

### Fiber splicing

connecting multiple optical fiber cables

## Future proving

- Be able to replace cables
- Cable through big tubes with lots of air

## ARPANET found as internet

Das ARPANET (Advanced Research Projects Agency Network) war ein Computer-Netzwerk und wurde ursprünglich im Auftrag der US Air Force ab 1968 von einer kleinen Forschergruppe unter der Leitung des Massachusetts Institute of Technology und des US-Verteidigungsministeriums entwickelt.

Used by:

- Military
- Universities
- Helping companies

Cisco produced the first router

- Really good Op-sec
- People hate it because of the bad user-interface
- So they founded the cisco-network-academy
  - The people didn't know the difference between a router and a switch...but the knew how to configure it
  - It is now the biggest online-teaching platform
  - For us @srh it is free of use
    - CCNA is relevant
    - There is a simulator (Download executable)
    - CCNA 1 is mandatory to complete for the course (Introduction into networks & Switching, Routing and Wireless Essentials)
    - CCNA 1-4 optional but a good investment

## Optical fibers

100m length limit in ethernet because it is a timing problem and not a problem of signal strength or throughput

## Network devices

Router
Switch
Repeater
(Modem)
Access-Point (AP)
Cable
"Bridge"

### Homerouter (Eierlegende Wollmilchsau)

1. Modem (With or without...determined by ethernet in or optical or dsl) (Optical fiber doesn't need a modem)
2. Router (They do NAT)
3. (Ethernet)-Switch (With Hardware frontend on the H-Roter)
4. (Included) Access-point
5. VOIP (Often)
6. Web interface (With web-server)
7. USB (Sometimes)

## Coarse classification

- LAN (Local Area Network)
  - Ethernet as we use it
  - My Network
- WAN (Wide Area Network)
  - Long distance technology
  - Third party
- MAN (Metropolitan Area Network)
  - Long distance technology but own administration
  - SRH connecting with other universities
- PAN (Personal Area Network)
  - Devices in a network ON YOUR body
- GAN (Global Area Network)

ISO/OSI 7-Layer-model - TCP/IP

International Standards Organisation/ Open System Interconnections

| Number | Layer          | Typical                 | TCP/IP              | Information             |
| :----- | :------------- | :---------------------- | :------------------ | :---------------------- |
| 7      | Application    | Apps,WWW,Servers        | Process/Application |                         |
| 6      | Presentation   | html, mp3, H.264, PGP   | Process/Application |                         |
| 5      | Session        | SQL, Time-service       | Process/Application |                         |
| 4      | Transport      | UDP, TCP, Port-number   | Host-To-Host        |                         |
| 3      | Network        | Internet, Router, IP    | Internet            | Not needed to be usable |
| 2      | Datalink       | Ethernet, switch, MAC   | Network Access      |                         |
| 1      | Physical (PHY) | Cable, wavelength, code | Network Access      |                         |

**SOHO** = Small Office Home Office

### Security

Cisco says the one with the physical access to the device can do anything.
So lock them away and keep the key secure.
