<p align="right">
  <a href="https://jslivka66.github.io/index.html">
    Home
  </a>
</p>

# Project MuSHBRooM: Modulating Steric Height of Kinesin Binding Region of MAP7

## Summer 2021
## in association with the Yildiz Lab

<img src="https://jslivka66.github.io/past_projects/Mario_MuSHBRooM.png" width="240" />
<br>

## Background
Large and oblong cells such as neurons are too large to rely on diffusion, the natural movement of material from areas of high concentration to lower concentration, to transport cargo in the cell. Therefore, eukaryotic cells have a well established intracellular network of microtubules which act as highways for motor proteins to transport cargo. Kinesin is a motor protein that transports out towards the cell periphery and Dynein inwards towards the nucleus.

Biophysics has extensively studied these motor proteins, but there is still a lot of work to be done understanding how these motor proteins interact with the many other proteins that coat the microtubule in the cell. These so-called Microtubule Associated Proteins (MAPs) have shown to both inhibit and enhance select motor proteins. But what are the exact dynamics of these interactions? This is an active question in the field.

## Project MuSHBRooM
My project in association with the Yildiz lab was to understand how changing the height above the microtubule where Kinesin bound to MAP7 may change the dynamics of it walking. By modifying the steric height of the kinesin binding region of MAP7 (MuSHBRooM), this would shed further light onto how Kinesin interacts with native MAP7.

## Techniques

### Protein Design and Purification

Preparing the protein requires creating a specific DNA template, and then expressing protein from this DNA template. Finally, after growing protein in cells, you can harvest the protein and purify it. Both kinesin and MAP7 and all its mutants can be made recombinantly.

### TIRF Microscopy

By preparing microtubules on a coverslip and flowing in kinesin and MAP, you can image these proteins if they have a fluorescent tag using Total Internal Reflection Microscopy (TIRF). Then, using analysis software, one can extract average motility parameters such as average distance traveled, time, and velocity, number of stalls, etc.

<img src="https://jslivka66.github.io/past_projects/500x_JC_Kif-5b_100nM_FL_MAP7_1_MMStack_Pos0_gif.gif" width="700" />
<figcaption> TIRF Image of Kinesin walking on microtubules in vitro </figcaption>
<br>

### FIESTA Analysis

To analyze these movies, we adapted existing single molecule tracking code [FIESTA](https://fusionforge.zih.tu-dresden.de/plugins/mediawiki/wiki/fiesta/index.php/FIESTA) and used handwritten MATLAB scripts to analyze these massive amounts of data. Compared to the previous method of by-hand analysis, this improved analysis efficiency by 1500%.


## Results
