### Official Python Implementation
This work was conducted by Yejin Shin, Yujin Choi, Jaeseung Won, Taehoon Hong, and Choongwan Koo (Corresponding Author) | [Paper](https://doi.org/10.1061/JMENEA.MEENG-5630)

Affiliation: Construction Engineering & Management Lab, Incheon National University.

### Cite This:
Shin, Y., Choi, Y., Won, J., Hong, T., and Koo, C. (Corresponding Author) (2024/03). "A new benchmark model for the automated detection and classification of a wide range of heavy construction equipment." Journal of Management in Engineering, 40(2), 04023069, https://doi.org/10.1061/JMENEA.MEENG-5630. <br><br>

# A new benchmark model for the automated recognition of a wide range of heavy construction equipment

### Abstract
The integration of computer vision technology into construction sites poses various challenges due to the complex environment. Prior studies on computer vision related to heavy construction equipment has primarily focused on a limited range of equipment types provided in standard databases, such as the Microsoft Common Objects in Context (MS COCO) dataset. The conventional approach has limitations in capturing the diverse working conditions and dynamic environments encountered in real construction sites. To overcome the challenge, this study proposed a new benchmark model for the automated detection and classification of a wide range of heavy construction equipment (i.e., nine representative types) commonly used in construction sites, by using a deep convolution neural network. This study was conducted in four steps: (i) data collection and preparation; (ii) data transformation; (iii) model training; and (iv) model validation. The proposed YOLOv5l (large, YOLOv5 with a larger network) model demonstrated high reliability, achieving a "mean Average Precision (mAP)_0.5:0.95" of 90.26%. This study makes a significant contribution to the domain of construction engineering and management by providing a more efficient and systematic management system to proactively prevent heavy equipment-related safety accidents with diverse working conditions and dynamic environments encountered at construction sites. Moreover, the proposed approach can be extended to integrate advanced techniques such as case-based reasoning, digital twin, and blockchain, allowing for the automated activity recognition in various occlusions, the carbon emissions monitoring and diagnostics of heavy equipment, and a robust real-time construction management system with enhanced security. <br><br>

### Keywords
Construction site; Heavy equipment; Benchmark model; Object detection and classification; Computer vision; Field applicability <br><br>

### Research Framework
**Figure 1.** Research framework

![Figure1](https://github.com/SenseableSpace/A-new-benchmark-model-for-the-automated-recognition-of-a-wide-range-of-heavy-construction-equipment/assets/162809473/4b78e3cf-dfc8-4eb6-9a93-064f4e16c4ea) <br><br>

### Results

**Figure 2.** Inference with image dataset - Confidence score by equipment class (YOLOv5s, YOLOv5m, and YOLOv5l models)

![Figure2-1](https://github.com/SenseableSpace/A-new-benchmark-model-for-the-automated-recognition-of-a-wide-range-of-heavy-construction-equipment/assets/162809473/364f5181-c688-4a52-bb6b-99ededc990e6)
![Figure2-2](https://github.com/SenseableSpace/A-new-benchmark-model-for-the-automated-recognition-of-a-wide-range-of-heavy-construction-equipment/assets/162809473/fabdf7c6-cfa1-4140-b7d9-4b8b17bcc431)
![Figure2-3](https://github.com/SenseableSpace/A-new-benchmark-model-for-the-automated-recognition-of-a-wide-range-of-heavy-construction-equipment/assets/162809473/90db217c-715e-4d72-a044-9a18ccd6fe0d) <br><br>

### Code Definition
| Category                 | Description                                                                           |
| ------------------------ | --------------------------------------------------                                    |
| `YOLOv5_open.ipynb`      | This code has been used to develop the proposed vision-based classifiers for the automated recognition of a wide range of heavy construction equipment. |

### Data Availability Statements
Some or all of the data or code that support the findings of this study are available from the corresponding author upon reasonable request. <br><br>

### Download link
| Category                              | Total   | Link                                                                                 | Release Date |
| ------------------------------------- | ------- |  ----------------------------------------------------------------------------------  | ------------ |
| Training dataset-images               | 4000    | https://drive.google.com/file/d/1oR4iLT82qBX_xiZD8yXkVHOjpNZ51gQr/view?usp=sharing   | 11 Mar 2024  |
| Training dataset-labels               | 4000    | https://drive.google.com/file/d/1Z-TaXi1k6Mr5hyfd8eiyuY52kZWPkHOS/view?usp=sharing   | 11 Mar 2024  |
| Test dataset-images                   | 576     | https://drive.google.com/file/d/1y5yLGsyNBXmoyT1IUd4-qJqo6mXeTAoj/view?usp=sharing   | 11 Mar 2024  |
| Test dataset-labels                   | 576     | https://drive.google.com/file/d/1gPlacSloHKc422tVJdQgEpHhs5W7iT8k/view?usp=sharing   | 11 Mar 2024  |
