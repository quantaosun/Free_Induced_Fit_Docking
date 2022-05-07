# Free_Cloud_Docking

# I will be sad if you ever decide to use this on a local computer, the whole point here is to use docking on the cloud. But it is definitely possible if you insist on using it locally.

Molecular docking is the simplest yet one of the most powerful methods of modelling in the medicinal chemistry field. There are many licensed and free academic options there, but most still need a local installation. This is a cloud pipeline based on Autodock Vina (Smina), aiming to provide a totally free tool to those who want to use molecular docking in their projects. You don't have to install anything but provide an SDF file that could be from Chemdraw and a protein RCSB four-letter code.

# References and contribution eleboration
# This code was first inspired by [https://www.macinchem.org/reviews/JupyterDocking/jupyterdocking.php](http://) and [https://www.cheminformania.com/ligand-docking-with-smina/](http://)


1. The following was changed in this notebook compared to the above two:
1. This notebook provides docking with a pocket water option compared to the original one, what I have done is use Pymol to keep 5 of the ligand then use the water-contained receptor in docking. There are two cells,and you should only run one of them, be careful!

1. The docking validation and docking separately existed in two non-related notebooks, but this one integrated them in a single notebook, which will save time and be more convenient.
1. If you use this notebook on AI Studio(https://aistudio.baidu.com/aistudio/index), it realized the "permanent" installation, unlike the google collab in which you have to install each time before you could do anything. 

1. Conda, Pymol and three to four paths have been modified to maintain the compatibility on Colab, but with extra AI studio compatibility, you may find the path a bit weird on Colab, that is to get rid of some user restrictions from AI studio, but it still works on Colab. 
