**NAME:** AmesHousing
**SIZE:** 2930 observations, 82 variables
**DESCRIPTION / DESCRIPTIVE ABSTRACT:** Data set contains information from the Ames Assessor’s Office used in computing assessed values for individual residential properties sold in Ames, IA from 2006 to 2010. See below for detailed variable descriptions.
**SOURCES:**
*   Ames, Iowa Assessor’s Office
*   De Cock, Dean. "Ames, Iowa: Alternative to the Boston housing data as an end of semester regression project." Journal of Statistics Education 19.3 (2011).

---

**VARIABLE DESCRIPTIONS:**

1.  **Order** (Discrete): Observation number.

2.  **PID** (Nominal): Parcel identification number - can be used with city web site for parcel review.

3.  **area** (Continuous): Above grade (ground) living area square feet. 

4.  **price** (Continuous): Sale price in USD. 

5.  **MS.SubClass** (Nominal): Identifies the type of dwelling involved in the sale.
    *   `020`: 1-STORY 1946 & NEWER ALL STYLES
    *   `030`: 1-STORY 1945 & OLDER
    *   `040`: 1-STORY W/FINISHED ATTIC ALL AGES
    *   `045`: 1-1/2 STORY - UNFINISHED ALL AGES
    *   `050`: 1-1/2 STORY FINISHED ALL AGES
    *   `060`: 2-STORY 1946 & NEWER
    *   `070`: 2-STORY 1945 & OLDER
    *   `075`: 2-1/2 STORY ALL AGES
    *   `080`: SPLIT OR MULTI-LEVEL
    *   `085`: SPLIT FOYER
    *   `090`: DUPLEX - ALL STYLES AND AGES
    *   `120`: 1-STORY PUD (Planned Unit Development) - 1946 & NEWER
    *   `150`: 1-1/2 STORY PUD - ALL AGES
    *   `160`: 2-STORY PUD - 1946 & NEWER
    *   `180`: PUD - MULTILEVEL - INCL SPLIT LEV/FOYER
    *   `190`: 2 FAMILY CONVERSION - ALL STYLES AND AGES

6.  **MS.Zoning** (Nominal): Identifies the general zoning classification of the sale.
    *   `A`: Agriculture
    *   `C`: Commercial
    *   `FV`: Floating Village Residential
    *   `I`: Industrial
    *   `RH`: Residential High Density
    *   `RL`: Residential Low Density
    *   `RP`: Residential Low Density Park
    *   `RM`: Residential Medium Density

7.  **Lot.Frontage** (Continuous): Linear feet of street connected to property.

8.  **Lot.Area** (Continuous): Lot size in square feet.

9.  **Street** (Nominal): Type of road access to property.
    *   `Grvl`: Gravel
    *   `Pave`: Paved

10. **Alley** (Nominal): Type of alley access to property.
    *   `Grvl`: Gravel
    *   `Pave`: Paved
    *   `NA`: No alley access

11. **Lot.Shape** (Ordinal): General shape of property.
    *   `Reg`: Regular
    *   `IR1`: Slightly irregular
    *   `IR2`: Moderately Irregular
    *   `IR3`: Irregular

12. **Land.Contour** (Nominal): Flatness of the property.
    *   `Lvl`: Near Flat/Level
    *   `Bnk`: Banked - Quick and significant rise from street grade to building
    *   `HLS`: Hillside - Significant slope from side to side
    *   `Low`: Depression

13. **Utilities** (Ordinal): Type of utilities available.
    *   `AllPub`: All public Utilities (E,G,W,& S)
    *   `NoSewr`: Electricity, Gas, and Water (Septic Tank)
    *   `NoSeWa`: Electricity and Gas Only
    *   `ELO`: Electricity only

14. **Lot.Config** (Nominal): Lot configuration.
    *   `Inside`: Inside lot
    *   `Corner`: Corner lot
    *   `CulDSac`: Cul-de-sac
    *   `FR2`: Frontage on 2 sides of property
    *   `FR3`: Frontage on 3 sides of property

15. **Land.Slope** (Ordinal): Slope of property.
    *   `Gtl`: Gentle slope
    *   `Mod`: Moderate Slope
    *   `Sev`: Severe Slope

16. **Neighborhood** (Nominal): Physical locations within Ames city limits (map available).
    *   `Blmngtn`: Bloomington Heights
    *   `Blueste`: Bluestem
    *   `BrDale`: Briardale
    *   `BrkSide`: Brookside
    *   `ClearCr`: Clear Creek
    *   `CollgCr`: College Creek
    *   `Crawfor`: Crawford
    *   `Edwards`: Edwards
    *   `Gilbert`: Gilbert
    *   `Greens`: Greens
    *   `GrnHill`: Green Hills
    *   `IDOTRR`: Iowa DOT and Rail Road
    *   `Landmrk`: Landmark
    *   `MeadowV`: Meadow Village
    *   `Mitchel`: Mitchell
    *   `Names`: North Ames
    *   `NoRidge`: Northridge
    *   `NPkVill`: Northpark Villa
    *   `NridgHt`: Northridge Heights
    *   `NWAmes`: Northwest Ames
    *   `OldTown`: Old Town
    *   `SWISU`: South & West of Iowa State University
    *   `Sawyer`: Sawyer
    *   `SawyerW`: Sawyer West
    *   `Somerst`: Somerset
    *   `StoneBr`: Stone Brook
    *   `Timber`: Timberland
    *   `Veenker`: Veenker

17. **Condition.1** (Nominal): Proximity to various conditions.
    *   `Artery`: Adjacent to arterial street
    *   `Feedr`: Adjacent to feeder street
    *   `Norm`: Normal
    *   `RRNn`: Within 200' of North-South Railroad
    *   `RRAn`: Adjacent to North-South Railroad
    *   `PosN`: Near positive off-site feature--park, greenbelt, etc.
    *   `PosA`: Adjacent to postive off-site feature
    *   `RRNe`: Within 200' of East-West Railroad
    *   `RRAe`: Adjacent to East-West Railroad

18. **Condition.2** (Nominal): Proximity to various conditions (if more than one is present).
    *   `Artery`: Adjacent to arterial street
    *   `Feedr`: Adjacent to feeder street
    *   `Norm`: Normal
    *   `RRNn`: Within 200' of North-South Railroad
    *   `RRAn`: Adjacent to North-South Railroad
    *   `PosN`: Near positive off-site feature--park, greenbelt, etc.
    *   `PosA`: Adjacent to postive off-site feature
    *   `RRNe`: Within 200' of East-West Railroad
    *   `RRAe`: Adjacent to East-West Railroad

19. **Bldg.Type** (Nominal): Type of dwelling.
    *   `1Fam`: Single-family Detached
    *   `2FmCon`: Two-family Conversion; originally built as one-family dwelling
    *   `Duplx`: Duplex
    *   `TwnhsE`: Townhouse End Unit
    *   `TwnhsI`: Townhouse Inside Unit

20. **House.Style** (Nominal): Style of dwelling.
    *   `1Story`: One story
    *   `1.5Fin`: One and one-half story: 2nd level finished
    *   `1.5Unf`: One and one-half story: 2nd level unfinished
    *   `2Story`: Two story
    *   `2.5Fin`: Two and one-half story: 2nd level finished
    *   `2.5Unf`: Two and one-half story: 2nd level unfinished
    *   `SFoyer`: Split Foyer
    *   `SLvl`: Split Level

21. **Overall.Qual** (Ordinal): Rates the overall material and finish of the house.
    *   `10`: Very Excellent
    *   `9`: Excellent
    *   `8`: Very Good
    *   `7`: Good
    *   `6`: Above Average
    *   `5`: Average
    *   `4`: Below Average
    *   `3`: Fair
    *   `2`: Poor
    *   `1`: Very Poor

22. **Overall.Cond** (Ordinal): Rates the overall condition of the house.
    *   `10`: Very Excellent
    *   `9`: Excellent
    *   `8`: Very Good
    *   `7`: Good
    *   `6`: Above Average
    *   `5`: Average
    *   `4`: Below Average
    *   `3`: Fair
    *   `2`: Poor
    *   `1`: Very Poor

23. **Year.Built** (Discrete): Original construction date.

24. **Year.Remod.Add** (Discrete): Remodel date (same as construction date if no remodeling or additions).

25. **Roof.Style** (Nominal): Type of roof.
    *   `Flat`: Flat
    *   `Gable`: Gable
    *   `Gambrel`: Gabrel (Barn)
    *   `Hip`: Hip
    *   `Mansard`: Mansard
    *   `Shed`: Shed

26. **Roof.Matl** (Nominal): Roof material.
    *   `ClyTile`: Clay or Tile
    *   `CompShg`: Standard (Composite) Shingle
    *   `Membran`: Membrane
    *   `Metal`: Metal
    *   `Roll`: Roll
    *   `Tar&Grv`: Gravel & Tar
    *   `WdShake`: Wood Shakes
    *   `WdShngl`: Wood Shingles

27. **Exterior.1st** (Nominal): Exterior covering on house.
    *   `AsbShng`: Asbestos Shingles
    *   `AsphShn`: Asphalt Shingles
    *   `BrkComm`: Brick Common
    *   `BrkFace`: Brick Face
    *   `CBlock`: Cinder Block
    *   `CemntBd`: Cement Board
    *   `HdBoard`: Hard Board
    *   `ImStucc`: Imitation Stucco
    *   `MetalSd`: Metal Siding
    *   `Other`: Other
    *   `Plywood`: Plywood
    *   `PreCast`: PreCast
    *   `Stone`: Stone
    *   `Stucco`: Stucco
    *   `VinylSd`: Vinyl Siding
    *   `Wd Sdng`: Wood Siding
    *   `WdShing`: Wood Shingles

28. **Exterior.2nd** (Nominal): Exterior covering on house (if more than one material).
    *   `AsbShng`: Asbestos Shingles
    *   `AsphShn`: Asphalt Shingles
    *   `BrkComm`: Brick Common
    *   `BrkFace`: Brick Face
    *   `CBlock`: Cinder Block
    *   `CemntBd`: Cement Board
    *   `HdBoard`: Hard Board
    *   `ImStucc`: Imitation Stucco
    *   `MetalSd`: Metal Siding
    *   `Other`: Other
    *   `Plywood`: Plywood
    *   `PreCast`: PreCast
    *   `Stone`: Stone
    *   `Stucco`: Stucco
    *   `VinylSd`: Vinyl Siding
    *   `Wd Sdng`: Wood Siding
    *   `WdShing`: Wood Shingles

29. **Mas.Vnr.Type** (Nominal): Masonry veneer type.
    *   `BrkCmn`: Brick Common
    *   `BrkFace`: Brick Face
    *   `CBlock`: Cinder Block
    *   `None`: None
    *   `Stone`: Stone

30. **Mas.Vnr.Area** (Continuous): Masonry veneer area in square feet.

31. **Exter.Qual** (Ordinal): Evaluates the quality of the material on the exterior.
    *   `Ex`: Excellent
    *   `Gd`: Good
    *   `TA`: Average/Typical
    *   `Fa`: Fair
    *   `Po`: Poor

32. **Exter.Cond** (Ordinal): Evaluates the present condition of the material on the exterior.
    *   `Ex`: Excellent
    *   `Gd`: Good
    *   `TA`: Average/Typical
    *   `Fa`: Fair
    *   `Po`: Poor

33. **Foundation** (Nominal): Type of foundation.
    *   `BrkTil`: Brick & Tile
    *   `CBlock`: Cinder Block
    *   `PConc`: Poured Contrete
    *   `Slab`: Slab
    *   `Stone`: Stone
    *   `Wood`: Wood

34. **Bsmt.Qual** (Ordinal): Evaluates the height of the basement.
    *   `Ex`: Excellent (100+ inches)
    *   `Gd`: Good (90-99 inches)
    *   `TA`: Typical (80-89 inches)
    *   `Fa`: Fair (70-79 inches)
    *   `Po`: Poor (<70 inches)
    *   `NA`: No Basement

35. **Bsmt.Cond** (Ordinal): Evaluates the general condition of the basement.
    *   `Ex`: Excellent
    *   `Gd`: Good
    *   `TA`: Typical - slight dampness allowed
    *   `Fa`: Fair - dampness or some cracking or settling
    *   `Po`: Poor - Severe cracking, settling, or wetness
    *   `NA`: No Basement

36. **Bsmt.Exposure** (Ordinal): Refers to walkout or garden level walls.
    *   `Gd`: Good Exposure
    *   `Av`: Average Exposure (split levels or foyers typically score average or above)
    *   `Mn`: Mimimum Exposure
    *   `No`: No Exposure
    *   `NA`: No Basement

37. **BsmtFin.Type.1** (Ordinal): Rating of basement finished area.
    *   `GLQ`: Good Living Quarters
    *   `ALQ`: Average Living Quarters
    *   `BLQ`: Below Average Living Quarters
    *   `Rec`: Average Rec Room
    *   `LwQ`: Low Quality
    *   `Unf`: Unfinshed
    *   `NA`: No Basement

38. **BsmtFin.SF.1** (Continuous): Type 1 finished square feet.

39. **BsmtFin.Type.2** (Ordinal): Rating of basement finished area (if multiple types).
    *   `GLQ`: Good Living Quarters
    *   `ALQ`: Average Living Quarters
    *   `BLQ`: Below Average Living Quarters
    *   `Rec`: Average Rec Room
    *   `LwQ`: Low Quality
    *   `Unf`: Unfinshed
    *   `NA`: No Basement

40. **BsmtFin.SF.2** (Continuous): Type 2 finished square feet.

41. **Bsmt.Unf.SF** (Continuous): Unfinished square feet of basement area.

42. **Total.Bsmt.SF** (Continuous): Total square feet of basement area.

43. **Heating** (Nominal): Type of heating.
    *   `Floor`: Floor Furnace
    *   `GasA`: Gas forced warm air furnace
    *   `GasW`: Gas hot water or steam heat
    *   `Grav`: Gravity furnace
    *   `OthW`: Hot water or steam heat other than gas
    *   `Wall`: Wall furnace

44. **Heating.QC** (Ordinal): Heating quality and condition.
    *   `Ex`: Excellent
    *   `Gd`: Good
    *   `TA`: Average/Typical
    *   `Fa`: Fair
    *   `Po`: Poor

45. **Central.Air** (Nominal): Central air conditioning.
    *   `N`: No
    *   `Y`: Yes

46. **Electrical** (Ordinal): Electrical system.
    *   `SBrkr`: Standard Circuit Breakers & Romex
    *   `FuseA`: Fuse Box over 60 AMP and all Romex wiring (Average)
    *   `FuseF`: 60 AMP Fuse Box and mostly Romex wiring (Fair)
    *   `FuseP`: 60 AMP Fuse Box and mostly knob & tube wiring (poor)
    *   `Mix`: Mixed

47. **X1st.Flr.SF** (Continuous): First Floor square feet.

48. **X2nd.Flr.SF** (Continuous): Second floor square feet.

49. **Low.Qual.Fin.SF** (Continuous): Low quality finished square feet (all floors).

50. **Bsmt.Full.Bath** (Discrete): Basement full bathrooms.

51. **Bsmt.Half.Bath** (Discrete): Basement half bathrooms.

52. **Full.Bath** (Discrete): Full bathrooms above grade.

53. **Half.Bath** (Discrete): Half baths above grade.

54. **Bedroom.AbvGr** (Discrete): Bedrooms above grade (does NOT include basement bedrooms). (Corresponds to `Bedroom` in AmesHousing.txt)

55. **Kitchen.AbvGr** (Discrete): Kitchens above grade. (Corresponds to `Kitchen` in AmesHousing.txt)

56. **Kitchen.Qual** (Ordinal): Kitchen quality.
    *   `Ex`: Excellent
    *   `Gd`: Good
    *   `TA`: Typical/Average
    *   `Fa`: Fair
    *   `Po`: Poor

57. **TotRms.AbvGrd** (Discrete): Total rooms above grade (does not include bathrooms).

58. **Functional** (Ordinal): Home functionality (Assume typical unless deductions are warranted).
    *   `Typ`: Typical Functionality
    *   `Min1`: Minor Deductions 1
    *   `Min2`: Minor Deductions 2
    *   `Mod`: Moderate Deductions
    *   `Maj1`: Major Deductions 1
    *   `Maj2`: Major Deductions 2
    *   `Sev`: Severely Damaged
    *   `Sal`: Salvage only

59. **Fireplaces** (Discrete): Number of fireplaces.

60. **Fireplace.Qu** (Ordinal): Fireplace quality.
    *   `Ex`: Excellent - Exceptional Masonry Fireplace
    *   `Gd`: Good - Masonry Fireplace in main level
    *   `TA`: Average - Prefabricated Fireplace in main living area or Masonry Fireplace in basement
    *   `Fa`: Fair - Prefabricated Fireplace in basement
    *   `Po`: Poor - Ben Franklin Stove
    *   `NA`: No Fireplace

61. **Garage.Type** (Nominal): Garage location.
    *   `2Types`: More than one type of garage
    *   `Attchd`: Attached to home
    *   `Basment`: Basement Garage
    *   `BuiltIn`: Built-In (Garage part of house - typically has room above garage)
    *   `CarPort`: Car Port
    *   `Detchd`: Detached from home
    *   `NA`: No Garage

62. **Garage.Yr.Blt** (Discrete): Year garage was built.

63. **Garage.Finish** (Ordinal): Interior finish of the garage.
    *   `Fin`: Finished
    *   `RFn`: Rough Finished
    *   `Unf`: Unfinished
    *   `NA`: No Garage

64. **Garage.Cars** (Discrete): Size of garage in car capacity.

65. **Garage.Area** (Continuous): Size of garage in square feet.

66. **Garage.Qual** (Ordinal): Garage quality.
    *   `Ex`: Excellent
    *   `Gd`: Good
    *   `TA`: Typical/Average
    *   `Fa`: Fair
    *   `Po`: Poor
    *   `NA`: No Garage

67. **Garage.Cond** (Ordinal): Garage condition.
    *   `Ex`: Excellent
    *   `Gd`: Good
    *   `TA`: Typical/Average
    *   `Fa`: Fair
    *   `Po`: Poor
    *   `NA`: No Garage

68. **Paved.Drive** (Ordinal): Paved driveway.
    *   `Y`: Paved
    *   `P`: Partial Pavement
    *   `N`: Dirt/Gravel

69. **Wood.Deck.SF** (Continuous): Wood deck area in square feet.

70. **Open.Porch.SF** (Continuous): Open porch area in square feet.

71. **Enclosed.Porch** (Continuous): Enclosed porch area in square feet.

72. **X3Ssn.Porch** (Continuous): Three season porch area in square feet. 
73. **Screen.Porch** (Continuous): Screen porch area in square feet.

74. **Pool.Area** (Continuous): Pool area in square feet.

75. **Pool.QC** (Ordinal): Pool quality.
    *   `Ex`: Excellent
    *   `Gd`: Good
    *   `TA`: Average/Typical
    *   `Fa`: Fair
    *   `NA`: No Pool

76. **Fence** (Ordinal): Fence quality.
    *   `GdPrv`: Good Privacy
    *   `MnPrv`: Minimum Privacy
    *   `GdWo`: Good Wood
    *   `MnWw`: Minimum Wood/Wire
    *   `NA`: No Fence

77. **Misc.Feature** (Nominal): Miscellaneous feature not covered in other categories.
    *   `Elev`: Elevator
    *   `Gar2`: 2nd Garage (if not described in garage section)
    *   `Othr`: Other
    *   `Shed`: Shed (over 100 SF)
    *   `TenC`: Tennis Court
    *   `NA`: None

78. **Misc.Val** (Continuous): $Value of miscellaneous feature.

79. **Mo.Sold** (Discrete): Month Sold (MM).

80. **Yr.Sold** (Discrete): Year Sold (YYYY).

81. **Sale.Type** (Nominal): Type of sale.
    *   `WD`: Warranty Deed - Conventional
    *   `CWD`: Warranty Deed - Cash
    *   `VWD`: Warranty Deed - VA Loan
    *   `New`: Home just constructed and sold
    *   `COD`: Court Officer Deed/Estate
    *   `Con`: Contract 15% Down payment regular terms
    *   `ConLw`: Contract Low Down payment and low interest
    *   `ConLI`: Contract Low Interest
    *   `ConLD`: Contract Low Down
    *   `Oth`: Other

82. **Sale.Condition** (Nominal): Condition of sale.
    *   `Normal`: Normal Sale
    *   `Abnorml`: Abnormal Sale - trade, foreclosure, short sale
    *   `AdjLand`: Adjoining Land Purchase
    *   `Alloca`: Allocation - two linked properties with separate deeds, typically condo with a garage unit
    *   `Family`: Sale between family members
    *   `Partial`: Home was not completed when last assessed (associated with New Homes)
