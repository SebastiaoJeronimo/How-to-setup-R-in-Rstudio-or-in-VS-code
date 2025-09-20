# How-to-setup-R-in-Rstudio-or-in-VS-code

This repo aims to instruct people on how to setup R in different IDEs.

---

## Table of Contents
- [RStudio](#rstudio)
  - [Install RStudio](#install-rstudio)
  - [Setup R in Windows](#setup-r-in-windows)
- [VS Code](#vs-code)
  - [Install VS Code](#install-vs-code)
  - [Install Linux](#install-linux)
  - [Install R in Linux](#install-r-in-linux)

---

## RStudio

### Install RStudio
[Install RStudio](https://posit.co/download/rstudio-desktop/)

### Setup R in Windows
[Install R](https://cran.rstudio.com/)

---

## VS Code

### Install VS Code
[Install VS Code](https://code.visualstudio.com/)

### Install Linux

If you are using **Windows**, you can install Linux through the [Microsoft Store](https://apps.microsoft.com/) by searching for a Linux distribution such as **Ubuntu**.

**Note (MacOS users):** You don’t need to install Linux. macOS is Unix-based, so your terminal already supports installing the necessary tools. The recommended way to install R packages and dependencies on macOS is by using Homebrew or the official CRAN installer.  

### Install R in Linux

**Windows**  (via WSL linux)
1. Open the Linux terminal.  
2. Update the system packages and install R:
   ```bash
   sudo apt update && sudo apt upgrade -y  # updates package lists + upgrades existing packages
   sudo apt install -y r-base              # installs R and Rscript
   R --version                             # shows installed R version
   Rscript --version                       # shows installed Rscript version
   ```
3. In VS Code you can open the linux terminal and run the R script with the following command:   
  ```bash
  Rscript nameOfTheFile.r  #replace the name of the file with your R file name please
  ``` 
**MacOS**  
  ```bash
  /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
  brew install r
  ```


