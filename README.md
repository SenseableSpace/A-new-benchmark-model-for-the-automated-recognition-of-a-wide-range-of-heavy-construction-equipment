### Official Python Implementation
This work was conducted by Yejin Shin, Yujin Choi, Jaeseung Won, Taehoon Hong, and Choongwan Koo (Corrensponding Author) | [Paper](https://doi.org/10.1061/JMENEA.MEENG-5630)

Affiliation: Construction Engineering & Management Lab, Incheon National University.

### Cite This:
Shin, Y., Choi, Y., Won, J., Hong, T., and Koo, C. (Corresponding Author) (2024/03). "A new benchmark model for the automated detection and classification of a wide range of heavy construction equipment." Journal of Management in Engineering, 40(2), 04023069, https://doi.org/10.1061/JMENEA.MEENG-5630. <br><br>

# A new benchmark model for the automated detection and classification of a wide range of heavy construction equipment

### Abstract
The integration of computer vision technology into construction sites poses various challenges due to the complex environment. Prior studies on computer vision related to heavy construction equipment has primarily focused on a limited range of equipment types provided in standard databases, such as the Microsoft Common Objects in Context (MS COCO) dataset. The conventional approach has limitations in capturing the diverse working conditions and dynamic environments encountered in real construction sites. To overcome the challenge, this study proposed a new benchmark model for the automated detection and classification of a wide range of heavy construction equipment (i.e., nine representative types) commonly used in construction sites, by using a deep convolution neural network. This study was conducted in four steps: (i) data collection and preparation; (ii) data transformation; (iii) model training; and (iv) model validation. The proposed YOLOv5l (large, YOLOv5 with a larger network) model demonstrated high reliability, achieving a "mean Average Precision (mAP)_0.5:0.95" of 90.26%. This study makes a significant contribution to the domain of construction engineering and management by providing a more efficient and systematic management system to proactively prevent heavy equipment-related safety accidents with diverse working conditions and dynamic environments encountered at construction sites. Moreover, the proposed approach can be extended to integrate advanced techniques such as case-based reasoning, digital twin, and blockchain, allowing for the automated activity recognition in various occlusions, the carbon emissions monitoring and diagnostics of heavy equipment, and a robust real-time construction management system with enhanced security. <br><br>

### Keywords
Construction site; Heavy equipment; Benchmark model; Object detection and classification; Computer vision; Field applicability <br><br>

### Framework and Dataset
**Figure 1.** Research framework

![Figure1](https://github.com/SenseableSpace/Utilizing-synthetic-images-to-enhance-the-automated-recognition-of-small-sized-construction-tools/assets/162809473/12262482-c487-496e-970d-bd673ee9dbe2) <br><br>

**Figure 2.** Representative examples of training and test dataset

![Figure2](https://github.com/SenseableSpace/Utilizing-synthetic-images-to-enhance-the-automated-recognition-of-small-sized-construction-tools/assets/162809473/c47012f3-c52a-4ef2-b9fc-9484db13828a) <br><br>

### Results
**Figure 3.** Inference results - confidence scores of small-sized tools, ‘Hammer’

![Figure3](https://github.com/SenseableSpace/Utilizing-synthetic-images-to-enhance-the-automated-recognition-of-small-sized-construction-tools/assets/162809473/4621b66d-aa52-486d-a781-8fca9f5ef7b3) <br><br>

**Figure 4.** Inference results - confidence scores of small-sized tools, ‘Tacker'

![Figure4](https://github.com/SenseableSpace/Utilizing-synthetic-images-to-enhance-the-automated-recognition-of-small-sized-construction-tools/assets/162809473/24685b01-dfef-4701-84bf-000ed1bee39d) <br><br>

### Code Definition
| Category                 | Description                                                                           |
| ------------------------ | --------------------------------------------------                                    |
| `ScreenshotCapture.cs`   | This code has been used to automatically generate a group of synthetic images by capturing the screen while incrementally changing the viewing angles of a 3D object's x and y axes from 0° to 360° by 15° increments. |
| `YOLOv8_open.ipynb`      | This code has been used to develop the proposed vision-based classifiers (i.e., 'Real-4000,' 'Hybrid-4000,' and 'Hybrid-8000') for the automated recognition of small-sized construction tools. |

### Data Availability Statements
Some or all of the data or code that support the findings of this study are available from the corresponding author upon reasonable request. <br><br>

### Download link
| Category                              | Total   | Link                                                                                 | Release Date |
| ------------------------------------- | ------- |  ----------------------------------------------------------------------------------  | ------------ |
| Training dataset-[Real-4000]-images   | 4000    | https://drive.google.com/file/d/1oR4iLT82qBX_xiZD8yXkVHOjpNZ51gQr/view?usp=sharing   | 11 Mar 2024  |
| Training dataset-[Real-4000]-labels   | 4000    | https://drive.google.com/file/d/1Z-TaXi1k6Mr5hyfd8eiyuY52kZWPkHOS/view?usp=sharing   | 11 Mar 2024  |
| Training dataset-[Hybrid-4000]-images | 4000    | https://drive.google.com/file/d/1hwVtejkUj0JpTiv-q2jjtW3ZzgIdFl-L/view?usp=sharing   | 11 Mar 2024  |
| Training dataset-[Hybrid-4000]-labels | 4000    | https://drive.google.com/file/d/1hwVtejkUj0JpTiv-q2jjtW3ZzgIdFl-L/view?usp=sharing   | 11 Mar 2024  |
| Training dataset-[Hybrid-8000]-images | 8000    | https://drive.google.com/file/d/1hwVtejkUj0JpTiv-q2jjtW3ZzgIdFl-L/view?usp=sharing   | 11 Mar 2024  |
| Training dataset-[Hybrid-8000]-labels | 8000    | https://drive.google.com/file/d/10Wl94qQ8DciSnBAyVLlLu1ZQdqOi4wCq/view?usp=sharing   | 11 Mar 2024  |
| Test dataset-images                   | 576     | https://drive.google.com/file/d/1y5yLGsyNBXmoyT1IUd4-qJqo6mXeTAoj/view?usp=sharing   | 11 Mar 2024  |
| Test dataset-labels                   | 576     | https://drive.google.com/file/d/1gPlacSloHKc422tVJdQgEpHhs5W7iT8k/view?usp=sharing   | 11 Mar 2024  |
