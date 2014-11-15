cryptfuzz
=========

cryptfuzz provides an automated way of uncovering cryptographic weaknesses in a target algorithm. Like a traditional fuzzer, cryptfuzz feeds the algorithm different inputs to provoke unexpected behavior. Unlike a traditional fuzzer, cryptfuzz does not look for software crashes, but for structural weaknesses such as (differential) distinguishers and side-channel leakages. This project is inspired by Serge Vaudenay’s research on computer aided cryptanalysis.
