## References

1. **National Institute of Standards and Technology (NIST).**  
   *FIPS PUB 180-4: Secure Hash Standard (SHS).*  
   https://nvlpubs.nist.gov/nistpubs/FIPS/NIST.FIPS.180-4.pdf  
   - I learned the official rules for the SHA-256 functions: `Ch(x, y, z)`, `Parity(x, y, z)`, and `Maj(x, y, z)`.
   - I also learned how these bitwise operations are used inside the hashing process.

2. **Python Software Foundation.**  
   *Python 3.12 Language Reference - Expressions.*  
   https://docs.python.org/3/reference/expressions.html#binary-bitwise-operations  
   - I learned what the bitwise operators mean in Python: `&` (AND), `^` (XOR), and `~` (NOT).
   - This helped me write the SHA-256 functions correctly.

3. **NumPy Developers.**  
   *NumPy v2.1 Manual - Data Types.*  
   https://numpy.org/doc/stable/reference/arrays.scalars.html#numpy.uint32  
   - I learned that `np.uint32` keeps numbers within a 32-bit range, like a real computer processor would.
   - This helped me make sure the SHA-256 operations behave like 32-bit hardware.

4. **Python Software Foundation.**  
   *PEP 8 - Style Guide for Python Code.*  
   https://peps.python.org/pep-0008/  
   - Learned to limit lines to 79 characters for readability.
   - Applied 4 spaces per indentation level.
   - Ensured consistent comments and blank line spacing throughout the project.

5. **Sha256Algorithm.com.**  
   *Understanding the SHA-256 Algorithm.*  
   https://sha256algorithm.com/  
   - This website helped me see how SHA-256 function works in practice.  
   - It gave an easy explanation of how the bitwise operations mix data to make a secure hash.

## Further reading / Tutorials

- **YouTube:** https://www.youtube.com/watch?v=PbFVTb7Pndc  
  - Helped me understand hashing at a high level.  
  - The visuals made the bitwise steps easier to follow.  

- **YouTube:** https://www.youtube.com/watch?v=orIgy2MjqrA  
  - Explained why small input changes cause big output changes (avalanche).  
  - Clarified collisions and why hashes are one-way.  

- **Boot.dev Blog – “How SHA-2 Works (Step-by-Step, SHA-256)”**  
  https://blog.boot.dev/cryptography/how-sha-2-works-step-by-step-sha-256/  
  - Gave a simple walkthrough of rounds, message schedule, and functions.  
  - Helped link `Ch`, `Maj`, and rotates to the full SHA-256 flow.  

