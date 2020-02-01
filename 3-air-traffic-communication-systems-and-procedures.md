---
layout: page
permalink: /3-air-traffic-communication-systems-and-procedures/
---

Table of Contents:

- [ATC Communication Introduction](#intro)
- [ICAO Standards on ATC Communication](#standards)
- [ATC Phraseology](#phraseology)
- [ATC-Pilot Miscommunication Issues](#miscommunication)
- [ATC Communication Systems](#systems)
- [Data Link Developments](#datalink)

<a name='intro'></a>

## ATC Communication Introduction

### ATC Communication
Communication is a vital link between controllers and pilots:
- Ability to __sequence and separate__ aircraft is achieve by communication between pilot and ATC
- Miss-communication could lead to accident

### Miscommunication
NASA Aviation Safety Reporting System: Incorrect or incomplete pilot-controller communication is a <ins>causal or circumstantial factor</ins> in __80 percent__ of incidents or accidents (2003-2013).

| Factor | % of Reports |
|:---:|:---:|
| Incorrect Communication | 80% |
| Absence of Communication | 33% |
| Correct but late Communication | 12% |

Incorrect or inadequate...
- ATC instructions (e.g. radar vectors, ...)
- Weather or traffic information
- Advice / service in case of emergency
... are causal factors in more than 30% of _approach and landing_ accidents.

### Early attempts to Air-Ground communications
- Visual, Bon Fire, Flags, Flash Guns (colored flash to represent different signals), Morse Code
- The first air-to-ground and ground-to-air radio communications were accomplished in 1917
- Each Aircraft Company has its own frequency allocation and radio operator
- Controller communicates via airlines
- __Aeronautical Radio Inc (AIRNIC)__ was formed in 1929 for Frequency Management. (Owned by airlines)

### Air-Ground Communication
- Main pillar in communication between pilot and controller is still __analog voice__
- Recently, first __digital data links__ were introducted
- Analog voice communications
  - Voice communication in __VHF-band__ (118-137 MHz)
  - Voice communication in __HF-band__ (2.8-22 MHz)
  
### The Pilot-Controller Communication Loop
Controller must:
- Issue appropriate clearances for the flight operation
- Assign altitudes to IFR flights in controlled airspace (Airspace A, B, C, D, & E)
- Ensures acknowledgement by the pilots
- Ensures correct read back by the pilots
- Make corrections if incorrect/distorted/incomplete read backs

Pilot must:
- Acknowledge ATC clearance
- Reads back any ATC safety instruction
- Request clarification and amendments
- Promptly complies with ATC clearance

<a name='standard'></a>

## ICAO Standards

### ICAO Annex 10
Annex 10 Aeronautical Telecommunications:
Annex 10 is divided into 5 volumes:
- Volume I: Radio Navigation Aids
- Volume II: Communication Procedures
- Volume III: Communication Systems
  - Part I: Digital Data Communication Systems
  - Part II: Voice Communications Systems
- Volume IV: Surveillance Radar and Collision Avoidance Systems
- Volume V: Aeronautical Radio Frequency Spectrum Utilization

### ATC English & ICAO Alphabets
Annex 10, Volume II: _"the air-ground radiotelephony communications shall be conducted in the language normally used by the station on the ground or in the <ins>English Language</ins>"_

ATC English
- Based on simplified English
- Distribute every meaning by different phases
- Issue command directly
- Very short sentence to reduce radio occupied time
- No concern of polite or not

### Common ATC Instructions
1. Request: Ask for permission/information
1. Affirm/Negative/Say again: Yes/No/Repeat what you said
1. Standby: Wait
1. Cleared to...: Approved
1. Taxi to runway ___ by taxiway A, B, C, D...: Taxi your plane to specified runway via taxiway A, B, C, D
1. Hold/Hold short/Hold your position: Stay at one place, stop and don't move
1. Squawking: ATC asks you to adjust your transponder code
1. Say intention: Tell ATC your intention of flight
1. Vector: ATC guiding your plane by using radar vector method
1. Climb FL170 / Descent to 3000ft: Climb to Flight Level 170 / Descent to 3000 feet
1. Contact _____ on 118 decimal 4: Switch your radio frequency to 118.4 and contact a specified ATC (e.g. Tokyo Tower)

<a name='phraseology'></a>

## ATC Phraseology
Commonly used radiotelephony (RTF) phrases that may be encountered during a routine commercial flight in an airspacec:
1. [Clearance and Taxi](#clearance)
1. [Take-off and Departure](#takeoff)
1. [Read-back](#readback)
1. [Climb, Cruise and Descent](#climb)
1. [Approach and Landing](#approach)
1. [Emergency Communications](#emergency)

<a name='clearance'></a>

### Clearance and Taxi
__Taxing is a Safety Critical Activity__
- Taxi Clearance Limit: Point at which the aircraft must stop unless further permission to proceed is given
- Crossing an Intermediate Runway: If a taxi route involves crossing a runway, whether active or not, specific clearance to cross that runway is required

Example: RTF Taxi Instructions to Departure Runway
Pil: Metro Ground, Big Jet 345, request taxi
ATC: Big Jet 345, Metro Ground, taxi to holding point C, runway 27
Pil: Taxi to holding point C, runway 27, Big Jet 345
ATC: Big Jet 345, contact Metro Tower 119 decimal 2
Pil: Contact Metro Tower 119 decimal 2, Big Jet 345

<a name='takeoff'></a>

### Take-off and Departure
- 'Take-off' shall only be used when issuing a clearance to take-off
- Any instructions to HOLD, HOLD POSITION or HOLD SHOFT OF, shall be read back in full
- In the airport environment, the word 'cleared' shall only be used in connection with a clearance to take-off or land.

Example:
```
Pil: Metro Tower, Big Jet 345, approaching holding point C1
ATC: Big Jet 345, Metro Tower, line up runway 27
Pil: Lining up runway 27, Big Jet 345
ATC: Big Jet 345, runway 27, cleared for take-off
Pil: Cleared for take-off, Big Jet 345
Once airborne:
ATC: Big Jet 345, contact Metro Radar 124 decimal 6
Pil: Contact Metro Radar 124 decimal 6, Big Jet 345
```

<a name='climb'></a>

### Climb, Cruise and Descent
Initial Calls: On first contact after departure include: Call-sign + SID + Current or passing level plus cleared level

Once Airborne:
```
ATC: Big Jet 345, contact Metro Radar 124 decimal 6
Pil: Contact Metro Radar 124 decimal 6, Big Jet 345
```

Initial call to radar:
```
Pil: Metro Radar, Big Jet 345, T3F, passing 2300 feet climbing to 6000 feet
ATC: Big Jet 345, Metro Radar, radar contact
```

Degrees & Flight Level changes:
ATC: Big Jet 345, fly heading 260 (degrees), climb to FL 100
Pil: Fly heading 260 (degrees), climb to FL 100, Big Jet 345
```

<a name='approach'></a>
Pilot-interpreted approaches (e.g. ILS) phraseology
'Cleared ILS Approach Runway xx',

Example RTF-ILS
```
ATC: Big Jet 345, turn right heading 240, descend to 3000 feet, report established localiser runway 27 right
Pil: Turn right heading 240, descent to 3000 feet, report established localiser runway 27 right, Big Jet 345
...
Pil: Established localiser, Big Jet 345
ATC: Big Jet 345, cleared ILS approach runway 27 Right
Pil: Cleared ILS approach runway 27 Right, Big Jet 345
```

<a name='emergency'></a>

### Emergency Communications
RTF Emergency Communications: Always ask for assistance when in doubt

A __distress__ message (situation where the aircraft __requires immediate assistance__) is prefixed: MAYDAY, MAYDAY, MAYDAY

An __urgency__ message (situtation __not requiring immediate assistance__) is prefixed: PAN-PAN, PAN-PAN, PAN-PAN

Initial call on the frequency in use ELSE __squawk 7700 and call on 121.5__.

Distress/Urgency message format:
1. Station addressed
1. Call sign
1. Nature of emergency
1. Fuel
1. Persons on board (POB)

Supporting information:
1. Position
1. Flight level
1. Ascending/descending
1. Speed
1. Heading
1. Intentions

Example: RTF Emergency Communications
```
Pil: MAYDAY, MAYDAY, MAYDAY, Metro Control, Big Jet 345, main electric failure, request immediate landing at Metro, position 35 miles north west of Metro, heading 120 flight level 80 descending, 150 persons on board, endurance 3 hours
ATC: Big Jet 345, roger the MAYDAY, turn left heading 090, radar vectors ILS runway 27
```
