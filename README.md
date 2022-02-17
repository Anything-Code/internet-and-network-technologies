# Internet & Network Technologies

<b style="color:teal">
Begin 14.02.2022
</b>

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

| Number | Layer          | Typical                 | TCP/IP              | Additional information  |
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

<b style="color:teal">
End 14.02.2022
</b>

<br>

<b style="color:teal">
Begin 15.06.2022
</b>

## Cisco Packet Tracer

- Switch works once powers on the first time
- Router (is a gateway to other networks) needs configuration the first time it starts up

0/0/0 Router/MainModule/SubModule

Physical/Logical Topology

## That what we call a network

### Packet oriented (packet switched)

- Less resources needed
- Flexible and scalable
- Complex
  - Media-Access-Control an Addressing needed
  - Special Protocols for Administration (many!)
  - Big to huge Overhead
  - SLOW!!!
- Standards mandatory

MAC address and IP Address relationship is lost after 5 minutes.

- Bus System (Token-Ring system)
  - Echo
  - Terminator (50 Ohm)

### Requirements

- Fast (Data rate "Bits/sec")
  - Unpack (ethernet) frame & repack frame is slow
- Fast (Latency/ "Ping-rate")
- Save (Hacker, Malware...)
- Save (Fault tolerance)
- Stability/reliability (up-time)
- Scalable (able to grow)
- Open (Standard)
- Less total costs (cost of ownership)
- Able to administrate or all automatic

### Network types

- Mainframe with Terminals (Serial) old!!!
- Field-busses (RS485, CAN-Bus, Profibus, KNX, I2C, ...) (connection between screen and pc)
- Interfaces (RS232, SATA, USB, IEEE1394, NFC, ...)
- Proprietary networks (many field-busses)
- Infrastructure networks
- AD-HOC-Networking

Bigger packets/chunks take priority

### Physical topologies

- Bus
- Star
- Extended star
- Hierarchical
- Ring, double ring
- Mesh
- Cellular
- Irregular

<b style="color:teal">
End 15.06.2022
</b>

<b style="color:teal">
Begin 16.06.2022
</b>

## Topologies

![Topologies](./img/topologies.jpg)

### Ring or double ring

- Ring (A describes direction of flow)
- Ring (B describes direction of flow)
- There are multiple rings for fallback reasons

## Terms

- BNC (British Navy Connector)
- Switches can be combinations between switches and routers

## Features of routers

- Routers can measure the load on cables and then perform load balancing

![Infrastructure](./img/infrastructures.jpg)

## Features of cables

### U/UTP (Unshielded twisted pairs)

- Typically green, blue, orange, brown colors
- Problem crosstalk: Prevent the cables from touching one-another

### F/UTP (Foiled UTP)

- Foil around the cable
- Good isolation from outside but does not prevent crosstalk

### U/FTP (Foiled twisted pairs)

- Foil around each pair

### SF/UTP (Shielded & Foiled UTP)

### S/FTP (Shielded FTP cable)

<b style="color:teal">
End 16.06.2022
</b>

<b style="color:teal">
Begin 17.06.2022
</b>

## Wired pairs

### RJ45 (Registrated Jack)

- A jack with 8 pins

#### Telephone outputs

- 3, 4 pin

- Telefax outputs

#### Ethernet is applied in the (extended) star topology

- 1, 2, 3, 6

#### Vectoring

- Prevention of crosstalk by removing concurrency
- Like a scheduler

### Cables

#### Patch cable

DCE - DTE for Star topology

1 to 1
2 to 2
3 to 3
4 to 4
5 to 5
6 to 6
7 to 7
8 to 8

#### Cross over or X over cable

DTE - DTE
DCE - DCE

1 to 3
2 to 6
3 to 1
4 to 4
5 to 5
6 to 1
7 to 7
8 to 8

### Signal interferences

- NEXT/FEXT (Crosstalk)
- ACR = Amplitude vs. Crosstalk relationship
- Attenuation
- DC-Potentials
- Interferences (LF, RF)
- Propagation Delay
- Noise (thermal - Brown movement) SNR

### Benefits of gold

1. No corrosion
2. Soft material so it can be formed a little on connection to make the surface area bigger

## Optical fiber

- Polymere -> TOS-Link (Audio-AC3...)
- Glass:
  - Multimode Step-Index
  - Multimode Gradient-Index
  - Singlemode (mono-mode)
  - Advantage:
    - Galvanical insulation
    - EMF/RF-resistance
  - Disadvantage:
    - Complex and expensive
    - Mechanical weak

### Features

- Diameter (125 micrometers)
- Single-Mode (Step-index => Inside diameter is 9 micrometers)
- Multi-Mode
  - Step-index (Diameter => 62,5 micrometers)
  - Gradient-index (Diameter => 50 micrometers)
- Ping time slower than copper
- Throughput is larger than copper
- Max length is much higher than copper cables => less repeaters

#### Glass types

- Inner glass (core-glass)
- Outer glass (cladding glass)

<b style="color:teal">
End 17.06.2022
</b>
