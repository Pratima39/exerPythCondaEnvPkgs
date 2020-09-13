# Setting up Environments and Installing Packages Using Conda

## Summary of steps to complete

- [ ] Fork this repository so you have your own copy to work on.
- [ ] Clone the repository on your local machine. 
- [ ] Edit this README.md file on your machine.
- [ ] Run the Conda commands shown in the video and describe them in the table below.
- [ ] Push your changes to your GitHub repository.
- [ ] Submit a link to this GitHub repository in Canvas.

## 1. Fork & Clone this repository

* We did this in a previous assignment. Instructions are here: https://github.com/cmcntsh/exerGitPractice
* This can also be done directly in VSCode
  * Create a new folder on your machine where you want to put this repository if you don't already have one you want to use.
  * Copy the Clone or Download path for this repository from GitHub.
  * In VSCode from the command pallette (Ctrl-Shift-P) run Git: Clone
  * Paste the path into the path field which pops up
  * Select your new folder you created on your machine
  * A new folder for the repository with the repository files should be in the folder you selected showing in the Explorer window in VSCode on the left side.
  
## Edit your README.md file

* [ ] In an editor of your choice (i.e. VSCode) edit this README.md file to add the answers requested in the tables.

## Follow along with this tutorial

* Conda What and Why? (27 min): https://www.youtube.com/watch?v=23aQdrS58e0&list=PLG9A6ovzPqX6d9uWzx0UYN9pm0zzl5ofA&index=13&t=0s
  * He installs Miniconda. We will be using Anaconda. Don't install Miniconda.
  * Follow along with the rest of the tutorial.
  * Go ahead and create the environments as he creates them in the tutorial.

## Conda Concepts

* [ ] Describe the Conda concepts used in the video and listed in the table below.

|   Concept   |         Description or short answer         |
|     ---     |                     ---                     |
|What is the purpose of having different environments?     |(Purpose-Simplifies and easy managing dependencies between multiple jobs with with different isolated workstream/Projects)|
|What is the default package manager in Python?            |(pip)|
|How do you manage environments and packages in Anaconda?  |(we can manage environments and packages in                                                               Anaconda using windows ternimal or using                                                                 Anaconda prompt terminal
                                                            *conda env create -f environment. yml
															                                             *conda activate myenv
															                                             *conda env list)|
|`conda list`       |(List all the packages in environment at C:\Users\binod\Anaconda3)|
|`conda env list`   |(List all the environments
                         # conda environments:
                         #
				                     base *  C:\Users\binod\Anaconda3
                         Test    C:\Users\binod\Anaconda3\envs\Test)|
|How do you keep your base environment unchanged?       |(Run deactive conda command from base                                                                    environment)|
|What is the link to the Conda cheat sheet? (link in video notes is broken)      |(https://docs.conda.io/projects/conda/en/4.6.0/_downloads/52a95608c49671267e40c689e0bc00ca/conda-cheatsheet.pdf)|
|`conda create --name XXXX`       |(Command to create the XXXX Environment)|
|`source activate XXXX`       |(Command to activate the XXXX Environment)|
|`conda install YYYY`       |(Command to install YYYY named package in XXXX Environment in Conda)|
|channels in Conda       |(Channels holds the packages in conda which are not default channels)|
|`conda install -c ZZZZ YYYY`       |(Command to install YYYY package in ZZZZ channel in Conda)|
|`conda config --show channels`       |(Show all the channels available in Environment)|
|`conda config --add channels ZZZZ`       |(Adds channel named ZZZZ in Environment in Conda)|
|conda-forge.org       |(It's web appllication led by community with collection of recipes and build                             infracture and distributions for the conda package manager)|
|`source deactivate`       |(This command will take us to default/base channel)|
|`conda config --get channels`       |(This command in Conda will let us know the piority of packages avilable in channels,i.e higher piority channels gets more piority during installation of same version of packages and vice-versa)|

* After creating the environments he created in the video on your computer, what would the results of running the command `conda env list` look like with the da35 environment activated. Paste the output from your command prompt in the code block below.

```
#Paste your results here.


```
* What command would you use to remove the environments you created for this exercise from your computer?

```
#Type the command here.

```
