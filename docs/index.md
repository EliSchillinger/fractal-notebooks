# Fractal patterns in Nature: Self-affinity vs Self-similarity

# Authors

[Tyson Lee Swetnam](https://tysonswetnam.com){target=_blank} [![](https://orcid.org/sites/default/files/images/orcid_16x16.png)](http://orcid.org/0000-0002-6639-7181){target=_blank}
 Institute for Computation and Data-enabled Insight, University of Arizona

 [Jon D Pelletier](http://jdpellet.github.io/){target=_blank} [![](https://orcid.org/sites/default/files/images/orcid_16x16.png)](http://orcid.org/0000-0002-0702-2646) Department of Geosciences, University of Arizona

Brian J. Enquist [![](https://orcid.org/sites/default/files/images/orcid_16x16.png)](http://orcid.org/0000-0002-6124-7096) Department of Ecology and Evolutionary Biology, University of Arizona

# Abstract

Much of the scientific literature describes the fractal-like hierarchical branching networks of vascular organisms as 'self-similar'. Here we examine papers where fractal-like self-similarity is incorrectly described. We also link why the hierarchical branching networks in vascular organisms are 'self-affine' rather than self-similar by linking metabolic scaling theory to these structural traits. Last, we propose a mechanistic theory of fractal dimensions for single cell through multicellular life forms forms. 

In our supplemental materials, we provide empirical explanations for the fractal-like structures of single cell colonies and autotrophs including primitive algae, vascular organisms including lichens and bryophytes, and higher order terrestrial plants. 

We also describe how self-affinity arises in heterotrophs as related to metabolic and circulatory networks.

## Background

Self-similarity is an appropriate term for isometry, where objects scale identically in one or more dimensions, while self-affinity describes allometry, or differential scaling in one or more dimensions. 

The vascular networks of most higher organisms facilitate mass transport as capillary action (in autotrophs) or laminar or pulsatile flow (in heterotrophs) and laminar flow with turbulent motion giving way to diffusion at smaller scale (<200nm). Diffusion is the most efficient mechanism for gas exchange at <200nm, eliminating the need for vascularity.

As an example of self-affine versus self-similar fractal dimensions, we calculated the mass dimension \(d_m\) by differential box counting in both synthetic fractal-like forms resembling plants and real vascular plants using x-ray and visible light photographs of the leaves, branches, and roots of individual organisms. We also calculated the mass dimension of forest-scale tree canopies from remote sensing. 

For leaves, branches, and roots, \(d_m\) was in good agreement with the predictions of Metabolic Scaling Theory (MST), where \(d_m\) is predicted to equal \( \frac{3}{2} \). At the forest level, canopy height models show that \(d_m\) is related to a zeta function \( \zeta^{-s} \), where fractal objects fill available space until they begin to self-thin in relation to their energetic equivalence with locally available free energy.

Our results demonstrate:

1. Dimensional analysis with appropriate self-affine mass dimension shows that many reported fractal dimensions in ecology are either incorrect or inappropriately reported.

2. A technique for testable predictions, including a mechanistic explanation for how individual branching networks grow and fill space and how communities of organisms emerge with fractal dimensions based on MST predictions.

These results may help reveal when communities of individuals have maximized their potential to cycle energy through an ecosystem or when they have been disturbed by exogenous forces.

## 1D, 2D, 3D, and 4D fractal-like patterns

Fractals are intricate patterns that repeat themselves at different scales. They can exist in various dimensions. This introduction provides a brief overview of fractals in one-dimensional (1D), two-dimensional (2D), three-dimensional (3D), and four-dimensional (4D) spaces, along with examples of self-similar and self-affine fractals in each dimension.

### 1D Fractals

#### 1/f Noise (Pink Noise)

##### What Is 1/f Noise?

1/f noise is a signal whose power spectral density (PSD) is inversely proportional to the frequency (f). This means that as the frequency decreases, the power increases, following the relationship:

\[
\text{PSD}(f) \propto \frac{1}{f^\alpha}
\]

where \(\alpha\) is approximately equal to 1 for true pink noise.

###### Fractal Characteristics

- **Self-Similarity**: The signal appears statistically similar across different time scales. Zooming in on a segment of the signal reveals patterns resembling the whole.
  
- **Long-Range Dependence**: Values in the signal are correlated over long time periods.
  
- **Non-Integer Dimension**: The signal has a fractal (non-integer) dimension, quantifying its complexity.

###### Examples in Sound

- **Ambient Noise**: Pink noise is perceived as balanced and soothing because it distributes equal power per octave. It's used in sound masking, tinnitus treatments, and sleep aids.
  
- **Music and Speech**: Elements of music dynamics and speech patterns often exhibit 1/f characteristics, contributing to their natural and pleasing qualities.

##### Examples in Electrical Signals

- **Electronic Components**: Resistors, semiconductors, and other electronic devices exhibit 1/f noise, also known as flicker noise. This can affect the performance of circuits, especially at low frequencies.
  
- **Neural Activity**: Electrical impulses in the brain, measured via electroencephalography (EEG), show 1/f spectral properties, indicating fractal-like neural dynamics.

---

#### Fractional Brownian Motion (fBm)

##### What Is Fractional Brownian Motion?

Fractional Brownian motion is a generalization of standard Brownian motion that includes memory and persistence. It is characterized by the **Hurst exponent (H)**, which determines the degree of self-similarity and long-range dependence.

#### Fractal Characteristics

- **Self-Affinity**: The statistical properties are preserved under anisotropic scaling of time and amplitude.
  
- **Hurst Exponent**: A value of \( H > 0.5 \) indicates persistence, while \( H < 0.5 \) indicates anti-persistence.

#### Applications

- **Heart Rate Variability**: The intervals between heartbeats can display fractal patterns modeled by fBm. Healthy heart rhythms often exhibit fractal characteristics.
  
- **Financial Markets**: Stock prices and market indices can be modeled using fBm to account for long-range dependencies and volatility clustering.
  
- **Telecommunications**: Network traffic often shows self-similar patterns over time, impacting network design and performance.

---

#### Why Are Signals Fractal?

Fractal signals like 1/f noise and fractional Brownian motion are considered fractal because they exhibit patterns that are consistent across different scales of observation. This property is known as **statistical self-similarity**.

- **Scaling Behavior**: The signals maintain their statistical properties under scaling transformations.

- **Complexity**: The fractal dimension quantifies the complexity and irregularity of the signal, which is greater than that of a simple, smooth signal.

---

#### Visualization

Imagine recording the sound of ocean waves:

- **Long Observation**: Over several minutes, you hear the rise and fall of waves.

- **Short Observation**: Zooming into a few seconds, the smaller ripples mimic the larger wave patterns.

- **Signal Analysis**: Plotting the amplitude over time reveals a waveform with self-similar patterns at different time scales.

---

#### Practical Implications

- **Engineering**: Understanding 1/f noise is crucial for designing low-noise electronic circuits and improving signal processing techniques.
  
- **Medicine**: Fractal analysis of physiological signals like heart rate and neural activity can aid in diagnosing health conditions.
  
- **Music Production**: Pink noise is used to test and calibrate audio equipment due to its balanced frequency distribution.

## 2D Fractals


### Fractional Brownian Surfaces (fBs)

#### What Are Fractional Brownian Surfaces?

Fractional Brownian surfaces are two-dimensional generalizations of fractional Brownian motion, representing surfaces whose elevations vary in a statistically self-similar way across different spatial scales. They are used to model natural terrains and textures that exhibit fractal characteristics.

### Fractal Characteristics

- **Self-Affinity**: The surface's statistical properties are preserved under anisotropic scaling, where spatial dimensions (x and y) and the elevation (z) are scaled by different factors.
- **Hurst Exponent (H)**: Determines the roughness or smoothness of the surface. A higher H results in a smoother surface, while a lower H leads to a rougher one.
- **Fractal Dimension (D)**: Given by \( D = 3 - H \), it quantifies the complexity of the surface. A higher fractal dimension indicates a more complex surface.

### Examples in Natural Images

- **Terrain and Landscapes**: Elevation maps of mountains and valleys often display fractal properties, where smaller hills resemble larger mountain structures.
- **Cloud Formations**: Satellite images of clouds show patterns that are statistically similar across different scales.
- **Coastlines**: The intricate patterns of coastlines can be modeled using fractional Brownian surfaces, capturing their fractal nature.

---

## Why Are These Surfaces Fractal?

Fractional Brownian surfaces are considered fractal because they exhibit **statistical self-affinity** across scales:

- **Scaling Behavior**: If you zoom into a portion of the surface and appropriately rescale the axes, the surface's statistical properties remain consistent.
- **Complexity**: The surfaces have a non-integer fractal dimension, filling space more than a flat plane but less than a full volume.

---

## Visualization

Imagine creating a digital elevation model for a landscape:

1. **Initial Generation**: Start with a grid representing the surface.
2. **Applying fBs**: Use algorithms that introduce fractional Brownian motion to assign elevation values, controlling roughness with the Hurst exponent.
3. **Resulting Surface**: The generated surface displays hills and valleys with patterns that look similar, regardless of the scale at which you observe them.

![Fractional Brownian Surface](https://upload.wikimedia.org/wikipedia/commons/7/70/Fractional_Brownian_Surface.png)

*An example of a fractional Brownian surface displaying self-affine fractal properties.*

---

## Applications

### Computer Graphics

- **Terrain Generation**: Used in video games and simulations to create realistic landscapes.
- **Texture Synthesis**: Generates natural-looking textures for objects and environments.

### Geographical Analysis

- **Satellite Imagery**: Analyzing landforms and geological structures using fractal dimensions.
- **Environmental Monitoring**: Studying patterns of vegetation, deforestation, or urban development.

### Medical Imaging

- **Tissue Analysis**: Fractal analysis helps in characterizing complex structures in biological tissues, aiding in diagnostics.
- **Bone Structure**: Evaluating the fractal nature of bone trabeculae can assist in osteoporosis research.

---

### Fractal Analysis Techniques

#### Box-Counting Methods

- **Process**: Overlay a grid of boxes over the image and count the number of boxes that contain part of the structure.

- **Scaling**: Repeat with different box sizes to see how the count changes.

- **Fractal Dimension**: Calculated based on how the number of occupied boxes scales with the box size.

#### Power Spectral Density (PSD)

- **Frequency Analysis**: Transform the image into the frequency domain to analyze the distribution of spatial frequencies.

- **Scaling Laws**: The PSD often follows a power law, indicative of fractal behavior.

---

## Practical Implications

### Engineering and Design

- **Surface Roughness**: Understanding the fractal nature of surfaces can improve material design and coatings.

- **Antenna Design**: Fractal-shaped antennas can operate efficiently over multiple frequency bands.

### Environmental Science

- **Erosion Patterns**: Modeling soil erosion and river networks using fractal geometry.

- **Climate Modeling**: Analyzing cloud patterns and atmospheric turbulence.

### Art and Aesthetics

- **Fractal Art**: Creating visually appealing images using fractal algorithms.

- **Texture Mapping**: Enhancing visual realism in digital art and animations.

---

### Understanding Self-Similarity and Self-Affinity in 2D Fractals

- **Self-Similar Fractals**: Patterns repeat exactly at different scales. Example: Sierpinski Carpet.
  
- **Self-Affine Fractals**: Scaling factors differ across axes. Natural terrains are self-affine because the vertical scale (elevation) and horizontal scales (latitude and longitude) scale differently.

---

### Example: Analyzing Satellite Images

#### Steps

1. **Data Acquisition**: Obtain high-resolution satellite images of a geographical area.
2. **Preprocessing**: Convert images to grayscale and normalize.
3. **Fractal Analysis**: Apply box-counting or PSD methods to calculate the fractal dimension.
4. **Interpretation**: Use the fractal dimension to infer characteristics like terrain roughness or vegetation density.

#### Insights

- **Urban vs. Natural Areas**: Urban regions may have different fractal dimensions compared to natural landscapes due to human-made structures.

- **Environmental Changes**: Changes in fractal dimension over time can indicate deforestation, desertification, or urban expansion.

### 3D Fractals

### 4D Fractals


# Applications

We have created interactive [example applications](tree_roots.md) written in Python which simulate and generate fractal like structures that can run as stand-alone applications in your web browser.

These applications allow you to calculate fractal dimensions of binary and scalar imagery, to interact with fractal like structures, and to upload and analyze your own data.

## Jupyter Notebooks

We provide a set of example [Jupyter Notebooks](notebooks/fractal_generators.ipynb) demonstrating dimensionality of fractal-like behavior in nature.

For all of our equations and figures, we provide example notebooks which use publicly available data and open source code .