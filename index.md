# How to Build a Syringe Pump

- **[Home](/Syringe-Pump-3890/index)**
- [Mechanical](/Syringe-Pump-3890/mechanical)
- [Electrical](/Syringe-Pump-3890/electrical)
- [Code](/Syringe-Pump-3890/code)

Specifications of the syringe pump.
When the pump is constructed with a syringe of the suggested specifications, up to *number* mL of fluid or gel can be dispensed in total. The smallest motor step size allowed by the Arduino wiring configuration is 1/16 of a rotation, or 22.5 degrees. The smallest linear distance achievable is therefore (1.25mm)/16 = 0.078mm. Moving the plunger this distance through the syringe's cylindrical barrel (19mm ID) gives a smallest theoretical extrudable volume of 22.15 mm^3 or 0.02215 mL. However, the mechanical inaccuracies involved with using a threaded rod may lead to variable resolution.

Syringe pumps offer precise and automated control when extruding gels or dispensing fluids, and can be built and programmed using open-source designs and readily available parts for a fraction of the cost of commercially available pumps. 

