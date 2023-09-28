## Linkage Synthesis Challenge Problem

This challenge problem is focused on synthesizing planar linkage mechanisms such that a specific output curve is traced using the mechanism. For this project you are tasked with synthesizing linkage mechanisms to trace 6 different output shapes. Further you are tasked with synthesizing mechanisms such that the total material used for the mechanisms in minimized. 

<img src="https://i.ibb.co/qsPC0gC/2021-09-13-0hl-Kleki.png" alt="Numbered Mechanism" border="0">


## Requirements For Python
<ul>
<li>Python >= 3.8</li>
<li>numpy<1.24</li>
<li>pymoo >= 0.6</li>
<li>matplotlib</li>
<li>scipy</li>
<li>pytorch</li>
<li>svgpath2mpl</li>
<li>tqdm</li>
</ul>

IMPORTANT: As of 9/2023, there is a package conflict between pymoo and numpy versions 1.24 or higher. You will need to install an older version of numpy to run this code. (Tested on 1.23.5)
Run:
```
conda create -n <environment-name> 
conda env update -n <environment-name> --file environment.yml
```

to make the correct enivronment in conda



