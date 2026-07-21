---
description: 'The point in the piston stroke at which steam admission to the cylinder is closed, after which the steam already admitted continues to expand.'
id: cut-off
label: Cut-off
tags: ["steam", "valve-gear", "expansion", "thermodynamics", "engine-efficiency"]
type: concept
---

**Cut-off** is the closing of steam admission to the [[cylinder]] before the [[piston]] has completed its full stroke, allowing the steam already admitted to expand and perform additional work. Cut-off is the essential mechanism for achieving [[expansion-valve|expansive working]] in the [[steam|steam engine]], enabling a given mass of steam to produce more work than it would if admitted at full boiler pressure throughout the entire stroke. The point of cut-off — expressed as a fraction of the stroke (e.g., one-third, one-half, two-thirds) — is the single most important adjustment governing engine efficiency.

## Principle of expansive working

When steam is admitted to the cylinder for only a portion of the stroke and then cut off, the steam expands as the piston continues to move, its pressure falling according to Boyle's law (or approximately so). This expansion extracts additional work from the steam without consuming additional fuel:

> [015-078] From the length of the stroke of the piston subtract that part of the stroke which is intended to be accomplished before the steam is cut off; divide the remainder by the length of the stroke of the piston, and extract the square root of the quotient, which multiply by half the stroke of the valve, and from the product take half the lead; the remainder will be the lap required. (015-082)

The earlier the cut-off, the greater the degree of expansion — and the greater the economy of steam. But earlier cut-off also reduces the mean effective pressure on the piston, so an engine designed for high expansion must be proportionately larger to deliver the same power.

## Practical limits of fixed cut-off

With a plain [[slide-valve]] having a fixed [[lap]], the cut-off point is determined by the geometry of the valve and cannot be altered while the engine is running. [[john-bourne|Bourne]] indicates that practical limits constrain how much lap can be applied:

> [015-125] To about one-third of the stroke; that is, the valve may be made with so much lap, that the steam will be cut off when two thirds of the stroke have been performed, leaving the residue to be accomplished by the agency of the expanding steam; but if more lap be put on than answers to this amount of expansion, a very distorted action of the valve will be produced, which may impair the efficiency of the engine. (015-128)

Thus with a simple [[slide-valve|slide valve]], the earliest achievable cut-off is at about two-thirds of the stroke — meaning the steam expands through only the final one-third of the stroke. Greater expansion requires a separate [[expansion-valve|expansion valve]].

## Methods of achieving variable cut-off

Beyond the fixed cut-off of a simple [[slide-valve|slide valve]], several mechanisms were developed to vary the cut-off point dynamically:

### Link motion

The [[link-motion]], invented by William Williams and improved by Robert [[george-stephenson|Stephenson]], uses two [[eccentric|eccentrics]] connected by a slotted link. By shifting the link relative to the die block, the engine driver can continuously vary the cut-off point from full gear (latest cut-off, maximum power) to mid-gear (earliest cut-off, maximum economy):

> [016-104] The eccentric is partially turned round so as to cut off the steam at a desired fraction of the stroke. (016-104)

The link motion became standard on locomotives and many [[marine-engine|marine engine]]s, offering forward and reverse operation with variable expansion from a single lever.

### Separate expansion valve

For engines requiring very early cut-off — such as Cornish pumping engines, where steam could be cut off at one-twelfth of the stroke — a separate expansion valve was employed:

> [015-153] In the Cornish engines, where the steam is cut off in some cases at one-twelfth of the stroke, a separate valve for the admission of steam, other than that which permits its escape, is of course indispensable. (015-155)

The expansion valve sits between the steam pipe and the main valve, closing independently at the predetermined point regardless of the main valve's position.

### Governor-controlled cut-off

In some engines, the [[governor]] was connected not to a [[valve|throttle valve]] but to the cut-off mechanism, varying the point of cut-off automatically in response to load changes. This is thermodynamically superior to throttling:

> [060-085] With a well-regulated cut-off, practical men know now that the best means of producing a uniform velocity with a varying resistance is not by throttling the steam, but by cutting it off at the proper point. (060-085)

## Indicator diagram and cut-off

The point of cut-off is clearly visible on an [[indicator|indicator diagram]] as the transition from the near-horizontal admission line to the descending expansion curve. The steepness of the expansion curve reveals whether cut-off occurs early or late, and the area enclosed by the diagram represents the work performed per stroke. In a well-adjusted engine:

> The indicator diagram shows at a glance the pressure of the steam at every point of the stroke, the point of cut-off, and the character of the expansion. (018-168)

## See also

- [[expansion-valve]] — separate valve for very early cut-off
- [[link-motion]] — mechanism for variable cut-off in locomotives
- [[lap]] — determines the fixed cut-off point in [[slide-valve]] engines
- [[governor]] — may be connected to vary cut-off automatically
- [[indicator]] — instrument that records the cut-off point on a diagram
- [[slide-valve]] — the valve whose motion determines the cut-off
