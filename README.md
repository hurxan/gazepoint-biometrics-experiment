# GazepointBiometrics PsychoPy Experiment
<div id="top"></div>

<!-- PROJECT SHIELDS -->

[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]

<br />
<div align="center">
<h3 align="center">GazepointBiometrics PsychoPy Experiment</h3>
  <p align="center">
    Simple PsychoPy experiment using the Gazepoint Eyetracker + Gazepoint Biometrics Kit.
    <br />
    <a href="https://www.gazept.com/downloads/"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/andreisenyuva/GazepointBiometrics_Experiment/issues">Report Bug</a>
    ·
    <a href="https://github.com/andreisenyuva/GazepointBiometrics_Experiment/issues">Request Feature</a>
  </p>
</div>



<!-- TABLE OF CONTENTS -->
<details>
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
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

This PsychoPy experiment runs multiple trials with a countdown timer. <br>
While the experiment is running it collects data from the Gazepoint Eyetracker (in our case from the GP3) and from the Biometrics Kit.


<p align="right">(<a href="#top">back to top</a>)</p>


### Built With

* [Python](https://www.python.org/)
* [PsychoPy](https://www.psychopy.org/)

<p align="right">(<a href="#top">back to top</a>)</p>


<!-- GETTING STARTED -->
## Getting Started

### Important

Due to the Gazepoint Control being available exclusively for Windows this experiment won't work on other Operating Systems (tested on W10)

### Prerequisites

* Gazepoint Control
* PsychoPy
* Opengaze library (included inside the project)


### Installation

1. Clone the repo
   ```sh
   git clone https://github.com/andreisenyuva/GazepointBiometrics_Experiment.git
   ```
2. Open the downloaded repo and navigate to the `src` folder

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- USAGE EXAMPLES -->
## Usage

As a result, at the end of the task an output file will be generated (`date_time.tsv`) inside the experiment folder.

The generated file contains data from:<br>
* The GP3 (`FPOGX`, `FPOGY`, `...`)
* The Biometrics Kit (`GSR	`, `HR`, `HRP`, `...`)

_For more details about the data, please refer to the [OpenGaze API Documentation](https://www.gazept.com/downloads/)_

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- CONTRIBUTING -->
## Contributing

Contributions are highly appreciated.

If you have a suggestion that would make this better, please fork the repo and create a pull request.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- CONTACT -->
## Contact

Andrei Senyuva - hurcanandrei.senyuva@unipd.it

[Project Link](https://github.com/andreisenyuva/GazepointBiometrics_Experiment)

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- ACKNOWLEDGMENTS -->
## Acknowledgments

* [PsychoBuilder Template](https://github.com/jgeller112/GazePoint_PsychoBuilder_Template)

<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/andreisenyuva/GazePointBiometrics_Experiment.svg?style=for-the-badge
[contributors-url]: https://github.com/andreisenyuva/GazePointBiometrics_Experiment/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/andreisenyuva/GazePointBiometrics_Experiment.svg?style=for-the-badge
[forks-url]: https://github.com/andreisenyuva/GazePointBiometrics_Experiment/network/members
[stars-shield]: https://img.shields.io/github/stars/andreisenyuva/GazePointBiometrics_Experiment.svg?style=for-the-badge
[stars-url]: https://github.com/andreisenyuva/GazePointBiometrics_Experiment/stargazers
[issues-shield]: https://img.shields.io/github/issues/andreisenyuva/GazePointBiometrics_Experiment.svg?style=for-the-badge
[issues-url]: https://github.com/andreisenyuva/GazePointBiometrics_Experiment/issues
[product-screenshot]: images/screenshot.png
