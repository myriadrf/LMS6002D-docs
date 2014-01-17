LMS6002D Documentation 
======================

A Message from Lime Microsystems CEO
------------------------------------

Our organisation is committed to supporting the open source community. We firmly believe that community-developed platforms will play an increasingly vital role in wireless innovation and will be key drivers in making universal wireless access a reality. With this in mind, since October 2011 we have been supplying our Field Programmable RF (FPRF) transceiver, LMS6002D, through major distribution channels and with no requirement for a non-disclosure agreement (NDA).

The organisations and individuals who gained access to the pre-production version of the device, prior to the aforementioned date, are free to share their information and encouraged to publish their designs for the benefit of the open source community. Furthermore, we would be delighted to provide links to such resources from our own open source initiative hosted at MyriadRF.org.

We at Lime are very excited by the prospect of working with the open source community to exploit our technology to its full potential and for the benefit of a large number of people.

We welcome contributions to the documentation in the form of reports of errors and omissions, and general suggestions for improvement, via the [issue tracker](https://github.com/myriadrf/LMS6002D-docs/issues) that is associated with this repository.

Thank you for your support.

Ebrahim Bushehri
CEO, Lime Microsystems

Contents
--------

 * [LMS6002Dr2-DataSheet-1.2r0.pdf][1] (5th June 2012) - LMS6002D datasheet.
 * [LMS6002Dr2-Programming and Calibration Guide-1_1r4.pdf][2] (11th June 2013) - LMS6002D Programming and Calibration Guide. Also contains description of calibration procedures.
 * [LMS6002Dr2-Quick Starter Manual-EVB_5_r2.3.pdf][3] (11th May 2012) - Quick Starter Manual for the [LMS6002D evaluation board][EVB]. Contains useful instructions for manual LO leakage and I/Q imbalance calibration.
 * [LMS6002D-FAQ-1.0r7.pdf][4] (16th July 2012) - Answers to Frequency Asked Questions. Don't miss this.
 * [LMS6002Dr2-Improving transceiver performance using digital techniques-1.0r1.pdf][5] - Shows how to cancel TX LO leakage and compensate RX IP2 and TX I/Q imbalance in baseband.
 * [LMS6002D-Temperature testing July 2011.pdf][6] - Measurements of the chip performance vs. temperature and frequency.
 * [LMS6002Dr2-RF LoopBack Response.pdf][7] - The document shows the frequency response of different RF Loopback. Adjusting the Tx/Rx gain stages you can make the frequency response to be flat up to 2.9 GHz for LNA1/2.
 * [LMS6002D IF-RF LoopBack Options.pdf][8] - A diagram showing baseband loopback connection options.
 * [LPF IF BW vs RCCAL_LPF.pdf][9] - Shows dependency between the LPF bandwidth and RCCAL_LPF (0x36[6-4]) values for the 750kHz filter.
 * [LMS6002D S-parameters application note -1.0r9.pdf][10] - documentation for the S-Parameter measurements in s2p-files.
 * [LMS6002D_RX_PLL_Locking_Time_v2_OS.pdf][11] - PLL settling time measurements.
 * [FAQ_v1.0r11.pdf][12] (17th January 2014) - Frequently Asked Questions.

[1]: https://github.com/myriadrf/LMS6002D-docs/raw/master/LMS6002Dr2-DataSheet-1.2r0.pdf
[2]: https://github.com/myriadrf/LMS6002D-docs/raw/master/LMS6002Dr2-Programming%20and%20Calibration%20Guide-1_1r4.pdf
[3]: https://github.com/myriadrf/LMS6002D-docs/raw/master/LMS6002Dr2-Quick%20Starter%20Manual-EVB_5_r2.3.pdf
[4]: https://github.com/myriadrf/LMS6002D-docs/raw/master/LMS6002D-FAQ-1.0r7.pdf
[5]: https://github.com/myriadrf/LMS6002D-docs/raw/master/LMS6002Dr2-Improving%20transceiver%20performance%20using%20digital%20techniques-1.0r1.pdf
[6]: https://github.com/myriadrf/LMS6002D-docs/raw/master/LMS6002D-Temperature%20testing%20July%202011.pdf
[7]: https://github.com/myriadrf/LMS6002D-docs/raw/master/LMS6002Dr2-RF%20LoopBack%20Response.pdf
[8]: https://github.com/myriadrf/LMS6002D-docs/raw/master/LMS6002D%20IF-RF%20LoopBack%20Options.pdf
[9]: https://github.com/myriadrf/LMS6002D-docs/raw/master/LPF%20IF%20BW%20vs%20RCCAL_LPF.pdf
[10]: https://github.com/myriadrf/LMS6002D-docs/raw/master/LMS6002D%20S-parameters%20application%20note%20-1.0r9.pdf
[11]: https://github.com/myriadrf/LMS6002D-docs/raw/master/LMS6002D_RX_PLL_Locking_Time_v2_OS.pdf
[EVB]: http://www.limemicro.com/lms6002d_eval.php
[12]: https://github.com/myriadrf/LMS6002D-docs/raw/master/FAQ_v1.0r11.pdf

Projects
--------

For details of open source projects that use the LMS6002D please see the [Myriad-RF website](http://myriadrf.org).

Support
-------

Support is available via the [forums](http://myriadrf.org/forums/) and [Google group](https://groups.google.com/forum/#!forum/limemicro-opensource).

Thanks
------

With thanks to Alexander Chemeris for initially hosting the documentation and starting an issues list.
