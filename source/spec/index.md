---
layout: page
title: RNCryptor Specifications
footer: false
---

RNCryptor is a specificiation for a correct way to perform AES encryption and encode the result. It more loosely refers to a collection of implementations of this specification.

The specification and the various implementations have independent versioning. For example, the Objective C implementation of RNCryptor v2.2 writes the v3 format.Refer to the implementation documention for details on which specification version the implementation reads and writes.

* [Version 3](https://github.com/RNCryptor/RNCryptor-Spec/blob/master/RNCryptor-Spec-v3.md) - Identical to version 2 specification. Version number was incremented to allow Objective C implementation to detect [possibly truncated multi-byte passwords](https://github.com/RNCryptor/RNCryptor/issues/77).