# Radar
Arduino Uno-val megvalósitott radar rendszer ami felismeri ha egy test érkezik a szenzor/szenzorok előterébe
Szövegkörnyezet: TinkerCad alkalmazásban készült a projekt C++ nyelven.
Rövid leírás: Egy távolság mérő szenzor segítségével mérjük a távolságot, amit megjelenítünk egy LCD 16-2 es Panelon. 30 centiméteres távolságon kívül csak a távolságot jelzi az LCD panelon és zöld LED lámpa világít. 30 centiméteres távolságon belül kiírja a távolságot , egy figyelmeztető jelzés és zöld helyett piros lámpa fog világítani.
Felhasznált eszközök: Arduino uno R3, LCD 16-2, 2 db LED lámpa(1 piros, 1 zöld), Ultrahangos távolságérzékelő, szerelőlap, 2db ellenállás. 
Vezetékezés:Piros-tápfeszültség, Fekete-földelés, Türkizkék-zöld jelzőlámpa,Narancssárga-piros jelzőlámpa, Sárga-LCD 16-2, Zöld-ultrahangos távolságmérő.

Szoftver:változók(cm(mért távolság),distanceThreshold(maximum távolság amíg mér a szenzor),triggerPin(eseményindító a távolságmérőhöz),echoPin(eredmény visszküldő a távolságmérőhöz)
