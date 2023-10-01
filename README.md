# Electron Transport Analysis
Project created for Quantum Mechanics and Quantum Computing course.

The quantization resulting from confinement affects significantly the electron transport on nanostructures. The first experimental observation of the conductance quantization was in the Quantum Point Contact structure, where the electrons were traveling through a very narrow channel created by the split-gate structure. In this analysis I will show how the presence of a single or multiple scattering centres inside the channel affects the transport properties of the system.

For the analysis the [kwant](https://kwant-project.org/) package was used, with help of basic data analysis libraries like numpy and matplotlib.

## Main conclusions:

1) The systems with the highest T(E) value for a given energy have no additional on-site energy added. Plots of the probability density show regions where electrons are likely to travel through the system. Number of those regions is proportional to the transmission coefficient for a given energy.  
2) Additional parabolic potential causes electrons to flow closer to the centre as they aren't able to move through potential increased by the additional y-axis dependent parabolic potential.  
3) Single scattering potential makes electrons' path through the system more scattered and the are likely to get affected by it. Attractive potential causes electrons to travel through it or get pulled into, while repellent potential causes them to get reflected back or bypass it.  
4) As the scattering centers get more complex, the T(E) function stops resembling the one for systems without any additional potential sources. For certain systems, the distribution of on-site potential may cause the electrons to get "trapped" and never travel across the system.  
5) Very complex nanosystems require a very good processor to properly calculate quantities such as transmission coefficient, taking into account every possible component. 
