# OpenSourceAgriculture (OSA)
Welcome to the OSA repository for all things open-source in agricultural technology (agritech) development. This accompanies the OpenSourceAgriculture newsletter, you can sign up to [here](https://opensourceag.beehiiv.com/subscribe). 

The idea behind this repository is to collate all open-source datasets and projects in agritech in one place for easy reference and to get a better picture of what is out there.

### Contributing
If you see a dataset is missing or you find an error in the tables, please submit a pull request or issue detailing the changes.

## Overview
* [Datasets]()
  * [Weeds]()
  * [Insects]()
  * [Diseases]()
  * [Crop Phenotyping]()
  * [Fruit Counting]()
* [Algorithm Development]()
* [In-field Deployment]()

# Datasets
## Weeds

| Dataset | Task | Image Number | Class Number | Species | Description |
|---------|---------------|--------------|--------------|-----------|-----------|
| [Agriculture-Vision]((https://github.com/SHI-Labs/Agriculture-Vision)) | Instance Segmentation | |  |  | Aerial images for detecting weeds in various agricultural fields. |
| [Carrot-Weed](https://github.com/lameski/rgbweeddetection)| Segmentation  | 39| 2| carrot (Daucus carota ssp. sativus), unspecified weeds|  |
| [Corn/Lettuce/Radish](https://github.com/zhangchuanyin/weed-datasets)| Classification| 7200| 8| maize (Zea mays), Canada thistle (Cirsium arvense), fat hen (Chenopodium album), bluegrass (Poa spp.), lettuce, radish | |
| [CottonWeeds](https://www.kaggle.com/yuzhenlu/cottonweedid15)| Classification| 5187| 15           | morningglory (Ipomoea spp.), carpetweed (Mollugo verticillata), Palmer amaranth (Amaranthus palmeri), waterhemp (Amaranthus tuberculata), purslane (Portulaca spp.), nutsedge (Cyperus spp.), eclipta (Eclipta prostrata), sicklepod (Senna obtusifolia), spotted spurge (Euphorbia maculata), ragweed (Ambrosia spp.), goosegrass (Eleusine indica), prickly sida (Sida spinosa), crabgrass (Digitaria spp.), swinecress (Lepidium spp.), spurred anoda (Anoda cristata) | |
| [CWF-788](https://github.com/ZhangXG001/Real-Time-Crop-Recognition)| Segmentation  | 788          | 1            | cauliflower (Brassica oleracea var. botrytis) |
| [CWFID](https://github.com/cwfid)   | Segmentation  | 60           | 2            | carrot, unspecified weeds | |
| [GrassClover](https://vision.eng.au.dk/grass-clover-dataset/)| Segmentation  | 8000         | 5            | white clover (Trifolium repens), red clover (Trifolium pratense), shepherd’s purse (Capsella bursa-pastoris), unspecified thistle, dandelion (Taraxacum officinale) | |
| [LincolnBeet](https://github.com/LAR/lincolnbeet_dataset#lincolnbeet_dataset)| Bounding box  | 4,402        | 2            | sugar beet (Beta vulgaris var. altissima), unspecified weeds| |
| [Plant Seedling Dataset](https://vision.eng.au.dk/plant-seedlings-dataset/)  | Segmentation  | 5,539        | 12           | maize, wheat (Triticum aestivum), sugar beet, scentless mayweed (Matricaria perforata), common chickweed (Stellaria media), shepherd’s purse, cleavers (Galium aparine), charlock (Sinapis arvensis), fat hen, small-flowered cranesbill (Geranium pusillum), blackgrass (Alopecurus myosuroides), loose silky-bent (Apera spica-venti) | |
| [Precision Sustainable Ag 2021 OpenCV Competition](https://weed-ai.sydney.edu.au/datasets/27813558-2b3c-496f-aab4-5e724a056213) | Bounding box  | 727| 7 | grass species (Poaceae spp.), horseweed (Erigeron canadensis), cowpea (Vigna unguiculata), crimson clover (Trifolium incarnatum), goosefoot (Chenopodium album), velvetleaf (Abutilon theophrasti), sunflower (Helianthus annuus) | |
| [RoboWeedMap](https://weed-ai.sydney.edu.au/datasets/aa0cb351-9b5a-400f-bb2e-ed02b2da3699)               | Bounding box  | 1147         | 2            | Unspecified monocotyledonous, Unspecified dicotyledonous| |
| [Soybean/Grass/Broadleaf/Soil](https://data.mendeley.com/datasets/3fmjm7ncc6/2)| Segmentation  | 15,336       | 3| soybean (Glycine max), grass weeds, broadleaf weeds| |
| [Sugar beets](http://www.ipb.uni-bonn.de/data/sugarbeets2016)| Segmentation  | 300          | 10           | sugar beet, Nine unspecified weed species| |
| [Weed-AI](https://weed-ai.sydney.edu.au)| All           | Hosting platform |             || |
| [WeedMap](https://github.com/viariasv/weedMap)| Segmentation  | 10,196       | 2            | sugar beet| |
| [WeedNet](https://github.com/inkyusa/weedNet)| Segmentation  | 155| 2| sugar beet, unspecified weeds| |

## Insects
| Dataset | Task | Image Number | Classes | Description |
|---------|------|--------------|---------|-----------|


## Diseases
| Dataset | Task | Image Number | Classes | Description |
|---------|------|------------|-----------|-------------|
| [PlantVillage](https://github.com/spMohanty/PlantVillage-Dataset) | Image Classification | 54,306 | 14 crop species, 26 diseases | Dataset with a focus on plant disease detection. | 
| [Dhan-Shomadhan: A Dataset of Rice Leaf Disease Classification for Bangladeshi Local Rice](https://data.mendeley.com/datasets/znsxdctwtt/1) | Image Classification | 1106 | 5 dieases (Brown Spot, Leaf Scaled, Rice Blast, Rice Turngo, Steath Blight) | An image classification dataset for five disease in Bangladeshi rice production, in field and white backgrounds. |

## Crop Phenotyping
| Dataset | Task | Image Number | Classes | Description |
|---------|------|--------------|---------|-----------|

## Fruit Counting
| Dataset | Task | Image Number | Classes | Description |
|---------|------|--------------|---------|-------------|
| [KFuji RGB-DSM dataset](https://www.grap.udl.cat/en/publications/kfuji-rgb-ds-database/) | Object Detection | 967 (12,839 instances) | 1 (fuji apples) | RGB and Depth images of apple trees for fruit detection and counting. | [KFuji RGB-DSM](https://github.com/ajdude/KFuji_RGB-DSM_Dataset) |

# Algorithm Development
| Project Name | Task |  Description |
|--------------|------|--------------|
| [Project AgML](https://github.com/Project-AgML/AgML) | ML Pipeline | Standardising the development of ML algorithms, specific to agricultural data. |

# In-Field Deployment
| Project Name | Task |  Description |
|--------------|------|--------------|
| [OpenWeedLocator (OWL)](https://github.com/geezacoleman/OpenWeedLocator) | Site-specific weed control | A DIY weed detection device based around the Raspberry Pi and Google Coral. Complete instructions for building and deploying. |
