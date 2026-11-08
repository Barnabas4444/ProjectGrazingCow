# ProjectGrazingCow
Repository for the main Deep learning in Python homework

Csapattagok: 
  Faludi Zsófia - B4ZPWB
  Danyi Kristóf - GQOKMW
  Szemán Barnabás - ZKR2O5
  
Projekt ismertetése: 
Van elég fű a legelőn az állatoknak? A rendelkezésre álló takarmány mennyiségének becslése segít a gazdáknak eldönteni, mikor hajtsák ki az állatokat, és mikor hagyják a legelőt regenerálódni. A CSIRO – Image2Biomass Prediction Kaggle-verseny feladata a legelők biomasszájának becslése fényképek alapján. A verseny adatkészlete különböző ausztrál régiókból és évszakokból származó, eltérő fajösszetételű legelőkről készült képeket tartalmaz. A képekhez helyszíni biomasszamérések és a növényzet állapotát jellemző NDVI-értékek is tartoznak. A feladatban öt, grammban megadott értéket kell becsülni.


test: a feltöltött teszt képet tartalmazzal

test.csv: a kód számára beolvasható csv formátumban tartalmazza a teszt képet

train_small_images: a kaggle-en meghatározott train adathalmaz, 30db-os részhalmazát tartalmazza png formátumokban

train_small.csv: a train_small_images-ben megtalálható 30db kép csv formátumban

data_preparation.ipynb: ez a notebook tartalmazza az adatok beolvasását, elemzését és vizualizációját

pasture_biomass_tensorflow.ipynb: a notebookban egy TensorFlow-modellt tanítunk be, amely egy legelőfotóból öt biomasszaértéket becsül grammban, illetve a végén a tesztképekre is elkészítjük a becsléseket.
