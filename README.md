# Perpetual_training_accademy_avionics
Perpetual is an affordable, easy-to-integrate rocket avionics platform for the Sapienza Rocket Team Training Academy, with a guided UI for configuration and operation without firmware reflashing.


Perpetual was created by Rotellini9809 for the Sapienza Rocket Team Training Academy. Hardware and software are maintained in independently licensed repositories linked as submodules. Hosting this integration repository under Sapienza Rocket Team does not transfer ownership of those projects.



## Licensing

Perpetual contains independently licensed submodules:

- Software: PolyForm Noncommercial 1.0.0.
  See the software repository's LICENSE and NOTICE files.
- Original hardware design files and documentation:
  CC BY-NC-SA 4.0.
  See the hardware repository's LICENSE file.

Each submodule retains its own license.
Third-party materials retain their respective licenses.

## Getting started

Clone this repository together with its submodules:

```sh
git clone --recurse-submodules https://github.com/Sapienza-Rocket-Team/Perpetual_training_accademy_avionics.git
```

For an existing clone, initialize the pinned submodule versions with:

```sh
git submodule update --init --recursive
```

- [perpetual_code](perpetual_code): firmware and desktop application.
- [perpetual_pcb](perpetual_pcb): hardware design files and documentation.
