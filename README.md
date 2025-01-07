<div align="center">
  <img src="https://user-images.githubusercontent.com/51358498/230220611-5b72ec57-3b41-480d-904d-80c1629e42c3.png" alt="osag" width="40%">
</div>

Welcome to the OSA repository for all things open-source in agricultural technology (agritech) development. This accompanies the OpenSourceAg newsletter, which you can sign up to [here](https://openagtech.beehiiv.com/subscribe). 

The idea behind this repository is to collate all open-source datasets and projects in agtech in one place for easy reference and to get a better picture of what is out there.

### Contributing
If you see a dataset is missing or you find an error in the tables, please submit a pull request or issue detailing the changes.

## Overview
* [Datasets](#datasets)
  * [Weeds](#weeds)
  * [Insects](#insects)
  * [Diseases](#diseases)
  * [Crop Phenotyping](#crop-phenotyping)
  * [Fruit Counting](#fruit-counting)
* [Algorithm Development](#algorithm-development)
* [In-field Deployment](#in-field-deployment)

# Datasets
Annotated image data is the backbone of precision agricultural operations such as site-specific weed control. This data is essential for training algorithms that can find weeds, insects and count fruit on the tree. A summary of datasets from each domain are provided below. Click on the drop-down list to find out more.

## Weeds
<details>
<summary>Open-access image datasets of weeds</summary>
<br>

| Dataset | Task | Image Number | Class Number | Species | Description |
|---------|------|--------------|--------------|---------|-------------|
| [Agriculture-Vision]((https://github.com/SHI-Labs/Agriculture-Vision)) | Instance Segmentation | |  |  | Aerial images for detecting weeds in various agricultural fields. |
| [Carrot-Weed](https://github.com/lameski/rgbweeddetection)| Segmentation  | 39| 2| carrot (Daucus carota ssp. sativus), unspecified weeds|  |
| [Corn/Lettuce/Radish](https://github.com/zhangchuanyin/weed-datasets)| Classification| 7200| 8| maize (Zea mays), Canada thistle (Cirsium arvense), fat hen (Chenopodium album), bluegrass (Poa spp.), lettuce, radish | |
| [CottonWeeds](https://www.kaggle.com/yuzhenlu/cottonweedid15)| Classification| 5187| 15 | morningglory (Ipomoea spp.), carpetweed (Mollugo verticillata), Palmer amaranth (Amaranthus palmeri), waterhemp (Amaranthus tuberculata), purslane (Portulaca spp.), nutsedge (Cyperus spp.), eclipta (Eclipta prostrata), sicklepod (Senna obtusifolia), spotted spurge (Euphorbia maculata), ragweed (Ambrosia spp.), goosegrass (Eleusine indica), prickly sida (Sida spinosa), crabgrass (Digitaria spp.), swinecress (Lepidium spp.), spurred anoda (Anoda cristata) | |
| [CottonWeedDet12](https://zenodo.org/record/7535814#.ZC3um3ZByUk) | Object Detection | 5648 (9370 instances) | 12 | |  |
| [CWF-788](https://github.com/ZhangXG001/Real-Time-Crop-Recognition)| Segmentation  | 788 | 1 | cauliflower (Brassica oleracea var. botrytis) | |
| [CWFID](https://github.com/cwfid)   | Segmentation  | 60           | 2            | carrot, unspecified weeds | |
| [CWD30](https://cwd-30.github.io/cwd-30/index.html) | Classification, Segmentation | 219,778 | 20 weed, 10 crop | Asian flatsedge (*Cyperus microiria*), Asiatic dayflower (*Commelina communis*), Bean (*Phaseolus vulgaris*), Bloodscale sedge (*Carex haematostoma*), Cockspur grass (*Echinochloa crus-galli*), Copperleaf (*Acalypha spp.*), Corn (*Zea mays*), Early barnyard grass (*Echinochloa oryzoides*), Fall panicum (*Panicum dichotomiflorum*), Finger grass (*Digitaria sanguinalis*), Foxtail millet (*Setaria italica*), Goosefoot (*Chenopodium album*), Great millet (*Sorghum bicolor*), Green foxtail (*Setaria viridis*), Green gram (*Vigna radiata*), Henbit (*Lamium amplexicaule*), Indian goosegrass (*Eleusine indica*), Korean dock (*Rumex crispus*), Livid pigweed (*Amaranthus lividus*), Nipponicus sedge (*Carex nipponica*), Peanut (*Arachis hypogaea*), Perilla (*Perilla frutescens*), Poa annua (*Poa annua*), Proso millet (*Panicum miliaceum*), Purslane (*Portulaca oleracea*), Red bean (*Phaseolus angularis*), Redroot pigweed (*Amaranthus retroflexus*), Sesame (*Sesamum indicum*), Smooth pigweed (*Amaranthus hybridus*), White goosefoot (*Chenopodium album*) | From the paper: Extensive crop-weed dataset with multi-view and multi-stage plant images. The repository includes pretrained models for transfer learning|
| [GrassClover](https://vision.eng.au.dk/grass-clover-dataset/)| Segmentation  | 8000         | 5            | white clover (Trifolium repens), red clover (Trifolium pratense), shepherd’s purse (Capsella bursa-pastoris), unspecified thistle, dandelion (Taraxacum officinale) | |
| [LincolnBeet](https://github.com/LAR/lincolnbeet_dataset#lincolnbeet_dataset)| Bounding box  | 4,402        | 2   | sugar beet (Beta vulgaris var. altissima), unspecified weeds| |
| [Plant Seedling Dataset](https://vision.eng.au.dk/plant-seedlings-dataset/)  | Segmentation  | 5,539        | 12  | maize, wheat (Triticum aestivum), sugar beet, scentless mayweed (Matricaria perforata), common chickweed (Stellaria media), shepherd’s purse, cleavers (Galium aparine), charlock (Sinapis arvensis), fat hen, small-flowered cranesbill (Geranium pusillum), blackgrass (Alopecurus myosuroides), loose silky-bent (Apera spica-venti) | |
| [Precision Sustainable Ag 2021 OpenCV Competition](https://weed-ai.sydney.edu.au/datasets/27813558-2b3c-496f-aab4-5e724a056213) | Bounding box  | 727| 7 | grass species (Poaceae spp.), horseweed (Erigeron canadensis), cowpea (Vigna unguiculata), crimson clover (Trifolium incarnatum), goosefoot (Chenopodium album), velvetleaf (Abutilon theophrasti), sunflower (Helianthus annuus) | |
| [RoboWeedMap](https://weed-ai.sydney.edu.au/datasets/aa0cb351-9b5a-400f-bb2e-ed02b2da3699) | Bounding box  | 1147         | 2            | Unspecified monocotyledonous, Unspecified dicotyledonous| |
| [Sandplain Lupins](https://figshare.com/articles/dataset/Segmentation_of_sandplain_lupin_weeds_from_morphologically_similar_narrow-leafed_lupins_in_the_field/21746669) | Segmentation | 795 (7989 instances) | 1 | Sandplain lupin (Lupinus cosentinii) | This repository contains five datasets collected in the field by a DJI Phantom 4 or smartphone in the northern wheatbelt of Western Australia. |
| [Soybean/Grass/Broadleaf/Soil](https://data.mendeley.com/datasets/3fmjm7ncc6/2)| Segmentation  | 15,336       | 3| soybean (Glycine max), grass weeds, broadleaf weeds| |
| [Sugar beets](http://www.ipb.uni-bonn.de/data/sugarbeets2016)| Segmentation  | 300          | 10           | sugar beet, Nine unspecified weed species| |
| [Weed-AI](https://weed-ai.sydney.edu.au)| All  | Hosting platform |     || Includes over 30,000 images with bounding box annotation sourced from datasets across the internet |
| [WeedMap](https://github.com/viariasv/weedMap)| Segmentation  | 10,196       | 2            | sugar beet| |
| [WeedNet](https://github.com/inkyusa/weedNet)| Segmentation  | 155| 2| sugar beet, unspecified weeds| |

</details>

## Insects
<details>
<summary>Open-access image datasets of insects</summary>
<br>

| Dataset | Task | Image Number | Classes | Description |
|---------|------|--------------|---------|-----------|
| [IP102](https://github.com/xpwu95/IP102) | Classification/ object detection | Classification: >75,000, bounding box: 19,000 | 102 | A very large open-source dataset of insect pests. The IP102 is annotated with a hierarchical taxonomy and the insect pests which mainly affect one specific agricultural product are grouped into the same upper-level category. [The full class list](https://github.com/xpwu95/IP102/blob/master/classes.txt)|

</details>

## Diseases
<details>
<summary>Open-access image datasets of plant diseases</summary>
<br>

| Dataset | Task | Image Number | Classes | Description |
|---------|------|------------|-----------|-------------|
| [PlantVillage](https://github.com/spMohanty/PlantVillage-Dataset) | Image Classification | 54,306 | 14 crop species, 26 diseases | Dataset with a focus on plant disease detection. | 
| [Dhan-Shomadhan: A Dataset of Rice Leaf Disease Classification for Bangladeshi Local Rice](https://data.mendeley.com/datasets/znsxdctwtt/1) | Image Classification | 1106 | 5 dieases (Brown Spot, Leaf Scaled, Rice Blast, Rice Turngo, Steath Blight) | An image classification dataset for five disease in Bangladeshi rice production, in field and white backgrounds. |

</details>

## Crop Phenotyping
<details>
<summary>Open-access image datasets for crop phenotyping</summary>
<br>

| Dataset | Task | Image Number | Classes | Description |
|---------|------|--------------|---------|-----------|
| [Global Wheat Head Dataset](http://www.global-wheat.com/)| Object detection/ segmentation | GWHD2020 - 4700, GWHD2021 - 6422 | wheat heads | A field-collected dataset with wheat heads annotated with either bounding boxes (2020) or segmentation (2021). The GWHD2021 builds on the GWHD2020 by adding 1722 images and segmentation level annotations. Both can be downloaded from the link provided. |

</details>

## Fruit Counting
<details>
<summary>Open-access image datasets for fruit counting and yield estimation</summary>
<br>

| Dataset | Task | Image Number | Classes | Description |
|---------|------|--------------|---------|-------------|
| [KFuji RGB-DSM dataset](https://www.grap.udl.cat/en/publications/kfuji-rgb-ds-database/) | Object Detection | 967 (12,839 instances) | 1 (fuji apples) | RGB and Depth images of apple trees for fruit detection and counting. | [KFuji RGB-DSM](https://github.com/ajdude/KFuji_RGB-DSM_Dataset) |
| [MinneApple](https://rsn.umn.edu/projects/orchard-monitoring/minneapple) | Object detection/ segmentation | 1 (apples) | 1000 (41,000 instances) | A comprehensive dataset for developing apple detection and segmentation algorithms. Representative results are provided for yield estimation. |

</details>

# Algorithm Development
<details>
<summary>Tools for improving the algorithm development process.</summary>
<br>

| Project Name | Task |  Description |
|--------------|------|--------------|
| [Project AgML](https://github.com/Project-AgML/AgML) | ML Pipeline | Standardising the development of ML algorithms, specific to agricultural data. |
| [RootPainter](https://github.com/Abe404/root_painter) | Custom segmentation | RootPainter is a GUI-based software tool for the rapid, corrective training of deep neural networks for use in biological image analysis. RootPainter uses a client-server architecture, allowing it to be used on a standard laptop with access to Google Colab or to be installed and run locally. |
| [Segment-Anything Model (SAM)](https://segment-anything.com/) | Zero-shot segmentation | A recently released tool for zero-shot segmentation of images from Meta Research. Whilst not trained on agricultural data (though one plant dataset is used), the algorithm learns the concept of objects and can extrapolate well into unseen areas. |

</details>

# In-Field Deployment

<details>
<summary>Open-source hardware projects for field use.</summary>
<br>

| Project Name | Task |  Description |
|--------------|------|--------------|
| [AgOpenGPS](https://discourse.agopengps.com/) | GPS Guidance | A globally popular open-source GPS guidance system for tractors and implements, with substantial user base and development community. AgOpenGPS features a substantial user interface for additional features such as variable rate and mapping. |
| [OpenWeedLocator (OWL)](https://github.com/geezacoleman/OpenWeedLocator) | Site-specific weed control | A DIY weed detection device based around the Raspberry Pi and Google Coral. Complete instructions for building and deploying. |
| [Twisted Fields - Acorn](https://github.com/Twisted-Fields/acorn-robot-electronics) | Robotic Platform | Acorn is a solar-powered, light-weight, and open source Precision Farming Rover (PFR) for in-field use. |

</details>
