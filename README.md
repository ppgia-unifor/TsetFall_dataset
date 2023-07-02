<p align="center">
  <a href="" rel="noopener">
 <img src="./img/header.jpg" alt="Project logo"></a>
</p>

<h1 align="center">TsetFall dataset</h1>

<div align="center">


[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](/LICENSE)

</div>

---

<p align="center">A Comprehensive, fine-grained, and publicly available dataset generated for human fall detection. <br> 
</p>

## Table of Contents

- [Table of Contents](#table-of-contents)
- [About ](#about-)
- [Data structure ](#data-structure-)
- [Videos description ](#videos-description-)
- [Download ](#download-)
- [Authors ](#authors-)
<!-- - [Acknowledgments](#acknowledgement) -->

## About <a name = "about"></a>

Human fall detection research remains an underdeveloped
area, particularly with respect to utilizing dynamic
images for analysis. Existing fall detection datasets often suffer
from size, diversity, and representativeness limitations, as they
generally comprise a small number of videos featuring a limited
range of actions, camera perspectives, and lighting conditions.
Moreover, these datasets typically lack the complexity of real-world
fall scenarios, as they often exclude distracting objects and
offer only one or two camera angles. To address these challenges,
this work introduces TsetFall, a comprehensive, fine-grained, and
publicly available dataset generated for fall detection research.
Employing a novel AI technique devised by the present authors,
the dataset annotation process was notably expedited. By bridging
the current gaps in available resources, the TsetFall dataset
serves as a valuable benchmark for advancing the field and
tackling the multifaceted nature of human fall detection.

## Data structure <a name = "data_description"></a>


The content is made available in the following format:
  - A folder containing our publications
  - A compressed folder containing each of the images from the video sequences. The image name follows the following pattern: `cam_number__sequenceNumber-sequenceName__frameNumber.jpeg`. Example: `cam_1__1-andando-normalmente__00001.jpeg`.

  - A compressed folder containing the sequences arranged in video format. The image name follows the following pattern: `cam_number__sequenceNumber-sequenceName.mp4`.

  - The CSV file containing the annotations performed by humans only. Each line of the file contains the following fields:

    - Image name
    - Detection confidence
    - Class of the objects of interest: Not Fallen (NF), Fallen (FN), Falling (FG), and Confounding (C)
    - 4 fields containing the object's location in the format x_min, y_min, x_max, y_max
    - The algorithm that generated the detection

  - The CSV file containing the ia-assisted annotations. Each line of the file contains the same strucutre of the previous file, with the addition of the following fields:
    - Detection confidence
    - The algorithm that generated the detection


```
tsetfall
├─ publications
├─ tsetfall.rar
│  └─ [list of images]
├─ tsetfall_videos.rar
│  └─ [list of videos]
├─ ground_truth.csv 
└─ ground_truth_extended.csv 
```
## Videos description <a name = "video_description"></a>

|#|Sequence Name|Description|
|-|-------------|-----------|
|1|andando-normalmente|The person is walking and engaging with various objects in their environment.|
|2|desmaiando|The person suddenly loses consciousness and collapses.|
|3|deitando-nas-cadeiras|The person is positioned lying across three chairs.|
|4|sentando-na-cadeira-com-gatinho|The person is seated in a chair with a kitten next to them.|
|5|sentando-no-chao|The person is seated on the floor.|
|6|andando-com-bengala |The person is using a cane to assist with walking but eventually falls down.|
|7|andando-com-anda-ja|The person is using a walker for support while walking but experiences a fall.|
|8|caindo-de-costas|The person falls backward.|
|9|caindo-de-barriga|The person falls forward.|
|10|andando-com-casaco-na-cadeira|The person is walking and engaging with objects, including a coat hanging on a chair.|
|11|sentando-com-casaco-na-cadeira|The person is seated on a chair positioned next to another chair with a coat hanging on it.|
|12|cair-no-escuro|The person falls forward in a dark environment.|
|13|teste-da-camisa-de-botoes|The person interacts with a button-up shirt hanging on a hanger in a dark environment.|
|14|polichinelos-no-escuro|The person performs jumping jacks exercise in a dark environment.|
|15|apoio-de-frente-escuro|The person engages in a front support exercise (plank) in a dark environment.|
|16|abdominal-no-escuro|The person performs abdominal exercises in a dark environment.|
|17|flexao-com-pesos-no-escuro|The person does push-ups with weights in a dark environment.|
|18|agachamentos-no-escuro|The person performs squats exercise in a dark environment.|
|19|busto-do-manequim-no-escuro|The person falls backward while holding a mannequin torso in a dark environment.|
|20|entrar-agachar-e-para-no-escuro|The person walks to the center of the room, squats down, stands up, and leaves, all in a dark environment.|
|21|andar-agachado-no-escuro|The person walks while crouched in a dark environment.|
|22|toalha-na-cabeca-no-escuro|The person walks with a towel wrapped around their head (turban) in a dark environment.|
|23|sentar-e-com-dificuldade|The person struggles to transition from a sitting to a standing position in a chair.|
|24|sentar-levantar-com-dificuldade-no-escuro|The person struggles to transition from a sitting to a standing position in a chair in a dark environment.|
|25|queda-com-manequim|The person falls backward while holding a mannequin torso.|
|26|teste-camisa-com-botoes|The person interacts with a button-up shirt hanging on a hanger.|
|27|polichinelo|The person performs jumping jacks exercise.|
|28|apoio-de-frente|The person engages in a front support exercise (plank).|
|29|abdominal|The person performs abdominal exercises.|
|30|flexao-com-pesos|The person does push-ups with weights.|
|31|agachamento|The person performs squats exercise.|
|32|entrar-e-agachar|The person walks to the center of the room and squats down.|
|33|andar-agachado|The person walks while crouched.|
|34|toalha-na-cabeca|The person walks with a towel wrapped around their head (turban).|
|35|sentar-levantar-com-dificuldade|The person struggles to walk with hands behind their back, then sits, stands, and exits the room.|
|36|teste-com-cachorro|The person is walking and engaging with a dog.|



## Download <a name = "download"></a>
 
 To access this content, please complete the following [form](https://forms.gle/fxcDziZSrp4zL9Uc6) to acquire the decoding key. You can find the download link [here](https://mega.nz/folder/u9dynToD).

## Authors <a name = "authors"></a>

- [@eduardodut](https://github.com/eduardodut)
- [@mandreia](https://github.com/mandreia)
- [@thiagoRCOliveira](https://github.com/thiagoRCOliveira)



