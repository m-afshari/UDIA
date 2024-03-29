# UDIA
Unsupervised Discovery of Image Annotation

## Description

Many images include details that we'd want to review but we don't have enough information to do so. This may happen, for example, if you have an idea of what an empty road should look like but have no idea what else could exist on it. Here, we provide a system for detecting malignant areas in a Whole Slide Image (WSI) based on previously detected healthy data. There are many WSIs with general diagnoses, however it is difficult to discover WSIs that are annotated to the greatest degree possible. There's no need to annotate anything beforehand using this technique.

![alt text](https://github.com/m-afshari/UDIA/blob/main/SamplePatch.png?raw=true)


## Getting Started



### Dependencies

* Recommended for Testing on Linux ubuntu
* Pytorch (torch and torchvision)
* Glob
* Pillow (PIL fork)
* Numpy
* tqdm

### Dataset

* To download the dataset use this [link](https://camelyon16.grand-challenge.org/Data/). 

### Executing program

* How to run the program
* Step-by-step bullets
Gradient calculations are done based on the [SPSR](https://github.com/Maclory/SPSR/blob/881e78111c418d5e0a0150b213e0f8c3525e8089/code/models/modules/architecture.py) repo.
```
class Get_gradient_nopadding(nn.Module):
```

## Assessment

For assessments the [PIQA](https://github.com/francois-rozet/piqa) library (PyTorch Image Quality Assessment) is used and the operations are suggested to be done on the same pytorch results of the network calculations for faster inference.

```
command to run if program contains helper info
```

## Version History

* 0.1
    * Initial Release

## License

This project is licensed under the MIT License - see the LICENSE.md file for details

## Acknowledgments

Inspiration, code snippets, etc.

* [awesome-readme](https://github.com/matiassingers/awesome-readme)
* [SPSR](https://github.com/Maclory/SPSR)


** So if you'd want to contribute, please send me a note! **
