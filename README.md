<div id="top"></div>

<div align="center">
 <a href="https://github.com/Link-Wolf/ft_otp" title="Go to GitHub repo"><img src="https://img.shields.io/static/v1?label=Link-Wolf&message=ft_otp&color=blue&logo=github&style=for-the-badge" alt="Link-Wolf - ft_otp"></a>
 <a href="https://"><img src="https://img.shields.io/badge/42_grade-125%2F_100-brightgreen?style=for-the-badge" alt="42 grade - 125 / 100"></a>
 <a href="https://"><img src="https://img.shields.io/badge/Year-2022-ffad9b?style=for-the-badge" alt="Year - 2022"></a>
 <a href="https://github.com/Link-Wolf/ft_otp/stargazers"><img src="https://img.shields.io/github/stars/Link-Wolf/ft_otp?style=for-the-badge&color=yellow" alt="stars - ft_otp"></a>
 <a href="https://github.com/Link-Wolf/ft_otp/network/members"><img src="https://img.shields.io/github/forks/Link-Wolf/ft_otp?style=for-the-badge&color=lightgray" alt="forks - ft_otp"></a>
 <a href="https://github.com/Link-Wolf/ft_otp/issues"><img src="https://img.shields.io/github/issues/Link-Wolf/ft_otp?style=for-the-badge&color=orange" alt="issues - ft_otp"></a>
 <a href="https://www.linux.org/" title="Go to Linux homepage"><img src="https://img.shields.io/badge/OS-linux-blue?logo=linux&logoColor=white&style=for-the-badge&color=9cf" alt="OS - linux"></a>
</div>

<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a>
    <img src="https://www.42mulhouse.fr/wp-content/uploads/2022/06/logo-42-Mulhouse-white.svg" alt="Logo" width="192" height="80">
  </a>

  <h3 align="center">Piscine Cybersecurity - ft_otp</h3>

  <p align="center">
   <em>Nothing ever lasts forever...</em><br/>
    A TOTP (Time-based One-Time Password) generator
    <br />
    <br />
    <a href="https://github.com/Link-Wolf/ft_otp/issues">Report Bug</a>
    ·
    <a href="https://github.com/Link-Wolf/ft_otp/issues">Request Feature</a>
  </p>
</div>

<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#goal">Goal</a>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage-examples">Usage examples</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#contact">Contact</a></li>
  </ol>
</details>

<!-- GOAL -->
## Goal

<div align="center">
  <a>
	<img src="https://www.onespan.com/sites/default/files/styles/max_800x800/public/2022-07/One-Button-Authenticator.png?itok=1_3U88Dn" alt="ft_otp">
  </a>
</div>
</br>

This cybersecurity project aims to implement a TOTP (Time-based One-Time Password) system, which will be capable of generating ephemeral passwords from a master key based on the RFC 6238 standard.
The program has to allow the user to store a initial password in file, and that is capable of generating a new one time password every time it is requested.
> The program is written in Python3


<p align="right">(<a href="#top">back to top</a>)</p>

<!-- GETTING STARTED -->
## Getting Started


### Prerequisites

- [Python3](https://www.python.org/downloads/)
- The following modules:
	- qrcode
	- rsa
	- pillow
	- tkinter
	- python-tk


### Installation

1. Clone the repo

   ```sh
   $> git clone https://github.com/Link-Wolf/ft_otp.git
   ```

2. Launch the script

	
   ```sh
   $> cd ft_otp
   $> ft_otp [-h] (-g HEX FILE | -k KEY FILE | -i)
   ```
   > -h, --help : display help
   > -g HEX_FILE : generate a .key file from a 64 characters hexadecimal key
   > -k KEY_FILE : generate a 1 time password that expires after 30 secs from a .key file
   > -i, --interface : interface mode


<p align="right">(<a href="#top">back to top</a>)</p>

<!-- USAGE EXAMPLES -->
## Usage examples

#### Using in command line

![](https://cdn.discordapp.com/attachments/907303542438629406/1129031415732912128/image.png)

#### Using in interface mode

![](https://cdn.discordapp.com/attachments/907303542438629406/1129030535033925784/image.png)

<p align="right">(<a href="#top">back to top</a>)</p>


<!-- CONTRIBUTING -->
## Contributing

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- CONTACT -->
## Contact

Mail : xxxxxxx@student.42mulhouse.fr

Project Link: [https://github.com/Link-Wolf/ft_otp](https://github.com/Link-Wolf/ft_otp)

<p align="right">(<a href="#top">back to top</a>)</p>
