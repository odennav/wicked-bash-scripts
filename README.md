# Wicked Bash Scripts

Welcome to the "Linux-and-Unix-Bash-Scripts" repository!
This collection of scripts is based on the book **"Wicked Cool Shell Scripts - 101 Scripts for Linux, OS X, and Unix Systems"**

![Wicked Cool Shell Scripts](https://m.media-amazon.com/images/I/91yPEGKwJ1L._AC_UF350,350_QL50_.jpg)

## Overview

The scripts in this repository have been curated to provide beginners with a comprehensive learning experience in Bash scripting. Each script is accompanied by detailed comments, offering a line-by-line explanation to help newcomers grasp the concepts and techniques involved.

## Book Credits

Special thanks to the authors of the book:
- Dave Taylor
- Brandon Perry

Their insightful work is the core for these scripts, and their expertise is acknowledged with gratitude.

## Modifications

Please note that some modifications have been made to the original scripts to enhance the learning experience. These adjustments aim to encourage a deeper understanding of Bash scripting and foster a hands-on approach to the material.

## Getting Started

To make your learning experience more practical, virtual machines (VMs) have been set up for you to run and test the scripts. [Vagrant](https://www.vagrantup.com/) was used to create and manage these VMs.

1. **Install Vagrant:**
   If you haven't installed Vagrant yet, you can download it [here](https://www.vagrantup.com/downloads.html) and follow the installation instructions for your operating system.

2. **Clone the Repository:**
   Clone this repository to your local machine to get the scripts and the Vagrant file.
   You might have to clone the repo again in Linux VM.
   First install git in VM.


   ```bash
   sudo apt-get install git
   git clone https://github.com/odennav/wicked-bash-scripts.git
   cd Linux-Unix-Bash-Scripts
   ```

3. **Spin Up Linux VMs:**
   ```bash
   vagrant up cool
   ```

4. **Access the VM:**
   ```bash
   vagrant ssh cool

5. **Practice with the Scripts:**

   Open a script file with a text editor of your choice, and type out every line of code for hands-on learning and to understand how it works


6. **Execute the scripts to see the results**:
   ```bash
   bash script_name.sh <arguments>
   ```

   ```bash
   script_name.sh <arguments>
   ```

   ```bash
   ./script_name.sh <arguments>
   ```


## Contribution Guidelines

If you have your own wicked cool scripts or improvements to existing ones, suggestions are welcome! Please support authors by purchasing this book [here](https://www.amazon.com/Wicked-Cool-Shell-Scripts-2nd/dp/1593276028)

Happy Scripting!

