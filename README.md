# LiDAR-Based Pose Initialization Dataset for Spinning Spacecrafts

This repository contains the datasets used in the paper:

**Recurrent Convolutional Neural Networks for LiDAR-Based Pose Initialization of Spinning Spacecrafts**  
Luca Bechis, Jean-Luc Sarvadon, Petre Ricioppo, Mauro Mancini  
Department of Mechanical and Aerospace Engineering, Politecnico di Torino

---

## Dataset Description

The dataset has been entirely generated from scratch by the authors and is designed for training and evaluating recurrent convolutional neural networks for LiDAR-based pose initialization of spinning spacecraft.

It is composed of two main components:

- **Image Dataset**  
- **Sequence Dataset**

Each dataset includes data from three different spacecraft models:

- **Aquarius**
- **Magellan**
- **NEAR Shoemaker**

The data are provided as compressed archives due to their size (several gigabytes).

---

## Dataset Structure
The dataset is organized as follows:

- `image_dataset.zip` – single-frame LiDAR data
  - `Aquarius/`
  - `Magellan/`
  - `NEAR_Shoemaker/`

- `sequence_dataset.zip` – temporal sequences for recurrent models
  - `Aquarius/`
  - `Magellan/`
  - `NEAR_Shoemaker/`


Each folder contains simulated LiDAR data generated under controlled conditions consistent with the experimental setup described in the paper.

---

## Code Availability (Important)

At the time of publication, this repository provides **only the dataset**.

The **code used to generate the datasets and the simulation environment** will be made publicly available **after the acceptance and publication of the associated article**, in order to ensure full reproducibility of the results.

Once released, the code will be integrated into this same repository.

---

## Citation

If you use this dataset in your work, **cite the associated article**.

### BibTeX (temporary – to be updated upon publication)

```bibtex
@article{BechisLiDAR2026,
  title   = {Recurrent Convolutional Neural Networks for LiDAR-Based Pose Initialization of Spinning Spacecrafts},
  author  = {Bechis, Luca and Sarvadon, Jean-Luc and Ricioppo, Petre and Mancini, Mauro},
  journal = {To appear},
  year    = {2026}
}
```
