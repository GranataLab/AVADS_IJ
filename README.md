# AVADS_IJ
This is the ImageJ version of Automated Video Analysis for Dynamic Systems, or AVADS.

This program does require the installation of the FFMPEG plugin for FIJI. This stable version of the program allows users to automatically track high-contrast markers, however, the program is still in development. As we have not yet been able to sucessfully load videos frame-by-frame instead of all at once, AVADS_IJ cannot be used with large video files (either long or very high resolution). Additionally, AVADS_IJ does not allow users to spline-interpolate across gaps in data,  low-pass filter data, or create 2D joint angles. However, we are also providing an excel spreadsheet which filters data exported from AVADS_IJ, computes an angle between three points, and computes the peak angle during a specified time. We hope to soon be able to include this functionality directly within AVADS_IJ. 

For a tutorial video showing you how to use AVADS_IJ, please see here: https://youtu.be/ZvraDxtiB90

If you use this program for your research, please cite the following paper:

Peebles AT, Carroll MM, Socha JJ, Schmitt D, and Queen RM. "Validity of using two-dimensional video analysis and automated marker tracking to assess continuous sagittal-plane running kinematics" In review at Annals of Biomedical Engineering as of June 2020.
