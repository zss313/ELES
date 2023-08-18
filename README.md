# SSN: Shift Suppression Network for Endogenous Shift of Photovoltaic Defect Detection

Electroluminescence (EL) Endogenous Shift (ELES) dataset is the first endogenous domain shift benchmark of photovoltaic manufacturing scenarios. Due to the differences in intrinsic mechanisms or hardware components of the imaging systems of different types of imaging conditions, there are subtle perturbations in EL images generated by different quality inspection production line, which cause the endogenous shift.

#2023 Dataset Access Instructions:
We collected three sets of EL data (EL group 1, EL group 2, and EL group 3) at different times during the production line update process of the same manufacturer. In this study, EL group 1 is used for training the detector, and the other two are used for the test. To efficiently test PV modules, we slice a PV module based on the unit of 2 cells and spliced it into a complete module after the detection. Combined with deep learning technology and with the assistance of multiple experts, we meticulously annotate all defects. The dataset contains a total of $16,323$ EL PV images. 

\\begin{array}{ccccccc} 

\\hline \\multirow{2}{\\*}{\\begin{array}{c}

\\text { Number of } \\\\  

\\text { defects } 

\\end{array}} & \\text { Training } & & \\multicolumn{3}{c}{\\text { Testing }} & \\multirow{2}{\*}{\\text { Total }} \\\\

\\cline { 2 - 2 } \\cline { 5 - 7 } & \\text { EL group 1 } & & \\text { EL group 1 } & \\text { EL group 2 } & \\text { EL group 3 } & \\\\

\\hline \\text { broken gate } & 2060 & & 376 & 909 & 335 & 1620 \\\\

\\text { unjoined weld } & 1336 & & 227 & 1167 & 275 & 1669 \\\\ 

\\text { black spot } & 1976 & & 337 & 833 & 270 & 1440 \\\\

\\text { crack } & 1692 & & 259 & 187 & 62 & 508 \\\\

\\text { scratch } & 1920 & & 299 & 1011 & 257 & 1567 \\\\

\\hline

\\end{array}

##Download Dataset

If you want to access the dataset, please read the ELES-Dataset Request Form in this folder carefully, sign the corresponding commitment file and send it to 202012801003@stu.hebut.edu.cn.

EDS dataset consists of:

  * 3 different domains

  * Altogether 16,323 EL images


