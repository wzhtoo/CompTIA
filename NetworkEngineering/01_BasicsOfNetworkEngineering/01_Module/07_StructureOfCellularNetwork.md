# 07_Structure Of Cellular Network

[Structure Of Cellular Network &#128279;](https://alison.com/topic/learn/145593/mobile-communication)

Structure of a Cellular Network
Cellular Structure
The region of a cellular network is divided into small cells of only a few kilometers or less wide, as opposed to having to cover a full area with high-power fixed radio stations as required by prior-generation radio systems. Smaller cells are used to cover high subscriber-density areas compared to low subscriber-density areas. With a smaller cell size, the power BSs and MSs are naturally reduced
Base Station Subsystem (BSs) handles the radio access functions and includes the Base Transceiver System (BTS) and the Base Station Controller (BSC)..
The Mobile Station (MS) consists of the terminal equipment and the Subscriber Identity Module (SIM).

The transmission power of the BSs and MSs (telephones) is managed to be as low as possible. This low-power transmission has no adverse effects on other cells that are using the same frequency (reuse of frequencies) as this cell.

## Cellular Structure of a Mobile Radio Network

![](https://courseware-assets.alison.com/public/published/14861/images/16811038871159512385.jpeg)

## HLR and VLR

Customers are enrolled in the Home Location Register(HLR) of their own mobile telephone operator when they buy a mobile phone. The HLR maintains its most recent subscriber data, including its current location (in the territory of the Visitor Location Register(VLR)), the services they are authorized to use, and the phone number to which it has transferred calls. Wherever they go, users may access their information through the HLR, which serves as a worldwide hub. The called subscriber's phone number informs the network of the location of their HLR when a call is routed to them.

Every subscriber in the area is profiled by VLR. When a new subscriber enters the HLR's service region, the VLR notifies the HLR. The VLR is usually integrated into a mobile telephone exchange but the HLR is usually a physically separate efficient database system.

## Radio Channels

The common control channel and the dedicated channels are the two primary types of channels offered by each BSs.

On the common control channel of each cell, information such as network identity, position data, designated power level, and paging for incoming calls is provided in the downlink or forward direction (from network to mobile stations). When MSs are in idle mode (there isn't a call going on), they are always listening to the cell's common control channel.

When making outgoing calls or when they detect that they have entered a new location region, for instance, the MSs send location update messages in the uplink or reverse direction of the common control channel.

## Operating Principle of a Cellular Network

- [ ] Mobile Station in Idle Mode

  - The frequencies of the control channels are preprogrammed into the MS. The mobile checks various frequencies when it is turned on and chooses the BS with the strongest common control channel. The MS then notifies the VLR over the control channel using its special identification code, which could be its phone number (or another identifying code, depending on the system).
  - The address of the subscriber's home country and home network is determined by the VLR using the MS's identification as a guide. The signaling message is then sent to the domestic network by the MSC(Mobile Switching Center)/VLR. The communication is subsequently forwarded to the HLR, which is then alerted to the fact that this particular subscriber has now moved into a certain VLR's service region. Now the HLR is able to route the calls to the right MSC/VLR, which routes it further to the mobile subscriber.

- [ ] Outgoing Call
  - Through the keypad of the mobile phone, the user enters the number they wish to call into the memory of the device. When the user touches the Call button, the mobile device sends a series of signaling messages to the BS over the common control channel. The dialed digits are contained in these messages, which the BS then sends to the Mobile Switching Center( MSC) for routing.
  - The MSC examines the dialed number, sends the numbers to the public switched telephone network (PSTN) for call establishment, and asks a BS to set aside a specific speech channel for the calling mobile. When the person who was phoned responds and the conversation is permitted to begin, the MS and BS switch to this channel
- [ ] Incoming Call

  - When a call is to be connected to the MS, the HLR determines to which VLR address the call should be routed. This address is global, containing the country and network codes according to the international telephone numbering scheme. The call is then routed to the MSC/VLR, which knows the exact location (the location area) of this specific subscriber inside its area.
  - A paging message with MS identification is sent on the common control channel of all BSs in that area where the subscriber is currently located. The receiving MS continuously listens to this channel and when it receives the message containing its own identification it requests a speech channel and a channel is allocated for this call. The BS and MS switch to the allocated channel, the telephone rings, and when the subscriber presses the Call button, the call is connected.

- [ ] Handover or Handoff
  - The transmission power of the MS and BS are continuously adjusted to maintain a sufficient degree of connection quality while also keeping the transmission power as low as feasible while a call is in progress. The transmission power is increased to the highest value permitted for that cell when an MS approaches the cell's edge. The Signal-to-noise ratio (S/N) of the channel diminishes and the error rate rises as an MS gets farther away from the BS.
  - When the quality drops below a certain threshold, a new channel is assigned in a nearby cell, and the BS and MS are asked to switch simultaneously to the new channel. The cellular network analyzed the measuring results before the switch and estimated the quality between the MS and neighbor cells. The best alternative is selected for a new cell.
- [ ] MS Transmitting Power
  - During the planning phase of a cellular network, the maximum transmitting power for each cell is defined. This power is dependent on the desired cell size and on geographic conditions. The transmitting power of the common control channel of the BS is adjusted to a level that is high enough to cover the cell area but not higher than necessary. During a call the network, to minimize interference between cells that use the same frequency, continuously controls the transmitting power of the MS and the BS. This also saves the battery of the MS.
