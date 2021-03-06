# thermal_micro_driver
Simulation of thermal micro driver
The direct current flowing along the MM induces Joule's heat and magnetic field. Elastic deformation of MM is caused by two phenomena: thermo-elastic (TE) deformation as a result of Joule's heat and magneto-elastic (ME) deformation as a result of induced magnetic field.
3.1	TE deformation
TE deformation of MM is simulated using a planar layer model where the chemical composition of the planar layers is the same as the chemical composition of the individual layers of MM and the thickness hi of each planar layer is twice the standard thickness deviation of the corresponding layer in MM  The planar layers represent the axial asymmetry of MM. The TE deformation of system of plane layers can be then expressed as bending amplitude A1 as a function of temperature change ∆T
1/P=(6∑_i^n▒〖E_i h_i (α_i-α_s ) 〗 ∆T)/(E_s h_s^2 )
P is the curvature radius P^2=〖(P-A1)〗^2+ 〖(l/2)〗^2
l is its length of plane layers’ system. ES and αS denote Young’s modules and thermal expansion coefficients of amorphous metal layer. Ei and αi (i=1, 2, 3) denote Young’s modules and thermal expansion coefficients of Pyrex glass, noble metal and external layer, respectively. hs is thickness of amorphous metal layer. 
Temperature changes of individual layers∆T_i=  (4q_i l^2)/(K_i π^3 ) {-exp[-κ_i (π/l)^2 t]}
where qi=Ii2/(Si2σi). Si, Ii, and σi are cross section, electric current, and electrical conductivity of i-th layer, respectively. κi=Ki/(Dici) where Ki, Di, and ci are heat conductivity, mass density, and specific heat capacity of the i-th layer, respectively. l is the length of i-th. t is a time interval at constant current. Electrical current, I, flows through three metallic layers. The values of direct currents flowing through amorphous metal layer, noble metal layer, and external layer was determined from Kirchhoff’s First and Second laws. The temperature change of plane layer system is calculated as a mean value of temperature changes in individual layers.
ME deformation
Magnetic field induced by direct current causes magnetostriction expansion of MM. If both ends are fixed, the bending is caused by the length change of MM. Actually, the resultant magnetic field is induced by the currents flowing through the three metallic layers; amorphous metallic core, an intermediate sputtered noble metal, and an external layer. Magnetic field induced by the direct current I in amorphous metallic core is calculated in two steps. In the first step, magnetic field, B1, generated inside the metallic core was determined from modified Biot-Savart law
	B_1=  (μ_0 Ix)/(2πR^2 )	(3.4)
where µ0 is vacuum permeability, R is radius of metallic core, and x is a radial distance from the MM’s axis in range 0-r1 where r1 is the radius of metallic core. As the second step, magnetic field outside the metallic core was determined form the Biot-Savart law for long straight wire 
	B_2=  (μ_0 I)/2πx	(3.5)

Magnetic fields induced by the direct current in next layers is determined in the same way. The bending amplitude A2 is determined from relation
	L= (A2+ l^2/(4*A2))arcsin(l/(A2+ l^2/(4*A2)))	(3.6)

where L = 𝛿l + l is the length of MM after magnetostrictive expansion and 𝛿l is the length change of MM, calculated as a product of the mean value of magnetostriction, 𝜆mean, and the initial length of MM. A mean value of magnetostriction is determined from individual values of magnetostriction along the MM’s radius. The values of direct current corresponds to temperature changes calculated in TE deformation.
Contribution of TE and ME deformation to resultant deformation of MM
The contribution of TE deformation to the deformation of MM is more than 20 times larger than the deformation related with magnetostrictive effect. Both contributions were included to the bending amplitude A as a function of ∆T.
