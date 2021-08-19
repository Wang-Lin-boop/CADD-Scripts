# Schrodinger-Script
Scripts to run Schrödinger jobs.

Vsgo GVSrun plmd DSMDrun XDock
----
Linux shell scripts to run Virual Screening, Molecular Dynamics Simulation in Schrodinger.
Using -h option to show help information for this scripts, such as `GVSrun -h`.

```
   Vsgo or GVSrun: Virual Screening;

   plmd or DSMDrun: Molecular Dynamics Simulation;

   XDock: Reverse Docking, Global Docking and Batch Grid Genenation.
```

GVSrun and plmd is higher recommoned than Vsgo and DSMDrun.

Environment variables
----
These environmental variables are necessary: 
1:`SCHRODINGER` (installation path of Schrodinger) is necessary for `GVSrun`, `Vsgo` and `XDock`;
2:`compound_library` (compound library for your compound databases) is necessary for `GVSrun`;
3:`Desmond` (installation path of Schrodinger or Academic Desmond) is necessary for `plmd` and `DSMDrun`;
4:`rosetta_app` or `rosetta_db` (installation path of rosetta) is optional for `XDock`;

How to cite
----
Citing is not required, but it is recommended that citing the script by link (such as: `GVSrun(https://github.com/Wang-Lin-boop/Schrodinger-Script)`) to promote reproducibility of your work.

后排插播一条广告，欢迎加入Schrödinger中文社区，请致信wanglin3@shanghaitech.edu.cn获取加群二维码。
