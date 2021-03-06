# **The content in this repository has been integrated as Chapter 3 with my dissertation (https://github.com/f-i/dissertation). Updates on this content will ONLY be posted in my 'dissertation (https://github.com/f-i/dissertation)' repository.**
# Making of Reliable APWPs

About how many ways we have to make paleomagnetic APWPs, and most importantly
which one(s) is(are) the best (determined by using the algorithm in another
repository: https://github.com/f-i/APWP_similarity)

## Supplementary Materials

The "data" folder contains two subfolders. The "FHM" includes all the results
from comparisons of Plates 101 (North America), 501 (India) and 801
(Australia)'s paleomagnetic paths and their Fixed Hotspot model (FHM) predicted
paths. The "MHM" includes all the results from comparisons of Plates 101, 501
and 801's paleomagnetic paths and their Moving Hotspot model (MHM) predicted
paths.

    data/SpreadingRidgeRotationFile.txt: Compilation of rotations of spreading ridges

    data/101FHS120predictPWP105.d: FHM and plate circuit predicted APWP (10 Myr sliding window, 5 Myr step) for Plate 101

    data/101FHS120predictPWP2010.d: FHM and plate circuit predicted APWP (20 Myr sliding window, 10 Myr step) for Plate 101

    data/501FHS120predictPWP105.d: FHM and plate circuit predicted APWP (10 Myr sliding window, 5 Myr step) for Plate 501

    data/501FHS120predictPWP2010.d: FHM and plate circuit predicted APWP (20 Myr sliding window, 10 Myr step) for Plate 501

    data/801FHS120predictPWP105.d: FHM and plate circuit predicted APWP (10 Myr sliding window, 5 Myr step) for Plate 801

    data/801FHS120predictPWP2010.d: FHM and plate circuit predicted APWP (20 Myr sliding window, 10 Myr step) for Plate 801

    data/101MHS120predictPWP105.d: MHM and plate circuit predicted APWP (10 Myr sliding window, 5 Myr step) for Plate 101

    data/101MHS120predictPWP2010.d: MHM and plate circuit predicted APWP (20 Myr sliding window, 10 Myr step) for Plate 101

    data/501MHS120predictPWP105.d: MHM and plate circuit predicted APWP (10 Myr sliding window, 5 Myr step) for Plate 501

    data/501MHS120predictPWP2010.d: MHM and plate circuit predicted APWP (20 Myr sliding window, 10 Myr step) for Plate 501

    data/801MHS120predictPWP105.d: MHM and plate circuit predicted APWP (10 Myr sliding window, 5 Myr step) for Plate 801

    data/801MHS120predictPWP2010.d: MHM and plate circuit predicted APWP (20 Myr sliding window, 10 Myr step) for Plate 801

    data/ay18_101comb contains: Plate 101's paleomagnetic paths

    data/ay18/101comb contains: Plate 101's raw paleopoles, paleopoles after filtering and (sub-folders) paleopoles in each sliding window with weights and rock types

    data/ay18_501comb contains: Plate 501's paleomagnetic paths

    data/ay18/501comb contains: Plate 501's raw paleopoles, paleopoles after filtering and (sub-folders) paleopoles in each sliding window with weights and rock types

    data/ay18_801comb contains: Plate 801's paleomagnetic paths

    data/ay18/801comb contains: Plate 801's raw paleopoles, paleopoles after filtering and (sub-folders) paleopoles in each sliding window with weights and rock types

    data/OtherWindowSizes contains: picking number 0 and 1 datasets with 2, 4, 6, 8, 12, 14, 16, 24 and 30 Myr sliding window sizes with half steps for the three representative continents (120-0 Ma)



Here is the video visualising the comparisons for Plate 101's 168 different
paleomagnetic paths and its Fixed Hotspot model predicted & plate circuit
projected path (Click on the image below to view the video):

[![Paleomagnetic APWPs vs. Fixed Hotspot Model Predicted APWP: An Example from North America](https://img.youtube.com/vi/KNEdqo5jcOY/0.jpg)](https://www.youtube.com/watch?v=KNEdqo5jcOY "Paleomagnetic APWPs vs. Fixed Hotspot Model Predicted APWP: An Example from North America")

And here are the corresponding distributions of paleomagnetic data picked from
28 different picking methods and then weighted by 6 different weighting methods:

[![How to Generate Paleomagnetic APWPs: An Example from North America](https://img.youtube.com/vi/GMhG3wwZAfw/0.jpg)](https://www.youtube.com/watch?v=GMhG3wwZAfw "How to Generate Paleomagnetic APWPs: An Example from North America")
