# TI-Nspire Physics Solver

Step-by-step solver for University Physics (Young & Freedman) chapters 21-23 on the TI-Nspire CX II CAS. Pick a problem type, type in the knowns, and it prints the formula, the numbers plugged in, the result with units, and the direction or sign reasoning.

## Install

1. Connect the calculator by USB and open https://nspireconnect.ti.com in Chrome.
2. Transfer File > To Calculator > From Computer, pick `phys.tns`, and put it in the MyLib folder.
3. On the calculator press doc > Refresh Libraries.

## Run

In a Calculator page type `phys\main()` and press enter, or use Catalog > Libraries > phys > main.

## Typing numbers

- Scientific notation: `2.5E-6` (or the EE key)
- Prefixes: `n` nano, `u` micro, `p` pico, `k` kilo, and `cm`, `mm`, `um`, `nm` (for example `4.4n`, `1.5cm`)
- Expressions work: `92*1.602E-19`
- Cancel on any prompt goes back

## Topics

- Ch 21: charge count, force between two charges, net force on a line and in 2D, zero-force point, hanging charged spheres
- Ch 22: flux through a surface, flux from enclosed charge, line charges, spheres and shells, force from a shell, charge densities, coaxial cable
- Ch 23: potential energy of charges, potential and work, work-energy in a uniform field, accelerating or stopping a particle, point charge from V and E, line charge potential, E from V(x,y,z), concentric spheres and coaxial cylinders, insulating sphere, where potential energy is zero

Results are in SI units to 3 significant figures, using k = 8.99E9, e0 = 8.854E-12, e = 1.602E-19, me = 9.109E-31, mp = 1.673E-27, g = 9.8.

`phys.tib` is the program source.
