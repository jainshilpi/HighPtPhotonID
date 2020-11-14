# HighPtPhotonID

Input files are provided in files.list

root -l -b -q runAll.C+

hadd minitree_dy.root minitree_dy*

mkdir plots

root -l -b -q plot.C
