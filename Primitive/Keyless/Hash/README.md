This directory includes executable specifications for several hash functions.

## SHA2

This directory contains a [`SHA2`](/Primitive/Keyless/Hash/SHA2) implementation that is equivalent to the on available in [cryptol-specs](https://github.com/GaloisInc/cryptol-specs/tree/master/Primitive/Keyless/Hash/SHA2). It was originally written as part of a proof of correctness for a Java implementation of SHA2. It makes public several internal components of SHA2, like the compression function and the state representation, that are not part of the public interface defined in [FIPS 180-4](https://nvlpubs.nist.gov/nistpubs/FIPS/NIST.FIPS.180-4.pdf). This refined cryptol specification is currently being used in the [BLST-Verification](https://github.com/GaloisInc/BLST-Verification) repository where you will find specifications and correctness proofs for the [blst](https://github.com/supranational/blst) BLS12-381 signature library.
