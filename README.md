# NTN Interference Nulling

This repository contains Python simulations for satellite NTN (Non-Terrestrial Network) interference nulling.

## Only need to run **`OFDM_Channel_add_users.ipynb`** with denver file

## Python Simulations
### Equation Verification
- **`verify_equations.ipynb`**: Verified equations (20), (21), and (54).

## Sionna-Based Simulations
- **`Narrow_Channel copy.ipynb`**: Only need denver.xml to run (combined **`data_generate.ipynb`** and **`channest_bf.ipynb`**)

- **`OFDM_Channel.ipynb`**: Simulation with OFDM channels

- **`data_generate.ipynb`**:
  - generated **`channels.pkl`**
  - One transmitter (Tx)
  - Three terrestrial UEs (T-UEs)
  - Three NTN-UEs
  - save the channel info
- **`channest_bf.ipynb`**: 
  - Channel estimation and beamforming

- **Scene Loading**: Use `denver.xml` to load the simulation scene.
- make `denver.xml` and 'meshes' into the same fold and then load

## Blender Files
- **`denver.blend`** and `meshes/`: Open in Blender to visualize locations.
  

