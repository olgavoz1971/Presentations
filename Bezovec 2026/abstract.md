# A Web-Based Tool for Semi-Automated Batch Timing of Variable-Star Extrema Using Gaussian Process Regression
**Authors:** **Olga Vozyakova** (Presenter), Co-author: V. Marsakova
**Conference:** Bezovec 2026 – Satellite Astronomy, Bezovec, Slovakia
**Date:** 4-6 September 2026

---

### Abstract
Determination of times of extrema is a routine task in variable-star research. O-C analysis based on these timings is an indispensable tool for studying period variations in many types of variable stars, making efficient and convenient timing tools highly desirable. This need has become even more important with the advent of space missions such as TESS, which provide long-term, high-cadence photometric time series.

We present a new web tool for rapid timing of variable-star extrema using Gaussian Process regression. GP regression provides a flexible probabilistic model for fitting light curves while taking observational uncertainties into account. It can naturally deal with uneven sampling, gaps and complex light-curve shapes. 

This makes it suitable for a wide range of variable-star light curves, including precise and well-defined eclipses in eclipsing binaries as well as asymmetric and evolving superhump profiles in cataclysmic variables. The method can be applied to both densely sampled, high-precision space-based photometry and sparse, unevenly sampled, noisy ground-based observations. 

The tool models a selected fragment of a light curve and determines the time of a minimum or maximum together with its uncertainty. For periodic variables, fragments containing extrema can be selected on the folded light curve in a single step. Once the model has been adjusted by the user for a particular time series, it can be applied automatically to all cycles, providing batch determination of extrema timings. 

We applied this method to determine the minima of several eclipsing binaries and the superhump maxima of a WZ Sge-type dwarf nova. 
While specialised interactive software such as MAVKA may provide higher precision for high-quality light curves, our method requires considerably less user interaction and manual work and has proven effective in approximating asymmetric and complex-shaped extrema.
