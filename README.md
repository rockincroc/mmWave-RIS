# mmWave-RIS
This repository includes code and RIS design for a millimeter-wave RIS paper presented at ACM MobiHoc 2025 "[Practical Design and Orchestration of Frequency-Shifting RIS for NLoS mmWave Sensing](https://dl.acm.org/doi/10.1145/3704413.3764440)".

The folders contain 
1. The MATLAB simulations used to generate the space-time modulation codes. These codes help to shift the frequency of the incident wave in several directions, each at a distinct frequency-shift.
2. The PCB schematic, pick-and-place file, and all intelligent data needed to fabricate and assemble a 1-bit RIS operating in the n260 band (37 to 40 GHz).
3. The CST simulations used to verify the operation of the phase-change created by the RIS elements.

The diodes in use are [MADP-000907-14020x](https://cdn.macom.com/datasheets/MADP-000907-14020x.pdf) from MACOM. 

Please consider citing this paper.
```
@inproceedings{10.1145/3704413.3764440,
  author = {Madnaik, Aadesh and Sundaresan, Karthikeyan},
  title = {Practical Design and Orchestration of Frequency-Shifting RIS for NLoS mmWave Sensing},
  year = {2025},
  isbn = {9798400713538},
  publisher = {Association for Computing Machinery},
  address = {New York, NY, USA},
  url = {https://doi.org/10.1145/3704413.3764440},
  doi = {10.1145/3704413.3764440},
  booktitle = {Proceedings of the Twenty-Sixth International Symposium on Theory, Algorithmic Foundations, and Protocol Design for Mobile Networks and Mobile Computing},
  pages = {91–100},
  numpages = {10},
  keywords = {reconfigurable intelligent surfaces, metasurface, mmwave, radar},
  location = {Rice University, Houston, TX, USA},
  series = {MobiHoc '25}
}
```
