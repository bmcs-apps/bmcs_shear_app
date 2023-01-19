# App - Shear of Brittle-Matrix-Composite Beams

## Description
A web app for interactive simulation of the shear zone behavior, including 
automated crack detection from DIC monitoring, analysis of shear crack kinematics,
and quantification of stress transfer mechanisms.

Showcase: crack propagation through a shear zone of a reinforced concrete 
beam captured using digital image correlation methods, combined with the 
simulation of the damage localization. 

![crack_detection](notebooks/cracking_animation.gif)

## Launch app
Start the app in standard Jupyter Notebook mode → 
[![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/bmcs-apps/bmcs_shear_app.git/main?filepath=notebooks/dic_crack_list.ipynb)

## App backend dependencies
This app depends on the following open-source packages from the [BMCS Group](https://github.com/bmcs-group):
* [bmcs_cross_section](https://pypi.org/project/bmcs-cross-section): for calculating moment-curvature behaviour of a cross-section.
* [bmcs_beam](https://pypi.org/project/bmcs-beam): for calculating the load-deflection response of a beam.
* [bmcs_shear_zone](https://pypi.org/project/bmcs-shear-zone): for shear zone analysis.
* [bmcs_utils](https://pypi.org/project/bmcs-utils): graphical user interface support using Jupyter widgets.

[//]: # (## Cite with: [![DOI]&#40;https://zenodo.org/badge/DOI/10.5281/zenodo.7550117.svg&#41;]&#40;https://doi.org/10.5281/zenodo.7550117&#41;)

[//]: # (The repository can refered to using a unique doi hosted at https://zenodo.org)
