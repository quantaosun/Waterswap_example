
# waterswap

It has been noticed for the moment we have to remove some keywords inside top file before using waterswap.
################################ Updated about an error ###########################
```
!grep -v %COMMENT SYS_gaff2_temp.prmtop > SYS_gaff2.prmtop

OR

Use sire 2023 version from https://sire.openbiosim.org/install.html
```
####################################################################################
## You need to run the first several blocks of 

https://github.com/pablo-arantes/making-it-rain/blob/main/Protein_ligand.ipynb to get two starting files before you could use this notebook.

These two files neede are

1. SYS_gaff2.prmtop
2. SYS_gaff2.crd

After having these two files ready, please open this link then click Oopen in colab button. 

https://github.com/quantaosun/Waterswap_example/blob/main/waterswap_example.ipynb 

<img width="1250" alt="image" src="https://user-images.githubusercontent.com/75652473/202317820-7b083a8a-52d8-4356-9f21-2a67809a707a.png">


Then you can upload the two files to run this notebook to get a ligand protein binding energy.
