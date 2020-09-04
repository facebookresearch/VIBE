# Body-aware clothing recommendation benchmark
This benchmark is collected for the ViBE project. 
It contains human judged evaluation on which clothing flatters a given subject's body shape. This evaluation is conducted through Amazon's Mechanical Turk platform. For more details, please see Section 4.3. in the [paper](https://arxiv.org/abs/1912.06697).

1. First line in the ```.txt ``` file is the comment header.
2. Including the header, there are in total 307 lines in the file. 
3. The header states that each line contains a human subject's name, the positive clothing's name that flatters this subject, and the negative clothing's name that does not.
4. Entities in a line are separated by white spaces.


Note: 
1. There are in total 14 different human subjects in the benchmark. The numbers reported in Table 2 in the paper is the averaged AUC over 14 subjects.
2. The information (body/dimension measurements, image urls, descriptions, etc.) of the human subjects and the clothing can be found in the ```dataset/``` folder. Simply lookup the subject's name or the clothing's name in the folder for their information.