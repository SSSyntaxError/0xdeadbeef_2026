# Baby Shark
> wire shark doo doo doo doo doo doo

Baby Shark is swimming along a Transmission Control Protocol stream! Can you find the flag?

From the hint, we can tell that the flag can be found in aTCP (Transmission Control Protocol) stream.

1. Filter `tcp.stream eq 5`

2. Follow TCP stream by right clicking any of the filtered packets and then `Follow > TCP stream`

3. The flag is found in the stream, but it is encoded: `upv{onol_funex_qbbqbbqbb}`

4. Since the flag is a basic ROT 13 Caesar's Cipher, we can use CyberChef to decode it (eg. `ROT13(true,true,false,13)` in CyberChef)

**Flag**: `hci{baby_shark_doodoodoo}`
