# PNetCalibration
cmsrel CMSSW_14_2_1 
cd CMSSW_14_2_1/src/
cmsenv
git clone https://github.com/cms-analysis/HiggsAnalysis-CombinedLimit.git HiggsAnalysis/CombinedLimit
cd HiggsAnalysis/CombinedLimit
git fetch origin
git checkout v10.0.0
cd ../..
git clone https://github.com/Moanwar/PNetCalibration.git
scramv1 b clean
scramv1 b -j 8

