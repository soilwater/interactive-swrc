## Soil Water Retention Curve Applet

This web-based applet provides an interactive visualization of soil water retention curves using the van Genuchten model, with matric potential expressed in kPa. The tool is designed to support teaching, research, and model development related to soil water availability and plant water stress.

Users can select USDA textural classes to load default hydraulic parameters derived from the Oklahoma Mesonet soil database (Scott et al., 2013), or manually adjust van Genuchten parameters using sliders. The applet computes and displays key soil water metrics, including field capacity (10 kPa), permanent wilting point (1500 kPa), plant available water capacity (PAWC), fraction of available water (FAW), and the corresponding matric potential at the onset of plant water stress.

In addition to traditional storage-based metrics, the applet calculates the cumulative work required to extract water between two matric potentials (∫ψ dθ, expressed in J m⁻³), providing a physically based perspective on soil water availability. The applet also identifies the inflection point of the retention curve on a log-scaled matric potential axis and visually highlights no-stress and stress water domains.

The application is implemented as a single HTML/JavaScript file using Plotly for visualization and requires no server-side components.
