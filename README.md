﻿# EEG-based decoding of the spatial focus of auditory attention using CSPs

## License

See the [LICENSE](LICENSE.md) file for license rights and limitations. By downloading and/or installing this software and associated files on your computing system you agree to use the software under the terms and condition as specified in the License agreement.

If this code has been useful for you, please cite [1].

## About

This repository includes the MATLAB-code for the subject-specific CSP decoder as explained in [1]. [mainSubjectSpecific.m](mainSubjectSpecific.m) contains the main script, which works by default with the dataset published in https://zenodo.org/record/3997352#.X0y1B3kzZEY. The [preprocessData.m](preprocessData.m)-script can be used to preprocess the data, downloaded from the aforementioned link, and replaces the function of the same name at https://zenodo.org/record/3997352#.X0y1B3kzZEY. 

Developed and tested in MATLAB R2020a.

Note: Tensorlab is required (https://www.tensorlab.net/).

### Quick guide

1. Download the dataset from https://zenodo.org/record/3997352#.X0y3nHkzZEZ.
2. Run [preprocessData.m](preprocessData.m).
3. Run [mainSubjectSpecific.m](mainSubjectSpecific.m).
4. Add your own datasets and play around!

## Contact
Simon Geirnaert  
KU Leuven, Department of Electrical Engineering (ESAT), STADIUS Center for Dynamical Systems, Signal Processing and Data Analytics  
KU Leuven, Department of Neurosciences, Research Group ExpORL  
Leuven.AI - KU Leuven institute for AI  
<simon.geirnaert@esat.kuleuven.be>

Tom Francart
KU Leuven, Department of Neurosciences, Research Group ExpORL  
<tom.francart@kuleuven.be>

Alexander Bertrand
KU Leuven, Department of Electrical Engineering (ESAT), STADIUS Center for Dynamical Systems, Signal Processing and Data Analytics  
Leuven.AI - KU Leuven institute for AI  
<alexander.bertrand@esat.kuleuven.be>

 ## References
 
[1] S. Geirnaert, T. Francart, and A. Bertrand, "Fast EEG-based decoding of the directional focus of auditory attention using common spatial patterns," bioRxiv, 2020.06.16.154450, https://doi.org/10.1101/2020.06.16.154450, 2020
