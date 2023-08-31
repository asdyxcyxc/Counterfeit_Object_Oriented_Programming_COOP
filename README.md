# Counterfeit Object Oriented Programming (COOP)

## Abstract

The main idea behind COOP is counterfeiting – that is crafting new objects in-memory from attacker-controlled payloads and to chain them together through virtual functions that are already present in the target application or in loaded libraries.
Each virtual function contained in a counterfeit object is called a vfgadget and is responsible for performing a small task. Similarly to ROP, vfgadgets can perform tasks like populating a value into a register. However when grouped together, multiple vfgadgets can execute more advanced operations, like API invokation.

More information about COOP technique can be found [here](https://www.matteomalvica.com/blog/2022/09/22/bypassing-intel-cet-counterfeit-objects)

## Contents

This repository contains the following material:

* **COOP_PoC**: A proof-of-concept application that demonstrates  Counterfeit_Object_Oriented_Programming
* **CVE-2019-0539_COOP**: Exploit for CVE-2019-0539 based on COOP gadgets.
* **COOP.pdf**: Presentation slide deck
* **demos**: a few demo videos of the PoC application and the MS Edge CVE


## Demos

Triggering Shadow Stack:
https://github.com/uf0o/Counterfeit_Object_Oriented_Programming_COOP/assets/24236867/2224424a-994d-4c11-96b4-ec915df08c31


CVE-2019-0539:
https://github.com/uf0o/Counterfeit_Object_Oriented_Programming_COOP/assets/24236867/c8165417-d6c9-4206-8ce8-38c061a7e015

