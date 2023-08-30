## Case 9 

* TSC = belowSpeedLimit 
* T = {noStopping} 
* CheckSatN(BC_1): case009_premise.smt2, expect sat 
* CheckSatN(BC_2): case009_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 10 

* TSC = noStopping 
* T = {belowSpeedLimit} 
* CheckSatN(BC_1): case010_premise.smt2, expect sat 
* CheckSatN(BC_2): case010_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 11 

* TSC = belowSpeedLimit 
* T = {keepInRightmostLane} 
* CheckSatN(BC_1): case011_premise.smt2, expect sat 
* CheckSatN(BC_2): case011_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 12 

* TSC = keepInRightmostLane 
* T = {belowSpeedLimit} 
* CheckSatN(BC_1): case012_premise.smt2, expect sat 
* CheckSatN(BC_2): case012_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 13 

* TSC = noStopping 
* T = {keepInRightmostLane} 
* CheckSatN(BC_1): case013_premise.smt2, expect sat 
* CheckSatN(BC_2): case013_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 14 

* TSC = keepInRightmostLane 
* T = {noStopping} 
* CheckSatN(BC_1): case014_premise.smt2, expect sat 
* CheckSatN(BC_2): case014_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 15 

* TSC = belowSpeedLimit 
* T = {noPassingOnTheRightSide} 
* CheckSatN(BC_1): case015_premise.smt2, expect sat 
* CheckSatN(BC_2): case015_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 16 

* TSC = noPassingOnTheRightSide 
* T = {belowSpeedLimit} 
* CheckSatN(BC_1): case016_premise.smt2, expect sat 
* CheckSatN(BC_2): case016_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 17 

* TSC = noStopping 
* T = {noPassingOnTheRightSide} 
* CheckSatN(BC_1): case017_premise.smt2, expect sat 
* CheckSatN(BC_2): case017_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 18 

* TSC = noPassingOnTheRightSide 
* T = {noStopping} 
* CheckSatN(BC_1): case018_premise.smt2, expect sat 
* CheckSatN(BC_2): case018_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 19 

* TSC = keepInRightmostLane 
* T = {noPassingOnTheRightSide} 
* CheckSatN(BC_1): case019_premise.smt2, expect sat 
* CheckSatN(BC_2): case019_consequence.smt2, expect unsat 
* CheckSatS(BC_1): case019_premiseCheck.smt2, expect sat 

## Case 20 

* TSC = noPassingOnTheRightSide 
* T = {keepInRightmostLane} 
* CheckSatN(BC_1): case020_premise.smt2, expect sat 
* CheckSatN(BC_2): case020_consequence.smt2, expect unsat 
* CheckSatS(BC_1): case020_premiseCheck.smt2, expect sat 

## Case 21 

* TSC = belowSpeedLimit 
* T = {safeLaneChange} 
* CheckSatN(BC_1): case021_premise.smt2, expect sat 
* CheckSatN(BC_2): case021_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 22 

* TSC = safeLaneChange 
* T = {belowSpeedLimit} 
* CheckSatN(BC_1): case022_premise.smt2, expect sat 
* CheckSatN(BC_2): case022_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 23 

* TSC = noStopping 
* T = {safeLaneChange} 
* CheckSatN(BC_1): case023_premise.smt2, expect sat 
* CheckSatN(BC_2): case023_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 24 

* TSC = safeLaneChange 
* T = {noStopping} 
* CheckSatN(BC_1): case024_premise.smt2, expect sat 
* CheckSatN(BC_2): case024_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 25 

* TSC = keepInRightmostLane 
* T = {safeLaneChange} 
* CheckSatN(BC_1): case025_premise.smt2, expect sat 
* CheckSatN(BC_2): case025_consequence.smt2, expect unsat 
* CheckSatS(BC_1): case025_premiseCheck.smt2, expect sat 

## Case 26 

* TSC = safeLaneChange 
* T = {keepInRightmostLane} 
* CheckSatN(BC_1): case026_premise.smt2, expect sat 
* CheckSatN(BC_2): case026_consequence.smt2, expect unsat 
* CheckSatS(BC_1): case026_premiseCheck.smt2, expect sat 

## Case 27 

* TSC = noPassingOnTheRightSide 
* T = {safeLaneChange} 
* CheckSatN(BC_1): case027_premise.smt2, expect sat 
* CheckSatN(BC_2): case027_consequence.smt2, expect unsat 
* CheckSatS(BC_1): case027_premiseCheck.smt2, expect sat 

## Case 28 

* TSC = safeLaneChange 
* T = {noPassingOnTheRightSide} 
* CheckSatN(BC_1): case028_premise.smt2, expect sat 
* CheckSatN(BC_2): case028_consequence.smt2, expect unsat 
* CheckSatS(BC_1): case028_premiseCheck.smt2, expect sat 

## Case 29 

* TSC = belowSpeedLimit 
* T = {speedAdvantageForOvertaking} 
* CheckSatN(BC_1): case029_premise.smt2, expect sat 
* CheckSatN(BC_2): case029_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 30 

* TSC = speedAdvantageForOvertaking 
* T = {belowSpeedLimit} 
* CheckSatN(BC_1): case030_premise.smt2, expect sat 
* CheckSatN(BC_2): case030_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 31 

* TSC = noStopping 
* T = {speedAdvantageForOvertaking} 
* CheckSatN(BC_1): case031_premise.smt2, expect sat 
* CheckSatN(BC_2): case031_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 32 

* TSC = speedAdvantageForOvertaking 
* T = {noStopping} 
* CheckSatN(BC_1): case032_premise.smt2, expect sat 
* CheckSatN(BC_2): case032_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 33 

* TSC = keepInRightmostLane 
* T = {speedAdvantageForOvertaking} 
* CheckSatN(BC_1): case033_premise.smt2, expect sat 
* CheckSatN(BC_2): case033_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 34 

* TSC = speedAdvantageForOvertaking 
* T = {keepInRightmostLane} 
* CheckSatN(BC_1): case034_premise.smt2, expect sat 
* CheckSatN(BC_2): case034_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 35 

* TSC = noPassingOnTheRightSide 
* T = {speedAdvantageForOvertaking} 
* CheckSatN(BC_1): case035_premise.smt2, expect unsat 
* CheckSatN(BC_2): skipped 
* CheckSatS(BC_1): skipped 

## Case 36 

* TSC = speedAdvantageForOvertaking 
* T = {noPassingOnTheRightSide} 
* CheckSatN(BC_1): case036_premise.smt2, expect unsat 
* CheckSatN(BC_2): skipped 
* CheckSatS(BC_1): skipped 

## Case 37 

* TSC = safeLaneChange 
* T = {speedAdvantageForOvertaking} 
* CheckSatN(BC_1): case037_premise.smt2, expect sat 
* CheckSatN(BC_2): case037_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 38 

* TSC = speedAdvantageForOvertaking 
* T = {safeLaneChange} 
* CheckSatN(BC_1): case038_premise.smt2, expect sat 
* CheckSatN(BC_2): case038_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 39 

* TSC = belowSpeedLimit 
* T = {safeDistance} 
* CheckSatN(BC_1): case039_premise.smt2, expect sat 
* CheckSatN(BC_2): case039_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 40 

* TSC = safeDistance 
* T = {belowSpeedLimit} 
* CheckSatN(BC_1): case040_premise.smt2, expect sat 
* CheckSatN(BC_2): case040_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 41 

* TSC = noStopping 
* T = {safeDistance} 
* CheckSatN(BC_1): case041_premise.smt2, expect sat 
* CheckSatN(BC_2): case041_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 42 

* TSC = safeDistance 
* T = {noStopping} 
* CheckSatN(BC_1): case042_premise.smt2, expect sat 
* CheckSatN(BC_2): case042_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 43 

* TSC = keepInRightmostLane 
* T = {safeDistance} 
* CheckSatN(BC_1): case043_premise.smt2, expect sat 
* CheckSatN(BC_2): case043_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 44 

* TSC = safeDistance 
* T = {keepInRightmostLane} 
* CheckSatN(BC_1): case044_premise.smt2, expect sat 
* CheckSatN(BC_2): case044_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 45 

* TSC = noPassingOnTheRightSide 
* T = {safeDistance} 
* CheckSatN(BC_1): case045_premise.smt2, expect sat 
* CheckSatN(BC_2): case045_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 46 

* TSC = safeDistance 
* T = {noPassingOnTheRightSide} 
* CheckSatN(BC_1): case046_premise.smt2, expect sat 
* CheckSatN(BC_2): case046_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 47 

* TSC = safeLaneChange 
* T = {safeDistance} 
* CheckSatN(BC_1): case047_premise.smt2, expect sat 
* CheckSatN(BC_2): case047_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 48 

* TSC = safeDistance 
* T = {safeLaneChange} 
* CheckSatN(BC_1): case048_premise.smt2, expect sat 
* CheckSatN(BC_2): case048_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 49 

* TSC = speedAdvantageForOvertaking 
* T = {safeDistance} 
* CheckSatN(BC_1): case049_premise.smt2, expect sat 
* CheckSatN(BC_2): case049_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 50 

* TSC = safeDistance 
* T = {speedAdvantageForOvertaking} 
* CheckSatN(BC_1): case050_premise.smt2, expect sat 
* CheckSatN(BC_2): case050_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 51 

* TSC = belowSpeedLimit 
* T = {beingOvertaken} 
* CheckSatN(BC_1): case051_premise.smt2, expect sat 
* CheckSatN(BC_2): case051_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 52 

* TSC = beingOvertaken 
* T = {belowSpeedLimit} 
* CheckSatN(BC_1): case052_premise.smt2, expect sat 
* CheckSatN(BC_2): case052_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 53 

* TSC = noStopping 
* T = {beingOvertaken} 
* CheckSatN(BC_1): case053_premise.smt2, expect sat 
* CheckSatN(BC_2): case053_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 54 

* TSC = beingOvertaken 
* T = {noStopping} 
* CheckSatN(BC_1): case054_premise.smt2, expect sat 
* CheckSatN(BC_2): case054_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 55 

* TSC = keepInRightmostLane 
* T = {beingOvertaken} 
* CheckSatN(BC_1): case055_premise.smt2, expect sat 
* CheckSatN(BC_2): case055_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 56 

* TSC = beingOvertaken 
* T = {keepInRightmostLane} 
* CheckSatN(BC_1): case056_premise.smt2, expect sat 
* CheckSatN(BC_2): case056_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 57 

* TSC = noPassingOnTheRightSide 
* T = {beingOvertaken} 
* CheckSatN(BC_1): case057_premise.smt2, expect sat 
* CheckSatN(BC_2): case057_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 58 

* TSC = beingOvertaken 
* T = {noPassingOnTheRightSide} 
* CheckSatN(BC_1): case058_premise.smt2, expect sat 
* CheckSatN(BC_2): case058_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 59 

* TSC = safeLaneChange 
* T = {beingOvertaken} 
* CheckSatN(BC_1): case059_premise.smt2, expect sat 
* CheckSatN(BC_2): case059_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 60 

* TSC = beingOvertaken 
* T = {safeLaneChange} 
* CheckSatN(BC_1): case060_premise.smt2, expect sat 
* CheckSatN(BC_2): case060_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 61 

* TSC = speedAdvantageForOvertaking 
* T = {beingOvertaken} 
* CheckSatN(BC_1): case061_premise.smt2, expect unsat 
* CheckSatN(BC_2): skipped 
* CheckSatS(BC_1): skipped 

## Case 62 

* TSC = beingOvertaken 
* T = {speedAdvantageForOvertaking} 
* CheckSatN(BC_1): case062_premise.smt2, expect sat 
* CheckSatN(BC_2): case062_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 63 

* TSC = safeDistance 
* T = {beingOvertaken} 
* CheckSatN(BC_1): case063_premise.smt2, expect sat 
* CheckSatN(BC_2): case063_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 64 

* TSC = beingOvertaken 
* T = {safeDistance} 
* CheckSatN(BC_1): case064_premise.smt2, expect sat 
* CheckSatN(BC_2): case064_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 65 

* TSC = belowSpeedLimit 
* T = {zipperMerge} 
* CheckSatN(BC_1): case065_premise.smt2, expect sat 
* CheckSatN(BC_2): case065_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 66 

* TSC = zipperMerge 
* T = {belowSpeedLimit} 
* CheckSatN(BC_1): case066_premise.smt2, expect sat 
* CheckSatN(BC_2): case066_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 67 

* TSC = noStopping 
* T = {zipperMerge} 
* CheckSatN(BC_1): case067_premise.smt2, expect sat 
* CheckSatN(BC_2): case067_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 68 

* TSC = zipperMerge 
* T = {noStopping} 
* CheckSatN(BC_1): case068_premise.smt2, expect sat 
* CheckSatN(BC_2): case068_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 69 

* TSC = keepInRightmostLane 
* T = {zipperMerge} 
* CheckSatN(BC_1): case069_premise.smt2, expect sat 
* CheckSatN(BC_2): case069_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 70 

* TSC = zipperMerge 
* T = {keepInRightmostLane} 
* CheckSatN(BC_1): case070_premise.smt2, expect sat 
* CheckSatN(BC_2): case070_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 71 

* TSC = noPassingOnTheRightSide 
* T = {zipperMerge} 
* CheckSatN(BC_1): case071_premise.smt2, expect sat 
* CheckSatN(BC_2): case071_consequence.smt2, expect unsat 
* CheckSatS(BC_1): case071_premiseCheck.smt2, expect unsat 

## Case 72 

* TSC = zipperMerge 
* T = {noPassingOnTheRightSide} 
* CheckSatN(BC_1): case072_premise.smt2, expect sat 
* CheckSatN(BC_2): case072_consequence.smt2, expect unsat 
* CheckSatS(BC_1): case072_premiseCheck.smt2, expect unsat 

## Case 73 

* TSC = safeLaneChange 
* T = {zipperMerge} 
* CheckSatN(BC_1): case073_premise.smt2, expect unsat 
* CheckSatN(BC_2): skipped 
* CheckSatS(BC_1): skipped 

## Case 74 

* TSC = zipperMerge 
* T = {safeLaneChange} 
* CheckSatN(BC_1): case074_premise.smt2, expect unsat 
* CheckSatN(BC_2): skipped 
* CheckSatS(BC_1): skipped 

## Case 75 

* TSC = speedAdvantageForOvertaking 
* T = {zipperMerge} 
* CheckSatN(BC_1): case075_premise.smt2, expect sat 
* CheckSatN(BC_2): case075_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 76 

* TSC = zipperMerge 
* T = {speedAdvantageForOvertaking} 
* CheckSatN(BC_1): case076_premise.smt2, expect sat 
* CheckSatN(BC_2): case076_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 77 

* TSC = safeDistance 
* T = {zipperMerge} 
* CheckSatN(BC_1): case077_premise.smt2, expect sat 
* CheckSatN(BC_2): case077_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 78 

* TSC = zipperMerge 
* T = {safeDistance} 
* CheckSatN(BC_1): case078_premise.smt2, expect sat 
* CheckSatN(BC_2): case078_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 79 

* TSC = beingOvertaken 
* T = {zipperMerge} 
* CheckSatN(BC_1): case079_premise.smt2, expect sat 
* CheckSatN(BC_2): case079_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 80 

* TSC = zipperMerge 
* T = {beingOvertaken} 
* CheckSatN(BC_1): case080_premise.smt2, expect sat 
* CheckSatN(BC_2): case080_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 81 

* TSC = belowSpeedLimit 
* T = {keepInRightmostLane, noStopping} 
* CheckSatN(BC_1): case081_premise.smt2, expect sat 
* CheckSatN(BC_2): case081_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 82 

* TSC = noStopping 
* T = {belowSpeedLimit, keepInRightmostLane} 
* CheckSatN(BC_1): case082_premise.smt2, expect sat 
* CheckSatN(BC_2): case082_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 83 

* TSC = keepInRightmostLane 
* T = {belowSpeedLimit, noStopping} 
* CheckSatN(BC_1): case083_premise.smt2, expect sat 
* CheckSatN(BC_2): case083_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 84 

* TSC = belowSpeedLimit 
* T = {noPassingOnTheRightSide, noStopping} 
* CheckSatN(BC_1): case084_premise.smt2, expect sat 
* CheckSatN(BC_2): case084_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 85 

* TSC = noStopping 
* T = {belowSpeedLimit, noPassingOnTheRightSide} 
* CheckSatN(BC_1): case085_premise.smt2, expect sat 
* CheckSatN(BC_2): case085_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 86 

* TSC = noPassingOnTheRightSide 
* T = {belowSpeedLimit, noStopping} 
* CheckSatN(BC_1): case086_premise.smt2, expect sat 
* CheckSatN(BC_2): case086_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 87 

* TSC = belowSpeedLimit 
* T = {noStopping, safeLaneChange} 
* CheckSatN(BC_1): case087_premise.smt2, expect sat 
* CheckSatN(BC_2): case087_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 88 

* TSC = noStopping 
* T = {belowSpeedLimit, safeLaneChange} 
* CheckSatN(BC_1): case088_premise.smt2, expect sat 
* CheckSatN(BC_2): case088_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 89 

* TSC = safeLaneChange 
* T = {belowSpeedLimit, noStopping} 
* CheckSatN(BC_1): case089_premise.smt2, expect sat 
* CheckSatN(BC_2): case089_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 90 

* TSC = belowSpeedLimit 
* T = {noStopping, speedAdvantageForOvertaking} 
* CheckSatN(BC_1): case090_premise.smt2, expect sat 
* CheckSatN(BC_2): case090_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 91 

* TSC = noStopping 
* T = {belowSpeedLimit, speedAdvantageForOvertaking} 
* CheckSatN(BC_1): case091_premise.smt2, expect sat 
* CheckSatN(BC_2): case091_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 92 

* TSC = speedAdvantageForOvertaking 
* T = {belowSpeedLimit, noStopping} 
* CheckSatN(BC_1): case092_premise.smt2, expect sat 
* CheckSatN(BC_2): case092_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 93 

* TSC = belowSpeedLimit 
* T = {keepInRightmostLane, speedAdvantageForOvertaking} 
* CheckSatN(BC_1): case093_premise.smt2, expect sat 
* CheckSatN(BC_2): case093_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 94 

* TSC = keepInRightmostLane 
* T = {belowSpeedLimit, speedAdvantageForOvertaking} 
* CheckSatN(BC_1): case094_premise.smt2, expect sat 
* CheckSatN(BC_2): case094_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 95 

* TSC = speedAdvantageForOvertaking 
* T = {belowSpeedLimit, keepInRightmostLane} 
* CheckSatN(BC_1): case095_premise.smt2, expect sat 
* CheckSatN(BC_2): case095_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 96 

* TSC = noStopping 
* T = {keepInRightmostLane, speedAdvantageForOvertaking} 
* CheckSatN(BC_1): case096_premise.smt2, expect sat 
* CheckSatN(BC_2): case096_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 97 

* TSC = keepInRightmostLane 
* T = {noStopping, speedAdvantageForOvertaking} 
* CheckSatN(BC_1): case097_premise.smt2, expect sat 
* CheckSatN(BC_2): case097_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 98 

* TSC = speedAdvantageForOvertaking 
* T = {keepInRightmostLane, noStopping} 
* CheckSatN(BC_1): case098_premise.smt2, expect sat 
* CheckSatN(BC_2): case098_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 99 

* TSC = belowSpeedLimit 
* T = {noPassingOnTheRightSide, speedAdvantageForOvertaking} 
* CheckSatN(BC_1): case099_premise.smt2, expect unsat 
* CheckSatN(BC_2): skipped 
* CheckSatS(BC_1): skipped 

## Case 100 

* TSC = noStopping 
* T = {noPassingOnTheRightSide, speedAdvantageForOvertaking} 
* CheckSatN(BC_1): case100_premise.smt2, expect unsat 
* CheckSatN(BC_2): skipped 
* CheckSatS(BC_1): skipped 

## Case 101 

* TSC = belowSpeedLimit 
* T = {safeLaneChange, speedAdvantageForOvertaking} 
* CheckSatN(BC_1): case101_premise.smt2, expect sat 
* CheckSatN(BC_2): case101_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 102 

* TSC = safeLaneChange 
* T = {belowSpeedLimit, speedAdvantageForOvertaking} 
* CheckSatN(BC_1): case102_premise.smt2, expect sat 
* CheckSatN(BC_2): case102_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 103 

* TSC = speedAdvantageForOvertaking 
* T = {belowSpeedLimit, safeLaneChange} 
* CheckSatN(BC_1): case103_premise.smt2, expect sat 
* CheckSatN(BC_2): case103_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 104 

* TSC = noStopping 
* T = {safeLaneChange, speedAdvantageForOvertaking} 
* CheckSatN(BC_1): case104_premise.smt2, expect sat 
* CheckSatN(BC_2): case104_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 105 

* TSC = safeLaneChange 
* T = {noStopping, speedAdvantageForOvertaking} 
* CheckSatN(BC_1): case105_premise.smt2, expect sat 
* CheckSatN(BC_2): case105_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 106 

* TSC = speedAdvantageForOvertaking 
* T = {noStopping, safeLaneChange} 
* CheckSatN(BC_1): case106_premise.smt2, expect sat 
* CheckSatN(BC_2): case106_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 107 

* TSC = belowSpeedLimit 
* T = {noStopping, safeDistance} 
* CheckSatN(BC_1): case107_premise.smt2, expect sat 
* CheckSatN(BC_2): case107_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 108 

* TSC = noStopping 
* T = {belowSpeedLimit, safeDistance} 
* CheckSatN(BC_1): case108_premise.smt2, expect sat 
* CheckSatN(BC_2): case108_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 109 

* TSC = safeDistance 
* T = {belowSpeedLimit, noStopping} 
* CheckSatN(BC_1): case109_premise.smt2, expect sat 
* CheckSatN(BC_2): case109_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 110 

* TSC = belowSpeedLimit 
* T = {keepInRightmostLane, safeDistance} 
* CheckSatN(BC_1): case110_premise.smt2, expect sat 
* CheckSatN(BC_2): case110_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 111 

* TSC = keepInRightmostLane 
* T = {belowSpeedLimit, safeDistance} 
* CheckSatN(BC_1): case111_premise.smt2, expect sat 
* CheckSatN(BC_2): case111_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 112 

* TSC = safeDistance 
* T = {belowSpeedLimit, keepInRightmostLane} 
* CheckSatN(BC_1): case112_premise.smt2, expect sat 
* CheckSatN(BC_2): case112_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 113 

* TSC = noStopping 
* T = {keepInRightmostLane, safeDistance} 
* CheckSatN(BC_1): case113_premise.smt2, expect sat 
* CheckSatN(BC_2): case113_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 114 

* TSC = keepInRightmostLane 
* T = {noStopping, safeDistance} 
* CheckSatN(BC_1): case114_premise.smt2, expect sat 
* CheckSatN(BC_2): case114_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 115 

* TSC = safeDistance 
* T = {keepInRightmostLane, noStopping} 
* CheckSatN(BC_1): case115_premise.smt2, expect sat 
* CheckSatN(BC_2): case115_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 116 

* TSC = belowSpeedLimit 
* T = {noPassingOnTheRightSide, safeDistance} 
* CheckSatN(BC_1): case116_premise.smt2, expect sat 
* CheckSatN(BC_2): case116_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 117 

* TSC = noPassingOnTheRightSide 
* T = {belowSpeedLimit, safeDistance} 
* CheckSatN(BC_1): case117_premise.smt2, expect sat 
* CheckSatN(BC_2): case117_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 118 

* TSC = safeDistance 
* T = {belowSpeedLimit, noPassingOnTheRightSide} 
* CheckSatN(BC_1): case118_premise.smt2, expect sat 
* CheckSatN(BC_2): case118_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 119 

* TSC = noStopping 
* T = {noPassingOnTheRightSide, safeDistance} 
* CheckSatN(BC_1): case119_premise.smt2, expect sat 
* CheckSatN(BC_2): case119_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 120 

* TSC = noPassingOnTheRightSide 
* T = {noStopping, safeDistance} 
* CheckSatN(BC_1): case120_premise.smt2, expect sat 
* CheckSatN(BC_2): case120_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 121 

* TSC = safeDistance 
* T = {noPassingOnTheRightSide, noStopping} 
* CheckSatN(BC_1): case121_premise.smt2, expect sat 
* CheckSatN(BC_2): case121_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 122 

* TSC = belowSpeedLimit 
* T = {safeDistance, safeLaneChange} 
* CheckSatN(BC_1): case122_premise.smt2, expect sat 
* CheckSatN(BC_2): case122_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 123 

* TSC = safeLaneChange 
* T = {belowSpeedLimit, safeDistance} 
* CheckSatN(BC_1): case123_premise.smt2, expect sat 
* CheckSatN(BC_2): case123_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 124 

* TSC = safeDistance 
* T = {belowSpeedLimit, safeLaneChange} 
* CheckSatN(BC_1): case124_premise.smt2, expect sat 
* CheckSatN(BC_2): case124_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 125 

* TSC = noStopping 
* T = {safeDistance, safeLaneChange} 
* CheckSatN(BC_1): case125_premise.smt2, expect sat 
* CheckSatN(BC_2): case125_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 126 

* TSC = safeLaneChange 
* T = {noStopping, safeDistance} 
* CheckSatN(BC_1): case126_premise.smt2, expect sat 
* CheckSatN(BC_2): case126_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 127 

* TSC = safeDistance 
* T = {noStopping, safeLaneChange} 
* CheckSatN(BC_1): case127_premise.smt2, expect sat 
* CheckSatN(BC_2): case127_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 128 

* TSC = belowSpeedLimit 
* T = {safeDistance, speedAdvantageForOvertaking} 
* CheckSatN(BC_1): case128_premise.smt2, expect sat 
* CheckSatN(BC_2): case128_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 129 

* TSC = speedAdvantageForOvertaking 
* T = {belowSpeedLimit, safeDistance} 
* CheckSatN(BC_1): case129_premise.smt2, expect sat 
* CheckSatN(BC_2): case129_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 130 

* TSC = safeDistance 
* T = {belowSpeedLimit, speedAdvantageForOvertaking} 
* CheckSatN(BC_1): case130_premise.smt2, expect sat 
* CheckSatN(BC_2): case130_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 131 

* TSC = noStopping 
* T = {safeDistance, speedAdvantageForOvertaking} 
* CheckSatN(BC_1): case131_premise.smt2, expect sat 
* CheckSatN(BC_2): case131_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 132 

* TSC = speedAdvantageForOvertaking 
* T = {noStopping, safeDistance} 
* CheckSatN(BC_1): case132_premise.smt2, expect sat 
* CheckSatN(BC_2): case132_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 133 

* TSC = safeDistance 
* T = {noStopping, speedAdvantageForOvertaking} 
* CheckSatN(BC_1): case133_premise.smt2, expect sat 
* CheckSatN(BC_2): case133_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 134 

* TSC = keepInRightmostLane 
* T = {safeDistance, speedAdvantageForOvertaking} 
* CheckSatN(BC_1): case134_premise.smt2, expect sat 
* CheckSatN(BC_2): case134_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 135 

* TSC = speedAdvantageForOvertaking 
* T = {keepInRightmostLane, safeDistance} 
* CheckSatN(BC_1): case135_premise.smt2, expect sat 
* CheckSatN(BC_2): case135_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 136 

* TSC = safeDistance 
* T = {keepInRightmostLane, speedAdvantageForOvertaking} 
* CheckSatN(BC_1): case136_premise.smt2, expect sat 
* CheckSatN(BC_2): case136_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 137 

* TSC = safeDistance 
* T = {noPassingOnTheRightSide, speedAdvantageForOvertaking} 
* CheckSatN(BC_1): case137_premise.smt2, expect unsat 
* CheckSatN(BC_2): skipped 
* CheckSatS(BC_1): skipped 

## Case 138 

* TSC = safeLaneChange 
* T = {safeDistance, speedAdvantageForOvertaking} 
* CheckSatN(BC_1): case138_premise.smt2, expect sat 
* CheckSatN(BC_2): case138_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 139 

* TSC = speedAdvantageForOvertaking 
* T = {safeDistance, safeLaneChange} 
* CheckSatN(BC_1): case139_premise.smt2, expect sat 
* CheckSatN(BC_2): case139_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 140 

* TSC = safeDistance 
* T = {safeLaneChange, speedAdvantageForOvertaking} 
* CheckSatN(BC_1): case140_premise.smt2, expect sat 
* CheckSatN(BC_2): case140_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 141 

* TSC = belowSpeedLimit 
* T = {beingOvertaken, noStopping} 
* CheckSatN(BC_1): case141_premise.smt2, expect sat 
* CheckSatN(BC_2): case141_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 142 

* TSC = noStopping 
* T = {beingOvertaken, belowSpeedLimit} 
* CheckSatN(BC_1): case142_premise.smt2, expect sat 
* CheckSatN(BC_2): case142_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 143 

* TSC = beingOvertaken 
* T = {belowSpeedLimit, noStopping} 
* CheckSatN(BC_1): case143_premise.smt2, expect sat 
* CheckSatN(BC_2): case143_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 144 

* TSC = belowSpeedLimit 
* T = {beingOvertaken, keepInRightmostLane} 
* CheckSatN(BC_1): case144_premise.smt2, expect sat 
* CheckSatN(BC_2): case144_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 145 

* TSC = keepInRightmostLane 
* T = {beingOvertaken, belowSpeedLimit} 
* CheckSatN(BC_1): case145_premise.smt2, expect sat 
* CheckSatN(BC_2): case145_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 146 

* TSC = beingOvertaken 
* T = {belowSpeedLimit, keepInRightmostLane} 
* CheckSatN(BC_1): case146_premise.smt2, expect sat 
* CheckSatN(BC_2): case146_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 147 

* TSC = noStopping 
* T = {beingOvertaken, keepInRightmostLane} 
* CheckSatN(BC_1): case147_premise.smt2, expect sat 
* CheckSatN(BC_2): case147_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 148 

* TSC = keepInRightmostLane 
* T = {beingOvertaken, noStopping} 
* CheckSatN(BC_1): case148_premise.smt2, expect sat 
* CheckSatN(BC_2): case148_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 149 

* TSC = beingOvertaken 
* T = {keepInRightmostLane, noStopping} 
* CheckSatN(BC_1): case149_premise.smt2, expect sat 
* CheckSatN(BC_2): case149_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 150 

* TSC = belowSpeedLimit 
* T = {beingOvertaken, noPassingOnTheRightSide} 
* CheckSatN(BC_1): case150_premise.smt2, expect sat 
* CheckSatN(BC_2): case150_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 151 

* TSC = noPassingOnTheRightSide 
* T = {beingOvertaken, belowSpeedLimit} 
* CheckSatN(BC_1): case151_premise.smt2, expect sat 
* CheckSatN(BC_2): case151_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 152 

* TSC = beingOvertaken 
* T = {belowSpeedLimit, noPassingOnTheRightSide} 
* CheckSatN(BC_1): case152_premise.smt2, expect sat 
* CheckSatN(BC_2): case152_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 153 

* TSC = noStopping 
* T = {beingOvertaken, noPassingOnTheRightSide} 
* CheckSatN(BC_1): case153_premise.smt2, expect sat 
* CheckSatN(BC_2): case153_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 154 

* TSC = noPassingOnTheRightSide 
* T = {beingOvertaken, noStopping} 
* CheckSatN(BC_1): case154_premise.smt2, expect sat 
* CheckSatN(BC_2): case154_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 155 

* TSC = beingOvertaken 
* T = {noPassingOnTheRightSide, noStopping} 
* CheckSatN(BC_1): case155_premise.smt2, expect sat 
* CheckSatN(BC_2): case155_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 156 

* TSC = belowSpeedLimit 
* T = {beingOvertaken, safeLaneChange} 
* CheckSatN(BC_1): case156_premise.smt2, expect sat 
* CheckSatN(BC_2): case156_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 157 

* TSC = safeLaneChange 
* T = {beingOvertaken, belowSpeedLimit} 
* CheckSatN(BC_1): case157_premise.smt2, expect sat 
* CheckSatN(BC_2): case157_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 158 

* TSC = beingOvertaken 
* T = {belowSpeedLimit, safeLaneChange} 
* CheckSatN(BC_1): case158_premise.smt2, expect sat 
* CheckSatN(BC_2): case158_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 159 

* TSC = noStopping 
* T = {beingOvertaken, safeLaneChange} 
* CheckSatN(BC_1): case159_premise.smt2, expect sat 
* CheckSatN(BC_2): case159_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 160 

* TSC = safeLaneChange 
* T = {beingOvertaken, noStopping} 
* CheckSatN(BC_1): case160_premise.smt2, expect sat 
* CheckSatN(BC_2): case160_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 161 

* TSC = beingOvertaken 
* T = {noStopping, safeLaneChange} 
* CheckSatN(BC_1): case161_premise.smt2, expect sat 
* CheckSatN(BC_2): case161_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 162 

* TSC = belowSpeedLimit 
* T = {beingOvertaken, speedAdvantageForOvertaking} 
* CheckSatN(BC_1): case162_premise.smt2, expect sat 
* CheckSatN(BC_2): case162_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 163 

* TSC = beingOvertaken 
* T = {belowSpeedLimit, speedAdvantageForOvertaking} 
* CheckSatN(BC_1): case163_premise.smt2, expect sat 
* CheckSatN(BC_2): case163_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 164 

* TSC = noStopping 
* T = {beingOvertaken, speedAdvantageForOvertaking} 
* CheckSatN(BC_1): case164_premise.smt2, expect sat 
* CheckSatN(BC_2): case164_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 165 

* TSC = beingOvertaken 
* T = {noStopping, speedAdvantageForOvertaking} 
* CheckSatN(BC_1): case165_premise.smt2, expect sat 
* CheckSatN(BC_2): case165_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 166 

* TSC = keepInRightmostLane 
* T = {beingOvertaken, speedAdvantageForOvertaking} 
* CheckSatN(BC_1): case166_premise.smt2, expect sat 
* CheckSatN(BC_2): case166_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 167 

* TSC = beingOvertaken 
* T = {keepInRightmostLane, speedAdvantageForOvertaking} 
* CheckSatN(BC_1): case167_premise.smt2, expect sat 
* CheckSatN(BC_2): case167_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 168 

* TSC = beingOvertaken 
* T = {noPassingOnTheRightSide, speedAdvantageForOvertaking} 
* CheckSatN(BC_1): case168_premise.smt2, expect unsat 
* CheckSatN(BC_2): skipped 
* CheckSatS(BC_1): skipped 

## Case 169 

* TSC = safeLaneChange 
* T = {beingOvertaken, speedAdvantageForOvertaking} 
* CheckSatN(BC_1): case169_premise.smt2, expect sat 
* CheckSatN(BC_2): case169_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 170 

* TSC = beingOvertaken 
* T = {safeLaneChange, speedAdvantageForOvertaking} 
* CheckSatN(BC_1): case170_premise.smt2, expect sat 
* CheckSatN(BC_2): case170_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 171 

* TSC = belowSpeedLimit 
* T = {beingOvertaken, safeDistance} 
* CheckSatN(BC_1): case171_premise.smt2, expect sat 
* CheckSatN(BC_2): case171_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 172 

* TSC = safeDistance 
* T = {beingOvertaken, belowSpeedLimit} 
* CheckSatN(BC_1): case172_premise.smt2, expect sat 
* CheckSatN(BC_2): case172_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 173 

* TSC = beingOvertaken 
* T = {belowSpeedLimit, safeDistance} 
* CheckSatN(BC_1): case173_premise.smt2, expect sat 
* CheckSatN(BC_2): case173_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 174 

* TSC = noStopping 
* T = {beingOvertaken, safeDistance} 
* CheckSatN(BC_1): case174_premise.smt2, expect sat 
* CheckSatN(BC_2): case174_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 175 

* TSC = safeDistance 
* T = {beingOvertaken, noStopping} 
* CheckSatN(BC_1): case175_premise.smt2, expect sat 
* CheckSatN(BC_2): case175_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 176 

* TSC = beingOvertaken 
* T = {noStopping, safeDistance} 
* CheckSatN(BC_1): case176_premise.smt2, expect sat 
* CheckSatN(BC_2): case176_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 177 

* TSC = keepInRightmostLane 
* T = {beingOvertaken, safeDistance} 
* CheckSatN(BC_1): case177_premise.smt2, expect sat 
* CheckSatN(BC_2): case177_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 178 

* TSC = safeDistance 
* T = {beingOvertaken, keepInRightmostLane} 
* CheckSatN(BC_1): case178_premise.smt2, expect sat 
* CheckSatN(BC_2): case178_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 179 

* TSC = beingOvertaken 
* T = {keepInRightmostLane, safeDistance} 
* CheckSatN(BC_1): case179_premise.smt2, expect sat 
* CheckSatN(BC_2): case179_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 180 

* TSC = noPassingOnTheRightSide 
* T = {beingOvertaken, safeDistance} 
* CheckSatN(BC_1): case180_premise.smt2, expect sat 
* CheckSatN(BC_2): case180_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 181 

* TSC = safeDistance 
* T = {beingOvertaken, noPassingOnTheRightSide} 
* CheckSatN(BC_1): case181_premise.smt2, expect sat 
* CheckSatN(BC_2): case181_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 182 

* TSC = beingOvertaken 
* T = {noPassingOnTheRightSide, safeDistance} 
* CheckSatN(BC_1): case182_premise.smt2, expect sat 
* CheckSatN(BC_2): case182_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 183 

* TSC = safeLaneChange 
* T = {beingOvertaken, safeDistance} 
* CheckSatN(BC_1): case183_premise.smt2, expect sat 
* CheckSatN(BC_2): case183_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 184 

* TSC = safeDistance 
* T = {beingOvertaken, safeLaneChange} 
* CheckSatN(BC_1): case184_premise.smt2, expect sat 
* CheckSatN(BC_2): case184_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 185 

* TSC = beingOvertaken 
* T = {safeDistance, safeLaneChange} 
* CheckSatN(BC_1): case185_premise.smt2, expect sat 
* CheckSatN(BC_2): case185_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 186 

* TSC = safeDistance 
* T = {beingOvertaken, speedAdvantageForOvertaking} 
* CheckSatN(BC_1): case186_premise.smt2, expect sat 
* CheckSatN(BC_2): case186_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 187 

* TSC = beingOvertaken 
* T = {safeDistance, speedAdvantageForOvertaking} 
* CheckSatN(BC_1): case187_premise.smt2, expect sat 
* CheckSatN(BC_2): case187_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 188 

* TSC = belowSpeedLimit 
* T = {noStopping, zipperMerge} 
* CheckSatN(BC_1): case188_premise.smt2, expect sat 
* CheckSatN(BC_2): case188_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 189 

* TSC = noStopping 
* T = {belowSpeedLimit, zipperMerge} 
* CheckSatN(BC_1): case189_premise.smt2, expect sat 
* CheckSatN(BC_2): case189_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 190 

* TSC = zipperMerge 
* T = {belowSpeedLimit, noStopping} 
* CheckSatN(BC_1): case190_premise.smt2, expect sat 
* CheckSatN(BC_2): case190_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 191 

* TSC = belowSpeedLimit 
* T = {keepInRightmostLane, zipperMerge} 
* CheckSatN(BC_1): case191_premise.smt2, expect sat 
* CheckSatN(BC_2): case191_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 192 

* TSC = keepInRightmostLane 
* T = {belowSpeedLimit, zipperMerge} 
* CheckSatN(BC_1): case192_premise.smt2, expect sat 
* CheckSatN(BC_2): case192_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 193 

* TSC = zipperMerge 
* T = {belowSpeedLimit, keepInRightmostLane} 
* CheckSatN(BC_1): case193_premise.smt2, expect sat 
* CheckSatN(BC_2): case193_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 194 

* TSC = noStopping 
* T = {keepInRightmostLane, zipperMerge} 
* CheckSatN(BC_1): case194_premise.smt2, expect sat 
* CheckSatN(BC_2): case194_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 195 

* TSC = keepInRightmostLane 
* T = {noStopping, zipperMerge} 
* CheckSatN(BC_1): case195_premise.smt2, expect sat 
* CheckSatN(BC_2): case195_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 196 

* TSC = zipperMerge 
* T = {keepInRightmostLane, noStopping} 
* CheckSatN(BC_1): case196_premise.smt2, expect sat 
* CheckSatN(BC_2): case196_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 197 

* TSC = belowSpeedLimit 
* T = {noPassingOnTheRightSide, zipperMerge} 
* CheckSatN(BC_1): case197_premise.smt2, expect sat 
* CheckSatN(BC_2): case197_consequence.smt2, expect unsat 
* CheckSatS(BC_1): case197_premiseCheck.smt2, expect unsat 

## Case 198 

* TSC = noStopping 
* T = {noPassingOnTheRightSide, zipperMerge} 
* CheckSatN(BC_1): case198_premise.smt2, expect sat 
* CheckSatN(BC_2): case198_consequence.smt2, expect unsat 
* CheckSatS(BC_1): case198_premiseCheck.smt2, expect unsat 

## Case 199 

* TSC = belowSpeedLimit 
* T = {safeLaneChange, zipperMerge} 
* CheckSatN(BC_1): case199_premise.smt2, expect unsat 
* CheckSatN(BC_2): skipped 
* CheckSatS(BC_1): skipped 

## Case 200 

* TSC = noStopping 
* T = {safeLaneChange, zipperMerge} 
* CheckSatN(BC_1): case200_premise.smt2, expect unsat 
* CheckSatN(BC_2): skipped 
* CheckSatS(BC_1): skipped 

## Case 201 

* TSC = belowSpeedLimit 
* T = {speedAdvantageForOvertaking, zipperMerge} 
* CheckSatN(BC_1): case201_premise.smt2, expect sat 
* CheckSatN(BC_2): case201_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 202 

* TSC = speedAdvantageForOvertaking 
* T = {belowSpeedLimit, zipperMerge} 
* CheckSatN(BC_1): case202_premise.smt2, expect sat 
* CheckSatN(BC_2): case202_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 203 

* TSC = zipperMerge 
* T = {belowSpeedLimit, speedAdvantageForOvertaking} 
* CheckSatN(BC_1): case203_premise.smt2, expect sat 
* CheckSatN(BC_2): case203_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 204 

* TSC = noStopping 
* T = {speedAdvantageForOvertaking, zipperMerge} 
* CheckSatN(BC_1): case204_premise.smt2, expect sat 
* CheckSatN(BC_2): case204_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 205 

* TSC = speedAdvantageForOvertaking 
* T = {noStopping, zipperMerge} 
* CheckSatN(BC_1): case205_premise.smt2, expect sat 
* CheckSatN(BC_2): case205_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 206 

* TSC = zipperMerge 
* T = {noStopping, speedAdvantageForOvertaking} 
* CheckSatN(BC_1): case206_premise.smt2, expect sat 
* CheckSatN(BC_2): case206_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 207 

* TSC = keepInRightmostLane 
* T = {speedAdvantageForOvertaking, zipperMerge} 
* CheckSatN(BC_1): case207_premise.smt2, expect sat 
* CheckSatN(BC_2): case207_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 208 

* TSC = speedAdvantageForOvertaking 
* T = {keepInRightmostLane, zipperMerge} 
* CheckSatN(BC_1): case208_premise.smt2, expect sat 
* CheckSatN(BC_2): case208_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 209 

* TSC = zipperMerge 
* T = {keepInRightmostLane, speedAdvantageForOvertaking} 
* CheckSatN(BC_1): case209_premise.smt2, expect sat 
* CheckSatN(BC_2): case209_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 210 

* TSC = speedAdvantageForOvertaking 
* T = {safeLaneChange, zipperMerge} 
* CheckSatN(BC_1): case210_premise.smt2, expect unsat 
* CheckSatN(BC_2): skipped 
* CheckSatS(BC_1): skipped 

## Case 211 

* TSC = belowSpeedLimit 
* T = {safeDistance, zipperMerge} 
* CheckSatN(BC_1): case211_premise.smt2, expect sat 
* CheckSatN(BC_2): case211_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 212 

* TSC = safeDistance 
* T = {belowSpeedLimit, zipperMerge} 
* CheckSatN(BC_1): case212_premise.smt2, expect sat 
* CheckSatN(BC_2): case212_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 213 

* TSC = zipperMerge 
* T = {belowSpeedLimit, safeDistance} 
* CheckSatN(BC_1): case213_premise.smt2, expect sat 
* CheckSatN(BC_2): case213_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 214 

* TSC = noStopping 
* T = {safeDistance, zipperMerge} 
* CheckSatN(BC_1): case214_premise.smt2, expect sat 
* CheckSatN(BC_2): case214_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 215 

* TSC = safeDistance 
* T = {noStopping, zipperMerge} 
* CheckSatN(BC_1): case215_premise.smt2, expect sat 
* CheckSatN(BC_2): case215_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 216 

* TSC = zipperMerge 
* T = {noStopping, safeDistance} 
* CheckSatN(BC_1): case216_premise.smt2, expect sat 
* CheckSatN(BC_2): case216_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 217 

* TSC = keepInRightmostLane 
* T = {safeDistance, zipperMerge} 
* CheckSatN(BC_1): case217_premise.smt2, expect sat 
* CheckSatN(BC_2): case217_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 218 

* TSC = safeDistance 
* T = {keepInRightmostLane, zipperMerge} 
* CheckSatN(BC_1): case218_premise.smt2, expect sat 
* CheckSatN(BC_2): case218_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 219 

* TSC = zipperMerge 
* T = {keepInRightmostLane, safeDistance} 
* CheckSatN(BC_1): case219_premise.smt2, expect sat 
* CheckSatN(BC_2): case219_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 220 

* TSC = safeDistance 
* T = {noPassingOnTheRightSide, zipperMerge} 
* CheckSatN(BC_1): case220_premise.smt2, expect sat 
* CheckSatN(BC_2): case220_consequence.smt2, expect unsat 
* CheckSatS(BC_1): case220_premiseCheck.smt2, expect unsat 

## Case 221 

* TSC = safeDistance 
* T = {safeLaneChange, zipperMerge} 
* CheckSatN(BC_1): case221_premise.smt2, expect unsat 
* CheckSatN(BC_2): skipped 
* CheckSatS(BC_1): skipped 

## Case 222 

* TSC = speedAdvantageForOvertaking 
* T = {safeDistance, zipperMerge} 
* CheckSatN(BC_1): case222_premise.smt2, expect sat 
* CheckSatN(BC_2): case222_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 223 

* TSC = safeDistance 
* T = {speedAdvantageForOvertaking, zipperMerge} 
* CheckSatN(BC_1): case223_premise.smt2, expect sat 
* CheckSatN(BC_2): case223_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 224 

* TSC = zipperMerge 
* T = {safeDistance, speedAdvantageForOvertaking} 
* CheckSatN(BC_1): case224_premise.smt2, expect sat 
* CheckSatN(BC_2): case224_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 225 

* TSC = belowSpeedLimit 
* T = {beingOvertaken, zipperMerge} 
* CheckSatN(BC_1): case225_premise.smt2, expect sat 
* CheckSatN(BC_2): case225_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 226 

* TSC = beingOvertaken 
* T = {belowSpeedLimit, zipperMerge} 
* CheckSatN(BC_1): case226_premise.smt2, expect sat 
* CheckSatN(BC_2): case226_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 227 

* TSC = zipperMerge 
* T = {beingOvertaken, belowSpeedLimit} 
* CheckSatN(BC_1): case227_premise.smt2, expect sat 
* CheckSatN(BC_2): case227_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 228 

* TSC = noStopping 
* T = {beingOvertaken, zipperMerge} 
* CheckSatN(BC_1): case228_premise.smt2, expect sat 
* CheckSatN(BC_2): case228_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 229 

* TSC = beingOvertaken 
* T = {noStopping, zipperMerge} 
* CheckSatN(BC_1): case229_premise.smt2, expect sat 
* CheckSatN(BC_2): case229_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 230 

* TSC = zipperMerge 
* T = {beingOvertaken, noStopping} 
* CheckSatN(BC_1): case230_premise.smt2, expect sat 
* CheckSatN(BC_2): case230_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 231 

* TSC = keepInRightmostLane 
* T = {beingOvertaken, zipperMerge} 
* CheckSatN(BC_1): case231_premise.smt2, expect sat 
* CheckSatN(BC_2): case231_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 232 

* TSC = beingOvertaken 
* T = {keepInRightmostLane, zipperMerge} 
* CheckSatN(BC_1): case232_premise.smt2, expect sat 
* CheckSatN(BC_2): case232_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 233 

* TSC = zipperMerge 
* T = {beingOvertaken, keepInRightmostLane} 
* CheckSatN(BC_1): case233_premise.smt2, expect sat 
* CheckSatN(BC_2): case233_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 234 

* TSC = beingOvertaken 
* T = {noPassingOnTheRightSide, zipperMerge} 
* CheckSatN(BC_1): case234_premise.smt2, expect sat 
* CheckSatN(BC_2): case234_consequence.smt2, expect unsat 
* CheckSatS(BC_1): case234_premiseCheck.smt2, expect unsat 

## Case 235 

* TSC = beingOvertaken 
* T = {safeLaneChange, zipperMerge} 
* CheckSatN(BC_1): case235_premise.smt2, expect unsat 
* CheckSatN(BC_2): skipped 
* CheckSatS(BC_1): skipped 

## Case 236 

* TSC = beingOvertaken 
* T = {speedAdvantageForOvertaking, zipperMerge} 
* CheckSatN(BC_1): case236_premise.smt2, expect sat 
* CheckSatN(BC_2): case236_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 237 

* TSC = zipperMerge 
* T = {beingOvertaken, speedAdvantageForOvertaking} 
* CheckSatN(BC_1): case237_premise.smt2, expect sat 
* CheckSatN(BC_2): case237_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 238 

* TSC = safeDistance 
* T = {beingOvertaken, zipperMerge} 
* CheckSatN(BC_1): case238_premise.smt2, expect sat 
* CheckSatN(BC_2): case238_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 239 

* TSC = beingOvertaken 
* T = {safeDistance, zipperMerge} 
* CheckSatN(BC_1): case239_premise.smt2, expect sat 
* CheckSatN(BC_2): case239_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 240 

* TSC = zipperMerge 
* T = {beingOvertaken, safeDistance} 
* CheckSatN(BC_1): case240_premise.smt2, expect sat 
* CheckSatN(BC_2): case240_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 241 

* TSC = belowSpeedLimit 
* T = {keepInRightmostLane, noStopping, speedAdvantageForOvertaking} 
* CheckSatN(BC_1): case241_premise.smt2, expect sat 
* CheckSatN(BC_2): case241_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 242 

* TSC = noStopping 
* T = {belowSpeedLimit, keepInRightmostLane, speedAdvantageForOvertaking} 
* CheckSatN(BC_1): case242_premise.smt2, expect sat 
* CheckSatN(BC_2): case242_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 243 

* TSC = keepInRightmostLane 
* T = {belowSpeedLimit, noStopping, speedAdvantageForOvertaking} 
* CheckSatN(BC_1): case243_premise.smt2, expect sat 
* CheckSatN(BC_2): case243_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 244 

* TSC = speedAdvantageForOvertaking 
* T = {belowSpeedLimit, keepInRightmostLane, noStopping} 
* CheckSatN(BC_1): case244_premise.smt2, expect sat 
* CheckSatN(BC_2): case244_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 245 

* TSC = belowSpeedLimit 
* T = {noStopping, safeLaneChange, speedAdvantageForOvertaking} 
* CheckSatN(BC_1): case245_premise.smt2, expect sat 
* CheckSatN(BC_2): case245_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 246 

* TSC = noStopping 
* T = {belowSpeedLimit, safeLaneChange, speedAdvantageForOvertaking} 
* CheckSatN(BC_1): case246_premise.smt2, expect sat 
* CheckSatN(BC_2): case246_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 247 

* TSC = safeLaneChange 
* T = {belowSpeedLimit, noStopping, speedAdvantageForOvertaking} 
* CheckSatN(BC_1): case247_premise.smt2, expect sat 
* CheckSatN(BC_2): case247_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 248 

* TSC = speedAdvantageForOvertaking 
* T = {belowSpeedLimit, noStopping, safeLaneChange} 
* CheckSatN(BC_1): case248_premise.smt2, expect sat 
* CheckSatN(BC_2): case248_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 249 

* TSC = belowSpeedLimit 
* T = {keepInRightmostLane, noStopping, safeDistance} 
* CheckSatN(BC_1): case249_premise.smt2, expect sat 
* CheckSatN(BC_2): case249_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 250 

* TSC = noStopping 
* T = {belowSpeedLimit, keepInRightmostLane, safeDistance} 
* CheckSatN(BC_1): case250_premise.smt2, expect sat 
* CheckSatN(BC_2): case250_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 251 

* TSC = keepInRightmostLane 
* T = {belowSpeedLimit, noStopping, safeDistance} 
* CheckSatN(BC_1): case251_premise.smt2, expect sat 
* CheckSatN(BC_2): case251_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 252 

* TSC = safeDistance 
* T = {belowSpeedLimit, keepInRightmostLane, noStopping} 
* CheckSatN(BC_1): case252_premise.smt2, expect sat 
* CheckSatN(BC_2): case252_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 253 

* TSC = belowSpeedLimit 
* T = {noPassingOnTheRightSide, noStopping, safeDistance} 
* CheckSatN(BC_1): case253_premise.smt2, expect sat 
* CheckSatN(BC_2): case253_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 254 

* TSC = noStopping 
* T = {belowSpeedLimit, noPassingOnTheRightSide, safeDistance} 
* CheckSatN(BC_1): case254_premise.smt2, expect sat 
* CheckSatN(BC_2): case254_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 255 

* TSC = noPassingOnTheRightSide 
* T = {belowSpeedLimit, noStopping, safeDistance} 
* CheckSatN(BC_1): case255_premise.smt2, expect sat 
* CheckSatN(BC_2): case255_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 256 

* TSC = safeDistance 
* T = {belowSpeedLimit, noPassingOnTheRightSide, noStopping} 
* CheckSatN(BC_1): case256_premise.smt2, expect sat 
* CheckSatN(BC_2): case256_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 257 

* TSC = belowSpeedLimit 
* T = {noStopping, safeDistance, safeLaneChange} 
* CheckSatN(BC_1): case257_premise.smt2, expect sat 
* CheckSatN(BC_2): case257_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 258 

* TSC = noStopping 
* T = {belowSpeedLimit, safeDistance, safeLaneChange} 
* CheckSatN(BC_1): case258_premise.smt2, expect sat 
* CheckSatN(BC_2): case258_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 259 

* TSC = safeLaneChange 
* T = {belowSpeedLimit, noStopping, safeDistance} 
* CheckSatN(BC_1): case259_premise.smt2, expect sat 
* CheckSatN(BC_2): case259_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 260 

* TSC = safeDistance 
* T = {belowSpeedLimit, noStopping, safeLaneChange} 
* CheckSatN(BC_1): case260_premise.smt2, expect sat 
* CheckSatN(BC_2): case260_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 261 

* TSC = belowSpeedLimit 
* T = {noStopping, safeDistance, speedAdvantageForOvertaking} 
* CheckSatN(BC_1): case261_premise.smt2, expect sat 
* CheckSatN(BC_2): case261_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 262 

* TSC = noStopping 
* T = {belowSpeedLimit, safeDistance, speedAdvantageForOvertaking} 
* CheckSatN(BC_1): case262_premise.smt2, expect sat 
* CheckSatN(BC_2): case262_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 263 

* TSC = speedAdvantageForOvertaking 
* T = {belowSpeedLimit, noStopping, safeDistance} 
* CheckSatN(BC_1): case263_premise.smt2, expect sat 
* CheckSatN(BC_2): case263_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 264 

* TSC = safeDistance 
* T = {belowSpeedLimit, noStopping, speedAdvantageForOvertaking} 
* CheckSatN(BC_1): case264_premise.smt2, expect sat 
* CheckSatN(BC_2): case264_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 265 

* TSC = belowSpeedLimit 
* T = {keepInRightmostLane, safeDistance, speedAdvantageForOvertaking} 
* CheckSatN(BC_1): case265_premise.smt2, expect sat 
* CheckSatN(BC_2): case265_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 266 

* TSC = keepInRightmostLane 
* T = {belowSpeedLimit, safeDistance, speedAdvantageForOvertaking} 
* CheckSatN(BC_1): case266_premise.smt2, expect sat 
* CheckSatN(BC_2): case266_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 267 

* TSC = speedAdvantageForOvertaking 
* T = {belowSpeedLimit, keepInRightmostLane, safeDistance} 
* CheckSatN(BC_1): case267_premise.smt2, expect sat 
* CheckSatN(BC_2): case267_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 268 

* TSC = safeDistance 
* T = {belowSpeedLimit, keepInRightmostLane, speedAdvantageForOvertaking} 
* CheckSatN(BC_1): case268_premise.smt2, expect sat 
* CheckSatN(BC_2): case268_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 269 

* TSC = noStopping 
* T = {keepInRightmostLane, safeDistance, speedAdvantageForOvertaking} 
* CheckSatN(BC_1): case269_premise.smt2, expect sat 
* CheckSatN(BC_2): case269_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 270 

* TSC = keepInRightmostLane 
* T = {noStopping, safeDistance, speedAdvantageForOvertaking} 
* CheckSatN(BC_1): case270_premise.smt2, expect sat 
* CheckSatN(BC_2): case270_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 271 

* TSC = speedAdvantageForOvertaking 
* T = {keepInRightmostLane, noStopping, safeDistance} 
* CheckSatN(BC_1): case271_premise.smt2, expect sat 
* CheckSatN(BC_2): case271_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 272 

* TSC = safeDistance 
* T = {keepInRightmostLane, noStopping, speedAdvantageForOvertaking} 
* CheckSatN(BC_1): case272_premise.smt2, expect sat 
* CheckSatN(BC_2): case272_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 273 

* TSC = belowSpeedLimit 
* T = {safeDistance, safeLaneChange, speedAdvantageForOvertaking} 
* CheckSatN(BC_1): case273_premise.smt2, expect sat 
* CheckSatN(BC_2): case273_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 274 

* TSC = safeLaneChange 
* T = {belowSpeedLimit, safeDistance, speedAdvantageForOvertaking} 
* CheckSatN(BC_1): case274_premise.smt2, expect sat 
* CheckSatN(BC_2): case274_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 275 

* TSC = speedAdvantageForOvertaking 
* T = {belowSpeedLimit, safeDistance, safeLaneChange} 
* CheckSatN(BC_1): case275_premise.smt2, expect sat 
* CheckSatN(BC_2): case275_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 276 

* TSC = safeDistance 
* T = {belowSpeedLimit, safeLaneChange, speedAdvantageForOvertaking} 
* CheckSatN(BC_1): case276_premise.smt2, expect sat 
* CheckSatN(BC_2): case276_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 277 

* TSC = noStopping 
* T = {safeDistance, safeLaneChange, speedAdvantageForOvertaking} 
* CheckSatN(BC_1): case277_premise.smt2, expect sat 
* CheckSatN(BC_2): case277_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 278 

* TSC = safeLaneChange 
* T = {noStopping, safeDistance, speedAdvantageForOvertaking} 
* CheckSatN(BC_1): case278_premise.smt2, expect sat 
* CheckSatN(BC_2): case278_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 279 

* TSC = speedAdvantageForOvertaking 
* T = {noStopping, safeDistance, safeLaneChange} 
* CheckSatN(BC_1): case279_premise.smt2, expect sat 
* CheckSatN(BC_2): case279_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 280 

* TSC = safeDistance 
* T = {noStopping, safeLaneChange, speedAdvantageForOvertaking} 
* CheckSatN(BC_1): case280_premise.smt2, expect sat 
* CheckSatN(BC_2): case280_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 281 

* TSC = belowSpeedLimit 
* T = {beingOvertaken, keepInRightmostLane, noStopping} 
* CheckSatN(BC_1): case281_premise.smt2, expect sat 
* CheckSatN(BC_2): case281_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 282 

* TSC = noStopping 
* T = {beingOvertaken, belowSpeedLimit, keepInRightmostLane} 
* CheckSatN(BC_1): case282_premise.smt2, expect sat 
* CheckSatN(BC_2): case282_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 283 

* TSC = keepInRightmostLane 
* T = {beingOvertaken, belowSpeedLimit, noStopping} 
* CheckSatN(BC_1): case283_premise.smt2, expect sat 
* CheckSatN(BC_2): case283_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 284 

* TSC = beingOvertaken 
* T = {belowSpeedLimit, keepInRightmostLane, noStopping} 
* CheckSatN(BC_1): case284_premise.smt2, expect sat 
* CheckSatN(BC_2): case284_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 285 

* TSC = belowSpeedLimit 
* T = {beingOvertaken, noPassingOnTheRightSide, noStopping} 
* CheckSatN(BC_1): case285_premise.smt2, expect sat 
* CheckSatN(BC_2): case285_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 286 

* TSC = noStopping 
* T = {beingOvertaken, belowSpeedLimit, noPassingOnTheRightSide} 
* CheckSatN(BC_1): case286_premise.smt2, expect sat 
* CheckSatN(BC_2): case286_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 287 

* TSC = noPassingOnTheRightSide 
* T = {beingOvertaken, belowSpeedLimit, noStopping} 
* CheckSatN(BC_1): case287_premise.smt2, expect sat 
* CheckSatN(BC_2): case287_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 288 

* TSC = beingOvertaken 
* T = {belowSpeedLimit, noPassingOnTheRightSide, noStopping} 
* CheckSatN(BC_1): case288_premise.smt2, expect sat 
* CheckSatN(BC_2): case288_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 289 

* TSC = belowSpeedLimit 
* T = {beingOvertaken, noStopping, safeLaneChange} 
* CheckSatN(BC_1): case289_premise.smt2, expect sat 
* CheckSatN(BC_2): case289_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 290 

* TSC = noStopping 
* T = {beingOvertaken, belowSpeedLimit, safeLaneChange} 
* CheckSatN(BC_1): case290_premise.smt2, expect sat 
* CheckSatN(BC_2): case290_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 291 

* TSC = safeLaneChange 
* T = {beingOvertaken, belowSpeedLimit, noStopping} 
* CheckSatN(BC_1): case291_premise.smt2, expect sat 
* CheckSatN(BC_2): case291_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 292 

* TSC = beingOvertaken 
* T = {belowSpeedLimit, noStopping, safeLaneChange} 
* CheckSatN(BC_1): case292_premise.smt2, expect sat 
* CheckSatN(BC_2): case292_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 293 

* TSC = belowSpeedLimit 
* T = {beingOvertaken, noStopping, safeDistance} 
* CheckSatN(BC_1): case293_premise.smt2, expect sat 
* CheckSatN(BC_2): case293_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 294 

* TSC = noStopping 
* T = {beingOvertaken, belowSpeedLimit, safeDistance} 
* CheckSatN(BC_1): case294_premise.smt2, expect sat 
* CheckSatN(BC_2): case294_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 295 

* TSC = safeDistance 
* T = {beingOvertaken, belowSpeedLimit, noStopping} 
* CheckSatN(BC_1): case295_premise.smt2, expect sat 
* CheckSatN(BC_2): case295_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 296 

* TSC = beingOvertaken 
* T = {belowSpeedLimit, noStopping, safeDistance} 
* CheckSatN(BC_1): case296_premise.smt2, expect sat 
* CheckSatN(BC_2): case296_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 297 

* TSC = belowSpeedLimit 
* T = {beingOvertaken, keepInRightmostLane, safeDistance} 
* CheckSatN(BC_1): case297_premise.smt2, expect sat 
* CheckSatN(BC_2): case297_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 298 

* TSC = keepInRightmostLane 
* T = {beingOvertaken, belowSpeedLimit, safeDistance} 
* CheckSatN(BC_1): case298_premise.smt2, expect sat 
* CheckSatN(BC_2): case298_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 299 

* TSC = safeDistance 
* T = {beingOvertaken, belowSpeedLimit, keepInRightmostLane} 
* CheckSatN(BC_1): case299_premise.smt2, expect sat 
* CheckSatN(BC_2): case299_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 300 

* TSC = beingOvertaken 
* T = {belowSpeedLimit, keepInRightmostLane, safeDistance} 
* CheckSatN(BC_1): case300_premise.smt2, expect sat 
* CheckSatN(BC_2): case300_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 301 

* TSC = noStopping 
* T = {beingOvertaken, keepInRightmostLane, safeDistance} 
* CheckSatN(BC_1): case301_premise.smt2, expect sat 
* CheckSatN(BC_2): case301_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 302 

* TSC = keepInRightmostLane 
* T = {beingOvertaken, noStopping, safeDistance} 
* CheckSatN(BC_1): case302_premise.smt2, expect sat 
* CheckSatN(BC_2): case302_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 303 

* TSC = safeDistance 
* T = {beingOvertaken, keepInRightmostLane, noStopping} 
* CheckSatN(BC_1): case303_premise.smt2, expect sat 
* CheckSatN(BC_2): case303_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 304 

* TSC = beingOvertaken 
* T = {keepInRightmostLane, noStopping, safeDistance} 
* CheckSatN(BC_1): case304_premise.smt2, expect sat 
* CheckSatN(BC_2): case304_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 305 

* TSC = belowSpeedLimit 
* T = {beingOvertaken, noPassingOnTheRightSide, safeDistance} 
* CheckSatN(BC_1): case305_premise.smt2, expect sat 
* CheckSatN(BC_2): case305_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 306 

* TSC = noPassingOnTheRightSide 
* T = {beingOvertaken, belowSpeedLimit, safeDistance} 
* CheckSatN(BC_1): case306_premise.smt2, expect sat 
* CheckSatN(BC_2): case306_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 307 

* TSC = safeDistance 
* T = {beingOvertaken, belowSpeedLimit, noPassingOnTheRightSide} 
* CheckSatN(BC_1): case307_premise.smt2, expect sat 
* CheckSatN(BC_2): case307_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 308 

* TSC = beingOvertaken 
* T = {belowSpeedLimit, noPassingOnTheRightSide, safeDistance} 
* CheckSatN(BC_1): case308_premise.smt2, expect sat 
* CheckSatN(BC_2): case308_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 309 

* TSC = noStopping 
* T = {beingOvertaken, noPassingOnTheRightSide, safeDistance} 
* CheckSatN(BC_1): case309_premise.smt2, expect sat 
* CheckSatN(BC_2): case309_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 310 

* TSC = noPassingOnTheRightSide 
* T = {beingOvertaken, noStopping, safeDistance} 
* CheckSatN(BC_1): case310_premise.smt2, expect sat 
* CheckSatN(BC_2): case310_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 311 

* TSC = safeDistance 
* T = {beingOvertaken, noPassingOnTheRightSide, noStopping} 
* CheckSatN(BC_1): case311_premise.smt2, expect sat 
* CheckSatN(BC_2): case311_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 312 

* TSC = beingOvertaken 
* T = {noPassingOnTheRightSide, noStopping, safeDistance} 
* CheckSatN(BC_1): case312_premise.smt2, expect sat 
* CheckSatN(BC_2): case312_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 313 

* TSC = belowSpeedLimit 
* T = {beingOvertaken, safeDistance, safeLaneChange} 
* CheckSatN(BC_1): case313_premise.smt2, expect sat 
* CheckSatN(BC_2): case313_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 314 

* TSC = safeLaneChange 
* T = {beingOvertaken, belowSpeedLimit, safeDistance} 
* CheckSatN(BC_1): case314_premise.smt2, expect sat 
* CheckSatN(BC_2): case314_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 315 

* TSC = safeDistance 
* T = {beingOvertaken, belowSpeedLimit, safeLaneChange} 
* CheckSatN(BC_1): case315_premise.smt2, expect sat 
* CheckSatN(BC_2): case315_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 316 

* TSC = beingOvertaken 
* T = {belowSpeedLimit, safeDistance, safeLaneChange} 
* CheckSatN(BC_1): case316_premise.smt2, expect sat 
* CheckSatN(BC_2): case316_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 317 

* TSC = noStopping 
* T = {beingOvertaken, safeDistance, safeLaneChange} 
* CheckSatN(BC_1): case317_premise.smt2, expect sat 
* CheckSatN(BC_2): case317_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 318 

* TSC = safeLaneChange 
* T = {beingOvertaken, noStopping, safeDistance} 
* CheckSatN(BC_1): case318_premise.smt2, expect sat 
* CheckSatN(BC_2): case318_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 319 

* TSC = safeDistance 
* T = {beingOvertaken, noStopping, safeLaneChange} 
* CheckSatN(BC_1): case319_premise.smt2, expect sat 
* CheckSatN(BC_2): case319_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 320 

* TSC = beingOvertaken 
* T = {noStopping, safeDistance, safeLaneChange} 
* CheckSatN(BC_1): case320_premise.smt2, expect sat 
* CheckSatN(BC_2): case320_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 321 

* TSC = belowSpeedLimit 
* T = {keepInRightmostLane, noStopping, zipperMerge} 
* CheckSatN(BC_1): case321_premise.smt2, expect sat 
* CheckSatN(BC_2): case321_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 322 

* TSC = noStopping 
* T = {belowSpeedLimit, keepInRightmostLane, zipperMerge} 
* CheckSatN(BC_1): case322_premise.smt2, expect sat 
* CheckSatN(BC_2): case322_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 323 

* TSC = keepInRightmostLane 
* T = {belowSpeedLimit, noStopping, zipperMerge} 
* CheckSatN(BC_1): case323_premise.smt2, expect sat 
* CheckSatN(BC_2): case323_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 324 

* TSC = zipperMerge 
* T = {belowSpeedLimit, keepInRightmostLane, noStopping} 
* CheckSatN(BC_1): case324_premise.smt2, expect sat 
* CheckSatN(BC_2): case324_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 325 

* TSC = belowSpeedLimit 
* T = {noStopping, speedAdvantageForOvertaking, zipperMerge} 
* CheckSatN(BC_1): case325_premise.smt2, expect sat 
* CheckSatN(BC_2): case325_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 326 

* TSC = noStopping 
* T = {belowSpeedLimit, speedAdvantageForOvertaking, zipperMerge} 
* CheckSatN(BC_1): case326_premise.smt2, expect sat 
* CheckSatN(BC_2): case326_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 327 

* TSC = speedAdvantageForOvertaking 
* T = {belowSpeedLimit, noStopping, zipperMerge} 
* CheckSatN(BC_1): case327_premise.smt2, expect sat 
* CheckSatN(BC_2): case327_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 328 

* TSC = zipperMerge 
* T = {belowSpeedLimit, noStopping, speedAdvantageForOvertaking} 
* CheckSatN(BC_1): case328_premise.smt2, expect sat 
* CheckSatN(BC_2): case328_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 329 

* TSC = belowSpeedLimit 
* T = {keepInRightmostLane, speedAdvantageForOvertaking, zipperMerge} 
* CheckSatN(BC_1): case329_premise.smt2, expect sat 
* CheckSatN(BC_2): case329_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 330 

* TSC = keepInRightmostLane 
* T = {belowSpeedLimit, speedAdvantageForOvertaking, zipperMerge} 
* CheckSatN(BC_1): case330_premise.smt2, expect sat 
* CheckSatN(BC_2): case330_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 331 

* TSC = speedAdvantageForOvertaking 
* T = {belowSpeedLimit, keepInRightmostLane, zipperMerge} 
* CheckSatN(BC_1): case331_premise.smt2, expect sat 
* CheckSatN(BC_2): case331_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 332 

* TSC = zipperMerge 
* T = {belowSpeedLimit, keepInRightmostLane, speedAdvantageForOvertaking} 
* CheckSatN(BC_1): case332_premise.smt2, expect sat 
* CheckSatN(BC_2): case332_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 333 

* TSC = noStopping 
* T = {keepInRightmostLane, speedAdvantageForOvertaking, zipperMerge} 
* CheckSatN(BC_1): case333_premise.smt2, expect sat 
* CheckSatN(BC_2): case333_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 334 

* TSC = keepInRightmostLane 
* T = {noStopping, speedAdvantageForOvertaking, zipperMerge} 
* CheckSatN(BC_1): case334_premise.smt2, expect sat 
* CheckSatN(BC_2): case334_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 335 

* TSC = speedAdvantageForOvertaking 
* T = {keepInRightmostLane, noStopping, zipperMerge} 
* CheckSatN(BC_1): case335_premise.smt2, expect sat 
* CheckSatN(BC_2): case335_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 336 

* TSC = zipperMerge 
* T = {keepInRightmostLane, noStopping, speedAdvantageForOvertaking} 
* CheckSatN(BC_1): case336_premise.smt2, expect sat 
* CheckSatN(BC_2): case336_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 337 

* TSC = belowSpeedLimit 
* T = {noStopping, safeDistance, zipperMerge} 
* CheckSatN(BC_1): case337_premise.smt2, expect sat 
* CheckSatN(BC_2): case337_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 338 

* TSC = noStopping 
* T = {belowSpeedLimit, safeDistance, zipperMerge} 
* CheckSatN(BC_1): case338_premise.smt2, expect sat 
* CheckSatN(BC_2): case338_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 339 

* TSC = safeDistance 
* T = {belowSpeedLimit, noStopping, zipperMerge} 
* CheckSatN(BC_1): case339_premise.smt2, expect sat 
* CheckSatN(BC_2): case339_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 340 

* TSC = zipperMerge 
* T = {belowSpeedLimit, noStopping, safeDistance} 
* CheckSatN(BC_1): case340_premise.smt2, expect sat 
* CheckSatN(BC_2): case340_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 341 

* TSC = belowSpeedLimit 
* T = {keepInRightmostLane, safeDistance, zipperMerge} 
* CheckSatN(BC_1): case341_premise.smt2, expect sat 
* CheckSatN(BC_2): case341_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 342 

* TSC = keepInRightmostLane 
* T = {belowSpeedLimit, safeDistance, zipperMerge} 
* CheckSatN(BC_1): case342_premise.smt2, expect sat 
* CheckSatN(BC_2): case342_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 343 

* TSC = safeDistance 
* T = {belowSpeedLimit, keepInRightmostLane, zipperMerge} 
* CheckSatN(BC_1): case343_premise.smt2, expect sat 
* CheckSatN(BC_2): case343_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 344 

* TSC = zipperMerge 
* T = {belowSpeedLimit, keepInRightmostLane, safeDistance} 
* CheckSatN(BC_1): case344_premise.smt2, expect sat 
* CheckSatN(BC_2): case344_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 345 

* TSC = noStopping 
* T = {keepInRightmostLane, safeDistance, zipperMerge} 
* CheckSatN(BC_1): case345_premise.smt2, expect sat 
* CheckSatN(BC_2): case345_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 346 

* TSC = keepInRightmostLane 
* T = {noStopping, safeDistance, zipperMerge} 
* CheckSatN(BC_1): case346_premise.smt2, expect sat 
* CheckSatN(BC_2): case346_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 347 

* TSC = safeDistance 
* T = {keepInRightmostLane, noStopping, zipperMerge} 
* CheckSatN(BC_1): case347_premise.smt2, expect sat 
* CheckSatN(BC_2): case347_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 348 

* TSC = zipperMerge 
* T = {keepInRightmostLane, noStopping, safeDistance} 
* CheckSatN(BC_1): case348_premise.smt2, expect sat 
* CheckSatN(BC_2): case348_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 349 

* TSC = belowSpeedLimit 
* T = {safeDistance, speedAdvantageForOvertaking, zipperMerge} 
* CheckSatN(BC_1): case349_premise.smt2, expect sat 
* CheckSatN(BC_2): case349_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 350 

* TSC = speedAdvantageForOvertaking 
* T = {belowSpeedLimit, safeDistance, zipperMerge} 
* CheckSatN(BC_1): case350_premise.smt2, expect sat 
* CheckSatN(BC_2): case350_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 351 

* TSC = safeDistance 
* T = {belowSpeedLimit, speedAdvantageForOvertaking, zipperMerge} 
* CheckSatN(BC_1): case351_premise.smt2, expect sat 
* CheckSatN(BC_2): case351_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 352 

* TSC = zipperMerge 
* T = {belowSpeedLimit, safeDistance, speedAdvantageForOvertaking} 
* CheckSatN(BC_1): case352_premise.smt2, expect sat 
* CheckSatN(BC_2): case352_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 353 

* TSC = noStopping 
* T = {safeDistance, speedAdvantageForOvertaking, zipperMerge} 
* CheckSatN(BC_1): case353_premise.smt2, expect sat 
* CheckSatN(BC_2): case353_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 354 

* TSC = speedAdvantageForOvertaking 
* T = {noStopping, safeDistance, zipperMerge} 
* CheckSatN(BC_1): case354_premise.smt2, expect sat 
* CheckSatN(BC_2): case354_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 355 

* TSC = safeDistance 
* T = {noStopping, speedAdvantageForOvertaking, zipperMerge} 
* CheckSatN(BC_1): case355_premise.smt2, expect sat 
* CheckSatN(BC_2): case355_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 356 

* TSC = zipperMerge 
* T = {noStopping, safeDistance, speedAdvantageForOvertaking} 
* CheckSatN(BC_1): case356_premise.smt2, expect sat 
* CheckSatN(BC_2): case356_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 357 

* TSC = keepInRightmostLane 
* T = {safeDistance, speedAdvantageForOvertaking, zipperMerge} 
* CheckSatN(BC_1): case357_premise.smt2, expect sat 
* CheckSatN(BC_2): case357_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 358 

* TSC = speedAdvantageForOvertaking 
* T = {keepInRightmostLane, safeDistance, zipperMerge} 
* CheckSatN(BC_1): case358_premise.smt2, expect sat 
* CheckSatN(BC_2): case358_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 359 

* TSC = safeDistance 
* T = {keepInRightmostLane, speedAdvantageForOvertaking, zipperMerge} 
* CheckSatN(BC_1): case359_premise.smt2, expect sat 
* CheckSatN(BC_2): case359_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 360 

* TSC = zipperMerge 
* T = {keepInRightmostLane, safeDistance, speedAdvantageForOvertaking} 
* CheckSatN(BC_1): case360_premise.smt2, expect sat 
* CheckSatN(BC_2): case360_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 361 

* TSC = belowSpeedLimit 
* T = {beingOvertaken, noStopping, zipperMerge} 
* CheckSatN(BC_1): case361_premise.smt2, expect sat 
* CheckSatN(BC_2): case361_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 362 

* TSC = noStopping 
* T = {beingOvertaken, belowSpeedLimit, zipperMerge} 
* CheckSatN(BC_1): case362_premise.smt2, expect sat 
* CheckSatN(BC_2): case362_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 363 

* TSC = beingOvertaken 
* T = {belowSpeedLimit, noStopping, zipperMerge} 
* CheckSatN(BC_1): case363_premise.smt2, expect sat 
* CheckSatN(BC_2): case363_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 364 

* TSC = zipperMerge 
* T = {beingOvertaken, belowSpeedLimit, noStopping} 
* CheckSatN(BC_1): case364_premise.smt2, expect sat 
* CheckSatN(BC_2): case364_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 365 

* TSC = belowSpeedLimit 
* T = {beingOvertaken, keepInRightmostLane, zipperMerge} 
* CheckSatN(BC_1): case365_premise.smt2, expect sat 
* CheckSatN(BC_2): case365_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 366 

* TSC = keepInRightmostLane 
* T = {beingOvertaken, belowSpeedLimit, zipperMerge} 
* CheckSatN(BC_1): case366_premise.smt2, expect sat 
* CheckSatN(BC_2): case366_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 367 

* TSC = beingOvertaken 
* T = {belowSpeedLimit, keepInRightmostLane, zipperMerge} 
* CheckSatN(BC_1): case367_premise.smt2, expect sat 
* CheckSatN(BC_2): case367_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 368 

* TSC = zipperMerge 
* T = {beingOvertaken, belowSpeedLimit, keepInRightmostLane} 
* CheckSatN(BC_1): case368_premise.smt2, expect sat 
* CheckSatN(BC_2): case368_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 369 

* TSC = noStopping 
* T = {beingOvertaken, keepInRightmostLane, zipperMerge} 
* CheckSatN(BC_1): case369_premise.smt2, expect sat 
* CheckSatN(BC_2): case369_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 370 

* TSC = keepInRightmostLane 
* T = {beingOvertaken, noStopping, zipperMerge} 
* CheckSatN(BC_1): case370_premise.smt2, expect sat 
* CheckSatN(BC_2): case370_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 371 

* TSC = beingOvertaken 
* T = {keepInRightmostLane, noStopping, zipperMerge} 
* CheckSatN(BC_1): case371_premise.smt2, expect sat 
* CheckSatN(BC_2): case371_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 372 

* TSC = zipperMerge 
* T = {beingOvertaken, keepInRightmostLane, noStopping} 
* CheckSatN(BC_1): case372_premise.smt2, expect sat 
* CheckSatN(BC_2): case372_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 373 

* TSC = belowSpeedLimit 
* T = {beingOvertaken, safeDistance, zipperMerge} 
* CheckSatN(BC_1): case373_premise.smt2, expect sat 
* CheckSatN(BC_2): case373_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 374 

* TSC = safeDistance 
* T = {beingOvertaken, belowSpeedLimit, zipperMerge} 
* CheckSatN(BC_1): case374_premise.smt2, expect sat 
* CheckSatN(BC_2): case374_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 375 

* TSC = beingOvertaken 
* T = {belowSpeedLimit, safeDistance, zipperMerge} 
* CheckSatN(BC_1): case375_premise.smt2, expect sat 
* CheckSatN(BC_2): case375_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 376 

* TSC = zipperMerge 
* T = {beingOvertaken, belowSpeedLimit, safeDistance} 
* CheckSatN(BC_1): case376_premise.smt2, expect sat 
* CheckSatN(BC_2): case376_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 377 

* TSC = noStopping 
* T = {beingOvertaken, safeDistance, zipperMerge} 
* CheckSatN(BC_1): case377_premise.smt2, expect sat 
* CheckSatN(BC_2): case377_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 378 

* TSC = safeDistance 
* T = {beingOvertaken, noStopping, zipperMerge} 
* CheckSatN(BC_1): case378_premise.smt2, expect sat 
* CheckSatN(BC_2): case378_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 379 

* TSC = beingOvertaken 
* T = {noStopping, safeDistance, zipperMerge} 
* CheckSatN(BC_1): case379_premise.smt2, expect sat 
* CheckSatN(BC_2): case379_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 380 

* TSC = zipperMerge 
* T = {beingOvertaken, noStopping, safeDistance} 
* CheckSatN(BC_1): case380_premise.smt2, expect sat 
* CheckSatN(BC_2): case380_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 381 

* TSC = keepInRightmostLane 
* T = {beingOvertaken, safeDistance, zipperMerge} 
* CheckSatN(BC_1): case381_premise.smt2, expect sat 
* CheckSatN(BC_2): case381_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 382 

* TSC = safeDistance 
* T = {beingOvertaken, keepInRightmostLane, zipperMerge} 
* CheckSatN(BC_1): case382_premise.smt2, expect sat 
* CheckSatN(BC_2): case382_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 383 

* TSC = beingOvertaken 
* T = {keepInRightmostLane, safeDistance, zipperMerge} 
* CheckSatN(BC_1): case383_premise.smt2, expect sat 
* CheckSatN(BC_2): case383_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 384 

* TSC = zipperMerge 
* T = {beingOvertaken, keepInRightmostLane, safeDistance} 
* CheckSatN(BC_1): case384_premise.smt2, expect sat 
* CheckSatN(BC_2): case384_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 385 

* TSC = belowSpeedLimit 
* T = {keepInRightmostLane, noStopping, safeDistance, speedAdvantageForOvertaking} 
* CheckSatN(BC_1): case385_premise.smt2, expect sat 
* CheckSatN(BC_2): case385_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 386 

* TSC = noStopping 
* T = {belowSpeedLimit, keepInRightmostLane, safeDistance, speedAdvantageForOvertaking} 
* CheckSatN(BC_1): case386_premise.smt2, expect sat 
* CheckSatN(BC_2): case386_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 387 

* TSC = keepInRightmostLane 
* T = {belowSpeedLimit, noStopping, safeDistance, speedAdvantageForOvertaking} 
* CheckSatN(BC_1): case387_premise.smt2, expect sat 
* CheckSatN(BC_2): case387_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 388 

* TSC = speedAdvantageForOvertaking 
* T = {belowSpeedLimit, keepInRightmostLane, noStopping, safeDistance} 
* CheckSatN(BC_1): case388_premise.smt2, expect sat 
* CheckSatN(BC_2): case388_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 389 

* TSC = safeDistance 
* T = {belowSpeedLimit, keepInRightmostLane, noStopping, speedAdvantageForOvertaking} 
* CheckSatN(BC_1): case389_premise.smt2, expect sat 
* CheckSatN(BC_2): case389_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 390 

* TSC = belowSpeedLimit 
* T = {noStopping, safeDistance, safeLaneChange, speedAdvantageForOvertaking} 
* CheckSatN(BC_1): case390_premise.smt2, expect sat 
* CheckSatN(BC_2): case390_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 391 

* TSC = noStopping 
* T = {belowSpeedLimit, safeDistance, safeLaneChange, speedAdvantageForOvertaking} 
* CheckSatN(BC_1): case391_premise.smt2, expect sat 
* CheckSatN(BC_2): case391_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 392 

* TSC = safeLaneChange 
* T = {belowSpeedLimit, noStopping, safeDistance, speedAdvantageForOvertaking} 
* CheckSatN(BC_1): case392_premise.smt2, expect sat 
* CheckSatN(BC_2): case392_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 393 

* TSC = speedAdvantageForOvertaking 
* T = {belowSpeedLimit, noStopping, safeDistance, safeLaneChange} 
* CheckSatN(BC_1): case393_premise.smt2, expect sat 
* CheckSatN(BC_2): case393_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 394 

* TSC = safeDistance 
* T = {belowSpeedLimit, noStopping, safeLaneChange, speedAdvantageForOvertaking} 
* CheckSatN(BC_1): case394_premise.smt2, expect sat 
* CheckSatN(BC_2): case394_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 395 

* TSC = belowSpeedLimit 
* T = {beingOvertaken, keepInRightmostLane, noStopping, safeDistance} 
* CheckSatN(BC_1): case395_premise.smt2, expect sat 
* CheckSatN(BC_2): case395_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 396 

* TSC = noStopping 
* T = {beingOvertaken, belowSpeedLimit, keepInRightmostLane, safeDistance} 
* CheckSatN(BC_1): case396_premise.smt2, expect sat 
* CheckSatN(BC_2): case396_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 397 

* TSC = keepInRightmostLane 
* T = {beingOvertaken, belowSpeedLimit, noStopping, safeDistance} 
* CheckSatN(BC_1): case397_premise.smt2, expect sat 
* CheckSatN(BC_2): case397_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 398 

* TSC = safeDistance 
* T = {beingOvertaken, belowSpeedLimit, keepInRightmostLane, noStopping} 
* CheckSatN(BC_1): case398_premise.smt2, expect sat 
* CheckSatN(BC_2): case398_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 399 

* TSC = beingOvertaken 
* T = {belowSpeedLimit, keepInRightmostLane, noStopping, safeDistance} 
* CheckSatN(BC_1): case399_premise.smt2, expect sat 
* CheckSatN(BC_2): case399_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 400 

* TSC = belowSpeedLimit 
* T = {beingOvertaken, noPassingOnTheRightSide, noStopping, safeDistance} 
* CheckSatN(BC_1): case400_premise.smt2, expect sat 
* CheckSatN(BC_2): case400_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 401 

* TSC = noStopping 
* T = {beingOvertaken, belowSpeedLimit, noPassingOnTheRightSide, safeDistance} 
* CheckSatN(BC_1): case401_premise.smt2, expect sat 
* CheckSatN(BC_2): case401_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 402 

* TSC = noPassingOnTheRightSide 
* T = {beingOvertaken, belowSpeedLimit, noStopping, safeDistance} 
* CheckSatN(BC_1): case402_premise.smt2, expect sat 
* CheckSatN(BC_2): case402_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 403 

* TSC = safeDistance 
* T = {beingOvertaken, belowSpeedLimit, noPassingOnTheRightSide, noStopping} 
* CheckSatN(BC_1): case403_premise.smt2, expect sat 
* CheckSatN(BC_2): case403_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 404 

* TSC = beingOvertaken 
* T = {belowSpeedLimit, noPassingOnTheRightSide, noStopping, safeDistance} 
* CheckSatN(BC_1): case404_premise.smt2, expect sat 
* CheckSatN(BC_2): case404_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 405 

* TSC = belowSpeedLimit 
* T = {beingOvertaken, noStopping, safeDistance, safeLaneChange} 
* CheckSatN(BC_1): case405_premise.smt2, expect sat 
* CheckSatN(BC_2): case405_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 406 

* TSC = noStopping 
* T = {beingOvertaken, belowSpeedLimit, safeDistance, safeLaneChange} 
* CheckSatN(BC_1): case406_premise.smt2, expect sat 
* CheckSatN(BC_2): case406_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 407 

* TSC = safeLaneChange 
* T = {beingOvertaken, belowSpeedLimit, noStopping, safeDistance} 
* CheckSatN(BC_1): case407_premise.smt2, expect sat 
* CheckSatN(BC_2): case407_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 408 

* TSC = safeDistance 
* T = {beingOvertaken, belowSpeedLimit, noStopping, safeLaneChange} 
* CheckSatN(BC_1): case408_premise.smt2, expect sat 
* CheckSatN(BC_2): case408_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 409 

* TSC = beingOvertaken 
* T = {belowSpeedLimit, noStopping, safeDistance, safeLaneChange} 
* CheckSatN(BC_1): case409_premise.smt2, expect sat 
* CheckSatN(BC_2): case409_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 410 

* TSC = belowSpeedLimit 
* T = {keepInRightmostLane, noStopping, speedAdvantageForOvertaking, zipperMerge} 
* CheckSatN(BC_1): case410_premise.smt2, expect sat 
* CheckSatN(BC_2): case410_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 411 

* TSC = noStopping 
* T = {belowSpeedLimit, keepInRightmostLane, speedAdvantageForOvertaking, zipperMerge} 
* CheckSatN(BC_1): case411_premise.smt2, expect sat 
* CheckSatN(BC_2): case411_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 412 

* TSC = keepInRightmostLane 
* T = {belowSpeedLimit, noStopping, speedAdvantageForOvertaking, zipperMerge} 
* CheckSatN(BC_1): case412_premise.smt2, expect sat 
* CheckSatN(BC_2): case412_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 413 

* TSC = speedAdvantageForOvertaking 
* T = {belowSpeedLimit, keepInRightmostLane, noStopping, zipperMerge} 
* CheckSatN(BC_1): case413_premise.smt2, expect sat 
* CheckSatN(BC_2): case413_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 414 

* TSC = zipperMerge 
* T = {belowSpeedLimit, keepInRightmostLane, noStopping, speedAdvantageForOvertaking} 
* CheckSatN(BC_1): case414_premise.smt2, expect sat 
* CheckSatN(BC_2): case414_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 415 

* TSC = belowSpeedLimit 
* T = {keepInRightmostLane, noStopping, safeDistance, zipperMerge} 
* CheckSatN(BC_1): case415_premise.smt2, expect sat 
* CheckSatN(BC_2): case415_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 416 

* TSC = noStopping 
* T = {belowSpeedLimit, keepInRightmostLane, safeDistance, zipperMerge} 
* CheckSatN(BC_1): case416_premise.smt2, expect sat 
* CheckSatN(BC_2): case416_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 417 

* TSC = keepInRightmostLane 
* T = {belowSpeedLimit, noStopping, safeDistance, zipperMerge} 
* CheckSatN(BC_1): case417_premise.smt2, expect sat 
* CheckSatN(BC_2): case417_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 418 

* TSC = safeDistance 
* T = {belowSpeedLimit, keepInRightmostLane, noStopping, zipperMerge} 
* CheckSatN(BC_1): case418_premise.smt2, expect sat 
* CheckSatN(BC_2): case418_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 419 

* TSC = zipperMerge 
* T = {belowSpeedLimit, keepInRightmostLane, noStopping, safeDistance} 
* CheckSatN(BC_1): case419_premise.smt2, expect sat 
* CheckSatN(BC_2): case419_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 420 

* TSC = belowSpeedLimit 
* T = {noStopping, safeDistance, speedAdvantageForOvertaking, zipperMerge} 
* CheckSatN(BC_1): case420_premise.smt2, expect sat 
* CheckSatN(BC_2): case420_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 421 

* TSC = noStopping 
* T = {belowSpeedLimit, safeDistance, speedAdvantageForOvertaking, zipperMerge} 
* CheckSatN(BC_1): case421_premise.smt2, expect sat 
* CheckSatN(BC_2): case421_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 422 

* TSC = speedAdvantageForOvertaking 
* T = {belowSpeedLimit, noStopping, safeDistance, zipperMerge} 
* CheckSatN(BC_1): case422_premise.smt2, expect sat 
* CheckSatN(BC_2): case422_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 423 

* TSC = safeDistance 
* T = {belowSpeedLimit, noStopping, speedAdvantageForOvertaking, zipperMerge} 
* CheckSatN(BC_1): case423_premise.smt2, expect sat 
* CheckSatN(BC_2): case423_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 424 

* TSC = zipperMerge 
* T = {belowSpeedLimit, noStopping, safeDistance, speedAdvantageForOvertaking} 
* CheckSatN(BC_1): case424_premise.smt2, expect sat 
* CheckSatN(BC_2): case424_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 425 

* TSC = belowSpeedLimit 
* T = {keepInRightmostLane, safeDistance, speedAdvantageForOvertaking, zipperMerge} 
* CheckSatN(BC_1): case425_premise.smt2, expect sat 
* CheckSatN(BC_2): case425_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 426 

* TSC = keepInRightmostLane 
* T = {belowSpeedLimit, safeDistance, speedAdvantageForOvertaking, zipperMerge} 
* CheckSatN(BC_1): case426_premise.smt2, expect sat 
* CheckSatN(BC_2): case426_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 427 

* TSC = speedAdvantageForOvertaking 
* T = {belowSpeedLimit, keepInRightmostLane, safeDistance, zipperMerge} 
* CheckSatN(BC_1): case427_premise.smt2, expect sat 
* CheckSatN(BC_2): case427_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 428 

* TSC = safeDistance 
* T = {belowSpeedLimit, keepInRightmostLane, speedAdvantageForOvertaking, zipperMerge} 
* CheckSatN(BC_1): case428_premise.smt2, expect sat 
* CheckSatN(BC_2): case428_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 429 

* TSC = zipperMerge 
* T = {belowSpeedLimit, keepInRightmostLane, safeDistance, speedAdvantageForOvertaking} 
* CheckSatN(BC_1): case429_premise.smt2, expect sat 
* CheckSatN(BC_2): case429_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 430 

* TSC = noStopping 
* T = {keepInRightmostLane, safeDistance, speedAdvantageForOvertaking, zipperMerge} 
* CheckSatN(BC_1): case430_premise.smt2, expect sat 
* CheckSatN(BC_2): case430_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 431 

* TSC = keepInRightmostLane 
* T = {noStopping, safeDistance, speedAdvantageForOvertaking, zipperMerge} 
* CheckSatN(BC_1): case431_premise.smt2, expect sat 
* CheckSatN(BC_2): case431_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 432 

* TSC = speedAdvantageForOvertaking 
* T = {keepInRightmostLane, noStopping, safeDistance, zipperMerge} 
* CheckSatN(BC_1): case432_premise.smt2, expect sat 
* CheckSatN(BC_2): case432_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 433 

* TSC = safeDistance 
* T = {keepInRightmostLane, noStopping, speedAdvantageForOvertaking, zipperMerge} 
* CheckSatN(BC_1): case433_premise.smt2, expect sat 
* CheckSatN(BC_2): case433_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 434 

* TSC = zipperMerge 
* T = {keepInRightmostLane, noStopping, safeDistance, speedAdvantageForOvertaking} 
* CheckSatN(BC_1): case434_premise.smt2, expect sat 
* CheckSatN(BC_2): case434_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 435 

* TSC = belowSpeedLimit 
* T = {beingOvertaken, keepInRightmostLane, noStopping, zipperMerge} 
* CheckSatN(BC_1): case435_premise.smt2, expect sat 
* CheckSatN(BC_2): case435_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 436 

* TSC = noStopping 
* T = {beingOvertaken, belowSpeedLimit, keepInRightmostLane, zipperMerge} 
* CheckSatN(BC_1): case436_premise.smt2, expect sat 
* CheckSatN(BC_2): case436_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 437 

* TSC = keepInRightmostLane 
* T = {beingOvertaken, belowSpeedLimit, noStopping, zipperMerge} 
* CheckSatN(BC_1): case437_premise.smt2, expect sat 
* CheckSatN(BC_2): case437_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 438 

* TSC = beingOvertaken 
* T = {belowSpeedLimit, keepInRightmostLane, noStopping, zipperMerge} 
* CheckSatN(BC_1): case438_premise.smt2, expect sat 
* CheckSatN(BC_2): case438_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 439 

* TSC = zipperMerge 
* T = {beingOvertaken, belowSpeedLimit, keepInRightmostLane, noStopping} 
* CheckSatN(BC_1): case439_premise.smt2, expect sat 
* CheckSatN(BC_2): case439_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 440 

* TSC = belowSpeedLimit 
* T = {beingOvertaken, noStopping, safeDistance, zipperMerge} 
* CheckSatN(BC_1): case440_premise.smt2, expect sat 
* CheckSatN(BC_2): case440_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 441 

* TSC = noStopping 
* T = {beingOvertaken, belowSpeedLimit, safeDistance, zipperMerge} 
* CheckSatN(BC_1): case441_premise.smt2, expect sat 
* CheckSatN(BC_2): case441_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 442 

* TSC = safeDistance 
* T = {beingOvertaken, belowSpeedLimit, noStopping, zipperMerge} 
* CheckSatN(BC_1): case442_premise.smt2, expect sat 
* CheckSatN(BC_2): case442_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 443 

* TSC = beingOvertaken 
* T = {belowSpeedLimit, noStopping, safeDistance, zipperMerge} 
* CheckSatN(BC_1): case443_premise.smt2, expect sat 
* CheckSatN(BC_2): case443_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 444 

* TSC = zipperMerge 
* T = {beingOvertaken, belowSpeedLimit, noStopping, safeDistance} 
* CheckSatN(BC_1): case444_premise.smt2, expect sat 
* CheckSatN(BC_2): case444_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 445 

* TSC = belowSpeedLimit 
* T = {beingOvertaken, keepInRightmostLane, safeDistance, zipperMerge} 
* CheckSatN(BC_1): case445_premise.smt2, expect sat 
* CheckSatN(BC_2): case445_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 446 

* TSC = keepInRightmostLane 
* T = {beingOvertaken, belowSpeedLimit, safeDistance, zipperMerge} 
* CheckSatN(BC_1): case446_premise.smt2, expect sat 
* CheckSatN(BC_2): case446_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 447 

* TSC = safeDistance 
* T = {beingOvertaken, belowSpeedLimit, keepInRightmostLane, zipperMerge} 
* CheckSatN(BC_1): case447_premise.smt2, expect sat 
* CheckSatN(BC_2): case447_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 448 

* TSC = beingOvertaken 
* T = {belowSpeedLimit, keepInRightmostLane, safeDistance, zipperMerge} 
* CheckSatN(BC_1): case448_premise.smt2, expect sat 
* CheckSatN(BC_2): case448_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 449 

* TSC = zipperMerge 
* T = {beingOvertaken, belowSpeedLimit, keepInRightmostLane, safeDistance} 
* CheckSatN(BC_1): case449_premise.smt2, expect sat 
* CheckSatN(BC_2): case449_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 450 

* TSC = noStopping 
* T = {beingOvertaken, keepInRightmostLane, safeDistance, zipperMerge} 
* CheckSatN(BC_1): case450_premise.smt2, expect sat 
* CheckSatN(BC_2): case450_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 451 

* TSC = keepInRightmostLane 
* T = {beingOvertaken, noStopping, safeDistance, zipperMerge} 
* CheckSatN(BC_1): case451_premise.smt2, expect sat 
* CheckSatN(BC_2): case451_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 452 

* TSC = safeDistance 
* T = {beingOvertaken, keepInRightmostLane, noStopping, zipperMerge} 
* CheckSatN(BC_1): case452_premise.smt2, expect sat 
* CheckSatN(BC_2): case452_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 453 

* TSC = beingOvertaken 
* T = {keepInRightmostLane, noStopping, safeDistance, zipperMerge} 
* CheckSatN(BC_1): case453_premise.smt2, expect sat 
* CheckSatN(BC_2): case453_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 454 

* TSC = zipperMerge 
* T = {beingOvertaken, keepInRightmostLane, noStopping, safeDistance} 
* CheckSatN(BC_1): case454_premise.smt2, expect sat 
* CheckSatN(BC_2): case454_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 455 

* TSC = belowSpeedLimit 
* T = {keepInRightmostLane, noStopping, safeDistance, speedAdvantageForOvertaking, zipperMerge} 
* CheckSatN(BC_1): case455_premise.smt2, expect sat 
* CheckSatN(BC_2): case455_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 456 

* TSC = noStopping 
* T = {belowSpeedLimit, keepInRightmostLane, safeDistance, speedAdvantageForOvertaking, zipperMerge} 
* CheckSatN(BC_1): case456_premise.smt2, expect sat 
* CheckSatN(BC_2): case456_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 457 

* TSC = keepInRightmostLane 
* T = {belowSpeedLimit, noStopping, safeDistance, speedAdvantageForOvertaking, zipperMerge} 
* CheckSatN(BC_1): case457_premise.smt2, expect sat 
* CheckSatN(BC_2): case457_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 458 

* TSC = speedAdvantageForOvertaking 
* T = {belowSpeedLimit, keepInRightmostLane, noStopping, safeDistance, zipperMerge} 
* CheckSatN(BC_1): case458_premise.smt2, expect sat 
* CheckSatN(BC_2): case458_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 459 

* TSC = safeDistance 
* T = {belowSpeedLimit, keepInRightmostLane, noStopping, speedAdvantageForOvertaking, zipperMerge} 
* CheckSatN(BC_1): case459_premise.smt2, expect sat 
* CheckSatN(BC_2): case459_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 460 

* TSC = zipperMerge 
* T = {belowSpeedLimit, keepInRightmostLane, noStopping, safeDistance, speedAdvantageForOvertaking} 
* CheckSatN(BC_1): case460_premise.smt2, expect sat 
* CheckSatN(BC_2): case460_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 461 

* TSC = belowSpeedLimit 
* T = {beingOvertaken, keepInRightmostLane, noStopping, safeDistance, zipperMerge} 
* CheckSatN(BC_1): case461_premise.smt2, expect sat 
* CheckSatN(BC_2): case461_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 462 

* TSC = noStopping 
* T = {beingOvertaken, belowSpeedLimit, keepInRightmostLane, safeDistance, zipperMerge} 
* CheckSatN(BC_1): case462_premise.smt2, expect sat 
* CheckSatN(BC_2): case462_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 463 

* TSC = keepInRightmostLane 
* T = {beingOvertaken, belowSpeedLimit, noStopping, safeDistance, zipperMerge} 
* CheckSatN(BC_1): case463_premise.smt2, expect sat 
* CheckSatN(BC_2): case463_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 464 

* TSC = safeDistance 
* T = {beingOvertaken, belowSpeedLimit, keepInRightmostLane, noStopping, zipperMerge} 
* CheckSatN(BC_1): case464_premise.smt2, expect sat 
* CheckSatN(BC_2): case464_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 465 

* TSC = beingOvertaken 
* T = {belowSpeedLimit, keepInRightmostLane, noStopping, safeDistance, zipperMerge} 
* CheckSatN(BC_1): case465_premise.smt2, expect sat 
* CheckSatN(BC_2): case465_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

## Case 466 

* TSC = zipperMerge 
* T = {beingOvertaken, belowSpeedLimit, keepInRightmostLane, noStopping, safeDistance} 
* CheckSatN(BC_1): case466_premise.smt2, expect sat 
* CheckSatN(BC_2): case466_consequence.smt2, expect sat 
* CheckSatS(BC_1): skipped 

