# Introduction to Ion:
---

Welcome, Devs!

As I am aware that the `README.md` file wasn't enough for anyone ti understand the basics of Ion.
The `/Tutorials/` Folder exists to contain all the Tutorials required for you to understand Ion.




# 📁 Ion File Extensions

This section lists **all file extensions that are native to the Ion ecosystem**.  
These files exist specifically because of Ion and are interpreted or produced by Ion tooling.

---

## 🔹 Source & Definition

### `.ion`
- Core Ion source file
- Used for:
  - Modules
  - Packages
  - Namespaces
  - Classes
- Parsed by the Ion compiler
- Compiles into `.ibc`

---

## 🔹 Intermediate & Compiled Output

### `.ibc` *(Ion ByteCode)*
- Compiled output of Ion source
- Executed by the Ion Runtime / IER
- Architecture-neutral (x64 runtime target)

---

## 🔹 Libraries & Binaries

### `.ilib`
- Ion library binary
- Used for:
  - Libraries
  - Engines
  - Framework components
- Loaded by the Ion Runtime
- Ion’s equivalent of shared binaries

---

## 🔹 Project & Build

### `.iprj`
- Ion project definition file
- Defines:
  - Project-wide configuration
  - VM targets
  - Entry modules
- A project may contain multiple modules

---

## 🔹 Assembly & Conversion

### `.assembly`
- Ion assembly definition file
- Describes how `.ibc` files are grouped
- Used to convert bytecode into:
  - `.ilib`
  - native executables
- Does **not** represent a project or package

---

## 🔹 Framework & Runtime Control

### `.isf` *(Ion Stabilization Framework)*
- Framework execution descriptor
- Interpreted by the Ion framework runtime (`skeleton.exe`)
- Controls stabilized and managed execution

---

## 🧠 Core Principle
> Every Ion source or definition file ultimately exists to produce **`.ibc`**.  
> `.ibc` is the single execution truth of the Ion ecosystem.



# Compatibility

---

- ### [Linux](https://www.kernel.org)
- ### [Windows](https://www.microsoft.com/windows)
- ### [Android](https://www.android.com) (via Linux kernel-based runtime support)

> Additional platforms may be supported as the runtime evolves.
