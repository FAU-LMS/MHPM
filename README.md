# MHPM (Multispectral Household Plastic Material Database)

## Overview
Effective plastic recycling requires the accurate identification of polymer types. However, existing optical sorting systems often struggle to distinguish common household plastics reliably. To overcome this identification bottleneck, multispectral imaging is necessary to capture the unique near-infrared (NIR) spectral fingerprints of different materials. Therefore, a <ins>M</ins>ultispectral <ins>H</ins>ousehold <ins>P</ins>lastic <ins>M</ins>aterial database (MHPM) was developed, which can be processed to train and evaluate automated material classifiers. For this, the database contains multispectral recordings of the seven most common household plastics, captured by a nine-camera array setup equipped with distinct NIR bandpass filters. The approach to extract the spectral fingerprints involves a dedicated preprocessing pipeline that spatially aligns and normalizes the raw images to derive features such as wavelength intensity differences and false-color representations. Of course, this database also can be used for many other tasks, where reliable material identification is necessary, for example, evaluating machine learning models, optimizing spectral band selection, and developing cost-efficient industrial sorting pipelines.

## Database
The actual data can be found here: TBA

The MHPM database provides 25 scenes recorded from 800 nm to 1600 nm in 25 nm and 50 nm steps, resulting in 24 multispectral channels. Furthermore, one RGB image of each scene is contained. Additionally, the Spectral fingerprints of each material class are included. The images are cropped/upsampled to a resolution of 1740 x 1348 pixels.

The images are already calibrated, normalized, and registered and reconstructed.

Camera specifics
| | Grayscale camera | RGB camera | Short-wave infrared camera (SWIR)|
| Camera type | Allied Vision Alvium 1800 U-1240m | Allied Vision Alvium 1800 U-1240c | Allied Vision Alvium 1800 U-130m VSWIR        |
| Focal Length | 5mm    | 5mm       |  60.1mm      | 
| Image Sensor  | Sony IMX226   |    Sony IMX226     | Sony IMX990     | 
| Sonsor pixel size | 1.85μm   | 1.85μm       | 5μm      | 
| Resolution | 4024x3036   | 4024x3036      | 1296x1032     | 
| Frame rate | 35 fps | 35 fps | 130 fps|
| Bit depth | 10 | 10 | 10 |
| Lens transmission | 200 nm - 1150 nm | 300 nm - 1100 nm | 400 nm - 1700 nm |

## Framework Usage
In progress

## License
The database and source are licensed using TBA.
If you use the dataset or source for your research, you should cite the follwing paper:
```
TBA
```

## Acknowledgement
This work was supported by the Bayerische Forschungs- und Transformationsstiftung (BFS, Bavarian Transformation and Research Foundation) under project number AZ-1547-22.
