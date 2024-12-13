<!-- PROJECT LOGO -->
<br />
<p align="center">
<!--   <a href="https://github.com/catiaspsilva/README-template">
    <img src="images/gators.jpg" alt="Logo" width="150" height="150">
  </a> -->

  <h3 align="center">Nutrition Table Extraction Model</h3>

  <p align="center">
    Nutrition Table Extraction Model integrating with CUDA, cuDNN, TensorRT
    <br />
    <a href="https://github.com/FITS-AI/Machine_Learning_OCR/blob/main/table_extractor/table_extractor.ipynb"><strong>Go»</strong></a>
    <br />
    <br />
    <a href="#usage">View Demo</a>
    ·
    <a href="https://github.com/FITS-AI/Machine_Learning_OCR/issues">Report Bug</a>
    ·
    <a href="https://github.com/FITS-AI/Machine_Learning_OCR/issues">Request Feature</a>
  </p>
</p>



<!-- TABLE OF CONTENTS -->
<details open="open">
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#dependencies">Dependencies</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
<!--     <li><a href="#usage">Usage</a></li> -->
<!--     <li><a href="#roadmap">Roadmap</a></li> -->
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#authors">Authors</a></li>
    <li><a href="#acknowledgements">Acknowledgements</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

The Nutrition Table Extraction project aims to develop an efficient solution for automatically detecting and extracting nutrition information from scanned images of nutrition tables..

[Here we go to Notebook](https://github.com/FITS-AI/Machine_Learning_OCR/blob/main/table_extractor/table_extractor.ipynb)

This project combines OCR techniques with table extraction models to detect tables within images and extract text in a structured manner, it can handle different types of table formats
<!-- GETTING STARTED -->
## Getting Started

In this section you should provide instructions on how to use this repository to recreate your project locally.

### Dependencies

Here, list all libraries, packages and other dependencies that need to be installed to run your project. Include library versions and how should be installed if a special requirement is needed.

#### Opsional
Download, install and setup to get more speed using internal GPU
Using:
<a href="https://developer.nvidia.com/cuda-toolkit-archive">CUDA 11.2</a>
<a href="https://developer.nvidia.com/rdp/cudnn-archive">cuDNN 8.1.1</a>
<a href="https://developer.nvidia.com/tensorrt">TensorRT 8.2.2.1</a>

* Pandas 2.2.3
  ```sh
  pip install pandas==2.2.3
  ```
* OpenCV 1.0.0
  ```sh
  pip install cv==1.0.0
  ```
* Numpy 1.26.4
  ```sh
  pip install numpy==1.26.4
  ```
* Matplotlib 3.9.2
  ```sh
  pip install matplotlib==3.9.2
  ```
* Albumentations 3.9.2
  ```sh
  pip install albumentations==1.4.21
  ```
* Tensorflow 2.10.1
  ```sh
  pip install tensorflow==2.10.1
  ```

### Installation

1. Clone the repo
   ```sh
   git clone https://github.com/FITS-AI/Machine_Learning_OCR.git
   ```
2. Running the table_extractor.ipynb

<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to be learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch
3. Commit your Changes 
4. Push to the Branch 
5. Open a Pull Request


<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE` for more information.


<!-- Authors -->
## Authors

Theodorus Limbong - [@linkedin](https://www.linkedin.com/in/theodorus-limbong-6479b8279/) - contacttheodorus@gmail.com


<!-- ACKNOWLEDGEMENTS -->
## Acknowledgements
Acknowledge any individual, group, institution or service.
* [off-nutrition-table-extractor](https://github.com/openfoodfacts/off-nutrition-table-extractor/tree/master)

## Thank you

<!-- If this is useful: [![Buy me a coffee](https://www.buymeacoffee.com/assets/img/guidelines/download-assets-sm-1.svg)](https://www.buymeacoffee.com/catiaspsilva) -->
