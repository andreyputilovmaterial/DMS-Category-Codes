# DMS-Category-Codes

A DMS script that helps you check data for ghost categories.

Just add MDD & DDF file name at the top. As it's a DMS script, it needs output data source to write to. Just specify a random name (Rtestout.mdd by default), but you'll have to delete these files when processing finishes.

The output is saved in a text file <code>report.categorymap.log.txt</code>

Example call:<br />
<code>dmsrun categorycodes.dms /d"INP_NAME """"R221646"""""</code>

Example of outputs:
<code>
Fields.KidInfo[{Child_1}].ModsQualified:1087=toddler
Fields.KidInfo[{Child_1}].ModsQualified_User:1087=toddler
Fields.DV_ModsQualified_NEW:1087=toddler
Fields.Attributes[{BrandTrust}].GV:7971=yummyspoonfuls
Fields.Attributes[{WorthPayingMore}].GV:7971=yummyspoonfuls
Fields.Attributes[{OffersRecyclablePackaging}].GV:7971=yummyspoonfuls
Fields.Attributes[{Nutritious}].GV:7971=yummyspoonfuls
Fields.Attributes[{SuperiorQualityBrand}].GV:7971=yummyspoonfuls
Fields.Attributes[{ContainNoBadStuff}].GV:7971=yummyspoonfuls
Fields.Attributes[{OffersCertifiedOrgIng}].GV:7971=yummyspoonfuls
Fields.Attributes[{SimplifiesLife}].GV:7971=yummyspoonfuls
Fields.Attributes[{UnderstandsNeedsParent}].GV:7971=yummyspoonfuls
Fields.Attributes[{SelfFeedSkills}].GV:7971=yummyspoonfuls
Fields.Attributes[{MadeSimpleIngredients}].GV:7971=yummyspoonfuls
Fields.Attributes[{TasteToddlerLoves}].GV:7971=yummyspoonfuls
Fields.Attributes[{BestICan}].GV:7971=yummyspoonfuls
Fields.Attributes[{BrandCaresEnvironment}].GV:7971=yummyspoonfuls
Fields.Attributes[{FruitsVegBestFarms}].GV:7971=yummyspoonfuls
Fields.Attributes[{HasWidestRange}].GV:7971=yummyspoonfuls
Fields.Attributes[{HealthiestToddler}].GV:7971=yummyspoonfuls
Fields.QTA_Module:1087=toddler
Fields.DV_ModsAssigned_FINAL:1087=toddler
Fields.DV_CatMods_First:1087=toddler
Fields.KidInfo[{Child_2}].ModsQualified:1087=toddler
Fields.KidInfo[{Child_2}].ModsQualified_User:1087=toddler
Fields.NetM8b:6115=clubplum
Fields.DV_CatMods_Second:1087=toddler
Fields.MB_Attributes[{RecFriendsFamily}].GV:1151=ella_kitchen
Fields.MB_Attributes[{TasteChildLoves}].GV:1151=ella_kitchen
Fields.MB_Attributes[{BrandTrust}].GV:1151=ella_kitchen
Fields.MB_Attributes[{NoBadStuff}].GV:1151=ella_kitchen
Fields.MB_Attributes[{WorthPayingMore}].GV:1151=ella_kitchen
Fields.MB_Attributes[{UnderstandsNeedsAsParent}].GV:1151=ella_kitchen
Fields.MB_Attributes[{Innovating}].GV:1151=ella_kitchen
Fields.MB_Attributes[{SuperiorQualityBrand}].GV:1151=ella_kitchen
Fields.MB_Attributes[{ConfidentAboutChoices}].GV:1151=ella_kitchen
Fields.MB_Attributes[{MakesProductNutrtDevelopment}].GV:1151=ella_kitchen
Fields.MB_Attributes[{HelpsParentsProvideHealthyFound}].GV:1151=ella_kitchen
Fields.MB_Attributes[{ValuableServicesTools}].GV:1151=ella_kitchen
Fields.MB_Attributes[{Successful}].GV:1151=ella_kitchen
Fields.MB_Attributes[{Committed}].GV:1151=ella_kitchen
Fields.MB_Attributes[{Happy}].GV:1151=ella_kitchen
Fields.MB_Attributes[{Expert}].GV:1151=ella_kitchen
Fields.MB_Attributes[{QualityProducts}].GV:1151=ella_kitchen
Fields.MB_Attributes[{InnovativeProducts}].GV:1151=ella_kitchen
Fields.MB_Attributes[{RecommendedDoctorsNu}].GV:1151=ella_kitchen
Fields.MB_Attributes[{Leader}].GV:1151=ella_kitchen
Fields.MB_Attributes[{First1000Days}].GV:1151=ella_kitchen
Fields.KidInfo[{Child_1}].ModsQualified_Intender:1087=toddler
Fields.KidInfo[{Child_2}].ModsQualified_Intender:1087=toddler
Fields.KidInfo[{Child_3}].ModsQualified:1087=toddler
Fields.KidInfo[{Child_3}].ModsQualified_User:1087=toddler
Fields.MB_Attributes[{Close}].GV:1151=ella_kitchen
Fields.KidInfo[{Child_3}].ModsQualified_Intender:1087=toddler
Fields.MB_Attributes[{BestQualityIngredien}].GV:1151=ella_kitchen
Fields.MB_Attributes[{Natural}].GV:1151=ella_kitchen
Fields.MB_Attributes[{Organic}].GV:1151=ella_kitchen
Fields.MB_Attributes[{Expensive}].GV:1151=ella_kitchen
Fields.MB_Attributes[{Value}].GV:1151=ella_kitchen
</code>
