# NTN Interference Nulling

- **`SNR_Baseline_nt*nr_section.ipynb`** CDF curves for:
- INR SNR with BS Beamforming to terrestrial UEs,
- INR SNR with BS Beamforming to nulling interference on ntn-UEs with h^ntn,
- INR SNR with BS Beamforming to nulling interference on ntn-UEs with h^ntn_hat

## Baseline:
- **`VSAT_ant.ipynb`** shows the vsat antenna patters
- **` Baseline_CDF.ipynb`** can get the scene use geo2sigmap in code

## Detection:
- **`.xml`** and map files are in Denver file
- **` detection probability.ipynb`** and **` detection probability_CDF.ipynb`** are for detection


This repository contains Python simulations for satellite NTN (Non-Terrestrial Network) interference nulling.

- Only need to run **`OFDM_Channel_add_users.ipynb`** with denver file
- **`OFDM_Channel_CFD.ipynb`** to generate CDF curve


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
  

