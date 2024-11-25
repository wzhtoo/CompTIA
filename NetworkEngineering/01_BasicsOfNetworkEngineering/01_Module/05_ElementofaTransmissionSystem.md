# 05_Element of a Transmission System

[Element of a Transmission System &#128279;](https://alison.com/topic/learn/145592/transmission-process)

## Elements of a Transmission System

The transducers, such as a microphone or a TV camera, that we need to convert an original signal to an electrical form are omitted; unwanted disturbances such as electromagnetic interference and noise are included. Note that bidirectional communication requires another system for simultaneous transmission in the opposite direction.

- Transmitter
- Transmission Channel
- Receiver

The transmitter processes the input signal and produces a transmitted signal suitable to the characteristics of a transmission channel. In the case of optical transmission, the conversion from an electrical signal format to an optical one is carried out in the transmitter.

## Continuous Wave Modulation

![](https://courseware-assets.alison.com/public/published/14861/images/1681228057776578727.jpeg)

The primary purpose of CW modulation in a communication system is to generate a modulated signal suited to the characteristics of a transmission channel. Modulation is needed in the transmission systems to transfer the message spectrum into high radio frequencies that propagate over radio channels. CW modulation is also used in voice-band modems where digital data modulate the carrier frequencies inside the voice frequency band.

In CW modulation the message alters the amplitude, frequency, or phase of the high-frequency carrier. This alteration is detected in the demodulator of the receiver and the original message is reproduced.

## Modulation Methods

There exists a definite relation among the peak value, average value, and RMS value of an alternating quantity. The relationship is expressed by two factors, namely; the form factor and the peak factor.

### Amplitude Modulation

The original carrier wave has a constant peak value (amplitude) and it has a much higher frequency than the modulating signal, the message. In AM the peak value of the carrier varies in accordance with the instantaneous value of the modulating signal and the outline wave shape, or envelope, of the modulated wave, follows the shape of the original modulating signal. Thus, the unique property of AM is that the envelope of the modulated carrier has the same shape as the message.

## Amplitude Modulation and Its Spectrum

![](https://courseware-assets.alison.com/public/published/14861/images/16811026871393523438.jpeg)

## Frequency Modulation

In FM the instantaneous frequency of the carrier is varied according to the message and its amplitude is kept constant. The image in next tab shows an example in which the frequency of the carrier is increased when the value of the modulating message is increased and vice versa. We can assume that FM has good noise performance because if the amplitude is distorted, we can cut it back to the constant value in the receiver, thus eliminating most of the external disturbances. In the detector of the receiver only the instants when the signal curve crosses zero voltage need to be detected.

## Frequency Modulation and Its Spectrum

![](https://courseware-assets.alison.com/public/published/14861/images/16811028521399383832.jpeg)

## Modulation Methods (Continued)

### Phase Modulation

PM is another method in the class of exponential modulations. In PM the instantaneous phase, instead of frequency, is varied linearly according to the message. Therefore, if the message has discontinuities, there will be discontinuities in the modulated carrier wave as well. The spectral characteristics are nearly the same as in the case of FM. When the message returns to zero there is a sudden phase change when the carrier returns to its nominal phase.

![](https://courseware-assets.alison.com/public/published/14861/images/168110297831593468.jpeg)

## Coding

![](https://courseware-assets.alison.com/public/published/14861/images/1681103122924474030.jpeg)

Coding is a digital symbol processing operation in which the digital form of the information is changed for improved communication. In general, coding contains many different processes, such as ciphering, compression, and error control coding. For ciphering, the transmitter and the receiver may simply perform an exclusive operation with data, and a ciphering sequence is known only by the transmitter and receiver. An eavesdropper is not able to detect information content without knowing the ciphering sequence.

## Regeneration

### Principle

In long-haul transmissions, the transmitted signal is attenuated and amplifiers or repeaters are needed. Analog amplifiers amplify the signal at the input, and the signal contains both the desired message and channel noise. In every amplifier and cable section, some noise is added, and the signal-to-noise ratio(S/N) decreases with distance.

Unlike analog amplifiers, digital repeaters are regenerative. A regenerative repeater station consists of an equalizing amplifier that compensates for the distortion and filters out the out-of-band noise and a comparator. The output of the comparator is high if the input signal is above the threshold voltage, and low if the input is below the threshold value. The regenerator also contains timing circuitry, which extracts the clock signal from the received data, and a D-type flip-flop which decides if a digit is high (1) or low (0) at the instant of the rising edge of the clock signal.

## Illustration

![](https://courseware-assets.alison.com/public/published/14861/images/16811032901683262752.jpeg)

## Transmission Media

Transmission systems may use copper cable, optical cable, or radio channels to interconnect far-end and near-end equipment. These channels and their characteristics are introduced next.

- [ ] Copper Cables

  - Copper cable is the oldest and most common transmission media. Its main disadvantages are high attenuation and sensibility to electrical interference.

- [ ] Twisted Pair

  - A twisted pair consists of two insulated copper wires that are typically 0.4 to 0.6 mm thick or about 1 mm thick if insulation is included. These two wires are twisted together to reduce external electrical interference and interference from one pair to another in the same cable. The twisted pair is symmetrical and the difference in voltage (or to be more accurate, electromagnetic wave) between these two wires contains the transmitted signal.
  - The twisted pair is easy to install, requires little space, and does not cost a lot. Twisted pairs are used in the telecommunications networks in subscriber lines, in 2Mbps digital transmissions with distances up to 2 km between repeaters, in DSLs up to several megabits per second, and in short-haul data transmissions up to 100 Mbps in LANs.

- [ ] Open Wire Lines

  - The oldest and simplest form of a two-wire line uses bare conductors suspended at pole tops. The wires must not touch each other, otherwise short circuit occurs in the line and communication will be interrupted. New open-wire lines are rarely installed today but they are still in use in rural areas as subscriber lines or analog carrier systems with a small number of speech channels.

- [ ] Coaxial Cable

  - In a coaxial cable, stiff copper wire makes up the core, which is surrounded by insulating material. The insulator is encased by a cylindrical conductor. The outer conductor is covered in a protective plastic sheath. The construction of the coaxial cable gives a good combination of high bandwidth and excellent noise immunity. Coaxial cables are used in LANs (original 10-Mbps Ethernet), in antenna systems for broadcast radio and TV, and in high-capacity analog and digital transmission systems in telecommunications networks and even in older-generation submarine systems.

- [ ] Optical Fiber Cables
  - Optical fiber is the most modern of the transmission media. It offers wide bandwidth, low attenuation, and extremely high immunity to external electrical interference. Fiber optic links are used as the major media for long-distance transmission in all developed countries and high-capacity coaxial cable systems are gradually being replaced by fiber systems.
