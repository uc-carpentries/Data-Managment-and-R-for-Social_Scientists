---
layout: page
title: Setup
---

# Spreadsheets Setup

> ## Data
>
> You need to download some files to follow this lesson:
>
> 1. Download the following three files:
>   * [SAFI_clean.csv](https://ndownloader.figshare.com/files/11492171)
>   * [SAFI_messy.xlsx](https://ndownloader.figshare.com/files/11502824)
>   * [SAFI_dates.xlsx](https://ndownloader.figshare.com/files/11502827)
>
> 2. Place these 3 files in a folder you can easily find and access on your
> computer (or instance in a `datacarpentry-spreadsheets` folder on your
> Desktop or within your Home folder).
>
> #### About the data
>
> For more information about the dataset and to
> download it from Figshare, check out the [Social Sciences workshop data
> page](http://www.datacarpentry.org/socialsci-workshop/data).
{: .prereq}

> ## Software
>
> To interact with spreadsheets, we can use LibreOffice, Microsoft Excel,
> Gnumeric, or other programs. Commands may differ a bit between programs, but
> the general ideas for thinking about spreadsheets are the same.
>
> For this lesson, if you don't have a spreadsheet program already, you can use
> LibreOffice. It's a free, open source spreadsheet program.
>
> macOS users who use Apple's Numbers application should note that it does not
> contain some of the features (particularly data validation) that we will
> be using. Please use LibreOffice or Microsoft Excel instead.
>
> #### Windows
>
> - Download the Installer
> - Install LibreOffice by going to [the installation
>   page](https://www.libreoffice.org/download/libreoffice-fresh/). The version
>   for Windows should automatically be selected. Click Download Version X.X.X
>   (whichever is the most recent version).
> - Install LibreOffice
> - Once the installer is downloaded, double click on it and LibreOffice should
>   install.
>
> #### Mac OS X
>
> - Download the Installer
>  - Install LibreOffice by going to [the installation
>    page](https://www.libreoffice.org/download/libreoffice-fresh/). The version
>    for Mac should automatically be selected. Click Download Version X.X.X
>    (whichever is the most recent version).
> - Install LibreOffice
> - Once the installer is downloaded, double click on it and LibreOffice should
>   install.
>
> #### Linux
>
> - Download the Installer
> - Install LibreOffice by going to [the installation
>   page](https://www.libreoffice.org/download/libreoffice-fresh/). The version
>   for Linux should automatically be selected. Click Download Version X.X.X
>   (whichever is the most recent version).
> - Install LibreOffice
> - Once the installer is downloaded, double click on it and LibreOffice should
>   install.
{: .prereq}

# OpenRefine Setup

> ## Data
>
> The data for this lesson is a part of the Data Carpentry Social Sciences
> workshop. It is a teaching version of the Studying African Farmer-Led
> Irrigation (SAFI) database. The SAFI dataset represents interviews of farmers
> in two countries in eastern sub-Saharan Africa (Mozambique and Tanzania).
> These interviews were conducted between November 2016 and June 2017 and probed
> household features (e.g. construction materials used, number of household
> members), agricultural practices (e.g. water usage), and assets (e.g. number
> and types of livestock).
> 
> The data used in this lesson
> is a subset of the teaching version that has been intentionally 'messed up'
> for this lesson.
> 
> **Download** the data file to your computer by [clicking this link](https://ndownloader.figshare.com/files/11502815). (direct link: <https://ndownloader.figshare.com/files/11502815>)
{: .prereq}

> ## Software
>
> For this lesson you will need **OpenRefine** (formerly Google Refine) and a
> web browser.
>
> Note: this is a Java program that runs on your machine (not in the cloud). It runs inside your browser, but no web connection is needed.
>
>
> #### Windows
>
> - Check that you have Firefox or Chrome browsers installed and set as your 
> default browser. OpenRefine runs in your default browser. It will not run correctly in Internet Explorer.
> - Download software from [http://openrefine.org](http://openrefine.org)
> - Unzip the downloaded file into a directory by right-clicking and 
> selecting “Extract…”. Name that directory something like OpenRefine.
> - Go to your newly created OpenRefine directory.
> - Launch OpenRefine
> - Click the openrefine.exe (this will launch a command prompt window, but you can ignore that and wait for the browser to launch)
> - If you are using a different browser, or OpenRefine does not automatically open for you, point your browser at http://127.0.0.1:3333/ or http://localhost:3333 to launch the program.
> 
> #### Mac
> 
> - Check that you have Firefox or Chrome browsers installed and set as your 
> default browser. OpenRefine runs in your default browser. It will not run correctly in Internet Explorer.
> - Download software from [http://openrefine.org](http://openrefine.org)
> - Unzip the downloaded file into a directory by double-clicking it. Name 
> that directory something like OpenRefine.
> - Go to your newly created OpenRefine directory.
> - Launch OpenRefine
> - Drag icon into Applications folder, and Ctrl-click/Open… it. 
> - If you are using a different browser, or OpenRefine does not automatically open for you, point your browser at http://127.0.0.1:3333/ or http://localhost:3333 to launch the program.
> 
> #### Linux
> 
> - Check that you have Firefox or Chrome browsers installed and set as your 
> default browser. OpenRefine runs in your default browser. It will not run correctly in Internet Explorer.
> - Download software from [http://openrefine.org](http://openrefine.org)
> - Unzip the downloaded file into a directory. Name 
> that directory something like OpenRefine.
> - Go to your newly created OpenRefine directory.
> - Launch OpenRefine
> - Type ./refine into the terminal within the OpenRefine directory
> - If you are using a different browser, or OpenRefine does not automatically open for you, point your browser at http://127.0.0.1:3333/ or http://localhost:3333 to launch the program.
{: .prereq}

# R Setup

> ## Overview
>
> **R** and **RStudio** are separate downloads and installations. R is the
> underlying statistical computing environment, but using R alone is no
> fun. RStudio is a graphical integrated development environment (IDE) that makes
> using R much easier and more interactive. You need to install R before you
> install RStudio. Once installed, because RStudio is an IDE, RStudio will run R in the background.  You do not need to run it separately. After installing both programs, you will need to install the
> **`tidyverse`** package from within RStudio. Follow the instructions below for
> your operating system, and then follow the instructions to install
> **`tidyverse`**.
{: .prereq}

> ## Software
> ### Windows
> 
> #### If you already have R and RStudio installed
> 
> * Open RStudio, and click on "Help" > "Check for updates". If a new version is
> 	available, quit RStudio, and download the latest version for RStudio.
> * To check which version of R you are using, start RStudio and the first thing
>  that appears in the console indicates the version of R you are
>  running. Alternatively, you can type `sessionInfo()`, which will also display
>  which version of R you are running. Go on
>  the [CRAN website](https://cran.r-project.org/bin/windows/base/) and check
>  whether a more recent version is available. If so, please download and install
>  it. You can [check here](https://cran.r-project.org/bin/windows/base/rw-FAQ.html#How-do-I-UNinstall-R_003f) for
>  more information on how to remove old versions from your system if you wish to do so.
>
> #### If you don't have R and RStudio installed
>
> * Download R from
>  the [CRAN website](http://cran.r-project.org/bin/windows/base/release.htm).
> * Run the `.exe` file that was just downloaded
> * Go to the [RStudio download page](https://www.rstudio.com/products/rstudio/download/#download)
> * Under *Installers* select **RStudio x.yy.zzz - Windows
>   Vista/7/8/10** (where x, y, and z represent version numbers)
> * Double click the file to install it
> * Once it's installed, open RStudio to make sure it works and you don't get any
>   error messages.
> 
> 
> ### macOS
> 
> #### If you already have R and RStudio installed
> 
> * Open RStudio, and click on "Help" > "Check for updates". If a new version is
> 	available, quit RStudio, and download the latest version for RStudio.
> * To check the version of R you are using, start RStudio and the first thing
>   that appears on the terminal indicates the version of R you are running. Alternatively, you can type `sessionInfo()`, which will also display which version of R you are running. Go on
>   the [CRAN website](https://cran.r-project.org/bin/macosx/) and check
>   whether a more recent version is available. If so, please download and install
>   it.
> 
> #### If you don't have R and RStudio installed
> 
> * Download R from
>   the [CRAN website](http://cran.r-project.org/bin/macosx/).
> * Select the `.pkg` file for the latest R version
> * Double click on the downloaded file to install R
> * It is also a good idea to install [XQuartz](https://www.xquartz.org/) (needed
>   by some packages)
> * Go to the [RStudio download page](https://www.rstudio.com/products/rstudio/download/#download)
> * Under *Installers* select **RStudio x.yy.zzz - Mac OS X 10.6+ (64-bit)**
>   (where x, y, and z represent version numbers)
> * Double click the file to install RStudio
> * Once it's installed, open RStudio to make sure it works and you don't get any
>   error messages.
> 
> 
> ### Linux
> 
> * Follow the instructions for your distribution
>   from [CRAN](https://cloud.r-project.org/bin/linux), they provide information
>   to get the most recent version of R for common distributions. For most
>   distributions, you could use your package manager (e.g., for Debian/Ubuntu run
>   `sudo apt-get install r-base`, and for Fedora `sudo yum install R`), but we
>   don't recommend this approach as the versions provided by this approach are
>   usually out of date. In any case, make sure you have at least R 3.3.1.
> * Go to the
> [RStudio download page](https://www.rstudio.com/products/rstudio/download/#download)
> * Under *Installers* select the version that matches your distribution, and
>   install it with your preferred method (e.g., with Debian/Ubuntu `sudo dpkg -i
>   rstudio-x.yy.zzz-amd64.deb` at the terminal).
> * Once it's installed, open RStudio to make sure it works and you don't get any
> error messages.
> 
> 
> ### For everyone
> 
> **After installing R and RStudio, you need to install the `tidyverse` package.**
> 
> * After starting RStudio, at the console type:
>  `install.packages(c("tidyverse"))`
{: .prereq}
