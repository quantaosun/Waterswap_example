# An update 
https://github.com/michellab/Sire/issues/397 

One more line has been added to the ipynb file, to keep the whole procedure working

```
! grep -v %COMMENT /content/SYS_gaff2.prmtop > SYS.prmtop
```

# waterswap
Utilize the Make it rain/protein_ligand  to generate SYS_gaff2.crd and SYS_gaff2.prctop file, then use as input for the water swap notebook to do a 100 iteration for an estimated binding free energy.

# You need to run the first several blocks of https://github.com/pablo-arantes/making-it-rain/blob/main/Protein_ligand.ipynb to get two starting files before you could use this notebook.

<img width="1186" alt="image" src="https://user-images.githubusercontent.com/75652473/155684830-f53f212b-b295-4d49-86a0-d3a3e8bf9785.png">

