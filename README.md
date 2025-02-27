# CADD-Scripts (using Schrödinger and Rosetta)
Scripts to run Schrödinger and Rosetta jobs.

[![DOI](https://zenodo.org/badge/365661221.svg)](https://zenodo.org/badge/latestdoi/365661221)

Installation
----

Download CADD-Scripts and set the environment variable.

```
git clone https://github.com/Wang-Lin-boop/CADD-Scripts
cd CADD-Scripts
echo "export PATH=${PWD}:\${PATH}" >> ~/.bashrc
chmod +x XDock
chmod +x GVSrun
chmod +x ProteinMC
source ~/.bashrc
```


Scripts
----
Linux shell scripts (`XDock, GVSrun, ProteinMC`) to run Virual Screening, Cross-Docking and MC Simulations.
Using -h option to show help information for this scripts, such as `GVSrun -h`.

```
   GVSrun: Virual Screening;

   XDock: Reverse Docking, Global Docking and Batch Grid Genenation.

   ProteinMC: Protein Relax, Protein-Protein Docking, MM-GBSA Calculation. 
```

Related-Script
----

Refer to [AutoMD](https://github.com/Wang-Lin-boop/AutoMD) for automated execution of molecular dynamics simulations and trajectory analysis.

Chinese documents
----
中文文档可以访问：

[XDock](https://zhuanlan.zhihu.com/p/387371069)

[靶标垂钓](https://zhuanlan.zhihu.com/p/422890966)

[GVSrun and plmd](https://zhuanlan.zhihu.com/p/370850885)


Environment Variables
----
These environmental variables are necessary: 

1:`SCHRODINGER` (installation path of Schrodinger) is required for `GVSrun`, and `XDock`;

2:`compound_library` (compound library for your compound databases) is required for `GVSrun`;

3:`rosetta_app` or `rosetta_db` (installation path of rosetta) is optional for `XDock`;

You can add those Environment Variables to your `~/.bashrc`!

For example,  `export SCHRODINGER=/public/home/wanglin3/software/SCHRODINGER`

How to cite
----
It is recommended that citing the script by a link (such as: `GVSrun(https://github.com/Wang-Lin-boop/CADD-Scripts)`) or refer to this page [Ways to cite a GitHub Repo](https://www.wikihow.com/Cite-a-GitHub-Repository) to promote reproducibility of your work.
