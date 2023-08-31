# Counterfeit_Object_Oriented_Programming (COOP)

### Abstract

The main idea behind this technique is counterfeiting – that is crafting new objects in-memory from attacker-controlled payloads and to chain them together through virtual functions that are already present in the target application or in loaded libraries.
Each virtual function contained in a counterfeit object is called a vfgadget and is responsible for performing a small task. Similarly to ROP, vfgadgets can perform tasks like populating a value into a register. However when grouped together, multiple vfgadgets can execute more advanced operations, like API invokation.

### Contents

This repository contains the following:

* **COOP_PoC**: A proof-of-concept application that demonstrates  Counterfeit_Object_Oriented_Programming
* **CVE-2019-0539_COOP**: Exploit for CVE-2019-0539 based on COOP gadgets.
* **COOP.pdf**: Presentation slide deck
