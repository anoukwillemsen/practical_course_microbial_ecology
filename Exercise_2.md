# Exercise_2: Analyse digital PCR data

In this exercise, you will analyse the experimental data you obtained from the digital PCR machine. There are many ways to analyse the data. In this exercise, you will be provided with a very simple script to analyse your data in R. Feel free to improve this script or even write your own in your preferred language (R, Python, ...)

### Implement the project structure

In our course directory (`/lisc/data/scratch/course/2026s301485/`), you have created the folder `<USER>` for Exercise 1. Go into your <USER> folder and implement a directory structure for the dPCR data analysis.

<details>  
<summary>See commands</summary>

```bash
cd /lisc/data/scratch/course/2026s301485/
```
```bash
cd  <USER>
```
```bash
# Make <USER>/dPCR_analysis directory and change to it
mkdir dPCR_analysis
cd dPCR_analysis
```
```bash
# Make directories inside of ~/2026s301485/dPCR_analysis*
mkdir data
mkdir scripts
mkdir tmp
mkdir plots
```
</details>

Copy the digital PCR data (output.csv) file to your ~/2026s301485/dPCR_analysis/data folder on LiSC.
<details>  
<summary>See commands</summary>
  
```bash
scp output.csv <USER>@login01.lisc.univie.ac.at:/lisc/data/scratch/course/2026s301485/<USER>/dPCR_analysis/data
```

</details>


### Log in to the RStudio server and have fun
We will be using the RStudio Server hosted by LiSC at [https://rstudio.lisc.univie.ac.at](https://rstudio.lisc.univie.ac.at).
The login credentials for the RStudio Server are the same as those for logging in to the LiSC login nodes. Make sure your network address has LiSC access.
If you have R or RStudio installed locally, you can, of course, also use them. 

<details>

<summary>After logging in, you should see this </summary>

![](./figures/RstudioServer_LiSC.png)

</details>
</br>
