# Admittance-Method

The admittance method is a numerical electromagnetic method in which the problem
space is discretely partitioned and its electrical properties represented in terms of an
admittance network created from the dielectric properties of the intervening materials. In
the presence of electromagnetic stimulation, the electrical response of the problem space
is approximated as the response of the admittance network to a stimulus representative
of the original source. 

# Key Features

A distinctive advantage of using the admittance method for bioelectromagnetic simulations
is that the method implies a representation of the system in terms of an electric
network. Examples of applications where this method can be of use are the modeling
of metal-electrolyte interfaces for implanted electrodes, and the simulation of electrical
behavior of neural cells using three-dimensional variations of the core-conductor model.
Because arbitrary circuital elements can be added to an admittance network to model
physiological behavior, the admittance method (and its dual, the impedance method)
can, in principle, be used to bridge the gap between tissue level and cellular level modeling.

Even though numerical treatments of bioelectromagnetic phenomena using the
admittance and impedance methods have been available for several decades, detailed
modeling of large biological structures has presented unique challenges, as the shapes of
anatomical structures tend to be complex, and frequently the sizes of features that must
be resolved are small compared to the overall size of the model. 

The multiresolution algorithm presented here these issues by greatly reducing the
resulting voxel count while keeping an error comparable to the uniform resolution cases.
This is achieved by selectively maintaining high resolutions at material boundaries while
progressively increasing voxel size inside large homogeneous volumes. Different from previous
treatments of the admittance method, which solved static or single-frequency (frequency
domain) models, the proposed formulation can take advantage of time-stepping
to simulate the effect of excitation using signals of arbitrary waveforms.


# Learn More

For more details, please see the following:

https://itemsusc.org/wp-content/uploads/2020/03/Cela_Dissertation.pdf


# Development

Main Developer:  Carlos J. Cela

This code was initially developed by Carlos Cela at North Carolina State University, as part of his Ph.D. thesis work.







