<div align="center">

<h1>direct-myoelectric-control</h1>

An open-source platform for direct myoelectric control using a Raspberry Pi, <br>enabling muscle control of robotic prostheses like the open-source leg or other Pi projects.

![]((https://github.com/rposh/direct-myoelectric-control/blob/main/assets-images/banner.gif))

</div>

<br>

## Uses

Out of the ROAM Lab at the University of Notre Dame, Ryan Posh has designed and compared multiple novel control approaches for robotic lower-limb prostheses. Among these is Hybrid Volitional Control, which makes use of a direct myoelectric controller as a sub-component. This myoelectric control component, available here for both knee-ankle and ankle-only configurations, allows users to control the Open-Source Leg with any agonist-antagonist muscle pair (e.g. the gastrocnemius and tibialis anterior). This component has been shown to enable a wide variety of user-directed activities, including biomimetic walking, standing on tip-toes, and tapping the foot, leading to high overall satisfaction for individuals with amputation [citation below]. Potential uses of this software release include but are not limited to: using our controller as a comparison point for a novel walking controller; using our controller as a component in a larger, more complex controller like Hybrid Volitional Control; using our controller when researching other related topics, such as human-robot interaction, prosthesis user preference, or fatigue. This software may also be used for other Raspberry Pi projects that would like to incorporate low-cost electromyography.

Proper citation of this controller is as follows:

R. R. Posh, J. P. Schmiedeler, and P. M. Wensing, “Finite-state impedance and direct myoelectric control for robotic ankle prostheses: Comparing their performance and exploring their combination,” IEEE T Neur Sys Reh, vol. 31, pp. 2778–2788, 2023.

## Documentation

You can find tutorials and API documentation at [opensourceleg.readthedocs.io](https://opensourceleg.readthedocs.io/en/latest/).

## License

The _direct-myoelectric-control_ repository is licensed under the terms of the [LGPL-v2.1 license](https://github.com/neurobionics/opensourceleg/raw/main/LICENSE). This license grants users a number of freedoms:

- You are free to use the _direct-myoelectric-control_ software for any purpose.
- You are free to modify the _direct-myoelectric-control_ software to suit your needs.
- You can study how the _direct-myoelectric-control_ software works and change it.
- You can distribute modified versions of the _direct-myoelectric-control_ software.

The GPL license ensures that all these freedoms are protected, now and in the future, requiring everyone to share their modifications when they also share the library in public.

## Contributing

This release is in collaboration with and a contribution to the Open-Source Leg project. As always, more contributions are welcome, and they are greatly appreciated! For more details, read the [contribution guidelines](https://github.com/neurobionics/opensourceleg/blob/11765f7f7dd94e5d8699675149d5ff3596ea01b8/CONTRIBUTING.md) from the OSL community.
