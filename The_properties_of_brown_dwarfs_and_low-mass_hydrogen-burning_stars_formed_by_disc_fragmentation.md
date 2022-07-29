**[Title]**

**[﻿]**The properties of brown dwarfs and low-mass
hydrogen-burning stars formed by disc fragmentation

**[Complete Citation.] (Author(s), Date of publication,
Title (book or article), Journal, Volume #, Issue #, pages:**

Stamatellos, D., & Whitworth, A. P. 2009, Mon Not R Astron Soc, 392, 413

**[Key Words]:**

Accretion; accretion discs; Hydrodynamics; Methods: numerical; Radiative
transfer; Stars: formation; Stars: low-mass; brown dwarfs

**[General subject:]**

Investigating the properties of the objects that form by disc
fragmentation in gravitationally unstable discs.

Comparison with observations of BDs and low mass hydrogen burning stars
(HBs)

Expected observations of fragmented discs in the first 100-300 years

Investigate the formation of BDs:

> Focusing on the formation by disc instability

**[Specific Subject:]**

-   Description of how object formation by disc fragmentation offers and
    explanation of the BD desert

-   How robust a mechanism disc fragmentation is for the formation of
    BDs

**[Hypothesis:]**

Evidence exists that BDs form differently from HBs as evidenced by the
brown dwarf desert

A large number of brown dwarfs are formed by disc fragmentation of the
massive, discs around solar like stars and that these discs should be
frequent but rarely observed due to the fact that they fragment rapidly.

**[Methodology:]**

Use of an SPH method using DRAGON code following the disc evolution
until 70-80% of the disc mass has been accreted onto the central star or
onto stars forming in the disc Note that the term star refers to any
object that is pressure supported and formed by gravitational
instability on the dynamical time scale. (Roughly 20 kyrs)

Time dependant viscosity scheme with alpha = 0.1 and beta = 2\* alpha
with active Balsara switch.

Sink particles are created when the density of a concentration exceeds
the critical density of e-9 gcm-3 and accrete particles that are within
1 au of the sink

The radiative transfer equation is not solved in this method
(computational expense) but Stamatellos et al (2007a) approximation is
used and performs well.

The gas is assumed to be a mix of hydrogen and helium

12 simulations are run, 10 with 150,000 particles, 1 with 250,000
particles and the final one with 400,000 particles to check convergence.
Each simulation is started with the same star and disc with the only
difference being the random seed used to construct the discs

**[Result(s):]**

The discs are initialised as unstable with Q = 0.9 so spiral arms form
and material is swept into dense concentrations. In the 12 simulations
96 stars form, with 67% being brown dwarfs, typically with R\>100 AU.

The planetary mass stars (PMs) (3% of the formed objects) form farthest
from the star.

Fragmentation starts at approx. 2 kyr which is around ¼ of a rotational
period, the stars condense out on the dynamical timescale meaning the
star formation occurs faster in the inner disc, these have longer to
accrete, having being born first, and end up at HBs with masses up to
200 Jupiter masses. The BDs and PMs form at later times and further from
the central star.

70% of the stars formed have masses below the Hydrogen burning limit and
3% of them are below the Deuterium burning limit with the distribution
of masses peaking around 30-40 Jupiter masses dropping to a lower limit
of star formation of 5 Jupiter masses. This cannot be compared to a
normal IMF due to it being the result of a specific simulation.

Stars are most likely to form being 100 and 200 au from the central
object with fragmentation being squashed in the inner regions where
though there is sufficient mass, the cooling tile is too long and the
stars are sheared apart, the far out regions where cooling time is
shorter, the mass is far less so fragmentation is supressed. The regions
between 100 and 200 au are the best of both worlds **[(for this
disc)]**

BD are mostly outside of 100AU while HB are mostly inside 100AU

By 200,000 years most of the BD have been ejected, those that remain are
on wide orbits - Provides an explanation for the brown dwarf desert;
interactions between stars tend to push more massive ones inwards and
less massive ones outwards.

Only one of the 12 simulations had a close BD companion at the end of
the simulations thereby implying that it is approx. 12 times more likely
for a close companion of a solar like star to be a HB rather than a BD
which is reflected in the observations which suggest that fewer that 0.5
% of sun like stars have a close BD companion within 5 AU.

BD are dominant from 400 to 10,000 AU

Discussion of the discs around the formed objects in §5.5, see relevant
paper summary

MAR on to BD is e-6 solar mass per year which is high compared to the
MAR of observed BD but this value is in the first 15kyrs where MAR is
inherently higher. The MAR may have periodic variation due to the
eccentricity of the BD orbit -- **Figure 11**

PMs can be formed by disc fragmentation but their fraction is low

**[Summary of key points:]**

Disc fragmentation is a viable mechanism for the formation of BDs and
PMS with a large proportion forming this way

Hot jupiters are unlikely to form via disc fragmentation

Objects formed by the fragmentation often have their own accretion
discs.

Brown dwarf desert means that BDs that are not ejected orbit outside of
200 AU

Stars forming further in migrate inwards to closer final orbits, the
reverse is true for those forming in the outer disc and they have the
potential to be ejected.

**[Context] (how this article relates to other work in the
field):**

Provides evidence for the brown dwarf desert being the results of
formation by disc fragmentation

Simulations here show objects that form by disc fragmentation have their
own accretion discs around them

One of the simulations performed here shows a warped disc which, though
rare, have been observed. They require a violent interaction between a
spiral arm and a star that is to be ejected

**[Significance] (to work in the field, to my own work):**

The simulations used here were used in the Stamatellos et al (2015)
paper to investigate the properties of the discs around objects formed
by disc fragmentation.

Provides good idea of what sort of values for masses, semi major axes
etc that I should be expecting in my own work.

**[Importance Figures/Tables] (Brief description and page
number):**

Figure 1, page 5 (417 of volume) -- snapshots of simulation with 0.7
solar mass star and 0.7 solar mass disc

Figure 3, page 6 -- Final mass and formation radius of the stars that
formed in the sims and a function of formation time.

Figures 8 and 9, page 9 -- Disc masses and size distributions

**[Cited references to follow up on:]**

**[Other Comments:]**

This is a long paper and fairly exhaustive in its detail so it is worth
a full read rather than just these brief points
