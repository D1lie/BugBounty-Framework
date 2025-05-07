<h1 align="center">
 <a>
  <img src="d1lie.png" width="200px" alt="D1lie Logo"></a>
  <br>
  The D1lie Framework
  <br>
</h1>


<p align="center"><img src="Add_FQDN.png" name="Image2" alt="Screenshot of Framework" align="bottom" width="669" height="265" border="0"/>

<img src="Dashboard_full.png" name="Image3" alt="Screenshot of Framework" align="bottom" width="575" height="942" border="0"/>

<img src="Dashboard.png" name="Image4" alt="Screenshot of Framework" align="bottom" width="688" height="410" border="0"/>

<img src="CVE_Testing.png" name="Image5" alt="Screenshot of Framework" align="bottom" width="665" height="530" border="0"/>

<img src="Recon.png" name="Image6" alt="Screenshot of Framework" align="bottom" width="656" height="472" border="0"/>

</p>

## Quick Start

Paste this code block into a clean installation of [Kali Linux 2023.4](https://www.kali.org/get-kali/#kali-installer-images) to download, install, and run the latest stable Alpha version of the framework:
```
sudo apt update && sudo apt-get update
sudo apt -y upgrade && sudo apt-get -y upgrade
git clone https://github.com/D1lie/The-D1lie-Framework.git 
cd The-D1lie-Framework
./install.sh
```

## Install

The D1lie Framework includes a script that installs all the necessary tools, packages, etc. that are needed to run the framework on a clean installation of [Kali Linux 2023.4](https://www.kali.org/get-kali/#kali-installer-images).

***Please note that the only supported installation of this framework is on a clean installation of Kali Linux 2023.3.  If you choose to try and run the framework outside of a clean Kali install, I will not be able to help troubleshoot if you have any issues.***

```
./install.sh
```

**If you are using an ARM Processor, you will need to add the --arm flag to all Install/Run scripts**

```
./install.sh --arm
```

You will be prompted to enter various API keys and tokens when the installation begins.  **Entering these is not required to run the core functionality of the framework.  If you do not enter these API keys and tokens at the time of installation, simply hit enter at each of the prompts.  The keys can be added later to the `~/.keys` directory.  More information about how to add these keys manually can be found in the [Frequently Asked Questions](#faq) section of this README.** 

## Run the Web Application (Client and Server)

Once the installation is complete, you will be given the option to run the application by entering `Y`.  If you choose not the run the application immediately, or if you need to run the application after a reboot, simply navigate to the root directly and run the `run.sh` bash script.

```
./run.sh
```

**If you are using an ARM Processor, you will need to add the --arm flag to all Install/Run scripts**

```
./run.sh --arm
```


Howdy! I am paimon (D1lie) when I want to feel cooler than I
really am. The code in this repository started as a small collection
of scripts to help automate many of the common Bug Bounty hunting
processes I found myself repeating. Over time, I built a simple web
application with a MongoDB connection to manage my findings and
identify valuable data points. After 5 years of Bug Bounty hunting,
both part-time and full-time, I'm finally ready to package this
collection of tools into a proper framework.

 **The D1lie Framework** is designed to provide aspiring Application Security Engineers with
all the tools they need to leverage Bug Bounty hunting as a means to
learn valuable, real-world AppSec concepts and make 💰 doing it! My
goal is to lower the barrier of entry for Bug Bounty hunting by
providing easy-to-use automation tools in combination with
educational content and how-to guides for a wide range of Web-based
and Cloud-based vulnerabilities. In combination with my YouTube
content, this framework will help aspiring Application Security
Engineers to quickly and easily understand real-world security
concepts that directly translate to a high paying career in Cyber
Security. 

In addition to using this tool for Bug Bounty Hunting,
aspiring engineers can also use this Github Repository as a canvas to
practice collaborating with other developers! This tool was inspired
by Metasploit and designed to be modular in a similar way. Each
Script (Ex: `wildfire.py` or `slowburn.py`) is basically an algorithm
that runs the Modules (Ex: `fire-starter.py` or `fire-scanner.py`) in
a specific patter for a desired result. Because of this design, the
community is free to build new Scripts to solve a specific use-case
or Modules to expand the results of these Scripts. By learning the
code in this framework and using Github to contribute your own code,
aspiring engineers will continue to learn real-world skills that can
be applied on the first day of a Security Engineer I position. My
hope is that this modular framework will act as a canvas to help
share what I've learned over my career to the next generation of
Security Engineers! Trust me, we need all the help we can get!! 
</p>
</body>
</html>