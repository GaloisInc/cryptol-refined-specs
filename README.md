This repository contains a wide range of cryptographic algorithms
specified in the Cryptol language. Contrary to [cryptol-specs](https://github.com/GaloisInc/cryptol-specs/),
the specifications defined in this repository deviate from their description in standards like those at NIST because
they are tailor made for optimization or proof related pruposes.

Our long-term goal is for these specifications to be proved equivalent to their standard counter-parts available in [cryptol-specs](https://github.com/GaloisInc/cryptol-specs/).

All Cryptol files in this repository are covered by [the 3-clause BSD license](LICENSE).

# Collections of Algorithms

This repo has executable specifications for many cryptographic algorithms.

## CNSA 2.0

This repo includes several general purpose, quantum-resistant algorithms approved in [the Commercial National Security Algorithm Suite 2.0 (CNSA 2.0)](https://media.defense.gov/2022/Sep/07/2003071836/-1/-1/0/CSI_CNSA_2.0_FAQ_.PDF) and one of the application-specific algorithms.

| Primitive | Specification | Parameters |
| --- | --- | --- |
| Block cipher | [AES](Primitive/Symmetric/Cipher/Block/AES/RefinedSpecification.cry) | [AES128](Primitive/Symmetric/Cipher/Block/AES/RefinedInstantiations/AES128.cry), [AES192](Primitive/Symmetric/Cipher/Block/AES/RefinedInstantiations/AES192.cry), [AES256](Primitive/Symmetric/Cipher/Block/AES/RefinedInstantiations/AES256.cry) |
| Hashing | [SHA2](Primitive/Keyless/Hash/SHA2/RefinedSpecification.cry) | [SHA-256](Primitive/Keyless/Hash/SHA2/RefinedInstantiations/SHA256.cry), [SHA-384](Primitive/Keyless/Hash/SHA2/RefinedInstantiations/SHA384.cry), [SHA-512](Primitive/Keyless/Hash/SHA2/RefinedInstantiations/SHA512.cry) |

# Contributing

You can contribute to this project by submitting issues or bug reports. Please see our [gold standard spec criteria](https://github.com/GaloisInc/cryptol-specs/wiki/Reviewing-guidelines) for details on what a good executable specification looks like. At this time, we have not completed a style guide, but we have [an issue](https://github.com/GaloisInc/cryptol-specs/issues/5) that may contain some preliminary guidelines.
