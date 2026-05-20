### son 😭😭

son 😭😭

son 😭😭

1. Open the txt in a hexeditor. If we inspect the hex after "son", we can notice there is a reoccurance of two patterns: "f0 9f 98 ad" and "e2 80 8b"

2. This corresponds to the emoji "😭" and a zero-width space "​" respectively.

3. Thus, by removing the redundant string "son" at the start, we can now convert every "😭" to 0, and every "​" (zero-width space) to 1.

4. This gives us "01101000011000110110100101111011011100110011000001101110001100010011000001101110010111110111001000110001011011100110011101111101", which is the flag in binary ASCII

**Flag**: `hci{s0n10n_r1ng}`