<!--
Hey, thanks for using the awesome-readme-template template.  
If you have any enhancements, then fork this project and create a pull request 
or just open an issue with the label "enhancement".

Don't forget to give this project a star for additional support ;)
Maybe you can mention me or this repo in the acknowledgements too
-->

<!--
This README is a slimmed down version of the original one.
Removed sections:
- Screenshots
- Running Test
- Deployment
- FAQ
-->

<div align="center">
  <h1>SmartDumbDoorbell</h1>
  
  <p>
    A simple ESPHome/Home Assistant-based battery-powered wifi doorbell
  </p>

  
<!-- Badges -->
<p>
  <a href="https://github.com/JustEnoughDucks/SmartDumbDoorbell/graphs/contributors">
    <img src="https://img.shields.io/github/contributors/JustEnoughDucks/SmartDumbDoorbell" alt="contributors" />
  </a>
  <a href="">
    <img src="https://img.shields.io/github/last-commit/JustEnoughDucks/SmartDumbDoorbell" alt="last update" />
  </a>
  <a href="https://github.com/JustEnoughDucks/SmartDumbDoorbell/network/members">
    <img src="https://img.shields.io/github/forks/JustEnoughDucks/SmartDumbDoorbell" alt="forks" />
  </a>
  <a href="https://github.com/JustEnoughDucks/SmartDumbDoorbell/stargazers">
    <img src="https://img.shields.io/github/stars/JustEnoughDucks/SmartDumbDoorbell  " alt="stars" />
  </a>
  <a href="https://github.com/JustEnoughDucks/SmartDumbDoorbell/issues/">
    <img src="https://img.shields.io/github/issues/JustEnoughDucks/SmartDumbDoorbell" alt="open issues" />
  </a>
  <a href="https://github.com/JustEnoughDucks/SmartDumbDoorbell/blob/master/LICENSE">
    <img src="https://img.shields.io/github/license/JustEnoughDucks/SmartDumbDoorbell.svg" alt="license" />
  </a>
</p>
   
<h4>
    <a href="https://github.com/JustEnoughDucks/SmartDumbDoorbell">Documentation</a>
  <span> · </span>
    <a href="https://github.com/JustEnoughDucks/SmartDumbDoorbell/issues/">Report Bug</a>
  <span> · </span>
    <a href="https://github.com/JustEnoughDucks/SmartDumbDoorbell/issues/">Request Feature</a>
  </h4>
</div>

<br />

<!-- Table of Contents -->
# :notebook_with_decorative_cover: Table of Contents

- [About the Project](#star2-about-the-project)
  * [Features](#dart-features)
- [Getting Started](#toolbox-getting-started)
  * [Prerequisites](#bangbang-prerequisites)
  * [Installation](#gear-installation)
- [Usage](#eyes-usage)
- [Roadmap](#compass-roadmap)
- [Contributing](#wave-contributing)
- [License](#warning-license)
- [Contact](#handshake-contact)
- [Acknowledgements](#gem-acknowledgements)
  

<!-- About the Project -->
## :star2: About the Project

<!--<div align="center"> 
  <img src="https://placehold.co/600x400?text=Your+Screenshot+here" alt="screenshot" />
</div>--!>
<p>
During our renovation, the doorbell no longer worked, but there was no electricity nearby to place a video doorbell. We didn't trust no-name battery-powered doorbells and had terrible experiences with barely functional commercial point-to-point doorbells. I decided to make my own, cheap dumb doorbell with my existing Home Assistant and ESPHome infrastructure, with the option of putting in a Reolink camera in the future.
  </p>
<p>
This project uses the same mounting holes and general shape of the Reolink PoE Doorbell Camera for upgradability. It uses an SEEED Xiao ESP32-C3 because of low cost, small size, and integrated battery charging. It can accomodate up to a 1200 mAh battery. Since the ESP is in deep sleep for the majority of the time, the battery has a very long life. 
  </p>
<p>
The project only gives entities available to Home Assistant, so it is up to you to add automations triggered on the entity to send notifications on your phone or play through a connected speaker.
  </p>

<!-- Features -->
### :dart: Features

- Long battery life & battery reporting
- Wifi-Enabled through ESPHome
- Easy integration with HomeAssistant

<!-- Getting Started -->
## 	:toolbox: Getting Started

<!-- Prerequisites -->
### :bangbang: Prerequisites

- Existing HomeAssistant installation with ESPHome
- Basic soldering skills
- Available wifi connection

<!-- Installation -->
### :gear: Installation



<!-- Run Locally -->
### :running: Run Locally



<!-- Usage -->
## :eyes: Usage


<!-- Roadmap -->
## :compass: Roadmap

* [x] Mechanical Design
* [x] Electrical Design
* [x] ESPHome Config
* [ ] Full Testing
* [ ] Documentation

<!-- Contributing -->
## :wave: Contributing

<a href="https://github.com/JustEnoughDucks/SmartDumbDoorbell/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=JustEnoughDucks/SmartDumbDoorbell" />
</a>


Contributions are always welcome!


<!-- License -->
## :warning: License

Distributed under the GPL-3.0. See LICENSE.txt for more information.


<!-- Contact -->
## :handshake: Contact

Project Link: [https://github.com/JustEnoughDucks/SmartDumbDoorbell](https://github.com/JustEnoughDucks/SmartDumbDoorbell)

<!-- Acknowledgments -->
## :gem: Acknowledgements

Use this section to mention useful resources and libraries that you have used in your projects.

 - [Shields.io](https://shields.io/)
 - [Awesome README](https://github.com/matiassingers/awesome-readme)
 - [Emoji Cheat Sheet](https://github.com/ikatyang/emoji-cheat-sheet/blob/master/README.md#travel--places)
 - [Readme Template](https://github.com/othneildrew/Best-README-Template)
