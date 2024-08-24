# BlueBounder

### Grain Boundary Detection and Analysis

Geological researchers study the kinematics of fault and shear zones within the earth's crust. To do this, they must analyze samples of rock samples that have been brought to the surface of the Earth. During the processes involved in fault movement, mineral grains (e.g., quartz) will often recrystallize in such a way as to develop a crystallographic fabric. That fabric can be analyzed in order to understand the mechanics of faulting.

The rock samples are cut and polished into thin slices which are then examined using Electron BackScatter Diffraction (EBSD) on the Scanning Electron Microscope (SEM). Current methods involve using proprietary software, such as Oxford Instruments’ AztecCrystal, to post-process these data; however, these software packages lack certain functionality, such as to fully utilizing both crystallographic and chemical data produced. Specifically, the software neglects to properly segment the quartz domains from its surroundings. 

Therefore, we have created our own pipeline involving image processing from the ground up to analyze both crystallographic and chemical data. This involves employing image morphology operations and graph-based image segmentation. In addition, our desktop application makes the entire process more streamlined and user-friendly while providing features such as image processing, creation, modification, and more. 

---

### To Build:

```bash
git clone --recursive https://github.com/BlueSonoma/BlueBounder.git
cd BlueBounder
npm run build
npm run start:server
npm start
```
