Case clamp_08 is a re-hash of clamp_06, with an updated convective heat transfer coefficient.

Includes
- two joined temperature equations: Tf and Ts.
- transient, incompressible, turbulent.
- fixed time step.

Does not include:
- cover cellZone
- variable inlet conditions

Updates on clamp_06
- inclusion of the necessary scalars to have h_sf as a scalar field:
- in CASE/0: h_sf, Re_D,
- in CASE/constant/transportProperties: D_eq, and K_f
