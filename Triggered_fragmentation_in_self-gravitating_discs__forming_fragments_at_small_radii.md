**[Title]**

Triggered fragmentation in self-gravitating discs: forming fragments at
small radii

**[Complete Citation.] (Author(s), Date of publication,
Title (book or article), Journal, Volume #, Issue #, pages:**

Meru, F. (2015). Triggered fragmentation in self-gravitating discs:
Forming fragments at small radii. *Monthly Notices of the Royal
Astronomical Society*, *454*(3), 2529--2538.
https://doi.org/10.1093/mnras/stv2128

**[If web access] url; date accessed:**

https://arxiv.org/abs/1509.03635

**[Key Words]:**

Accretion; Accretion discs; Gravitation; Hydrodynamics; Instabilities;
Planets and satellites: formation; Protoplanetary discs

**[General subject:]**

-   SPH simulations

-   Gravitationally unstable discs

-   Movement of mass in fragmenting discs

**[Specific Subject:]**

Fragmenting gravitationally unstable protoplanetary discs

Fragmentation in outer regions causes subsequent fragmentation in the
inner regions

**[Hypothesis / Question:]**

In a gravitationally unstable disc, can fragmentation in the outer
regions of the disc cause a subsequent secondary fragmentation in the
inner regions of the disc?

**[Methodology:]**

SPH simulations using flux limited diffusion to model the transfer of
radiation.

Artificial viscosity is used to model shocks but they don't seem to use
a 'switch' to turn down the viscosity away from shocks

αSPH and βSPH are set to 0.1 and 0.2, they seem low. I have only ever
seen them set to 1 and 2.

Sink particles replace fragments when they reach a critical density of
7-9e-6 g/cm3

Radius of disc is 100 AU and the surface density follows power law with
exponent -3/2 between R = 1 AU and 100 AU

Sort of low resolution with 250,000 particles -- this is because they
are less concerned with the fragmentation itself, just the dynamics.

Very high mass disc uses, presumably to ensure fragmentation: 1.1 solar
mass disc around a 1.5 solar mass star and a 0.9 solar mass disc around
a 1 solar mass star.

This disc setup means that the lowest value of toomre Q is 0.75 and 0.7
in simulation 1 and simulation 2 respectively. The viscous heating does
increase Q throughout the simulations.

**[Result(s):]**

-   Mass moves inwards following the formation of the first fragment

-   Disc is more dynamic with radial velocities \~10 times higher than
    before fragmentation

    -   This causes mass to accumulate in inner regions, decreasing Q
        and causing fragmentation

-   Following the formation of the first fragmentation, the inner spiral
    density increases and Q decreases to Q \< 1 at \~ 24 AU.

**[Summary of key points:]**

**[Context] (how this article relates to other work in the
field):**

**[Significance] (to work in the field, to my own work):**

**[Importance Figures/Tables] (Brief description and page
number):**

**[Cited references to follow up on:]**

**[Other Comments:]**
