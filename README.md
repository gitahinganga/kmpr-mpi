# Fingerprint Manager

An API for adapting sundry fingerprinting implementations to OpenEMRConnect modules.

# Description

OpenEMRConnect supports fingerprinting in an implementation-agnostic way. As long as you have a
fingerprinting SDK written in Java, you can implement a "wrapper" based on this API to make it
available to OpenEMRConnect modules. A reference implementation for the Griaule Fingerprint SDK
exists, as well as a dummy implementation that allows OpenEMRConnect modules that require
fingerprinting to compile without a concrete implementation.

# Getting Started

Implement the FingerprintManager class to wrap your underlying fingerprint technology in a way that
it can be plugged into OpenEMRConnect. 

# Dependencies

None

# Installing

N/A

# Running

N/A

## License

This project is licensed under the Mozilla Public License.
 
