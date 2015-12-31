# 3d_magnetic_ball_joint
Low-friction magnetic ball joints for delta 3d printer based on standard components

## Design B: conic magnet with epoxy coating
Chromeball sliding directly on a epoxyd cylindric magnet with a conical hole where the ball snapps in

* Pro:
  * cheap standard components
  * ball is hold tight and is keept centered
  * N42 magnets provide enough stength to keep up with high printing speeds / accelerations
  * screw to maintain magnet holder pockets are reachable through magnet hole
* Contra:
  * potential wear from opertion on the epoxy coating
    * it's conical, not spherical so friction is not distributed equally
    * silikon lubrication or PTFE (Teflon) spray-paint-coating on top of the epoxy could help
  * in current design the magnet is press-fit in the pocket
    * A) tighten the screw might leave tiny traces from inserting/extrating screwdriver
    * B) sintered magnets usually dont like pressure and impact forces
    * snap-in design or glueing into wider pockets could solve this

![B) conic ball joint example](https://raw.githubusercontent.com/splosch/3d_magnetic_ball_joint/master/documentation/conic_ball_joint_example.png)

### Example: end effector
![end effector example image](https://raw.githubusercontent.com/splosch/3d_magnetic_ball_joint/master/documentation/end_effector_example.png)

![end effector example printed](https://raw.githubusercontent.com/splosch/3d_magnetic_ball_joint/master/documentation/end_effector_printed_example.jpg)

### BOM (Bill of materials)
Version B (Chromeball sliding on conic magnet coated in epoxy)
* 10mm Chrome-Steel-Ball
* 8 x 3mm conic Neodym-Magnet (N42 worked fine)
 * 45deg cone
 * 6.7mm top cone diameter
 * 3.5mm hole
* M3 Screw DIN 7991
* M3 Nut DIN 892 (tried a nylon one)

# Dropped Designs

## Design A: flat magnet with nylon washer (not working)
Chromeball sliding on a nylon washer, kept in place by a flat cylindric magnet
a 10mm ball sinks in the M6 nylon washers hole (6.2mm) with ~1.5mm thickness just far enough to not touch the magnet. Tight fit 6mm holes require ~1.2mm thickness.

* Pro:
  * cheap standard components
  * low friction
  * low wear on the washer --> little maintainance
* Contra:
  * the spacing that the washer and the spherical outline create is big
  * a 8x2mm N42 Magnet is not strong enough to hold the steelball tight
  * practical printing speeds / accelerations would not be possible
    * thicker magnets could help bridge the gap but add more weight

![A) ball joint example](https://raw.githubusercontent.com/splosch/3d_magnetic_ball_joint/master/documentation/ball_joint_example_A.png)

### BOM (Bill of materials)
Design A (not working):
* 10mm Chrome-Steel-Ball
* 8 x 2mm Neodym-Magnet (for my purpose N50 worked fine)
* 11.9 x 1.5 mm M6 Nylon washer / disc
 * inner diameter 6.2mm