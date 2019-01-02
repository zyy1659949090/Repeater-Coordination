# Repeater-Coordination
Repeater Coordination
Problem	 
 	
The VHF radio spectrum involves line-of-sight transmission and reception. This limitation can be overcome by "repeaters," which pick up weak signals, amplify them, and retransmit them on a different frequency. Thus, using a repeater, low-power users (such as mobile stations) can communicate with one another in situations where direct user-to-user contact would not be possible. However, repeaters can interfere with one another unless they are far enough apart or transmit on sufficiently separated frequencies.

In addition to geographical separation, the "continuous tone-coded squelch system" (CTCSS), sometimes nicknamed "private line" (PL), technology can be used to mitigate interference problems. This system associates to each repeater a separate subaudible tone that is transmitted by all users who wish to communicate through that repeater. The repeater responds only to received signals with its specific PL tone. With this system, two nearby repeaters can share the same frequency pair (for receive and transmit); so more repeaters (and hence more users) can be accommodated in a particular area.

For a circular flat area of radius 40 miles radius, determine the minimum number of repeaters necessary to accommodate 1,000 simultaneous users. Assume that the spectrum available is 145 to 148 MHz, the transmitter frequency in a repeater is either 600 kHz above or 600 kHz below the receiver frequency, and there are 54 different PL tones available.

How does your solution change if there are 10,000 users?

Discuss the case where there might be defects in line-of-sight propagation caused by mountainous areas.
