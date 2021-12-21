# Coherent Diffraction Imaging Reconstruction of Gold Superlattice Self-Assembly

## Spring 2021
## in association with the Ginsberg Group

## Background

Understanding how individual constituents of a massive object come together is a problem that spans many disciplines, but is especially prevalent in chemistry and nanoscale physics. In particular, engineering nanoscale photonics through driven self-assembly into custom patterns is a sought after technique.

One interesting example of self-assembly is coating conducting (gold) or dielectric (lead sulfate) nanoparticle lattices approximately 4 nm in size in ion-rich ligands. These particles are colloids that are usually individual in low ion solutions. However, when placed in an ion-rich solution, they are naturally driven to assemble into larger superlattices (since they are now lattices of lattices).

Recently, physical chemists have been able to sizably increase the packing factor of these superlattices and make superlattices with unique conducting properties. By understanding this mechanism, opening the doors of engineering nanoscale objects in solution becomes plausible.

<img src="https://jslivka66.github.io/past_projects/Au_SL_with_planes.png" width="800" />
<figcaption> Real space images of different Gold (Au) superlattices </figcaption>
<br>
<br>

## SLSA

As a rotation student in Naomi Ginsberg's Lab, I became familiar with small angle coherent x-ray experiments and analyzing diffraction pattern data. In particular, we attempted to do Coherent Diffractive Imaging Reconstruction (CDI Reconstruction) to reconstruct real-space images of electron density from the diffracted pattern. This was only one aspect of a project which also included designing an apparatus that could test these assembled particles, stabilizing the particles sufficiently in a capillary, and then training a beam onto these less than micron sized particles to see diffraction data.


## Techniques

In order to study real-time self-assembly in a solution, one is required to perform complicated beamline experiments. Direct light microscopy is ill-fitted to observe nanometer sized structure due to diffraction limited resolution. However, X-rays are photons with the correct wavelength characteristics to observe the intrasuperlattice spacing, but in its diffraction pattern. Then, using these diffraction patterns

### Scattering Experiments

Using coherent beamlines, such as at the Stanford Linear Accelerator, we were able to see patterns in inverse distance space (known commonly as q-space) and analyze this data to observe particle structure and size. This is a common way to observe structure for countless applications, but has an especially well-formed pattern for infinite, well-spaced crystal structures

### Reconstruction

Scattering due to quantum mechanics as a formalism was developed in the 1920s. Understanding how to go from a real space electron density to the image it forms on a detector in q-space is well-known and can be computed computationally to good precision. This is equivalent to a forward Fourier Transform where what is seen on the detector is the real space projection of this transformation.

The inverse problem, however, is less trivial. Due to the loss of phase information from the forward Fourier Transform, the inverse fourier transform has a loss of information and cannot uniquely find its real-space counterpart. This leads to a common problem in all diffraction experiments known as "the inverse fourier problem".

To solve this problem, one can implement machine learning algorithms to iteratively improve the real space image, see its diffraction pattern, observe how well it matches the actual data, make corrections in the real space image and continue to cycle. Coherent Diffractive Imaging Reconstruction is one of the ways to figure this out.


## Results
