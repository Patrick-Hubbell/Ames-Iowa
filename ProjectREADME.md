|Column Name|Type|Description|Vaiable: Description of Variable|
|SalePrice|Int|The property's sale price in dollars.|**¯\\_(ツ)_/¯**|
|MSSubClass|Int|The building class|
                    - 20 : 1-STORY 1946 & NEWER ALL STYLES
                    - 30 : 1-STORY 1945 & OLDER
                    - 40 : 1-STORY W/FINISHED ATTIC ALL AGES
                    - 45 : 1-1/2 STORY - UNFINISHED ALL AGES
                    - 50 : 1-1/2 STORY FINISHED ALL AGES
                    - 60 : 2-STORY 1946 & NEWER
                    - 70 : 2-STORY 1945 & OLDER
                    - 75 : 2-1/2 STORY ALL AGES
                    - 80 : SPLIT OR MULTI-LEVEL
                    - 85 : SPLIT FOYER
                    - 90 : DUPLEX - ALL STYLES AND AGES
                    - 120 : 1-STORY PUD (Planned Unit Development) - 1946 & NEWER
                    - 150 : 1-1/2 STORY PUD - ALL AGES
                    - 160 : 2-STORY PUD - 1946 & NEWER
                    - 180 : PUD - MULTILEVEL - INCL SPLIT LEV/FOYER
                    - 190 : 2 FAMILY CONVERSION - ALL STYLES AND AGES|
|MSZoning|Obj|Identifies the general zoning classification of the sale|
                    - A : Agriculture
                    - C : Commercial
                    - FV :Floating Village Residential
                    - I : Industrial
                    - RH : Residential High Density
                    - RL : Residential Low Density
                    - RP : Residential Low Density Park
                    - RM : Residential Medium Density|
|LotFrontage|Float|Linear feet of street connected to property|**¯\\_(ツ)_/¯**|
|LotArea|Float|Lot size in square feet|**¯\\_(ツ)_/¯**|
|Street|Obj|Type of road access to property|
                    - Grvl : Gravel
                    - Pave : Paved|
|Alley|Obj|Type of alley access to property|
                    - Grvl : Gravel
                    - Pave : Paved
                    - NA : No alley access|
|LotShape|Obj|General shape of property|
                    - Reg : Regular
                    - IR1 : Slightly irregular
                    - IR2 : Moderately Irregular
                    - IR3 : Irregular|
|LandContour|Obj|Flatness of the property|
                    - Lvl : Near Flat/Level
                    - Bnk : Banked - Quick and significant rise from street grade to building
                    - HLS : Hillside - Significant slope from side to side
                    - Low : Depression|
|Utilities|Obj|Type of utilities available|
                    - AllPub : All public Utilities (E,G,W,& S)
                    - NoSewr : Electricity, Gas, and Water (Septic Tank)
                    - NoSeWa : Electricity and Gas Only
                    - ELO : Electricity only|
|LotConfig|Obj|Lot configuration|
                    - Inside : Inside lot
                    - Corner : Corner lot
                    - CulDSac : Cul-de-sac
                    - FR2 : Frontage on 2 sides of property
                    - FR3 : Frontage on 3 sides of property|
|LandSlope|Obj|Slope of property|
                    - Gtl : Gentle slope
                    - Mod : Moderate Slope
                    - Sev : Severe Slope|
|Neighborhood|Obj|Physical locations within Ames city limits|
                    - Blmngtn : Bloomington Heights
                    - Blueste : Bluestem
                    - BrDale : Briardale
                    - BrkSide : Brookside
                    - ClearCr : Clear Creek
                    - CollgCr : College Creek
                    - Crawfor : Crawford
                    - Edwards : Edwards
                    - Gilbert : Gilbert
                    - IDOTRR : Iowa DOT and Rail Road
                    - MeadowV : Meadow Village
                    - Mitchel : Mitchell
                    - Names : North Ames
                    - NoRidge : Northridge
                    - NPkVill : Northpark Villa
                    - NridgHt : Northridge Heights
                    - NWAmes : Northwest Ames
                    - OldTown : Old Town
                    - SWISU : South & West of Iowa State University
                    - Sawyer : Sawyer
                    - SawyerW : Sawyer West
                    - Somerst : Somerset
                    - StoneBr : Stone Brook
                    - Timber : Timberland
                    - Veenker : Veenker|
|Condition1|Obj|Proximity to main road or railroad|
                    - Artery : Adjacent to arterial street
                    - Feedr : Adjacent to feeder street
                    - Norm : Normal
                    - RRNn : Within 200' of North-South Railroad
                    - RRAn : Adjacent to North-South Railroad
                    - PosN : Near positive off-site feature--park, greenbelt, etc.
                    - PosA : Adjacent to postive off-site feature
                    - RRNe : Within 200' of East-West Railroad
                    - RRAe : Adjacent to East-West Railroad|
|Condition2|Obj|Proximity to main road or railroad (if a second is present)|
                    - Artery : Adjacent to arterial street
                    - Feedr : Adjacent to feeder street
                    - Norm : Normal
                    - RRNn : Within 200' of North-South Railroad
                    - RRAn : Adjacent to North-South Railroad
                    - PosN : Near positive off-site feature--park, greenbelt, etc.
                    - PosA : Adjacent to postive off-site feature
                    - RRNe : Within 200' of East-West Railroad
                    - RRAe : Adjacent to East-West Railroad|
|BldgType|Obj|Type of dwelling|
                    - 1Fam : Single-family Detached
                    - 2FmCon : Two-family Conversion; originally built as one-family dwelling
                    - Duplx : Duplex
                    - TwnhsE : Townhouse End Unit
                    - TwnhsI : Townhouse Inside Unit|
|HouseStyle|Obj|Style of dwelling|
                    - 1Story : One story
                    - 1.5Fin : One and one-half story: 2nd level finished
                    - 1.5Unf : One and one-half story: 2nd level unfinished
                    - 2Story : Two story
                    - 2.5Fin : Two and one-half story: 2nd level finished
                    - 2.5Unf : Two and one-half story: 2nd level unfinished
                    - SFoyer : Split Foyer
                    - SLvl : Split Level|
|OverallQual|Int|Overall material and finish quality|
                    - 10 : Very Excellent
                    - 9 : Excellent
                    - 8 : Very Good
                    - 7 : Good
                    - 6 : Above Average
                    - 5 : Average
                    - 4 : Below Average
                    - 3 : Fair
                    - 2 : Poor
                    - 1 : Very Poor|
|OverallCond|Int|Overall condition rating|
                    - 10 : Very Excellent
                    - 9 : Excellent
                    - 8 : Very Good
                    - 7 : Good
                    - 6 : Above Average
                    - 5 : Average
                    - 4 : Below Average
                    - 3 : Fair
                    - 2 : Poor
                    - 1 : Very Poor|
|YearBuilt|Float|Original construction date|**¯\\_(ツ)_/¯**|
|YearRemodAdd|Float|Remodel date (same as construction date if no remodeling or additions)|**¯\\_(ツ)_/¯**|
|RoofStyle|Obj|Type of roof|
                    - Flat : Flat
                    - Gable : Gable
                    - Gambrel : Gabrel (Barn)
                    - Hip : Hip
                    - Mansard : Mansard
                    - Shed : Shed|
|RoofMatl|Obj|Roof material|
                    - ClyTile : Clay or Tile
                    - CompShg : Standard (Composite) Shingle
                    - Membran : Membrane
                    - Metal : Metal
                    - Roll : Roll
                    - Tar&Grv : Gravel & Tar
                    - WdShake : Wood Shakes
                    - WdShngl : Wood Shingles|
|Exterior1st|Obj|Exterior covering on house|
                    - AsbShng : Asbestos Shingles
                    - AsphShn : Asphalt Shingles
                    - BrkComm : Brick Common
                    - BrkFace : Brick Face
                    - CBlock : Cinder Block
                    - CemntBd : Cement Board
                    - HdBoard : Hard Board
                    - ImStucc : Imitation Stucco
                    - MetalSd : Metal Siding
                    - Other : Other
                    - Plywood : Plywood
                    - PreCast : PreCast
                    - Stone : Stone
                    - Stucco : Stucco
                    - VinylSd : Vinyl Siding
                    - Wd Sdng : Wood Siding
                    - WdShing : Wood Shingles|
|Exterior2nd|Obj|Exterior covering on house (if more than one material)|
                    - AsbShng : Asbestos Shingles
                    - AsphShn : Asphalt Shingles
                    - BrkComm : Brick Common
                    - BrkFace : Brick Face
                    - CBlock : Cinder Block
                    - CemntBd : Cement Board
                    - HdBoard : Hard Board
                    - ImStucc : Imitation Stucco
                    - MetalSd : Metal Siding
                    - Other : Other
                    - Plywood : Plywood
                    - PreCast : PreCast
                    - Stone : Stone
                    - Stucco : Stucco
                    - VinylSd : Vinyl Siding
                    - Wd Sdng : Wood Siding
                    - WdShing : Wood Shingles
                    - MasVnrType : Masonry veneer type
                    - BrkCmn : Brick Common
                    - BrkFace : Brick Face
                    - CBlock : Cinder Block
                    - None : None|
|MasVnrArea|Float|Masonry veneer area in square feet|**¯\\_(ツ)_/¯**|
|ExterQual|Obj|Exterior material quality|
                    - Ex : Excellent
                    - Gd : Good
                    - TA : Average/Typical
                    - Fa : Fair
                    - Po : Poor
|ExterCond|Obj|Present condition of the material on the exterior|
                    - Ex : Excellent
                    - Gd : Good
                    - TA : Average/Typical
                    - Fa : Fair
                    - Po : Poor|
|Foundation|Obj|Type of foundation|
                    - BrkTil : Brick & Tile
                    - CBlock : Cinder Block
                    - PConc : Poured Contrete
                    - Slab : Slab
                    - Stone : Stone
                    - Wood : Wood|
|BsmtQual|Obj|Height of the basement|
                    - Ex : Excellent (100+ inches)
                    - Gd : Good (90-99 inches)
                    - TA : Typical (80-89 inches)
                    - Fa : Fair (70-79 inches)
                    - Po : Poor (<70 inches)
                    - NA : No Basement|
|BsmtCond|Obj|General condition of the basement|
                    - Ex : Excellent
                    - Gd : Good
                    - TA : Typical - slight dampness allowed
                    - Fa : Fair - dampness or some cracking or settling
                    - Po : Poor - Severe cracking, settling, or wetness
                    - NA : No Basement|
|BsmtExposure|Obj|Walkout or garden level basement walls|
                    - Gd : Good Exposure
                    - Av : Average Exposure (split levels or foyers typically score average or above)
                    - Mn : Mimimum Exposure
                    - No : No Exposure
                    - NA : No Basement|
|BsmtFinType1|Obj|Quality of basement finished area|
                    - GLQ : Good Living Quarters
                    - ALQ : Average Living Quarters
                    - BLQ : Below Average Living Quarters
                    - Rec : Average Rec Room
                    - LwQ : Low Quality
                    - Unf : Unfinshed
                    - NA : No Basement|
|BsmtFinSF1|Float|Type 1 finished square feet|**¯\\_(ツ)_/¯**|
|BsmtFinType2|Obj|Quality of second finished area (if present)|
                    - GLQ : Good Living Quarters
                    - ALQ : Average Living Quarters
                    - BLQ : Below Average Living Quarters
                    - Rec : Average Rec Room
                    - LwQ : Low Quality
                    - Unf : Unfinshed
                    - NA : No Basement|
|BsmtFinSF2|Float|Type 2 finished square feet|**¯\\_(ツ)_/¯**|
|BsmtUnfSF|Float|Unfinished square feet of basement area|**¯\\_(ツ)_/¯**|
|TotalBsmtSF|Float|Total square feet of basement area|**¯\\_(ツ)_/¯**|
|Heating|Obj|Type of heating|
                    - Floor : Floor Furnace
                    - GasA : Gas forced warm air furnace
                    - GasW : Gas hot water or steam heat
                    - Grav : Gravity furnace
                    - OthW : Hot water or steam heat other than gas
                    - Wall : Wall furnace|
|HeatingQC|Obj|Heating quality and condition|
                    - Ex : Excellent
                    - Gd : Good
                    - TA : Average/Typical
                    - Fa : Fair
                    - Po : Poor|
|CentralAir|Obj|Central air conditioning|
                    - N : No
                    - Y : Yes|
|Electrical|Obj|Electrical system|
                    - SBrkr : Standard Circuit Breakers & Romex
                    - FuseA : Fuse Box over 60 AMP and all Romex wiring (Average)
                    - FuseF : 60 AMP Fuse Box and mostly Romex wiring (Fair)
                    - FuseP : 60 AMP Fuse Box and mostly knob & tube wiring (poor)
                    - Mix : Mixed|
|1stFlrSF|Float|First Floor square feet|**¯\\_(ツ)_/¯**|
|2ndFlrSF|Float|Second floor square feet|**¯\\_(ツ)_/¯**|
|LowQualFinSF|Float|Low quality finished square feet (all floors)|**¯\\_(ツ)_/¯**|
|GrLivArea|Float|Above (ground) living area square feet|**¯\\_(ツ)_/¯**|
|BsmtFullBath|Float|Basement full bathrooms|**¯\\_(ツ)_/¯**|
|BsmtHalfBath|Float|Basement half bathrooms|**¯\\_(ツ)_/¯**|
|FullBath|Float|Full bathrooms above grade|**¯\\_(ツ)_/¯**|
|HalfBath|Float|Half baths above grade|**¯\\_(ツ)_/¯**|
|Bedroom|Float|Number of bedrooms above basement level|**¯\\_(ツ)_/¯**|
|Kitchen|Float|Number of kitchens|**¯\\_(ツ)_/¯**|
|KitchenQual|Obj|Kitchen quality|
                    - Ex : Excellent
                    - Gd : Good
                    - TA : Typical/Average
                    - Fa : Fair
                    - Po : Poor|
|TotRmsAbvGrd|Float|Total rooms above grade (does not include bathrooms)|**¯\\_(ツ)_/¯**|
|Functional|Obj|Home functionality rating|
                    - Typ : Typical Functionality
                    - Min1 : Minor Deductions 1
                    - Min2 : Minor Deductions 2
                    - Mod : Moderate Deductions
                    - Maj1 : Major Deductions 1
                    - Maj2 : Major Deductions 2
                    - Sev : Severely Damaged
                    - Sal : Salvage only|
|Fireplaces|Float|Number of fireplaces|**¯\\_(ツ)_/¯**|
|FireplaceQu|Obj|Fireplace quality|
                    - Ex : Excellent, Exceptional Masonry Fireplace
                    - Gd : Good - Masonry Fireplace in main level
                    - TA : Average - Prefabricated Fireplace in main living area or Masonry Fireplace in basement
                    - Fa : Fair - Prefabricated Fireplace in basement
                    - Po : Poor - Ben Franklin Stove
                    - NA : No Fireplace|
|GarageType|Obj|Garage location|
                    - 2Types : More than one type of garage
                    - Attchd : Attached to home
                    - Basment : Basement Garage
                    - BuiltIn : Built-In (Garage part of house - typically has room above garage)
                    - CarPort : Car Port
                    - Detchd : Detached from home
                    - NA : No Garage|
|GarageYrBlt|Float|Year garage was built|**¯\\_(ツ)_/¯**|
|GarageFinish|Obj|Interior finish of the garage|
                    - Fin : Finished
                    - RFn : Rough Finished
                    - Unf : Unfinished
                    - NA : No Garage|
|GarageCars|Float|Size of garage in car capacity|**¯\\_(ツ)_/¯**|
|GarageArea|Float|Size of garage in square feet|**¯\\_(ツ)_/¯**|
|GarageQual|Obj|Garage quality|
                    - Ex : Excellent
                    - Gd : Good
                    - TA : Typical/Average
                    - Fa : Fair
                    - Po : Poor
                    - NA : No Garage|
|GarageCond|Obj|Garage condition|
                    - Ex : Excellent
                    - Gd : Good
                    - TA : Typical/Average
                    - Fa : Fair
                    - Po : Poor
                    - NA : No Garage|
|PavedDrive|Obj|Paved driveway|
                    - Y : Paved
                    - P : Partial Pavement
                    - N : Dirt/Gravel|
|WoodDeckSF|Float|Wood deck area in square feet|**¯\\_(ツ)_/¯**|
|OpenPorchSF|Float|Open porch area in square feet|**¯\\_(ツ)_/¯**|
|EnclosedPorch|Float|Enclosed porch area in square feet|**¯\\_(ツ)_/¯**|
|3SsnPorch|Float|Three season porch area in square feet|**¯\\_(ツ)_/¯**|
|ScreenPorch|Float|Screen porch area in square feet|**¯\\_(ツ)_/¯**|
|PoolArea|Float|Pool area in square feet|**¯\\_(ツ)_/¯**|
|PoolQC|Obj|Pool quality|
                    - Ex : Excellent
                    - Gd : Good
                    - TA : Average/Typical
                    - Fa : Fair
                    - NA : No Pool|
|Fence|Obj|Fence quality|
                    - GdPrv : Good Privacy
                    - MnPrv : Minimum Privacy
                    - GdWo : Good Wood
                    - MnWw : Minimum Wood/Wire
                    - NA : No Fence|
|MiscFeature|Obj|Miscellaneous feature not covered in other categories|
                    - Elev : Elevator
                    - Gar2 : 2nd Garage (if not described in garage section)
                    - Othr : Other
                    - Shed : Shed (over 100 SF)
                    - TenC : Tennis Court
                    - NA : None|
|MiscVal|Float|Value of miscellaneous feature|**¯\\_(ツ)_/¯**|
|MoSold|Float|Month Sold|**¯\\_(ツ)_/¯**|
|YrSold|Float|Year Sold|**¯\\_(ツ)_/¯**|
|SaleType|Obj|Type of sale|
                    - WD : Warranty Deed - Conventional
                    - CWD : Warranty Deed - Cash
                    - VWD : Warranty Deed - VA Loan
                    - New : Home just constructed and sold
                    - COD : Court Officer Deed/Estate
                    - Con : Contract 15% Down payment regular terms
                    - ConLw : Contract Low Down payment and low interest
                    - ConLI : Contract Low Interest
                    - ConLD : Contract Low Down
                    - Oth : Other|