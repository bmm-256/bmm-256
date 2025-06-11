bpm-256 — Bitcoin Pixel Mnemonic
bpm-256 is an open protocol and reference implementation for representing BIP-39 seed
phrases as 16×16 pixel grids. It provides a visual and editable interface for entropy,
enabling precise, deterministic encoding of BIP-39 data as an image.
Features
Visual representation of 256-bit entropy
Support for BIP-39 seed phrases and raw HEX input
Editable 16×16 pixel grid (1 pixel = 1 bit)
Custom colors for bits 0 and 1
PNG export
Validity check and automatic checksum generation (BIP-39 compliant)
Fully client-side and offline-capable
Official reference implementation of the
bpm-256
protocol
Specification
Protocol:
bpm-256
(Bitcoin Pixel Mnemonic)
Input entropy: 256 bits (32 bytes)
Output: 24-word BIP-39 seed phrase
Grid size: 16×16 pixels
1 pixel = 1 bit (white = 0, black = 1 by default)
Checksum: 8 bits derived from SHA-256(entropy)
Wordlist: standard English BIP-39 (2048 words)

---

 Author: Aleksandr Yashchuk (2025)
  License: CC BY 4.0 — https://creativecommons.org/licenses/by/4.0/
  
  GitHub:   https://github.com/bpm-256/bpm-256
  Website:  https://bpm-256.com
  Twitter:  https://twitter.com/pixel_mnemonic
  Contact:  1548xfr@gmail.com