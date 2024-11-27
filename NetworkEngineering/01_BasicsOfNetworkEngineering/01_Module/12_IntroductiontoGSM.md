# 12_Introduction to GSM

[Introduction to GSM &#128279;](https://alison.com/topic/learn/145595/global-system-for-mobile-communication)

# Introduction to GSM

![](https://courseware-assets.alison.com/public/published/14861/images/168122693627861377.png)

The GSM (Global System for Mobile Communication) digital mobile network is used by a large number of mobile phone users in Europe and other parts of the world. Time division multiple access (TDMA), GSM, and CDMA are the three digital wireless telecommunication systems that are most widely used. Data is transformed into an electronic format by GSM, compressed, and delivered along a channel together with two other streams of user data, each in its own time slot. It operates in the 900 MHz or 1,800 MHz frequency range.

High-Speed Circuit-Switched Data (HSCSD), General Packet Radio Service (GPRS), Enhanced Data GSM Environment (EDGE), and Universal Mobile Telecommunication Service (UMTS) are among the technologies being developed for wireless mobile telecommunications.

# GSM Architecture

The network and switching subsystem (NSS), the base station subsystem (BSS), and the operations subsystem (OSS), which regulate the operation of the NSS and the BSS, make up the GSM network. The GSM system architecture, including the most crucial interfaces. A GSM network also includes features for the storage of voice mailbox messages and the gathering of billing information, in addition to the ones seen in the image. These components are frequently operator-specific and made by outside suppliers because the requirements did not always identify them.

![](https://courseware-assets.alison.com/public/published/14861/images/1681105916697439314.jpeg)

# The Base Station Subsystem (BSS)

Through the radio interface, the base station subsystem (BSS) is in direct communication with the mobile terminals.

Base stations (BTS, base transceiver station) and base station controllers (BSC), which manage the BTSs, as well as the transcoder/rate adapter unit (TRAU), make up the BSS.

## The Base Transceiver Station

The base transceiver station consists of the physical equipment center and the base station hardware (BTS). The TRX components, power sources, combiners, power dividers, antenna cabling, the mast, encryption tools, antennas, and mast amplifiers are all part of the BTS hardware. There may occasionally be a separate uninterruptible power system (UPS) for power maintenance.
The Base Station Controller
The Transcoder

One or more cells' traffic can be transmitted via a BTS. A cell is a coverage area made up of one or more TRXs where there is a chance that radio frequencies may be used. The terminals in the cell's region can view each cell's unique cell identification (CI).

## The Base Station Controller

The base station controller's (BSC) primary duty is to manage the radio resources in its locality. While the BSC manages events in the radio interface at the time of connection, the MSC shifts call via the right BSC to the mobile station (MS).

Each BSC often covers a large area with many base stations. By combining these base stations, location zones are created. A location area may include the entirety of one or more BSC-controlled areas or portions of two or more such areas.

## The Transcoder

The base station subsystem's third component is the transcoder/rate adapter unit (TRAU). The speech encoding and decoding, as well as data rate adaptation to meet the transmission types of the internal GSM network and external networks, are handled by the TRAU. The packet control unit (PCU), which distinguishes GPRS data packets from GSM traffic, is the analogous component in the GPRS network.

The transcoder converts speech from a mobile phone's encoded form to one that can be interpreted by a traditional fixed-line network, and the other way around. The notion is that speech, data, and signaling traffic may be routed from the mobile terminal to the transcoder in a 16 kb/s-sub multiplexed PCM timeslot, however, the usage of full 64 kb/s timeslots is also possible.

# Network Switching Subsystem

![](https://courseware-assets.alison.com/public/published/14861/images/1681227265483093088.jpeg)

The mobile services switching center (MSC) and its associated registers, including the home location register (HLR), visitor location register (VLR), equipment identification register (EIR), and authentication center, make up the network switching subsystem (NSS) (AuC). The group call register is the newest register to be included in the GSM specifications (GCR).

The Mobile Application Part (MAP) is an SS7 protocol that provides an application layer for the various nodes in GSM and UMTS mobile core networks and GPRS core networks to communicate with each other in order to provide services to users. The NSS creates connections between GSM terminals and phones that are not a part of the GSM network. The GSM network's calls, which include calls between MSCs or from one MSC to another, are likewise switched by the NSS. MSCs and other MSCs can communicate directly or through the public telephone network. Even if the connection was made between two GSM terminals within the same cell, the connection is always routed through at least one MSC in the area.

# Operation Subsystem

The operations subsystem (OSS) performs a number of tasks that call for connections to the BSS and the NSS. The Operation and Support Subsystem (OSS) serves as the backbone for managing, monitoring, and maintaining the network’s infrastructure and services. OSS plays a central role in ensuring that the GSM network operates efficiently, reliably, and securely.

The duties of the OSS include:

- Network servicing, operation and management
- Performance monitoring and optimization
- Security and fault management
- Control of subscriber information, including billing information
- Control of mobile stations, configuration and inventory management.
- Traffic Engineering
- Reporting and Analysis

# Functionality of GSM

![](https://courseware-assets.alison.com/public/published/14861/images/1681106716227274968.jpeg)

- [ ] Frequencies

  - Time division multiple access (TDMA) is a technique used by GSM. For each frequency in the GSM system, eight-time slots (TS) are multiplexed. Therefore, when employing a full-rate speech codec, each frequency can have a maximum of eight traffic time slots. By allocating one-time slot for two users, a half-rate codec allows the supplied capacity to be roughly twice.

- [ ] Channels
  - The GSM system refers to each TDMA time slot as a physical channel. Depending on the channel configurations in use, a physical channel may contain traffic channels, control channels, and their combinations. We refer to these as logical channels. One physical channel, for instance, can be used to transfer two half-rate channels, relevant control channels, and one full-rate channel.
- [ ] Traffic Channels
  - A traffic channel can be either full rate (TCH/F), half rate (TCH/H), or an improved variant of the two, where speech links employ an improved full/half rate codec. All of them have been stated, with the exception of the enhanced half-rate codec. It can be seen as a part of the adaptive multi-rate codec (AMR), which is currently being specified. GSM traffic channels are full-duplex or two-way channels.
- [ ] Control Channels
  - Control or signaling channels are used when a mobile phone joins and leaves the network, tracks its location, and establishes, maintains, and ends a connection. The channels are also used to send brief messages and parameters relating to the aforementioned functions. Control channels can be one-way or two-way, depending on the situation.
- [ ] Multi frames
  - The data sent by the sender while a phone is in call mode (voice, data, or fax call) is sent in a 26-multiframe. The sender's data, call control information, and measurement data are sent intermittently over frames 0–25, each of which has eight-time slots.

# Numbering of GSM

## Mobile Subscriber ISDN Number (MSISDN)

The Mobile Subscriber ISDN Number is a mobile station's genuine phone number (MSISDN). A mobile station may have many MSISDNs depending on the SIM because each subscriber's SIM is given a unique MSISDN.

Following is a list of the MSISDN categories' organizational structure, as determined by the international ISDN number plan.

- Up to three decimal places for the country code (CC).
- NDC, or national destination code, usually has two to three decimal places.
- Maximum 10 decimal places for the Subscriber Number (SN).

## International Mobile Subscriber Identity (IMSI)

An original International Mobile Subscriber Identity (IMSI) with a current IMEI is kept on file in the Subscriber Identity Module of every registered user (SIM).

The components of IMSI are as follows:

- 3 decimal places, internationally recognized Mobile Country Code (MCC).
- Mobile Network Code (MNC) with two decimal places is used to uniquely identify mobile networks inside a nation.
- Mobile Subscriber Identifying Number (MSIN): This is the subscriber's home mobile network identification number, with a maximum of 10 decimal places.

## Temporary Mobile Subscriber Identity (TMSI)

The VLR, which manages a subscriber's current location, has the ability to assign Temporary Mobile

Subscriber Identity (TMSI). Only local importance in the region serviced by the VLR is required for the TMSI. This is not sent to the Home Location Register (HLR) but rather stored only on the network side in the VLR.

A subscriber is uniquely identified by their TMSI in addition to their present geographic location. It has a maximum bit size of 4 × 8 bits.

## International Mobile Station Equipment Identity (IMEI)

A mobile station, its manufacturer, and the year of manufacture are all uniquely identified by its International Mobile Station Equipment Identity (IMEI), a type of serial number. The network operator registers the IMEI and keeps a copy of it in the EIR. The IMEI can be used to locate lost or broken equipment.

The components of an IMEI are as follows:

- Centrally assigned Type Approval Code (TAC) with six decimal places.
- Final Assembly Code (FAC) assigned by the manufacturer, with 6 decimal places.
- Six-digit serial number (SNR) given by the manufacturer.  One decimal place (SP).

## SIM and LAI

An individual ICC number, or integrated circuit card code, is assigned to each Subscriber Identity Module(SIM) in the GSM network. It displays the manufacturer code, serial number, operating code, and revision number.

An individual identifier is assigned to each LA in a cellular network. The Location Area Identity(LAI) is also hierarchically organized and globally distinct, and it again consists of an operator-dependent part and an internationally standardized part:

- Location Area Code (LAC), a maximum of five digits or a maximum of 2 × 8 bits, encoded in hexadecimal;
- CC, three digits;
- MNC, two digits;

## BSIC

A base station identity code is the BSIC. It is a more advanced "color code" that separates the cells from one another, for instance, in border regions of various GSM networks. The BSIC has a range of 64 possible values. The 3-bit NCC is a network color code that sets the various GSM networks apart from one another. For the purpose of separating the international neighboring networks, the requirements specify an NCC code for each nation. The NCC codes were chosen such that no neighboring nation had the same number.
