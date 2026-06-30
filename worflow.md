# workflow notes
## ctchest smaple dataset provided through 3d slicer
threshold segmentation isolate high0density bone structures structures
- bone set around 150 - 300 HU, calibrated to discretion at 100 - 400 HU
- ribs highlighted, vertebrae highlighted, soft tissue excluded
- keep large islands
- erased scapula and connected islands to leave ribcage, sternum, spine
- median smoothing applied at 2-3 mm. 3.00 took off too much volume
- set at 2.00 mm
minor artifacts removed and smoothed

## expoert
stl mesh
