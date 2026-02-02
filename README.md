# laser_benchy
A collection of standard files for calibrating and comparing fiber laser setups

This collection came about from a conversation on the Laser Everything discord server. The intent is to have a standard set of files that can be engraved to be used as standard reference points in configuration/calibration and for using when getting support from the community, similar in concept to the 3D printed benchy.

Because fiber lasers have much more variation between brands, models, and controllers, there have to be multiple files for many of the tests.

At the moment, the following files are provided:

* A smooth gradient ramp depth map, in conical format, sized for doing a deep engrave on a 40mm coin. Due to the nature of the ramp, it can be engraved into smaller diameter coins with edge-to-edge coverage. It can also be engraved on larger materials, just with a rim around it. Two files are provided for this, the original XCF file created in gimp and an exported PNG that is imported into lightburn or EZCAD2.
* A depth map of a circle divided into 8 wedges, each corresponding to a different brightness level. The levels are 0, 13, 25, 38, 50, 63, 75, and 88% luminance. There is a 2mm wide rim around the edge and a 5mm diameter hub in the center that are both 100% luminance (a.k.a. not engraved) for reference surfaces when measuring achieved depth.
* A vector file sized 86x54mm to fit on a business card sized blank. It has the following features on it:
  * A set of lines spaced at various distances from each other to determine how close features can be placed to each other and still have visible separation
