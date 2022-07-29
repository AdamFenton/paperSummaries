**[Title]**

Planet Migration in Self-Gravitating Discs: Survival of Planets

**[Complete Citation.] (Author(s), Date of publication,
Title (book or article), Journal, Volume #, Issue #, pages:**

Rowther, S., & Meru, F. 2020, 13, 1

**[If web access] url; date accessed:**

<http://arxiv.org/abs/2006.03077>, accessed 8^th^ June 2020

**[Key Words]:**

hydrodynamics; planet-disc interactions; protoplanetary discs

**[General subject:]**

3D SPH simulations

Self gravitating protoplanetary discs

Planet migration in discs

**[Specific Subject:]**

Planets forming in the early stages of disc lifetimes while they are
still massive and self gravitating can survive

Rapid initial inward migration of planets for both low and high mass
planets ( \< Mnep and \> Msat respectively)

**[Hypothesis / Question:]**

Do planets have the ability to slow their migration to the inner stable
part of the disc, irrespective of how they form?

**[Methodology:]**

PHANTOM is used for the SPH simulations with mostly 2e6 particles with a
few using 1e6 and 4e6 to ensure consistency across resolution.

Artificial viscosity using Cullen and Dehnen switch, αmax = 1 αmin = 0
and β = 2

Disc to star mass ratio of 0.1

Cooling timescale set to Gammie beta t_cool = βΩ\^-1

Two cooling implementations, one with β varying with radius and another
with β set to a constant value of 15 equivalent to α = 0.027. This means
that the inner regions avoid being gravitationally unstable by cooling
slowly and the outer regions cool quickly enough to be unstable and form
spiral structure.

Planet is embedded at R=20, planets have different masses. See section
2.4

**[Result(s):]**

Disc with constant β shows spiral structure first, from the inside first
and then throughout the disc

Disc with variable β only shows spiral structure in the outer regions.
The cooling time in the inner region is much larger. The disc cooling is
inefficient in the inner regions meaning that the temperature are much
higher.

A giant planet inserted at 20 radius units reaches the inner disc within
a few orbits. When β varies, the migration inwards slows down inside the
gravitationally stable part of the disc

Stochastic kicks increase with decreasing planet mass.

Lower mass planets migrate slower than the giant planets but show now
signs of slowing down in the constant β runs.

With variable β, the low mass planets show very little migration inwards
and in the case where migration exists it is significantly slowed in the
inner regions

**[Summary of key points:]**

The use of a radially decreasing β parameter that ensure that the inner
regions of the disc are gravitationally stable while the outer regions
are not shows that inward migration of planets is slowed upon reaching
the gravitationally stable region without a gap opening.

Planets may be able to survive inward migration in self-gravitating
discs

**[Context] (how this article relates to other work in the
field):**

Development of cooling treatment to mimic more realistic discs

Relation to observations of planet forming discs like HL Tau which is
placed in the gravitationally unstable regime beyond 50 AU

**[Significance] (to work in the field, to my own work):**

Any planets that form in my simulations may go through a period of
inward migration as shown in this work and when I start looking at
radiative transfer maybe I should entertain the idea of a variable β

**[Importance Figures/Tables] (Brief description and page
number):**

Figure 1, page 3, Comparison of cooling times based on two treatments of
β

Figure 3, page 4, Temp and Toomre Values as a function of radius

Figure 5, page 5, Column density plots of their discs at certain orbital
times

**[Cited references to follow up on:]**

**[Other Comments:]**
