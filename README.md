# recipe
Use any >10_4_X release
cd CMSSW_10_4_X/src/
cmsenv

git cms-addpkg RecoMET/METFilters

git clone git@github.com:amkalsi/miniAOD_IIHE_2018.git    -b CMSSW_10_2_5_patch1 UserCode/IIHETree

scramv1 b -j 16

