# NTN Interference Nulling

This repository contains Python simulations for satellite NTN (Non-Terrestrial Network) interference nulling.

## Python Simulations
### Equation Verification
- **`verify_equations.ipynb`**: Verified equations (20), (21), and (54).

### Sionna-Based Simulations
- **`random_add_multi_ntnue.ipynb`**: Randomly adds NTN-UEs around the transmitter based on distance and SNR range.
- **`Sionna_simu_with_3ntn_ue.ipynb`**: Simulation setup with:
  - One transmitter (Tx)
  - Three terrestrial UEs (T-UEs)
  - Three NTN-UEs
  - Channel estimation and beamforming

- **Scene Loading**: Use `denver.xml` to load the simulation scene.

## Blender Files
- **`denver.blend`** and `meshes/`: Open in Blender to visualize locations.

