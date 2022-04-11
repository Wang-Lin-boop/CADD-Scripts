# Schrodinger-Script
Scripts to run Schrödinger jobs.

[![DOI](https://zenodo.org/badge/365661221.svg)](https://zenodo.org/badge/latestdoi/365661221)


Scripts
----
Linux shell scripts (`Vsgo GVSrun plmd DSMDrun XDock`) to run Virual Screening, Molecular Dynamics Simulation in Schrodinger.
Using -h option to show help information for this scripts, such as `GVSrun -h`.

```
   GVSrun or Vsgo: Virual Screening;

   plmd or DSMDrun: Molecular Dynamics Simulation;

   XDock: Reverse Docking, Global Docking and Batch Grid Genenation.
```

GVSrun and plmd is higher recommoned than Vsgo and DSMDrun.

Chinese documents
----
中文文档可以访问：

[XDock](https://zhuanlan.zhihu.com/p/387371069)

[靶标垂钓](https://zhuanlan.zhihu.com/p/422890966)

[GVSrun and plmd](https://zhuanlan.zhihu.com/p/370850885)


Environment Variables
----
These environmental variables are necessary: 

1:`SCHRODINGER` (installation path of Schrodinger) is necessary for `GVSrun`, `Vsgo` and `XDock`;

2:`compound_library` (compound library for your compound databases) is necessary for `GVSrun`;

3:`Desmond` (installation path of Schrodinger or Academic Desmond) is necessary for `plmd` and `DSMDrun`;

4:`rosetta_app` or `rosetta_db` (installation path of rosetta) is optional for `XDock`;

You can add those Environment Variables to your `~/.bashrc`!

For example,  `export Desmond=/public/home/wanglin3/software/DS21`

How to cite
----
It is recommended that citing the script by a link (such as: `GVSrun(https://github.com/Wang-Lin-boop/Schrodinger-Script)`) or refer to this page [Ways to cite a GitHub Repo](https://www.wikihow.com/Cite-a-GitHub-Repository) to promote reproducibility of your work.

后排插播一条广告，欢迎加入Schrödinger中文社区，请致信wanglin3@shanghaitech.edu.cn获取加群二维码。
