---
title: "Introduction to Remote Sensing"
excerpt_separator: "A brief introduction to remote sensing."
last_modified_at: 2021-09-10T16:20:02-05:00
categories:
  - Remote Sensing and Satellite Image Processing
tags:
  - remote sensing
  - electromagnetic radiation
  - band
header:
  image: "https://www.rmets.org/sites/default/files/Depositphotos_51022571_s-2015.jpg"
  caption: "Photo credit: [**Royal Meteorological Society**](https://www.rmets.org/sites/default/files/Depositphotos_51022571_s-2015.jpg)"
---

### Remote sensing

> Remote sensing is the science (and to some extent, art) of acquiring
> information about the Earth's surface without actually being in contact
> with it. This is done by sensing and recording reflected or emitted energy
> and processing, analyzing, and applying that information.

When the energy travels from its source (A) to the target (C), it will come in contact with the atmosphere (B) and then reflect back to hit the satellite (D) through the atmosphere. The satellite has some sensors to record the electromagnetic radiation which is then transmitted to the processing station (E) and is processed into an image. Thus the created image can be interpreted and analysed at (F) to extract information about the target which was illuminated. And ultimately applied to better understand it, reveal some new information, or assist in solving a particular problem.

![remote sensing]({{ site.url }}{{ site.baseurl }}/assets/images/remote-sensing-and-satellite-image/Introduction_to_Remote_sensing/image5.png)

### Electromagnetic Radiation and Spectrum

Electromagnetic radiation consists of an _electrical field (E)_ and _magnetic field (M)_. E varies in magnitude perpendicular to the direction in which the radiation travels and M at right angles to the electrical field as shown in figure.

![remote sensing]({{ site.url }}{{ site.baseurl }}/assets/images/remote-sensing-and-satellite-image/Introduction_to_Remote_sensing/image1.png)

_[Image source](https://depts.washington.edu/cmditr/modules/lum/400px-Emwavepropagation.jpg)_

In remote sensing **wavelength** and **frequency** are of major concern. Understanding the
characteristics of electromagnetic radiation in terms of their wavelength and frequency is
crucial to understanding the information to be extracted from remote sensing data. Wavelength ( $\lambda$ ) is the length of one wave cycle (distance between successive wave crests). Frequency is the number of cycles of wave passing a fixed point per unit time.
The relation between wavelength and frequency is:

$c$ = $\lambda$ \* $v$

where,
$\lambda$ = wavelength ($m$),
$v$ = frequency ($Hz$), and
$c$ = speed of light

### Interaction with the atmosphere

The radiation before hitting the earth and then reflecting has to travel through the atmosphere which has gas and particles. These cause **scattering** and **absorption**.

Scattering occurs when electromagnetic radiation is redirected from its original path by the particles or large gas molecules in the atmosphere. Basically, there are three types of scattering:

**Rayleigh scattering**: occurs when particles are very small compared to the wavelength of the radiation. This causes shorter wavelengths of energy to be scattered much more than longer wavelengths. In fact, the sky appears “blue” during the day due to this as blue (shorter wavelength) scattered more than any other.

**Mie scattering**: occurs when the particles are just about the size as the wavelength of the radiation.

**Nonselective scattering**: occurs when particles are larger than the wavelength of the radiation.

**Absorption** is the other main mechanism that occurs when electromagnetic radiation interacts with the atmosphere. Ozone, carbon dioxide, and water vapour are the three main atmospheric constituents which absorb radiation. As these gases absorb energy in very specific regions of the spectrum, those areas that are not influenced by this absorption, which are useful in remote sensing, are called atmospheric windows.

![remote sensing]({{ site.url }}{{ site.baseurl }}/assets/images/remote-sensing-and-satellite-image/Introduction_to_Remote_sensing/image2.png)

### Radiation - Target Interaction

Radiation that is not absorbed or scattered in the atmosphere interacts with the target object. It can be: absorption, transmission and reflection. Absorption occurs when radiation is absorbed into the target while transmission occurs when radiation passes through a target. Reflection occurs when radiation "bounces" off the target and is redirected. In remote sensing, we are most interested in measuring the radiation reflected from targets.

Some examples are:
_Vegetation_: Chlorophyll strongly absorbs radiation in the red and blue wavelength but reflects green wavelengths. Also the healthy leaves act as excellent diffuse reflectors of near-infrared wavelengths which can be used to classify the vegetation as healthy or not.

![remote sensing]({{ site.url }}{{ site.baseurl }}/assets/images/remote-sensing-and-satellite-image/Introduction_to_Remote_sensing/image6.png)

As we can see in the figure, water and vegetation reflect somewhat similar visible wavelengths but are almost separable in the infrared region.

Similarly if we want to distinguish deciduous and coniferous trees, we would go for the near-IR region as they are separable in that region.

![remote sensing]({{ site.url }}{{ site.baseurl }}/assets/images/remote-sensing-and-satellite-image/Introduction_to_Remote_sensing/image3.png)

### Bands

Like our eyes see colors and detect them, remote sensors gather and store information from a narrow wavelength range, called channels (sometimes band).

**Hyperspectral bands** contain more than 100 bands while multispectral bands have less than 16 bands.

**Panchromatic images**
Panchromatic images are created by combining RGB bands and sometimes infrared channels as well resulting in single band images. Panchromatic images have lower spatial resolution which can be improved by combining with multispectral images. The resulting image is called pansharpened.

Co-Authors: Shital Adhikari and Anil Kumar Shrestha
