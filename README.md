🔐 DES Background Prep-1 Assignment

✅ Objectives:
Implement the following components of the DES (Data Encryption Standard) algorithm:

Initial Permutation (IP) and Final Permutation (FP)

Compression Permutation Box (64 → 48 bits)

Expansion Box (48 → 64 bits)

🧠 Concept Overview:
Initial Permutation (IP): Rearranges the 64-bit input before encryption starts.

Final Permutation (FP): The inverse of IP, applied at the end of DES.

Compression (PC-2): From 64-bit key to 48-bit subkey.

Expansion (E-box): From 48-bit to 64-bit data (hypothetical here, as original DES expands from 32 to 48 bits).

 How to Use It:
Initial Permutation (IP): Reorders bits of 64-bit input before encryption.

Final Permutation (FP): Reorders bits back to original order after processing.

Compression Box: Reduces a 64-bit input to 48 bits.

Expansion Box: Artificially expands a 48-bit input back to 64 bits.

📌 Notes:
In actual DES, expansion is from 32 → 48 bits, not 48 → 64. The expansion here is a custom mapping for this assignment.

permute() is a general function that can apply any permutation table.

This implementation is for educational purposes and does not perform full DES encryption.
