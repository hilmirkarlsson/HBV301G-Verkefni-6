# Staðsetning krafna í SRS

Sýnið staðsetningu allra gildandi krafna, einnig eftir uppskiptingu. Aðlagið kaflaheiti að kerfinu og rökstyðjið skipulag út frá tilgangi skjalsins og þörfum lesenda. Þetta er yfirlit; ekki þarf fullbúna SRS-skýrslu.

## Kröfur

| SRS-kafli eða undirkafli | Auðkenni og tenglar í kröfuskjöl | Rök fyrir staðsetningu og þörf lesenda |
| --- | --- | --- |
| 3.5 Virknikröfur | [FR-10 Tilbúin plön](requirements/FR-10.md) | Krafan lýsir virkni sem tengist vali á æfingaplani og styður notendakröfuna [UR-4](https://github.com/hilmirkarlsson/HBV301G-Verkefni-1/blob/main/SRS/user_requirement.md#ur-4-setja-upp-vikuna-f-2). Lesendur sem vinna með uppsetningu æfingaplana finna tengdar kröfur á sama stað. |


## Tengdar upplýsingar

Taflan hér fyrir neðan hjálpar lesanda að finna bakgrunnsupplýsingar sem þarf
til að skilja og túlka kröfurnar. Til dæmis getur krafa vísað til notendahlutverks,
hugtaks eða viðskiptareglu sem er útskýrt annars staðar. Taflan sýnir hvar þær
upplýsingar eru og hvaða kröfum þær tengjast. Hún dregur líka fram upplýsingar
sem vantar eða þarf að skýra.

Nýtið gögn sem þegar eru til, t.d. úr verkefni 1. Ekki þarf að skrifa þau upp
aftur eða búa til nýtt skjal fyrir hverja röð. Fyllið töfluna út þannig:

- Í **Staðsetning / auðkenni / tengill** setjið þið tengil á viðeigandi skjal,
  kafla eða issue og tilgreinið auðkenni ef það er til.
- Í **Tengsl við kröfur eða sýnileg eyða og eftirfylgni** tilgreinið þið hvaða kröfum upplýsingarnar tengjast, með auðkennum, og hvernig þær hjálpa við að skilja kröfurnar.
- Ef nauðsynlegar upplýsingar vantar, skráið `TBD`, hvað vantar,
  ábyrgðaraðila og næsta skref. Ef atriði á ekki við, skrifið „Á ekki við“ og rökstyðjið stuttlega.

Til dæmis gæti röðin **Notendahlutverk** vísað í kafla í verkefni 1 og skýrt að þar sé hlutverkið „umsjónarmaður“ skilgreint, sem krafan FR-03 vísar til.

| Upplýsingar | Staðsetning / auðkenni / tengill | Tengsl við kröfur eða sýnileg eyða og eftirfylgni |
| --- | --- | --- |
| Samhengi kerfisins | [SRS verkefni 1, kafli 1.2 Umfang og mörk kerfisins](https://github.com/hilmirkarlsson/HBV301G-Verkefni-1/blob/main/SRS/SRS.md#12-umfang-og-m%C3%B6rk-kerfisins) | Skýrir hvernig æfingaplan, æfingaskráning og framfarir tengjast FR-10, FR-11, FR-12 og FR-13. |
| Notendahlutverk | [SRS verkefni 1, kafli 2.1 Notendahópar](https://github.com/hilmirkarlsson/HBV301G-Verkefni-1/blob/main/SRS/SRS.md#21-notendah%C3%B3par) | FR-10, FR-11 og FR-12 styðja sérstaklega byrjendur. FR-13 styður notendur sem vilja fylgjast með framvindu sinni. |
| Orðasafn | [SRS verkefni 1, kafli 1.3 Skilgreiningar](https://github.com/hilmirkarlsson/HBV301G-Verkefni-1/blob/main/SRS/SRS.md#13-skilgreiningar) | Skilgreinir hugtök eins og „plan“, „sett“, „endurtekning“ og önnur hugtök sem koma fyrir í FR-10, FR-12, FR-11 og FR-13.|
| Viðskiptareglur | [VR-3 Framfarir reiknaðar út frá skráningum](https://github.com/hilmirkarlsson/HBV301G-Verkefni-5/blob/master/business-rules.md)| Tengist FR-13 þar sem saga og framfarir byggjast á áður skráðum æfingagögnum. |
| Gæðakröfur | [GÆ-2 Nytsemi](https://github.com/hilmirkarlsson/HBV301G-Verkefni-5/blob/master/quality-attributes.md) | FR-10, FR-11 og FR-12 styðja við markmið um að nýr notandi geti fljótt byrjað að nota kerfið án aðstoðar. |
| Forsendur | [F-2 Æfingaplan](https://github.com/hilmirkarlsson/HBV301G-Verkefni-1/blob/main/SRS/feature.md#f-2-%C3%A6fingaplan), [F-3 Framfarir](https://github.com/hilmirkarlsson/HBV301G-Verkefni-1/blob/main/SRS/feature.md#f-3-framfarir) | FR-10 og FR-11 byggja á því að notandi noti æfingaplan. FR-13 byggir á því að notandi hafi áður skráð æfingar. |
