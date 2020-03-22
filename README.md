# Gate_ICRP110_dosi

```
GATE macro for nuclear medicine dosimetry with the ICRP 110 voxel models  

Author: Maxime Chauvin, maxime.chauvin@inserm.fr
Last revision: 22-03-2020

  Usage example, for mono energetic source:
    Gate -a [Source_ID,95][particle,gamma][energy,1][nb,1e5][job,1] mac/main_A$.mac
  Usage example, for 177 Lu source (uncomment in section SOURCE):
    Gate -a [Source_ID,95][nb,1e5][job,1] mac/main_A$.mac

  Inputs:
    - data/activity_ranges/ActivityRange*.dat
    - data/A$_GateMaterials.db
    - data/A$_LabelsToMaterials.txt
    - data/A$_UINT16_299_137_348.mhd
    - data/A$_UINT16_299_137_348.raw

  Outputs:
    - {job}_A$-DoseByRegions.txt
    - {job}_A$-model-Dose.mhd
    - {job}_A$-model-Dose.raw
    - {job}_A$-model-Dose-Squared.mhd
    - {job}_A$-model-Dose-Squared.raw
    - {job}_A$-model-Dose-Uncertainty.mhd
    - {job}_A$-model-Dose-Uncertainty.raw
    - {job}_A$-stats.txt
```
