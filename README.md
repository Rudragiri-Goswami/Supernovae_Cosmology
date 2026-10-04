# Supernova Cosmology

### Estimating the Hubble Constant Using Type Ia Supernovae

This project uses the **Pantheon+SH0ES** Type Ia supernova dataset to study the expansion of the Universe.

The analysis uses the observed relationship between redshift and distance modulus and fits a **flat ΛCDM cosmological model** to estimate the Hubble constant and matter density parameter.

## Objectives

- Construct the Hubble diagram
- Estimate the Hubble constant ($H_0$)
- Estimate the matter density parameter ($\Omega_m$)
- Compare the estimated $H_0$ with the Planck18 measurement
- Estimate the age of the Universe
- Analyze model residuals
- Compare low-redshift and high-redshift supernovae

## Method

The analysis is performed using:

- Python
- NumPy
- Pandas
- Matplotlib
- SciPy

A flat ΛCDM model is used, with the expansion function

$$
E(z) = \sqrt{\Omega_m(1+z)^3 + (1-\Omega_m)}
$$

The theoretical luminosity distance is used to calculate the distance modulus and fit the observed supernova data.

## Dataset

The project uses the **Pantheon+SH0ES** Type Ia supernova dataset.

The dataset file is included in this repository:

```text
Pantheon+SH0ES.dat
