---
description: 'The pump that forces feed water into the boiler against the steam pressure within, replacing water lost as steam and maintaining a safe water level.'
id: feed-pump
label: Feed Pump
tags: ["steam", "mechanics", "engineering", "boiler", "concept"]
type: concept
---

# Feed Pump

The **feed pump** is a pump that supplies water to the [[Boiler|boiler]] to replace the water that has been evaporated into steam. (014-043) It must force water into the boiler against the pressure of the steam already generated, which in high-pressure engines can be substantial. (014-048)

## Required Capacity

The capacity of the feed pump must exceed the theoretical consumption of water by the engine, because practical losses from leaks, priming, and other irregularities demand a larger margin. (014-045) In low-pressure engines the feed pump is sized according to a standard rule, but this rule must be adjusted for higher pressures and for engines where boiling or very hot feed water is employed. (014-051) (014-065)

> "The feed pump should be able to supply the boiler with a much larger quantity of water than is evaporated in the engine, as, from leaks, priming, or other disarrangements, the feed pump is liable to occasional interruptions in its action." (014-043) (014-045)

When water is supplied very hot or near the boiling point, the feed pump requires additional size to compensate for the reduced density and the tendency of hot water to flash into steam on entering the pump barrel. (014-063) (014-069)

## Sizing Rules

| Engine Type | Feed Pump Capacity Rule |
|-------------|------------------------|
| Low-pressure, [[double-acting|single-acting]] pump + [[double-acting|double-acting engine]] | [[cylinder|Cylinder]] capacity ÷ 4,800 = pump capacity in cubic inches (027-120) (027-121) |
| Double-acting pump or [[double-acting|single-acting]] engine | Halve the quotient from the standard rule (027-122) |
| High-pressure | Apply a multiplier based on pressure ratio |
| Hot feed water | Increase size further beyond theoretical (014-069) |

The capacity of the feed pump was stated as 1/240th of the cylinder capacity at standard pressure, but this fraction does not remain constant at all pressures. (027-102) (027-107) At higher pressures the steam occupies a smaller volume, and the feed pump may be slightly smaller relative to the cylinder, though in practice the opposite is often required to ensure reliable supply. (027-111)

## Construction and Operation

The feed pump is typically a reciprocating plunger pump driven by an eccentric on the main shaft or by a connection from the cross-head. (025-065) When the engine is running and the pump plunger retracts, water is drawn in through a suction valve; when the plunger advances, the water is forced past a delivery valve into the boiler against the boiler pressure.

If the feed pump fails or cannot keep pace, the water level in the boiler falls, and parts exposed above the water may become red hot. (023-173) In such a case water thrown onto the overheated surfaces by the restored action of the feed pump can cause violent and dangerous steam generation. (025-065)

## Operational Hazards

A reliable feed pump is critical to boiler safety. A feed pump that is too small to maintain the water supply can lead to the boiler crown becoming uncovered — one of the most frequent causes of boiler explosions in early steam practice. For this reason [[john-bourne|Bourne]] recommends making the feed pump "very much larger than theory requires" as a safety margin. (014-069)

## See Also

- [[Boiler]] — the pressure vessel supplied by the feed pump
- [[Air-Pump]] — removes condensate and air from the [[condensation|condenser]], complementary to the feed pump
- [[Condensation]] — the condensing cycle that the feed pump completes by returning water
- [[Safety-Valve]] — protects the boiler if water supply fails
- [[Steam]] — the working fluid whose loss the feed pump replaces
