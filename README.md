<br/>
<div align="center">
  <img src="https://github.com/MrCjxer/marzban-templates/blob/dca23a0ecbee84839686a1b928a2dc7e8aba4089/template-01/screenshot.jpg" alt="screenshot" width="512" height="auto">
</div>

<p align="center">
  <h3 align="center">MrCjxer-Subcription-ForWard</h3>

  <p align="center">
    A good tool to mediate between the border guard and the user, for the subscription link
    <br/>
    <br/>
    <a href="https://github.com/MrCjxer/MrCjxer-Subcription-ForWard/issues">Report Bug</a>
    .
    <a href="https://github.com/MrCjxer/MrCjxer-Subcription-ForWard/issues">Request Feature</a>
  </p>
</p>
 
![Contributors](https://img.shields.io/github/contributors/MrCjxer/MrCjxer-Subcription-ForWard?color=dark-green) ![Forks](https://img.shields.io/github/forks/MrCjxer/MrCjxer-Subcription-ForWard?style=social) ![Stargazers](https://img.shields.io/github/stars/MrCjxer/MrCjxer-Subcription-ForWard?style=social) ![License](https://img.shields.io/github/license/MrCjxer/MrCjxer-Subcription-ForWard) 

## Table Of Contents

* [About the Project](#about-the-project)
* [Getting Started](#getting-started)
  * [Prerequisites](#prerequisites)
  * [Installation](#installation)
* [Customize and Modify Source Code](#customize-and-modify-source-code)
* [Roadmap](#roadmap)
* [Contributing](#contributing)
* [License](#license)
* [Authors](#authors)
* [Acknowledgements](#acknowledgements)

## About The Project

The advantage of mediation is that if the Internet becomes an intranet subscription, the links will still work
And if the IP of the VPN server is filtered or any other problem persists, you can access the subscription link
Special thanks to Muhammad Ashouri for creating the subscription link template.

> Note: This script works both on the web and in V2ray clients


## Getting Started

Follow the instructions below to get started

### Prerequisites

Web host from: [www.bestla.net](https://www.bestla.net/portal/aff.php?aff=263)<br>
Domain<br>
PHP 8.0+

### Installation

1. Download the latest version of the [releases](https://github.com/MrCjxer/MrCjxer-Subcription-ForWard/releases/latest)
2. Upload to your web host
3. Unzip the zip file
4. Edit the file `index.php` in the path `/sub/index.php` and replace the IP address and port of your border panel in `BASE_URL` line <a href="https://github.com/MrCjxer//blob/b8f02880524fdc29894653c4b4f2b703caee0ae5/sub/index.php#L9">9</a><br>
<sub>Note: If your panel does not use SSL, change https to http in `BASE_URL` line <a href="https://github.com/MrCjxer//blob/b8f02880524fdc29894653c4b4f2b703caee0ae5/sub/index.php#L9">9</a></sub><br>
<sub>Note: If your panel port is 443 or 80, there is no need to enter the port</sub>
5. Edit `.env` in path `/opt/marzban/` and add `XRAY_SUBSCRIPTION_URL_PREFIX="https://ir-doamin.com"`<br>
<sub>Note: The `.env` file is hidden</sub><br>
<sub>Note: Put your web host domain address instead of `ir-domain.com`</sub>
6. Restart Marzban


## Customize and Modify Source Code
* You can change default settings from settings variable in `index.php`, here line <a href="https://github.com/MrCjxer/MrCjxer-Subcription-ForWard/blob/b8f02880524fdc29894653c4b4f2b703caee0ae5/view-service/index.php#L207">207</a>
* You can also change tutorial from `appsJson` variable in `index.php`, here line <a href="https://github.com/MrCjxer/MrCjxer-Subcription-ForWard/blob/b8f02880524fdc29894653c4b4f2b703caee0ae5/view-service/index.php#L48">48</a><br>
<sub>For tutorial video, you need to set direct link of video to tutorial of json</sub>
* To change logo you can change **src** in line <a href="https://github.com/MrCjxer/MrCjxer-Subcription-ForWard/blob/b8f02880524fdc29894653c4b4f2b703caee0ae5/view-service/index.php#L236">236</a>

## Roadmap

See the [open issues](https://github.com/MrCjxer/MrCjxer-Subcription-ForWard/issues) for a list of proposed features (and known issues).

## Contributing

Contributions are what make the open source community such an amazing place to be learn, inspire, and create. Any contributions you make are **greatly appreciated**.
* If you have suggestions for adding or removing projects, feel free to [open an issue](https://github.com/MrCjxer/MrCjxer-Subcription-ForWard/issues/new) to discuss it, or directly create a pull request after you edit the *README.md* file with necessary changes.
* Please make sure you check your spelling and grammar.
* Create individual PR for each suggestion.
* Please also read through the [Code Of Conduct](https://github.com/MrCjxer/MrCjxer-Subcription-ForWard/blob/main/CODE_OF_CONDUCT.md) before posting your first idea as well.

### Creating A Pull Request

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

Distributed under the MIT License. See [LICENSE](https://github.com/MrCjxer/MrCjxer-Subcription-ForWard/blob/master/LICENSE) for more information.

## Authors

* **AC Lover** - *Backend developer* - [AC Lover](https://github.com/MrCjxer) - *Build AC Subcription script*
* **Muhammad Ashouri** - *Front developer* - [Muhammad Ashouri](https://github.com/MuhammadAshouri) - *Build template*

## Acknowledgements

* [Gozargah](https://github.com/Gozargah/Marzban)
* [Muhammad Ashouri](https://github.com/MuhammadAshouri)

  
<h1 align="left">Donation</h1>
<p align="left">https://nowpayments.io/donation/ACLover</p>
