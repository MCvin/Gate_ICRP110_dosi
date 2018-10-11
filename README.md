# Gate_voxPhantomDosi

```
GATE macro for nuclear medicine dosimetry with voxel phantoms

Author: Maxime Chauvin, maxime.chauvin@inserm.fr
 Last revision: 10-10-2018

 Usage example:
   Gate -a [Source_ID,95][particle,gamma][energy,1][nb,1e5] mac/main.mac

 Inputs:
   - data/ActivityRange*.dat
   - data/phantom_GateMaterials.db
   - data/phantom_LabelsToMaterials.txt
   - data/phantom.mhd
   - data/phantom.raw

 Outputs:
   - DoseByRegions.txt
   - output-Dose.mhd
   - output-Dose.raw
   - output-Dose-Squared.mhd
   - output-Dose-Squared.raw
   - output-Dose-Uncertainty.mhd
   - output-Dose-Uncertainty.raw
   - stat.log
```

