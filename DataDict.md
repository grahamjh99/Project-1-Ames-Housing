Dataset Description
Data
There are three files:

    train.csv -- this data contains all of the training data for your model. The target variable (SalePrice) is removed from the test set!
    test.csv -- this data contains the test data for your model. You will feed this data into your regression model to make predictions.
    sample_sub_reg.csv -- an example of a correctly formatted submission for this challenge (with a random number provided as predictions for SalePrice. Please ensure that your submission to Kaggle matches this format.

Codebook / Data Dictionary:

    SalePrice - the property's sale price in dollars. This is the target variable that you're trying to predict for this challenge.
    MSSubClass: The building class ---> changed to get dummy columns for each
        20 1-STORY 1946 & NEWER ALL STYLES
        30 1-STORY 1945 & OLDER
        40 1-STORY W/FINISHED ATTIC ALL AGES
        45 1-1/2 STORY - UNFINISHED ALL AGES
        50 1-1/2 STORY FINISHED ALL AGES
        60 2-STORY 1946 & NEWER
        70 2-STORY 1945 & OLDER
        75 2-1/2 STORY ALL AGES
        80 SPLIT OR MULTI-LEVEL
        85 SPLIT FOYER
        90 DUPLEX - ALL STYLES AND AGES
        120 1-STORY PUD (Planned Unit Development) - 1946 & NEWER
        150 1-1/2 STORY PUD - ALL AGES
        160 2-STORY PUD - 1946 & NEWER
        180 PUD - MULTILEVEL - INCL SPLIT LEV/FOYER
        190 2 FAMILY CONVERSION - ALL STYLES AND AGES
    MSZoning: Identifies the general zoning classification of the sale.
        A Agriculture
        C Commercial
        FV Floating Village Residential
        I Industrial
        RH Residential High Density
        RL Residential Low Density
        RP Residential Low Density Park
        RM Residential Medium Density
    LotFrontage: Linear feet of street connected to property
    LotArea: Lot size in square feet
    Street: Type of road access to property
        Grvl Gravel
        Pave Paved
    Alley: Type of alley access to property
        Grvl Gravel
        Pave Paved
        NA No alley access
    LotShape: General shape of property
        Reg Regular
        IR1 Slightly irregular
        IR2 Moderately Irregular
        IR3 Irregular
    LandContour: Flatness of the property
        Lvl Near Flat/Level
        Bnk Banked - Quick and significant rise from street grade to building
        HLS Hillside - Significant slope from side to side
        Low Depression
    Utilities: Type of utilities available
        AllPub All public Utilities (E,G,W,& S)
        NoSewr Electricity, Gas, and Water (Septic Tank)
        NoSeWa Electricity and Gas Only
        ELO Electricity only
    LotConfig: Lot configuration
        Inside Inside lot
        Corner Corner lot
        CulDSac Cul-de-sac
        FR2 Frontage on 2 sides of property
        FR3 Frontage on 3 sides of property
    LandSlope: Slope of property
        Gtl Gentle slope
        Mod Moderate Slope
        Sev Severe Slope
    Neighborhood: Physical locations within Ames city limits
        Blmngtn Bloomington Heights
        Blueste Bluestem
        BrDale Briardale
        BrkSide Brookside
        ClearCr Clear Creek
        CollgCr College Creek
        Crawfor Crawford
        Edwards Edwards
        Gilbert Gilbert
        IDOTRR Iowa DOT and Rail Road
        MeadowV Meadow Village
        Mitchel Mitchell
        Names North Ames
        NoRidge Northridge
        NPkVill Northpark Villa
        NridgHt Northridge Heights
        NWAmes Northwest Ames
        OldTown Old Town
        SWISU South & West of Iowa State University
        Sawyer Sawyer
        SawyerW Sawyer West
        Somerst Somerset
        StoneBr Stone Brook
        Timber Timberland
        Veenker Veenker
    Condition1: Proximity to main road or railroad
        Artery Adjacent to arterial street
        Feedr Adjacent to feeder street
        Norm Normal
        RRNn Within 200' of North-South Railroad
        RRAn Adjacent to North-South Railroad
        PosN Near positive off-site feature--park, greenbelt, etc.
        PosA Adjacent to postive off-site feature
        RRNe Within 200' of East-West Railroad
        RRAe Adjacent to East-West Railroad
    Condition2: Proximity to main road or railroad (if a second is present)
        Artery Adjacent to arterial street
        Feedr Adjacent to feeder street
        Norm Normal
        RRNn Within 200' of North-South Railroad
        RRAn Adjacent to North-South Railroad
        PosN Near positive off-site feature--park, greenbelt, etc.
        PosA Adjacent to postive off-site feature
        RRNe Within 200' of East-West Railroad
        RRAe Adjacent to East-West Railroad
    BldgType: Type of dwelling
        1Fam Single-family Detached
        2FmCon Two-family Conversion; originally built as one-family dwelling
        Duplx Duplex
        TwnhsE Townhouse End Unit
        TwnhsI Townhouse Inside Unit
    HouseStyle: Style of dwelling
        1Story One story
        1.5Fin One and one-half story: 2nd level finished
        1.5Unf One and one-half story: 2nd level unfinished
        2Story Two story
        2.5Fin Two and one-half story: 2nd level finished
        2.5Unf Two and one-half story: 2nd level unfinished
        SFoyer Split Foyer
        SLvl Split Level
    OverallQual: Overall material and finish quality
        10 Very Excellent
        9 Excellent
        8 Very Good
        7 Good
        6 Above Average
        5 Average
        4 Below Average
        3 Fair
        2 Poor
        1 Very Poor
    OverallCond: Overall condition rating
        10 Very Excellent
        9 Excellent
        8 Very Good
        7 Good
        6 Above Average
        5 Average
        4 Below Average
        3 Fair
        2 Poor
        1 Very Poor
    YearBuilt: Original construction date
    YearRemodAdd: Remodel date (same as construction date if no remodeling or additions)
    RoofStyle: Type of roof
        Flat Flat
        Gable Gable
        Gambrel Gabrel (Barn)
        Hip Hip
        Mansard Mansard
        Shed Shed
    RoofMatl: Roof material
        ClyTile Clay or Tile
        CompShg Standard (Composite) Shingle
        Membran Membrane
        Metal Metal
        Roll Roll
        Tar&Grv Gravel & Tar
        WdShake Wood Shakes
        WdShngl Wood Shingles
    Exterior1st: Exterior covering on house
        AsbShng Asbestos Shingles
        AsphShn Asphalt Shingles
        BrkComm Brick Common
        BrkFace Brick Face
        CBlock Cinder Block
        CemntBd Cement Board
        HdBoard Hard Board
        ImStucc Imitation Stucco
        MetalSd Metal Siding
        Other Other
        Plywood Plywood
        PreCast PreCast
        Stone Stone
        Stucco Stucco
        VinylSd Vinyl Siding
        Wd Sdng Wood Siding
        WdShing Wood Shingles
    Exterior2nd: Exterior covering on house (if more than one material)
        AsbShng Asbestos Shingles
        AsphShn Asphalt Shingles
        BrkComm Brick Common
        BrkFace Brick Face
        CBlock Cinder Block
        CemntBd Cement Board
        HdBoard Hard Board
        ImStucc Imitation Stucco
        MetalSd Metal Siding
        Other Other
        Plywood Plywood
        PreCast PreCast
        Stone Stone
        Stucco Stucco
        VinylSd Vinyl Siding
        Wd Sdng Wood Siding
        WdShing Wood Shingles
    MasVnrType: Masonry veneer type
        BrkCmn Brick Common
        BrkFace Brick Face
        CBlock Cinder Block
        None None
        Stone Stone
    MasVnrArea: Masonry veneer area in square feet
    ExterQual: Exterior material quality ----> changed to 1-5 scale
        Ex Excellent
        Gd Good
        TA Average/Typical
        Fa Fair
        Po Poor
    ExterCond: Present condition of the material on the exterior ---> changed to 1-5 scale
        Ex Excellent
        Gd Good
        TA Average/Typical
        Fa Fair
        Po Poor
    Foundation: Type of foundation
        BrkTil Brick & Tile
        CBlock Cinder Block
        PConc Poured Contrete
        Slab Slab
        Stone Stone
        Wood Wood
    BsmtQual: Height of the basement----> changed to a 0-5 scale
        Ex Excellent (100+ inches)
        Gd Good (90-99 inches)
        TA Typical (80-89 inches)
        Fa Fair (70-79 inches)
        Po Poor (<70 inches)
        NA No Basement
    BsmtCond: General condition of the basement ---> changed to a 0-5 scale
        Ex Excellent
        Gd Good
        TA Typical - slight dampness allowed
        Fa Fair - dampness or some cracking or settling
        Po Poor - Severe cracking, settling, or wetness
        NA No Basement
    BsmtExposure: Walkout or garden level basement walls ---> Changed to a 0-4
        Gd Good Exposure
        Av Average Exposure (split levels or foyers typically score average or above)
        Mn Mimimum Exposure
        No No Exposure
        NA No Basement
    BsmtFinType1: Quality of basement finished area 
        GLQ Good Living Quarters
        ALQ Average Living Quarters
        BLQ Below Average Living Quarters
        Rec Average Rec Room
        LwQ Low Quality
        Unf Unfinshed
        NA No Basement
    BsmtFinSF1: Type 1 finished square feet
    BsmtFinType2: Quality of second finished area (if present) 
        GLQ Good Living Quarters
        ALQ Average Living Quarters
        BLQ Below Average Living Quarters
        Rec Average Rec Room
        LwQ Low Quality
        Unf Unfinshed
        NA No Basement
    BsmtFinSF2: Type 2 finished square feet
    BsmtUnfSF: Unfinished square feet of basement area
    TotalBsmtSF: Total square feet of basement area
    Heating: Type of heating
        Floor Floor Furnace
        GasA Gas forced warm air furnace
        GasW Gas hot water or steam heat
        Grav Gravity furnace
        OthW Hot water or steam heat other than gas
        Wall Wall furnace
    HeatingQC: Heating quality and condition ---> Changed to 1-5 scale
        Ex Excellent
        Gd Good
        TA Average/Typical
        Fa Fair
        Po Poor
    CentralAir: Central air conditioning
        N No
        Y Yes
    Electrical: Electrical system
        SBrkr Standard Circuit Breakers & Romex
        FuseA Fuse Box over 60 AMP and all Romex wiring (Average)
        FuseF 60 AMP Fuse Box and mostly Romex wiring (Fair)
        FuseP 60 AMP Fuse Box and mostly knob & tube wiring (poor)
        Mix Mixed
    1stFlrSF: First Floor square feet
    2ndFlrSF: Second floor square feet
    LowQualFinSF: Low quality finished square feet (all floors)
    GrLivArea: Above grade (ground) living area square feet
    BsmtFullBath: Basement full bathrooms
    BsmtHalfBath: Basement half bathrooms
    FullBath: Full bathrooms above grade
    HalfBath: Half baths above grade
    Bedroom: Number of bedrooms above basement level
    Kitchen: Number of kitchens
    KitchenQual: Kitchen quality ---> Changed to 1-5 scale
        Ex Excellent
        Gd Good
        TA Typical/Average
        Fa Fair
        Po Poor
    TotRmsAbvGrd: Total rooms above grade (does not include bathrooms)
    Functional: Home functionality rating
        Typ Typical Functionality
        Min1 Minor Deductions 1
        Min2 Minor Deductions 2
        Mod Moderate Deductions
        Maj1 Major Deductions 1
        Maj2 Major Deductions 2
        Sev Severely Damaged
        Sal Salvage only
    Fireplaces: Number of fireplaces
    FireplaceQu: Fireplace quality ---> changed to 0-5 scale
        Ex Excellent - Exceptional Masonry Fireplace
        Gd Good - Masonry Fireplace in main level
        TA Average - Prefabricated Fireplace in main living area or Masonry Fireplace in basement
        Fa Fair - Prefabricated Fireplace in basement
        Po Poor - Ben Franklin Stove
        NA No Fireplace
    GarageType: Garage location
        2Types More than one type of garage
        Attchd Attached to home
        Basment Basement Garage
        BuiltIn Built-In (Garage part of house - typically has room above garage)
        CarPort Car Port
        Detchd Detached from home
        NA No Garage
    GarageYrBlt: Year garage was built
    GarageFinish: Interior finish of the garage
        Fin Finished
        RFn Rough Finished
        Unf Unfinished
        NA No Garage
    GarageCars: Size of garage in car capacity
    GarageArea: Size of garage in square feet
    GarageQual: Garage quality ---> changed to 0-5 scale
        Ex Excellent
        Gd Good
        TA Typical/Average
        Fa Fair
        Po Poor
        NA No Garage
    GarageCond: Garage condition ---> changed to 0-5 scale
        Ex Excellent
        Gd Good
        TA Typical/Average
        Fa Fair
        Po Poor
        NA No Garage
    PavedDrive: Paved driveway
        Y Paved
        P Partial Pavement
        N Dirt/Gravel
    WoodDeckSF: Wood deck area in square feet
    OpenPorchSF: Open porch area in square feet
    EnclosedPorch: Enclosed porch area in square feet
    3SsnPorch: Three season porch area in square feet
    ScreenPorch: Screen porch area in square feet
    PoolArea: Pool area in square feet
    PoolQC: Pool quality ---> changed to 0-4 scale
        Ex Excellent
        Gd Good
        TA Average/Typical
        Fa Fair
        NA No Pool
    Fence: Fence quality
        GdPrv Good Privacy
        MnPrv Minimum Privacy
        GdWo Good Wood
        MnWw Minimum Wood/Wire
        NA No Fence
    MiscFeature: Miscellaneous feature not covered in other categories
        Elev Elevator
        Gar2 2nd Garage (if not described in garage section)
        Othr Other
        Shed Shed (over 100 SF)
        TenC Tennis Court
        NA None
    MiscVal: $Value of miscellaneous feature
    MoSold: Month Sold
    YrSold: Year Sold
    SaleType: Type of sale
        WD Warranty Deed - Conventional
        CWD Warranty Deed - Cash
        VWD Warranty Deed - VA Loan
        New Home just constructed and sold
        COD Court Officer Deed/Estate
        Con Contract 15% Down payment regular terms
        ConLw Contract Low Down payment and low interest
        ConLI Contract Low Interest
        ConLD Contract Low Down
        Oth Other
