# HASEL — Hydraulically Amplified Self-healing Electrostatic Actuators

## What It Is

HASEL actuators are soft pouches filled with a dielectric liquid (usually a vegetable or silicone oil), with flexible electrodes printed or laminated onto the surface. When voltage is applied, electrostatic force pulls the electrodes together, displacing the fluid and deforming the pouch — creating motion.

Developed primarily at the **University of Colorado Boulder** by Christoph Keplinger's group. First major paper: *Science* 2018.

## Why It Matters

- **Intrinsic compliance** — yields when it hits something unexpected. No force sensor needed.
- **Self-healing** — minor punctures seal themselves due to the liquid interior
- **Fast** — can operate at many Hz, unlike SMA or TCP
- **Gentle by default** — the physics of the material, not the control loop, makes it safe
- **Transparent** — can be made optically clear

## The Egg Demo

The canonical demonstration: a HASEL gripper picks up a raw egg, a blueberry, and a live spider without breaking or harming any of them. No feedback control. The compliance is built in.

## Current Limitations

- Requires moderately high voltage (1–10 kV range, lower than DEAs but still non-trivial)
- Energy density still below biological muscle
- Scaling to full limb actuation is an open problem
- Manufacturing consistency at scale not yet demonstrated

## Key People

- **Christoph Keplinger** — CU Boulder, founder of Artimus Robotics (HASEL commercialization)
- **Eric Acome** — first HASEL paper lead author
- **Artimus Robotics** — startup commercializing HASEL for industrial and medical use

## Links

- TED Talk: Christoph Keplinger, "Muscles made of the wrong stuff" (search YouTube)
- Original paper: Acome et al., *Science* 2018: "Hydraulically amplified self-healing electrostatic actuators with muscle-like performance"
- Artimus Robotics: https://www.artimusrobotics.com

## Compared to Human Muscle

| Property | Human Muscle | HASEL |
|---|---|---|
| Self-healing | Yes | Partial |
| Energy source | Chemical (ATP) | Electrical |
| Speed | Medium | Fast |
| Force/weight | ~250 W/kg peak | Approaching |
| Compliance | Intrinsic | Intrinsic ✓ |
| Safe near humans | Yes | Yes ✓ |
