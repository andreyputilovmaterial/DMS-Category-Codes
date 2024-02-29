# DMS-Category-Codes

A DMS script that helps you check data for ghost categories.

Just add MDD & DDF file name at the top (or, better pass it as a param from BAT file or command line - see example below). Output files are the same with <code>.del</code> added, deleted in OnJobEnd.

The output is saved in a text file <code>report.categorymap.log.txt</code>

Example call:<br />
<code>dmsrun categorycodes.dms /d"INP_NAME """"R221646"""""</code><br />
or<br />
<code>dmsrun categorycodes.dms /d"INP_NAME """"Data\R221646"""""</code>

Example of outputs:
<code>
Fields[Child_1].KidInfo.ModsQualified:1087=toddler
Fields[Child_1].KidInfo.ModsQualified_User:1087=toddler
Fields.DV_ModsQualified_NEW:1087=toddler
Fields[BrandTrust].Attributes.GV:7971=yummyspoonfuls
Fields[WorthPayingMore].Attributes.GV:7971=yummyspoonfuls
Fields[OffersRecyclablePackaging].Attributes.GV:7971=yummyspoonfuls
Fields[Nutritious].Attributes.GV:7971=yummyspoonfuls
Fields[SuperiorQualityBrand].Attributes.GV:7971=yummyspoonfuls
Fields[ContainNoBadStuff].Attributes.GV:7971=yummyspoonfuls
Fields[OffersCertifiedOrgIng].Attributes.GV:7971=yummyspoonfuls
Fields[SimplifiesLife].Attributes.GV:7971=yummyspoonfuls
Fields[UnderstandsNeedsParent].Attributes.GV:7971=yummyspoonfuls
Fields[SelfFeedSkills].Attributes.GV:7971=yummyspoonfuls
Fields[MadeSimpleIngredients].Attributes.GV:7971=yummyspoonfuls
Fields[TasteToddlerLoves].Attributes.GV:7971=yummyspoonfuls
Fields[BestICan].Attributes.GV:7971=yummyspoonfuls
Fields[BrandCaresEnvironment].Attributes.GV:7971=yummyspoonfuls
Fields[FruitsVegBestFarms].Attributes.GV:7971=yummyspoonfuls
Fields[HasWidestRange].Attributes.GV:7971=yummyspoonfuls
Fields[HealthiestToddler].Attributes.GV:7971=yummyspoonfuls
Fields.QTA_Module:1087=toddler
Fields.DV_ModsAssigned_FINAL:1087=toddler
Fields.DV_CatMods_First:1087=toddler
Fields[Child_2].KidInfo.ModsQualified:1087=toddler
Fields[Child_2].KidInfo.ModsQualified_User:1087=toddler
Fields.NetM8b:6115=clubplum
Fields.DV_CatMods_Second:1087=toddler
Fields[RecFriendsFamily].MB_Attributes.GV:1151=ella_kitchen
Fields[TasteChildLoves].MB_Attributes.GV:1151=ella_kitchen
Fields[BrandTrust].MB_Attributes.GV:1151=ella_kitchen
Fields[NoBadStuff].MB_Attributes.GV:1151=ella_kitchen
Fields[WorthPayingMore].MB_Attributes.GV:1151=ella_kitchen
Fields[UnderstandsNeedsAsParent].MB_Attributes.GV:1151=ella_kitchen
Fields[Innovating].MB_Attributes.GV:1151=ella_kitchen
Fields[SuperiorQualityBrand].MB_Attributes.GV:1151=ella_kitchen
Fields[ConfidentAboutChoices].MB_Attributes.GV:1151=ella_kitchen
Fields[MakesProductNutrtDevelopment].MB_Attributes.GV:1151=ella_kitchen
Fields[HelpsParentsProvideHealthyFound].MB_Attributes.GV:1151=ella_kitchen
Fields[ValuableServicesTools].MB_Attributes.GV:1151=ella_kitchen
Fields[Successful].MB_Attributes.GV:1151=ella_kitchen
Fields[Committed].MB_Attributes.GV:1151=ella_kitchen
Fields[Happy].MB_Attributes.GV:1151=ella_kitchen
Fields[Expert].MB_Attributes.GV:1151=ella_kitchen
Fields[QualityProducts].MB_Attributes.GV:1151=ella_kitchen
Fields[InnovativeProducts].MB_Attributes.GV:1151=ella_kitchen
Fields[Child_1].KidInfo.ModsQualified_Intender:1087=toddler
Fields[RecommendedDoctorsNu].MB_Attributes.GV:1151=ella_kitchen
Fields[Leader].MB_Attributes.GV:1151=ella_kitchen
Fields[First1000Days].MB_Attributes.GV:1151=ella_kitchen
Fields[Child_2].KidInfo.ModsQualified_Intender:1087=toddler
Fields[Close].MB_Attributes.GV:1151=ella_kitchen
Fields[Child_3].KidInfo.ModsQualified:1087=toddler
Fields[Child_3].KidInfo.ModsQualified_Intender:1087=toddler
Fields[Child_3].KidInfo.ModsQualified_User:1087=toddler
Fields[BestQualityIngredien].MB_Attributes.GV:1151=ella_kitchen
Fields[Natural].MB_Attributes.GV:1151=ella_kitchen
Fields[Organic].MB_Attributes.GV:1151=ella_kitchen
Fields[Expensive].MB_Attributes.GV:1151=ella_kitchen
Fields[Value].MB_Attributes.GV:1151=ella_kitchen
</code>
