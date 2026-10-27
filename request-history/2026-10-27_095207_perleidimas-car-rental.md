# Perleidimas nuo žingsnio „Auto nuoma“ — 2026-10-27 09:52:07 UTC

- **Kelionė:** `7aa468f3b124`
- **Pradžia / pabaiga:** 2026-10-27 09:52:07 → 11:00:03 (67 min.)
- **Agentų rinkinys:** Base
- **Rezultatas:** ✅ Baigta

## Eiga

- `09:52:07` Perleidžiama nuo žingsnio: car_rental...
- `09:52:07` Automobilio nuomos pasiūlymai...
- `09:54:46` Maistas, vietiniai patiekalai ir barai...
- `10:00:47` Orų prognozė...
- `10:00:47` Planas B blogam orui (alternatyvos ir kelių patikra)...
- `10:11:58` Daiktų sąrašas...
- `10:13:38` Biudžeto skaičiavimas...
- `10:15:24` Puslapio atnaujinimas (dizainas išlaikomas)...
- `10:29:29` Nepavyko: Page Designer did not return a complete HTML document: ' Berate – kaip pagrindiniame plane.</p>\n    </div>\n    <p>Bendras vairavimo laikas: apie 179 min.</p>\n    <a class="route-btn" href="https://www.google.com/maps/dir/?api=1&origin=Kalaja+e+Kruj%C3%ABs,+Kruj%C3%AB,+Albania&destination=Lili+Homemade+Food,+Berat,+Albania&travelmode=driving&waypoints=Liq'
- `10:29:29` Automatinis pakartojimas 1/5 po 60 s (jau atlikti žingsniai perpanaudojami)...
- `10:30:29` Tęsiama nuo žingsnio: Puslapis
- `10:30:29` Puslapio generavimas...
- `10:38:35` Puslapio patikra rado 9 netikslumų - taisomas tik puslapis...
- `10:44:40` Puslapio patikra rado 2 netikslumų - taisomas tik puslapis...
- `10:52:10` Puslapio patikra rado 1 netikslumų - taisomas tik puslapis...
- `10:58:27` Repozitorijos kūrimas ir puslapio publikavimas...
- `11:00:03` Puslapis paskelbtas: https://sauliusc.github.io/ai-trip-albanija-roundtrip/

## Agentų kvietimai (10)

### 1. Auto nuoma — 09:54:46 ✅

- **Modelis:** `claude-haiku-4-5-20251001, claude-sonnet-5` · **Vykdė:** Native Claude (claude -p) · **Trukmė:** 158.8 s
- **Sistemos promptas:** `prompts/car_rental.md`

<details><summary><b>Užklausa</b></summary>

**Trip requirements:**

```json
{
  "destination": "Albanija",
  "trip_type": "roundtrip",
  "start_date": "2026-10-30",
  "end_date": "2026-11-02",
  "travelers": 4,
  "budget_eur": null,
  "airport": "TIA",
  "return_flight_time": "19:05",
  "max_driving_hours_per_day": 4.0,
  "priorities": [
    "gamta"
  ],
  "language": "lt",
  "notes": "Ratu per Albaniją (TIA-TIA), kiekvieną naktį kita nakvynės vieta (3 nakvynės: penktadienį, šeštadienį, sekmadienį). Vengti šiaurinių kalnų kelių (Theth, Valbona) dėl rudens/žiemos oro rizikos — orientuotis į vidurio/pietų Albaniją arba lengviau pasiekiamas šiaurines vietas (Škodrio ežeras, Komano užtvanka). Trumpos dienos šviesos valandos (sutemsta ~17:00–17:30), pageidaujama važiuoti ne daugiau 3,5–4 val. per dieną. Nuomojamas automobilis turi tilpti 4 žmonėms ir bagažui, atsiimamas ir grąžinamas TIA (grąžinti iki ~17:00 lapkričio 2 d.). Papildoma logistika (ne pagrindinis Albanijos maršrutas): asmeninis automobilis Kaunas–Varšuva (WAW)–Kaunas; išvykimo skrydis WAW 18:30 → TIA 20:30 spalio 30 d. (iš Kauno išvykti ne vėliau ~11:00); grįžimo skrydis TIA 19:05 → WAW 21:10 lapkričio 2 d."
}
```

Original request:
Štai susistemintas ir detalus reikalavimų sąrašas (promptas), kurį galite pateikti AI modeliui, kad jis sugeneruotų tikslų ir įgyvendinamą kelionės maršrutą:Reikalavimai AI: Trumpos 3 dienų kelionės automobiliais ir lėktuvu maršrutas Albanijoje1. Bendra informacija ir keliautojaiKeliautojų skaičius: 4 suaugę asmenys.Transportas:Asmeninis automobilis: Kaunas–Varšuva (WAW)–Kaunas.Nuomojamas automobilis: Tiranos oro uostas (TIA) – ratu per Albaniją – TIA (reikia vietos 4 žmonėms ir bagažui).2. Skrydžių ir logistikos laikaiIšskridimas: Spalio 30 d. (penktadienis), WAW 18:30 → TIA 20:30.Pastaba: Automobiliu iš Kauno į Varšuvos oro uostą reiktų išvykti ne vėliau kaip ~11:00 (įvertinus ~5 val. kelio ir 2 val. rezervą iki skrydžio).Atvykimas: Spalio 30 d. 20:30 Tiranoje. Automobilio atsiėmimas ir 1-oji nakvynė netoliese arba pakeliui.Grįžimas: Lapkričio 2 d. (pirmadienis), TIA 19:05 → WAW 21:10.Pastaba: Automobilis grąžinamas Tiranos oro uoste iki ~17:00. Vėliau – kelionė automobiliu Varšuva–Kaunas.3. Maršruto pobūdis ir apribojimaiPagrindinis tikslas: Gamtos objektai (nacionaliniai parkai, kanjonai, ežerai, pakrantės, panoraminiai keliai).Maršruto struktūra: Ratu (circular route), kiekvieną naktį nakvojant vis kitoje vietoje (iš viso 3 nakvynės).Sezoniškumas (Spalio pabaiga / Lapkričio pradžia):Trumpos dienos (sutemsta apie 17:00–17:30).Šiauriniai kalnų keliai (pvz., Theth ar Valbona) gali būti rizikingi dėl oro sąlygų ar sniego, todėl maršrutas turėtų orientuotis į Vidurio / Pietų Albaniją arba lengviau pasiekiamas šiaurines vietas (pvz., Škodrio ežeras, Komano užtvanka).Tempo apribojimai: Maksimalus važiavimo laikas per dieną – iki 3,5–4 valandų, kad liktų laiko šviesiu paros metu lankyti objektus.4. Užduotis AI modeliuiSugeneruok diena iš dienos maršrutą, įtraukiant:Konkrečias nakvynės vietas/miestus (1-a naktis penktadienį, 2-a naktis šeštadienį, 3-ia naktis sekmadienį).Lankytinus gamtos objektus kiekvieną dieną su optimaliais sustojimais (atsižvelgiant į trumpą dienos šviesą).Praktiškus patarimus: automobilio nuomos rekomendacijas 4 asmenims, eismo/kelių būklės ypatumus vėlyvą rudenį ir laiko planavimą Kaunas–Varšuva atstumui.

Later changes by the traveller (applied in this order; they override the original request and earlier changes):
- Berat mieste norim pamatyti ir Gorica tiltą. Apsvarstyk galimybę aplankyti Daiti express ir bovilla ežerą
- Trečią dieną vėl reikia toli važiuoti. Lieka ilga kelionės trukmė 4 dieną grįžti į oro uostą. Peržiūrėk siūlomas modifikacijas ir pakoreguok kelionės planą. Pirma naktis visdar tiranojeDay 2 (Sat, Oct 31): Central Lakes & UNESCO Heritage - Morning: Krujë Castle & Old Bazaar -> Drive to Belsh (Dumre Plateau) via SH2/SH3 (~85 km, 1.5h). - Midday: Coffee & lake view stop at Belsh Lake -> Drive to Berat (~45 km, 1h). - Afternoon: Lunch in Mangalem -> Berat Castle (Kala), Gorica Quarter, and Osumi River view before dark (~17:00). - Night 2: Berat. - Total Driving: ~130 km | ~2.5h.  Day 3 (Sun, Nov 1): Canyon, Mountain Pass & Coastal Riviera - Morning: Drive Berat to Osumi Canyon Viewpoints (Çorovodë) via SH72 (~55 km, 1.25h). - Midday: Drive Çorovodë -> Vlorë -> Llogara National Park (~115 km, 2.5h). - Afternoon: Lunch at Llogara Pass (1,027m) -> Short pine forest walk & Ionian Sea panorama -> Drive down to Vlorë/Radhimë coast (~30 km, 45m). - Night 3: Vlorë / Radhimë coast. - Total Driving: ~200 km | ~4.5h.  Day 4 (Mon, Nov 2): Coastal Lagoon & Departure - Morning: Drive Vlorë to Divjakë-Karavasta National Park via A2/SH4 (~65 km, 1.15h). - Midday: Karavasta Lagoon 360° View Tower, bird watching (Dalmatian Pelicans), trail walk, seafood lunch. - Afternoon: Drive Divjakë to Tirana Airport (TIA) (~90 km, 1.75h). Car return at TIA by 17:00. Flight TIA->WAW at 19:05. - Total Driving (Albania): ~155 km | ~2.75h.
- Atnaujink kelionės nakvynės vietas. pagal tai atnaujink ir žemėlapį bei žemėlapio nuorodas: Pirma naktis https://www.booking.com/hotel/al/apartament-tirana8.lt.html (Hanna Apartment, 51e už naktį). Antra naktis https://www.booking.com/hotel/al/dd-villa.lt.html (DD Villa, 61 už naktį). Trečia naktis https://www.booking.com/hotel/al/liro.lt.html (hotel liro - adults only, 117e už naktį). Viešbučių kaina aiški, atnaujink ir biudžeto dalį.  Skrydis kainavo 84e žmogui.
- Pridėk automobilio nuomos informaciją dalyje prie siūlomų nuomos bendrovių. Atnaujink biudžeto dalį, pridėdamas tikslią automobilio nuomos kainąPICK UP Tirana International Airport (TIA), Tirana, Albania October 30, 2026 21:00 VEHICLE TYPE VW TIGUAN or similar Full-Size SUV Automatic DROP OFF Tirana International Airport (TIA), Tirana, Albania November 2, 2026 17:00 ADD-ONS Additional Driver, Super Protective Insurance PAYMENT INFORMATION Estimated Total - €168
- Palik tik užsakytas apgyvendinimo vietas, išimk rekomenduojamas gyvenamas vietas

</details>

<details><summary><b>Atsakymas</b></summary>

```json
{
  "needed": true,
  "recommended_car_types": [
    {
      "car_type": "Kompaktinis visureigis (Dacia Duster, Škoda Karoq, VW T-Roc)",
      "why": "Pakankamai vietos 4 žmonėms ir bagažui, didesnė prošvaisa nelygiems/žvyruotiems ruožams (Osumo kanjono apžvalgos aikštelės, Beratas), ekonomiškos degalų sąnaudos trumpiems rudens maršrutams.",
      "avg_price_per_day_eur": 40,
      "avg_total_eur": 160
    },
    {
      "car_type": "Pilno dydžio visureigis (VW Tiguan, Hyundai Tucson, Nissan Qashqai)",
      "why": "Daugiausia vietos bagažui ir patogiausia 4 suaugusiems ilgesnėse atkarpose (Vlorė–Llogara perėja); tai klasė, kurią jau užsisakėte (VW Tiguan) – patikima pasirinktis rudens/žiemos sąlygoms kalnų perėjose.",
      "avg_price_per_day_eur": 55,
      "avg_total_eur": 220
    },
    {
      "car_type": "Kompaktinis sedanas/hečbekas (Škoda Octavia, VW Golf)",
      "why": "Pigiausias variantas, jei maršrutas apsiriboja asfaltuotais keliais; mažesnė prošvaisa mažiau tinkama Osumo kanjono ar kalnų ruožams, mažiau bagažo vietos 4 žmonėms.",
      "avg_price_per_day_eur": 30,
      "avg_total_eur": 120
    }
  ],
  "companies": [
    {
      "name": "Karruka Rent a Car",
      "pickup_location": "Tirana International Airport (TIA), Rinas – atvykimo salė",
      "rating": 4.9,
      "review_count": 1000,
      "review_source": "Google Maps",
      "car_class": "Pilno dydžio visureigis (SUV), 5 vietos",
      "price_estimate_eur": 180,
      "why": "Tiranos oro uosto klientų dažniausiai renkama vietinė įmonė – be depozito, minimalus popierizmas, draudimas įskaičiuotas į kainą.",
      "booking_url": "https://karrukarental.com/reservation/"
    },
    {
      "name": "Tirana Airport Rental Car",
      "pickup_location": "Tirana International Airport (TIA), Rinas",
      "rating": 4.7,
      "review_count": 1413,
      "review_source": "Google Maps",
      "car_class": "Kompaktinis/pilno dydžio visureigis, 5 vietos",
      "price_estimate_eur": 175,
      "why": "Nauji automobiliai su pilnu draudimu ir be depozito – patikimas ir geros kainos/kokybės santykio pasirinkimas 4 keliautojams.",
      "booking_url": "https://tiranaairportrentalcar.com/"
    },
    {
      "name": "Sixt",
      "pickup_location": "Tirana International Airport (TIA), nuomos centras prie terminalo",
      "rating": 4.1,
      "review_count": 4494,
      "review_source": "EasyTerra (8.2/10)",
      "car_class": "Visureigis (SUV), 5 vietos",
      "price_estimate_eur": 255,
      "why": "Tarptautinis prekės ženklas su aiškiai pažymėtu biuru oro uoste ir platesniu pagalbos kelyje tinklu – saugus pasirinkimas, jei svarbiau aptarnavimo nuspėjamumas nei mažiausia kaina.",
      "booking_url": "https://www.sixt.com/car-rental/albania/tirana/tirana-airport/"
    }
  ],
  "tips": [
    "Automobilis šiai kelionei jau užsakytas (VW Tiguan / pilno dydžio visureigis, atsiėmimas TIA spalio 30 d. 21:00, grąžinimas lapkričio 2 d. 17:00, su Papildomu vairuotoju ir Super Protective Insurance, iš viso €168) – aukščiau pateikti pasiūlymai skirti palyginimui arba atsarginiam variantui.",
    "Atsiėmimas vėlai vakare (21:00): būtina iš anksto patvirtinti, kad pasirinktos įmonės biuras tuo metu dirba – dauguma vietinių nuomotojų oro uoste veikia 24/7, bet verta gauti patvirtinimą el. paštu.",
    "Kalnų ir kaimo kelių ruožai (Llogara perėja, Osumo kanjono apžvalgos keliai) gali būti duobėti ar žvyruoti – didesnė prošvaisa (SUV) patogesnė nei sedanas.",
    "Degalų politika: patikrinti „pilnas-į-pilną“ sąlygą; dauguma vietinių įmonių nereikalauja depozito grynaisiais, tik kreditinės kortelės rezervacijos.",
    "Rudens/žiemos sąlygoms rekomenduojamas pilnas draudimas be išskaitos (kaip jau pasirinktas Super Protective Insurance) – kalnų keliuose po lietaus gali būti slidu."
  ]
}
```

</details>

### 2. Maistas ir barai — 10:00:40 ✅

- **Modelis:** `claude-haiku-4-5-20251001, claude-sonnet-5` · **Vykdė:** Native Claude (claude -p) · **Trukmė:** 353.9 s
- **Sistemos promptas:** `prompts/food.md`

<details><summary><b>Užklausa</b></summary>

**Trip requirements:**

```json
{
  "destination": "Albanija",
  "trip_type": "roundtrip",
  "start_date": "2026-10-30",
  "end_date": "2026-11-02",
  "travelers": 4,
  "budget_eur": null,
  "airport": "TIA",
  "return_flight_time": "19:05",
  "max_driving_hours_per_day": 4.0,
  "priorities": [
    "gamta"
  ],
  "language": "lt",
  "notes": "Ratu per Albaniją (TIA-TIA), kiekvieną naktį kita nakvynės vieta (3 nakvynės: penktadienį, šeštadienį, sekmadienį). Vengti šiaurinių kalnų kelių (Theth, Valbona) dėl rudens/žiemos oro rizikos — orientuotis į vidurio/pietų Albaniją arba lengviau pasiekiamas šiaurines vietas (Škodrio ežeras, Komano užtvanka). Trumpos dienos šviesos valandos (sutemsta ~17:00–17:30), pageidaujama važiuoti ne daugiau 3,5–4 val. per dieną. Nuomojamas automobilis turi tilpti 4 žmonėms ir bagažui, atsiimamas ir grąžinamas TIA (grąžinti iki ~17:00 lapkričio 2 d.). Papildoma logistika (ne pagrindinis Albanijos maršrutas): asmeninis automobilis Kaunas–Varšuva (WAW)–Kaunas; išvykimo skrydis WAW 18:30 → TIA 20:30 spalio 30 d. (iš Kauno išvykti ne vėliau ~11:00); grįžimo skrydis TIA 19:05 → WAW 21:10 lapkričio 2 d."
}
```

**Itinerary:**

```json
{
  "days": [
    {
      "number": 1,
      "title": "Atvykimas į Tiraną",
      "stops": [
        {
          "name": "Tiranos oro uostas (TIA)",
          "lat": 41.4147,
          "lon": 19.7206,
          "arrive": "20:30",
          "depart": "21:00",
          "maps_query": "Tirana International Airport Nënë Tereza, Albania",
          "google_maps_url": "https://www.google.com/maps/search/?api=1&query=Tirana%20International%20Airport%20N%C3%ABn%C3%AB%20Tereza%2C%20Albania",
          "notes": "Skrydis iš Varšuvos nusileidžia 20:30. Automobilio nuomos (VW Tiguan ar panašus visureigis, tinka 4 žmonėms ir bagažui, su Papildomo vairuotojo ir pilnos apsaugos draudimu) atsiėmimas 21:00. Tą pačią vietą reikės grąžinti automobilį lapkričio 2 d. iki 17:00.",
          "arrive_by": "car",
          "transit": ""
        },
        {
          "name": "Hanna Apartment",
          "lat": 41.3192,
          "lon": 19.8294,
          "arrive": "21:20",
          "depart": "21:20",
          "maps_query": "Apartament Tirana8, Rruga e Elbasanit, Tirana, Albania",
          "google_maps_url": "https://www.google.com/maps/search/?api=1&query=Apartament%20Tirana8%2C%20Rruga%20e%20Elbasanit%2C%20Tirana%2C%20Albania",
          "notes": "Pirma nakvynė – butas Rruga e Elbasanit, kondicionierius, nemokamas WiFi, tinka 4 žmonėms. Kelias nuo oro uosto apie 20 min, vėlai vakare eismas ramus.",
          "arrive_by": "car",
          "transit": ""
        }
      ],
      "driving_minutes": 20,
      "overnight_city": "Tirana"
    },
    {
      "number": 2,
      "title": "Krujė, Belšo ežeras ir Beratas",
      "stops": [
        {
          "name": "Krujos pilis ir Skenderbego muziejus bei Senasis bazaras",
          "lat": 41.5086,
          "lon": 19.7919,
          "arrive": "09:45",
          "depart": "10:30",
          "maps_query": "Kalaja e Krujës, Krujë, Albania",
          "google_maps_url": "https://www.google.com/maps/search/?api=1&query=Kalaja%20e%20Kruj%C3%ABs%2C%20Kruj%C3%AB%2C%20Albania",
          "notes": "Skenderbego muziejus pilies viduje, bilietas apie 200 lekų (~2 €). Žiemos darbo laikas apytiksliai 09:00–16:00 – darbo laiką verta pasitikrinti. Prie pilies – senasis bazaras su amatininkų dirbiniais ir suvenyrais.",
          "arrive_by": "car",
          "transit": ""
        },
        {
          "name": "Belšo ežeras (apžvalgos sustojimas)",
          "lat": 41.0931,
          "lon": 19.8828,
          "arrive": "12:02",
          "depart": "12:17",
          "maps_query": "Liqeni i Belshit, Belsh, Albania",
          "google_maps_url": "https://www.google.com/maps/search/?api=1&query=Liqeni%20i%20Belshit%2C%20Belsh%2C%20Albania",
          "notes": "Trumpas sustojimas pakeliui – gražus Dumrės plokščiakalnio ir ežerų vaizdas, proga kavai ir nuotraukai.",
          "arrive_by": "car",
          "transit": ""
        },
        {
          "name": "Pietūs „Lili Homemade Food“",
          "lat": 40.7064,
          "lon": 19.9513,
          "arrive": "13:54",
          "depart": "14:55",
          "maps_query": "Lili Homemade Food, Berat, Albania",
          "google_maps_url": "https://www.google.com/maps/search/?api=1&query=Lili%20Homemade%20Food%2C%20Berat%2C%20Albania",
          "notes": "Populiarus namų virtuvės restoranas Mangalemo kvartale, vietiniai patiekalai.",
          "arrive_by": "car",
          "transit": ""
        },
        {
          "name": "Mangalemo senasis kvartalas",
          "lat": 40.706,
          "lon": 19.951,
          "arrive": "14:55",
          "depart": "15:09",
          "maps_query": "Mangalem Quarter, Berat, Albania",
          "google_maps_url": "https://www.google.com/maps/search/?api=1&query=Mangalem%20Quarter%2C%20Berat%2C%20Albania",
          "notes": "Pasivaikščiojimas osmanų laikų gatvelėmis su garsiaisiais „tūkstančio langų“ namais.",
          "arrive_by": "walk",
          "transit": ""
        },
        {
          "name": "Berato pilis (Kalaja e Beratit)",
          "lat": 40.7014,
          "lon": 19.9447,
          "arrive": "15:29",
          "depart": "16:13",
          "maps_query": "Kalaja e Beratit, Berat, Albania",
          "google_maps_url": "https://www.google.com/maps/search/?api=1&query=Kalaja%20e%20Beratit%2C%20Berat%2C%20Albania",
          "notes": "Gyvenama pilis su bizantiškomis bažnyčiomis. Įėjimas į teritoriją laisvas, Onufrijaus muziejuje bilietas apie 200 lekų – darbo laiką verta pasitikrinti.",
          "arrive_by": "walk",
          "transit": ""
        },
        {
          "name": "Goricos tiltas ir kvartalas",
          "lat": 40.7021,
          "lon": 19.9497,
          "arrive": "16:38",
          "depart": "17:08",
          "maps_query": "Ura e Goricës, Berat, Albania",
          "google_maps_url": "https://www.google.com/maps/search/?api=1&query=Ura%20e%20Goric%C3%ABs%2C%20Berat%2C%20Albania",
          "notes": "Osmanų laikų akmeninis tiltas per Osumo upę – ypač gražus prieblandoje, puikus vaizdas į Mangalemą.",
          "arrive_by": "walk",
          "transit": ""
        },
        {
          "name": "DD Villa",
          "lat": 40.7057,
          "lon": 19.952,
          "arrive": "17:23",
          "depart": "17:23",
          "maps_query": "DD Villa, Rruga Antipatrea, Berat, Albania",
          "google_maps_url": "https://www.google.com/maps/search/?api=1&query=DD%20Villa%2C%20Rruga%20Antipatrea%2C%20Berat%2C%20Albania",
          "notes": "Nakvynė Berate – sodas, baras, pusryčiai, privatus parkavimas už papildomą mokestį.",
          "arrive_by": "walk",
          "transit": ""
        }
      ],
      "driving_minutes": 180,
      "overnight_city": "Berat"
    },
    {
      "number": 3,
      "title": "Osumio kanjonas ir Vlorės pakrantė",
      "stops": [
        {
          "name": "Osumio kanjono apžvalgos aikštelė",
          "lat": 40.5044,
          "lon": 20.227,
          "arrive": "10:15",
          "depart": "11:00",
          "maps_query": "Kanioni i Osumit, Çorovodë, Albania",
          "google_maps_url": "https://www.google.com/maps/search/?api=1&query=Kanioni%20i%20Osumit%2C%20%C3%87orovod%C3%AB%2C%20Albania",
          "notes": "Vienas gražiausių gamtos vaizdų kelyje – kanjono apžvalgos aikštelė prie kelio, patogi stovėjimo vieta.",
          "arrive_by": "car",
          "transit": ""
        },
        {
          "name": "Pietūs Vlorės marina",
          "lat": 40.458,
          "lon": 19.485,
          "arrive": "13:51",
          "depart": "14:51",
          "maps_query": "Marina e Vlorës, Vlorë, Albania",
          "google_maps_url": "https://www.google.com/maps/search/?api=1&query=Marina%20e%20Vlor%C3%ABs%2C%20Vlor%C3%AB%2C%20Albania",
          "notes": "Vlorės uosto promenadoje daug žuvies restoranų – pasirinkite bet kurį su šviežia dienos žuvimi.",
          "arrive_by": "car",
          "transit": ""
        },
        {
          "name": "Vlorės pakrantės promenada (Lungomare)",
          "lat": 40.458,
          "lon": 19.485,
          "arrive": "14:51",
          "depart": "15:51",
          "maps_query": "Lungomare, Vlorë, Albania",
          "google_maps_url": "https://www.google.com/maps/search/?api=1&query=Lungomare%2C%20Vlor%C3%AB%2C%20Albania",
          "notes": "Pasivaikščiojimas pakrante, vaizdas į Jonų jūrą ir Sazano salą.",
          "arrive_by": "walk",
          "transit": ""
        },
        {
          "name": "Hotel Liro – Adults Only",
          "lat": 40.455,
          "lon": 19.484,
          "arrive": "16:01",
          "depart": "16:01",
          "maps_query": "Hotel Liro Adults Only, Rruga Aleksandër Moisiu, Vlorë, Albania",
          "google_maps_url": "https://www.google.com/maps/search/?api=1&query=Hotel%20Liro%20Adults%20Only%2C%20Rruga%20Aleksand%C3%ABr%20Moisiu%2C%20Vlor%C3%AB%2C%20Albania",
          "notes": "Nakvynė Vlorėje – privatus paplūdimio ruožas, lauko baseinas, vaizdas į jūrą nuo balkono. Tik suaugusiems.",
          "arrive_by": "car",
          "transit": ""
        }
      ],
      "driving_minutes": 205,
      "overnight_city": "Vlorë"
    },
    {
      "number": 4,
      "title": "Divjakė-Karavasta ir išvykimas",
      "stops": [
        {
          "name": "Karavastos lagūnos Lankytojų centras ir apžvalgos bokštas",
          "lat": 40.979,
          "lon": 19.466,
          "arrive": "10:10",
          "depart": "13:20",
          "maps_query": "Qendra e Vizitorëve Divjakë-Karavasta, Divjakë, Albania",
          "google_maps_url": "https://www.google.com/maps/search/?api=1&query=Qendra%20e%20Vizitor%C3%ABve%20Divjak%C3%AB-Karavasta%2C%20Divjak%C3%AB%2C%20Albania",
          "notes": "Automobilį palikite Lankytojų centro aikštelėje – čia veda geras asfaltuotas/tvarkingas kelias, o čia pat yra apie 35 m aukščio apžvalgos bokštas su gražiu vaizdu į lagūną. Jei norite pasiekti giliau lagūnoje esantį bokštą, paskutinius 1–2 km (ir tiek pat atgal) reikia nueiti pėsčiomis – nuomotam automobiliui tas kelias po lietaus būna dumblinas ir netinkamas. Rudenį čia gerai matomi rausvieji pelikanai ir flamingai. Nedidelis mokestis automobiliui įvažiuojant į parką.",
          "arrive_by": "car",
          "transit": ""
        },
        {
          "name": "Pietūs Divjakės paplūdimyje",
          "lat": 40.9958,
          "lon": 19.4705,
          "arrive": "13:30",
          "depart": "14:30",
          "maps_query": "Plazhi i Divjakës, Divjakë, Albania",
          "google_maps_url": "https://www.google.com/maps/search/?api=1&query=Plazhi%20i%20Divjak%C3%ABs%2C%20Divjak%C3%AB%2C%20Albania",
          "notes": "Paplūdimio žuvies kioskai ir restoranėliai – šviežia žuvis ir jūros gėrybės.",
          "arrive_by": "car",
          "transit": ""
        },
        {
          "name": "Tiranos oro uostas (TIA) – automobilio grąžinimas ir skrydis namo",
          "lat": 41.4147,
          "lon": 19.7206,
          "arrive": "16:15",
          "depart": "19:05",
          "maps_query": "Tirana International Airport Nënë Tereza, Albania",
          "google_maps_url": "https://www.google.com/maps/search/?api=1&query=Tirana%20International%20Airport%20N%C3%ABn%C3%AB%20Tereza%2C%20Albania",
          "notes": "Automobilio grąžinimas (reikia iki 17:00) – atsargos laiko pakaks. Skrydis į Varšuvą išskrenda 19:05 – registracijai ir saugumo patikrai liks pakankamai laiko.",
          "arrive_by": "car",
          "transit": ""
        }
      ],
      "driving_minutes": 170,
      "overnight_city": "Nėra (skrydis namo)"
    }
  ]
}
```

Accommodation:
## Nakvynės vietos (tik užsakytos)

Keliautojas jau užsakė ir patvirtino konkrečius nakvynės objektus per booking.com nuorodas. Žemiau — tik šios užsakytos vietos, be papildomų alternatyvų.

### 1. Tirana (penktadienis, 2026-10-30 → šeštadienis, 2026-10-31)

**✅ Užsakyta — Hanna Apartment** — **51 €/naktį**
- Rruga e Elbasanit, Tirana. Įvertinimas 9.0/10 (186 atsiliepimai).
- Kondicionierius, nemokamas WiFi. Tinka 4 žmonėms (butas).
- Nuoroda: https://www.booking.com/hotel/al/apartament-tirana8.lt.html

### 2. Beratas (šeštadienis, 2026-10-31 → sekmadienis, 2026-11-01)

**✅ Užsakyta — DD Villa** — **61 €/naktį**
- Rruga Antipatrea, Beratas. Įvertinimas 8.8/10 (667 atsiliepimai).
- Sodas, baras, bendra svetainė, miesto vaizdas, pusryčiai (bufetas/à la carte), privatus parkavimas (už papildomą mokestį), restoranas vietoje.
- Nuoroda: https://www.booking.com/hotel/al/dd-villa.lt.html

### 3. Vlorė / Radhimė (sekmadienis, 2026-11-01 → pirmadienis, 2026-11-02)

**✅ Užsakyta — Hotel Liro – Adults Only** — **117 €/naktį**
- Aleksandër Moisiu Street, Vlorė. Įvertinimas 8.6/10 (1295 atsiliepimai).
- Privatus paplūdimio ruožas, lauko baseinas, nemokamas parkavimas, restoranas/baras, pusryčiai, vaizdas į jūrą nuo balkono. Autobusų stotelė priešais viešbutį.
- Nuoroda: https://www.booking.com/hotel/al/liro.lt.html
- ⚠️ Pastaba: "Adults Only" — jei grupėje yra vaikų, šią vietą reikėtų pakeisti.

**Biudžeto suma nakvynėms (3 naktys, visai grupei):** 51 + 61 + 117 = **229 €**

```json
{"picks": [
  {"city": "Tirana", "name": "Hanna Apartment", "checkin": "2026-10-30", "checkout": "2026-10-31", "price_per_night_eur": 51},
  {"city": "Berat", "name": "DD Villa", "checkin": "2026-10-31", "checkout": "2026-11-01", "price_per_night_eur": 61},
  {"city": "Vlorë", "name": "Hotel Liro - Adults Only", "checkin": "2026-11-01", "checkout": "2026-11-02", "price_per_night_eur": 117}
]}
```

</details>

<details><summary><b>Atsakymas</b></summary>

```json
{
  "eateries": [
    {
      "name": "Sofra e Ariut",
      "city": "Tirana",
      "day": 1,
      "near": "nakvynė Hanna Apartment (ta pati pačia Rruga e Elbasanit gatve)",
      "address": "Rruga e Elbasanit, Tiranë",
      "kind": "tradicinė taverna",
      "local_cuisine": true,
      "avg_price_eur": 13,
      "dinner_price_eur": 17,
      "must_try": [
        {
          "name": "Tavė kosi (ėriena su jogurto padažu)",
          "local_name": "Tavë kosi",
          "price_eur": 9,
          "commons_filename": "TAVE KOSI- agnello allo yogurt albanese.jpg"
        },
        {
          "name": "Įdaryti paprikos su varške",
          "local_name": "Speca me gjizë",
          "price_eur": 6,
          "commons_filename": "Dollma,Speca te mbushur me mish dhe oriz.jpg"
        },
        {
          "name": "Ėrienos kotletai ant grotelių",
          "local_name": "Copa qengji në skarë",
          "price_eur": 11,
          "commons_filename": "Liat Portal for Foodie Disorder - Homemade Lamb Chops with Rice and Grilled Vegetables.jpg"
        }
      ],
      "why": "Pačioje Rruga e Elbasanit gatvėje, 5 min pėsčiomis nuo nakvynės – patogu pirmą vakarą po vėlyvo atvykimo (nusileidus 20:30), siūlo tradicinius albanų patiekalus gražioje sodo aplinkoje; kai kurie atsiliepimai mini aukštesnes kainas, tad geriau rinktis pagrindinius patiekalus, ne žuvį."
    },
    {
      "name": "Snack Bar Derexhiku",
      "city": "Krujë",
      "day": 2,
      "near": "Krujos senasis bazaras ir pilis",
      "address": "Pazari i Vjetër (Senasis bazaras), Krujë",
      "kind": "byrektorė/kavinė bazare",
      "local_cuisine": true,
      "avg_price_eur": 4,
      "dinner_price_eur": 6,
      "must_try": [
        {
          "name": "Byrekas su spinatais ir varške",
          "local_name": "Byrek me spinaq",
          "price_eur": 2,
          "commons_filename": "Byrek from Kosovo.png"
        },
        {
          "name": "Molinio puodo troškinys",
          "local_name": "Tavë dheu",
          "price_eur": 5,
          "commons_filename": "Pasul me suxhuk në tavë të dheut.jpg"
        },
        {
          "name": "Vištienos file su garnyru",
          "local_name": "Filetë pule",
          "price_eur": 5,
          "commons_filename": ""
        }
      ],
      "why": "Mažas kioskas pačiame senojo bazaro centre – puikus greitas užkandis tarp pilies ir muziejaus lankymo, vietinių gerai vertinamas už skanų ir pigų byreką."
    },
    {
      "name": "Lili Homemade Food",
      "city": "Berat",
      "day": 2,
      "near": "Mangalemo senasis kvartalas (pietų sustojimas maršrute)",
      "address": "Rruga Llambi Guxhumani, Mangalem, Beratas",
      "kind": "šeimos namų virtuvė",
      "local_cuisine": true,
      "avg_price_eur": 12,
      "dinner_price_eur": 14,
      "must_try": [
        {
          "name": "Fërgesë (paprikų ir varškės troškinys)",
          "local_name": "Fërgesë",
          "price_eur": 6,
          "commons_filename": "Fërgesë dhe Tavë me oriz.jpg"
        },
        {
          "name": "Tavë kosi",
          "local_name": "Tavë kosi",
          "price_eur": 9,
          "commons_filename": "TAVE KOSI- agnello allo yogurt albanese.jpg"
        },
        {
          "name": "Įdarytos baklažanai",
          "local_name": "Patëllxhan i mbushur",
          "price_eur": 7,
          "commons_filename": ""
        }
      ],
      "why": "Lili ir jo žmona gamina patiekalus savo kieme pagal senelio receptus – vienas geriausiai įvertintų restoranų visoje Albanijoje (4.9/5, virš 2000 atsiliepimų); rezervacija WhatsApp būtina dėl mažo vietų skaičiaus."
    },
    {
      "name": "Guva Mangalem",
      "city": "Berat",
      "day": 2,
      "near": "nakvynė DD Villa, Mangalemo kvartalas",
      "address": "Rr. Llambi Guxhumani nr. 44, Beratas",
      "kind": "tradicinė taverna",
      "local_cuisine": true,
      "avg_price_eur": 10,
      "dinner_price_eur": 14,
      "must_try": [
        {
          "name": "Tavė kosi",
          "local_name": "Tavë kosi",
          "price_eur": 8,
          "commons_filename": "TAVE KOSI- agnello allo yogurt albanese.jpg"
        },
        {
          "name": "Įdarytos paprikos",
          "local_name": "Speca të mbushur",
          "price_eur": 5,
          "commons_filename": "Dollma,Speca te mbushur me mish dhe oriz.jpg"
        },
        {
          "name": "Byrekas",
          "local_name": "Byrek",
          "price_eur": 3,
          "commons_filename": "Byrek from Kosovo.png"
        }
      ],
      "why": "Vos keli žingsniai nuo DD Villa, terasa su vaizdu į Berato pilį ir Mangalemą, tradiciniai Berato patiekalai patiekiami klasikiniu stiliumi."
    },
    {
      "name": "Restaurant Salvadore",
      "city": "Vlorë",
      "day": 3,
      "near": "Vlorės marina (pietų sustojimas maršrute)",
      "address": "Rruga Pelivan Leskaj, Vlorë",
      "kind": "žuvies restoranas su savo turgumi",
      "local_cuisine": true,
      "avg_price_eur": 14,
      "dinner_price_eur": 17,
      "must_try": [
        {
          "name": "Žuvis ant grotelių",
          "local_name": "Peshk në skarë",
          "price_eur": 12,
          "commons_filename": "Grilled sea bass (7906690230).jpg"
        },
        {
          "name": "Keptas kalmaras",
          "local_name": "Kallamar i skuqur",
          "price_eur": 8,
          "commons_filename": "Calamari fritti - Enzo's 2026-05-05.jpg"
        },
        {
          "name": "Aštuonkojo salotos",
          "local_name": "Sallatë oktapodi",
          "price_eur": 9,
          "commons_filename": "Octopus salad .jpg"
        }
      ],
      "why": "Šeimos valdomas žuvies turgus su restoranu – žvejys savininkas pats pristato kasdienį laimikį, atsiliepimuose minimos sąžiningos kainos ir gausios porcijos."
    },
    {
      "name": "Taverna Djepi",
      "city": "Vlorë",
      "day": 3,
      "near": "nakvynė Hotel Liro – Adults Only, Rruga Aleksandër Moisiu",
      "address": "Rruga Aleksandër Moisiu, Vlorë",
      "kind": "šeimos taverna su jūros vaizdu",
      "local_cuisine": true,
      "avg_price_eur": 15,
      "dinner_price_eur": 19,
      "must_try": [
        {
          "name": "Keptas ešerys",
          "local_name": "Levrek në skarë",
          "price_eur": 13,
          "commons_filename": "Grilled sea bass (7906690230).jpg"
        },
        {
          "name": "Krevetės ant grotelių",
          "local_name": "Karkaleca në skarë",
          "price_eur": 14,
          "commons_filename": "2026-05-24 01 Grilled Spot prawns (Pandalus platyceros) - Victoria BC CAN.jpg"
        },
        {
          "name": "Aštuonkojis",
          "local_name": "Oktapod",
          "price_eur": 12,
          "commons_filename": "Octopus salad .jpg"
        }
      ],
      "why": "Toje pačioje gatvėje kaip Hotel Liro (apie 5 min.), terasa su saulėlydžio vaizdu į jūrą, 4.8/5 įvertinimas – šeimyniška atmosfera ir švelnios kainos."
    },
    {
      "name": "Restorant Pelikan",
      "city": "Divjakë",
      "day": 4,
      "near": "Divjakės paplūdimys (pietų sustojimas po Karavastos lagūnos)",
      "address": "Divjakë Qendër Plazh, Divjakë",
      "kind": "žuvies restoranėlis paplūdimyje",
      "local_cuisine": true,
      "avg_price_eur": 13,
      "dinner_price_eur": 15,
      "must_try": [
        {
          "name": "Keptas ešerys",
          "local_name": "Levrek në skarë",
          "price_eur": 11,
          "commons_filename": "Grilled sea bass (7906690230).jpg"
        },
        {
          "name": "Keptas kalmaras",
          "local_name": "Kallamar i skuqur",
          "price_eur": 8,
          "commons_filename": "Calamari fritti - Enzo's 2026-05-05.jpg"
        },
        {
          "name": "Ungurys (lagūnos specialitetas)",
          "local_name": "Ngjalë",
          "price_eur": 14,
          "commons_filename": ""
        }
      ],
      "why": "Vos žingsnis nuo paplūdimio ir lagūnos, lokalūs žvejai pristato ungurius ir žuvį tiesiai iš Karavastos lagūnos – 4.8/5 įvertinimas, puikus paskutinis pietų stotelė prieš skrydį."
    }
  ],
  "dishes": [
    {
      "name": "Tavė kosi (ėriena jogurto padaže)",
      "local_name": "Tavë kosi",
      "description": "Albanijos nacionalinis patiekalas – keptos ėrienos gabalai, apkepti jogurto ir kiaušinių padaže su ryžiais, iškepti orkaitėje.",
      "price_eur_min": 7,
      "price_eur_max": 11,
      "where_to_try": [
        "Sofra e Ariut",
        "Lili Homemade Food",
        "Guva Mangalem"
      ],
      "commons_filename": "TAVE KOSI- agnello allo yogurt albanese.jpg"
    },
    {
      "name": "Byrekas",
      "local_name": "Byrek",
      "description": "Plonos tešlos pyragas, dažniausiai su spinatais ir varške arba mėsa – populiarus pusryčių ir užkandžių patiekalas visoje šalyje.",
      "price_eur_min": 1,
      "price_eur_max": 3,
      "where_to_try": [
        "Snack Bar Derexhiku",
        "Guva Mangalem"
      ],
      "commons_filename": "Byrek from Kosovo.png"
    },
    {
      "name": "Fërgesė",
      "local_name": "Fërgesë",
      "description": "Troškintos paprikos su pomidorais ir vietine varške ar fetos tipo sūriu, patiekiama moliniame puode.",
      "price_eur_min": 5,
      "price_eur_max": 8,
      "where_to_try": [
        "Lili Homemade Food"
      ],
      "commons_filename": "Fërgesë dhe Tavë me oriz.jpg"
    },
    {
      "name": "Įdarytos paprikos",
      "local_name": "Speca të mbushur / Speca me gjizë",
      "description": "Keptos paprikos, įdarytos ryžiais ir mėsa arba vietine varške – klasikinis šeimyninis patiekalas.",
      "price_eur_min": 4,
      "price_eur_max": 6,
      "where_to_try": [
        "Sofra e Ariut",
        "Guva Mangalem"
      ],
      "commons_filename": "Dollma,Speca te mbushur me mish dhe oriz.jpg"
    },
    {
      "name": "Kepsniai (mėsos kukuliai)",
      "local_name": "Qofte",
      "description": "Grilinti mėsos kukuliai su mėtomis ir prieskoniais, patiekiami su jogurto padažu ar salotomis.",
      "price_eur_min": 4,
      "price_eur_max": 7,
      "where_to_try": [
        "Sofra e Ariut",
        "Guva Mangalem"
      ],
      "commons_filename": "Qofte shtëpie me lëng.jpg"
    },
    {
      "name": "Žuvis ant grotelių",
      "local_name": "Peshk në skarë",
      "description": "Šviežia Adrijos/Jonijos jūros žuvis (levrek, zarkadhël), kepta ant žarijų ir patiekiama su alyvuogių aliejumi ir citrina – Vlorės ir Divjakės pakrantės specialitetas.",
      "price_eur_min": 10,
      "price_eur_max": 18,
      "where_to_try": [
        "Restaurant Salvadore",
        "Taverna Djepi",
        "Restorant Pelikan"
      ],
      "commons_filename": "Grilled sea bass (7906690230).jpg"
    },
    {
      "name": "Trilece",
      "local_name": "Trilece",
      "description": "Trijų pienų tortas su karameliniu padažu – populiariausias albaniškas desertas, randamas beveik visose kavinėse.",
      "price_eur_min": 2,
      "price_eur_max": 4,
      "where_to_try": [
        "Sofra e Ariut",
        "Guva Mangalem",
        "Lili Homemade Food"
      ],
      "commons_filename": "Trileće cake and tea in Visegrad, Bosnia and Herzegovina.jpg"
    }
  ],
  "bars": [
    {
      "name": "Komiteti – Kafe Muzeum",
      "city": "Tirana",
      "day": 1,
      "address": "Rruga Fatmir Haxhiu 2, Tiranë",
      "near": "Tiranos centras, apie 15 min. nuo Hanna Apartment",
      "why_special": "Baras-muziejus, pilnas komunistinės epochos daiktų – uniformų, senų televizorių, radijo imtuvų ir net lubose kabančių grėblių, naudojamų kaip vyno taurių pakaba; unikali atmosfera ir plati raki pasirinkimo galimybė (Tripadvisor 4.3/5)."
    }
  ]
}
```

</details>

### 3. Planas B — 10:11:19 ✅

- **Modelis:** `claude-haiku-4-5-20251001, claude-sonnet-5` · **Vykdė:** Native Claude (claude -p) · **Trukmė:** 631.2 s
- **Sistemos promptas:** `prompts/plan_b.md`

<details><summary><b>Užklausa</b></summary>

**Trip requirements:**

```json
{
  "destination": "Albanija",
  "trip_type": "roundtrip",
  "start_date": "2026-10-30",
  "end_date": "2026-11-02",
  "travelers": 4,
  "budget_eur": null,
  "airport": "TIA",
  "return_flight_time": "19:05",
  "max_driving_hours_per_day": 4.0,
  "priorities": [
    "gamta"
  ],
  "language": "lt",
  "notes": "Ratu per Albaniją (TIA-TIA), kiekvieną naktį kita nakvynės vieta (3 nakvynės: penktadienį, šeštadienį, sekmadienį). Vengti šiaurinių kalnų kelių (Theth, Valbona) dėl rudens/žiemos oro rizikos — orientuotis į vidurio/pietų Albaniją arba lengviau pasiekiamas šiaurines vietas (Škodrio ežeras, Komano užtvanka). Trumpos dienos šviesos valandos (sutemsta ~17:00–17:30), pageidaujama važiuoti ne daugiau 3,5–4 val. per dieną. Nuomojamas automobilis turi tilpti 4 žmonėms ir bagažui, atsiimamas ir grąžinamas TIA (grąžinti iki ~17:00 lapkričio 2 d.). Papildoma logistika (ne pagrindinis Albanijos maršrutas): asmeninis automobilis Kaunas–Varšuva (WAW)–Kaunas; išvykimo skrydis WAW 18:30 → TIA 20:30 spalio 30 d. (iš Kauno išvykti ne vėliau ~11:00); grįžimo skrydis TIA 19:05 → WAW 21:10 lapkričio 2 d."
}
```

**Itinerary (main plan):**

```json
{
  "days": [
    {
      "number": 1,
      "title": "Atvykimas į Tiraną",
      "stops": [
        {
          "name": "Tiranos oro uostas (TIA)",
          "lat": 41.4147,
          "lon": 19.7206,
          "arrive": "20:30",
          "depart": "21:00",
          "maps_query": "Tirana International Airport Nënë Tereza, Albania",
          "google_maps_url": "https://www.google.com/maps/search/?api=1&query=Tirana%20International%20Airport%20N%C3%ABn%C3%AB%20Tereza%2C%20Albania",
          "notes": "Skrydis iš Varšuvos nusileidžia 20:30. Automobilio nuomos (VW Tiguan ar panašus visureigis, tinka 4 žmonėms ir bagažui, su Papildomo vairuotojo ir pilnos apsaugos draudimu) atsiėmimas 21:00. Tą pačią vietą reikės grąžinti automobilį lapkričio 2 d. iki 17:00.",
          "arrive_by": "car",
          "transit": ""
        },
        {
          "name": "Hanna Apartment",
          "lat": 41.3192,
          "lon": 19.8294,
          "arrive": "21:20",
          "depart": "21:20",
          "maps_query": "Apartament Tirana8, Rruga e Elbasanit, Tirana, Albania",
          "google_maps_url": "https://www.google.com/maps/search/?api=1&query=Apartament%20Tirana8%2C%20Rruga%20e%20Elbasanit%2C%20Tirana%2C%20Albania",
          "notes": "Pirma nakvynė – butas Rruga e Elbasanit, kondicionierius, nemokamas WiFi, tinka 4 žmonėms. Kelias nuo oro uosto apie 20 min, vėlai vakare eismas ramus.",
          "arrive_by": "car",
          "transit": ""
        }
      ],
      "driving_minutes": 20,
      "overnight_city": "Tirana"
    },
    {
      "number": 2,
      "title": "Krujė, Belšo ežeras ir Beratas",
      "stops": [
        {
          "name": "Krujos pilis ir Skenderbego muziejus bei Senasis bazaras",
          "lat": 41.5086,
          "lon": 19.7919,
          "arrive": "09:45",
          "depart": "10:30",
          "maps_query": "Kalaja e Krujës, Krujë, Albania",
          "google_maps_url": "https://www.google.com/maps/search/?api=1&query=Kalaja%20e%20Kruj%C3%ABs%2C%20Kruj%C3%AB%2C%20Albania",
          "notes": "Skenderbego muziejus pilies viduje, bilietas apie 200 lekų (~2 €). Žiemos darbo laikas apytiksliai 09:00–16:00 – darbo laiką verta pasitikrinti. Prie pilies – senasis bazaras su amatininkų dirbiniais ir suvenyrais.",
          "arrive_by": "car",
          "transit": ""
        },
        {
          "name": "Belšo ežeras (apžvalgos sustojimas)",
          "lat": 41.0931,
          "lon": 19.8828,
          "arrive": "12:02",
          "depart": "12:17",
          "maps_query": "Liqeni i Belshit, Belsh, Albania",
          "google_maps_url": "https://www.google.com/maps/search/?api=1&query=Liqeni%20i%20Belshit%2C%20Belsh%2C%20Albania",
          "notes": "Trumpas sustojimas pakeliui – gražus Dumrės plokščiakalnio ir ežerų vaizdas, proga kavai ir nuotraukai.",
          "arrive_by": "car",
          "transit": ""
        },
        {
          "name": "Pietūs „Lili Homemade Food“",
          "lat": 40.7064,
          "lon": 19.9513,
          "arrive": "13:54",
          "depart": "14:55",
          "maps_query": "Lili Homemade Food, Berat, Albania",
          "google_maps_url": "https://www.google.com/maps/search/?api=1&query=Lili%20Homemade%20Food%2C%20Berat%2C%20Albania",
          "notes": "Populiarus namų virtuvės restoranas Mangalemo kvartale, vietiniai patiekalai.",
          "arrive_by": "car",
          "transit": ""
        },
        {
          "name": "Mangalemo senasis kvartalas",
          "lat": 40.706,
          "lon": 19.951,
          "arrive": "14:55",
          "depart": "15:09",
          "maps_query": "Mangalem Quarter, Berat, Albania",
          "google_maps_url": "https://www.google.com/maps/search/?api=1&query=Mangalem%20Quarter%2C%20Berat%2C%20Albania",
          "notes": "Pasivaikščiojimas osmanų laikų gatvelėmis su garsiaisiais „tūkstančio langų“ namais.",
          "arrive_by": "walk",
          "transit": ""
        },
        {
          "name": "Berato pilis (Kalaja e Beratit)",
          "lat": 40.7014,
          "lon": 19.9447,
          "arrive": "15:29",
          "depart": "16:13",
          "maps_query": "Kalaja e Beratit, Berat, Albania",
          "google_maps_url": "https://www.google.com/maps/search/?api=1&query=Kalaja%20e%20Beratit%2C%20Berat%2C%20Albania",
          "notes": "Gyvenama pilis su bizantiškomis bažnyčiomis. Įėjimas į teritoriją laisvas, Onufrijaus muziejuje bilietas apie 200 lekų – darbo laiką verta pasitikrinti.",
          "arrive_by": "walk",
          "transit": ""
        },
        {
          "name": "Goricos tiltas ir kvartalas",
          "lat": 40.7021,
          "lon": 19.9497,
          "arrive": "16:38",
          "depart": "17:08",
          "maps_query": "Ura e Goricës, Berat, Albania",
          "google_maps_url": "https://www.google.com/maps/search/?api=1&query=Ura%20e%20Goric%C3%ABs%2C%20Berat%2C%20Albania",
          "notes": "Osmanų laikų akmeninis tiltas per Osumo upę – ypač gražus prieblandoje, puikus vaizdas į Mangalemą.",
          "arrive_by": "walk",
          "transit": ""
        },
        {
          "name": "DD Villa",
          "lat": 40.7057,
          "lon": 19.952,
          "arrive": "17:23",
          "depart": "17:23",
          "maps_query": "DD Villa, Rruga Antipatrea, Berat, Albania",
          "google_maps_url": "https://www.google.com/maps/search/?api=1&query=DD%20Villa%2C%20Rruga%20Antipatrea%2C%20Berat%2C%20Albania",
          "notes": "Nakvynė Berate – sodas, baras, pusryčiai, privatus parkavimas už papildomą mokestį.",
          "arrive_by": "walk",
          "transit": ""
        }
      ],
      "driving_minutes": 180,
      "overnight_city": "Berat"
    },
    {
      "number": 3,
      "title": "Osumio kanjonas ir Vlorės pakrantė",
      "stops": [
        {
          "name": "Osumio kanjono apžvalgos aikštelė",
          "lat": 40.5044,
          "lon": 20.227,
          "arrive": "10:15",
          "depart": "11:00",
          "maps_query": "Kanioni i Osumit, Çorovodë, Albania",
          "google_maps_url": "https://www.google.com/maps/search/?api=1&query=Kanioni%20i%20Osumit%2C%20%C3%87orovod%C3%AB%2C%20Albania",
          "notes": "Vienas gražiausių gamtos vaizdų kelyje – kanjono apžvalgos aikštelė prie kelio, patogi stovėjimo vieta.",
          "arrive_by": "car",
          "transit": ""
        },
        {
          "name": "Pietūs Vlorės marina",
          "lat": 40.458,
          "lon": 19.485,
          "arrive": "13:51",
          "depart": "14:51",
          "maps_query": "Marina e Vlorës, Vlorë, Albania",
          "google_maps_url": "https://www.google.com/maps/search/?api=1&query=Marina%20e%20Vlor%C3%ABs%2C%20Vlor%C3%AB%2C%20Albania",
          "notes": "Vlorės uosto promenadoje daug žuvies restoranų – pasirinkite bet kurį su šviežia dienos žuvimi.",
          "arrive_by": "car",
          "transit": ""
        },
        {
          "name": "Vlorės pakrantės promenada (Lungomare)",
          "lat": 40.458,
          "lon": 19.485,
          "arrive": "14:51",
          "depart": "15:51",
          "maps_query": "Lungomare, Vlorë, Albania",
          "google_maps_url": "https://www.google.com/maps/search/?api=1&query=Lungomare%2C%20Vlor%C3%AB%2C%20Albania",
          "notes": "Pasivaikščiojimas pakrante, vaizdas į Jonų jūrą ir Sazano salą.",
          "arrive_by": "walk",
          "transit": ""
        },
        {
          "name": "Hotel Liro – Adults Only",
          "lat": 40.455,
          "lon": 19.484,
          "arrive": "16:01",
          "depart": "16:01",
          "maps_query": "Hotel Liro Adults Only, Rruga Aleksandër Moisiu, Vlorë, Albania",
          "google_maps_url": "https://www.google.com/maps/search/?api=1&query=Hotel%20Liro%20Adults%20Only%2C%20Rruga%20Aleksand%C3%ABr%20Moisiu%2C%20Vlor%C3%AB%2C%20Albania",
          "notes": "Nakvynė Vlorėje – privatus paplūdimio ruožas, lauko baseinas, vaizdas į jūrą nuo balkono. Tik suaugusiems.",
          "arrive_by": "car",
          "transit": ""
        }
      ],
      "driving_minutes": 205,
      "overnight_city": "Vlorë"
    },
    {
      "number": 4,
      "title": "Divjakė-Karavasta ir išvykimas",
      "stops": [
        {
          "name": "Karavastos lagūnos Lankytojų centras ir apžvalgos bokštas",
          "lat": 40.979,
          "lon": 19.466,
          "arrive": "10:10",
          "depart": "13:20",
          "maps_query": "Qendra e Vizitorëve Divjakë-Karavasta, Divjakë, Albania",
          "google_maps_url": "https://www.google.com/maps/search/?api=1&query=Qendra%20e%20Vizitor%C3%ABve%20Divjak%C3%AB-Karavasta%2C%20Divjak%C3%AB%2C%20Albania",
          "notes": "Automobilį palikite Lankytojų centro aikštelėje – čia veda geras asfaltuotas/tvarkingas kelias, o čia pat yra apie 35 m aukščio apžvalgos bokštas su gražiu vaizdu į lagūną. Jei norite pasiekti giliau lagūnoje esantį bokštą, paskutinius 1–2 km (ir tiek pat atgal) reikia nueiti pėsčiomis – nuomotam automobiliui tas kelias po lietaus būna dumblinas ir netinkamas. Rudenį čia gerai matomi rausvieji pelikanai ir flamingai. Nedidelis mokestis automobiliui įvažiuojant į parką.",
          "arrive_by": "car",
          "transit": ""
        },
        {
          "name": "Pietūs Divjakės paplūdimyje",
          "lat": 40.9958,
          "lon": 19.4705,
          "arrive": "13:30",
          "depart": "14:30",
          "maps_query": "Plazhi i Divjakës, Divjakë, Albania",
          "google_maps_url": "https://www.google.com/maps/search/?api=1&query=Plazhi%20i%20Divjak%C3%ABs%2C%20Divjak%C3%AB%2C%20Albania",
          "notes": "Paplūdimio žuvies kioskai ir restoranėliai – šviežia žuvis ir jūros gėrybės.",
          "arrive_by": "car",
          "transit": ""
        },
        {
          "name": "Tiranos oro uostas (TIA) – automobilio grąžinimas ir skrydis namo",
          "lat": 41.4147,
          "lon": 19.7206,
          "arrive": "16:15",
          "depart": "19:05",
          "maps_query": "Tirana International Airport Nënë Tereza, Albania",
          "google_maps_url": "https://www.google.com/maps/search/?api=1&query=Tirana%20International%20Airport%20N%C3%ABn%C3%AB%20Tereza%2C%20Albania",
          "notes": "Automobilio grąžinimas (reikia iki 17:00) – atsargos laiko pakaks. Skrydis į Varšuvą išskrenda 19:05 – registracijai ir saugumo patikrai liks pakankamai laiko.",
          "arrive_by": "car",
          "transit": ""
        }
      ],
      "driving_minutes": 170,
      "overnight_city": "Nėra (skrydis namo)"
    }
  ]
}
```

**Weather for the trip dates:**

```json
{
  "generated_on": "2026-10-27",
  "days": [
    {
      "day": 1,
      "date": "2026-10-30",
      "place": "Tirana",
      "source": "forecast",
      "summary": "Debesuota",
      "temp_min_c": 10.1,
      "temp_max_c": 19.7,
      "precip_chance_pct": 11,
      "precip_mm": 0.1,
      "wind_max_kmh": 5.9
    },
    {
      "day": 2,
      "date": "2026-10-31",
      "place": "Berat",
      "source": "forecast",
      "summary": "Lietus",
      "temp_min_c": 9.5,
      "temp_max_c": 20.2,
      "precip_chance_pct": 25,
      "precip_mm": 1.6,
      "wind_max_kmh": 6.6
    },
    {
      "day": 3,
      "date": "2026-11-01",
      "place": "Vlorë",
      "source": "forecast",
      "summary": "Perkūnija",
      "temp_min_c": 14.0,
      "temp_max_c": 17.5,
      "precip_chance_pct": 54,
      "precip_mm": 14.7,
      "wind_max_kmh": 7.2
    },
    {
      "day": 4,
      "date": "2026-11-02",
      "place": "Nėra (skrydis namo)",
      "source": "forecast",
      "summary": "Perkūnija",
      "temp_min_c": 5.8,
      "temp_max_c": 14.2,
      "precip_chance_pct": 45,
      "precip_mm": 12.0,
      "wind_max_kmh": 9.5
    }
  ]
}
```

</details>

<details><summary><b>Atsakymas</b></summary>

```json
{
  "days": [
    {
      "day": 1,
      "needed": false
    },
    {
      "day": 2,
      "needed": true,
      "title": "Krujė ir Beratas – uždaros vietos nuo lietaus",
      "weather_sensitive": "Mangalemo kvartalo pasivaikščiojimas, Berato pilies teritorijos apžvalga ir Goricos tilto lankymas lauke užtrunka kelias valandas – per liūtį ar vėją tai nepatogu ir mažiau įdomu.",
      "tip": "Berato etnografijos muziejus žiemą (nuo lapkričio 1 d.) dirba antradieniais–šeštadieniais 9:00–16:00, spalio 31 d. darbo laiką verta patikrinti iš anksto telefonu; restoranas „Klea“ pilyje dirba visą dieną, tad tinka ir vėlesniam vizitui nepaisant oro.",
      "stops": [
        {
          "name": "Krujës pilis ir Skenderbego muziejus bei Senasis bazaras",
          "lat": 41.5086,
          "lon": 19.7919,
          "arrive": "09:45",
          "depart": "10:30",
          "arrive_by": "car",
          "maps_query": "Kalaja e Krujës, Krujë, Albania",
          "notes": "Skenderbego muziejus pilies viduje – nuo lietaus apsaugota vieta."
        },
        {
          "name": "Belšo ežero apžvalgos stotelė",
          "lat": 41.0931,
          "lon": 19.8828,
          "arrive": "12:02",
          "depart": "12:17",
          "arrive_by": "car",
          "maps_query": "Liqeni i Belshit, Belsh, Albania",
          "notes": "Trumpas sustojimas prie kelio – vaizdą galima pamatyti ir neišlipus iš automobilio, jei smarkiai lyja."
        },
        {
          "name": "Pietūs „Lili Homemade Food“",
          "lat": 40.7064,
          "lon": 19.9513,
          "arrive": "13:54",
          "depart": "14:55",
          "arrive_by": "car",
          "maps_query": "Lili Homemade Food, Berat, Albania",
          "notes": "Vidinis restoranas Mangalemo kvartale – nuo oro nepriklauso."
        },
        {
          "name": "Berato etnografijos muziejus",
          "lat": 40.7076,
          "lon": 19.9504,
          "arrive": "15:00",
          "depart": "15:45",
          "arrive_by": "walk",
          "maps_query": "National Ethnographic Museum, Berat, Albania",
          "notes": "Osmanų laikų namas-muziejus Mangaleme, kelios minutės nuo restorano – uždaros patalpos su tautiniais kostiumais ir buities eksponatais. Žiemą uždarytas pirmadieniais, darbo laiką patikrinti iš anksto."
        },
        {
          "name": "Restoranas „Klea“ Berato pilyje",
          "lat": 40.7014,
          "lon": 19.9447,
          "arrive": "16:05",
          "depart": "16:50",
          "arrive_by": "walk",
          "maps_query": "Restaurant Klea, Kalaja e Beratit, Berat, Albania",
          "notes": "Dengta terasa pilies viduje su vaizdu į Mangalemą ir Goricą – kava ar vietinis vynas net per lietų, darbo laikas nuo oro nepriklauso."
        },
        {
          "name": "DD Villa",
          "lat": 40.7057,
          "lon": 19.952,
          "arrive": "17:05",
          "depart": "17:05",
          "arrive_by": "walk",
          "maps_query": "DD Villa, Rruga Antipatrea, Berat, Albania",
          "notes": "Nakvynė Berate – kaip pagrindiniame plane."
        }
      ]
    },
    {
      "day": 3,
      "needed": true,
      "title": "Osumi ir Vlorė – vidinis variantas",
      "weather_sensitive": "Osumio kanjono apžvalgos aikštelė atvira ir vaizdas blogai matomas per rūką ar liūtį, o Vlorės pakrantės promenada (Lungomare) – ilgas pasivaikščiojimas lauke prie jūros, nepatogus vėjuotu ar lietingu metu.",
      "tip": "Perkūnijos metu kanjono aikštelėje nerekomenduojama ilgai stovėti dėl žaibo rizikos – pakanka trumpo sustojimo prie automobilio. Muradie mečetė Vlorėje lankoma nemokamai visą dieną, darbo laikas nuo oro ir savaitės dienos nepriklauso.",
      "stops": [
        {
          "name": "Osumio kanjono apžvalgos aikštelė (trumpas sustojimas)",
          "lat": 40.5044,
          "lon": 20.227,
          "arrive": "10:15",
          "depart": "10:30",
          "arrive_by": "car",
          "maps_query": "Kanioni i Osumit, Çorovodë, Albania",
          "notes": "Per lietų ar perkūniją – trumpas vaizdas nuo aikštelės, neišlipant toliau nuo automobilio."
        },
        {
          "name": "Pietūs Vlorės marina",
          "lat": 40.458,
          "lon": 19.485,
          "arrive": "13:40",
          "depart": "14:40",
          "arrive_by": "car",
          "maps_query": "Marina e Vlorës, Vlorë, Albania",
          "notes": "Tas pats restoranas kaip pagrindiniame plane – uždaros patalpos su vaizdu į uostą."
        },
        {
          "name": "Muradie mečetė (Xhamia Muradie)",
          "lat": 40.469049,
          "lon": 19.490932,
          "arrive": "14:55",
          "depart": "15:25",
          "arrive_by": "walk",
          "maps_query": "Xhamia Muradie, Vlorë, Albania",
          "notes": "XVI a. mečetė miesto centre, dengta – gera alternatyva lietingam orui, laisvai lankoma dienos metu."
        },
        {
          "name": "Hotel Liro – Adults Only",
          "lat": 40.455,
          "lon": 19.484,
          "arrive": "15:45",
          "depart": "15:45",
          "arrive_by": "walk",
          "maps_query": "Hotel Liro Adults Only, Rruga Aleksandër Moisiu, Vlorë, Albania",
          "notes": "Nakvynė Vlorėje – kaip pagrindiniame plane."
        }
      ]
    },
    {
      "day": 4,
      "needed": true,
      "title": "Karavasta ir Tirana lietaus dieną",
      "weather_sensitive": "Pelikanų apžvalgos bokšto takelis dumblėja po lietaus, o pietūs atvirame Divjakės paplūdimyje nepatogūs vėjuotu ar lietingu oru – abi vietos geriausios giedrą dieną.",
      "tip": "Lankytojų centro vidinė ekspozicija veikia nepriklausomai nuo oro, pirmadieniais apie 8:00–16:00 – paskambinti iš anksto pasitikrinti. Bunk'Art 2 dirba visas savaitės dienas 9:30–18:30.",
      "stops": [
        {
          "name": "Karavastos lagūnos Lankytojų centras (vidinė ekspozicija)",
          "lat": 40.979,
          "lon": 19.466,
          "arrive": "10:10",
          "depart": "11:30",
          "arrive_by": "car",
          "maps_query": "Qendra e Vizitorëve Divjakë-Karavasta, Divjakë, Albania",
          "notes": "Per lietų likti prie Lankytojų centro vidinės ekspozicijos – pelikanų ir flamingų nuotraukos, modeliai, filmas. Dumblėjantis takelis iki apžvalgos bokšto ir pietūs paplūdimyje šią dieną atšaukiami."
        },
        {
          "name": "Pietūs Pazari i Ri (Tiranos naujasis turgus)",
          "lat": 41.329,
          "lon": 19.8243,
          "arrive": "13:20",
          "depart": "14:20",
          "arrive_by": "car",
          "maps_query": "Pazari i Ri, Tiranë, Albania",
          "notes": "Dengta prekybos salė su vietinių produktų kioskais ir restoranėliais – gera pietų vieta per lietų, pakeliui į oro uostą."
        },
        {
          "name": "Bunk'Art 2",
          "lat": 41.327023,
          "lon": 19.819551,
          "arrive": "14:30",
          "depart": "15:45",
          "arrive_by": "walk",
          "maps_query": "Bunk'Art 2, Rruga Abdi Toptani, Tiranë, Albania",
          "notes": "Požeminis bunkerių muziejus miesto centre, visiškai apsaugotas nuo oro – apie 700 m pėsčiomis nuo turgaus."
        },
        {
          "name": "Tiranos oro uostas (TIA) – automobilio grąžinimas ir skrydis namo",
          "lat": 41.4147,
          "lon": 19.7206,
          "arrive": "16:20",
          "depart": "19:05",
          "arrive_by": "car",
          "maps_query": "Tirana International Airport Nënë Tereza, Albania",
          "notes": "Automobilio grąžinimas iki 17:00 – laiko pakanka. Skrydis į Varšuvą išskrenda 19:05."
        }
      ]
    }
  ]
}
```

</details>

### 4. Daiktai — 10:13:38 ✅

- **Modelis:** `claude-sonnet-5` · **Vykdė:** Native Claude (claude -p) · **Trukmė:** 99.1 s
- **Sistemos promptas:** `prompts/packing.md`

<details><summary><b>Užklausa</b></summary>

**Trip requirements:**

```json
{
  "destination": "Albanija",
  "trip_type": "roundtrip",
  "start_date": "2026-10-30",
  "end_date": "2026-11-02",
  "travelers": 4,
  "budget_eur": null,
  "airport": "TIA",
  "return_flight_time": "19:05",
  "max_driving_hours_per_day": 4.0,
  "priorities": [
    "gamta"
  ],
  "language": "lt",
  "notes": "Ratu per Albaniją (TIA-TIA), kiekvieną naktį kita nakvynės vieta (3 nakvynės: penktadienį, šeštadienį, sekmadienį). Vengti šiaurinių kalnų kelių (Theth, Valbona) dėl rudens/žiemos oro rizikos — orientuotis į vidurio/pietų Albaniją arba lengviau pasiekiamas šiaurines vietas (Škodrio ežeras, Komano užtvanka). Trumpos dienos šviesos valandos (sutemsta ~17:00–17:30), pageidaujama važiuoti ne daugiau 3,5–4 val. per dieną. Nuomojamas automobilis turi tilpti 4 žmonėms ir bagažui, atsiimamas ir grąžinamas TIA (grąžinti iki ~17:00 lapkričio 2 d.). Papildoma logistika (ne pagrindinis Albanijos maršrutas): asmeninis automobilis Kaunas–Varšuva (WAW)–Kaunas; išvykimo skrydis WAW 18:30 → TIA 20:30 spalio 30 d. (iš Kauno išvykti ne vėliau ~11:00); grįžimo skrydis TIA 19:05 → WAW 21:10 lapkričio 2 d."
}
```

Original request:
Štai susistemintas ir detalus reikalavimų sąrašas (promptas), kurį galite pateikti AI modeliui, kad jis sugeneruotų tikslų ir įgyvendinamą kelionės maršrutą:Reikalavimai AI: Trumpos 3 dienų kelionės automobiliais ir lėktuvu maršrutas Albanijoje1. Bendra informacija ir keliautojaiKeliautojų skaičius: 4 suaugę asmenys.Transportas:Asmeninis automobilis: Kaunas–Varšuva (WAW)–Kaunas.Nuomojamas automobilis: Tiranos oro uostas (TIA) – ratu per Albaniją – TIA (reikia vietos 4 žmonėms ir bagažui).2. Skrydžių ir logistikos laikaiIšskridimas: Spalio 30 d. (penktadienis), WAW 18:30 → TIA 20:30.Pastaba: Automobiliu iš Kauno į Varšuvos oro uostą reiktų išvykti ne vėliau kaip ~11:00 (įvertinus ~5 val. kelio ir 2 val. rezervą iki skrydžio).Atvykimas: Spalio 30 d. 20:30 Tiranoje. Automobilio atsiėmimas ir 1-oji nakvynė netoliese arba pakeliui.Grįžimas: Lapkričio 2 d. (pirmadienis), TIA 19:05 → WAW 21:10.Pastaba: Automobilis grąžinamas Tiranos oro uoste iki ~17:00. Vėliau – kelionė automobiliu Varšuva–Kaunas.3. Maršruto pobūdis ir apribojimaiPagrindinis tikslas: Gamtos objektai (nacionaliniai parkai, kanjonai, ežerai, pakrantės, panoraminiai keliai).Maršruto struktūra: Ratu (circular route), kiekvieną naktį nakvojant vis kitoje vietoje (iš viso 3 nakvynės).Sezoniškumas (Spalio pabaiga / Lapkričio pradžia):Trumpos dienos (sutemsta apie 17:00–17:30).Šiauriniai kalnų keliai (pvz., Theth ar Valbona) gali būti rizikingi dėl oro sąlygų ar sniego, todėl maršrutas turėtų orientuotis į Vidurio / Pietų Albaniją arba lengviau pasiekiamas šiaurines vietas (pvz., Škodrio ežeras, Komano užtvanka).Tempo apribojimai: Maksimalus važiavimo laikas per dieną – iki 3,5–4 valandų, kad liktų laiko šviesiu paros metu lankyti objektus.4. Užduotis AI modeliuiSugeneruok diena iš dienos maršrutą, įtraukiant:Konkrečias nakvynės vietas/miestus (1-a naktis penktadienį, 2-a naktis šeštadienį, 3-ia naktis sekmadienį).Lankytinus gamtos objektus kiekvieną dieną su optimaliais sustojimais (atsižvelgiant į trumpą dienos šviesą).Praktiškus patarimus: automobilio nuomos rekomendacijas 4 asmenims, eismo/kelių būklės ypatumus vėlyvą rudenį ir laiko planavimą Kaunas–Varšuva atstumui.

Later changes by the traveller (applied in this order; they override the original request and earlier changes):
- Berat mieste norim pamatyti ir Gorica tiltą. Apsvarstyk galimybę aplankyti Daiti express ir bovilla ežerą
- Trečią dieną vėl reikia toli važiuoti. Lieka ilga kelionės trukmė 4 dieną grįžti į oro uostą. Peržiūrėk siūlomas modifikacijas ir pakoreguok kelionės planą. Pirma naktis visdar tiranojeDay 2 (Sat, Oct 31): Central Lakes & UNESCO Heritage - Morning: Krujë Castle & Old Bazaar -> Drive to Belsh (Dumre Plateau) via SH2/SH3 (~85 km, 1.5h). - Midday: Coffee & lake view stop at Belsh Lake -> Drive to Berat (~45 km, 1h). - Afternoon: Lunch in Mangalem -> Berat Castle (Kala), Gorica Quarter, and Osumi River view before dark (~17:00). - Night 2: Berat. - Total Driving: ~130 km | ~2.5h.  Day 3 (Sun, Nov 1): Canyon, Mountain Pass & Coastal Riviera - Morning: Drive Berat to Osumi Canyon Viewpoints (Çorovodë) via SH72 (~55 km, 1.25h). - Midday: Drive Çorovodë -> Vlorë -> Llogara National Park (~115 km, 2.5h). - Afternoon: Lunch at Llogara Pass (1,027m) -> Short pine forest walk & Ionian Sea panorama -> Drive down to Vlorë/Radhimë coast (~30 km, 45m). - Night 3: Vlorë / Radhimë coast. - Total Driving: ~200 km | ~4.5h.  Day 4 (Mon, Nov 2): Coastal Lagoon & Departure - Morning: Drive Vlorë to Divjakë-Karavasta National Park via A2/SH4 (~65 km, 1.15h). - Midday: Karavasta Lagoon 360° View Tower, bird watching (Dalmatian Pelicans), trail walk, seafood lunch. - Afternoon: Drive Divjakë to Tirana Airport (TIA) (~90 km, 1.75h). Car return at TIA by 17:00. Flight TIA->WAW at 19:05. - Total Driving (Albania): ~155 km | ~2.75h.
- Atnaujink kelionės nakvynės vietas. pagal tai atnaujink ir žemėlapį bei žemėlapio nuorodas: Pirma naktis https://www.booking.com/hotel/al/apartament-tirana8.lt.html (Hanna Apartment, 51e už naktį). Antra naktis https://www.booking.com/hotel/al/dd-villa.lt.html (DD Villa, 61 už naktį). Trečia naktis https://www.booking.com/hotel/al/liro.lt.html (hotel liro - adults only, 117e už naktį). Viešbučių kaina aiški, atnaujink ir biudžeto dalį.  Skrydis kainavo 84e žmogui.
- Pridėk automobilio nuomos informaciją dalyje prie siūlomų nuomos bendrovių. Atnaujink biudžeto dalį, pridėdamas tikslią automobilio nuomos kainąPICK UP Tirana International Airport (TIA), Tirana, Albania October 30, 2026 21:00 VEHICLE TYPE VW TIGUAN or similar Full-Size SUV Automatic DROP OFF Tirana International Airport (TIA), Tirana, Albania November 2, 2026 17:00 ADD-ONS Additional Driver, Super Protective Insurance PAYMENT INFORMATION Estimated Total - €168
- Palik tik užsakytas apgyvendinimo vietas, išimk rekomenduojamas gyvenamas vietas

**Itinerary:**

```json
{
  "days": [
    {
      "number": 1,
      "title": "Atvykimas į Tiraną",
      "stops": [
        {
          "name": "Tiranos oro uostas (TIA)",
          "lat": 41.4147,
          "lon": 19.7206,
          "arrive": "20:30",
          "depart": "21:00",
          "maps_query": "Tirana International Airport Nënë Tereza, Albania",
          "google_maps_url": "https://www.google.com/maps/search/?api=1&query=Tirana%20International%20Airport%20N%C3%ABn%C3%AB%20Tereza%2C%20Albania",
          "notes": "Skrydis iš Varšuvos nusileidžia 20:30. Automobilio nuomos (VW Tiguan ar panašus visureigis, tinka 4 žmonėms ir bagažui, su Papildomo vairuotojo ir pilnos apsaugos draudimu) atsiėmimas 21:00. Tą pačią vietą reikės grąžinti automobilį lapkričio 2 d. iki 17:00.",
          "arrive_by": "car",
          "transit": ""
        },
        {
          "name": "Hanna Apartment",
          "lat": 41.3192,
          "lon": 19.8294,
          "arrive": "21:20",
          "depart": "21:20",
          "maps_query": "Apartament Tirana8, Rruga e Elbasanit, Tirana, Albania",
          "google_maps_url": "https://www.google.com/maps/search/?api=1&query=Apartament%20Tirana8%2C%20Rruga%20e%20Elbasanit%2C%20Tirana%2C%20Albania",
          "notes": "Pirma nakvynė – butas Rruga e Elbasanit, kondicionierius, nemokamas WiFi, tinka 4 žmonėms. Kelias nuo oro uosto apie 20 min, vėlai vakare eismas ramus.",
          "arrive_by": "car",
          "transit": ""
        }
      ],
      "driving_minutes": 20,
      "overnight_city": "Tirana"
    },
    {
      "number": 2,
      "title": "Krujė, Belšo ežeras ir Beratas",
      "stops": [
        {
          "name": "Krujos pilis ir Skenderbego muziejus bei Senasis bazaras",
          "lat": 41.5086,
          "lon": 19.7919,
          "arrive": "09:45",
          "depart": "10:30",
          "maps_query": "Kalaja e Krujës, Krujë, Albania",
          "google_maps_url": "https://www.google.com/maps/search/?api=1&query=Kalaja%20e%20Kruj%C3%ABs%2C%20Kruj%C3%AB%2C%20Albania",
          "notes": "Skenderbego muziejus pilies viduje, bilietas apie 200 lekų (~2 €). Žiemos darbo laikas apytiksliai 09:00–16:00 – darbo laiką verta pasitikrinti. Prie pilies – senasis bazaras su amatininkų dirbiniais ir suvenyrais.",
          "arrive_by": "car",
          "transit": ""
        },
        {
          "name": "Belšo ežeras (apžvalgos sustojimas)",
          "lat": 41.0931,
          "lon": 19.8828,
          "arrive": "12:02",
          "depart": "12:17",
          "maps_query": "Liqeni i Belshit, Belsh, Albania",
          "google_maps_url": "https://www.google.com/maps/search/?api=1&query=Liqeni%20i%20Belshit%2C%20Belsh%2C%20Albania",
          "notes": "Trumpas sustojimas pakeliui – gražus Dumrės plokščiakalnio ir ežerų vaizdas, proga kavai ir nuotraukai.",
          "arrive_by": "car",
          "transit": ""
        },
        {
          "name": "Pietūs „Lili Homemade Food“",
          "lat": 40.7064,
          "lon": 19.9513,
          "arrive": "13:54",
          "depart": "14:55",
          "maps_query": "Lili Homemade Food, Berat, Albania",
          "google_maps_url": "https://www.google.com/maps/search/?api=1&query=Lili%20Homemade%20Food%2C%20Berat%2C%20Albania",
          "notes": "Populiarus namų virtuvės restoranas Mangalemo kvartale, vietiniai patiekalai.",
          "arrive_by": "car",
          "transit": ""
        },
        {
          "name": "Mangalemo senasis kvartalas",
          "lat": 40.706,
          "lon": 19.951,
          "arrive": "14:55",
          "depart": "15:09",
          "maps_query": "Mangalem Quarter, Berat, Albania",
          "google_maps_url": "https://www.google.com/maps/search/?api=1&query=Mangalem%20Quarter%2C%20Berat%2C%20Albania",
          "notes": "Pasivaikščiojimas osmanų laikų gatvelėmis su garsiaisiais „tūkstančio langų“ namais.",
          "arrive_by": "walk",
          "transit": ""
        },
        {
          "name": "Berato pilis (Kalaja e Beratit)",
          "lat": 40.7014,
          "lon": 19.9447,
          "arrive": "15:29",
          "depart": "16:13",
          "maps_query": "Kalaja e Beratit, Berat, Albania",
          "google_maps_url": "https://www.google.com/maps/search/?api=1&query=Kalaja%20e%20Beratit%2C%20Berat%2C%20Albania",
          "notes": "Gyvenama pilis su bizantiškomis bažnyčiomis. Įėjimas į teritoriją laisvas, Onufrijaus muziejuje bilietas apie 200 lekų – darbo laiką verta pasitikrinti.",
          "arrive_by": "walk",
          "transit": ""
        },
        {
          "name": "Goricos tiltas ir kvartalas",
          "lat": 40.7021,
          "lon": 19.9497,
          "arrive": "16:38",
          "depart": "17:08",
          "maps_query": "Ura e Goricës, Berat, Albania",
          "google_maps_url": "https://www.google.com/maps/search/?api=1&query=Ura%20e%20Goric%C3%ABs%2C%20Berat%2C%20Albania",
          "notes": "Osmanų laikų akmeninis tiltas per Osumo upę – ypač gražus prieblandoje, puikus vaizdas į Mangalemą.",
          "arrive_by": "walk",
          "transit": ""
        },
        {
          "name": "DD Villa",
          "lat": 40.7057,
          "lon": 19.952,
          "arrive": "17:23",
          "depart": "17:23",
          "maps_query": "DD Villa, Rruga Antipatrea, Berat, Albania",
          "google_maps_url": "https://www.google.com/maps/search/?api=1&query=DD%20Villa%2C%20Rruga%20Antipatrea%2C%20Berat%2C%20Albania",
          "notes": "Nakvynė Berate – sodas, baras, pusryčiai, privatus parkavimas už papildomą mokestį.",
          "arrive_by": "walk",
          "transit": ""
        }
      ],
      "driving_minutes": 180,
      "overnight_city": "Berat"
    },
    {
      "number": 3,
      "title": "Osumio kanjonas ir Vlorės pakrantė",
      "stops": [
        {
          "name": "Osumio kanjono apžvalgos aikštelė",
          "lat": 40.5044,
          "lon": 20.227,
          "arrive": "10:15",
          "depart": "11:00",
          "maps_query": "Kanioni i Osumit, Çorovodë, Albania",
          "google_maps_url": "https://www.google.com/maps/search/?api=1&query=Kanioni%20i%20Osumit%2C%20%C3%87orovod%C3%AB%2C%20Albania",
          "notes": "Vienas gražiausių gamtos vaizdų kelyje – kanjono apžvalgos aikštelė prie kelio, patogi stovėjimo vieta.",
          "arrive_by": "car",
          "transit": ""
        },
        {
          "name": "Pietūs Vlorės marina",
          "lat": 40.458,
          "lon": 19.485,
          "arrive": "13:51",
          "depart": "14:51",
          "maps_query": "Marina e Vlorës, Vlorë, Albania",
          "google_maps_url": "https://www.google.com/maps/search/?api=1&query=Marina%20e%20Vlor%C3%ABs%2C%20Vlor%C3%AB%2C%20Albania",
          "notes": "Vlorės uosto promenadoje daug žuvies restoranų – pasirinkite bet kurį su šviežia dienos žuvimi.",
          "arrive_by": "car",
          "transit": ""
        },
        {
          "name": "Vlorės pakrantės promenada (Lungomare)",
          "lat": 40.458,
          "lon": 19.485,
          "arrive": "14:51",
          "depart": "15:51",
          "maps_query": "Lungomare, Vlorë, Albania",
          "google_maps_url": "https://www.google.com/maps/search/?api=1&query=Lungomare%2C%20Vlor%C3%AB%2C%20Albania",
          "notes": "Pasivaikščiojimas pakrante, vaizdas į Jonų jūrą ir Sazano salą.",
          "arrive_by": "walk",
          "transit": ""
        },
        {
          "name": "Hotel Liro – Adults Only",
          "lat": 40.455,
          "lon": 19.484,
          "arrive": "16:01",
          "depart": "16:01",
          "maps_query": "Hotel Liro Adults Only, Rruga Aleksandër Moisiu, Vlorë, Albania",
          "google_maps_url": "https://www.google.com/maps/search/?api=1&query=Hotel%20Liro%20Adults%20Only%2C%20Rruga%20Aleksand%C3%ABr%20Moisiu%2C%20Vlor%C3%AB%2C%20Albania",
          "notes": "Nakvynė Vlorėje – privatus paplūdimio ruožas, lauko baseinas, vaizdas į jūrą nuo balkono. Tik suaugusiems.",
          "arrive_by": "car",
          "transit": ""
        }
      ],
      "driving_minutes": 205,
      "overnight_city": "Vlorë"
    },
    {
      "number": 4,
      "title": "Divjakė-Karavasta ir išvykimas",
      "stops": [
        {
          "name": "Karavastos lagūnos Lankytojų centras ir apžvalgos bokštas",
          "lat": 40.979,
          "lon": 19.466,
          "arrive": "10:10",
          "depart": "13:20",
          "maps_query": "Qendra e Vizitorëve Divjakë-Karavasta, Divjakë, Albania",
          "google_maps_url": "https://www.google.com/maps/search/?api=1&query=Qendra%20e%20Vizitor%C3%ABve%20Divjak%C3%AB-Karavasta%2C%20Divjak%C3%AB%2C%20Albania",
          "notes": "Automobilį palikite Lankytojų centro aikštelėje – čia veda geras asfaltuotas/tvarkingas kelias, o čia pat yra apie 35 m aukščio apžvalgos bokštas su gražiu vaizdu į lagūną. Jei norite pasiekti giliau lagūnoje esantį bokštą, paskutinius 1–2 km (ir tiek pat atgal) reikia nueiti pėsčiomis – nuomotam automobiliui tas kelias po lietaus būna dumblinas ir netinkamas. Rudenį čia gerai matomi rausvieji pelikanai ir flamingai. Nedidelis mokestis automobiliui įvažiuojant į parką.",
          "arrive_by": "car",
          "transit": ""
        },
        {
          "name": "Pietūs Divjakės paplūdimyje",
          "lat": 40.9958,
          "lon": 19.4705,
          "arrive": "13:30",
          "depart": "14:30",
          "maps_query": "Plazhi i Divjakës, Divjakë, Albania",
          "google_maps_url": "https://www.google.com/maps/search/?api=1&query=Plazhi%20i%20Divjak%C3%ABs%2C%20Divjak%C3%AB%2C%20Albania",
          "notes": "Paplūdimio žuvies kioskai ir restoranėliai – šviežia žuvis ir jūros gėrybės.",
          "arrive_by": "car",
          "transit": ""
        },
        {
          "name": "Tiranos oro uostas (TIA) – automobilio grąžinimas ir skrydis namo",
          "lat": 41.4147,
          "lon": 19.7206,
          "arrive": "16:15",
          "depart": "19:05",
          "maps_query": "Tirana International Airport Nënë Tereza, Albania",
          "google_maps_url": "https://www.google.com/maps/search/?api=1&query=Tirana%20International%20Airport%20N%C3%ABn%C3%AB%20Tereza%2C%20Albania",
          "notes": "Automobilio grąžinimas (reikia iki 17:00) – atsargos laiko pakaks. Skrydis į Varšuvą išskrenda 19:05 – registracijai ir saugumo patikrai liks pakankamai laiko.",
          "arrive_by": "car",
          "transit": ""
        }
      ],
      "driving_minutes": 170,
      "overnight_city": "Nėra (skrydis namo)"
    }
  ]
}
```

**Forecast:**

```json
{
  "generated_on": "2026-10-27",
  "days": [
    {
      "day": 1,
      "date": "2026-10-30",
      "place": "Tirana",
      "source": "forecast",
      "summary": "Debesuota",
      "temp_min_c": 10.1,
      "temp_max_c": 19.7,
      "precip_chance_pct": 11,
      "precip_mm": 0.1,
      "wind_max_kmh": 5.9
    },
    {
      "day": 2,
      "date": "2026-10-31",
      "place": "Berat",
      "source": "forecast",
      "summary": "Lietus",
      "temp_min_c": 9.5,
      "temp_max_c": 20.2,
      "precip_chance_pct": 25,
      "precip_mm": 1.6,
      "wind_max_kmh": 6.6
    },
    {
      "day": 3,
      "date": "2026-11-01",
      "place": "Vlorë",
      "source": "forecast",
      "summary": "Perkūnija",
      "temp_min_c": 14.0,
      "temp_max_c": 17.5,
      "precip_chance_pct": 54,
      "precip_mm": 14.7,
      "wind_max_kmh": 7.2
    },
    {
      "day": 4,
      "date": "2026-11-02",
      "place": "Nėra (skrydis namo)",
      "source": "forecast",
      "summary": "Perkūnija",
      "temp_min_c": 5.8,
      "temp_max_c": 14.2,
      "precip_chance_pct": 45,
      "precip_mm": 12.0,
      "wind_max_kmh": 9.5
    }
  ]
}
```

Rental car: true

</details>

<details><summary><b>Atsakymas</b></summary>

```json
{
  "baggage": "Tik rankinis bagažas (vienas kelioninis krepšys/lagaminas ~10 kg + asmeninis daiktas kiekvienam) – trumpa 3 nakvynių kelionė, skrydis WAW–TIA–WAW.",
  "categories": [
    {
      "name": "Dokumentai ir pinigai",
      "items": [
        {
          "name": "Asmens tapatybės kortelė arba pasas",
          "note": "Albanija leidžia atvykti ES piliečiams su ID kortele"
        },
        {
          "name": "Vairuotojo pažymėjimas",
          "note": "automobilio nuomai TIA"
        },
        {
          "name": "Kreditinė kortelė pagrindinio vairuotojo vardu",
          "note": "automobilio nuomos depozitui (~168 €)"
        },
        {
          "name": "Kelionės/sveikatos draudimas",
          "note": "Albanija ne ES – Europos sveikatos draudimo kortelė negalioja"
        },
        {
          "name": "Lėktuvo bilietai ir viešbučių rezervacijos",
          "note": "Hanna Apartment, DD Villa, Hotel Liro – PDF/telefone"
        },
        {
          "name": "Grynieji – eurai ir keli tūkstančiai Albanijos lekų",
          "note": "pilių bilietams, parkavimui Karavastoje, smulkiems pirkiniams"
        }
      ]
    },
    {
      "name": "Drabužiai",
      "items": [
        {
          "name": "Lengvas vandeniui atsparus lietpaltis ar striukė su gobtuvu",
          "note": "lietaus tikimybė 25–54% 2–4 dienomis"
        },
        {
          "name": "Kompaktiškas skėtis",
          "note": "trumpiems sustojimams prie pilių"
        },
        {
          "name": "Šiltesnis flisas ar megztinis vakarams",
          "note": "nakties temperatūra krinta iki ~6–10°C"
        },
        {
          "name": "Ilgomis rankovėmis marškinėliai/palaidinės sluoksniavimui",
          "note": "3 dienos, dienos temp. 14–20°C"
        },
        {
          "name": "Džinsai/kelnės, vienas rezervinis komplektas",
          "note": ""
        },
        {
          "name": "Kepurė ar snapelis bei lengvas šalikas",
          "note": "vėjas pakrantėje Vlorėje"
        }
      ]
    },
    {
      "name": "Avalynė",
      "items": [
        {
          "name": "Patogūs, įmindyti kelioniniai batai",
          "note": "Krujos, Berato akmenimis grįstos gatvelės, Gorica tiltas"
        },
        {
          "name": "Vandeniui atsparūs/purvui tinkami bateliai",
          "note": "takelis prie Karavastos bokšto po lietaus"
        }
      ]
    },
    {
      "name": "Higiena (rankiniam bagažui)",
      "items": [
        {
          "name": "Dantų šepetėlis, pasta, dezodorantas",
          "note": ""
        },
        {
          "name": "Šampūnas/kremai ≤100 ml talpyklose",
          "note": "sudėti į 1 L permatomą maišelį"
        },
        {
          "name": "Saulės akiniai ir SPF kremas",
          "note": "pravers pietų metu kanjone ir pakrantėje"
        },
        {
          "name": "Vaistinėlė: paracetamolis, pleistrai, asmeniniai vaistai",
          "note": ""
        }
      ]
    },
    {
      "name": "Elektronika",
      "items": [
        {
          "name": "Telefono įkrovikliai ir automobilinis USB įkroviklis",
          "note": ""
        },
        {
          "name": "Telefono laikiklis automobiliui",
          "note": "GPS navigacijai nuomotame automobilyje"
        },
        {
          "name": "Nešiojamas akumuliatorius (power bank)",
          "note": ""
        },
        {
          "name": "Fotoaparatas ar papildoma telefono atmintis",
          "note": "kanjonas, pilys, lagūna"
        }
      ]
    },
    {
      "name": "Gamtai ir kelionei automobiliu",
      "items": [
        {
          "name": "Žiūronai",
          "note": "paukščių stebėjimui Karavastos lagūnoje (pelikanai, flamingai)"
        },
        {
          "name": "Nedidelis dienos kuprinys",
          "note": "trumpiems žygeliams ir takams"
        },
        {
          "name": "Gertuvė vandeniui",
          "note": "ilgoms kelionės dienoms automobilyje"
        },
        {
          "name": "Užkandžiai Kauno–Varšuvos ruožui",
          "note": "išvykstant ~11:00, ~5 val. kelias"
        }
      ]
    }
  ],
  "tips": [
    "Skysčiai rankiniame bagaže – tik iki 100 ml talpyklose, visi kartu viename 1 L permatomame maišelyje.",
    "Jokių peilių ar daugiafunkcių įrankių rankiniame bagaže – jų šioje kelionėje ir nereikės.",
    "Albanijoje ir Lietuvoje/Lenkijoje tas pats kištukų tipas (C/F, 230V) – adapterio nereikia.",
    "Atsisiųskite offline žemėlapius (Google Maps ar Maps.me) – kaimo vietovėse tarp Berato, Osumio kanjono ir Karavastos ryšys gali dingti.",
    "Nuomos sutartyje nurodytas depozitas – būtina turėti kreditinę (ne debeto) kortelę pagrindinio vairuotojo vardu."
  ]
}
```

</details>

### 5. Biudžetas — 10:15:24 ✅

- **Modelis:** `claude-sonnet-5` · **Vykdė:** Native Claude (claude -p) · **Trukmė:** 106.5 s
- **Sistemos promptas:** `prompts/budget.md`

<details><summary><b>Užklausa</b></summary>

````json
{
  "itinerary": "{\"days\":[{\"number\":1,\"title\":\"Atvykimas į Tiraną\",\"stops\":[{\"name\":\"Tiranos oro uostas (TIA)\",\"lat\":41.4147,\"lon\":19.7206,\"arrive\":\"20:30\",\"depart\":\"21:00\",\"maps_query\":\"Tirana International Airport Nënë Tereza, Albania\",\"google_maps_url\":\"https://www.google.com/maps/search/?api=1&query=Tirana%20International%20Airport%20N%C3%ABn%C3%AB%20Tereza%2C%20Albania\",\"notes\":\"Skrydis iš Varšuvos nusileidžia 20:30. Automobilio nuomos (VW Tiguan ar panašus visureigis, tinka 4 žmonėms ir bagažui, su Papildomo vairuotojo ir pilnos apsaugos draudimu) atsiėmimas 21:00. Tą pačią vietą reikės grąžinti automobilį lapkričio 2 d. iki 17:00.\",\"arrive_by\":\"car\",\"transit\":\"\"},{\"name\":\"Hanna Apartment\",\"lat\":41.3192,\"lon\":19.8294,\"arrive\":\"21:20\",\"depart\":\"21:20\",\"maps_query\":\"Apartament Tirana8, Rruga e Elbasanit, Tirana, Albania\",\"google_maps_url\":\"https://www.google.com/maps/search/?api=1&query=Apartament%20Tirana8%2C%20Rruga%20e%20Elbasanit%2C%20Tirana%2C%20Albania\",\"notes\":\"Pirma nakvynė – butas Rruga e Elbasanit, kondicionierius, nemokamas WiFi, tinka 4 žmonėms. Kelias nuo oro uosto apie 20 min, vėlai vakare eismas ramus.\",\"arrive_by\":\"car\",\"transit\":\"\"}],\"driving_minutes\":20,\"overnight_city\":\"Tirana\"},{\"number\":2,\"title\":\"Krujė, Belšo ežeras ir Beratas\",\"stops\":[{\"name\":\"Krujos pilis ir Skenderbego muziejus bei Senasis bazaras\",\"lat\":41.5086,\"lon\":19.7919,\"arrive\":\"09:45\",\"depart\":\"10:30\",\"maps_query\":\"Kalaja e Krujës, Krujë, Albania\",\"google_maps_url\":\"https://www.google.com/maps/search/?api=1&query=Kalaja%20e%20Kruj%C3%ABs%2C%20Kruj%C3%AB%2C%20Albania\",\"notes\":\"Skenderbego muziejus pilies viduje, bilietas apie 200 lekų (~2 €). Žiemos darbo laikas apytiksliai 09:00–16:00 – darbo laiką verta pasitikrinti. Prie pilies – senasis bazaras su amatininkų dirbiniais ir suvenyrais.\",\"arrive_by\":\"car\",\"transit\":\"\"},{\"name\":\"Belšo ežeras (apžvalgos sustojimas)\",\"lat\":41.0931,\"lon\":19.8828,\"arrive\":\"12:02\",\"depart\":\"12:17\",\"maps_query\":\"Liqeni i Belshit, Belsh, Albania\",\"google_maps_url\":\"https://www.google.com/maps/search/?api=1&query=Liqeni%20i%20Belshit%2C%20Belsh%2C%20Albania\",\"notes\":\"Trumpas sustojimas pakeliui – gražus Dumrės plokščiakalnio ir ežerų vaizdas, proga kavai ir nuotraukai.\",\"arrive_by\":\"car\",\"transit\":\"\"},{\"name\":\"Pietūs „Lili Homemade Food“\",\"lat\":40.7064,\"lon\":19.9513,\"arrive\":\"13:54\",\"depart\":\"14:55\",\"maps_query\":\"Lili Homemade Food, Berat, Albania\",\"google_maps_url\":\"https://www.google.com/maps/search/?api=1&query=Lili%20Homemade%20Food%2C%20Berat%2C%20Albania\",\"notes\":\"Populiarus namų virtuvės restoranas Mangalemo kvartale, vietiniai patiekalai.\",\"arrive_by\":\"car\",\"transit\":\"\"},{\"name\":\"Mangalemo senasis kvartalas\",\"lat\":40.706,\"lon\":19.951,\"arrive\":\"14:55\",\"depart\":\"15:09\",\"maps_query\":\"Mangalem Quarter, Berat, Albania\",\"google_maps_url\":\"https://www.google.com/maps/search/?api=1&query=Mangalem%20Quarter%2C%20Berat%2C%20Albania\",\"notes\":\"Pasivaikščiojimas osmanų laikų gatvelėmis su garsiaisiais „tūkstančio langų“ namais.\",\"arrive_by\":\"walk\",\"transit\":\"\"},{\"name\":\"Berato pilis (Kalaja e Beratit)\",\"lat\":40.7014,\"lon\":19.9447,\"arrive\":\"15:29\",\"depart\":\"16:13\",\"maps_query\":\"Kalaja e Beratit, Berat, Albania\",\"google_maps_url\":\"https://www.google.com/maps/search/?api=1&query=Kalaja%20e%20Beratit%2C%20Berat%2C%20Albania\",\"notes\":\"Gyvenama pilis su bizantiškomis bažnyčiomis. Įėjimas į teritoriją laisvas, Onufrijaus muziejuje bilietas apie 200 lekų – darbo laiką verta pasitikrinti.\",\"arrive_by\":\"walk\",\"transit\":\"\"},{\"name\":\"Goricos tiltas ir kvartalas\",\"lat\":40.7021,\"lon\":19.9497,\"arrive\":\"16:38\",\"depart\":\"17:08\",\"maps_query\":\"Ura e Goricës, Berat, Albania\",\"google_maps_url\":\"https://www.google.com/maps/search/?api=1&query=Ura%20e%20Goric%C3%ABs%2C%20Berat%2C%20Albania\",\"notes\":\"Osmanų laikų akmeninis tiltas per Osumo upę – ypač gražus prieblandoje, puikus vaizdas į Mangalemą.\",\"arrive_by\":\"walk\",\"transit\":\"\"},{\"name\":\"DD Villa\",\"lat\":40.7057,\"lon\":19.952,\"arrive\":\"17:23\",\"depart\":\"17:23\",\"maps_query\":\"DD Villa, Rruga Antipatrea, Berat, Albania\",\"google_maps_url\":\"https://www.google.com/maps/search/?api=1&query=DD%20Villa%2C%20Rruga%20Antipatrea%2C%20Berat%2C%20Albania\",\"notes\":\"Nakvynė Berate – sodas, baras, pusryčiai, privatus parkavimas už papildomą mokestį.\",\"arrive_by\":\"walk\",\"transit\":\"\"}],\"driving_minutes\":180,\"overnight_city\":\"Berat\"},{\"number\":3,\"title\":\"Osumio kanjonas ir Vlorės pakrantė\",\"stops\":[{\"name\":\"Osumio kanjono apžvalgos aikštelė\",\"lat\":40.5044,\"lon\":20.227,\"arrive\":\"10:15\",\"depart\":\"11:00\",\"maps_query\":\"Kanioni i Osumit, Çorovodë, Albania\",\"google_maps_url\":\"https://www.google.com/maps/search/?api=1&query=Kanioni%20i%20Osumit%2C%20%C3%87orovod%C3%AB%2C%20Albania\",\"notes\":\"Vienas gražiausių gamtos vaizdų kelyje – kanjono apžvalgos aikštelė prie kelio, patogi stovėjimo vieta.\",\"arrive_by\":\"car\",\"transit\":\"\"},{\"name\":\"Pietūs Vlorės marina\",\"lat\":40.458,\"lon\":19.485,\"arrive\":\"13:51\",\"depart\":\"14:51\",\"maps_query\":\"Marina e Vlorës, Vlorë, Albania\",\"google_maps_url\":\"https://www.google.com/maps/search/?api=1&query=Marina%20e%20Vlor%C3%ABs%2C%20Vlor%C3%AB%2C%20Albania\",\"notes\":\"Vlorės uosto promenadoje daug žuvies restoranų – pasirinkite bet kurį su šviežia dienos žuvimi.\",\"arrive_by\":\"car\",\"transit\":\"\"},{\"name\":\"Vlorės pakrantės promenada (Lungomare)\",\"lat\":40.458,\"lon\":19.485,\"arrive\":\"14:51\",\"depart\":\"15:51\",\"maps_query\":\"Lungomare, Vlorë, Albania\",\"google_maps_url\":\"https://www.google.com/maps/search/?api=1&query=Lungomare%2C%20Vlor%C3%AB%2C%20Albania\",\"notes\":\"Pasivaikščiojimas pakrante, vaizdas į Jonų jūrą ir Sazano salą.\",\"arrive_by\":\"walk\",\"transit\":\"\"},{\"name\":\"Hotel Liro – Adults Only\",\"lat\":40.455,\"lon\":19.484,\"arrive\":\"16:01\",\"depart\":\"16:01\",\"maps_query\":\"Hotel Liro Adults Only, Rruga Aleksandër Moisiu, Vlorë, Albania\",\"google_maps_url\":\"https://www.google.com/maps/search/?api=1&query=Hotel%20Liro%20Adults%20Only%2C%20Rruga%20Aleksand%C3%ABr%20Moisiu%2C%20Vlor%C3%AB%2C%20Albania\",\"notes\":\"Nakvynė Vlorėje – privatus paplūdimio ruožas, lauko baseinas, vaizdas į jūrą nuo balkono. Tik suaugusiems.\",\"arrive_by\":\"car\",\"transit\":\"\"}],\"driving_minutes\":205,\"overnight_city\":\"Vlorë\"},{\"number\":4,\"title\":\"Divjakė-Karavasta ir išvykimas\",\"stops\":[{\"name\":\"Karavastos lagūnos Lankytojų centras ir apžvalgos bokštas\",\"lat\":40.979,\"lon\":19.466,\"arrive\":\"10:10\",\"depart\":\"13:20\",\"maps_query\":\"Qendra e Vizitorëve Divjakë-Karavasta, Divjakë, Albania\",\"google_maps_url\":\"https://www.google.com/maps/search/?api=1&query=Qendra%20e%20Vizitor%C3%ABve%20Divjak%C3%AB-Karavasta%2C%20Divjak%C3%AB%2C%20Albania\",\"notes\":\"Automobilį palikite Lankytojų centro aikštelėje – čia veda geras asfaltuotas/tvarkingas kelias, o čia pat yra apie 35 m aukščio apžvalgos bokštas su gražiu vaizdu į lagūną. Jei norite pasiekti giliau lagūnoje esantį bokštą, paskutinius 1–2 km (ir tiek pat atgal) reikia nueiti pėsčiomis – nuomotam automobiliui tas kelias po lietaus būna dumblinas ir netinkamas. Rudenį čia gerai matomi rausvieji pelikanai ir flamingai. Nedidelis mokestis automobiliui įvažiuojant į parką.\",\"arrive_by\":\"car\",\"transit\":\"\"},{\"name\":\"Pietūs Divjakės paplūdimyje\",\"lat\":40.9958,\"lon\":19.4705,\"arrive\":\"13:30\",\"depart\":\"14:30\",\"maps_query\":\"Plazhi i Divjakës, Divjakë, Albania\",\"google_maps_url\":\"https://www.google.com/maps/search/?api=1&query=Plazhi%20i%20Divjak%C3%ABs%2C%20Divjak%C3%AB%2C%20Albania\",\"notes\":\"Paplūdimio žuvies kioskai ir restoranėliai – šviežia žuvis ir jūros gėrybės.\",\"arrive_by\":\"car\",\"transit\":\"\"},{\"name\":\"Tiranos oro uostas (TIA) – automobilio grąžinimas ir skrydis namo\",\"lat\":41.4147,\"lon\":19.7206,\"arrive\":\"16:15\",\"depart\":\"19:05\",\"maps_query\":\"Tirana International Airport Nënë Tereza, Albania\",\"google_maps_url\":\"https://www.google.com/maps/search/?api=1&query=Tirana%20International%20Airport%20N%C3%ABn%C3%AB%20Tereza%2C%20Albania\",\"notes\":\"Automobilio grąžinimas (reikia iki 17:00) – atsargos laiko pakaks. Skrydis į Varšuvą išskrenda 19:05 – registracijai ir saugumo patikrai liks pakankamai laiko.\",\"arrive_by\":\"car\",\"transit\":\"\"}],\"driving_minutes\":170,\"overnight_city\":\"Nėra (skrydis namo)\"}]}",
  "accommodation": "## Nakvynės vietos (tik užsakytos)\n\nKeliautojas jau užsakė ir patvirtino konkrečius nakvynės objektus per booking.com nuorodas. Žemiau — tik šios užsakytos vietos, be papildomų alternatyvų.\n\n### 1. Tirana (penktadienis, 2026-10-30 → šeštadienis, 2026-10-31)\n\n**✅ Užsakyta — Hanna Apartment** — **51 €/naktį**\n- Rruga e Elbasanit, Tirana. Įvertinimas 9.0/10 (186 atsiliepimai).\n- Kondicionierius, nemokamas WiFi. Tinka 4 žmonėms (butas).\n- Nuoroda: https://www.booking.com/hotel/al/apartament-tirana8.lt.html\n\n### 2. Beratas (šeštadienis, 2026-10-31 → sekmadienis, 2026-11-01)\n\n**✅ Užsakyta — DD Villa** — **61 €/naktį**\n- Rruga Antipatrea, Beratas. Įvertinimas 8.8/10 (667 atsiliepimai).\n- Sodas, baras, bendra svetainė, miesto vaizdas, pusryčiai (bufetas/à la carte), privatus parkavimas (už papildomą mokestį), restoranas vietoje.\n- Nuoroda: https://www.booking.com/hotel/al/dd-villa.lt.html\n\n### 3. Vlorė / Radhimė (sekmadienis, 2026-11-01 → pirmadienis, 2026-11-02)\n\n**✅ Užsakyta — Hotel Liro – Adults Only** — **117 €/naktį**\n- Aleksandër Moisiu Street, Vlorė. Įvertinimas 8.6/10 (1295 atsiliepimai).\n- Privatus paplūdimio ruožas, lauko baseinas, nemokamas parkavimas, restoranas/baras, pusryčiai, vaizdas į jūrą nuo balkono. Autobusų stotelė priešais viešbutį.\n- Nuoroda: https://www.booking.com/hotel/al/liro.lt.html\n- ⚠️ Pastaba: \"Adults Only\" — jei grupėje yra vaikų, šią vietą reikėtų pakeisti.\n\n**Biudžeto suma nakvynėms (3 naktys, visai grupei):** 51 + 61 + 117 = **229 €**\n\n```json\n{\"picks\": [\n  {\"city\": \"Tirana\", \"name\": \"Hanna Apartment\", \"checkin\": \"2026-10-30\", \"checkout\": \"2026-10-31\", \"price_per_night_eur\": 51},\n  {\"city\": \"Berat\", \"name\": \"DD Villa\", \"checkin\": \"2026-10-31\", \"checkout\": \"2026-11-01\", \"price_per_night_eur\": 61},\n  {\"city\": \"Vlorë\", \"name\": \"Hotel Liro - Adults Only\", \"checkin\": \"2026-11-01\", \"checkout\": \"2026-11-02\", \"price_per_night_eur\": 117}\n]}\n```",
  "car_rental": {
    "needed": true,
    "recommended_car_types": [
      {
        "car_type": "Kompaktinis visureigis (Dacia Duster, Škoda Karoq, VW T-Roc)",
        "why": "Pakankamai vietos 4 žmonėms ir bagažui, didesnė prošvaisa nelygiems/žvyruotiems ruožams (Osumo kanjono apžvalgos aikštelės, Beratas), ekonomiškos degalų sąnaudos trumpiems rudens maršrutams.",
        "avg_price_per_day_eur": 40,
        "avg_total_eur": 160
      },
      {
        "car_type": "Pilno dydžio visureigis (VW Tiguan, Hyundai Tucson, Nissan Qashqai)",
        "why": "Daugiausia vietos bagažui ir patogiausia 4 suaugusiems ilgesnėse atkarpose (Vlorė–Llogara perėja); tai klasė, kurią jau užsisakėte (VW Tiguan) – patikima pasirinktis rudens/žiemos sąlygoms kalnų perėjose.",
        "avg_price_per_day_eur": 55,
        "avg_total_eur": 220
      },
      {
        "car_type": "Kompaktinis sedanas/hečbekas (Škoda Octavia, VW Golf)",
        "why": "Pigiausias variantas, jei maršrutas apsiriboja asfaltuotais keliais; mažesnė prošvaisa mažiau tinkama Osumo kanjono ar kalnų ruožams, mažiau bagažo vietos 4 žmonėms.",
        "avg_price_per_day_eur": 30,
        "avg_total_eur": 120
      }
    ],
    "companies": [
      {
        "name": "Karruka Rent a Car",
        "pickup_location": "Tirana International Airport (TIA), Rinas – atvykimo salė",
        "rating": 4.9,
        "review_count": 1000,
        "review_source": "Google Maps",
        "car_class": "Pilno dydžio visureigis (SUV), 5 vietos",
        "price_estimate_eur": 180,
        "why": "Tiranos oro uosto klientų dažniausiai renkama vietinė įmonė – be depozito, minimalus popierizmas, draudimas įskaičiuotas į kainą.",
        "booking_url": "https://karrukarental.com/reservation/"
      },
      {
        "name": "Tirana Airport Rental Car",
        "pickup_location": "Tirana International Airport (TIA), Rinas",
        "rating": 4.7,
        "review_count": 1413,
        "review_source": "Google Maps",
        "car_class": "Kompaktinis/pilno dydžio visureigis, 5 vietos",
        "price_estimate_eur": 175,
        "why": "Nauji automobiliai su pilnu draudimu ir be depozito – patikimas ir geros kainos/kokybės santykio pasirinkimas 4 keliautojams.",
        "booking_url": "https://tiranaairportrentalcar.com/"
      },
      {
        "name": "Sixt",
        "pickup_location": "Tirana International Airport (TIA), nuomos centras prie terminalo",
        "rating": 4.1,
        "review_count": 4494,
        "review_source": "EasyTerra (8.2/10)",
        "car_class": "Visureigis (SUV), 5 vietos",
        "price_estimate_eur": 255,
        "why": "Tarptautinis prekės ženklas su aiškiai pažymėtu biuru oro uoste ir platesniu pagalbos kelyje tinklu – saugus pasirinkimas, jei svarbiau aptarnavimo nuspėjamumas nei mažiausia kaina.",
        "booking_url": "https://www.sixt.com/car-rental/albania/tirana/tirana-airport/"
      }
    ],
    "tips": [
      "Automobilis šiai kelionei jau užsakytas (VW Tiguan / pilno dydžio visureigis, atsiėmimas TIA spalio 30 d. 21:00, grąžinimas lapkričio 2 d. 17:00, su Papildomu vairuotoju ir Super Protective Insurance, iš viso €168) – aukščiau pateikti pasiūlymai skirti palyginimui arba atsarginiam variantui.",
      "Atsiėmimas vėlai vakare (21:00): būtina iš anksto patvirtinti, kad pasirinktos įmonės biuras tuo metu dirba – dauguma vietinių nuomotojų oro uoste veikia 24/7, bet verta gauti patvirtinimą el. paštu.",
      "Kalnų ir kaimo kelių ruožai (Llogara perėja, Osumo kanjono apžvalgos keliai) gali būti duobėti ar žvyruoti – didesnė prošvaisa (SUV) patogesnė nei sedanas.",
      "Degalų politika: patikrinti „pilnas-į-pilną“ sąlygą; dauguma vietinių įmonių nereikalauja depozito grynaisiais, tik kreditinės kortelės rezervacijos.",
      "Rudens/žiemos sąlygoms rekomenduojamas pilnas draudimas be išskaitos (kaip jau pasirinktas Super Protective Insurance) – kalnų keliuose po lietaus gali būti slidu."
    ]
  },
  "food": {
    "eateries": [
      {
        "name": "Sofra e Ariut",
        "city": "Tirana",
        "address": "Rruga e Elbasanit, Tiranë",
        "day": 1,
        "near": "nakvynė Hanna Apartment (ta pati pačia Rruga e Elbasanit gatve)",
        "kind": "tradicinė taverna",
        "local_cuisine": true,
        "avg_price_eur": 13,
        "dinner_price_eur": 17,
        "must_try": [
          {
            "name": "Tavė kosi (ėriena su jogurto padažu)",
            "local_name": "Tavë kosi",
            "price_eur": 9,
            "commons_filename": "TAVE KOSI- agnello allo yogurt albanese.jpg"
          },
          {
            "name": "Įdaryti paprikos su varške",
            "local_name": "Speca me gjizë",
            "price_eur": 6,
            "commons_filename": "Dollma,Speca te mbushur me mish dhe oriz.jpg"
          },
          {
            "name": "Ėrienos kotletai ant grotelių",
            "local_name": "Copa qengji në skarë",
            "price_eur": 11,
            "commons_filename": "Liat Portal for Foodie Disorder - Homemade Lamb Chops with Rice and Grilled Vegetables.jpg"
          }
        ],
        "why": "Pačioje Rruga e Elbasanit gatvėje, 5 min pėsčiomis nuo nakvynės – patogu pirmą vakarą po vėlyvo atvykimo (nusileidus 20:30), siūlo tradicinius albanų patiekalus gražioje sodo aplinkoje; kai kurie atsiliepimai mini aukštesnes kainas, tad geriau rinktis pagrindinius patiekalus, ne žuvį.",
        "maps_url": "https://www.google.com/maps/search/?api=1&query=Sofra%20e%20Ariut%2C%20Rruga%20e%20Elbasanit%2C%20Tiran%C3%AB"
      },
      {
        "name": "Snack Bar Derexhiku",
        "city": "Krujë",
        "address": "Pazari i Vjetër (Senasis bazaras), Krujë",
        "day": 2,
        "near": "Krujos senasis bazaras ir pilis",
        "kind": "byrektorė/kavinė bazare",
        "local_cuisine": true,
        "avg_price_eur": 4,
        "dinner_price_eur": 6,
        "must_try": [
          {
            "name": "Byrekas su spinatais ir varške",
            "local_name": "Byrek me spinaq",
            "price_eur": 2,
            "commons_filename": "Byrek from Kosovo.png"
          },
          {
            "name": "Molinio puodo troškinys",
            "local_name": "Tavë dheu",
            "price_eur": 5,
            "commons_filename": "Pasul me suxhuk në tavë të dheut.jpg"
          },
          {
            "name": "Vištienos file su garnyru",
            "local_name": "Filetë pule",
            "price_eur": 5,
            "commons_filename": ""
          }
        ],
        "why": "Mažas kioskas pačiame senojo bazaro centre – puikus greitas užkandis tarp pilies ir muziejaus lankymo, vietinių gerai vertinamas už skanų ir pigų byreką.",
        "maps_url": "https://www.google.com/maps/search/?api=1&query=Snack%20Bar%20Derexhiku%2C%20Pazari%20i%20Vjet%C3%ABr%20%28Senasis%20bazaras%29%2C%20Kruj%C3%AB"
      },
      {
        "name": "Lili Homemade Food",
        "city": "Berat",
        "address": "Rruga Llambi Guxhumani, Mangalem, Beratas",
        "day": 2,
        "near": "Mangalemo senasis kvartalas (pietų sustojimas maršrute)",
        "kind": "šeimos namų virtuvė",
        "local_cuisine": true,
        "avg_price_eur": 12,
        "dinner_price_eur": 14,
        "must_try": [
          {
            "name": "Fërgesë (paprikų ir varškės troškinys)",
            "local_name": "Fërgesë",
            "price_eur": 6,
            "commons_filename": "Fërgesë dhe Tavë me oriz.jpg"
          },
          {
            "name": "Tavë kosi",
            "local_name": "Tavë kosi",
            "price_eur": 9,
            "commons_filename": "TAVE KOSI- agnello allo yogurt albanese.jpg"
          },
          {
            "name": "Įdarytos baklažanai",
            "local_name": "Patëllxhan i mbushur",
            "price_eur": 7,
            "commons_filename": ""
          }
        ],
        "why": "Lili ir jo žmona gamina patiekalus savo kieme pagal senelio receptus – vienas geriausiai įvertintų restoranų visoje Albanijoje (4.9/5, virš 2000 atsiliepimų); rezervacija WhatsApp būtina dėl mažo vietų skaičiaus.",
        "maps_url": "https://www.google.com/maps/search/?api=1&query=Lili%20Homemade%20Food%2C%20Rruga%20Llambi%20Guxhumani%2C%20Mangalem%2C%20Beratas"
      },
      {
        "name": "Guva Mangalem",
        "city": "Berat",
        "address": "Rr. Llambi Guxhumani nr. 44, Beratas",
        "day": 2,
        "near": "nakvynė DD Villa, Mangalemo kvartalas",
        "kind": "tradicinė taverna",
        "local_cuisine": true,
        "avg_price_eur": 10,
        "dinner_price_eur": 14,
        "must_try": [
          {
            "name": "Tavė kosi",
            "local_name": "Tavë kosi",
            "price_eur": 8,
            "commons_filename": "TAVE KOSI- agnello allo yogurt albanese.jpg"
          },
          {
            "name": "Įdarytos paprikos",
            "local_name": "Speca të mbushur",
            "price_eur": 5,
            "commons_filename": "Dollma,Speca te mbushur me mish dhe oriz.jpg"
          },
          {
            "name": "Byrekas",
            "local_name": "Byrek",
            "price_eur": 3,
            "commons_filename": "Byrek from Kosovo.png"
          }
        ],
        "why": "Vos keli žingsniai nuo DD Villa, terasa su vaizdu į Berato pilį ir Mangalemą, tradiciniai Berato patiekalai patiekiami klasikiniu stiliumi.",
        "maps_url": "https://www.google.com/maps/search/?api=1&query=Guva%20Mangalem%2C%20Rr.%20Llambi%20Guxhumani%20nr.%2044%2C%20Beratas"
      },
      {
        "name": "Restaurant Salvadore",
        "city": "Vlorë",
        "address": "Rruga Pelivan Leskaj, Vlorë",
        "day": 3,
        "near": "Vlorės marina (pietų sustojimas maršrute)",
        "kind": "žuvies restoranas su savo turgumi",
        "local_cuisine": true,
        "avg_price_eur": 14,
        "dinner_price_eur": 17,
        "must_try": [
          {
            "name": "Žuvis ant grotelių",
            "local_name": "Peshk në skarë",
            "price_eur": 12,
            "commons_filename": "Grilled sea bass (7906690230).jpg"
          },
          {
            "name": "Keptas kalmaras",
            "local_name": "Kallamar i skuqur",
            "price_eur": 8,
            "commons_filename": "Calamari fritti - Enzo's 2026-05-05.jpg"
          },
          {
            "name": "Aštuonkojo salotos",
            "local_name": "Sallatë oktapodi",
            "price_eur": 9,
            "commons_filename": "Octopus salad .jpg"
          }
        ],
        "why": "Šeimos valdomas žuvies turgus su restoranu – žvejys savininkas pats pristato kasdienį laimikį, atsiliepimuose minimos sąžiningos kainos ir gausios porcijos.",
        "maps_url": "https://www.google.com/maps/search/?api=1&query=Restaurant%20Salvadore%2C%20Rruga%20Pelivan%20Leskaj%2C%20Vlor%C3%AB"
      },
      {
        "name": "Taverna Djepi",
        "city": "Vlorë",
        "address": "Rruga Aleksandër Moisiu, Vlorë",
        "day": 3,
        "near": "nakvynė Hotel Liro – Adults Only, Rruga Aleksandër Moisiu",
        "kind": "šeimos taverna su jūros vaizdu",
        "local_cuisine": true,
        "avg_price_eur": 15,
        "dinner_price_eur": 19,
        "must_try": [
          {
            "name": "Keptas ešerys",
            "local_name": "Levrek në skarë",
            "price_eur": 13,
            "commons_filename": "Grilled sea bass (7906690230).jpg"
          },
          {
            "name": "Krevetės ant grotelių",
            "local_name": "Karkaleca në skarë",
            "price_eur": 14,
            "commons_filename": "2026-05-24 01 Grilled Spot prawns (Pandalus platyceros) - Victoria BC CAN.jpg"
          },
          {
            "name": "Aštuonkojis",
            "local_name": "Oktapod",
            "price_eur": 12,
            "commons_filename": "Octopus salad .jpg"
          }
        ],
        "why": "Toje pačioje gatvėje kaip Hotel Liro (apie 5 min.), terasa su saulėlydžio vaizdu į jūrą, 4.8/5 įvertinimas – šeimyniška atmosfera ir švelnios kainos.",
        "maps_url": "https://www.google.com/maps/search/?api=1&query=Taverna%20Djepi%2C%20Rruga%20Aleksand%C3%ABr%20Moisiu%2C%20Vlor%C3%AB"
      },
      {
        "name": "Restorant Pelikan",
        "city": "Divjakë",
        "address": "Divjakë Qendër Plazh, Divjakë",
        "day": 4,
        "near": "Divjakės paplūdimys (pietų sustojimas po Karavastos lagūnos)",
        "kind": "žuvies restoranėlis paplūdimyje",
        "local_cuisine": true,
        "avg_price_eur": 13,
        "dinner_price_eur": 15,
        "must_try": [
          {
            "name": "Keptas ešerys",
            "local_name": "Levrek në skarë",
            "price_eur": 11,
            "commons_filename": "Grilled sea bass (7906690230).jpg"
          },
          {
            "name": "Keptas kalmaras",
            "local_name": "Kallamar i skuqur",
            "price_eur": 8,
            "commons_filename": "Calamari fritti - Enzo's 2026-05-05.jpg"
          },
          {
            "name": "Ungurys (lagūnos specialitetas)",
            "local_name": "Ngjalë",
            "price_eur": 14,
            "commons_filename": ""
          }
        ],
        "why": "Vos žingsnis nuo paplūdimio ir lagūnos, lokalūs žvejai pristato ungurius ir žuvį tiesiai iš Karavastos lagūnos – 4.8/5 įvertinimas, puikus paskutinis pietų stotelė prieš skrydį.",
        "maps_url": "https://www.google.com/maps/search/?api=1&query=Restorant%20Pelikan%2C%20Divjak%C3%AB%20Qend%C3%ABr%20Plazh%2C%20Divjak%C3%AB"
      }
    ],
    "dishes": [
      {
        "name": "Tavė kosi (ėriena jogurto padaže)",
        "local_name": "Tavë kosi",
        "description": "Albanijos nacionalinis patiekalas – keptos ėrienos gabalai, apkepti jogurto ir kiaušinių padaže su ryžiais, iškepti orkaitėje.",
        "price_eur_min": 7,
        "price_eur_max": 11,
        "where_to_try": [
          "Sofra e Ariut",
          "Lili Homemade Food",
          "Guva Mangalem"
        ],
        "commons_filename": "TAVE KOSI- agnello allo yogurt albanese.jpg"
      },
      {
        "name": "Byrekas",
        "local_name": "Byrek",
        "description": "Plonos tešlos pyragas, dažniausiai su spinatais ir varške arba mėsa – populiarus pusryčių ir užkandžių patiekalas visoje šalyje.",
        "price_eur_min": 1,
        "price_eur_max": 3,
        "where_to_try": [
          "Snack Bar Derexhiku",
          "Guva Mangalem"
        ],
        "commons_filename": "Byrek from Kosovo.png"
      },
      {
        "name": "Fërgesė",
        "local_name": "Fërgesë",
        "description": "Troškintos paprikos su pomidorais ir vietine varške ar fetos tipo sūriu, patiekiama moliniame puode.",
        "price_eur_min": 5,
        "price_eur_max": 8,
        "where_to_try": [
          "Lili Homemade Food"
        ],
        "commons_filename": "Fërgesë dhe Tavë me oriz.jpg"
      },
      {
        "name": "Įdarytos paprikos",
        "local_name": "Speca të mbushur / Speca me gjizë",
        "description": "Keptos paprikos, įdarytos ryžiais ir mėsa arba vietine varške – klasikinis šeimyninis patiekalas.",
        "price_eur_min": 4,
        "price_eur_max": 6,
        "where_to_try": [
          "Sofra e Ariut",
          "Guva Mangalem"
        ],
        "commons_filename": "Dollma,Speca te mbushur me mish dhe oriz.jpg"
      },
      {
        "name": "Kepsniai (mėsos kukuliai)",
        "local_name": "Qofte",
        "description": "Grilinti mėsos kukuliai su mėtomis ir prieskoniais, patiekiami su jogurto padažu ar salotomis.",
        "price_eur_min": 4,
        "price_eur_max": 7,
        "where_to_try": [
          "Sofra e Ariut",
          "Guva Mangalem"
        ],
        "commons_filename": "Qofte shtëpie me lëng.jpg"
      },
      {
        "name": "Žuvis ant grotelių",
        "local_name": "Peshk në skarë",
        "description": "Šviežia Adrijos/Jonijos jūros žuvis (levrek, zarkadhël), kepta ant žarijų ir patiekiama su alyvuogių aliejumi ir citrina – Vlorės ir Divjakės pakrantės specialitetas.",
        "price_eur_min": 10,
        "price_eur_max": 18,
        "where_to_try": [
          "Restaurant Salvadore",
          "Taverna Djepi",
          "Restorant Pelikan"
        ],
        "commons_filename": "Grilled sea bass (7906690230).jpg"
      },
      {
        "name": "Trilece",
        "local_name": "Trilece",
        "description": "Trijų pienų tortas su karameliniu padažu – populiariausias albaniškas desertas, randamas beveik visose kavinėse.",
        "price_eur_min": 2,
        "price_eur_max": 4,
        "where_to_try": [
          "Sofra e Ariut",
          "Guva Mangalem",
          "Lili Homemade Food"
        ],
        "commons_filename": "Trileće cake and tea in Visegrad, Bosnia and Herzegovina.jpg"
      }
    ],
    "bars": [
      {
        "name": "Komiteti – Kafe Muzeum",
        "city": "Tirana",
        "address": "Rruga Fatmir Haxhiu 2, Tiranë",
        "day": 1,
        "near": "Tiranos centras, apie 15 min. nuo Hanna Apartment",
        "why_special": "Baras-muziejus, pilnas komunistinės epochos daiktų – uniformų, senų televizorių, radijo imtuvų ir net lubose kabančių grėblių, naudojamų kaip vyno taurių pakaba; unikali atmosfera ir plati raki pasirinkimo galimybė (Tripadvisor 4.3/5).",
        "maps_url": "https://www.google.com/maps/search/?api=1&query=Komiteti%20%E2%80%93%20Kafe%20Muzeum%2C%20Rruga%20Fatmir%20Haxhiu%202%2C%20Tiran%C3%AB"
      }
    ]
  }
}
````

</details>

<details><summary><b>Atsakymas</b></summary>

# Biudžeto suvestinė — Albanija, 2026-10-30–11-02 (4 dienos / 3 naktys, 4 keliautojai)

## 1. Skrydžiai ✅ patvirtinta (Kiwi.com paieška, tikslios datos/laikai sutampa su maršrutu)

| Skrydis | Laikas | Kaina (4 asm.) |
|---|---|---|
| WAW → TIA, Ryanair FR6809 | 2026-10-30, 18:30→20:30 | — |
| TIA → WAW, Ryanair FR6810 | 2026-11-02, 19:00→21:05 | — |
| **Viso (4 suaugę, be registruoto bagažo)** | | **405 €** |

- Rastas pasiūlymas **tiksliai atitinka** maršrute nurodytus laikus (atvykimas 20:30, išskridimas ~19:05).
- Kaina **neapima registruoto bagažo** (tik asmeninis daiktas) — jei reikės 2 krepšių kelionei pirmyn-atgal, pridėti ~€80–100 (įvertis).
- **Min/Likely/Max: 405 / 405 / 505 €**

## 2. Automobilio nuoma ✅ patvirtinta (jau užsakyta)

| | |
|---|---|
| VW Tiguan (ar panašus), TIA, 10-30 21:00 → 11-02 17:00 | **168 €** |
| Įskaičiuota | Papildomas vairuotojas + Super Protective Insurance (be išskaitos) |

- **Min/Likely/Max: 168 / 168 / 168 €** (fiksuota, jau apmokėta/patvirtinta rezervacija).
- Viešasis transportas nereikalingas (automobilis būtinas dėl maršruto).

## 3. Nakvynė ✅ patvirtinta (booking.com, jau užsakyta)

| Vieta | Naktys | €/naktį | Viso |
|---|---|---|---|
| Hanna Apartment, Tirana | 1 | 51 | 51 |
| DD Villa, Beratas | 1 | 61 | 61 |
| Hotel Liro, Vlorė | 1 | 117 | 117 |
| **Viso** | 3 | | **229 €** |

- **Min/Likely/Max: 229 / 229 / 229 €** (fiksuota, visai grupei/butui/kambariui, ne per asmenį).

## 4. Maistas — ⚠ įvertis (pagal Food & Bars agento nurodytas vietas ir jų kainas)

Pusryčiai DD Villa (11-01) ir Hotel Liro (11-02) **įskaičiuoti** į nakvynės kainą — nepriskaičiuoti papildomai.

| Diena | Valgymas | Vieta | €/asm. |
|---|---|---|---|
| 1 | Vakarienė | Sofra e Ariut, Tirana | 17 |
| 2 | Pusryčiai/užkandis | Snack Bar Derexhiku, Krujė | 4 |
| 2 | Pietūs | Lili Homemade Food, Beratas | 12 |
| 2 | Vakarienė | Guva Mangalem, Beratas | 14 |
| 3 | Pusryčiai | *(įskaičiuota DD Villa)* | 0 |
| 3 | Pietūs | Restaurant Salvadore, Vlorė | 14 |
| 3 | Vakarienė | Taverna Djepi, Vlorė | 19 |
| 4 | Pusryčiai | *(įskaičiuota Hotel Liro)* | 0 |
| 4 | Pietūs | Restorant Pelikan, Divjakė | 13 |
| **Viso / asmeniui** | | | **≈93 €** |
| **Viso / 4 asmenims** | | | **≈372 €** |

- Papildomas buferis gėrimams/kavai/baro apsilankymui (pvz. Komiteti, Tirana) — ~15–25 €/asm.
- **Min/Likely/Max (4 asm.): 340 / 392 / 460 €**

## 5. Įėjimo bilietai — ⚠ įvertis (iš Research Agent pastabų, apytikslis lekių kursas)

| Objektas | Kaina/asm. | 4 asm. |
|---|---|---|
| Skenderbego muziejus, Krujė (~200 lekų) | ~2 € | 8 € |
| Onufrijaus muziejus, Berato pilis (~200 lekų) | ~2 € | 8 € |
| Karavastos parko įvažiavimo mokestis (automobiliui) | — | ~3 € |
| **Viso** | | **≈19 €** |

- Darbo laikai/kainos žiemą nepatvirtinti — rekomenduojama patikrinti vietoje.
- **Min/Likely/Max: 15 / 19 / 25 €**

## 6. Degalai — ⚠ įvertis (atstumas apskaičiuotas iš maršruto važiavimo trukmės, ne iš atskiro Logistics Validator atstumo — toks nebuvo pateiktas)

- Bendra važiavimo trukmė: 20+180+205+170 = **575 min (~9,6 val.)**.
- Vidutinis greitis kalnų/pakrantės keliais Albanijoje ~40–45 km/h (Krujė–Beratas–Osumio kanjonas–Vlorė–Divjakė turi daug vingiuotų/kalnų atkarpų) → **įvertintas atstumas ≈350–430 km**.
- Dyzelinas ~1,90–2,00 €/l; SUV (Tiguan tipo) sąnaudos ~7,5–8,5 l/100 km (su oro kondicionavimu, kalnų kelias).

| | Min | Likely | Max |
|---|---|---|---|
| Degalai | 45 € | 58 € | 75 € |

## 📊 Bendra suvestinė (visai grupei, 4 asm.)

| Kategorija | Statusas | Min € | Likely € | Max € |
|---|---|---|---|---|
| Skrydžiai | ✅ patvirtinta (+ įvertis bagažui) | 405 | 405 | 505 |
| Automobilio nuoma | ✅ patvirtinta (jau užsakyta) | 168 | 168 | 168 |
| Nakvynė | ✅ patvirtinta (jau užsakyta) | 229 | 229 | 229 |
| Maistas | ⚠ įvertis (konkrečios vietos/kainos) | 340 | 392 | 460 |
| Įėjimo bilietai | ⚠ įvertis (apytikslis lekių kursas) | 15 | 19 | 25 |
| Degalai | ⚠ įvertis (atstumas apskaičiuotas iš laiko) | 45 | 58 | 75 |
| **VISO (4 asm.)** | | **1202 €** | **1271 €** | **1462 €** |
| **Vienam asmeniui** | | **301 €** | **318 €** | **366 €** |

### Pastabos
- Skrydžių ir nuomos/nakvynės kainos — **patvirtintos** (realios paieškos/rezervacijos), likusios kategorijos — **įverčiai**, nes tiksli maršruto rida (km) iš Logistics Validator nebuvo pateikta šiame įvestyje, o lekių/eurų kainos muziejams yra apytikslės.
- Jei reikės registruoto bagažo skrydžiams, biudžetą didinti ~80–100 €.

</details>

### 6. Puslapis — 10:29:29 ✅

- **Modelis:** `claude-sonnet-5` · **Vykdė:** Native Claude (claude -p) · **Trukmė:** 844.9 s
- **Sistemos promptas:** `prompts/page_designer.md`

<details><summary><b>Užklausa</b></summary>

You are updating an already published trip page, not designing a new one. Below are the current page and the current data. Apply the listed changes and make every part of the page match the current data, but keep the design -- colors, layout, CSS, JS, section order -- and all wording that isn't affected exactly as it is. Keep the <!-- PACKING_LIST --> and <!-- TRIP_MAP --> lines where they are.

Changes:
Updated data: Auto nuoma, Maistas ir barai, Orų prognozė, Planas B, Daiktai, Biudžetas

**Current data:**

```json
{
  "language": "lt",
  "research": "# Research summary: Albania, TIA to TIA, 30 Oct – 2 Nov 2026 (4 people, nature focus)\n\n**Coverage:** Reddit is blocked for the crawler, and TripAdvisor forum threads returned 403. So I have no r/travel or r/albania posts and only TripAdvisor search snippets. Everything else comes from Wikivoyage, blogs and operator sites. Dates are the page's own date where visible, otherwise \"undated\". I did not verify any drive times myself.\n\n## 1. Candidate stops\n\n| # | Stop | Why recommended | Source (date) |\n|---|---|---|---|\n| 1 | **Berat** (UNESCO) | Ottoman old town, uncrowded off-season. About 2–3 h from Tirana. | [Wikivoyage Albania](https://en.wikivoyage.org/wiki/Albania) (undated); [TripAdvisor thread snippet](https://www.tripadvisor.com/ShowTopic-g294445-i4583-k6457473-Tirana_Berat_Gjirokastra_Saranda-Albania.html) (undated) |\n| 2 | **Osumi Canyon and Bogovë waterfall** (from Berat) | Best nature stop within reach of Berat. The road from Berat to Bogova village is paved (about 1 h), and a regular car is fine. The canyon viewpoint is reachable in a normal car, and the author parked at the top. | [Wander with Laura](https://wanderwithlaura.com/how-to-get-to-bogove-waterfall-and-osum-canyon/) (published Aug 2022, updated 10 Jan 2026) |\n| 3 | **Divjakë-Karavasta lagoon** (pelicans, flamingos) | Autumn is a best season for birds. About 1h40 from Tirana, 30 min north of Fier and Apollonia. | [Nomads Travel Guide](https://www.nomads-travel-guide.com/places/divjake-karavasta-national-park/) (undated); [Birdingplaces](https://www.birdingplaces.eu/en/birdingplaces/albania/divjake-karavasta-national-park) (undated) |\n| 4 | **Gjirokastër** (UNESCO) | Stone town, \"empty of summer crowds\" in November. About 3h20 from Tirana on Google, and about 4 h realistically. This is at your daily driving limit. | [thingstodoinalbania](https://thingstodoinalbania.com/month/november/) (undated); [TIC Rent Car](https://ticrentcar.com/tirana-to-gjirokastra/) (undated) |\n| 5 | **Blue Eye (Syri i Kaltër)** | Spring-fed pool, open year-round, 07:00–19:00, 50 LEK entry. It is 22 km from Sarandë and 35 km from Gjirokastër. The last 2 km of road are unpaved but \"doable\", followed by a 2 km walk. | [Laure Wanders](https://www.laurewanders.com/blue-eye-albania/) (29 Aug 2026) |\n| 6 | **Llogara Pass and Dhermi coast** | The old pass road is still open and paved. The new tunnel costs 250 LEK (from 16 Sep 2025) and saves about 30 min. Snow and ice risk is Dec–Feb, so fine for early November, though fog and rain are possible. | [Explorer Tom](https://explorertom.com/en/llogara-pass-albania/) (11 Jun 2026) |\n| 7 | **Shkodër, Rozafa Castle, Lake Shkodra** | Easy northern option, about 1h47 from Tirana on the A1. | [Travelmath / ViaMichelin results](https://www.travelmath.com/driving-time/from/Shkoder,+Albania/to/Tirana,+Albania) (undated) |\n| 8 | **Komani Lake ferry** (Koman to Fierza) | The most scenic northern option. See the caveats in section 2. | [Ferry operator](https://komanilakeferry.com/timetables-and-prices/) (undated) |\n| 9 | **Bënja thermal baths / Përmet / Vjosa valley** | About 1h15 north of Gjirokastër, on the paved main road. Year-round, and best in cold weather. | [Vjosa Rafting guide](https://vjosarafting.com/benja-thermal-baths-permet/) and [Himara.net](https://himara.net/blog/benja-thermal-baths-destination-guide) (both undated) |\n| 10 | Pogradec / Lake Ohrid (Albanian side) | Low confidence. It is 2.5–3 h from Tirana. I found nothing on Korçë or Voskopojë in autumn. | [Explorer Tom](https://explorertom.com/en/lake-ohrid-albanian-side/) (undated) |\n\n**Overrated or skippable:**\n- **Ksamil and the Riviera beach towns:** described as overrun and overpriced in season. In late October the coast is mostly shuttered, with Ksamil and Dhermi venues closed and \"finding restaurants between Vlorë and Sarandë is challenging\" ([thingstodoinalbania](https://thingstodoinalbania.com/month/november/), undated). Himarë is \"empty by end of October\" per a TripAdvisor snippet (undated).\n- **Bovilla lake and Dajti:** the Dajti cable car is closed on Tuesdays. Your dates fall on Fri–Mon, so this doesn't matter ([TripAdvisor FAQ](https://www.tripadvisor.com/FAQ-g294445-d4573567-Dajti_Ekspres_Cable_Car.html)).\n- **Not found:** I found no sourced opinion on Bunk'Art, Blloku or Durrës. Treat those as unresearched.\n\n## 2. Road and logistics warnings\n\n**Roads to exclude for a standard rental car** (all from [Localrent \"Prohibited routes\"](https://www.localrent.com/en/journal/albania/articles/prohibited-routes/), undated with 2023 file metadata):\n- **SH74 Berat–Përmet:** \"narrow unpaved mountain road covered with small stones\". This is the one your earlier projects flagged.\n- **Berat–Përmet through Osumi Canyon:** unpaved with potholes and large puddles.\n- **Memaliaj–Berat (Martallozi):** unpaved.\n- **Tirana–Qafë-Shtamë via Lake Bovilla:** unpaved serpentine. A regular car can reach the dam, but not beyond ([Localrent](https://www.localrent.com/en/journal/albania/articles/prohibited-routes/) and search results, undated).\n- **Krujë–Burreli:** \"terrible state of disrepair\".\n- **Theth–Valbona:** already excluded by you.\n- **Beach access roads off SH8:** unpaved.\n\nOsumi Canyon is fine only when approached from Berat, so don't continue from it onward to Përmet.\n\n**Komani ferry caveats:**\n- **Season end is unclear.** The operator says 15 Apr to 5 Nov, so 30 Oct – 2 Nov is inside the season. A search snippet from another page said 2 Nov, which I could not verify. Confirm directly with the operator.\n- **Timetable:** Koman 09:00 to Fierza (about 2.5 h), and Fierza 13:00 back to Koman ([operator](https://komanilakeferry.com/timetables-and-prices/); [Explorer Tom](https://explorertom.com/en/koman-lake-ferry-guide/), 2026).\n- **A same-day round trip returns after dark.** By my own arithmetic, the boat is back at Koman about 15:30, plus at least 2 h to Shkodër gives about 17:30, after sunset. This is my calculation, not from a source. It suggests sleeping near Shkodër or Koman.\n- **The car does not need to cross.** The ferry is a dead end, so you would leave the car at Koman and go as foot passengers. That avoids the vehicle-booking problem below.\n- **Car on the ferry:** online pre-booking is essential, priced at €7/m² ([Explorer Tom](https://explorertom.com/en/koman-lake-ferry-guide/)). One traveller in Nov 2025 had to upgrade to an SUV because of rental-company restrictions ([Perchance to Roam](https://perchancetoroam.com/2025/11/01/a-complete-guide-to-taking-albanias-komani-lake-ferry-with-or-without-a-car/), 1 Nov 2025). Check the rental terms.\n- **Road Shkodër to Koman (SH25):** about 60 km and about 2 h, with a narrow one-lane tunnel near the terminal ([Explorer Tom](https://explorertom.com/en/koman-lake-ferry-guide/)). It was in poor shape in Nov 2025, with the last 10 km \"completely ripped open\" ([Perchance to Roam](https://perchancetoroam.com/2025/11/01/a-complete-guide-to-taking-albanias-komani-lake-ferry-with-or-without-a-car/)). [inAlbania](https://www.inalbania.info/koman-road-transformed-to-boost-tourism-in-northern-albania/) (15 Sep 2026) reports the Vau i Dejës–Koman reconstruction as completed. It gives no surface or tunnel details, and the government page I tried to fetch was empty. I'd call this likely improved but not confirmed.\n\n**General driving:**\n- **Time estimates:** Google Maps underestimates mountain roads. Add 25% (\"2 h shows, allow 2.5\", [Endless Travellers](https://theendlesstravellers.com/driving-in-albania/), updated 22 Feb 2026). Tirana to Theth shows 3.5 h but takes about 5 h ([Along Dusty Roads](https://www.alongdustyroads.com/posts/driving-in-albania-car-hire), updated Jun 2025).\n- **Night driving:** avoid it. Village roads are unlit, with livestock and pedestrians (same Along Dusty Roads and Wikivoyage sources). You land at 20:30 on Friday, so keep the first night's drive short, and check that the rental desk is open at that hour (not researched).\n- **Flash floods:** flash flooding is possible in the Vjosa and Osum valleys after heavy rain, and the Lengarica canyon is inaccessible after heavy rain ([thingstodoinalbania](https://thingstodoinalbania.com/month/november/), undated, single source).\n- **Tolls:** the Llogara Tunnel and the A1 to Kosovo are tolled ([Endless Travellers](https://theendlesstravellers.com/driving-in-albania/)).\n- **Rules:** police speed checks are frequent, alcohol limit is 0.01% ([Wikivoyage](https://en.wikivoyage.org/wiki/Albania)).\n\n## 3. Seasonal notes (30 Oct – 2 Nov)\n\n- **Rain:** November is the rainiest month, about 12 rain days and 180 mm, with roughly 12–15 °C average temperatures ([Climates to Travel](https://www.climatestotravel.com/weatherbymonth/albania/november) and similar, undated).\n- **Unreliable figure:** thingstodoinalbania claims 25 °C highs and 2 in of rain in November. That contradicts every other source, so don't use its numbers.\n- **Snow:** snow is possible above 1,500 m before mid-November. Theth/Valbona is snow-covered ([thingstodoinalbania](https://thingstodoinalbania.com/month/november/), undated, single source).\n- **Fog:** persistent morning fog on Lake Shkodra and in the Korçë basin (same source).\n- **Lake Shkodra boats:** schedules shrink to weekends only (same source, unconfirmed). Your Sat and Sun fall on weekends.\n- **Daylight:** sources give sunset of 16:45–17:25 (Wanderlog and others, undated). Their sunrise figure of 05:46 is implausible, so I don't trust them. My own rough estimate for Tirana (CET, after clocks change on 25 Oct) is sunset about 16:30–16:40. That is earlier than your 17:00–17:30 assumption. The Weather/Season Agent should check this with Open-Meteo.\n- **Calendar:** 30 Oct is a Friday and 2 Nov a Monday, so the trip has two full days (Sat, Sun) plus the Friday-night arrival and the Monday return. Monday needs the car back at TIA by about 17:00.\n\n## 4. Route shapes for the Logistics Validator (not validated)\n\n- **Central/south:** Fri night near Tirana or Durrës. Sat via Karavasta and Apollonia to Berat. Sun via Osumi and Bogova to Gjirokastër. Mon Gjirokastër to TIA at about 3.5–4 h. The last leg is the tightest, needing an early start. Blue Eye and Përmet do not fit without dropping something.\n- **North (easier):** Fri night Tirana. Sat Shkodër, Rozafa and the lake. Sun Komani ferry from a Shkodër or Koman base. Mon return via the A1 (about 1h47).\n\nBoth fit the 3.5–4 h limit only if the Validator confirms the legs. The central/south option depends on avoiding SH74 and the Berat–Përmet canyon road.\n\n## 5. Gaps to close\n\n- Direct confirmation of the Komani ferry season end and whether foot passengers can get a seat in early November.\n- Rental terms: a 4-person vehicle, ferry carriage, and the airport desk's opening hours after a 20:30 landing.\n- Osumi Canyon water levels and access in early November. The one detailed source visited in summer.\n- Korçë and Voskopojë autumn conditions, if you want a southeastern alternative.",
  "accommodation": "## Nakvynės vietos (tik užsakytos)\n\nKeliautojas jau užsakė ir patvirtino konkrečius nakvynės objektus per booking.com nuorodas. Žemiau — tik šios užsakytos vietos, be papildomų alternatyvų.\n\n### 1. Tirana (penktadienis, 2026-10-30 → šeštadienis, 2026-10-31)\n\n**✅ Užsakyta — Hanna Apartment** — **51 €/naktį**\n- Rruga e Elbasanit, Tirana. Įvertinimas 9.0/10 (186 atsiliepimai).\n- Kondicionierius, nemokamas WiFi. Tinka 4 žmonėms (butas).\n- Nuoroda: https://www.booking.com/hotel/al/apartament-tirana8.lt.html\n\n### 2. Beratas (šeštadienis, 2026-10-31 → sekmadienis, 2026-11-01)\n\n**✅ Užsakyta — DD Villa** — **61 €/naktį**\n- Rruga Antipatrea, Beratas. Įvertinimas 8.8/10 (667 atsiliepimai).\n- Sodas, baras, bendra svetainė, miesto vaizdas, pusryčiai (bufetas/à la carte), privatus parkavimas (už papildomą mokestį), restoranas vietoje.\n- Nuoroda: https://www.booking.com/hotel/al/dd-villa.lt.html\n\n### 3. Vlorė / Radhimė (sekmadienis, 2026-11-01 → pirmadienis, 2026-11-02)\n\n**✅ Užsakyta — Hotel Liro – Adults Only** — **117 €/naktį**\n- Aleksandër Moisiu Street, Vlorė. Įvertinimas 8.6/10 (1295 atsiliepimai).\n- Privatus paplūdimio ruožas, lauko baseinas, nemokamas parkavimas, restoranas/baras, pusryčiai, vaizdas į jūrą nuo balkono. Autobusų stotelė priešais viešbutį.\n- Nuoroda: https://www.booking.com/hotel/al/liro.lt.html\n- ⚠️ Pastaba: \"Adults Only\" — jei grupėje yra vaikų, šią vietą reikėtų pakeisti.\n\n**Biudžeto suma nakvynėms (3 naktys, visai grupei):** 51 + 61 + 117 = **229 €**",
  "booking_search": [
    {
      "city": "Tirana",
      "name": "Hanna Apartment",
      "checkin": "2026-10-30",
      "checkout": "2026-10-31",
      "nights": 1,
      "price_per_night_eur": 51,
      "url": "https://www.booking.com/searchresults.html?ss=Hanna+Apartment%2C+Tirana&checkin=2026-10-30&checkout=2026-10-31&group_adults=4&group_children=0&no_rooms=1"
    },
    {
      "city": "Berat",
      "name": "DD Villa",
      "checkin": "2026-10-31",
      "checkout": "2026-11-01",
      "nights": 1,
      "price_per_night_eur": 61,
      "url": "https://www.booking.com/searchresults.html?ss=DD+Villa%2C+Berat&checkin=2026-10-31&checkout=2026-11-01&group_adults=4&group_children=0&no_rooms=1"
    },
    {
      "city": "Vlorë",
      "name": "Hotel Liro - Adults Only",
      "checkin": "2026-11-01",
      "checkout": "2026-11-02",
      "nights": 1,
      "price_per_night_eur": 117,
      "url": "https://www.booking.com/searchresults.html?ss=Hotel+Liro+-+Adults+Only%2C+Vlor%C3%AB&checkin=2026-11-01&checkout=2026-11-02&group_adults=4&group_children=0&no_rooms=1"
    }
  ],
  "stays": [
    {
      "url": "https://www.booking.com/hotel/al/apartament-tirana8.lt.html",
      "name": "Hanna Apartment",
      "address": "Rruga e Elbasanit, 1035 Tirana, Albanija, 1035, Rruga e Elbasanit, Albanija",
      "description": "Hanna Apartment is located in Tirana. This apartment provides air-conditioned accommodation with free WiFi.",
      "full_description": null,
      "facilities": null,
      "rating": 9.0,
      "rating_scale": 10,
      "review_count": 186,
      "photo_urls": [
        "https://cf.bstatic.com/xdata/images/hotel/max1024x768/633887464.jpg?k=b976c4febe171b551f477e9eee870608b6dc963117d876c793f0d9f4e74a10c1&o=&hp=1",
        "https://cf.bstatic.com/xdata/images/hotel/max1024x768/633887550.jpg?k=694dc1002849285d2f750017340c1edd34a96dd80c7fbc5b6481ab43eadda7c0&o=&hp=1",
        "https://cf.bstatic.com/xdata/images/hotel/max1024x768/633887291.jpg?k=4963ffaa4c10e0fd9f47b51e58b930fc53eff67747c24a914957854aecfefbc0&o=&hp=1",
        "https://cf.bstatic.com/xdata/images/hotel/max1024x768/633889677.jpg?k=5da3b33dfa81e6240d74fe7d36bf94844df25d861a8cfb0f6e6d273f1eb9459a&o=&hp=1",
        "https://cf.bstatic.com/xdata/images/hotel/max1024x768/651343123.jpg?k=5441b1e29d0d9b0725ae1274688a078b2e764fba7c641900e5a8cc9a87c5bc84&o=&hp=1"
      ],
      "photos": [
        {
          "stop_name": "Hanna Apartment",
          "local_path": "images/stay-hanna-apartment-1.jpg",
          "commons_filename": "",
          "license": "© apgyvendinimo įstaiga / Booking.com",
          "author": null,
          "source_url": "https://www.booking.com/hotel/al/apartament-tirana8.lt.html",
          "size_bytes": 110275
        },
        {
          "stop_name": "Hanna Apartment",
          "local_path": "images/stay-hanna-apartment-2.jpg",
          "commons_filename": "",
          "license": "© apgyvendinimo įstaiga / Booking.com",
          "author": null,
          "source_url": "https://www.booking.com/hotel/al/apartament-tirana8.lt.html",
          "size_bytes": 32003
        },
        {
          "stop_name": "Hanna Apartment",
          "local_path": "images/stay-hanna-apartment-3.jpg",
          "commons_filename": "",
          "license": "© apgyvendinimo įstaiga / Booking.com",
          "author": null,
          "source_url": "https://www.booking.com/hotel/al/apartament-tirana8.lt.html",
          "size_bytes": 55703
        },
        {
          "stop_name": "Hanna Apartment",
          "local_path": "images/stay-hanna-apartment-4.jpg",
          "commons_filename": "",
          "license": "© apgyvendinimo įstaiga / Booking.com",
          "author": null,
          "source_url": "https://www.booking.com/hotel/al/apartament-tirana8.lt.html",
          "size_bytes": 53502
        },
        {
          "stop_name": "Hanna Apartment",
          "local_path": "images/stay-hanna-apartment-5.jpg",
          "commons_filename": "",
          "license": "© apgyvendinimo įstaiga / Booking.com",
          "author": null,
          "source_url": "https://www.booking.com/hotel/al/apartament-tirana8.lt.html",
          "size_bytes": 54202
        }
      ]
    },
    {
      "url": "https://www.booking.com/hotel/al/dd-villa.lt.html",
      "name": "DD Villa",
      "address": "Rruga Antipatrea, 5001 Beratis, Albanija, 5001, Rruga Antipatrea, Albanija",
      "description": "Situated in Berat, DD Villa features a garden, a bar and a shared lounge. The property has city views. Private parking can be arranged at an extra charge.",
      "full_description": [
        "Situated in Berat, DD Villa features a garden, a bar and a shared lounge. The property has city views. Private parking can be arranged at an extra charge. The bed and breakfast will provide guests with air-conditioned units offering a wardrobe, a kettle, a dishwasher, a microwave, a safety deposit box, a flat-screen TV and a private bathroom with a bidet. Free WiFi is accessible to all guests, while certain rooms are equipped with a terrace. At the bed and breakfast, every unit is equipped with bed linen and towels. A buffet, à la carte or continental breakfast is available at the property. Guests are welcome to eat in the on-site family-friendly restaurant, which is open for dinner, lunch, brunch and high tea. Sightseeing tours are available around the property. Both a bicycle rental service and a car rental service are available at the bed and breakfast, while cycling can be enjoyed nearby. Tirana International Mother Teresa Airport is 120 km from the property, and the property offers a paid airport shuttle service."
      ],
      "facilities": [
        "Populiariausi patogumai",
        "Privati automobilių stovėjimo aikštelė",
        "Spartus nemokamas belaidis internetas (101 Mbps)",
        "Pervežimas iš / į oro uostą",
        "Numeriai nerūkantiems",
        "Numeriai šeimai",
        "Aptarnavimas numeriuose",
        "Restoranas",
        "Baras",
        "Nuostabūs pusryčiai"
      ],
      "rating": 8.8,
      "rating_scale": 10,
      "review_count": 667,
      "photo_urls": [
        "https://cf.bstatic.com/xdata/images/hotel/max1024x768/529582807.jpg?k=731fe174d8d2b7402280e7c8008fdd355a874d76e0b7f03f1f516ad3c92ccd4f&o=&hp=1",
        "https://cf.bstatic.com/xdata/images/hotel/max1024x768/921271115.jpg?k=714680e569beb3f835a5ab5f15daaf4460dda2cd2509890599543048e17af49a&o=&hp=1",
        "https://cf.bstatic.com/xdata/images/hotel/max1024x768/529582816.jpg?k=8c6581a00d3c484f9e62bbaa3ba21bf08b13e50ccda4cf1e32c52876fb08a13d&o=&hp=1",
        "https://cf.bstatic.com/xdata/images/hotel/max1024x768/544036358.jpg?k=03e5cee7c142331675268001c541cbe0e4cb64ba67f8d850dc1cf05be6ee1024&o=&hp=1",
        "https://cf.bstatic.com/xdata/images/hotel/max1024x768/529582821.jpg?k=58830e6a252b81f2a06faccae174fad12a474f063ed8162b382a1ac3626b93d9&o=&hp=1"
      ],
      "photos": [
        {
          "stop_name": "DD Villa",
          "local_path": "images/stay-dd-villa-1.jpg",
          "commons_filename": "",
          "license": "© apgyvendinimo įstaiga / Booking.com",
          "author": null,
          "source_url": "https://www.booking.com/hotel/al/dd-villa.lt.html",
          "size_bytes": 154626
        },
        {
          "stop_name": "DD Villa",
          "local_path": "images/stay-dd-villa-2.jpg",
          "commons_filename": "",
          "license": "© apgyvendinimo įstaiga / Booking.com",
          "author": null,
          "source_url": "https://www.booking.com/hotel/al/dd-villa.lt.html",
          "size_bytes": 69651
        },
        {
          "stop_name": "DD Villa",
          "local_path": "images/stay-dd-villa-3.jpg",
          "commons_filename": "",
          "license": "© apgyvendinimo įstaiga / Booking.com",
          "author": null,
          "source_url": "https://www.booking.com/hotel/al/dd-villa.lt.html",
          "size_bytes": 99758
        },
        {
          "stop_name": "DD Villa",
          "local_path": "images/stay-dd-villa-4.jpg",
          "commons_filename": "",
          "license": "© apgyvendinimo įstaiga / Booking.com",
          "author": null,
          "source_url": "https://www.booking.com/hotel/al/dd-villa.lt.html",
          "size_bytes": 99712
        },
        {
          "stop_name": "DD Villa",
          "local_path": "images/stay-dd-villa-5.jpg",
          "commons_filename": "",
          "license": "© apgyvendinimo įstaiga / Booking.com",
          "author": null,
          "source_url": "https://www.booking.com/hotel/al/dd-villa.lt.html",
          "size_bytes": 129326
        }
      ]
    },
    {
      "url": "https://www.booking.com/hotel/al/liro.lt.html",
      "name": "Hotel Liro - Adults Only",
      "address": "Aleksandër Moisiu Street, 9405 Vliorė, Albanija, 9405, Aleksandër Moisiu Street, Albanija",
      "description": "Located in Vlorë, Hotel Liro - Adults Only offers a private beach area with free-to-use sun loungers and parasols.",
      "full_description": [
        "Located in Vlorë, Hotel Liro - Adults Only offers a private beach area with free-to-use sun loungers and parasols. The on-site bar and restaurant offers a spacious terrace where guests can enjoy the Mediterranean dishes it serves. Free WiFi access is available throughout the property. All the rooms are air-conditioned and come with a furnished balcony overlooking the sea. Each room is equipped with satellite TV, a minibar and a safe. Featuring a shower, private bathrooms also come with a hairdryer and free toiletries. Hotel Liro - Adults Only offers an array of activities can be enjoyed on site or in the surroundings, including windsurfing. The cenre of Vlorë and the scenic outlook of Kuzum Baba can be found within a 6-km radius. The Archaeological Park of Oricum is 10 km from Liro Hotel. Llogara National Park is 25 km away. The local bus stop is right in front of the hotel. Tirana Airport is 150 km away. The property offers free parking."
      ],
      "facilities": [
        "Populiariausi patogumai",
        "Lauko baseinas",
        "Nemokama vieta automobiliui",
        "Šalia paplūdimio",
        "Nemokamas belaidis internetas",
        "Numeriai šeimai",
        "Restoranas",
        "Numeriai nerūkantiems",
        "Baras",
        "Privati paplūdimio dalis",
        "Nuostabūs pusryčiai"
      ],
      "rating": 8.6,
      "rating_scale": 10,
      "review_count": 1295,
      "photo_urls": [
        "https://cf.bstatic.com/xdata/images/hotel/max1024x768/506995294.jpg?k=23925d61528b241c35e7b43446d3f11a9faa202b08e9903c82a6e3cb2afa43d7&o=&hp=1",
        "https://cf.bstatic.com/xdata/images/hotel/max1024x768/506995475.jpg?k=8b2bd840a2ed21d4d6da7442afc978dd5073fc1eb1d9a567413fdab748546eac&o=&hp=1",
        "https://cf.bstatic.com/xdata/images/hotel/max1024x768/556057394.jpg?k=575cc81ebc625197b6b6c6af18c2ec9a6eda54fa3ed14e29ecef4935b13b27a6&o=&hp=1",
        "https://cf.bstatic.com/xdata/images/hotel/max1024x768/506995518.jpg?k=2db992e93cda20eb611af0c65c6d59f388efc2150e468dfbfae8e8e3fbb3b665&o=&hp=1",
        "https://cf.bstatic.com/xdata/images/hotel/max1024x768/506995661.jpg?k=d3755c0ed1215710923e75d5050056023d41ecd92820d69af21aa384123992dd&o=&hp=1"
      ],
      "photos": [
        {
          "stop_name": "Hotel Liro - Adults Only",
          "local_path": "images/stay-hotel-liro-adults-only-1.jpg",
          "commons_filename": "",
          "license": "© apgyvendinimo įstaiga / Booking.com",
          "author": null,
          "source_url": "https://www.booking.com/hotel/al/liro.lt.html",
          "size_bytes": 125824
        },
        {
          "stop_name": "Hotel Liro - Adults Only",
          "local_path": "images/stay-hotel-liro-adults-only-2.jpg",
          "commons_filename": "",
          "license": "© apgyvendinimo įstaiga / Booking.com",
          "author": null,
          "source_url": "https://www.booking.com/hotel/al/liro.lt.html",
          "size_bytes": 238091
        },
        {
          "stop_name": "Hotel Liro - Adults Only",
          "local_path": "images/stay-hotel-liro-adults-only-3.jpg",
          "commons_filename": "",
          "license": "© apgyvendinimo įstaiga / Booking.com",
          "author": null,
          "source_url": "https://www.booking.com/hotel/al/liro.lt.html",
          "size_bytes": 133915
        },
        {
          "stop_name": "Hotel Liro - Adults Only",
          "local_path": "images/stay-hotel-liro-adults-only-4.jpg",
          "commons_filename": "",
          "license": "© apgyvendinimo įstaiga / Booking.com",
          "author": null,
          "source_url": "https://www.booking.com/hotel/al/liro.lt.html",
          "size_bytes": 211665
        },
        {
          "stop_name": "Hotel Liro - Adults Only",
          "local_path": "images/stay-hotel-liro-adults-only-5.jpg",
          "commons_filename": "",
          "license": "© apgyvendinimo įstaiga / Booking.com",
          "author": null,
          "source_url": "https://www.booking.com/hotel/al/liro.lt.html",
          "size_bytes": 64880
        }
      ]
    }
  ],
  "itinerary": "{\"days\":[{\"number\":1,\"title\":\"Atvykimas į Tiraną\",\"stops\":[{\"name\":\"Tiranos oro uostas (TIA)\",\"lat\":41.4147,\"lon\":19.7206,\"arrive\":\"20:30\",\"depart\":\"21:00\",\"maps_query\":\"Tirana International Airport Nënë Tereza, Albania\",\"google_maps_url\":\"https://www.google.com/maps/search/?api=1&query=Tirana%20International%20Airport%20N%C3%ABn%C3%AB%20Tereza%2C%20Albania\",\"notes\":\"Skrydis iš Varšuvos nusileidžia 20:30. Automobilio nuomos (VW Tiguan ar panašus visureigis, tinka 4 žmonėms ir bagažui, su Papildomo vairuotojo ir pilnos apsaugos draudimu) atsiėmimas 21:00. Tą pačią vietą reikės grąžinti automobilį lapkričio 2 d. iki 17:00.\",\"arrive_by\":\"car\",\"transit\":\"\"},{\"name\":\"Hanna Apartment\",\"lat\":41.3192,\"lon\":19.8294,\"arrive\":\"21:20\",\"depart\":\"21:20\",\"maps_query\":\"Apartament Tirana8, Rruga e Elbasanit, Tirana, Albania\",\"google_maps_url\":\"https://www.google.com/maps/search/?api=1&query=Apartament%20Tirana8%2C%20Rruga%20e%20Elbasanit%2C%20Tirana%2C%20Albania\",\"notes\":\"Pirma nakvynė – butas Rruga e Elbasanit, kondicionierius, nemokamas WiFi, tinka 4 žmonėms. Kelias nuo oro uosto apie 20 min, vėlai vakare eismas ramus.\",\"arrive_by\":\"car\",\"transit\":\"\"}],\"driving_minutes\":20,\"overnight_city\":\"Tirana\"},{\"number\":2,\"title\":\"Krujė, Belšo ežeras ir Beratas\",\"stops\":[{\"name\":\"Krujos pilis ir Skenderbego muziejus bei Senasis bazaras\",\"lat\":41.5086,\"lon\":19.7919,\"arrive\":\"09:45\",\"depart\":\"10:30\",\"maps_query\":\"Kalaja e Krujës, Krujë, Albania\",\"google_maps_url\":\"https://www.google.com/maps/search/?api=1&query=Kalaja%20e%20Kruj%C3%ABs%2C%20Kruj%C3%AB%2C%20Albania\",\"notes\":\"Skenderbego muziejus pilies viduje, bilietas apie 200 lekų (~2 €). Žiemos darbo laikas apytiksliai 09:00–16:00 – darbo laiką verta pasitikrinti. Prie pilies – senasis bazaras su amatininkų dirbiniais ir suvenyrais.\",\"arrive_by\":\"car\",\"transit\":\"\"},{\"name\":\"Belšo ežeras (apžvalgos sustojimas)\",\"lat\":41.0931,\"lon\":19.8828,\"arrive\":\"12:02\",\"depart\":\"12:17\",\"maps_query\":\"Liqeni i Belshit, Belsh, Albania\",\"google_maps_url\":\"https://www.google.com/maps/search/?api=1&query=Liqeni%20i%20Belshit%2C%20Belsh%2C%20Albania\",\"notes\":\"Trumpas sustojimas pakeliui – gražus Dumrės plokščiakalnio ir ežerų vaizdas, proga kavai ir nuotraukai.\",\"arrive_by\":\"car\",\"transit\":\"\"},{\"name\":\"Pietūs „Lili Homemade Food“\",\"lat\":40.7064,\"lon\":19.9513,\"arrive\":\"13:54\",\"depart\":\"14:55\",\"maps_query\":\"Lili Homemade Food, Berat, Albania\",\"google_maps_url\":\"https://www.google.com/maps/search/?api=1&query=Lili%20Homemade%20Food%2C%20Berat%2C%20Albania\",\"notes\":\"Populiarus namų virtuvės restoranas Mangalemo kvartale, vietiniai patiekalai.\",\"arrive_by\":\"car\",\"transit\":\"\"},{\"name\":\"Mangalemo senasis kvartalas\",\"lat\":40.706,\"lon\":19.951,\"arrive\":\"14:55\",\"depart\":\"15:09\",\"maps_query\":\"Mangalem Quarter, Berat, Albania\",\"google_maps_url\":\"https://www.google.com/maps/search/?api=1&query=Mangalem%20Quarter%2C%20Berat%2C%20Albania\",\"notes\":\"Pasivaikščiojimas osmanų laikų gatvelėmis su garsiaisiais „tūkstančio langų“ namais.\",\"arrive_by\":\"walk\",\"transit\":\"\"},{\"name\":\"Berato pilis (Kalaja e Beratit)\",\"lat\":40.7014,\"lon\":19.9447,\"arrive\":\"15:29\",\"depart\":\"16:13\",\"maps_query\":\"Kalaja e Beratit, Berat, Albania\",\"google_maps_url\":\"https://www.google.com/maps/search/?api=1&query=Kalaja%20e%20Beratit%2C%20Berat%2C%20Albania\",\"notes\":\"Gyvenama pilis su bizantiškomis bažnyčiomis. Įėjimas į teritoriją laisvas, Onufrijaus muziejuje bilietas apie 200 lekų – darbo laiką verta pasitikrinti.\",\"arrive_by\":\"walk\",\"transit\":\"\"},{\"name\":\"Goricos tiltas ir kvartalas\",\"lat\":40.7021,\"lon\":19.9497,\"arrive\":\"16:38\",\"depart\":\"17:08\",\"maps_query\":\"Ura e Goricës, Berat, Albania\",\"google_maps_url\":\"https://www.google.com/maps/search/?api=1&query=Ura%20e%20Goric%C3%ABs%2C%20Berat%2C%20Albania\",\"notes\":\"Osmanų laikų akmeninis tiltas per Osumo upę – ypač gražus prieblandoje, puikus vaizdas į Mangalemą.\",\"arrive_by\":\"walk\",\"transit\":\"\"},{\"name\":\"DD Villa\",\"lat\":40.7057,\"lon\":19.952,\"arrive\":\"17:23\",\"depart\":\"17:23\",\"maps_query\":\"DD Villa, Rruga Antipatrea, Berat, Albania\",\"google_maps_url\":\"https://www.google.com/maps/search/?api=1&query=DD%20Villa%2C%20Rruga%20Antipatrea%2C%20Berat%2C%20Albania\",\"notes\":\"Nakvynė Berate – sodas, baras, pusryčiai, privatus parkavimas už papildomą mokestį.\",\"arrive_by\":\"walk\",\"transit\":\"\"}],\"driving_minutes\":180,\"overnight_city\":\"Berat\"},{\"number\":3,\"title\":\"Osumio kanjonas ir Vlorės pakrantė\",\"stops\":[{\"name\":\"Osumio kanjono apžvalgos aikštelė\",\"lat\":40.5044,\"lon\":20.227,\"arrive\":\"10:15\",\"depart\":\"11:00\",\"maps_query\":\"Kanioni i Osumit, Çorovodë, Albania\",\"google_maps_url\":\"https://www.google.com/maps/search/?api=1&query=Kanioni%20i%20Osumit%2C%20%C3%87orovod%C3%AB%2C%20Albania\",\"notes\":\"Vienas gražiausių gamtos vaizdų kelyje – kanjono apžvalgos aikštelė prie kelio, patogi stovėjimo vieta.\",\"arrive_by\":\"car\",\"transit\":\"\"},{\"name\":\"Pietūs Vlorės marina\",\"lat\":40.458,\"lon\":19.485,\"arrive\":\"13:51\",\"depart\":\"14:51\",\"maps_query\":\"Marina e Vlorës, Vlorë, Albania\",\"google_maps_url\":\"https://www.google.com/maps/search/?api=1&query=Marina%20e%20Vlor%C3%ABs%2C%20Vlor%C3%AB%2C%20Albania\",\"notes\":\"Vlorės uosto promenadoje daug žuvies restoranų – pasirinkite bet kurį su šviežia dienos žuvimi.\",\"arrive_by\":\"car\",\"transit\":\"\"},{\"name\":\"Vlorės pakrantės promenada (Lungomare)\",\"lat\":40.458,\"lon\":19.485,\"arrive\":\"14:51\",\"depart\":\"15:51\",\"maps_query\":\"Lungomare, Vlorë, Albania\",\"google_maps_url\":\"https://www.google.com/maps/search/?api=1&query=Lungomare%2C%20Vlor%C3%AB%2C%20Albania\",\"notes\":\"Pasivaikščiojimas pakrante, vaizdas į Jonų jūrą ir Sazano salą.\",\"arrive_by\":\"walk\",\"transit\":\"\"},{\"name\":\"Hotel Liro – Adults Only\",\"lat\":40.455,\"lon\":19.484,\"arrive\":\"16:01\",\"depart\":\"16:01\",\"maps_query\":\"Hotel Liro Adults Only, Rruga Aleksandër Moisiu, Vlorë, Albania\",\"google_maps_url\":\"https://www.google.com/maps/search/?api=1&query=Hotel%20Liro%20Adults%20Only%2C%20Rruga%20Aleksand%C3%ABr%20Moisiu%2C%20Vlor%C3%AB%2C%20Albania\",\"notes\":\"Nakvynė Vlorėje – privatus paplūdimio ruožas, lauko baseinas, vaizdas į jūrą nuo balkono. Tik suaugusiems.\",\"arrive_by\":\"car\",\"transit\":\"\"}],\"driving_minutes\":205,\"overnight_city\":\"Vlorë\"},{\"number\":4,\"title\":\"Divjakė-Karavasta ir išvykimas\",\"stops\":[{\"name\":\"Karavastos lagūnos Lankytojų centras ir apžvalgos bokštas\",\"lat\":40.979,\"lon\":19.466,\"arrive\":\"10:10\",\"depart\":\"13:20\",\"maps_query\":\"Qendra e Vizitorëve Divjakë-Karavasta, Divjakë, Albania\",\"google_maps_url\":\"https://www.google.com/maps/search/?api=1&query=Qendra%20e%20Vizitor%C3%ABve%20Divjak%C3%AB-Karavasta%2C%20Divjak%C3%AB%2C%20Albania\",\"notes\":\"Automobilį palikite Lankytojų centro aikštelėje – čia veda geras asfaltuotas/tvarkingas kelias, o čia pat yra apie 35 m aukščio apžvalgos bokštas su gražiu vaizdu į lagūną. Jei norite pasiekti giliau lagūnoje esantį bokštą, paskutinius 1–2 km (ir tiek pat atgal) reikia nueiti pėsčiomis – nuomotam automobiliui tas kelias po lietaus būna dumblinas ir netinkamas. Rudenį čia gerai matomi rausvieji pelikanai ir flamingai. Nedidelis mokestis automobiliui įvažiuojant į parką.\",\"arrive_by\":\"car\",\"transit\":\"\"},{\"name\":\"Pietūs Divjakės paplūdimyje\",\"lat\":40.9958,\"lon\":19.4705,\"arrive\":\"13:30\",\"depart\":\"14:30\",\"maps_query\":\"Plazhi i Divjakës, Divjakë, Albania\",\"google_maps_url\":\"https://www.google.com/maps/search/?api=1&query=Plazhi%20i%20Divjak%C3%ABs%2C%20Divjak%C3%AB%2C%20Albania\",\"notes\":\"Paplūdimio žuvies kioskai ir restoranėliai – šviežia žuvis ir jūros gėrybės.\",\"arrive_by\":\"car\",\"transit\":\"\"},{\"name\":\"Tiranos oro uostas (TIA) – automobilio grąžinimas ir skrydis namo\",\"lat\":41.4147,\"lon\":19.7206,\"arrive\":\"16:15\",\"depart\":\"19:05\",\"maps_query\":\"Tirana International Airport Nënë Tereza, Albania\",\"google_maps_url\":\"https://www.google.com/maps/search/?api=1&query=Tirana%20International%20Airport%20N%C3%ABn%C3%AB%20Tereza%2C%20Albania\",\"notes\":\"Automobilio grąžinimas (reikia iki 17:00) – atsargos laiko pakaks. Skrydis į Varšuvą išskrenda 19:05 – registracijai ir saugumo patikrai liks pakankamai laiko.\",\"arrive_by\":\"car\",\"transit\":\"\"}],\"driving_minutes\":170,\"overnight_city\":\"Nėra (skrydis namo)\"}]}",
  "day_routes": [
    {
      "day": 1,
      "title": "Atvykimas į Tiraną",
      "urls": [
        "https://www.google.com/maps/dir/?api=1&origin=Tirana+International+Airport+N%C3%ABn%C3%AB+Tereza,+Albania&destination=Apartament+Tirana8,+Rruga+e+Elbasanit,+Tirana,+Albania&travelmode=driving"
      ],
      "modes": [
        "car"
      ]
    },
    {
      "day": 2,
      "title": "Krujė, Belšo ežeras ir Beratas",
      "urls": [
        "https://www.google.com/maps/dir/?api=1&origin=Kalaja+e+Kruj%C3%ABs,+Kruj%C3%AB,+Albania&destination=Lili+Homemade+Food,+Berat,+Albania&travelmode=driving&waypoints=Liqeni+i+Belshit,+Belsh,+Albania",
        "https://www.google.com/maps/dir/?api=1&origin=Lili+Homemade+Food,+Berat,+Albania&destination=DD+Villa,+Rruga+Antipatrea,+Berat,+Albania&travelmode=walking&waypoints=Mangalem+Quarter,+Berat,+Albania|Kalaja+e+Beratit,+Berat,+Albania|Ura+e+Goric%C3%ABs,+Berat,+Albania"
      ],
      "modes": [
        "car",
        "walk"
      ]
    },
    {
      "day": 3,
      "title": "Osumio kanjonas ir Vlorės pakrantė",
      "urls": [
        "https://www.google.com/maps/dir/?api=1&origin=Kanioni+i+Osumit,+%C3%87orovod%C3%AB,+Albania&destination=Hotel+Liro+Adults+Only,+Rruga+Aleksand%C3%ABr+Moisiu,+Vlor%C3%AB,+Albania&travelmode=driving&waypoints=Marina+e+Vlor%C3%ABs,+Vlor%C3%AB,+Albania"
      ],
      "modes": [
        "car"
      ]
    },
    {
      "day": 4,
      "title": "Divjakė-Karavasta ir išvykimas",
      "urls": [
        "https://www.google.com/maps/dir/?api=1&origin=Qendra+e+Vizitor%C3%ABve+Divjak%C3%AB-Karavasta,+Divjak%C3%AB,+Albania&destination=Tirana+International+Airport+N%C3%ABn%C3%AB+Tereza,+Albania&travelmode=driving&waypoints=Plazhi+i+Divjak%C3%ABs,+Divjak%C3%AB,+Albania"
      ],
      "modes": [
        "car"
      ]
    }
  ],
  "logistics": {
    "legs": [
      {
        "day": 1,
        "from_stop": "Tiranos oro uostas (TIA)",
        "to_stop": "Hanna Apartment",
        "mode": "car",
        "distance_km": 19.0,
        "minutes": 31,
        "transit_kind": "",
        "transit": "",
        "road": "asfaltuotas kelias iš oro uosto į Tiraną, Rruga e Elbasanit rajoną, lygus reljefas",
        "icon": "🚗"
      },
      {
        "day": 2,
        "from_stop": "Krujos pilis ir Skenderbego muziejus bei Senasis bazaras",
        "to_stop": "Belšo ežeras (apžvalgos sustojimas)",
        "mode": "car",
        "distance_km": 91.0,
        "minutes": 92,
        "transit_kind": "",
        "transit": "",
        "road": "asfaltuotas kelias/greitkelis per Tiranos-Elbasano lygumą link Belšo",
        "icon": "🚗"
      },
      {
        "day": 2,
        "from_stop": "Belšo ežeras (apžvalgos sustojimas)",
        "to_stop": "Pietūs „Lili Homemade Food“",
        "mode": "car",
        "distance_km": 62.0,
        "minutes": 97,
        "transit_kind": "",
        "transit": "",
        "road": "asfaltuotas kelias per kalvas link Berato",
        "icon": "🚗"
      },
      {
        "day": 2,
        "from_stop": "Pietūs „Lili Homemade Food“",
        "to_stop": "Mangalemo senasis kvartalas",
        "mode": "walk",
        "distance_km": 0.1,
        "minutes": 1,
        "transit_kind": "",
        "transit": "",
        "road": "per senamiestį",
        "icon": "🚶"
      },
      {
        "day": 2,
        "from_stop": "Mangalemo senasis kvartalas",
        "to_stop": "Berato pilis (Kalaja e Beratit)",
        "mode": "walk",
        "distance_km": 1.0,
        "minutes": 14,
        "transit_kind": "",
        "transit": "",
        "road": "pėsčiųjų takas į kalvą prie pilies",
        "icon": "🚶"
      },
      {
        "day": 2,
        "from_stop": "Berato pilis (Kalaja e Beratit)",
        "to_stop": "Goricos tiltas ir kvartalas",
        "mode": "walk",
        "distance_km": 0.6,
        "minutes": 9,
        "transit_kind": "",
        "transit": "",
        "road": "pėsčiomis žemyn nuo pilies prie Goricos tilto",
        "icon": "🚶"
      },
      {
        "day": 2,
        "from_stop": "Goricos tiltas ir kvartalas",
        "to_stop": "DD Villa",
        "mode": "walk",
        "distance_km": 0.8,
        "minutes": 10,
        "transit_kind": "",
        "transit": "",
        "road": "pėsčiomis per tiltą atgal į Mangalemo kvartalą",
        "icon": "🚶"
      },
      {
        "day": 3,
        "from_stop": "Osumio kanjono apžvalgos aikštelė",
        "to_stop": "Pietūs Vlorės marina",
        "mode": "car",
        "distance_km": 153.0,
        "minutes": 171,
        "transit_kind": "",
        "transit": "",
        "road": "asfaltuotas kelias atgal pro Beratą ir toliau per Fierą (greitkelis) į Vlorę",
        "icon": "🚗"
      },
      {
        "day": 3,
        "from_stop": "Pietūs Vlorės marina",
        "to_stop": "Vlorės pakrantės promenada (Lungomare)",
        "mode": "walk",
        "distance_km": 0.0,
        "minutes": 1,
        "transit_kind": "",
        "transit": "",
        "road": "ta pati vieta Vlorės uoste",
        "icon": "🚶"
      },
      {
        "day": 3,
        "from_stop": "Vlorės pakrantės promenada (Lungomare)",
        "to_stop": "Hotel Liro – Adults Only",
        "mode": "car",
        "distance_km": 0.3,
        "minutes": 1,
        "transit_kind": "",
        "transit": "",
        "road": "ta pati vieta Vlorės pakrantėje",
        "icon": "🚗"
      },
      {
        "day": 4,
        "from_stop": "Karavastos lagūnos Lankytojų centras ir apžvalgos bokštas",
        "to_stop": "Pietūs Divjakės paplūdimyje",
        "mode":
… (sutrumpinta, iš viso 103650 simbolių)
```

Current page:
[HTML puslapis, 79 KB — nerodomas]

Reply with the complete HTML document itself as your entire answer, starting with <!DOCTYPE html>. Do not write files, and do not describe or summarise what you did.

</details>

<details><summary><b>Atsakymas</b></summary>

```
 Berate – kaip pagrindiniame plane.</p>
    </div>
    <p>Bendras vairavimo laikas: apie 179 min.</p>
    <a class="route-btn" href="https://www.google.com/maps/dir/?api=1&origin=Kalaja+e+Kruj%C3%ABs,+Kruj%C3%AB,+Albania&destination=Lili+Homemade+Food,+Berat,+Albania&travelmode=driving&waypoints=Liqeni+i+Belshit,+Belsh,+Albania" target="_blank">🧭 Plano B maršrutas: 🚗 Automobiliu</a>
    <a class="route-btn" href="https://www.google.com/maps/dir/?api=1&origin=Lili+Homemade+Food,+Berat,+Albania&destination=DD+Villa,+Rruga+Antipatrea,+Berat,+Albania&travelmode=walking&waypoints=National+Ethnographic+Museum,+Berat,+Albania|Restaurant+Klea,+Kalaja+e+Beratit,+Berat,+Albania" target="_blank">🧭 Plano B maršrutas: 🚶 Pėsčiomis</a>
    <p><strong>Patarimas:</strong> Berato etnografijos muziejus žiemą (nuo lapkričio 1 d.) dirba antradieniais–šeštadieniais 9:00–16:00, spalio 31 d. darbo laiką verta patikrinti iš anksto telefonu; restoranas „Klea“ pilyje dirba visą dieną, tad tinka ir vėlesniam vizitui nepaisant oro.</p>
  </details>
</section>

<!-- ===================== DAY 3 ===================== -->
<section id="day3">
  <div class="day-header">
    <h2>📅 3 diena · sekmadienis, 2026-11-01 — Osumio kanjonas ir Vlorės pakrantė</h2>
    <span class="weather-note">⛈ Vlorėje tikėtina perkūnija (54 % tikimybė, ~14,7 mm), 14–18 °C, vėjas iki 7,2 km/h.</span>
    <p class="plan-b-hint">Didelė lietaus tikimybė – šiandien Planas B gali būti geresnis pasirinkimas.</p>
  </div>
  <a class="route-btn" href="https://www.google.com/maps/dir/?api=1&origin=Kanioni+i+Osumit,+%C3%87orovod%C3%AB,+Albania&destination=Hotel+Liro+Adults+Only,+Rruga+Aleksand%C3%ABr+Moisiu,+Vlor%C3%AB,+Albania&travelmode=driving&waypoints=Marina+e+Vlor%C3%ABs,+Vlor%C3%AB,+Albania" target="_blank">🧭 Dienos maršrutas Google Maps</a>

  <div class="stop">
    <div class="stop-header"><span class="stop-time">10:15</span> Osumio kanjono apžvalgos aikštelė <a class="maps-link" href="https://www.google.com/maps/search/?api=1&query=Kanioni%20i%20Osumit%2C%20%C3%87orovod%C3%AB%2C%20Albania" target="_blank">📍 Google Maps</a></div>
    <img class="spot-thumb" src="images/osumio-kanjono-ap-valgos-aik-tel-8aa2a495.jpg" alt="Osumio kanjonas">
    <div class="credit">Nuotrauka: Pasztilla aka Attila Terbócs, CC BY-SA 4.0, <a href="https://commons.wikimedia.org/wiki/File:Osum_Canyon,_2016-07_02.jpg" target="_blank">šaltinis</a></div>
    <p class="notes">Vienas gražiausių gamtos vaizdų kelyje – kanjono apžvalgos aikštelė prie kelio, patogi stovėjimo vieta.</p>
  </div>

  <div class="leg">🚗 153 km · 171 min – asfaltuotas kelias atgal pro Beratą ir toliau per Fierą (greitkelis) į Vlorę</div>

  <div class="stop">
    <div class="stop-header"><span class="stop-time">13:51</span> Pietūs Vlorės marina <a class="maps-link" href="https://www.google.com/maps/search/?api=1&query=Marina%20e%20Vlor%C3%ABs%2C%20Vlor%C3%AB%2C%20Albania" target="_blank">📍 Google Maps</a></div>
    <img class="spot-thumb" src="images/piet-s-vlor-s-marina-00fcdd6c.jpg" alt="Vlorės marina">
    <div class="credit">Nuotrauka: Anila amataj, CC BY-SA 4.0, <a href="https://commons.wikimedia.org/wiki/File:Porti_i_Vlores.jpg" target="_blank">šaltinis</a></div>
    <p class="notes">Vlorės uosto promenadoje daug žuvies restoranų. Rekomenduojame <strong><a href="https://www.google.com/maps/search/?api=1&query=Restaurant%20Salvadore%2C%20Rruga%20Pelivan%20Leskaj%2C%20Vlor%C3%AB" target="_blank">Restaurant Salvadore</a></strong> – šeimos valdomas žuvies turgus su restoranu, žvejys savininkas pats pristato kasdienį laimikį, sąžiningos kainos ir gausios porcijos, ~14 €/asm.</p>
  </div>

  <div class="leg">🚶 0,0 km · 1 min pėsčiomis – ta pati vieta Vlorės uoste</div>

  <div class="stop">
    <div class="stop-header"><span class="stop-time">14:51</span> Vlorės pakrantės promenada (Lungomare) <a class="maps-link" href="https://www.google.com/maps/search/?api=1&query=Lungomare%2C%20Vlor%C3%AB%2C%20Albania" target="_blank">📍 Google Maps</a></div>
    <img class="spot-thumb" src="images/vlor-s-pakrant-s-promenada-lungomare-0b1ff0c5.jpg" alt="Lungomare">
    <div class="credit">Nuotrauka: I would appreciate being notified if you use my work outside Wikimedia, CC BY 4.0, <a href="https://commons.wikimedia.org/wiki/File:Vlora,_pob%C5%99e%C5%BE%C3%AD.jpg" target="_blank">šaltinis</a></div>
    <p class="notes">Pasivaikščiojimas pakrante, vaizdas į Jonų jūrą ir Sazano salą.</p>
  </div>

  <div class="leg">🚗 0,3 km · 1 min – ta pati vieta Vlorės pakrantėje</div>

  <div class="stop">
    <div class="stop-header"><span class="stop-time">16:01</span> Hotel Liro – Adults Only <a class="maps-link" href="https://www.google.com/maps/search/?api=1&query=Hotel%20Liro%20Adults%20Only%2C%20Rruga%20Aleksand%C3%ABr%20Moisiu%2C%20Vlor%C3%AB%2C%20Albania" target="_blank">📍 Google Maps</a></div>
    <img class="spot-thumb" src="images/hotel-liro-adults-only-2b392f25.jpg" alt="Hotel Liro">
    <div class="credit">Nuotrauka: Sharon Hahn Darlin, CC BY 2.0, <a href="https://commons.wikimedia.org/wiki/File:Vlor%C3%AB,_Albania_2022-12-03_balcony_view_-_City_at_Night.jpg" target="_blank">šaltinis</a></div>
    <p class="notes">Nakvynė Vlorėje – privatus paplūdimio ruožas, lauko baseinas, vaizdas į jūrą nuo balkono. Tik suaugusiems.</p>
  </div>
  <div class="eatery-mention">🍽 Vakarienė: <strong><a href="https://www.google.com/maps/search/?api=1&query=Taverna%20Djepi%2C%20Rruga%20Aleksand%C3%ABr%20Moisiu%2C%20Vlor%C3%AB" target="_blank">Taverna Djepi</a></strong> (~19 €/asm.) – toje pačioje gatvėje kaip viešbutis (apie 5 min.), terasa su saulėlydžio vaizdu į jūrą, 4,8/5 įvertinimas, šeimyniška atmosfera.</div>

  <details class="plan-b">
    <summary>🌧 Planas B (jei blogas oras)</summary>
    <p><strong>Kodėl:</strong> Osumio kanjono apžvalgos aikštelė atvira ir vaizdas blogai matomas per rūką ar liūtį, o Vlorės pakrantės promenada (Lungomare) – ilgas pasivaikščiojimas lauke prie jūros, nepatogus vėjuotu ar lietingu metu.</p>
    <h4>Osumi ir Vlorė – vidinis variantas</h4>
    <div class="stop">
      <div class="stop-header"><span class="stop-time">10:15</span> Osumio kanjono apžvalgos aikštelė (trumpas sustojimas) <a class="maps-link" href="https://www.google.com/maps/search/?api=1&query=Kanioni%20i%20Osumit%2C%20%C3%87orovod%C3%AB%2C%20Albania" target="_blank">📍 Google Maps</a></div>
      <p class="notes">🚗 Per lietų ar perkūniją – trumpas vaizdas nuo aikštelės, neišlipant toliau nuo automobilio.</p>
    </div>
    <div class="stop">
      <div class="stop-header"><span class="stop-time">13:40</span> Pietūs Vlorės marina <a class="maps-link" href="https://www.google.com/maps/search/?api=1&query=Marina%20e%20Vlor%C3%ABs%2C%20Vlor%C3%AB%2C%20Albania" target="_blank">📍 Google Maps</a></div>
      <p class="notes">🚗 Tas pats restoranas kaip pagrindiniame plane – uždaros patalpos su vaizdu į uostą.</p>
    </div>
    <div class="stop">
      <div class="stop-header"><span class="stop-time">14:55</span> Muradie mečetė (Xhamia Muradie) <a class="maps-link" href="https://www.google.com/maps/search/?api=1&query=Xhamia%20Muradie%2C%20Vlor%C3%AB%2C%20Albania" target="_blank">📍 Google Maps</a></div>
      <p class="notes">🚶 XVI a. mečetė miesto centre, dengta – gera alternatyva lietingam orui, laisvai lankoma dienos metu.</p>
    </div>
    <div class="stop">
      <div class="stop-header"><span class="stop-time">15:45</span> Hotel Liro – Adults Only <a class="maps-link" href="https://www.google.com/maps/search/?api=1&query=Hotel%20Liro%20Adults%20Only%2C%20Rruga%20Aleksand%C3%ABr%20Moisiu%2C%20Vlor%C3%AB%2C%20Albania" target="_blank">📍 Google Maps</a></div>
      <p class="notes">🚶 Nakvynė Vlorėje – kaip pagrindiniame plane.</p>
    </div>
    <p>Bendras vairavimo laikas: apie 156 min.</p>
    <a class="route-btn" href="https://www.google.com/maps/dir/?api=1&origin=Kanioni+i+Osumit,+%C3%87orovod%C3%AB,+Albania&destination=Marina+e+Vlor%C3%ABs,+Vlor%C3%AB,+Albania&travelmode=driving" target="_blank">🧭 Plano B maršrutas: 🚗 Automobiliu</a>
    <a class="route-btn" href="https://www.google.com/maps/dir/?api=1&origin=Marina+e+Vlor%C3%ABs,+Vlor%C3%AB,+Albania&destination=Hotel+Liro+Adults+Only,+Rruga+Aleksand%C3%ABr+Moisiu,+Vlor%C3%AB,+Albania&travelmode=walking&waypoints=Xhamia+Muradie,+Vlor%C3%AB,+Albania" target="_blank">🧭 Plano B maršrutas: 🚶 Pėsčiomis</a>
    <p><strong>Patarimas:</strong> Perkūnijos metu kanjono aikštelėje nerekomenduojama ilgai stovėti dėl žaibo rizikos – pakanka trumpo sustojimo prie automobilio. Muradie mečetė Vlorėje lankoma nemokamai visą dieną, darbo laikas nuo oro ir savaitės dienos nepriklauso.</p>
  </details>
</section>

<!-- ===================== DAY 4 ===================== -->
<section id="day4">
  <div class="day-header">
    <h2>📅 4 diena · pirmadienis, 2026-11-02 — Divjakė-Karavasta ir išvykimas</h2>
    <span class="weather-note">⛈ Paskutinę dieną tikėtina perkūnija (45 % tikimybė, ~12 mm), 6–14 °C, vėjas iki 9,5 km/h.</span>
    <p class="plan-b-hint">Didelė lietaus tikimybė – šiandien Planas B gali būti geresnis pasirinkimas.</p>
  </div>
  <a class="route-btn" href="https://www.google.com/maps/dir/?api=1&origin=Qendra+e+Vizitor%C3%ABve+Divjak%C3%AB-Karavasta,+Divjak%C3%AB,+Albania&destination=Tirana+International+Airport+N%C3%ABn%C3%AB+Tereza,+Albania&travelmode=driving&waypoints=Plazhi+i+Divjak%C3%ABs,+Divjak%C3%AB,+Albania" target="_blank">🧭 Dienos maršrutas Google Maps</a>

  <div class="stop">
    <div class="stop-header"><span class="stop-time">10:10</span> Karavastos lagūnos Lankytojų centras ir apžvalgos bokštas <a class="maps-link" href="https://www.google.com/maps/search/?api=1&query=Qendra%20e%20Vizitor%C3%ABve%20Divjak%C3%AB-Karavasta%2C%20Divjak%C3%AB%2C%20Albania" target="_blank">📍 Google Maps</a></div>
    <img class="spot-thumb" src="images/karavastos-lag-nos-lankytoj-centras-ir-ap-valgos-bok-tas-04d4296b.jpg" alt="Karavastos lagūna">
    <div class="credit">Nuotrauka: Leeturtle, CC BY-SA 4.0, <a href="https://commons.wikimedia.org/wiki/File:Karavasta_bay,_Divjak%C3%AB,_Albania_2.jpg" target="_blank">šaltinis</a></div>
    <p class="notes">Automobilį palikite Lankytojų centro aikštelėje – čia veda geras asfaltuotas/tvarkingas kelias, o čia pat yra apie 35 m aukščio apžvalgos bokštas su gražiu vaizdu į lagūną. Jei norite pasiekti giliau lagūnoje esantį bokštą, paskutinius 1–2 km (ir tiek pat atgal) reikia nueiti pėsčiomis – nuomotam automobiliui tas kelias po lietaus būna dumblinas ir netinkamas. Rudenį čia gerai matomi rausvieji pelikanai ir flamingai. Nedidelis mokestis automobiliui įvažiuojant į parką.</p>
  </div>

  <div class="leg">🚗 1 km · 3 min – parko kelias prie paplūdimio</div>

  <div class="stop">
    <div class="stop-header"><span class="stop-time">13:30</span> Pietūs Divjakės paplūdimyje <a class="maps-link" href="https://www.google.com/maps/search/?api=1&query=Plazhi%20i%20Divjak%C3%ABs%2C%20Divjak%C3%AB%2C%20Albania" target="_blank">📍 Google Maps</a></div>
    <img class="spot-thumb" src="images/piet-s-divjak-s-papl-dimyje-913e1095.jpg" alt="Divjakės paplūdimys">
    <div class="credit">Nuotrauka: Arbenllapashtica, CC BY-SA 4.0, <a href="https://commons.wikimedia.org/wiki/File:Pelikan_Divjake_Arben_Llapashtica.jpg" target="_blank">šaltinis</a></div>
    <p class="notes">Paplūdimio žuvies kioskai ir restoranėliai. Rekomenduojame <strong><a href="https://www.google.com/maps/search/?api=1&query=Restorant%20Pelikan%2C%20Divjak%C3%AB%20Qend%C3%ABr%20Plazh%2C%20Divjak%C3%AB" target="_blank">Restorant Pelikan</a></strong> (~13 €/asm.) – vos žingsnis nuo paplūdimio ir lagūnos, lokalūs žvejai pristato ungurius ir žuvį tiesiai iš Karavastos lagūnos, 4,8/5 įvertinimas.</p>
  </div>

  <div class="leg">🚗 88 km · 113 min – asfaltuotas lygumos kelias per Lušnję ir Rrogožiną į oro uostą</div>

  <div class="stop">
    <div class="stop-header"><span class="stop-time">16:15</span> Tiranos oro uostas (TIA) – automobilio grąžinimas ir skrydis namo <a class="maps-link" href="https://www.google.com/maps/search/?api=1&query=Tirana%20International%20Airport%20N%C3%ABn%C3%AB%20Tereza%2C%20Albania" target="_blank">📍 Google Maps</a></div>
    <img class="spot-thumb" src="images/tiranos-oro-uostas-tia-automobilio-gr-inimas-ir-skrydis-namo-f858d520.jpg" alt="Tiranos oro uostas">
    <div class="credit">Nuotrauka: Peter Nath, CC BY 4.0, <a href="https://commons.wikimedia.org/wiki/File:2007_03_27_Tirana_Airport_TIA_LATI_06.jpg" target="_blank">šaltinis</a></div>
    <p class="notes">Automobilio grąžinimas (reikia iki 17:00) – atsargos laiko pakaks. Skrydis į Varšuvą išskrenda 19:05 – registracijai ir saugumo patikrai liks pakankamai laiko.</p>
  </div>

  <details class="plan-b">
    <summary>🌧 Planas B (jei blogas oras)</summary>
    <p><strong>Kodėl:</strong> Pelikanų apžvalgos bokšto takelis dumblėja po lietaus, o pietūs atvirame Divjakės paplūdimyje nepatogūs vėjuotu ar lietingu oru – abi vietos geriausios giedrą dieną.</p>
    <h4>Karavasta ir Tirana lietaus dieną</h4>
    <div class="stop">
      <div class="stop-header"><span class="stop-time">10:10</span> Karavastos lagūnos Lankytojų centras (vidinė ekspozicija) <a class="maps-link" href="https://www.google.com/maps/search/?api=1&query=Qendra%20e%20Vizitor%C3%ABve%20Divjak%C3%AB-Karavasta%2C%20Divjak%C3%AB%2C%20Albania" target="_blank">📍 Google Maps</a></div>
      <p class="notes">🚗 Per lietų likti prie Lankytojų centro vidinės ekspozicijos – pelikanų ir flamingų nuotraukos, modeliai, filmas. Dumblėjantis takelis iki apžvalgos bokšto ir pietūs paplūdimyje šią dieną atšaukiami.</p>
    </div>
    <div class="stop">
      <div class="stop-header"><span class="stop-time">13:20</span> Pietūs Pazari i Ri (Tiranos naujasis turgus) <a class="maps-link" href="https://www.google.com/maps/search/?api=1&query=Pazari%20i%20Ri%2C%20Tiran%C3%AB%2C%20Albania" target="_blank">📍 Google Maps</a></div>
      <p class="notes">🚗 Dengta prekybos salė su vietinių produktų kioskais ir restoranėliais – gera pietų vieta per lietų, pakeliui į oro uostą.</p>
    </div>
    <div class="stop">
      <div class="stop-header"><span class="stop-time">14:30</span> Bunk'Art 2 <a class="maps-link" href="https://www.google.com/maps/search/?api=1&query=Bunk%27Art%202%2C%20Rruga%20Abdi%20Toptani%2C%20Tiran%C3%AB%2C%20Albania" target="_blank">📍 Google Maps</a></div>
      <p class="notes">🚶 Požeminis bunkerių muziejus miesto centre, visiškai apsaugotas nuo oro – apie 700 m pėsčiomis nuo turgaus.</p>
    </div>
    <div class="stop">
      <div class="stop-header"><span class="stop-time">16:20</span> Tiranos oro uostas (TIA) – automobilio grąžinimas ir skrydis namo <a class="maps-link" href="https://www.google.com/maps/search/?api=1&query=Tirana%20International%20Airport%20N%C3%ABn%C3%AB%20Tereza%2C%20Albania" target="_blank">📍 Google Maps</a></div>
      <p class="notes">🚗 Automobilio grąžinimas iki 17:00 – laiko pakanka. Skrydis į Varšuvą išskrenda 19:05.</p>
    </div>
    <p>Bendras vairavimo laikas: apie 133 min.</p>
    <a class="route-btn" href="https://www.google.com/maps/dir/?api=1&origin=Qendra+e+Vizitor%C3%ABve+Divjak%C3%AB-Karavasta,+Divjak%C3%AB,+Albania&destination=Pazari+i+Ri,+Tiran%C3%AB,+Albania&travelmode=driving" target="_blank">🧭 Plano B maršrutas: 🚗 Automobiliu</a>
    <a class="route-btn" href="https://www.google.com/maps/dir/?api=1&origin=Pazari+i+Ri,+Tiran%C3%AB,+Albania&destination=Bunk%27Art+2,+Rruga+Abdi+Toptani,+Tiran%C3%AB,+Albania&travelmode=walking" target="_blank">🧭 Plano B maršrutas: 🚶 Pėsčiomis</a>
    <a class="route-btn" href="https://www.google.com/maps/dir/?api=1&origin=Bunk%27Art+2,+Rruga+Abdi+Toptani,+Tiran%C3%AB,+Albania&destination=Tirana+International+Airport+N%C3%ABn%C3%AB+Tereza,+Albania&travelmode=driving" target="_blank">🧭 Plano B maršrutas: 🚗 Automobiliu 2</a>
    <p><strong>Patarimas:</strong> Lankytojų centro vidinė ekspozicija veikia nepriklausomai nuo oro, pirmadieniais apie 8:00–16:00 – paskambinti iš anksto pasitikrinti. Bunk'Art 2 dirba visas savaitės dienas 9:30–18:30.</p>
  </details>
</section>

<!-- ===================== MAP ===================== -->
<section id="map-section">
  <h2>🗺️ Žemėlapis</h2>
  <!-- TRIP_MAP -->
</section>

<!-- ===================== BUDGET ===================== -->
<section id="budget">
  <h2>💶 Biudžeto suvestinė</h2>
  <p>4 keliautojai, 3 nakvynės, 2026-10-30 → 2026-11-02.</p>
  <table>
    <tr><th>Kategorija</th><th>Tikėtina suma</th><th>Pastaba</th></tr>
    <tr><td>Skrydžiai (WAW↔TIA, 4 asm.)</td><td>405 €</td><td>Ryanair, be registruoto bagažo (iki 505 € su bagažu)</td></tr>
    <tr><td>Automobilio nuoma (jau užsakyta)</td><td>168 €</td><td>VW Tiguan, TIA 10-30 21:00 → 11-02 17:00, papildomas vairuotojas + pilnas draudimas</td></tr>
    <tr><td>Degalai (~350–430 km)</td><td>58 €</td><td>Dyzelinas ~1,90–2,00 €/l</td></tr>
    <tr><td>Nakvynė (3 naktys, visai grupei)</td><td>229 €</td><td>Patvirtinta pagal užsakymus</td></tr>
    <tr><td>Maistas (4 asm. × 4 d.)</td><td>392 €</td><td>Žr. lentelę žemiau</td></tr>
    <tr><td>Įėjimo bilietai</td><td>19 €</td><td>Krujė, Beratas, Karavasta</td></tr>
    <tr><th>Iš viso (visai grupei)</th><th>≈1 271 €</th><td>Intervalas 1 202–1 462 €</td></tr>
    <tr><th>Vienam asmeniui</th><th>≈318 €</th><td>Intervalas 301–366 €</td></tr>
  </table>

  <h3>Maisto detalizacija (€/asm.)</h3>
  <table>
    <tr><th>Diena</th><th>Pusryčiai</th><th>Pietūs</th><th>Vakarienė</th><th>Iš viso/asm.</th></tr>
    <tr><td>1 (atvykimas)</td><td>—</td><td>—</td><td>17 €</td><td>17 €</td></tr>
    <tr><td>2 (Krujė→Beratas)</td><td>4 €</td><td>12 €</td><td>14 €</td><td>30 €</td></tr>
    <tr><td>3 (Osumi→Vlorė)</td><td>0 € (su nakvyne)</td><td>14 €</td><td>19 €</td><td>33 €</td></tr>
    <tr><td>4 (Divjakė→išvykimas)</td><td>0 € (su nakvyne)</td><td>13 €</td><td>—</td><td>13 €</td></tr>
  </table>
  <p style="font-size:.85rem;color:var(--muted);">Jūsų užsakytas automobilis (Karruka Rent a Car, 168 €) yra pigesnis už palyginamus pasiūlymus – Tirana Airport Rental Car kainuotų ~175 €, Sixt ~255 €.</p>
</section>

<!-- ===================== PRACTICAL INFO ===================== -->
<section id="practical">
  <h2>ℹ️ Praktinė informacija</h2>
  <ul class="tips">
    <li><strong>Saugumas:</strong> policijos greičio patikros kelyje dažnos, alkoholio limitas vairuotojams – 0,01 % (praktiškai nulinė tolerancija).</li>
    <li><strong>Vairavimas naktį:</strong> kaimo kelių ruožai neapšviesti, gali netikėtai pasirodyti gyvuliai ar pėstieji – vakare vairuoti nerekomenduojama.</li>
    <li><strong>Mokami keliai:</strong> Llogaros tunelis ir A1 greitkelis link Kosovo yra mokami.</li>
    <li><strong>Staigūs potvyniai:</strong> po smarkaus lietaus Vjosos ir Osumo upių slėniuose gali kilti staigūs potvyniai.</li>
    <li><strong>Pagalbos telefonas:</strong> 112 (bendras pagalbos skambučių numeris Albanijoje).</li>
  </ul>

  <h3>Kelionės duomenys</h3>
  <ul class="tips">
    <li>Automobilio grąžinimas: Tiranos oro uoste (TIA), iki <strong>2026-11-02, 17:00</strong>.</li>
    <li>Skrydis į Albaniją: Varšuva 18:30 → Tirana 20:30, 2026-10-30.</li>
    <li>Skrydis namo: Tirana 19:05 → Varšuva ~21:05, 2026-11-02.</li>
    <li>Kontaktai Albanijoje: — (įrašykite automobilio nuomos ir viešbučių telefono numerius prieš kelionę).</li>
  </ul>

  <h3>⚠️ Patarimai kelyje</h3>
  <ul class="tips">
    <li>Prie Osumo kanjono apžvalgos aikštelės Google Maps kartais siūlo trumpesnį kelią toliau per Pėrmetą -- tai žvyrkelis, netinkamas standartiniam automobiliui. Važiuokite tik iki apžvalgos aikštelės prie Čorovodės ir grįžkite tuo pačiu asfaltuotu keliu per Beratą ir toliau per Fierą į Vlorę.</li>
    <li>Berato senamiestyje Mangalemo ir Goricos kvartalus geriausia apžiūrėti pėsčiomis -- tiltas per Osumo upę skirtas tik pėstiesiems.</li>
    <li>Karavastos-Divjakės nacionaliniame parke automobilį palikite Lankytojų centro aikštelėje -- čia veda geras asfaltuotas kelias ir čia pat yra apžvalgos bokštas. Jei norite pasiekti giliau lagūnoje esantį bokštą, paskutinius 1-2 km nueikite pėsčiomis, nes tas kelias po lietaus būna dumblinas.</li>
    <li>Antrą ir trečią kelionės dieną vairavimo laikas artėja prie 4 valandų -- neplanuokite papildomų stotelių, kad liktų laiko ramiai pasigrožėti Krujë, Beratu ir kanjonu.</li>
    <li>Paskutinę dieną grįžus į Tiranos oro uostą iki skrydžio liks apie 2 val. 40-50 min -- automobilio grąžinimui ir registracijai laiko turėtų pakakti.</li>
  </ul>
</section>

<!-- ===================== WEATHER ===================== -->
<section id="weather">
  <h2>☁️ Orų prognozė</h2>
  <table>
    <tr><th>Diena</th><th>Vieta</th><th>Oras</th><th>Temperatūra</th><th>Lietaus tikimybė</th><th>Vėjas</th></tr>
    <tr><td>Pn, 2026-10-30</td><td>Tirana</td><td>Debesuota</td><td>10–20 °C</td><td>11 %</td><td>iki 5,9 km/h</td></tr>
    <tr><td>Št, 2026-10-31</td><td>Beratas</td><td>Lietus</td><td>10–20 °C</td><td>25 %</td><td>iki 6,6 km/h</td></tr>
    <tr><td>Sk, 2026-11-01</td><td>Vlorė</td><td>Perkūnija</td><td>14–18 °C</td><td>54 %</td><td>iki 7,2 km/h</td></tr>
    <tr><td>Pr, 2026-11-02</td><td>Divjakė / Tirana (grįžimo diena)</td><td>Perkūnija</td><td>6–14 °C</td><td>45 %</td><td>iki 9,5 km/h</td></tr>
  </table>
  <p style="font-size:.85rem;color:var(--muted);">Prognozė galioja visoms kelionės dienoms – jos atnaujintos 2026-10-27, likus kelioms dienoms iki kelionės.</p>
</section>

<!-- ===================== PACKING ===================== -->
<section id="packing">
  <h2>🎒 Ką pasiimti</h2>
  <!-- PACKING_LIST -->
</section>

<!-- ===================== CAR RENTAL ===================== -->
<section id="car-rental">
  <h2>🚗 Automobilio nuoma</h2>

  <h3>Rekomenduojami automobilių tipai</h3>
  <div class="card car-type-card">
    <strong>Kompaktinis visureigis (Dacia Duster, Škoda Karoq, VW T-Roc)</strong>
    <p>Pakankamai vietos 4 žmonėms ir bagažui, didesnė prošvaisa nelygiems/žvyruotiems ruožams (Osumo kanjono apžvalgos aikštelės, Beratas), ekonomiškos degalų sąnaudos trumpiems rudens maršrutams.</p>
    <p>~40 €/d. · viso kelionei ~160 €</p>
  </div>
  <div class="card car-type-card">
    <strong>Pilno dydžio visureigis (VW Tiguan, Hyundai Tucson, Nissan Qashqai)</strong>
    <p>Daugiausia vietos bagažui ir patogiausia 4 suaugusiems ilgesnėse atkarpose (Vlorė–Llogara perėja); tai klasė, kurią jau užsisakėte (VW Tiguan) – patikima pasirinktis rudens/žiemos sąlygoms kalnų perėjose.</p>
    <p>~55 €/d. · viso kelionei ~220 €</p>
  </div>
  <div class="card car-type-card">
    <strong>Kompaktinis sedanas/hečbekas (Škoda Octavia, VW Golf)</strong>
    <p>Pigiausias variantas, jei maršrutas apsiriboja asfaltuotais keliais; mažesnė prošvaisa mažiau tinkama Osumo kanjono ar kalnų ruožams, mažiau bagažo vietos 4 žmonėms.</p>
    <p>~30 €/d. · viso kelionei ~120 €</p>
  </div>

  <h3>Nuomos įmonės</h3>
  <div class="card company-card">
    <strong>Karruka Rent a Car</strong> · ⭐ 4,9 (1000+ atsiliepimų, Google Maps)
    <p>Pilno dydžio visureigis (SUV), 5 vietos · įvertinta kaina ~180 €</p>
    <p>Tiranos oro uosto klientų dažniausiai renkama vietinė įmonė – be depozito, minimalus popierizmas, draudimas įskaičiuotas į kainą. Tai jūsų pasirinkta įmonė – faktiška užsakymo kaina su papildomu vairuotoju ir pilnu draudimu yra 168 €.</p>
    <p>Atsiėmimas: Tiranos tarptautinis oro uostas (TIA), Rinas – atvykimo salė.</p>
    <a class="booking-link" href="https://karrukarental.com/reservation/" target="_blank">Užsisakyti</a>
  </div>
  <div class="card company-card">
    <strong>Tirana Airport Rental Car</strong> · ⭐ 4,7 (1413 atsiliepimų, Google Maps)
    <p>Kompaktinis/pilno dydžio visureigis, 5 vietos · įvertinta kaina ~175 €</p>
    <p>Nauji automobiliai su pilnu draudimu ir be depozito – patikimas ir geros kainos/kokybės santykio pasirinkimas 4 keliautojams.</p>
    <p>Atsiėmimas: Tiranos tarptautinis oro uostas (TIA), Rinas.</p>
    <a class="booking-link" href="https://tiranaairportrentalcar.com/" target="_blank">Užsisakyti</a>
  </div>
  <div class="card company-card">
    <strong>Sixt</strong> · ⭐ 4,1 (4494 atsiliepimų, EasyTerra 8,2/10)
    <p>Visureigis (SUV), 5 vietos · įvertinta kaina ~255 €</p>
    <p>Tarptautinis prekės ženklas su aiškiai pažymėtu biuru oro uoste ir platesniu pagalbos kelyje tinklu – saugus pasirinkimas, jei svarbiau aptarnavimo nuspėjamumas nei mažiausia kaina.</p>
    <p>Atsiėmimas: Tiranos tarptautinis oro uostas (TIA), nuomos centras prie terminalo.</p>
    <a class="booking-link" href="https://www.sixt.com/car-rental/albania/tirana/tirana-airport/" target="_blank">Užsisakyti</a>
  </div>

  <h3>Patarimai</h3>
  <ul class="tips">
    <li>Automobilis šiai kelionei jau užsakytas (VW Tiguan / pilno dydžio visureigis, atsiėmimas TIA spalio 30 d. 21:00, grąžinimas lapkričio 2 d. 17:00, su Papildomu vairuotoju ir Super Protective Insurance, iš viso €168) – aukščiau pateikti pasiūlymai skirti palyginimui arba atsarginiam variantui.</li>
    <li>Atsiėmimas vėlai vakare (21:00): būtina iš anksto patvirtinti, kad pasirinktos įmonės biuras tuo metu dirba – dauguma vietinių nuomotojų oro uoste veikia 24/7, bet verta gauti patvirtinimą el. paštu.</li>
    <li>Kalnų ir kaimo kelių ruožai (Llogara perėja, Osumo kanjono apžvalgos keliai) gali būti duobėti ar žvyruoti – didesnė prošvaisa (SUV) patogesnė nei sedanas.</li>
    <li>Degalų politika: patikrinti „pilnas-į-pilną“ sąlygą; dauguma vietinių įmonių nereikalauja depozito grynaisiais, tik kreditinės kortelės rezervacijos.</li>
    <li>Rudens/žiemos sąlygoms rekomenduojamas pilnas draudimas be išskaitos (kaip jau pasirinktas Super Protective Insurance) – kalnų keliuose po lietaus gali būti slidu.</li>
  </ul>
</section>

<!-- ===================== FOOD ===================== -->
<section id="food">
  <h2>🍽 Kur pavalgyti</h2>

  <h3>1 diena — Tirana</h3>
  <div class="card food-card">
    <strong>Sofra e Ariut</strong> · netoli nakvynės Hanna Apartment (ta pačia Rruga e Elbasanit gatve)
    <p>Tradicinė taverna · vidutinė kaina ~13 €/asm. · Vakarienė ~17 € asmeniui</p>
    <p>Pačioje Rruga e Elbasanit gatvėje, 5 min pėsčiomis nuo nakvynės – patogu pirmą vakarą po vėlyvo atvykimo, siūlo tradicinius albanų patiekalus gražioje sodo aplinkoje; kai kurie atsiliepimai mini aukštesnes kainas, tad geriau rinktis pagrindinius patiekalus, ne žuvį.</p>
    <p><a href="https://www.google.com/maps/search/?api=1&query=Sofra%20e%20Ariut%2C%20Rruga%20e%20Elbasanit%2C%20Tiran%C3%AB" target="_blank">📍 Google Maps</a></p>
    <strong>Ką paragauti čia</strong>
    <div class="dish-grid">
      <figure><img class="spot-thumb dish-thumb" src="images/tav-kosi-riena-jogurto-pada-e-e67a530d.jpg" alt="Tavė kosi"><figcaption>Tavė kosi (ėriena su jogurto padažu) (<em>Tavë kosi</em>) – 9 €<br><span class="credit">fugzu, CC BY 2.0, <a href="https://commons.wikimedia.org/wiki/File:TAVE_KOSI-_agnello_allo_yogurt_albanese.jpg" target="_blank">šaltinis</a></span></figcaption></figure>
      <figure><img class="spot-thumb dish-thumb" src="images/darytos-paprikos-3e1890d0.jpg" alt="Įdarytos paprikos su varške"><figcaption>Įdaryti paprikos su varške (<em>Speca me gjizë</em>) – 6 €<br><span class="credit">Kkushta, CC BY-SA 4.0, <a href="https://commons.wikimedia.org/wiki/File:Dollma,Speca_te_mbushur_me_mish_dhe_oriz.jpg" target="_blank">šaltinis</a></span></figcaption></figure>
      <figure><img class="spot-thumb dish-thumb" src="images/rienos-kotletai-ant-groteli-f8d294ab.jpg" alt="Ėrienos kotletai ant grotelių"><figcaption>Ėrienos kotletai ant grotelių (<em>Copa qengji në skarë</em>) – 11 €<br><span class="credit">HaJunkiyada, CC BY-SA 4.0, <a href="https://commons.wikimedia.org/wiki/File:Liat_Portal_for_Foodie_Disorder_-_Homemade_Lamb_Chops_with_Rice_and_Grilled_Vegetables.jpg" target="_blank">šaltinis</a></span></figcaption></figure>
    </div>
  </div>
  <div class="card food-card">
    <strong>Komiteti – Kafe Muzeum</strong> (baras) · Tiranos centras, apie 15 min. nuo Hanna Apartment
    <p>Baras-muziejus, pilnas komunistinės epochos daiktų – uniformų, senų televizorių, radijo imtuvų ir net lubose kabančių grėblių, naudojamų kaip vyno taurių pakaba; unikali atmosfera ir plati raki pasirinkimo galimybė (Tripadvisor 4,3/5).</p>
    <p><a href="https://www.google.com/maps/search/?api=1&query=Komiteti%20%E2%80%93%20Kafe%20Muzeum%2C%20Rruga%20Fatmir%20Haxhiu%202%2C%20Tiran%C3%AB" target="_blank">📍 Google Maps</a></p>
  </div>

  <h3>2 diena — Krujė ir Beratas</h3>
  <div class="card food-card">
    <strong>Snack Bar Derexhiku</strong> · netoli Krujos senojo bazaro ir pilies
    <p>Nedidelis kioskas / kavinė bazare · vidutinė kaina ~4 €/asm. · Vakarienė ~6 € asmeniui</p>
    <p>Mažas kioskas pačiame senojo bazaro centre – puikus greitas užkandis tarp pilies ir muziejaus lankymo, vietinių gerai vertinamas už skanų ir pigų byreką.</p>
    <p><a href="https://www.google.com/maps/search/?api=1&query=Snack%20Bar%20Derexhiku%2C%20Pazari%20i%20Vjet%C3%ABr%20%28Senasis%20bazaras%29%2C%20Kruj%C3%AB" target="_blank">📍 Google Maps</a></p>
    <strong>Ką paragauti čia</strong>
    <div class="dish-grid">
      <figure><img class="spot-thumb dish-thumb" src="images/byrekas-88fe47b0.png" alt="Byrekas su spinatais ir varške"><figcaption>Byrekas su spinatais ir varške (<em>Byrek me spinaq</em>) – 2 €<br><span class="credit">Albaniandude, CC0, <a href="https://commons.wikimedia.org/wiki/File:Byrek_from_Kosovo.png" target="_blank">šaltinis</a></span></figcaption></figure>
      <figure><img class="spot-thumb dish-thumb" src="images/molinio-puodo-tro-kinys-e8337c95.jpg" alt="Molinio puodo troškinys"><figcaption>Molinio puodo troškinys (<em>Tavë dheu</em>) – 5 €<br><span class="credit">Nok Selmani, CC BY-SA 4.0, <a href="https://commons.wikimedia.org/wiki/File:Pasul_me_suxhuk_n%C3%AB_tav%C3%AB_t%C3%AB_dheut.jpg" target="_blank">šaltinis</a></span></figcaption></figure>
      <figure><figcaption>Vištienos file su garnyru (<em>Filetë pule</em>) – 5 €</figcaption></figure>
    </div>
  </div>
  <div class="card food-card">
    <strong>Lili Homemade Food</strong> · netoli Mangalemo senojo kvartalo (pietų sustojimas maršrute)
    <p>Šeimos namų virtuvė · vidutinė kaina ~12 €/asm. · Vakarienė ~14 € asmeniui</p>
    <p>Lili ir jo žmona gamina patiekalus savo kieme pagal senelio receptus – vienas geriausiai įvertintų restoranų visoje Albanijoje (4,9/5, virš 2000 atsiliepimų); rezervacija WhatsApp būtina dėl mažo vietų skaičiaus.</p>
    <p><a href="https://www.google.com/maps/search/?api=1&query=Lili%20Homemade%20Food%2C%20Rruga%20Llambi%20Guxhumani%2C%20Mangalem%2C%20Beratas" target="_blank">📍 Google Maps</a></p>
    <strong>Ką paragauti čia</strong>
    <div class="dish-grid">
      <figure><img class="spot-thumb dish-thumb" src="images/f-rges-bd6c81b3.jpg" alt="Fërgesė"><figcaption>Fërgesë (paprikų ir varškės troškinys) (<em>Fërgesë</em>) – 6 €<br><span class="credit">Kj1595, CC BY-SA 4.0, <a href="https://commons.wikimedia.org/wiki/File:F%C3%ABrges%C3%AB_dhe_Tav%C3%AB_me_oriz.jpg" target="_blank">šaltinis</a></span></figcaption></figure>
      <figure><img class="spot-thumb dish-thumb" src="images/tav-kosi-riena-jogurto-pada-e-e67a530d.jpg" alt="Tavė kosi"><figcaption>Tavë kosi – 9 €<br><span class="credit">fugzu, CC BY 2.0, <a href="https://commons.wikimedia.org/wiki/File:TAVE_KOSI-_agnello_allo_yogurt_albanese.jpg" target="_blank">šaltinis</a></span></figcaption></figure>
      <figure><figcaption>Įdarytos baklažanai (<em>Patëllxhan i mbushur</em>) – 7 €</figcaption></figure>
    </div>
  </div>
  <div class="card food-card">
    <strong>Guva Mangalem</strong> · netoli nakvynės DD Villa, Mangalemo kvartale
    <p>Tradicinė taverna · vidutinė kaina ~10 €/asm. · Vakarienė ~14 € asmeniui</p>
    <p>Vos keli žingsniai nuo DD Villa, terasa su vaizdu į Berato pilį ir Mangalemą, tradiciniai Berato patiekalai patiekiami klasikiniu stiliumi.</p>
    <p><a href="https://www.google.com/maps/search/?api=1&query=Guva%20Mangalem%2C%20Rr.%20Llambi%20Guxhumani%20nr.%2044%2C%20Beratas" target="_blank">📍 Google Maps</a></p>
    <strong>Ką paragauti čia</strong>
    <div class="dish-grid">
      <figure><img class="spot-thumb dish-thumb" src="images/tav-kosi-riena-jogurto-pada-e-e67a530d.jpg" alt="Tavė kosi"><figcaption>Tavė kosi – 8 €<br><span class="credit">fugzu, CC BY 2.0, <a href="https://commons.wikimedia.org/wiki/File:TAVE_KOSI-_agnello_allo_yogurt_albanese.jpg" target="_blank">šaltinis</a></span></figcaption></figure>
      <figure><img class="spot-thumb dish-thumb" src="images/darytos-paprikos-3e1890d0.jpg" alt="Įdarytos paprikos"><figcaption>Įdarytos paprikos (<em>Speca të mbushur</em>) – 5 €<br><span class="credit">Kkushta, CC BY-SA 4.0, <a href="https://commons.wikimedia.org/wiki/File:Dollma,Speca_te_mbushur_me_mish_dhe_oriz.jpg" target="_blank">šaltinis</a></span></figcaption></figure>
      <figure><img class="spot-thumb dish-thumb" src="images/byrekas-88fe47b0.png" alt="Byrekas"><figcaption>Byrekas (<em>Byrek</em>) – 3 €<br><span class="credit">Albaniandude, CC0, <a href="https://commons.wikimedia.org/wiki/File:Byrek_from_Kosovo.png" target="_blank">šaltinis</a></span></figcaption></figure>
    </div>
  </div>

  <h3>3 diena — Osumio kanjonas ir Vlorė</h3>
  <div class="card food-card">
    <strong>Restaurant Salvadore</strong> · netoli Vlorės marinos (pietų sustojimas maršrute)
    <p>Žuvies restoranas su savo turgumi · vidutinė kaina ~14 €/asm. · Vakarienė ~17 € asmeniui</p>
    <p>Šeimos valdomas žuvies turgus su restoranu – žvejys savininkas pats pristato kasdienį laimikį, atsiliepimuose minimos sąžiningos kainos ir gausios porcijos.</p>
    <p><a href="https://www.google.com/maps/search/?api=1&query=Restaurant%20Salvadore%2C%20Rruga%20Pelivan%20Leskaj%2C%20Vlor%C3%AB" target="_blank">📍 Google Maps</a></p>
    <strong>Ką paragauti čia</strong>
    <div class="dish-grid">
      <figure><img class="spot-thumb dish-thumb" src="images/uvis-ant-groteli-5dfb84c9.jpg" alt="Žuvis ant grotelių"><figcaption>Žuvis ant grotelių (<em>Peshk në skarë</em>) – 12 €<br><span class="credit">pelican from Tokyo, Japan, CC BY-SA 2.0, <a href="https://commons.wikimedia.org/wiki/File:Grilled_sea_bass_(7906690230).jpg" target="_blank">šaltinis</a></span></figcaption></figure>
      <figure><img class="spot-thumb dish-thumb" src="images/keptas-kalmaras-4894e67c.jpg" alt="Keptas kalmaras"><figcaption>Keptas kalmaras (<em>Kallamar i skuqur</em>) – 8 €<br><span class="credit">Andy Li, CC0, <a href="https://commons.wikimedia.org/wiki/File:Calamari_fritti_-_Enzo%27s_2026-05-05.jpg" target="_blank">šaltinis</a></span></figcaption></figure>
      <figure><img class="spot-thumb dish-thumb" src="images/a-tuonkojo-salotos-341a8ea8.jpg" alt="Aštuonkojo salotos"><figcaption>Aštuonkojo salotos (<em>Sallatë oktapodi</em>) – 9 €<br><span class="credit">Emnamizouni, CC BY-SA 4.0, <a href="https://commons.wikimedia.org/wiki/File:Octopus_salad_.jpg" target="_blank">šaltinis</a></span></figcaption></figure>
    </div>
  </div>
  <div class="card food-card">
    <strong>Taverna Djepi</strong> · netoli nakvynės Hotel Liro – Adults Only, Rruga Aleksandër Moisiu
    <p>Šeimos taverna su jūros vaizdu · vidutinė kaina ~15 €/asm. · Vakarienė ~19 € asmeniui</p>
    <p>Toje pačioje gatvėje kaip Hotel Liro (apie 5 min.), terasa su saulėlydžio vaizdu į jūrą, 4,8/5 įvertinimas – šeimyniška atmosfera ir švelnios kainos.</p>
    <p><a href="https://www.google.com/maps/search/?api=1&query=Taverna%20Djepi%2C%20Rruga%20Aleksand%C3%ABr%20Moisiu%2C%20Vlor%C3%AB" target="_blank">📍 Google Maps</a></p>
    <strong>Ką paragauti čia</strong>
    <div class="dish-grid">
      <figure><img class="spot-thumb dish-thumb" src="images/uvis-ant-groteli-5dfb84c9.jpg" alt="Keptas ešerys"><figcaption>Keptas ešerys (<em>Levrek në skarë</em>) – 13 €<br><span class="credit">pelican from Tokyo, Japan, CC BY-SA 2.0, <a href="https://commons.wikimedia.org/wiki/File:Grilled_sea_bass_(7906690230).jpg" target="_blank">šaltinis</a></span></figcaption></figure>
      <figure><img class="spot-thumb dish-thumb" src="images/krevet-s-ant-groteli-8ab308c6.jpg" alt="Krevetės ant grotelių"><figcaption>Krevetės ant grotelių (<em>Karkaleca në skarë</em>) – 14 €<br><span class="credit">Gordon Leggett, CC BY 4.0, <a href="https://commons.wikimedia.org/wiki/File:2026-05-24_01_Grilled_Spot_prawns_(Pandalus_platyceros)_-_Victoria_BC_CAN.jpg" target="_blank">šaltinis</a></span></figcaption></figure>
      <figure><img class="spot-thumb dish-thumb" src="images/a-tuonkojo-salotos-341a8ea8.jpg" alt="Aštuonkojis"><figcaption>Aštuonkojis (<em>Oktapod</em>) – 12 €<br><span class="credit">Emnamizouni, CC BY-SA 4.0, <a href="https://commons.wikimedia.org/wiki/File:Octopus_salad_.jpg" target="_blank">šaltinis</a></span></figcaption></figure>
    </div>
  </div>

  <h3>4 diena — Divjakė</h3>
  <div class="card food-card">
    <strong>Restorant Pelikan</strong> · netoli Divjakės paplūdimio (pietų sustojimas po Karavastos lagūnos)
    <p>Žuvies restoranėlis paplūdimyje · vidutinė kaina ~13 €/asm. · Vakarienė ~15 € asmeniui</p>
    <p>Vos žingsnis nuo paplūdimio ir lagūnos, lokalūs žvejai pristato ungurius ir žuvį tiesiai iš Karavastos lagūnos – 4,8/5 įvertinimas, puikus paskutinis pietų stotelė prieš skrydį.</p>
    <p><a href="https://www.google.com/maps/search/?api=1&query=Restorant%20Pelikan%2C%20Divjak%C3%AB%20Qend%C3%ABr%20Plazh%2C%20Divjak%C3%AB" target="_blank">📍 Google Maps</a></p>
    <strong>Ką paragauti čia</strong>
    <div class="dish-grid">
      <figure><img class="spot-thumb dish-thumb" src="images/uvis-ant-groteli-5dfb84c9.jpg" alt="Keptas ešerys"><figcaption>Keptas ešerys (<em>Levrek në skarë</em>) – 11 €<br><span class="credit">pelican from Tokyo, Japan, CC BY-SA 2.0, <a href="https://commons.wikimedia.org/wiki/File:Grilled_sea_bass_(7906690230).jpg" target="_blank">šaltinis</a></span></figcaption></figure>
      <figure><img class="spot-thumb dish-thumb" src="images/keptas-kalmaras-4894e67c.jpg" alt="Keptas kalmaras"><figcaption>Keptas kalmaras (<em>Kallamar i skuqur</em>) – 8 €<br><span class="credit">Andy Li, CC0, <a href="https://commons.wikimedia.org/wiki/File:Calamari_fritti_-_Enzo%27s_2026-05-05.jpg" target="_blank">šaltinis</a></span></figcaption></figure>
      <figure><figcaption>Ungurys (lagūnos specialitetas) (<em>Ngjalë</em>) – 14 €</figcaption></figure>
    </div>
  </div>
</section>

<!-- ===================== DISHES ===================== -->
<section id="dishes">
  <h2>🍲 Ką paragauti</h2>

  <div class="card">
    <h4 style="margin:0 0 4px;">Tavė kosi</h4>
    <img class="spot-thumb" src="images/tav-kosi-riena-jogurto-pada-e-e67a530d.jpg" alt="Tavė kosi">
    <div class="credit">Nuotrauka: fugzu, CC BY 2.0, <a href="https://commons.wikimedia.org/wiki/File:TAVE_KOSI-_agnello_allo_yogurt_albanese.jpg" target="_blank">šaltinis</a></div>
    <p>Albanijos nacionalinis patiekalas – keptos ėrienos gabalai, apkepti jogurto ir kiaušinių padaže su ryžiais, iškepti orkaitėje.</p>
    <p>Kaina: 7–11 € · Kur ragauti: Sofra e Ariut, Lili Homemade Food, Guva Mangalem</p>
  </div>

  <div class="card">
    <h4 style="margin:0 0 4px;">Byrek</h4>
    <img class="spot-thumb" src="images/byrekas-88fe47b0.png" alt="Byrek">
    <div class="credit">Nuotrauka: Albaniandude, CC0, <a href="https://commons.wikimedia.org/wiki/File:Byrek_from_Kosovo.png" target="_blank">šaltinis</a></div>
    <p>Plonos tešlos pyragas, dažniausiai su spinatais ir varške arba mėsa – populiarus pusryčių ir užkandžių patiekalas visoje šalyje.</p>
    <p>Kaina: 1–3 € · Kur ragauti: Snack Bar Derexhiku, Guva Mangalem</p>
  </div>

  <div class="card">
    <h4 style="margin:0 0 4px;">Fërgesë</h4>
    <img class="spot-thumb" src="images/f-rges-bd6c81b3.jpg" alt="Fërgesë">
    <div class="credit">Nuotrauka: Kj1595, CC BY-SA 4.0, <a href="https://commons.wikimedia.org/wiki/File:F%C3%ABrges%C3%AB_dhe_Tav%C3%AB_me_oriz.jpg" target="_blank">šaltinis</a></div>
    <p>Troškintos paprikos su pomidorais ir vietine varške ar fetos tipo sūriu, patiekiama moliniame puode.</p>
    <p>Kai
… (sutrumpinta, iš viso 43226 simbolių)
```

</details>

### 7. Puslapis — 10:38:35 ✅

- **Modelis:** `claude-sonnet-5` · **Vykdė:** Native Claude (claude -p) · **Trukmė:** 485.7 s
- **Sistemos promptas:** `prompts/page_designer.md`

<details><summary><b>Užklausa</b></summary>

```json
{
  "language": "lt",
  "research": "# Research summary: Albania, TIA to TIA, 30 Oct – 2 Nov 2026 (4 people, nature focus)\n\n**Coverage:** Reddit is blocked for the crawler, and TripAdvisor forum threads returned 403. So I have no r/travel or r/albania posts and only TripAdvisor search snippets. Everything else comes from Wikivoyage, blogs and operator sites. Dates are the page's own date where visible, otherwise \"undated\". I did not verify any drive times myself.\n\n## 1. Candidate stops\n\n| # | Stop | Why recommended | Source (date) |\n|---|---|---|---|\n| 1 | **Berat** (UNESCO) | Ottoman old town, uncrowded off-season. About 2–3 h from Tirana. | [Wikivoyage Albania](https://en.wikivoyage.org/wiki/Albania) (undated); [TripAdvisor thread snippet](https://www.tripadvisor.com/ShowTopic-g294445-i4583-k6457473-Tirana_Berat_Gjirokastra_Saranda-Albania.html) (undated) |\n| 2 | **Osumi Canyon and Bogovë waterfall** (from Berat) | Best nature stop within reach of Berat. The road from Berat to Bogova village is paved (about 1 h), and a regular car is fine. The canyon viewpoint is reachable in a normal car, and the author parked at the top. | [Wander with Laura](https://wanderwithlaura.com/how-to-get-to-bogove-waterfall-and-osum-canyon/) (published Aug 2022, updated 10 Jan 2026) |\n| 3 | **Divjakë-Karavasta lagoon** (pelicans, flamingos) | Autumn is a best season for birds. About 1h40 from Tirana, 30 min north of Fier and Apollonia. | [Nomads Travel Guide](https://www.nomads-travel-guide.com/places/divjake-karavasta-national-park/) (undated); [Birdingplaces](https://www.birdingplaces.eu/en/birdingplaces/albania/divjake-karavasta-national-park) (undated) |\n| 4 | **Gjirokastër** (UNESCO) | Stone town, \"empty of summer crowds\" in November. About 3h20 from Tirana on Google, and about 4 h realistically. This is at your daily driving limit. | [thingstodoinalbania](https://thingstodoinalbania.com/month/november/) (undated); [TIC Rent Car](https://ticrentcar.com/tirana-to-gjirokastra/) (undated) |\n| 5 | **Blue Eye (Syri i Kaltër)** | Spring-fed pool, open year-round, 07:00–19:00, 50 LEK entry. It is 22 km from Sarandë and 35 km from Gjirokastër. The last 2 km of road are unpaved but \"doable\", followed by a 2 km walk. | [Laure Wanders](https://www.laurewanders.com/blue-eye-albania/) (29 Aug 2026) |\n| 6 | **Llogara Pass and Dhermi coast** | The old pass road is still open and paved. The new tunnel costs 250 LEK (from 16 Sep 2025) and saves about 30 min. Snow and ice risk is Dec–Feb, so fine for early November, though fog and rain are possible. | [Explorer Tom](https://explorertom.com/en/llogara-pass-albania/) (11 Jun 2026) |\n| 7 | **Shkodër, Rozafa Castle, Lake Shkodra** | Easy northern option, about 1h47 from Tirana on the A1. | [Travelmath / ViaMichelin results](https://www.travelmath.com/driving-time/from/Shkoder,+Albania/to/Tirana,+Albania) (undated) |\n| 8 | **Komani Lake ferry** (Koman to Fierza) | The most scenic northern option. See the caveats in section 2. | [Ferry operator](https://komanilakeferry.com/timetables-and-prices/) (undated) |\n| 9 | **Bënja thermal baths / Përmet / Vjosa valley** | About 1h15 north of Gjirokastër, on the paved main road. Year-round, and best in cold weather. | [Vjosa Rafting guide](https://vjosarafting.com/benja-thermal-baths-permet/) and [Himara.net](https://himara.net/blog/benja-thermal-baths-destination-guide) (both undated) |\n| 10 | Pogradec / Lake Ohrid (Albanian side) | Low confidence. It is 2.5–3 h from Tirana. I found nothing on Korçë or Voskopojë in autumn. | [Explorer Tom](https://explorertom.com/en/lake-ohrid-albanian-side/) (undated) |\n\n**Overrated or skippable:**\n- **Ksamil and the Riviera beach towns:** described as overrun and overpriced in season. In late October the coast is mostly shuttered, with Ksamil and Dhermi venues closed and \"finding restaurants between Vlorë and Sarandë is challenging\" ([thingstodoinalbania](https://thingstodoinalbania.com/month/november/), undated). Himarë is \"empty by end of October\" per a TripAdvisor snippet (undated).\n- **Bovilla lake and Dajti:** the Dajti cable car is closed on Tuesdays. Your dates fall on Fri–Mon, so this doesn't matter ([TripAdvisor FAQ](https://www.tripadvisor.com/FAQ-g294445-d4573567-Dajti_Ekspres_Cable_Car.html)).\n- **Not found:** I found no sourced opinion on Bunk'Art, Blloku or Durrës. Treat those as unresearched.\n\n## 2. Road and logistics warnings\n\n**Roads to exclude for a standard rental car** (all from [Localrent \"Prohibited routes\"](https://www.localrent.com/en/journal/albania/articles/prohibited-routes/), undated with 2023 file metadata):\n- **SH74 Berat–Përmet:** \"narrow unpaved mountain road covered with small stones\". This is the one your earlier projects flagged.\n- **Berat–Përmet through Osumi Canyon:** unpaved with potholes and large puddles.\n- **Memaliaj–Berat (Martallozi):** unpaved.\n- **Tirana–Qafë-Shtamë via Lake Bovilla:** unpaved serpentine. A regular car can reach the dam, but not beyond ([Localrent](https://www.localrent.com/en/journal/albania/articles/prohibited-routes/) and search results, undated).\n- **Krujë–Burreli:** \"terrible state of disrepair\".\n- **Theth–Valbona:** already excluded by you.\n- **Beach access roads off SH8:** unpaved.\n\nOsumi Canyon is fine only when approached from Berat, so don't continue from it onward to Përmet.\n\n**Komani ferry caveats:**\n- **Season end is unclear.** The operator says 15 Apr to 5 Nov, so 30 Oct – 2 Nov is inside the season. A search snippet from another page said 2 Nov, which I could not verify. Confirm directly with the operator.\n- **Timetable:** Koman 09:00 to Fierza (about 2.5 h), and Fierza 13:00 back to Koman ([operator](https://komanilakeferry.com/timetables-and-prices/); [Explorer Tom](https://explorertom.com/en/koman-lake-ferry-guide/), 2026).\n- **A same-day round trip returns after dark.** By my own arithmetic, the boat is back at Koman about 15:30, plus at least 2 h to Shkodër gives about 17:30, after sunset. This is my calculation, not from a source. It suggests sleeping near Shkodër or Koman.\n- **The car does not need to cross.** The ferry is a dead end, so you would leave the car at Koman and go as foot passengers. That avoids the vehicle-booking problem below.\n- **Car on the ferry:** online pre-booking is essential, priced at €7/m² ([Explorer Tom](https://explorertom.com/en/koman-lake-ferry-guide/)). One traveller in Nov 2025 had to upgrade to an SUV because of rental-company restrictions ([Perchance to Roam](https://perchancetoroam.com/2025/11/01/a-complete-guide-to-taking-albanias-komani-lake-ferry-with-or-without-a-car/), 1 Nov 2025). Check the rental terms.\n- **Road Shkodër to Koman (SH25):** about 60 km and about 2 h, with a narrow one-lane tunnel near the terminal ([Explorer Tom](https://explorertom.com/en/koman-lake-ferry-guide/)). It was in poor shape in Nov 2025, with the last 10 km \"completely ripped open\" ([Perchance to Roam](https://perchancetoroam.com/2025/11/01/a-complete-guide-to-taking-albanias-komani-lake-ferry-with-or-without-a-car/)). [inAlbania](https://www.inalbania.info/koman-road-transformed-to-boost-tourism-in-northern-albania/) (15 Sep 2026) reports the Vau i Dejës–Koman reconstruction as completed. It gives no surface or tunnel details, and the government page I tried to fetch was empty. I'd call this likely improved but not confirmed.\n\n**General driving:**\n- **Time estimates:** Google Maps underestimates mountain roads. Add 25% (\"2 h shows, allow 2.5\", [Endless Travellers](https://theendlesstravellers.com/driving-in-albania/), updated 22 Feb 2026). Tirana to Theth shows 3.5 h but takes about 5 h ([Along Dusty Roads](https://www.alongdustyroads.com/posts/driving-in-albania-car-hire), updated Jun 2025).\n- **Night driving:** avoid it. Village roads are unlit, with livestock and pedestrians (same Along Dusty Roads and Wikivoyage sources). You land at 20:30 on Friday, so keep the first night's drive short, and check that the rental desk is open at that hour (not researched).\n- **Flash floods:** flash flooding is possible in the Vjosa and Osum valleys after heavy rain, and the Lengarica canyon is inaccessible after heavy rain ([thingstodoinalbania](https://thingstodoinalbania.com/month/november/), undated, single source).\n- **Tolls:** the Llogara Tunnel and the A1 to Kosovo are tolled ([Endless Travellers](https://theendlesstravellers.com/driving-in-albania/)).\n- **Rules:** police speed checks are frequent, alcohol limit is 0.01% ([Wikivoyage](https://en.wikivoyage.org/wiki/Albania)).\n\n## 3. Seasonal notes (30 Oct – 2 Nov)\n\n- **Rain:** November is the rainiest month, about 12 rain days and 180 mm, with roughly 12–15 °C average temperatures ([Climates to Travel](https://www.climatestotravel.com/weatherbymonth/albania/november) and similar, undated).\n- **Unreliable figure:** thingstodoinalbania claims 25 °C highs and 2 in of rain in November. That contradicts every other source, so don't use its numbers.\n- **Snow:** snow is possible above 1,500 m before mid-November. Theth/Valbona is snow-covered ([thingstodoinalbania](https://thingstodoinalbania.com/month/november/), undated, single source).\n- **Fog:** persistent morning fog on Lake Shkodra and in the Korçë basin (same source).\n- **Lake Shkodra boats:** schedules shrink to weekends only (same source, unconfirmed). Your Sat and Sun fall on weekends.\n- **Daylight:** sources give sunset of 16:45–17:25 (Wanderlog and others, undated). Their sunrise figure of 05:46 is implausible, so I don't trust them. My own rough estimate for Tirana (CET, after clocks change on 25 Oct) is sunset about 16:30–16:40. That is earlier than your 17:00–17:30 assumption. The Weather/Season Agent should check this with Open-Meteo.\n- **Calendar:** 30 Oct is a Friday and 2 Nov a Monday, so the trip has two full days (Sat, Sun) plus the Friday-night arrival and the Monday return. Monday needs the car back at TIA by about 17:00.\n\n## 4. Route shapes for the Logistics Validator (not validated)\n\n- **Central/south:** Fri night near Tirana or Durrës. Sat via Karavasta and Apollonia to Berat. Sun via Osumi and Bogova to Gjirokastër. Mon Gjirokastër to TIA at about 3.5–4 h. The last leg is the tightest, needing an early start. Blue Eye and Përmet do not fit without dropping something.\n- **North (easier):** Fri night Tirana. Sat Shkodër, Rozafa and the lake. Sun Komani ferry from a Shkodër or Koman base. Mon return via the A1 (about 1h47).\n\nBoth fit the 3.5–4 h limit only if the Validator confirms the legs. The central/south option depends on avoiding SH74 and the Berat–Përmet canyon road.\n\n## 5. Gaps to close\n\n- Direct confirmation of the Komani ferry season end and whether foot passengers can get a seat in early November.\n- Rental terms: a 4-person vehicle, ferry carriage, and the airport desk's opening hours after a 20:30 landing.\n- Osumi Canyon water levels and access in early November. The one detailed source visited in summer.\n- Korçë and Voskopojë autumn conditions, if you want a southeastern alternative.",
  "accommodation": "## Nakvynės vietos (tik užsakytos)\n\nKeliautojas jau užsakė ir patvirtino konkrečius nakvynės objektus per booking.com nuorodas. Žemiau — tik šios užsakytos vietos, be papildomų alternatyvų.\n\n### 1. Tirana (penktadienis, 2026-10-30 → šeštadienis, 2026-10-31)\n\n**✅ Užsakyta — Hanna Apartment** — **51 €/naktį**\n- Rruga e Elbasanit, Tirana. Įvertinimas 9.0/10 (186 atsiliepimai).\n- Kondicionierius, nemokamas WiFi. Tinka 4 žmonėms (butas).\n- Nuoroda: https://www.booking.com/hotel/al/apartament-tirana8.lt.html\n\n### 2. Beratas (šeštadienis, 2026-10-31 → sekmadienis, 2026-11-01)\n\n**✅ Užsakyta — DD Villa** — **61 €/naktį**\n- Rruga Antipatrea, Beratas. Įvertinimas 8.8/10 (667 atsiliepimai).\n- Sodas, baras, bendra svetainė, miesto vaizdas, pusryčiai (bufetas/à la carte), privatus parkavimas (už papildomą mokestį), restoranas vietoje.\n- Nuoroda: https://www.booking.com/hotel/al/dd-villa.lt.html\n\n### 3. Vlorė / Radhimė (sekmadienis, 2026-11-01 → pirmadienis, 2026-11-02)\n\n**✅ Užsakyta — Hotel Liro – Adults Only** — **117 €/naktį**\n- Aleksandër Moisiu Street, Vlorė. Įvertinimas 8.6/10 (1295 atsiliepimai).\n- Privatus paplūdimio ruožas, lauko baseinas, nemokamas parkavimas, restoranas/baras, pusryčiai, vaizdas į jūrą nuo balkono. Autobusų stotelė priešais viešbutį.\n- Nuoroda: https://www.booking.com/hotel/al/liro.lt.html\n- ⚠️ Pastaba: \"Adults Only\" — jei grupėje yra vaikų, šią vietą reikėtų pakeisti.\n\n**Biudžeto suma nakvynėms (3 naktys, visai grupei):** 51 + 61 + 117 = **229 €**",
  "booking_search": [
    {
      "city": "Tirana",
      "name": "Hanna Apartment",
      "checkin": "2026-10-30",
      "checkout": "2026-10-31",
      "nights": 1,
      "price_per_night_eur": 51,
      "url": "https://www.booking.com/searchresults.html?ss=Hanna+Apartment%2C+Tirana&checkin=2026-10-30&checkout=2026-10-31&group_adults=4&group_children=0&no_rooms=1"
    },
    {
      "city": "Berat",
      "name": "DD Villa",
      "checkin": "2026-10-31",
      "checkout": "2026-11-01",
      "nights": 1,
      "price_per_night_eur": 61,
      "url": "https://www.booking.com/searchresults.html?ss=DD+Villa%2C+Berat&checkin=2026-10-31&checkout=2026-11-01&group_adults=4&group_children=0&no_rooms=1"
    },
    {
      "city": "Vlorë",
      "name": "Hotel Liro - Adults Only",
      "checkin": "2026-11-01",
      "checkout": "2026-11-02",
      "nights": 1,
      "price_per_night_eur": 117,
      "url": "https://www.booking.com/searchresults.html?ss=Hotel+Liro+-+Adults+Only%2C+Vlor%C3%AB&checkin=2026-11-01&checkout=2026-11-02&group_adults=4&group_children=0&no_rooms=1"
    }
  ],
  "stays": [
    {
      "url": "https://www.booking.com/hotel/al/apartament-tirana8.lt.html",
      "name": "Hanna Apartment",
      "address": "Rruga e Elbasanit, 1035 Tirana, Albanija, 1035, Rruga e Elbasanit, Albanija",
      "description": "Hanna Apartment is located in Tirana. This apartment provides air-conditioned accommodation with free WiFi.",
      "full_description": null,
      "facilities": null,
      "rating": 9.0,
      "rating_scale": 10,
      "review_count": 186,
      "photo_urls": [
        "https://cf.bstatic.com/xdata/images/hotel/max1024x768/633887464.jpg?k=b976c4febe171b551f477e9eee870608b6dc963117d876c793f0d9f4e74a10c1&o=&hp=1",
        "https://cf.bstatic.com/xdata/images/hotel/max1024x768/633887550.jpg?k=694dc1002849285d2f750017340c1edd34a96dd80c7fbc5b6481ab43eadda7c0&o=&hp=1",
        "https://cf.bstatic.com/xdata/images/hotel/max1024x768/633887291.jpg?k=4963ffaa4c10e0fd9f47b51e58b930fc53eff67747c24a914957854aecfefbc0&o=&hp=1",
        "https://cf.bstatic.com/xdata/images/hotel/max1024x768/633889677.jpg?k=5da3b33dfa81e6240d74fe7d36bf94844df25d861a8cfb0f6e6d273f1eb9459a&o=&hp=1",
        "https://cf.bstatic.com/xdata/images/hotel/max1024x768/651343123.jpg?k=5441b1e29d0d9b0725ae1274688a078b2e764fba7c641900e5a8cc9a87c5bc84&o=&hp=1"
      ],
      "photos": [
        {
          "stop_name": "Hanna Apartment",
          "local_path": "images/stay-hanna-apartment-1.jpg",
          "commons_filename": "",
          "license": "© apgyvendinimo įstaiga / Booking.com",
          "author": null,
          "source_url": "https://www.booking.com/hotel/al/apartament-tirana8.lt.html",
          "size_bytes": 110275
        },
        {
          "stop_name": "Hanna Apartment",
          "local_path": "images/stay-hanna-apartment-2.jpg",
          "commons_filename": "",
          "license": "© apgyvendinimo įstaiga / Booking.com",
          "author": null,
          "source_url": "https://www.booking.com/hotel/al/apartament-tirana8.lt.html",
          "size_bytes": 32003
        },
        {
          "stop_name": "Hanna Apartment",
          "local_path": "images/stay-hanna-apartment-3.jpg",
          "commons_filename": "",
          "license": "© apgyvendinimo įstaiga / Booking.com",
          "author": null,
          "source_url": "https://www.booking.com/hotel/al/apartament-tirana8.lt.html",
          "size_bytes": 55703
        },
        {
          "stop_name": "Hanna Apartment",
          "local_path": "images/stay-hanna-apartment-4.jpg",
          "commons_filename": "",
          "license": "© apgyvendinimo įstaiga / Booking.com",
          "author": null,
          "source_url": "https://www.booking.com/hotel/al/apartament-tirana8.lt.html",
          "size_bytes": 53502
        },
        {
          "stop_name": "Hanna Apartment",
          "local_path": "images/stay-hanna-apartment-5.jpg",
          "commons_filename": "",
          "license": "© apgyvendinimo įstaiga / Booking.com",
          "author": null,
          "source_url": "https://www.booking.com/hotel/al/apartament-tirana8.lt.html",
          "size_bytes": 54202
        }
      ]
    },
    {
      "url": "https://www.booking.com/hotel/al/dd-villa.lt.html",
      "name": "DD Villa",
      "address": "Rruga Antipatrea, 5001 Beratis, Albanija, 5001, Rruga Antipatrea, Albanija",
      "description": "Situated in Berat, DD Villa features a garden, a bar and a shared lounge. The property has city views. Private parking can be arranged at an extra charge.",
      "full_description": [
        "Situated in Berat, DD Villa features a garden, a bar and a shared lounge. The property has city views. Private parking can be arranged at an extra charge. The bed and breakfast will provide guests with air-conditioned units offering a wardrobe, a kettle, a dishwasher, a microwave, a safety deposit box, a flat-screen TV and a private bathroom with a bidet. Free WiFi is accessible to all guests, while certain rooms are equipped with a terrace. At the bed and breakfast, every unit is equipped with bed linen and towels. A buffet, à la carte or continental breakfast is available at the property. Guests are welcome to eat in the on-site family-friendly restaurant, which is open for dinner, lunch, brunch and high tea. Sightseeing tours are available around the property. Both a bicycle rental service and a car rental service are available at the bed and breakfast, while cycling can be enjoyed nearby. Tirana International Mother Teresa Airport is 120 km from the property, and the property offers a paid airport shuttle service."
      ],
      "facilities": [
        "Populiariausi patogumai",
        "Privati automobilių stovėjimo aikštelė",
        "Spartus nemokamas belaidis internetas (101 Mbps)",
        "Pervežimas iš / į oro uostą",
        "Numeriai nerūkantiems",
        "Numeriai šeimai",
        "Aptarnavimas numeriuose",
        "Restoranas",
        "Baras",
        "Nuostabūs pusryčiai"
      ],
      "rating": 8.8,
      "rating_scale": 10,
      "review_count": 667,
      "photo_urls": [
        "https://cf.bstatic.com/xdata/images/hotel/max1024x768/529582807.jpg?k=731fe174d8d2b7402280e7c8008fdd355a874d76e0b7f03f1f516ad3c92ccd4f&o=&hp=1",
        "https://cf.bstatic.com/xdata/images/hotel/max1024x768/921271115.jpg?k=714680e569beb3f835a5ab5f15daaf4460dda2cd2509890599543048e17af49a&o=&hp=1",
        "https://cf.bstatic.com/xdata/images/hotel/max1024x768/529582816.jpg?k=8c6581a00d3c484f9e62bbaa3ba21bf08b13e50ccda4cf1e32c52876fb08a13d&o=&hp=1",
        "https://cf.bstatic.com/xdata/images/hotel/max1024x768/544036358.jpg?k=03e5cee7c142331675268001c541cbe0e4cb64ba67f8d850dc1cf05be6ee1024&o=&hp=1",
        "https://cf.bstatic.com/xdata/images/hotel/max1024x768/529582821.jpg?k=58830e6a252b81f2a06faccae174fad12a474f063ed8162b382a1ac3626b93d9&o=&hp=1"
      ],
      "photos": [
        {
          "stop_name": "DD Villa",
          "local_path": "images/stay-dd-villa-1.jpg",
          "commons_filename": "",
          "license": "© apgyvendinimo įstaiga / Booking.com",
          "author": null,
          "source_url": "https://www.booking.com/hotel/al/dd-villa.lt.html",
          "size_bytes": 154626
        },
        {
          "stop_name": "DD Villa",
          "local_path": "images/stay-dd-villa-2.jpg",
          "commons_filename": "",
          "license": "© apgyvendinimo įstaiga / Booking.com",
          "author": null,
          "source_url": "https://www.booking.com/hotel/al/dd-villa.lt.html",
          "size_bytes": 69651
        },
        {
          "stop_name": "DD Villa",
          "local_path": "images/stay-dd-villa-3.jpg",
          "commons_filename": "",
          "license": "© apgyvendinimo įstaiga / Booking.com",
          "author": null,
          "source_url": "https://www.booking.com/hotel/al/dd-villa.lt.html",
          "size_bytes": 99758
        },
        {
          "stop_name": "DD Villa",
          "local_path": "images/stay-dd-villa-4.jpg",
          "commons_filename": "",
          "license": "© apgyvendinimo įstaiga / Booking.com",
          "author": null,
          "source_url": "https://www.booking.com/hotel/al/dd-villa.lt.html",
          "size_bytes": 99712
        },
        {
          "stop_name": "DD Villa",
          "local_path": "images/stay-dd-villa-5.jpg",
          "commons_filename": "",
          "license": "© apgyvendinimo įstaiga / Booking.com",
          "author": null,
          "source_url": "https://www.booking.com/hotel/al/dd-villa.lt.html",
          "size_bytes": 129326
        }
      ]
    },
    {
      "url": "https://www.booking.com/hotel/al/liro.lt.html",
      "name": "Hotel Liro - Adults Only",
      "address": "Aleksandër Moisiu Street, 9405 Vliorė, Albanija, 9405, Aleksandër Moisiu Street, Albanija",
      "description": "Located in Vlorë, Hotel Liro - Adults Only offers a private beach area with free-to-use sun loungers and parasols.",
      "full_description": [
        "Located in Vlorë, Hotel Liro - Adults Only offers a private beach area with free-to-use sun loungers and parasols. The on-site bar and restaurant offers a spacious terrace where guests can enjoy the Mediterranean dishes it serves. Free WiFi access is available throughout the property. All the rooms are air-conditioned and come with a furnished balcony overlooking the sea. Each room is equipped with satellite TV, a minibar and a safe. Featuring a shower, private bathrooms also come with a hairdryer and free toiletries. Hotel Liro - Adults Only offers an array of activities can be enjoyed on site or in the surroundings, including windsurfing. The cenre of Vlorë and the scenic outlook of Kuzum Baba can be found within a 6-km radius. The Archaeological Park of Oricum is 10 km from Liro Hotel. Llogara National Park is 25 km away. The local bus stop is right in front of the hotel. Tirana Airport is 150 km away. The property offers free parking."
      ],
      "facilities": [
        "Populiariausi patogumai",
        "Lauko baseinas",
        "Nemokama vieta automobiliui",
        "Šalia paplūdimio",
        "Nemokamas belaidis internetas",
        "Numeriai šeimai",
        "Restoranas",
        "Numeriai nerūkantiems",
        "Baras",
        "Privati paplūdimio dalis",
        "Nuostabūs pusryčiai"
      ],
      "rating": 8.6,
      "rating_scale": 10,
      "review_count": 1295,
      "photo_urls": [
        "https://cf.bstatic.com/xdata/images/hotel/max1024x768/506995294.jpg?k=23925d61528b241c35e7b43446d3f11a9faa202b08e9903c82a6e3cb2afa43d7&o=&hp=1",
        "https://cf.bstatic.com/xdata/images/hotel/max1024x768/506995475.jpg?k=8b2bd840a2ed21d4d6da7442afc978dd5073fc1eb1d9a567413fdab748546eac&o=&hp=1",
        "https://cf.bstatic.com/xdata/images/hotel/max1024x768/556057394.jpg?k=575cc81ebc625197b6b6c6af18c2ec9a6eda54fa3ed14e29ecef4935b13b27a6&o=&hp=1",
        "https://cf.bstatic.com/xdata/images/hotel/max1024x768/506995518.jpg?k=2db992e93cda20eb611af0c65c6d59f388efc2150e468dfbfae8e8e3fbb3b665&o=&hp=1",
        "https://cf.bstatic.com/xdata/images/hotel/max1024x768/506995661.jpg?k=d3755c0ed1215710923e75d5050056023d41ecd92820d69af21aa384123992dd&o=&hp=1"
      ],
      "photos": [
        {
          "stop_name": "Hotel Liro - Adults Only",
          "local_path": "images/stay-hotel-liro-adults-only-1.jpg",
          "commons_filename": "",
          "license": "© apgyvendinimo įstaiga / Booking.com",
          "author": null,
          "source_url": "https://www.booking.com/hotel/al/liro.lt.html",
          "size_bytes": 125824
        },
        {
          "stop_name": "Hotel Liro - Adults Only",
          "local_path": "images/stay-hotel-liro-adults-only-2.jpg",
          "commons_filename": "",
          "license": "© apgyvendinimo įstaiga / Booking.com",
          "author": null,
          "source_url": "https://www.booking.com/hotel/al/liro.lt.html",
          "size_bytes": 238091
        },
        {
          "stop_name": "Hotel Liro - Adults Only",
          "local_path": "images/stay-hotel-liro-adults-only-3.jpg",
          "commons_filename": "",
          "license": "© apgyvendinimo įstaiga / Booking.com",
          "author": null,
          "source_url": "https://www.booking.com/hotel/al/liro.lt.html",
          "size_bytes": 133915
        },
        {
          "stop_name": "Hotel Liro - Adults Only",
          "local_path": "images/stay-hotel-liro-adults-only-4.jpg",
          "commons_filename": "",
          "license": "© apgyvendinimo įstaiga / Booking.com",
          "author": null,
          "source_url": "https://www.booking.com/hotel/al/liro.lt.html",
          "size_bytes": 211665
        },
        {
          "stop_name": "Hotel Liro - Adults Only",
          "local_path": "images/stay-hotel-liro-adults-only-5.jpg",
          "commons_filename": "",
          "license": "© apgyvendinimo įstaiga / Booking.com",
          "author": null,
          "source_url": "https://www.booking.com/hotel/al/liro.lt.html",
          "size_bytes": 64880
        }
      ]
    }
  ],
  "itinerary": "{\"days\":[{\"number\":1,\"title\":\"Atvykimas į Tiraną\",\"stops\":[{\"name\":\"Tiranos oro uostas (TIA)\",\"lat\":41.4147,\"lon\":19.7206,\"arrive\":\"20:30\",\"depart\":\"21:00\",\"maps_query\":\"Tirana International Airport Nënë Tereza, Albania\",\"google_maps_url\":\"https://www.google.com/maps/search/?api=1&query=Tirana%20International%20Airport%20N%C3%ABn%C3%AB%20Tereza%2C%20Albania\",\"notes\":\"Skrydis iš Varšuvos nusileidžia 20:30. Automobilio nuomos (VW Tiguan ar panašus visureigis, tinka 4 žmonėms ir bagažui, su Papildomo vairuotojo ir pilnos apsaugos draudimu) atsiėmimas 21:00. Tą pačią vietą reikės grąžinti automobilį lapkričio 2 d. iki 17:00.\",\"arrive_by\":\"car\",\"transit\":\"\"},{\"name\":\"Hanna Apartment\",\"lat\":41.3192,\"lon\":19.8294,\"arrive\":\"21:20\",\"depart\":\"21:20\",\"maps_query\":\"Apartament Tirana8, Rruga e Elbasanit, Tirana, Albania\",\"google_maps_url\":\"https://www.google.com/maps/search/?api=1&query=Apartament%20Tirana8%2C%20Rruga%20e%20Elbasanit%2C%20Tirana%2C%20Albania\",\"notes\":\"Pirma nakvynė – butas Rruga e Elbasanit, kondicionierius, nemokamas WiFi, tinka 4 žmonėms. Kelias nuo oro uosto apie 20 min, vėlai vakare eismas ramus.\",\"arrive_by\":\"car\",\"transit\":\"\"}],\"driving_minutes\":20,\"overnight_city\":\"Tirana\"},{\"number\":2,\"title\":\"Krujė, Belšo ežeras ir Beratas\",\"stops\":[{\"name\":\"Krujos pilis ir Skenderbego muziejus bei Senasis bazaras\",\"lat\":41.5086,\"lon\":19.7919,\"arrive\":\"09:45\",\"depart\":\"10:30\",\"maps_query\":\"Kalaja e Krujës, Krujë, Albania\",\"google_maps_url\":\"https://www.google.com/maps/search/?api=1&query=Kalaja%20e%20Kruj%C3%ABs%2C%20Kruj%C3%AB%2C%20Albania\",\"notes\":\"Skenderbego muziejus pilies viduje, bilietas apie 200 lekų (~2 €). Žiemos darbo laikas apytiksliai 09:00–16:00 – darbo laiką verta pasitikrinti. Prie pilies – senasis bazaras su amatininkų dirbiniais ir suvenyrais.\",\"arrive_by\":\"car\",\"transit\":\"\"},{\"name\":\"Belšo ežeras (apžvalgos sustojimas)\",\"lat\":41.0931,\"lon\":19.8828,\"arrive\":\"12:02\",\"depart\":\"12:17\",\"maps_query\":\"Liqeni i Belshit, Belsh, Albania\",\"google_maps_url\":\"https://www.google.com/maps/search/?api=1&query=Liqeni%20i%20Belshit%2C%20Belsh%2C%20Albania\",\"notes\":\"Trumpas sustojimas pakeliui – gražus Dumrės plokščiakalnio ir ežerų vaizdas, proga kavai ir nuotraukai.\",\"arrive_by\":\"car\",\"transit\":\"\"},{\"name\":\"Pietūs „Lili Homemade Food“\",\"lat\":40.7064,\"lon\":19.9513,\"arrive\":\"13:54\",\"depart\":\"14:55\",\"maps_query\":\"Lili Homemade Food, Berat, Albania\",\"google_maps_url\":\"https://www.google.com/maps/search/?api=1&query=Lili%20Homemade%20Food%2C%20Berat%2C%20Albania\",\"notes\":\"Populiarus namų virtuvės restoranas Mangalemo kvartale, vietiniai patiekalai.\",\"arrive_by\":\"car\",\"transit\":\"\"},{\"name\":\"Mangalemo senasis kvartalas\",\"lat\":40.706,\"lon\":19.951,\"arrive\":\"14:55\",\"depart\":\"15:09\",\"maps_query\":\"Mangalem Quarter, Berat, Albania\",\"google_maps_url\":\"https://www.google.com/maps/search/?api=1&query=Mangalem%20Quarter%2C%20Berat%2C%20Albania\",\"notes\":\"Pasivaikščiojimas osmanų laikų gatvelėmis su garsiaisiais „tūkstančio langų“ namais.\",\"arrive_by\":\"walk\",\"transit\":\"\"},{\"name\":\"Berato pilis (Kalaja e Beratit)\",\"lat\":40.7014,\"lon\":19.9447,\"arrive\":\"15:29\",\"depart\":\"16:13\",\"maps_query\":\"Kalaja e Beratit, Berat, Albania\",\"google_maps_url\":\"https://www.google.com/maps/search/?api=1&query=Kalaja%20e%20Beratit%2C%20Berat%2C%20Albania\",\"notes\":\"Gyvenama pilis su bizantiškomis bažnyčiomis. Įėjimas į teritoriją laisvas, Onufrijaus muziejuje bilietas apie 200 lekų – darbo laiką verta pasitikrinti.\",\"arrive_by\":\"walk\",\"transit\":\"\"},{\"name\":\"Goricos tiltas ir kvartalas\",\"lat\":40.7021,\"lon\":19.9497,\"arrive\":\"16:38\",\"depart\":\"17:08\",\"maps_query\":\"Ura e Goricës, Berat, Albania\",\"google_maps_url\":\"https://www.google.com/maps/search/?api=1&query=Ura%20e%20Goric%C3%ABs%2C%20Berat%2C%20Albania\",\"notes\":\"Osmanų laikų akmeninis tiltas per Osumo upę – ypač gražus prieblandoje, puikus vaizdas į Mangalemą.\",\"arrive_by\":\"walk\",\"transit\":\"\"},{\"name\":\"DD Villa\",\"lat\":40.7057,\"lon\":19.952,\"arrive\":\"17:23\",\"depart\":\"17:23\",\"maps_query\":\"DD Villa, Rruga Antipatrea, Berat, Albania\",\"google_maps_url\":\"https://www.google.com/maps/search/?api=1&query=DD%20Villa%2C%20Rruga%20Antipatrea%2C%20Berat%2C%20Albania\",\"notes\":\"Nakvynė Berate – sodas, baras, pusryčiai, privatus parkavimas už papildomą mokestį.\",\"arrive_by\":\"walk\",\"transit\":\"\"}],\"driving_minutes\":180,\"overnight_city\":\"Berat\"},{\"number\":3,\"title\":\"Osumio kanjonas ir Vlorės pakrantė\",\"stops\":[{\"name\":\"Osumio kanjono apžvalgos aikštelė\",\"lat\":40.5044,\"lon\":20.227,\"arrive\":\"10:15\",\"depart\":\"11:00\",\"maps_query\":\"Kanioni i Osumit, Çorovodë, Albania\",\"google_maps_url\":\"https://www.google.com/maps/search/?api=1&query=Kanioni%20i%20Osumit%2C%20%C3%87orovod%C3%AB%2C%20Albania\",\"notes\":\"Vienas gražiausių gamtos vaizdų kelyje – kanjono apžvalgos aikštelė prie kelio, patogi stovėjimo vieta.\",\"arrive_by\":\"car\",\"transit\":\"\"},{\"name\":\"Pietūs Vlorės marina\",\"lat\":40.458,\"lon\":19.485,\"arrive\":\"13:51\",\"depart\":\"14:51\",\"maps_query\":\"Marina e Vlorës, Vlorë, Albania\",\"google_maps_url\":\"https://www.google.com/maps/search/?api=1&query=Marina%20e%20Vlor%C3%ABs%2C%20Vlor%C3%AB%2C%20Albania\",\"notes\":\"Vlorės uosto promenadoje daug žuvies restoranų – pasirinkite bet kurį su šviežia dienos žuvimi.\",\"arrive_by\":\"car\",\"transit\":\"\"},{\"name\":\"Vlorės pakrantės promenada (Lungomare)\",\"lat\":40.458,\"lon\":19.485,\"arrive\":\"14:51\",\"depart\":\"15:51\",\"maps_query\":\"Lungomare, Vlorë, Albania\",\"google_maps_url\":\"https://www.google.com/maps/search/?api=1&query=Lungomare%2C%20Vlor%C3%AB%2C%20Albania\",\"notes\":\"Pasivaikščiojimas pakrante, vaizdas į Jonų jūrą ir Sazano salą.\",\"arrive_by\":\"walk\",\"transit\":\"\"},{\"name\":\"Hotel Liro – Adults Only\",\"lat\":40.455,\"lon\":19.484,\"arrive\":\"16:01\",\"depart\":\"16:01\",\"maps_query\":\"Hotel Liro Adults Only, Rruga Aleksandër Moisiu, Vlorë, Albania\",\"google_maps_url\":\"https://www.google.com/maps/search/?api=1&query=Hotel%20Liro%20Adults%20Only%2C%20Rruga%20Aleksand%C3%ABr%20Moisiu%2C%20Vlor%C3%AB%2C%20Albania\",\"notes\":\"Nakvynė Vlorėje – privatus paplūdimio ruožas, lauko baseinas, vaizdas į jūrą nuo balkono. Tik suaugusiems.\",\"arrive_by\":\"car\",\"transit\":\"\"}],\"driving_minutes\":205,\"overnight_city\":\"Vlorë\"},{\"number\":4,\"title\":\"Divjakė-Karavasta ir išvykimas\",\"stops\":[{\"name\":\"Karavastos lagūnos Lankytojų centras ir apžvalgos bokštas\",\"lat\":40.979,\"lon\":19.466,\"arrive\":\"10:10\",\"depart\":\"13:20\",\"maps_query\":\"Qendra e Vizitorëve Divjakë-Karavasta, Divjakë, Albania\",\"google_maps_url\":\"https://www.google.com/maps/search/?api=1&query=Qendra%20e%20Vizitor%C3%ABve%20Divjak%C3%AB-Karavasta%2C%20Divjak%C3%AB%2C%20Albania\",\"notes\":\"Automobilį palikite Lankytojų centro aikštelėje – čia veda geras asfaltuotas/tvarkingas kelias, o čia pat yra apie 35 m aukščio apžvalgos bokštas su gražiu vaizdu į lagūną. Jei norite pasiekti giliau lagūnoje esantį bokštą, paskutinius 1–2 km (ir tiek pat atgal) reikia nueiti pėsčiomis – nuomotam automobiliui tas kelias po lietaus būna dumblinas ir netinkamas. Rudenį čia gerai matomi rausvieji pelikanai ir flamingai. Nedidelis mokestis automobiliui įvažiuojant į parką.\",\"arrive_by\":\"car\",\"transit\":\"\"},{\"name\":\"Pietūs Divjakės paplūdimyje\",\"lat\":40.9958,\"lon\":19.4705,\"arrive\":\"13:30\",\"depart\":\"14:30\",\"maps_query\":\"Plazhi i Divjakës, Divjakë, Albania\",\"google_maps_url\":\"https://www.google.com/maps/search/?api=1&query=Plazhi%20i%20Divjak%C3%ABs%2C%20Divjak%C3%AB%2C%20Albania\",\"notes\":\"Paplūdimio žuvies kioskai ir restoranėliai – šviežia žuvis ir jūros gėrybės.\",\"arrive_by\":\"car\",\"transit\":\"\"},{\"name\":\"Tiranos oro uostas (TIA) – automobilio grąžinimas ir skrydis namo\",\"lat\":41.4147,\"lon\":19.7206,\"arrive\":\"16:15\",\"depart\":\"19:05\",\"maps_query\":\"Tirana International Airport Nënë Tereza, Albania\",\"google_maps_url\":\"https://www.google.com/maps/search/?api=1&query=Tirana%20International%20Airport%20N%C3%ABn%C3%AB%20Tereza%2C%20Albania\",\"notes\":\"Automobilio grąžinimas (reikia iki 17:00) – atsargos laiko pakaks. Skrydis į Varšuvą išskrenda 19:05 – registracijai ir saugumo patikrai liks pakankamai laiko.\",\"arrive_by\":\"car\",\"transit\":\"\"}],\"driving_minutes\":170,\"overnight_city\":\"Nėra (skrydis namo)\"}]}",
  "day_routes": [
    {
      "day": 1,
      "title": "Atvykimas į Tiraną",
      "urls": [
        "https://www.google.com/maps/dir/?api=1&origin=Tirana+International+Airport+N%C3%ABn%C3%AB+Tereza,+Albania&destination=Apartament+Tirana8,+Rruga+e+Elbasanit,+Tirana,+Albania&travelmode=driving"
      ],
      "modes": [
        "car"
      ]
    },
    {
      "day": 2,
      "title": "Krujė, Belšo ežeras ir Beratas",
      "urls": [
        "https://www.google.com/maps/dir/?api=1&origin=Kalaja+e+Kruj%C3%ABs,+Kruj%C3%AB,+Albania&destination=Lili+Homemade+Food,+Berat,+Albania&travelmode=driving&waypoints=Liqeni+i+Belshit,+Belsh,+Albania",
        "https://www.google.com/maps/dir/?api=1&origin=Lili+Homemade+Food,+Berat,+Albania&destination=DD+Villa,+Rruga+Antipatrea,+Berat,+Albania&travelmode=walking&waypoints=Mangalem+Quarter,+Berat,+Albania|Kalaja+e+Beratit,+Berat,+Albania|Ura+e+Goric%C3%ABs,+Berat,+Albania"
      ],
      "modes": [
        "car",
        "walk"
      ]
    },
    {
      "day": 3,
      "title": "Osumio kanjonas ir Vlorės pakrantė",
      "urls": [
        "https://www.google.com/maps/dir/?api=1&origin=Kanioni+i+Osumit,+%C3%87orovod%C3%AB,+Albania&destination=Hotel+Liro+Adults+Only,+Rruga+Aleksand%C3%ABr+Moisiu,+Vlor%C3%AB,+Albania&travelmode=driving&waypoints=Marina+e+Vlor%C3%ABs,+Vlor%C3%AB,+Albania"
      ],
      "modes": [
        "car"
      ]
    },
    {
      "day": 4,
      "title": "Divjakė-Karavasta ir išvykimas",
      "urls": [
        "https://www.google.com/maps/dir/?api=1&origin=Qendra+e+Vizitor%C3%ABve+Divjak%C3%AB-Karavasta,+Divjak%C3%AB,+Albania&destination=Tirana+International+Airport+N%C3%ABn%C3%AB+Tereza,+Albania&travelmode=driving&waypoints=Plazhi+i+Divjak%C3%ABs,+Divjak%C3%AB,+Albania"
      ],
      "modes": [
        "car"
      ]
    }
  ],
  "logistics": {
    "legs": [
      {
        "day": 1,
        "from_stop": "Tiranos oro uostas (TIA)",
        "to_stop": "Hanna Apartment",
        "mode": "car",
        "distance_km": 19.0,
        "minutes": 31,
        "transit_kind": "",
        "transit": "",
        "road": "asfaltuotas kelias iš oro uosto į Tiraną, Rruga e Elbasanit rajoną, lygus reljefas",
        "icon": "🚗"
      },
      {
        "day": 2,
        "from_stop": "Krujos pilis ir Skenderbego muziejus bei Senasis bazaras",
        "to_stop": "Belšo ežeras (apžvalgos sustojimas)",
        "mode": "car",
        "distance_km": 91.0,
        "minutes": 92,
        "transit_kind": "",
        "transit": "",
        "road": "asfaltuotas kelias/greitkelis per Tiranos-Elbasano lygumą link Belšo",
        "icon": "🚗"
      },
      {
        "day": 2,
        "from_stop": "Belšo ežeras (apžvalgos sustojimas)",
        "to_stop": "Pietūs „Lili Homemade Food“",
        "mode": "car",
        "distance_km": 62.0,
        "minutes": 97,
        "transit_kind": "",
        "transit": "",
        "road": "asfaltuotas kelias per kalvas link Berato",
        "icon": "🚗"
      },
      {
        "day": 2,
        "from_stop": "Pietūs „Lili Homemade Food“",
        "to_stop": "Mangalemo senasis kvartalas",
        "mode": "walk",
        "distance_km": 0.1,
        "minutes": 1,
        "transit_kind": "",
        "transit": "",
        "road": "per senamiestį",
        "icon": "🚶"
      },
      {
        "day": 2,
        "from_stop": "Mangalemo senasis kvartalas",
        "to_stop": "Berato pilis (Kalaja e Beratit)",
        "mode": "walk",
        "distance_km": 1.0,
        "minutes": 14,
        "transit_kind": "",
        "transit": "",
        "road": "pėsčiųjų takas į kalvą prie pilies",
        "icon": "🚶"
      },
      {
        "day": 2,
        "from_stop": "Berato pilis (Kalaja e Beratit)",
        "to_stop": "Goricos tiltas ir kvartalas",
        "mode": "walk",
        "distance_km": 0.6,
        "minutes": 9,
        "transit_kind": "",
        "transit": "",
        "road": "pėsčiomis žemyn nuo pilies prie Goricos tilto",
        "icon": "🚶"
      },
      {
        "day": 2,
        "from_stop": "Goricos tiltas ir kvartalas",
        "to_stop": "DD Villa",
        "mode": "walk",
        "distance_km": 0.8,
        "minutes": 10,
        "transit_kind": "",
        "transit": "",
        "road": "pėsčiomis per tiltą atgal į Mangalemo kvartalą",
        "icon": "🚶"
      },
      {
        "day": 3,
        "from_stop": "Osumio kanjono apžvalgos aikštelė",
        "to_stop": "Pietūs Vlorės marina",
        "mode": "car",
        "distance_km": 153.0,
        "minutes": 171,
        "transit_kind": "",
        "transit": "",
        "road": "asfaltuotas kelias atgal pro Beratą ir toliau per Fierą (greitkelis) į Vlorę",
        "icon": "🚗"
      },
      {
        "day": 3,
        "from_stop": "Pietūs Vlorės marina",
        "to_stop": "Vlorės pakrantės promenada (Lungomare)",
        "mode": "walk",
        "distance_km": 0.0,
        "minutes": 1,
        "transit_kind": "",
        "transit": "",
        "road": "ta pati vieta Vlorės uoste",
        "icon": "🚶"
      },
      {
        "day": 3,
        "from_stop": "Vlorės pakrantės promenada (Lungomare)",
        "to_stop": "Hotel Liro – Adults Only",
        "mode": "car",
        "distance_km": 0.3,
        "minutes": 1,
        "transit_kind": "",
        "transit": "",
        "road": "ta pati vieta Vlorės pakrantėje",
        "icon": "🚗"
      },
      {
        "day": 4,
        "from_stop": "Karavastos lagūnos Lankytojų centras ir apžvalgos bokštas",
        "to_stop": "Pietūs Divjakės paplūdimyje",
        "mode":
… (sutrumpinta, iš viso 103650 simbolių)
```

Reply with the complete HTML document itself as your entire answer, starting with <!DOCTYPE html>. Do not write files, and do not describe or summarise what you did.

</details>

<details><summary><b>Atsakymas</b></summary>

HTML puslapis sugeneruotas (72 KB).

</details>

### 8. Puslapis — 10:44:40 ✅

- **Modelis:** `claude-sonnet-5` · **Vykdė:** Native Claude (claude -p) · **Trukmė:** 364.8 s
- **Sistemos promptas:** `prompts/page_designer.md`

<details><summary><b>Užklausa</b></summary>

You are updating an already published trip page, not designing a new one. Below are the current page and the current data. Apply the listed changes and make every part of the page match the current data, but keep the design -- colors, layout, CSS, JS, section order -- and all wording that isn't affected exactly as it is. Keep the <!-- PACKING_LIST --> and <!-- TRIP_MAP --> lines where they are.

Changes:
Fix these review findings:
- Sofra e Ariut (Kur pavalgyti, Ką paragauti čia): show "Tavė kosi (ėriena su jogurto padažu)"
- Snack Bar Derexhiku (Kur pavalgyti, Ką paragauti čia): show "Vištienos file su garnyru"
- Lili Homemade Food (Kur pavalgyti, Ką paragauti čia): show "Fërgesë (paprikų ir varškės troškinys)"
- Restorant Pelikan (Kur pavalgyti, Ką paragauti čia): show "Ungurys (lagūnos specialitetas)"
- Missing traveller tip (show it word for word): Prie Osumo kanjono apžvalgos aikštelės Google Maps kartais siūlo trumpesnį kelią toliau per Pėrmetą -- tai žvyrkelis, netinkamas standartiniam automobiliui. Važiuokite tik iki apžvalgos aikštelės prie Čorovodės ir grįžkite tuo pačiu asfaltuotu keliu per Beratą ir toliau per Fierą į Vlorę.
- Missing traveller tip (show it word for word): Berato senamiestyje Mangalemo ir Goricos kvartalus geriausia apžiūrėti pėsčiomis -- tiltas per Osumo upę skirtas tik pėstiesiems.
- Missing traveller tip (show it word for word): Karavastos-Divjakės nacionaliniame parke automobilį palikite Lankytojų centro aikštelėje -- čia veda geras asfaltuotas kelias ir čia pat yra apžvalgos bokštas. Jei norite pasiekti giliau lagūnoje esantį bokštą, paskutinius 1-2 km nueikite pėsčiomis, nes tas kelias po lietaus būna dumblinas.
- Missing traveller tip (show it word for word): Antrą ir trečią kelionės dieną vairavimo laikas artėja prie 4 valandų -- neplanuokite papildomų stotelių, kad liktų laiko ramiai pasigrožėti Krujë, Beratu ir kanjonu.
- Missing traveller tip (show it word for word): Paskutinę dieną grįžus į Tiranos oro uostą iki skrydžio liks apie 2 val. 40-50 min -- automobilio grąžinimui ir registracijai laiko turėtų pakakti.
Updated data: Puslapis

**Current data:**

```json
{
  "language": "lt",
  "research": "# Research summary: Albania, TIA to TIA, 30 Oct – 2 Nov 2026 (4 people, nature focus)\n\n**Coverage:** Reddit is blocked for the crawler, and TripAdvisor forum threads returned 403. So I have no r/travel or r/albania posts and only TripAdvisor search snippets. Everything else comes from Wikivoyage, blogs and operator sites. Dates are the page's own date where visible, otherwise \"undated\". I did not verify any drive times myself.\n\n## 1. Candidate stops\n\n| # | Stop | Why recommended | Source (date) |\n|---|---|---|---|\n| 1 | **Berat** (UNESCO) | Ottoman old town, uncrowded off-season. About 2–3 h from Tirana. | [Wikivoyage Albania](https://en.wikivoyage.org/wiki/Albania) (undated); [TripAdvisor thread snippet](https://www.tripadvisor.com/ShowTopic-g294445-i4583-k6457473-Tirana_Berat_Gjirokastra_Saranda-Albania.html) (undated) |\n| 2 | **Osumi Canyon and Bogovë waterfall** (from Berat) | Best nature stop within reach of Berat. The road from Berat to Bogova village is paved (about 1 h), and a regular car is fine. The canyon viewpoint is reachable in a normal car, and the author parked at the top. | [Wander with Laura](https://wanderwithlaura.com/how-to-get-to-bogove-waterfall-and-osum-canyon/) (published Aug 2022, updated 10 Jan 2026) |\n| 3 | **Divjakë-Karavasta lagoon** (pelicans, flamingos) | Autumn is a best season for birds. About 1h40 from Tirana, 30 min north of Fier and Apollonia. | [Nomads Travel Guide](https://www.nomads-travel-guide.com/places/divjake-karavasta-national-park/) (undated); [Birdingplaces](https://www.birdingplaces.eu/en/birdingplaces/albania/divjake-karavasta-national-park) (undated) |\n| 4 | **Gjirokastër** (UNESCO) | Stone town, \"empty of summer crowds\" in November. About 3h20 from Tirana on Google, and about 4 h realistically. This is at your daily driving limit. | [thingstodoinalbania](https://thingstodoinalbania.com/month/november/) (undated); [TIC Rent Car](https://ticrentcar.com/tirana-to-gjirokastra/) (undated) |\n| 5 | **Blue Eye (Syri i Kaltër)** | Spring-fed pool, open year-round, 07:00–19:00, 50 LEK entry. It is 22 km from Sarandë and 35 km from Gjirokastër. The last 2 km of road are unpaved but \"doable\", followed by a 2 km walk. | [Laure Wanders](https://www.laurewanders.com/blue-eye-albania/) (29 Aug 2026) |\n| 6 | **Llogara Pass and Dhermi coast** | The old pass road is still open and paved. The new tunnel costs 250 LEK (from 16 Sep 2025) and saves about 30 min. Snow and ice risk is Dec–Feb, so fine for early November, though fog and rain are possible. | [Explorer Tom](https://explorertom.com/en/llogara-pass-albania/) (11 Jun 2026) |\n| 7 | **Shkodër, Rozafa Castle, Lake Shkodra** | Easy northern option, about 1h47 from Tirana on the A1. | [Travelmath / ViaMichelin results](https://www.travelmath.com/driving-time/from/Shkoder,+Albania/to/Tirana,+Albania) (undated) |\n| 8 | **Komani Lake ferry** (Koman to Fierza) | The most scenic northern option. See the caveats in section 2. | [Ferry operator](https://komanilakeferry.com/timetables-and-prices/) (undated) |\n| 9 | **Bënja thermal baths / Përmet / Vjosa valley** | About 1h15 north of Gjirokastër, on the paved main road. Year-round, and best in cold weather. | [Vjosa Rafting guide](https://vjosarafting.com/benja-thermal-baths-permet/) and [Himara.net](https://himara.net/blog/benja-thermal-baths-destination-guide) (both undated) |\n| 10 | Pogradec / Lake Ohrid (Albanian side) | Low confidence. It is 2.5–3 h from Tirana. I found nothing on Korçë or Voskopojë in autumn. | [Explorer Tom](https://explorertom.com/en/lake-ohrid-albanian-side/) (undated) |\n\n**Overrated or skippable:**\n- **Ksamil and the Riviera beach towns:** described as overrun and overpriced in season. In late October the coast is mostly shuttered, with Ksamil and Dhermi venues closed and \"finding restaurants between Vlorë and Sarandë is challenging\" ([thingstodoinalbania](https://thingstodoinalbania.com/month/november/), undated). Himarë is \"empty by end of October\" per a TripAdvisor snippet (undated).\n- **Bovilla lake and Dajti:** the Dajti cable car is closed on Tuesdays. Your dates fall on Fri–Mon, so this doesn't matter ([TripAdvisor FAQ](https://www.tripadvisor.com/FAQ-g294445-d4573567-Dajti_Ekspres_Cable_Car.html)).\n- **Not found:** I found no sourced opinion on Bunk'Art, Blloku or Durrës. Treat those as unresearched.\n\n## 2. Road and logistics warnings\n\n**Roads to exclude for a standard rental car** (all from [Localrent \"Prohibited routes\"](https://www.localrent.com/en/journal/albania/articles/prohibited-routes/), undated with 2023 file metadata):\n- **SH74 Berat–Përmet:** \"narrow unpaved mountain road covered with small stones\". This is the one your earlier projects flagged.\n- **Berat–Përmet through Osumi Canyon:** unpaved with potholes and large puddles.\n- **Memaliaj–Berat (Martallozi):** unpaved.\n- **Tirana–Qafë-Shtamë via Lake Bovilla:** unpaved serpentine. A regular car can reach the dam, but not beyond ([Localrent](https://www.localrent.com/en/journal/albania/articles/prohibited-routes/) and search results, undated).\n- **Krujë–Burreli:** \"terrible state of disrepair\".\n- **Theth–Valbona:** already excluded by you.\n- **Beach access roads off SH8:** unpaved.\n\nOsumi Canyon is fine only when approached from Berat, so don't continue from it onward to Përmet.\n\n**Komani ferry caveats:**\n- **Season end is unclear.** The operator says 15 Apr to 5 Nov, so 30 Oct – 2 Nov is inside the season. A search snippet from another page said 2 Nov, which I could not verify. Confirm directly with the operator.\n- **Timetable:** Koman 09:00 to Fierza (about 2.5 h), and Fierza 13:00 back to Koman ([operator](https://komanilakeferry.com/timetables-and-prices/); [Explorer Tom](https://explorertom.com/en/koman-lake-ferry-guide/), 2026).\n- **A same-day round trip returns after dark.** By my own arithmetic, the boat is back at Koman about 15:30, plus at least 2 h to Shkodër gives about 17:30, after sunset. This is my calculation, not from a source. It suggests sleeping near Shkodër or Koman.\n- **The car does not need to cross.** The ferry is a dead end, so you would leave the car at Koman and go as foot passengers. That avoids the vehicle-booking problem below.\n- **Car on the ferry:** online pre-booking is essential, priced at €7/m² ([Explorer Tom](https://explorertom.com/en/koman-lake-ferry-guide/)). One traveller in Nov 2025 had to upgrade to an SUV because of rental-company restrictions ([Perchance to Roam](https://perchancetoroam.com/2025/11/01/a-complete-guide-to-taking-albanias-komani-lake-ferry-with-or-without-a-car/), 1 Nov 2025). Check the rental terms.\n- **Road Shkodër to Koman (SH25):** about 60 km and about 2 h, with a narrow one-lane tunnel near the terminal ([Explorer Tom](https://explorertom.com/en/koman-lake-ferry-guide/)). It was in poor shape in Nov 2025, with the last 10 km \"completely ripped open\" ([Perchance to Roam](https://perchancetoroam.com/2025/11/01/a-complete-guide-to-taking-albanias-komani-lake-ferry-with-or-without-a-car/)). [inAlbania](https://www.inalbania.info/koman-road-transformed-to-boost-tourism-in-northern-albania/) (15 Sep 2026) reports the Vau i Dejës–Koman reconstruction as completed. It gives no surface or tunnel details, and the government page I tried to fetch was empty. I'd call this likely improved but not confirmed.\n\n**General driving:**\n- **Time estimates:** Google Maps underestimates mountain roads. Add 25% (\"2 h shows, allow 2.5\", [Endless Travellers](https://theendlesstravellers.com/driving-in-albania/), updated 22 Feb 2026). Tirana to Theth shows 3.5 h but takes about 5 h ([Along Dusty Roads](https://www.alongdustyroads.com/posts/driving-in-albania-car-hire), updated Jun 2025).\n- **Night driving:** avoid it. Village roads are unlit, with livestock and pedestrians (same Along Dusty Roads and Wikivoyage sources). You land at 20:30 on Friday, so keep the first night's drive short, and check that the rental desk is open at that hour (not researched).\n- **Flash floods:** flash flooding is possible in the Vjosa and Osum valleys after heavy rain, and the Lengarica canyon is inaccessible after heavy rain ([thingstodoinalbania](https://thingstodoinalbania.com/month/november/), undated, single source).\n- **Tolls:** the Llogara Tunnel and the A1 to Kosovo are tolled ([Endless Travellers](https://theendlesstravellers.com/driving-in-albania/)).\n- **Rules:** police speed checks are frequent, alcohol limit is 0.01% ([Wikivoyage](https://en.wikivoyage.org/wiki/Albania)).\n\n## 3. Seasonal notes (30 Oct – 2 Nov)\n\n- **Rain:** November is the rainiest month, about 12 rain days and 180 mm, with roughly 12–15 °C average temperatures ([Climates to Travel](https://www.climatestotravel.com/weatherbymonth/albania/november) and similar, undated).\n- **Unreliable figure:** thingstodoinalbania claims 25 °C highs and 2 in of rain in November. That contradicts every other source, so don't use its numbers.\n- **Snow:** snow is possible above 1,500 m before mid-November. Theth/Valbona is snow-covered ([thingstodoinalbania](https://thingstodoinalbania.com/month/november/), undated, single source).\n- **Fog:** persistent morning fog on Lake Shkodra and in the Korçë basin (same source).\n- **Lake Shkodra boats:** schedules shrink to weekends only (same source, unconfirmed). Your Sat and Sun fall on weekends.\n- **Daylight:** sources give sunset of 16:45–17:25 (Wanderlog and others, undated). Their sunrise figure of 05:46 is implausible, so I don't trust them. My own rough estimate for Tirana (CET, after clocks change on 25 Oct) is sunset about 16:30–16:40. That is earlier than your 17:00–17:30 assumption. The Weather/Season Agent should check this with Open-Meteo.\n- **Calendar:** 30 Oct is a Friday and 2 Nov a Monday, so the trip has two full days (Sat, Sun) plus the Friday-night arrival and the Monday return. Monday needs the car back at TIA by about 17:00.\n\n## 4. Route shapes for the Logistics Validator (not validated)\n\n- **Central/south:** Fri night near Tirana or Durrës. Sat via Karavasta and Apollonia to Berat. Sun via Osumi and Bogova to Gjirokastër. Mon Gjirokastër to TIA at about 3.5–4 h. The last leg is the tightest, needing an early start. Blue Eye and Përmet do not fit without dropping something.\n- **North (easier):** Fri night Tirana. Sat Shkodër, Rozafa and the lake. Sun Komani ferry from a Shkodër or Koman base. Mon return via the A1 (about 1h47).\n\nBoth fit the 3.5–4 h limit only if the Validator confirms the legs. The central/south option depends on avoiding SH74 and the Berat–Përmet canyon road.\n\n## 5. Gaps to close\n\n- Direct confirmation of the Komani ferry season end and whether foot passengers can get a seat in early November.\n- Rental terms: a 4-person vehicle, ferry carriage, and the airport desk's opening hours after a 20:30 landing.\n- Osumi Canyon water levels and access in early November. The one detailed source visited in summer.\n- Korçë and Voskopojë autumn conditions, if you want a southeastern alternative.",
  "accommodation": "## Nakvynės vietos (tik užsakytos)\n\nKeliautojas jau užsakė ir patvirtino konkrečius nakvynės objektus per booking.com nuorodas. Žemiau — tik šios užsakytos vietos, be papildomų alternatyvų.\n\n### 1. Tirana (penktadienis, 2026-10-30 → šeštadienis, 2026-10-31)\n\n**✅ Užsakyta — Hanna Apartment** — **51 €/naktį**\n- Rruga e Elbasanit, Tirana. Įvertinimas 9.0/10 (186 atsiliepimai).\n- Kondicionierius, nemokamas WiFi. Tinka 4 žmonėms (butas).\n- Nuoroda: https://www.booking.com/hotel/al/apartament-tirana8.lt.html\n\n### 2. Beratas (šeštadienis, 2026-10-31 → sekmadienis, 2026-11-01)\n\n**✅ Užsakyta — DD Villa** — **61 €/naktį**\n- Rruga Antipatrea, Beratas. Įvertinimas 8.8/10 (667 atsiliepimai).\n- Sodas, baras, bendra svetainė, miesto vaizdas, pusryčiai (bufetas/à la carte), privatus parkavimas (už papildomą mokestį), restoranas vietoje.\n- Nuoroda: https://www.booking.com/hotel/al/dd-villa.lt.html\n\n### 3. Vlorė / Radhimė (sekmadienis, 2026-11-01 → pirmadienis, 2026-11-02)\n\n**✅ Užsakyta — Hotel Liro – Adults Only** — **117 €/naktį**\n- Aleksandër Moisiu Street, Vlorė. Įvertinimas 8.6/10 (1295 atsiliepimai).\n- Privatus paplūdimio ruožas, lauko baseinas, nemokamas parkavimas, restoranas/baras, pusryčiai, vaizdas į jūrą nuo balkono. Autobusų stotelė priešais viešbutį.\n- Nuoroda: https://www.booking.com/hotel/al/liro.lt.html\n- ⚠️ Pastaba: \"Adults Only\" — jei grupėje yra vaikų, šią vietą reikėtų pakeisti.\n\n**Biudžeto suma nakvynėms (3 naktys, visai grupei):** 51 + 61 + 117 = **229 €**",
  "booking_search": [
    {
      "city": "Tirana",
      "name": "Hanna Apartment",
      "checkin": "2026-10-30",
      "checkout": "2026-10-31",
      "nights": 1,
      "price_per_night_eur": 51,
      "url": "https://www.booking.com/searchresults.html?ss=Hanna+Apartment%2C+Tirana&checkin=2026-10-30&checkout=2026-10-31&group_adults=4&group_children=0&no_rooms=1"
    },
    {
      "city": "Berat",
      "name": "DD Villa",
      "checkin": "2026-10-31",
      "checkout": "2026-11-01",
      "nights": 1,
      "price_per_night_eur": 61,
      "url": "https://www.booking.com/searchresults.html?ss=DD+Villa%2C+Berat&checkin=2026-10-31&checkout=2026-11-01&group_adults=4&group_children=0&no_rooms=1"
    },
    {
      "city": "Vlorë",
      "name": "Hotel Liro - Adults Only",
      "checkin": "2026-11-01",
      "checkout": "2026-11-02",
      "nights": 1,
      "price_per_night_eur": 117,
      "url": "https://www.booking.com/searchresults.html?ss=Hotel+Liro+-+Adults+Only%2C+Vlor%C3%AB&checkin=2026-11-01&checkout=2026-11-02&group_adults=4&group_children=0&no_rooms=1"
    }
  ],
  "stays": [
    {
      "url": "https://www.booking.com/hotel/al/apartament-tirana8.lt.html",
      "name": "Hanna Apartment",
      "address": "Rruga e Elbasanit, 1035 Tirana, Albanija, 1035, Rruga e Elbasanit, Albanija",
      "description": "Hanna Apartment is located in Tirana. This apartment provides air-conditioned accommodation with free WiFi.",
      "full_description": null,
      "facilities": null,
      "rating": 9.0,
      "rating_scale": 10,
      "review_count": 186,
      "photo_urls": [
        "https://cf.bstatic.com/xdata/images/hotel/max1024x768/633887464.jpg?k=b976c4febe171b551f477e9eee870608b6dc963117d876c793f0d9f4e74a10c1&o=&hp=1",
        "https://cf.bstatic.com/xdata/images/hotel/max1024x768/633887550.jpg?k=694dc1002849285d2f750017340c1edd34a96dd80c7fbc5b6481ab43eadda7c0&o=&hp=1",
        "https://cf.bstatic.com/xdata/images/hotel/max1024x768/633887291.jpg?k=4963ffaa4c10e0fd9f47b51e58b930fc53eff67747c24a914957854aecfefbc0&o=&hp=1",
        "https://cf.bstatic.com/xdata/images/hotel/max1024x768/633889677.jpg?k=5da3b33dfa81e6240d74fe7d36bf94844df25d861a8cfb0f6e6d273f1eb9459a&o=&hp=1",
        "https://cf.bstatic.com/xdata/images/hotel/max1024x768/651343123.jpg?k=5441b1e29d0d9b0725ae1274688a078b2e764fba7c641900e5a8cc9a87c5bc84&o=&hp=1"
      ],
      "photos": [
        {
          "stop_name": "Hanna Apartment",
          "local_path": "images/stay-hanna-apartment-1.jpg",
          "commons_filename": "",
          "license": "© apgyvendinimo įstaiga / Booking.com",
          "author": null,
          "source_url": "https://www.booking.com/hotel/al/apartament-tirana8.lt.html",
          "size_bytes": 110275
        },
        {
          "stop_name": "Hanna Apartment",
          "local_path": "images/stay-hanna-apartment-2.jpg",
          "commons_filename": "",
          "license": "© apgyvendinimo įstaiga / Booking.com",
          "author": null,
          "source_url": "https://www.booking.com/hotel/al/apartament-tirana8.lt.html",
          "size_bytes": 32003
        },
        {
          "stop_name": "Hanna Apartment",
          "local_path": "images/stay-hanna-apartment-3.jpg",
          "commons_filename": "",
          "license": "© apgyvendinimo įstaiga / Booking.com",
          "author": null,
          "source_url": "https://www.booking.com/hotel/al/apartament-tirana8.lt.html",
          "size_bytes": 55703
        },
        {
          "stop_name": "Hanna Apartment",
          "local_path": "images/stay-hanna-apartment-4.jpg",
          "commons_filename": "",
          "license": "© apgyvendinimo įstaiga / Booking.com",
          "author": null,
          "source_url": "https://www.booking.com/hotel/al/apartament-tirana8.lt.html",
          "size_bytes": 53502
        },
        {
          "stop_name": "Hanna Apartment",
          "local_path": "images/stay-hanna-apartment-5.jpg",
          "commons_filename": "",
          "license": "© apgyvendinimo įstaiga / Booking.com",
          "author": null,
          "source_url": "https://www.booking.com/hotel/al/apartament-tirana8.lt.html",
          "size_bytes": 54202
        }
      ]
    },
    {
      "url": "https://www.booking.com/hotel/al/dd-villa.lt.html",
      "name": "DD Villa",
      "address": "Rruga Antipatrea, 5001 Beratis, Albanija, 5001, Rruga Antipatrea, Albanija",
      "description": "Situated in Berat, DD Villa features a garden, a bar and a shared lounge. The property has city views. Private parking can be arranged at an extra charge.",
      "full_description": [
        "Situated in Berat, DD Villa features a garden, a bar and a shared lounge. The property has city views. Private parking can be arranged at an extra charge. The bed and breakfast will provide guests with air-conditioned units offering a wardrobe, a kettle, a dishwasher, a microwave, a safety deposit box, a flat-screen TV and a private bathroom with a bidet. Free WiFi is accessible to all guests, while certain rooms are equipped with a terrace. At the bed and breakfast, every unit is equipped with bed linen and towels. A buffet, à la carte or continental breakfast is available at the property. Guests are welcome to eat in the on-site family-friendly restaurant, which is open for dinner, lunch, brunch and high tea. Sightseeing tours are available around the property. Both a bicycle rental service and a car rental service are available at the bed and breakfast, while cycling can be enjoyed nearby. Tirana International Mother Teresa Airport is 120 km from the property, and the property offers a paid airport shuttle service."
      ],
      "facilities": [
        "Populiariausi patogumai",
        "Privati automobilių stovėjimo aikštelė",
        "Spartus nemokamas belaidis internetas (101 Mbps)",
        "Pervežimas iš / į oro uostą",
        "Numeriai nerūkantiems",
        "Numeriai šeimai",
        "Aptarnavimas numeriuose",
        "Restoranas",
        "Baras",
        "Nuostabūs pusryčiai"
      ],
      "rating": 8.8,
      "rating_scale": 10,
      "review_count": 667,
      "photo_urls": [
        "https://cf.bstatic.com/xdata/images/hotel/max1024x768/529582807.jpg?k=731fe174d8d2b7402280e7c8008fdd355a874d76e0b7f03f1f516ad3c92ccd4f&o=&hp=1",
        "https://cf.bstatic.com/xdata/images/hotel/max1024x768/921271115.jpg?k=714680e569beb3f835a5ab5f15daaf4460dda2cd2509890599543048e17af49a&o=&hp=1",
        "https://cf.bstatic.com/xdata/images/hotel/max1024x768/529582816.jpg?k=8c6581a00d3c484f9e62bbaa3ba21bf08b13e50ccda4cf1e32c52876fb08a13d&o=&hp=1",
        "https://cf.bstatic.com/xdata/images/hotel/max1024x768/544036358.jpg?k=03e5cee7c142331675268001c541cbe0e4cb64ba67f8d850dc1cf05be6ee1024&o=&hp=1",
        "https://cf.bstatic.com/xdata/images/hotel/max1024x768/529582821.jpg?k=58830e6a252b81f2a06faccae174fad12a474f063ed8162b382a1ac3626b93d9&o=&hp=1"
      ],
      "photos": [
        {
          "stop_name": "DD Villa",
          "local_path": "images/stay-dd-villa-1.jpg",
          "commons_filename": "",
          "license": "© apgyvendinimo įstaiga / Booking.com",
          "author": null,
          "source_url": "https://www.booking.com/hotel/al/dd-villa.lt.html",
          "size_bytes": 154626
        },
        {
          "stop_name": "DD Villa",
          "local_path": "images/stay-dd-villa-2.jpg",
          "commons_filename": "",
          "license": "© apgyvendinimo įstaiga / Booking.com",
          "author": null,
          "source_url": "https://www.booking.com/hotel/al/dd-villa.lt.html",
          "size_bytes": 69651
        },
        {
          "stop_name": "DD Villa",
          "local_path": "images/stay-dd-villa-3.jpg",
          "commons_filename": "",
          "license": "© apgyvendinimo įstaiga / Booking.com",
          "author": null,
          "source_url": "https://www.booking.com/hotel/al/dd-villa.lt.html",
          "size_bytes": 99758
        },
        {
          "stop_name": "DD Villa",
          "local_path": "images/stay-dd-villa-4.jpg",
          "commons_filename": "",
          "license": "© apgyvendinimo įstaiga / Booking.com",
          "author": null,
          "source_url": "https://www.booking.com/hotel/al/dd-villa.lt.html",
          "size_bytes": 99712
        },
        {
          "stop_name": "DD Villa",
          "local_path": "images/stay-dd-villa-5.jpg",
          "commons_filename": "",
          "license": "© apgyvendinimo įstaiga / Booking.com",
          "author": null,
          "source_url": "https://www.booking.com/hotel/al/dd-villa.lt.html",
          "size_bytes": 129326
        }
      ]
    },
    {
      "url": "https://www.booking.com/hotel/al/liro.lt.html",
      "name": "Hotel Liro - Adults Only",
      "address": "Aleksandër Moisiu Street, 9405 Vliorė, Albanija, 9405, Aleksandër Moisiu Street, Albanija",
      "description": "Located in Vlorë, Hotel Liro - Adults Only offers a private beach area with free-to-use sun loungers and parasols.",
      "full_description": [
        "Located in Vlorë, Hotel Liro - Adults Only offers a private beach area with free-to-use sun loungers and parasols. The on-site bar and restaurant offers a spacious terrace where guests can enjoy the Mediterranean dishes it serves. Free WiFi access is available throughout the property. All the rooms are air-conditioned and come with a furnished balcony overlooking the sea. Each room is equipped with satellite TV, a minibar and a safe. Featuring a shower, private bathrooms also come with a hairdryer and free toiletries. Hotel Liro - Adults Only offers an array of activities can be enjoyed on site or in the surroundings, including windsurfing. The cenre of Vlorë and the scenic outlook of Kuzum Baba can be found within a 6-km radius. The Archaeological Park of Oricum is 10 km from Liro Hotel. Llogara National Park is 25 km away. The local bus stop is right in front of the hotel. Tirana Airport is 150 km away. The property offers free parking."
      ],
      "facilities": [
        "Populiariausi patogumai",
        "Lauko baseinas",
        "Nemokama vieta automobiliui",
        "Šalia paplūdimio",
        "Nemokamas belaidis internetas",
        "Numeriai šeimai",
        "Restoranas",
        "Numeriai nerūkantiems",
        "Baras",
        "Privati paplūdimio dalis",
        "Nuostabūs pusryčiai"
      ],
      "rating": 8.6,
      "rating_scale": 10,
      "review_count": 1295,
      "photo_urls": [
        "https://cf.bstatic.com/xdata/images/hotel/max1024x768/506995294.jpg?k=23925d61528b241c35e7b43446d3f11a9faa202b08e9903c82a6e3cb2afa43d7&o=&hp=1",
        "https://cf.bstatic.com/xdata/images/hotel/max1024x768/506995475.jpg?k=8b2bd840a2ed21d4d6da7442afc978dd5073fc1eb1d9a567413fdab748546eac&o=&hp=1",
        "https://cf.bstatic.com/xdata/images/hotel/max1024x768/556057394.jpg?k=575cc81ebc625197b6b6c6af18c2ec9a6eda54fa3ed14e29ecef4935b13b27a6&o=&hp=1",
        "https://cf.bstatic.com/xdata/images/hotel/max1024x768/506995518.jpg?k=2db992e93cda20eb611af0c65c6d59f388efc2150e468dfbfae8e8e3fbb3b665&o=&hp=1",
        "https://cf.bstatic.com/xdata/images/hotel/max1024x768/506995661.jpg?k=d3755c0ed1215710923e75d5050056023d41ecd92820d69af21aa384123992dd&o=&hp=1"
      ],
      "photos": [
        {
          "stop_name": "Hotel Liro - Adults Only",
          "local_path": "images/stay-hotel-liro-adults-only-1.jpg",
          "commons_filename": "",
          "license": "© apgyvendinimo įstaiga / Booking.com",
          "author": null,
          "source_url": "https://www.booking.com/hotel/al/liro.lt.html",
          "size_bytes": 125824
        },
        {
          "stop_name": "Hotel Liro - Adults Only",
          "local_path": "images/stay-hotel-liro-adults-only-2.jpg",
          "commons_filename": "",
          "license": "© apgyvendinimo įstaiga / Booking.com",
          "author": null,
          "source_url": "https://www.booking.com/hotel/al/liro.lt.html",
          "size_bytes": 238091
        },
        {
          "stop_name": "Hotel Liro - Adults Only",
          "local_path": "images/stay-hotel-liro-adults-only-3.jpg",
          "commons_filename": "",
          "license": "© apgyvendinimo įstaiga / Booking.com",
          "author": null,
          "source_url": "https://www.booking.com/hotel/al/liro.lt.html",
          "size_bytes": 133915
        },
        {
          "stop_name": "Hotel Liro - Adults Only",
          "local_path": "images/stay-hotel-liro-adults-only-4.jpg",
          "commons_filename": "",
          "license": "© apgyvendinimo įstaiga / Booking.com",
          "author": null,
          "source_url": "https://www.booking.com/hotel/al/liro.lt.html",
          "size_bytes": 211665
        },
        {
          "stop_name": "Hotel Liro - Adults Only",
          "local_path": "images/stay-hotel-liro-adults-only-5.jpg",
          "commons_filename": "",
          "license": "© apgyvendinimo įstaiga / Booking.com",
          "author": null,
          "source_url": "https://www.booking.com/hotel/al/liro.lt.html",
          "size_bytes": 64880
        }
      ]
    }
  ],
  "itinerary": "{\"days\":[{\"number\":1,\"title\":\"Atvykimas į Tiraną\",\"stops\":[{\"name\":\"Tiranos oro uostas (TIA)\",\"lat\":41.4147,\"lon\":19.7206,\"arrive\":\"20:30\",\"depart\":\"21:00\",\"maps_query\":\"Tirana International Airport Nënë Tereza, Albania\",\"google_maps_url\":\"https://www.google.com/maps/search/?api=1&query=Tirana%20International%20Airport%20N%C3%ABn%C3%AB%20Tereza%2C%20Albania\",\"notes\":\"Skrydis iš Varšuvos nusileidžia 20:30. Automobilio nuomos (VW Tiguan ar panašus visureigis, tinka 4 žmonėms ir bagažui, su Papildomo vairuotojo ir pilnos apsaugos draudimu) atsiėmimas 21:00. Tą pačią vietą reikės grąžinti automobilį lapkričio 2 d. iki 17:00.\",\"arrive_by\":\"car\",\"transit\":\"\"},{\"name\":\"Hanna Apartment\",\"lat\":41.3192,\"lon\":19.8294,\"arrive\":\"21:20\",\"depart\":\"21:20\",\"maps_query\":\"Apartament Tirana8, Rruga e Elbasanit, Tirana, Albania\",\"google_maps_url\":\"https://www.google.com/maps/search/?api=1&query=Apartament%20Tirana8%2C%20Rruga%20e%20Elbasanit%2C%20Tirana%2C%20Albania\",\"notes\":\"Pirma nakvynė – butas Rruga e Elbasanit, kondicionierius, nemokamas WiFi, tinka 4 žmonėms. Kelias nuo oro uosto apie 20 min, vėlai vakare eismas ramus.\",\"arrive_by\":\"car\",\"transit\":\"\"}],\"driving_minutes\":20,\"overnight_city\":\"Tirana\"},{\"number\":2,\"title\":\"Krujė, Belšo ežeras ir Beratas\",\"stops\":[{\"name\":\"Krujos pilis ir Skenderbego muziejus bei Senasis bazaras\",\"lat\":41.5086,\"lon\":19.7919,\"arrive\":\"09:45\",\"depart\":\"10:30\",\"maps_query\":\"Kalaja e Krujës, Krujë, Albania\",\"google_maps_url\":\"https://www.google.com/maps/search/?api=1&query=Kalaja%20e%20Kruj%C3%ABs%2C%20Kruj%C3%AB%2C%20Albania\",\"notes\":\"Skenderbego muziejus pilies viduje, bilietas apie 200 lekų (~2 €). Žiemos darbo laikas apytiksliai 09:00–16:00 – darbo laiką verta pasitikrinti. Prie pilies – senasis bazaras su amatininkų dirbiniais ir suvenyrais.\",\"arrive_by\":\"car\",\"transit\":\"\"},{\"name\":\"Belšo ežeras (apžvalgos sustojimas)\",\"lat\":41.0931,\"lon\":19.8828,\"arrive\":\"12:02\",\"depart\":\"12:17\",\"maps_query\":\"Liqeni i Belshit, Belsh, Albania\",\"google_maps_url\":\"https://www.google.com/maps/search/?api=1&query=Liqeni%20i%20Belshit%2C%20Belsh%2C%20Albania\",\"notes\":\"Trumpas sustojimas pakeliui – gražus Dumrės plokščiakalnio ir ežerų vaizdas, proga kavai ir nuotraukai.\",\"arrive_by\":\"car\",\"transit\":\"\"},{\"name\":\"Pietūs „Lili Homemade Food“\",\"lat\":40.7064,\"lon\":19.9513,\"arrive\":\"13:54\",\"depart\":\"14:55\",\"maps_query\":\"Lili Homemade Food, Berat, Albania\",\"google_maps_url\":\"https://www.google.com/maps/search/?api=1&query=Lili%20Homemade%20Food%2C%20Berat%2C%20Albania\",\"notes\":\"Populiarus namų virtuvės restoranas Mangalemo kvartale, vietiniai patiekalai.\",\"arrive_by\":\"car\",\"transit\":\"\"},{\"name\":\"Mangalemo senasis kvartalas\",\"lat\":40.706,\"lon\":19.951,\"arrive\":\"14:55\",\"depart\":\"15:09\",\"maps_query\":\"Mangalem Quarter, Berat, Albania\",\"google_maps_url\":\"https://www.google.com/maps/search/?api=1&query=Mangalem%20Quarter%2C%20Berat%2C%20Albania\",\"notes\":\"Pasivaikščiojimas osmanų laikų gatvelėmis su garsiaisiais „tūkstančio langų“ namais.\",\"arrive_by\":\"walk\",\"transit\":\"\"},{\"name\":\"Berato pilis (Kalaja e Beratit)\",\"lat\":40.7014,\"lon\":19.9447,\"arrive\":\"15:29\",\"depart\":\"16:13\",\"maps_query\":\"Kalaja e Beratit, Berat, Albania\",\"google_maps_url\":\"https://www.google.com/maps/search/?api=1&query=Kalaja%20e%20Beratit%2C%20Berat%2C%20Albania\",\"notes\":\"Gyvenama pilis su bizantiškomis bažnyčiomis. Įėjimas į teritoriją laisvas, Onufrijaus muziejuje bilietas apie 200 lekų – darbo laiką verta pasitikrinti.\",\"arrive_by\":\"walk\",\"transit\":\"\"},{\"name\":\"Goricos tiltas ir kvartalas\",\"lat\":40.7021,\"lon\":19.9497,\"arrive\":\"16:38\",\"depart\":\"17:08\",\"maps_query\":\"Ura e Goricës, Berat, Albania\",\"google_maps_url\":\"https://www.google.com/maps/search/?api=1&query=Ura%20e%20Goric%C3%ABs%2C%20Berat%2C%20Albania\",\"notes\":\"Osmanų laikų akmeninis tiltas per Osumo upę – ypač gražus prieblandoje, puikus vaizdas į Mangalemą.\",\"arrive_by\":\"walk\",\"transit\":\"\"},{\"name\":\"DD Villa\",\"lat\":40.7057,\"lon\":19.952,\"arrive\":\"17:23\",\"depart\":\"17:23\",\"maps_query\":\"DD Villa, Rruga Antipatrea, Berat, Albania\",\"google_maps_url\":\"https://www.google.com/maps/search/?api=1&query=DD%20Villa%2C%20Rruga%20Antipatrea%2C%20Berat%2C%20Albania\",\"notes\":\"Nakvynė Berate – sodas, baras, pusryčiai, privatus parkavimas už papildomą mokestį.\",\"arrive_by\":\"walk\",\"transit\":\"\"}],\"driving_minutes\":180,\"overnight_city\":\"Berat\"},{\"number\":3,\"title\":\"Osumio kanjonas ir Vlorės pakrantė\",\"stops\":[{\"name\":\"Osumio kanjono apžvalgos aikštelė\",\"lat\":40.5044,\"lon\":20.227,\"arrive\":\"10:15\",\"depart\":\"11:00\",\"maps_query\":\"Kanioni i Osumit, Çorovodë, Albania\",\"google_maps_url\":\"https://www.google.com/maps/search/?api=1&query=Kanioni%20i%20Osumit%2C%20%C3%87orovod%C3%AB%2C%20Albania\",\"notes\":\"Vienas gražiausių gamtos vaizdų kelyje – kanjono apžvalgos aikštelė prie kelio, patogi stovėjimo vieta.\",\"arrive_by\":\"car\",\"transit\":\"\"},{\"name\":\"Pietūs Vlorės marina\",\"lat\":40.458,\"lon\":19.485,\"arrive\":\"13:51\",\"depart\":\"14:51\",\"maps_query\":\"Marina e Vlorës, Vlorë, Albania\",\"google_maps_url\":\"https://www.google.com/maps/search/?api=1&query=Marina%20e%20Vlor%C3%ABs%2C%20Vlor%C3%AB%2C%20Albania\",\"notes\":\"Vlorės uosto promenadoje daug žuvies restoranų – pasirinkite bet kurį su šviežia dienos žuvimi.\",\"arrive_by\":\"car\",\"transit\":\"\"},{\"name\":\"Vlorės pakrantės promenada (Lungomare)\",\"lat\":40.458,\"lon\":19.485,\"arrive\":\"14:51\",\"depart\":\"15:51\",\"maps_query\":\"Lungomare, Vlorë, Albania\",\"google_maps_url\":\"https://www.google.com/maps/search/?api=1&query=Lungomare%2C%20Vlor%C3%AB%2C%20Albania\",\"notes\":\"Pasivaikščiojimas pakrante, vaizdas į Jonų jūrą ir Sazano salą.\",\"arrive_by\":\"walk\",\"transit\":\"\"},{\"name\":\"Hotel Liro – Adults Only\",\"lat\":40.455,\"lon\":19.484,\"arrive\":\"16:01\",\"depart\":\"16:01\",\"maps_query\":\"Hotel Liro Adults Only, Rruga Aleksandër Moisiu, Vlorë, Albania\",\"google_maps_url\":\"https://www.google.com/maps/search/?api=1&query=Hotel%20Liro%20Adults%20Only%2C%20Rruga%20Aleksand%C3%ABr%20Moisiu%2C%20Vlor%C3%AB%2C%20Albania\",\"notes\":\"Nakvynė Vlorėje – privatus paplūdimio ruožas, lauko baseinas, vaizdas į jūrą nuo balkono. Tik suaugusiems.\",\"arrive_by\":\"car\",\"transit\":\"\"}],\"driving_minutes\":205,\"overnight_city\":\"Vlorë\"},{\"number\":4,\"title\":\"Divjakė-Karavasta ir išvykimas\",\"stops\":[{\"name\":\"Karavastos lagūnos Lankytojų centras ir apžvalgos bokštas\",\"lat\":40.979,\"lon\":19.466,\"arrive\":\"10:10\",\"depart\":\"13:20\",\"maps_query\":\"Qendra e Vizitorëve Divjakë-Karavasta, Divjakë, Albania\",\"google_maps_url\":\"https://www.google.com/maps/search/?api=1&query=Qendra%20e%20Vizitor%C3%ABve%20Divjak%C3%AB-Karavasta%2C%20Divjak%C3%AB%2C%20Albania\",\"notes\":\"Automobilį palikite Lankytojų centro aikštelėje – čia veda geras asfaltuotas/tvarkingas kelias, o čia pat yra apie 35 m aukščio apžvalgos bokštas su gražiu vaizdu į lagūną. Jei norite pasiekti giliau lagūnoje esantį bokštą, paskutinius 1–2 km (ir tiek pat atgal) reikia nueiti pėsčiomis – nuomotam automobiliui tas kelias po lietaus būna dumblinas ir netinkamas. Rudenį čia gerai matomi rausvieji pelikanai ir flamingai. Nedidelis mokestis automobiliui įvažiuojant į parką.\",\"arrive_by\":\"car\",\"transit\":\"\"},{\"name\":\"Pietūs Divjakės paplūdimyje\",\"lat\":40.9958,\"lon\":19.4705,\"arrive\":\"13:30\",\"depart\":\"14:30\",\"maps_query\":\"Plazhi i Divjakës, Divjakë, Albania\",\"google_maps_url\":\"https://www.google.com/maps/search/?api=1&query=Plazhi%20i%20Divjak%C3%ABs%2C%20Divjak%C3%AB%2C%20Albania\",\"notes\":\"Paplūdimio žuvies kioskai ir restoranėliai – šviežia žuvis ir jūros gėrybės.\",\"arrive_by\":\"car\",\"transit\":\"\"},{\"name\":\"Tiranos oro uostas (TIA) – automobilio grąžinimas ir skrydis namo\",\"lat\":41.4147,\"lon\":19.7206,\"arrive\":\"16:15\",\"depart\":\"19:05\",\"maps_query\":\"Tirana International Airport Nënë Tereza, Albania\",\"google_maps_url\":\"https://www.google.com/maps/search/?api=1&query=Tirana%20International%20Airport%20N%C3%ABn%C3%AB%20Tereza%2C%20Albania\",\"notes\":\"Automobilio grąžinimas (reikia iki 17:00) – atsargos laiko pakaks. Skrydis į Varšuvą išskrenda 19:05 – registracijai ir saugumo patikrai liks pakankamai laiko.\",\"arrive_by\":\"car\",\"transit\":\"\"}],\"driving_minutes\":170,\"overnight_city\":\"Nėra (skrydis namo)\"}]}",
  "day_routes": [
    {
      "day": 1,
      "title": "Atvykimas į Tiraną",
      "urls": [
        "https://www.google.com/maps/dir/?api=1&origin=Tirana+International+Airport+N%C3%ABn%C3%AB+Tereza,+Albania&destination=Apartament+Tirana8,+Rruga+e+Elbasanit,+Tirana,+Albania&travelmode=driving"
      ],
      "modes": [
        "car"
      ]
    },
    {
      "day": 2,
      "title": "Krujė, Belšo ežeras ir Beratas",
      "urls": [
        "https://www.google.com/maps/dir/?api=1&origin=Kalaja+e+Kruj%C3%ABs,+Kruj%C3%AB,+Albania&destination=Lili+Homemade+Food,+Berat,+Albania&travelmode=driving&waypoints=Liqeni+i+Belshit,+Belsh,+Albania",
        "https://www.google.com/maps/dir/?api=1&origin=Lili+Homemade+Food,+Berat,+Albania&destination=DD+Villa,+Rruga+Antipatrea,+Berat,+Albania&travelmode=walking&waypoints=Mangalem+Quarter,+Berat,+Albania|Kalaja+e+Beratit,+Berat,+Albania|Ura+e+Goric%C3%ABs,+Berat,+Albania"
      ],
      "modes": [
        "car",
        "walk"
      ]
    },
    {
      "day": 3,
      "title": "Osumio kanjonas ir Vlorės pakrantė",
      "urls": [
        "https://www.google.com/maps/dir/?api=1&origin=Kanioni+i+Osumit,+%C3%87orovod%C3%AB,+Albania&destination=Hotel+Liro+Adults+Only,+Rruga+Aleksand%C3%ABr+Moisiu,+Vlor%C3%AB,+Albania&travelmode=driving&waypoints=Marina+e+Vlor%C3%ABs,+Vlor%C3%AB,+Albania"
      ],
      "modes": [
        "car"
      ]
    },
    {
      "day": 4,
      "title": "Divjakė-Karavasta ir išvykimas",
      "urls": [
        "https://www.google.com/maps/dir/?api=1&origin=Qendra+e+Vizitor%C3%ABve+Divjak%C3%AB-Karavasta,+Divjak%C3%AB,+Albania&destination=Tirana+International+Airport+N%C3%ABn%C3%AB+Tereza,+Albania&travelmode=driving&waypoints=Plazhi+i+Divjak%C3%ABs,+Divjak%C3%AB,+Albania"
      ],
      "modes": [
        "car"
      ]
    }
  ],
  "logistics": {
    "legs": [
      {
        "day": 1,
        "from_stop": "Tiranos oro uostas (TIA)",
        "to_stop": "Hanna Apartment",
        "mode": "car",
        "distance_km": 19.0,
        "minutes": 31,
        "transit_kind": "",
        "transit": "",
        "road": "asfaltuotas kelias iš oro uosto į Tiraną, Rruga e Elbasanit rajoną, lygus reljefas",
        "icon": "🚗"
      },
      {
        "day": 2,
        "from_stop": "Krujos pilis ir Skenderbego muziejus bei Senasis bazaras",
        "to_stop": "Belšo ežeras (apžvalgos sustojimas)",
        "mode": "car",
        "distance_km": 91.0,
        "minutes": 92,
        "transit_kind": "",
        "transit": "",
        "road": "asfaltuotas kelias/greitkelis per Tiranos-Elbasano lygumą link Belšo",
        "icon": "🚗"
      },
      {
        "day": 2,
        "from_stop": "Belšo ežeras (apžvalgos sustojimas)",
        "to_stop": "Pietūs „Lili Homemade Food“",
        "mode": "car",
        "distance_km": 62.0,
        "minutes": 97,
        "transit_kind": "",
        "transit": "",
        "road": "asfaltuotas kelias per kalvas link Berato",
        "icon": "🚗"
      },
      {
        "day": 2,
        "from_stop": "Pietūs „Lili Homemade Food“",
        "to_stop": "Mangalemo senasis kvartalas",
        "mode": "walk",
        "distance_km": 0.1,
        "minutes": 1,
        "transit_kind": "",
        "transit": "",
        "road": "per senamiestį",
        "icon": "🚶"
      },
      {
        "day": 2,
        "from_stop": "Mangalemo senasis kvartalas",
        "to_stop": "Berato pilis (Kalaja e Beratit)",
        "mode": "walk",
        "distance_km": 1.0,
        "minutes": 14,
        "transit_kind": "",
        "transit": "",
        "road": "pėsčiųjų takas į kalvą prie pilies",
        "icon": "🚶"
      },
      {
        "day": 2,
        "from_stop": "Berato pilis (Kalaja e Beratit)",
        "to_stop": "Goricos tiltas ir kvartalas",
        "mode": "walk",
        "distance_km": 0.6,
        "minutes": 9,
        "transit_kind": "",
        "transit": "",
        "road": "pėsčiomis žemyn nuo pilies prie Goricos tilto",
        "icon": "🚶"
      },
      {
        "day": 2,
        "from_stop": "Goricos tiltas ir kvartalas",
        "to_stop": "DD Villa",
        "mode": "walk",
        "distance_km": 0.8,
        "minutes": 10,
        "transit_kind": "",
        "transit": "",
        "road": "pėsčiomis per tiltą atgal į Mangalemo kvartalą",
        "icon": "🚶"
      },
      {
        "day": 3,
        "from_stop": "Osumio kanjono apžvalgos aikštelė",
        "to_stop": "Pietūs Vlorės marina",
        "mode": "car",
        "distance_km": 153.0,
        "minutes": 171,
        "transit_kind": "",
        "transit": "",
        "road": "asfaltuotas kelias atgal pro Beratą ir toliau per Fierą (greitkelis) į Vlorę",
        "icon": "🚗"
      },
      {
        "day": 3,
        "from_stop": "Pietūs Vlorės marina",
        "to_stop": "Vlorės pakrantės promenada (Lungomare)",
        "mode": "walk",
        "distance_km": 0.0,
        "minutes": 1,
        "transit_kind": "",
        "transit": "",
        "road": "ta pati vieta Vlorės uoste",
        "icon": "🚶"
      },
      {
        "day": 3,
        "from_stop": "Vlorės pakrantės promenada (Lungomare)",
        "to_stop": "Hotel Liro – Adults Only",
        "mode": "car",
        "distance_km": 0.3,
        "minutes": 1,
        "transit_kind": "",
        "transit": "",
        "road": "ta pati vieta Vlorės pakrantėje",
        "icon": "🚗"
      },
      {
        "day": 4,
        "from_stop": "Karavastos lagūnos Lankytojų centras ir apžvalgos bokštas",
        "to_stop": "Pietūs Divjakės paplūdimyje",
        "mode":
… (sutrumpinta, iš viso 103650 simbolių)
```

Current page:
[HTML puslapis, 72 KB — nerodomas]

Reply with the complete HTML document itself as your entire answer, starting with <!DOCTYPE html>. Do not write files, and do not describe or summarise what you did.

</details>

<details><summary><b>Atsakymas</b></summary>

HTML puslapis sugeneruotas (72 KB).

</details>

### 9. Puslapis — 10:52:10 ✅

- **Modelis:** `claude-sonnet-5` · **Vykdė:** Native Claude (claude -p) · **Trukmė:** 449.8 s
- **Sistemos promptas:** `prompts/page_designer.md`

<details><summary><b>Užklausa</b></summary>

You are updating an already published trip page, not designing a new one. Below are the current page and the current data. Apply the listed changes and make every part of the page match the current data, but keep the design -- colors, layout, CSS, JS, section order -- and all wording that isn't affected exactly as it is. Keep the <!-- PACKING_LIST --> and <!-- TRIP_MAP --> lines where they are.

Changes:
Fix these review findings:
- Lili Homemade Food (Kur pavalgyti, Ką paragauti čia): show "Fërgesë (paprikų ir varškės troškinys)"
- Restorant Pelikan (Kur pavalgyti, Ką paragauti čia): show "Ungurys (lagūnos specialitetas)"
Updated data: Puslapis

**Current data:**

```json
{
  "language": "lt",
  "research": "# Research summary: Albania, TIA to TIA, 30 Oct – 2 Nov 2026 (4 people, nature focus)\n\n**Coverage:** Reddit is blocked for the crawler, and TripAdvisor forum threads returned 403. So I have no r/travel or r/albania posts and only TripAdvisor search snippets. Everything else comes from Wikivoyage, blogs and operator sites. Dates are the page's own date where visible, otherwise \"undated\". I did not verify any drive times myself.\n\n## 1. Candidate stops\n\n| # | Stop | Why recommended | Source (date) |\n|---|---|---|---|\n| 1 | **Berat** (UNESCO) | Ottoman old town, uncrowded off-season. About 2–3 h from Tirana. | [Wikivoyage Albania](https://en.wikivoyage.org/wiki/Albania) (undated); [TripAdvisor thread snippet](https://www.tripadvisor.com/ShowTopic-g294445-i4583-k6457473-Tirana_Berat_Gjirokastra_Saranda-Albania.html) (undated) |\n| 2 | **Osumi Canyon and Bogovë waterfall** (from Berat) | Best nature stop within reach of Berat. The road from Berat to Bogova village is paved (about 1 h), and a regular car is fine. The canyon viewpoint is reachable in a normal car, and the author parked at the top. | [Wander with Laura](https://wanderwithlaura.com/how-to-get-to-bogove-waterfall-and-osum-canyon/) (published Aug 2022, updated 10 Jan 2026) |\n| 3 | **Divjakë-Karavasta lagoon** (pelicans, flamingos) | Autumn is a best season for birds. About 1h40 from Tirana, 30 min north of Fier and Apollonia. | [Nomads Travel Guide](https://www.nomads-travel-guide.com/places/divjake-karavasta-national-park/) (undated); [Birdingplaces](https://www.birdingplaces.eu/en/birdingplaces/albania/divjake-karavasta-national-park) (undated) |\n| 4 | **Gjirokastër** (UNESCO) | Stone town, \"empty of summer crowds\" in November. About 3h20 from Tirana on Google, and about 4 h realistically. This is at your daily driving limit. | [thingstodoinalbania](https://thingstodoinalbania.com/month/november/) (undated); [TIC Rent Car](https://ticrentcar.com/tirana-to-gjirokastra/) (undated) |\n| 5 | **Blue Eye (Syri i Kaltër)** | Spring-fed pool, open year-round, 07:00–19:00, 50 LEK entry. It is 22 km from Sarandë and 35 km from Gjirokastër. The last 2 km of road are unpaved but \"doable\", followed by a 2 km walk. | [Laure Wanders](https://www.laurewanders.com/blue-eye-albania/) (29 Aug 2026) |\n| 6 | **Llogara Pass and Dhermi coast** | The old pass road is still open and paved. The new tunnel costs 250 LEK (from 16 Sep 2025) and saves about 30 min. Snow and ice risk is Dec–Feb, so fine for early November, though fog and rain are possible. | [Explorer Tom](https://explorertom.com/en/llogara-pass-albania/) (11 Jun 2026) |\n| 7 | **Shkodër, Rozafa Castle, Lake Shkodra** | Easy northern option, about 1h47 from Tirana on the A1. | [Travelmath / ViaMichelin results](https://www.travelmath.com/driving-time/from/Shkoder,+Albania/to/Tirana,+Albania) (undated) |\n| 8 | **Komani Lake ferry** (Koman to Fierza) | The most scenic northern option. See the caveats in section 2. | [Ferry operator](https://komanilakeferry.com/timetables-and-prices/) (undated) |\n| 9 | **Bënja thermal baths / Përmet / Vjosa valley** | About 1h15 north of Gjirokastër, on the paved main road. Year-round, and best in cold weather. | [Vjosa Rafting guide](https://vjosarafting.com/benja-thermal-baths-permet/) and [Himara.net](https://himara.net/blog/benja-thermal-baths-destination-guide) (both undated) |\n| 10 | Pogradec / Lake Ohrid (Albanian side) | Low confidence. It is 2.5–3 h from Tirana. I found nothing on Korçë or Voskopojë in autumn. | [Explorer Tom](https://explorertom.com/en/lake-ohrid-albanian-side/) (undated) |\n\n**Overrated or skippable:**\n- **Ksamil and the Riviera beach towns:** described as overrun and overpriced in season. In late October the coast is mostly shuttered, with Ksamil and Dhermi venues closed and \"finding restaurants between Vlorë and Sarandë is challenging\" ([thingstodoinalbania](https://thingstodoinalbania.com/month/november/), undated). Himarë is \"empty by end of October\" per a TripAdvisor snippet (undated).\n- **Bovilla lake and Dajti:** the Dajti cable car is closed on Tuesdays. Your dates fall on Fri–Mon, so this doesn't matter ([TripAdvisor FAQ](https://www.tripadvisor.com/FAQ-g294445-d4573567-Dajti_Ekspres_Cable_Car.html)).\n- **Not found:** I found no sourced opinion on Bunk'Art, Blloku or Durrës. Treat those as unresearched.\n\n## 2. Road and logistics warnings\n\n**Roads to exclude for a standard rental car** (all from [Localrent \"Prohibited routes\"](https://www.localrent.com/en/journal/albania/articles/prohibited-routes/), undated with 2023 file metadata):\n- **SH74 Berat–Përmet:** \"narrow unpaved mountain road covered with small stones\". This is the one your earlier projects flagged.\n- **Berat–Përmet through Osumi Canyon:** unpaved with potholes and large puddles.\n- **Memaliaj–Berat (Martallozi):** unpaved.\n- **Tirana–Qafë-Shtamë via Lake Bovilla:** unpaved serpentine. A regular car can reach the dam, but not beyond ([Localrent](https://www.localrent.com/en/journal/albania/articles/prohibited-routes/) and search results, undated).\n- **Krujë–Burreli:** \"terrible state of disrepair\".\n- **Theth–Valbona:** already excluded by you.\n- **Beach access roads off SH8:** unpaved.\n\nOsumi Canyon is fine only when approached from Berat, so don't continue from it onward to Përmet.\n\n**Komani ferry caveats:**\n- **Season end is unclear.** The operator says 15 Apr to 5 Nov, so 30 Oct – 2 Nov is inside the season. A search snippet from another page said 2 Nov, which I could not verify. Confirm directly with the operator.\n- **Timetable:** Koman 09:00 to Fierza (about 2.5 h), and Fierza 13:00 back to Koman ([operator](https://komanilakeferry.com/timetables-and-prices/); [Explorer Tom](https://explorertom.com/en/koman-lake-ferry-guide/), 2026).\n- **A same-day round trip returns after dark.** By my own arithmetic, the boat is back at Koman about 15:30, plus at least 2 h to Shkodër gives about 17:30, after sunset. This is my calculation, not from a source. It suggests sleeping near Shkodër or Koman.\n- **The car does not need to cross.** The ferry is a dead end, so you would leave the car at Koman and go as foot passengers. That avoids the vehicle-booking problem below.\n- **Car on the ferry:** online pre-booking is essential, priced at €7/m² ([Explorer Tom](https://explorertom.com/en/koman-lake-ferry-guide/)). One traveller in Nov 2025 had to upgrade to an SUV because of rental-company restrictions ([Perchance to Roam](https://perchancetoroam.com/2025/11/01/a-complete-guide-to-taking-albanias-komani-lake-ferry-with-or-without-a-car/), 1 Nov 2025). Check the rental terms.\n- **Road Shkodër to Koman (SH25):** about 60 km and about 2 h, with a narrow one-lane tunnel near the terminal ([Explorer Tom](https://explorertom.com/en/koman-lake-ferry-guide/)). It was in poor shape in Nov 2025, with the last 10 km \"completely ripped open\" ([Perchance to Roam](https://perchancetoroam.com/2025/11/01/a-complete-guide-to-taking-albanias-komani-lake-ferry-with-or-without-a-car/)). [inAlbania](https://www.inalbania.info/koman-road-transformed-to-boost-tourism-in-northern-albania/) (15 Sep 2026) reports the Vau i Dejës–Koman reconstruction as completed. It gives no surface or tunnel details, and the government page I tried to fetch was empty. I'd call this likely improved but not confirmed.\n\n**General driving:**\n- **Time estimates:** Google Maps underestimates mountain roads. Add 25% (\"2 h shows, allow 2.5\", [Endless Travellers](https://theendlesstravellers.com/driving-in-albania/), updated 22 Feb 2026). Tirana to Theth shows 3.5 h but takes about 5 h ([Along Dusty Roads](https://www.alongdustyroads.com/posts/driving-in-albania-car-hire), updated Jun 2025).\n- **Night driving:** avoid it. Village roads are unlit, with livestock and pedestrians (same Along Dusty Roads and Wikivoyage sources). You land at 20:30 on Friday, so keep the first night's drive short, and check that the rental desk is open at that hour (not researched).\n- **Flash floods:** flash flooding is possible in the Vjosa and Osum valleys after heavy rain, and the Lengarica canyon is inaccessible after heavy rain ([thingstodoinalbania](https://thingstodoinalbania.com/month/november/), undated, single source).\n- **Tolls:** the Llogara Tunnel and the A1 to Kosovo are tolled ([Endless Travellers](https://theendlesstravellers.com/driving-in-albania/)).\n- **Rules:** police speed checks are frequent, alcohol limit is 0.01% ([Wikivoyage](https://en.wikivoyage.org/wiki/Albania)).\n\n## 3. Seasonal notes (30 Oct – 2 Nov)\n\n- **Rain:** November is the rainiest month, about 12 rain days and 180 mm, with roughly 12–15 °C average temperatures ([Climates to Travel](https://www.climatestotravel.com/weatherbymonth/albania/november) and similar, undated).\n- **Unreliable figure:** thingstodoinalbania claims 25 °C highs and 2 in of rain in November. That contradicts every other source, so don't use its numbers.\n- **Snow:** snow is possible above 1,500 m before mid-November. Theth/Valbona is snow-covered ([thingstodoinalbania](https://thingstodoinalbania.com/month/november/), undated, single source).\n- **Fog:** persistent morning fog on Lake Shkodra and in the Korçë basin (same source).\n- **Lake Shkodra boats:** schedules shrink to weekends only (same source, unconfirmed). Your Sat and Sun fall on weekends.\n- **Daylight:** sources give sunset of 16:45–17:25 (Wanderlog and others, undated). Their sunrise figure of 05:46 is implausible, so I don't trust them. My own rough estimate for Tirana (CET, after clocks change on 25 Oct) is sunset about 16:30–16:40. That is earlier than your 17:00–17:30 assumption. The Weather/Season Agent should check this with Open-Meteo.\n- **Calendar:** 30 Oct is a Friday and 2 Nov a Monday, so the trip has two full days (Sat, Sun) plus the Friday-night arrival and the Monday return. Monday needs the car back at TIA by about 17:00.\n\n## 4. Route shapes for the Logistics Validator (not validated)\n\n- **Central/south:** Fri night near Tirana or Durrës. Sat via Karavasta and Apollonia to Berat. Sun via Osumi and Bogova to Gjirokastër. Mon Gjirokastër to TIA at about 3.5–4 h. The last leg is the tightest, needing an early start. Blue Eye and Përmet do not fit without dropping something.\n- **North (easier):** Fri night Tirana. Sat Shkodër, Rozafa and the lake. Sun Komani ferry from a Shkodër or Koman base. Mon return via the A1 (about 1h47).\n\nBoth fit the 3.5–4 h limit only if the Validator confirms the legs. The central/south option depends on avoiding SH74 and the Berat–Përmet canyon road.\n\n## 5. Gaps to close\n\n- Direct confirmation of the Komani ferry season end and whether foot passengers can get a seat in early November.\n- Rental terms: a 4-person vehicle, ferry carriage, and the airport desk's opening hours after a 20:30 landing.\n- Osumi Canyon water levels and access in early November. The one detailed source visited in summer.\n- Korçë and Voskopojë autumn conditions, if you want a southeastern alternative.",
  "accommodation": "## Nakvynės vietos (tik užsakytos)\n\nKeliautojas jau užsakė ir patvirtino konkrečius nakvynės objektus per booking.com nuorodas. Žemiau — tik šios užsakytos vietos, be papildomų alternatyvų.\n\n### 1. Tirana (penktadienis, 2026-10-30 → šeštadienis, 2026-10-31)\n\n**✅ Užsakyta — Hanna Apartment** — **51 €/naktį**\n- Rruga e Elbasanit, Tirana. Įvertinimas 9.0/10 (186 atsiliepimai).\n- Kondicionierius, nemokamas WiFi. Tinka 4 žmonėms (butas).\n- Nuoroda: https://www.booking.com/hotel/al/apartament-tirana8.lt.html\n\n### 2. Beratas (šeštadienis, 2026-10-31 → sekmadienis, 2026-11-01)\n\n**✅ Užsakyta — DD Villa** — **61 €/naktį**\n- Rruga Antipatrea, Beratas. Įvertinimas 8.8/10 (667 atsiliepimai).\n- Sodas, baras, bendra svetainė, miesto vaizdas, pusryčiai (bufetas/à la carte), privatus parkavimas (už papildomą mokestį), restoranas vietoje.\n- Nuoroda: https://www.booking.com/hotel/al/dd-villa.lt.html\n\n### 3. Vlorė / Radhimė (sekmadienis, 2026-11-01 → pirmadienis, 2026-11-02)\n\n**✅ Užsakyta — Hotel Liro – Adults Only** — **117 €/naktį**\n- Aleksandër Moisiu Street, Vlorė. Įvertinimas 8.6/10 (1295 atsiliepimai).\n- Privatus paplūdimio ruožas, lauko baseinas, nemokamas parkavimas, restoranas/baras, pusryčiai, vaizdas į jūrą nuo balkono. Autobusų stotelė priešais viešbutį.\n- Nuoroda: https://www.booking.com/hotel/al/liro.lt.html\n- ⚠️ Pastaba: \"Adults Only\" — jei grupėje yra vaikų, šią vietą reikėtų pakeisti.\n\n**Biudžeto suma nakvynėms (3 naktys, visai grupei):** 51 + 61 + 117 = **229 €**",
  "booking_search": [
    {
      "city": "Tirana",
      "name": "Hanna Apartment",
      "checkin": "2026-10-30",
      "checkout": "2026-10-31",
      "nights": 1,
      "price_per_night_eur": 51,
      "url": "https://www.booking.com/searchresults.html?ss=Hanna+Apartment%2C+Tirana&checkin=2026-10-30&checkout=2026-10-31&group_adults=4&group_children=0&no_rooms=1"
    },
    {
      "city": "Berat",
      "name": "DD Villa",
      "checkin": "2026-10-31",
      "checkout": "2026-11-01",
      "nights": 1,
      "price_per_night_eur": 61,
      "url": "https://www.booking.com/searchresults.html?ss=DD+Villa%2C+Berat&checkin=2026-10-31&checkout=2026-11-01&group_adults=4&group_children=0&no_rooms=1"
    },
    {
      "city": "Vlorë",
      "name": "Hotel Liro - Adults Only",
      "checkin": "2026-11-01",
      "checkout": "2026-11-02",
      "nights": 1,
      "price_per_night_eur": 117,
      "url": "https://www.booking.com/searchresults.html?ss=Hotel+Liro+-+Adults+Only%2C+Vlor%C3%AB&checkin=2026-11-01&checkout=2026-11-02&group_adults=4&group_children=0&no_rooms=1"
    }
  ],
  "stays": [
    {
      "url": "https://www.booking.com/hotel/al/apartament-tirana8.lt.html",
      "name": "Hanna Apartment",
      "address": "Rruga e Elbasanit, 1035 Tirana, Albanija, 1035, Rruga e Elbasanit, Albanija",
      "description": "Hanna Apartment is located in Tirana. This apartment provides air-conditioned accommodation with free WiFi.",
      "full_description": null,
      "facilities": null,
      "rating": 9.0,
      "rating_scale": 10,
      "review_count": 186,
      "photo_urls": [
        "https://cf.bstatic.com/xdata/images/hotel/max1024x768/633887464.jpg?k=b976c4febe171b551f477e9eee870608b6dc963117d876c793f0d9f4e74a10c1&o=&hp=1",
        "https://cf.bstatic.com/xdata/images/hotel/max1024x768/633887550.jpg?k=694dc1002849285d2f750017340c1edd34a96dd80c7fbc5b6481ab43eadda7c0&o=&hp=1",
        "https://cf.bstatic.com/xdata/images/hotel/max1024x768/633887291.jpg?k=4963ffaa4c10e0fd9f47b51e58b930fc53eff67747c24a914957854aecfefbc0&o=&hp=1",
        "https://cf.bstatic.com/xdata/images/hotel/max1024x768/633889677.jpg?k=5da3b33dfa81e6240d74fe7d36bf94844df25d861a8cfb0f6e6d273f1eb9459a&o=&hp=1",
        "https://cf.bstatic.com/xdata/images/hotel/max1024x768/651343123.jpg?k=5441b1e29d0d9b0725ae1274688a078b2e764fba7c641900e5a8cc9a87c5bc84&o=&hp=1"
      ],
      "photos": [
        {
          "stop_name": "Hanna Apartment",
          "local_path": "images/stay-hanna-apartment-1.jpg",
          "commons_filename": "",
          "license": "© apgyvendinimo įstaiga / Booking.com",
          "author": null,
          "source_url": "https://www.booking.com/hotel/al/apartament-tirana8.lt.html",
          "size_bytes": 110275
        },
        {
          "stop_name": "Hanna Apartment",
          "local_path": "images/stay-hanna-apartment-2.jpg",
          "commons_filename": "",
          "license": "© apgyvendinimo įstaiga / Booking.com",
          "author": null,
          "source_url": "https://www.booking.com/hotel/al/apartament-tirana8.lt.html",
          "size_bytes": 32003
        },
        {
          "stop_name": "Hanna Apartment",
          "local_path": "images/stay-hanna-apartment-3.jpg",
          "commons_filename": "",
          "license": "© apgyvendinimo įstaiga / Booking.com",
          "author": null,
          "source_url": "https://www.booking.com/hotel/al/apartament-tirana8.lt.html",
          "size_bytes": 55703
        },
        {
          "stop_name": "Hanna Apartment",
          "local_path": "images/stay-hanna-apartment-4.jpg",
          "commons_filename": "",
          "license": "© apgyvendinimo įstaiga / Booking.com",
          "author": null,
          "source_url": "https://www.booking.com/hotel/al/apartament-tirana8.lt.html",
          "size_bytes": 53502
        },
        {
          "stop_name": "Hanna Apartment",
          "local_path": "images/stay-hanna-apartment-5.jpg",
          "commons_filename": "",
          "license": "© apgyvendinimo įstaiga / Booking.com",
          "author": null,
          "source_url": "https://www.booking.com/hotel/al/apartament-tirana8.lt.html",
          "size_bytes": 54202
        }
      ]
    },
    {
      "url": "https://www.booking.com/hotel/al/dd-villa.lt.html",
      "name": "DD Villa",
      "address": "Rruga Antipatrea, 5001 Beratis, Albanija, 5001, Rruga Antipatrea, Albanija",
      "description": "Situated in Berat, DD Villa features a garden, a bar and a shared lounge. The property has city views. Private parking can be arranged at an extra charge.",
      "full_description": [
        "Situated in Berat, DD Villa features a garden, a bar and a shared lounge. The property has city views. Private parking can be arranged at an extra charge. The bed and breakfast will provide guests with air-conditioned units offering a wardrobe, a kettle, a dishwasher, a microwave, a safety deposit box, a flat-screen TV and a private bathroom with a bidet. Free WiFi is accessible to all guests, while certain rooms are equipped with a terrace. At the bed and breakfast, every unit is equipped with bed linen and towels. A buffet, à la carte or continental breakfast is available at the property. Guests are welcome to eat in the on-site family-friendly restaurant, which is open for dinner, lunch, brunch and high tea. Sightseeing tours are available around the property. Both a bicycle rental service and a car rental service are available at the bed and breakfast, while cycling can be enjoyed nearby. Tirana International Mother Teresa Airport is 120 km from the property, and the property offers a paid airport shuttle service."
      ],
      "facilities": [
        "Populiariausi patogumai",
        "Privati automobilių stovėjimo aikštelė",
        "Spartus nemokamas belaidis internetas (101 Mbps)",
        "Pervežimas iš / į oro uostą",
        "Numeriai nerūkantiems",
        "Numeriai šeimai",
        "Aptarnavimas numeriuose",
        "Restoranas",
        "Baras",
        "Nuostabūs pusryčiai"
      ],
      "rating": 8.8,
      "rating_scale": 10,
      "review_count": 667,
      "photo_urls": [
        "https://cf.bstatic.com/xdata/images/hotel/max1024x768/529582807.jpg?k=731fe174d8d2b7402280e7c8008fdd355a874d76e0b7f03f1f516ad3c92ccd4f&o=&hp=1",
        "https://cf.bstatic.com/xdata/images/hotel/max1024x768/921271115.jpg?k=714680e569beb3f835a5ab5f15daaf4460dda2cd2509890599543048e17af49a&o=&hp=1",
        "https://cf.bstatic.com/xdata/images/hotel/max1024x768/529582816.jpg?k=8c6581a00d3c484f9e62bbaa3ba21bf08b13e50ccda4cf1e32c52876fb08a13d&o=&hp=1",
        "https://cf.bstatic.com/xdata/images/hotel/max1024x768/544036358.jpg?k=03e5cee7c142331675268001c541cbe0e4cb64ba67f8d850dc1cf05be6ee1024&o=&hp=1",
        "https://cf.bstatic.com/xdata/images/hotel/max1024x768/529582821.jpg?k=58830e6a252b81f2a06faccae174fad12a474f063ed8162b382a1ac3626b93d9&o=&hp=1"
      ],
      "photos": [
        {
          "stop_name": "DD Villa",
          "local_path": "images/stay-dd-villa-1.jpg",
          "commons_filename": "",
          "license": "© apgyvendinimo įstaiga / Booking.com",
          "author": null,
          "source_url": "https://www.booking.com/hotel/al/dd-villa.lt.html",
          "size_bytes": 154626
        },
        {
          "stop_name": "DD Villa",
          "local_path": "images/stay-dd-villa-2.jpg",
          "commons_filename": "",
          "license": "© apgyvendinimo įstaiga / Booking.com",
          "author": null,
          "source_url": "https://www.booking.com/hotel/al/dd-villa.lt.html",
          "size_bytes": 69651
        },
        {
          "stop_name": "DD Villa",
          "local_path": "images/stay-dd-villa-3.jpg",
          "commons_filename": "",
          "license": "© apgyvendinimo įstaiga / Booking.com",
          "author": null,
          "source_url": "https://www.booking.com/hotel/al/dd-villa.lt.html",
          "size_bytes": 99758
        },
        {
          "stop_name": "DD Villa",
          "local_path": "images/stay-dd-villa-4.jpg",
          "commons_filename": "",
          "license": "© apgyvendinimo įstaiga / Booking.com",
          "author": null,
          "source_url": "https://www.booking.com/hotel/al/dd-villa.lt.html",
          "size_bytes": 99712
        },
        {
          "stop_name": "DD Villa",
          "local_path": "images/stay-dd-villa-5.jpg",
          "commons_filename": "",
          "license": "© apgyvendinimo įstaiga / Booking.com",
          "author": null,
          "source_url": "https://www.booking.com/hotel/al/dd-villa.lt.html",
          "size_bytes": 129326
        }
      ]
    },
    {
      "url": "https://www.booking.com/hotel/al/liro.lt.html",
      "name": "Hotel Liro - Adults Only",
      "address": "Aleksandër Moisiu Street, 9405 Vliorė, Albanija, 9405, Aleksandër Moisiu Street, Albanija",
      "description": "Located in Vlorë, Hotel Liro - Adults Only offers a private beach area with free-to-use sun loungers and parasols.",
      "full_description": [
        "Located in Vlorë, Hotel Liro - Adults Only offers a private beach area with free-to-use sun loungers and parasols. The on-site bar and restaurant offers a spacious terrace where guests can enjoy the Mediterranean dishes it serves. Free WiFi access is available throughout the property. All the rooms are air-conditioned and come with a furnished balcony overlooking the sea. Each room is equipped with satellite TV, a minibar and a safe. Featuring a shower, private bathrooms also come with a hairdryer and free toiletries. Hotel Liro - Adults Only offers an array of activities can be enjoyed on site or in the surroundings, including windsurfing. The cenre of Vlorë and the scenic outlook of Kuzum Baba can be found within a 6-km radius. The Archaeological Park of Oricum is 10 km from Liro Hotel. Llogara National Park is 25 km away. The local bus stop is right in front of the hotel. Tirana Airport is 150 km away. The property offers free parking."
      ],
      "facilities": [
        "Populiariausi patogumai",
        "Lauko baseinas",
        "Nemokama vieta automobiliui",
        "Šalia paplūdimio",
        "Nemokamas belaidis internetas",
        "Numeriai šeimai",
        "Restoranas",
        "Numeriai nerūkantiems",
        "Baras",
        "Privati paplūdimio dalis",
        "Nuostabūs pusryčiai"
      ],
      "rating": 8.6,
      "rating_scale": 10,
      "review_count": 1295,
      "photo_urls": [
        "https://cf.bstatic.com/xdata/images/hotel/max1024x768/506995294.jpg?k=23925d61528b241c35e7b43446d3f11a9faa202b08e9903c82a6e3cb2afa43d7&o=&hp=1",
        "https://cf.bstatic.com/xdata/images/hotel/max1024x768/506995475.jpg?k=8b2bd840a2ed21d4d6da7442afc978dd5073fc1eb1d9a567413fdab748546eac&o=&hp=1",
        "https://cf.bstatic.com/xdata/images/hotel/max1024x768/556057394.jpg?k=575cc81ebc625197b6b6c6af18c2ec9a6eda54fa3ed14e29ecef4935b13b27a6&o=&hp=1",
        "https://cf.bstatic.com/xdata/images/hotel/max1024x768/506995518.jpg?k=2db992e93cda20eb611af0c65c6d59f388efc2150e468dfbfae8e8e3fbb3b665&o=&hp=1",
        "https://cf.bstatic.com/xdata/images/hotel/max1024x768/506995661.jpg?k=d3755c0ed1215710923e75d5050056023d41ecd92820d69af21aa384123992dd&o=&hp=1"
      ],
      "photos": [
        {
          "stop_name": "Hotel Liro - Adults Only",
          "local_path": "images/stay-hotel-liro-adults-only-1.jpg",
          "commons_filename": "",
          "license": "© apgyvendinimo įstaiga / Booking.com",
          "author": null,
          "source_url": "https://www.booking.com/hotel/al/liro.lt.html",
          "size_bytes": 125824
        },
        {
          "stop_name": "Hotel Liro - Adults Only",
          "local_path": "images/stay-hotel-liro-adults-only-2.jpg",
          "commons_filename": "",
          "license": "© apgyvendinimo įstaiga / Booking.com",
          "author": null,
          "source_url": "https://www.booking.com/hotel/al/liro.lt.html",
          "size_bytes": 238091
        },
        {
          "stop_name": "Hotel Liro - Adults Only",
          "local_path": "images/stay-hotel-liro-adults-only-3.jpg",
          "commons_filename": "",
          "license": "© apgyvendinimo įstaiga / Booking.com",
          "author": null,
          "source_url": "https://www.booking.com/hotel/al/liro.lt.html",
          "size_bytes": 133915
        },
        {
          "stop_name": "Hotel Liro - Adults Only",
          "local_path": "images/stay-hotel-liro-adults-only-4.jpg",
          "commons_filename": "",
          "license": "© apgyvendinimo įstaiga / Booking.com",
          "author": null,
          "source_url": "https://www.booking.com/hotel/al/liro.lt.html",
          "size_bytes": 211665
        },
        {
          "stop_name": "Hotel Liro - Adults Only",
          "local_path": "images/stay-hotel-liro-adults-only-5.jpg",
          "commons_filename": "",
          "license": "© apgyvendinimo įstaiga / Booking.com",
          "author": null,
          "source_url": "https://www.booking.com/hotel/al/liro.lt.html",
          "size_bytes": 64880
        }
      ]
    }
  ],
  "itinerary": "{\"days\":[{\"number\":1,\"title\":\"Atvykimas į Tiraną\",\"stops\":[{\"name\":\"Tiranos oro uostas (TIA)\",\"lat\":41.4147,\"lon\":19.7206,\"arrive\":\"20:30\",\"depart\":\"21:00\",\"maps_query\":\"Tirana International Airport Nënë Tereza, Albania\",\"google_maps_url\":\"https://www.google.com/maps/search/?api=1&query=Tirana%20International%20Airport%20N%C3%ABn%C3%AB%20Tereza%2C%20Albania\",\"notes\":\"Skrydis iš Varšuvos nusileidžia 20:30. Automobilio nuomos (VW Tiguan ar panašus visureigis, tinka 4 žmonėms ir bagažui, su Papildomo vairuotojo ir pilnos apsaugos draudimu) atsiėmimas 21:00. Tą pačią vietą reikės grąžinti automobilį lapkričio 2 d. iki 17:00.\",\"arrive_by\":\"car\",\"transit\":\"\"},{\"name\":\"Hanna Apartment\",\"lat\":41.3192,\"lon\":19.8294,\"arrive\":\"21:20\",\"depart\":\"21:20\",\"maps_query\":\"Apartament Tirana8, Rruga e Elbasanit, Tirana, Albania\",\"google_maps_url\":\"https://www.google.com/maps/search/?api=1&query=Apartament%20Tirana8%2C%20Rruga%20e%20Elbasanit%2C%20Tirana%2C%20Albania\",\"notes\":\"Pirma nakvynė – butas Rruga e Elbasanit, kondicionierius, nemokamas WiFi, tinka 4 žmonėms. Kelias nuo oro uosto apie 20 min, vėlai vakare eismas ramus.\",\"arrive_by\":\"car\",\"transit\":\"\"}],\"driving_minutes\":20,\"overnight_city\":\"Tirana\"},{\"number\":2,\"title\":\"Krujė, Belšo ežeras ir Beratas\",\"stops\":[{\"name\":\"Krujos pilis ir Skenderbego muziejus bei Senasis bazaras\",\"lat\":41.5086,\"lon\":19.7919,\"arrive\":\"09:45\",\"depart\":\"10:30\",\"maps_query\":\"Kalaja e Krujës, Krujë, Albania\",\"google_maps_url\":\"https://www.google.com/maps/search/?api=1&query=Kalaja%20e%20Kruj%C3%ABs%2C%20Kruj%C3%AB%2C%20Albania\",\"notes\":\"Skenderbego muziejus pilies viduje, bilietas apie 200 lekų (~2 €). Žiemos darbo laikas apytiksliai 09:00–16:00 – darbo laiką verta pasitikrinti. Prie pilies – senasis bazaras su amatininkų dirbiniais ir suvenyrais.\",\"arrive_by\":\"car\",\"transit\":\"\"},{\"name\":\"Belšo ežeras (apžvalgos sustojimas)\",\"lat\":41.0931,\"lon\":19.8828,\"arrive\":\"12:02\",\"depart\":\"12:17\",\"maps_query\":\"Liqeni i Belshit, Belsh, Albania\",\"google_maps_url\":\"https://www.google.com/maps/search/?api=1&query=Liqeni%20i%20Belshit%2C%20Belsh%2C%20Albania\",\"notes\":\"Trumpas sustojimas pakeliui – gražus Dumrės plokščiakalnio ir ežerų vaizdas, proga kavai ir nuotraukai.\",\"arrive_by\":\"car\",\"transit\":\"\"},{\"name\":\"Pietūs „Lili Homemade Food“\",\"lat\":40.7064,\"lon\":19.9513,\"arrive\":\"13:54\",\"depart\":\"14:55\",\"maps_query\":\"Lili Homemade Food, Berat, Albania\",\"google_maps_url\":\"https://www.google.com/maps/search/?api=1&query=Lili%20Homemade%20Food%2C%20Berat%2C%20Albania\",\"notes\":\"Populiarus namų virtuvės restoranas Mangalemo kvartale, vietiniai patiekalai.\",\"arrive_by\":\"car\",\"transit\":\"\"},{\"name\":\"Mangalemo senasis kvartalas\",\"lat\":40.706,\"lon\":19.951,\"arrive\":\"14:55\",\"depart\":\"15:09\",\"maps_query\":\"Mangalem Quarter, Berat, Albania\",\"google_maps_url\":\"https://www.google.com/maps/search/?api=1&query=Mangalem%20Quarter%2C%20Berat%2C%20Albania\",\"notes\":\"Pasivaikščiojimas osmanų laikų gatvelėmis su garsiaisiais „tūkstančio langų“ namais.\",\"arrive_by\":\"walk\",\"transit\":\"\"},{\"name\":\"Berato pilis (Kalaja e Beratit)\",\"lat\":40.7014,\"lon\":19.9447,\"arrive\":\"15:29\",\"depart\":\"16:13\",\"maps_query\":\"Kalaja e Beratit, Berat, Albania\",\"google_maps_url\":\"https://www.google.com/maps/search/?api=1&query=Kalaja%20e%20Beratit%2C%20Berat%2C%20Albania\",\"notes\":\"Gyvenama pilis su bizantiškomis bažnyčiomis. Įėjimas į teritoriją laisvas, Onufrijaus muziejuje bilietas apie 200 lekų – darbo laiką verta pasitikrinti.\",\"arrive_by\":\"walk\",\"transit\":\"\"},{\"name\":\"Goricos tiltas ir kvartalas\",\"lat\":40.7021,\"lon\":19.9497,\"arrive\":\"16:38\",\"depart\":\"17:08\",\"maps_query\":\"Ura e Goricës, Berat, Albania\",\"google_maps_url\":\"https://www.google.com/maps/search/?api=1&query=Ura%20e%20Goric%C3%ABs%2C%20Berat%2C%20Albania\",\"notes\":\"Osmanų laikų akmeninis tiltas per Osumo upę – ypač gražus prieblandoje, puikus vaizdas į Mangalemą.\",\"arrive_by\":\"walk\",\"transit\":\"\"},{\"name\":\"DD Villa\",\"lat\":40.7057,\"lon\":19.952,\"arrive\":\"17:23\",\"depart\":\"17:23\",\"maps_query\":\"DD Villa, Rruga Antipatrea, Berat, Albania\",\"google_maps_url\":\"https://www.google.com/maps/search/?api=1&query=DD%20Villa%2C%20Rruga%20Antipatrea%2C%20Berat%2C%20Albania\",\"notes\":\"Nakvynė Berate – sodas, baras, pusryčiai, privatus parkavimas už papildomą mokestį.\",\"arrive_by\":\"walk\",\"transit\":\"\"}],\"driving_minutes\":180,\"overnight_city\":\"Berat\"},{\"number\":3,\"title\":\"Osumio kanjonas ir Vlorės pakrantė\",\"stops\":[{\"name\":\"Osumio kanjono apžvalgos aikštelė\",\"lat\":40.5044,\"lon\":20.227,\"arrive\":\"10:15\",\"depart\":\"11:00\",\"maps_query\":\"Kanioni i Osumit, Çorovodë, Albania\",\"google_maps_url\":\"https://www.google.com/maps/search/?api=1&query=Kanioni%20i%20Osumit%2C%20%C3%87orovod%C3%AB%2C%20Albania\",\"notes\":\"Vienas gražiausių gamtos vaizdų kelyje – kanjono apžvalgos aikštelė prie kelio, patogi stovėjimo vieta.\",\"arrive_by\":\"car\",\"transit\":\"\"},{\"name\":\"Pietūs Vlorės marina\",\"lat\":40.458,\"lon\":19.485,\"arrive\":\"13:51\",\"depart\":\"14:51\",\"maps_query\":\"Marina e Vlorës, Vlorë, Albania\",\"google_maps_url\":\"https://www.google.com/maps/search/?api=1&query=Marina%20e%20Vlor%C3%ABs%2C%20Vlor%C3%AB%2C%20Albania\",\"notes\":\"Vlorės uosto promenadoje daug žuvies restoranų – pasirinkite bet kurį su šviežia dienos žuvimi.\",\"arrive_by\":\"car\",\"transit\":\"\"},{\"name\":\"Vlorės pakrantės promenada (Lungomare)\",\"lat\":40.458,\"lon\":19.485,\"arrive\":\"14:51\",\"depart\":\"15:51\",\"maps_query\":\"Lungomare, Vlorë, Albania\",\"google_maps_url\":\"https://www.google.com/maps/search/?api=1&query=Lungomare%2C%20Vlor%C3%AB%2C%20Albania\",\"notes\":\"Pasivaikščiojimas pakrante, vaizdas į Jonų jūrą ir Sazano salą.\",\"arrive_by\":\"walk\",\"transit\":\"\"},{\"name\":\"Hotel Liro – Adults Only\",\"lat\":40.455,\"lon\":19.484,\"arrive\":\"16:01\",\"depart\":\"16:01\",\"maps_query\":\"Hotel Liro Adults Only, Rruga Aleksandër Moisiu, Vlorë, Albania\",\"google_maps_url\":\"https://www.google.com/maps/search/?api=1&query=Hotel%20Liro%20Adults%20Only%2C%20Rruga%20Aleksand%C3%ABr%20Moisiu%2C%20Vlor%C3%AB%2C%20Albania\",\"notes\":\"Nakvynė Vlorėje – privatus paplūdimio ruožas, lauko baseinas, vaizdas į jūrą nuo balkono. Tik suaugusiems.\",\"arrive_by\":\"car\",\"transit\":\"\"}],\"driving_minutes\":205,\"overnight_city\":\"Vlorë\"},{\"number\":4,\"title\":\"Divjakė-Karavasta ir išvykimas\",\"stops\":[{\"name\":\"Karavastos lagūnos Lankytojų centras ir apžvalgos bokštas\",\"lat\":40.979,\"lon\":19.466,\"arrive\":\"10:10\",\"depart\":\"13:20\",\"maps_query\":\"Qendra e Vizitorëve Divjakë-Karavasta, Divjakë, Albania\",\"google_maps_url\":\"https://www.google.com/maps/search/?api=1&query=Qendra%20e%20Vizitor%C3%ABve%20Divjak%C3%AB-Karavasta%2C%20Divjak%C3%AB%2C%20Albania\",\"notes\":\"Automobilį palikite Lankytojų centro aikštelėje – čia veda geras asfaltuotas/tvarkingas kelias, o čia pat yra apie 35 m aukščio apžvalgos bokštas su gražiu vaizdu į lagūną. Jei norite pasiekti giliau lagūnoje esantį bokštą, paskutinius 1–2 km (ir tiek pat atgal) reikia nueiti pėsčiomis – nuomotam automobiliui tas kelias po lietaus būna dumblinas ir netinkamas. Rudenį čia gerai matomi rausvieji pelikanai ir flamingai. Nedidelis mokestis automobiliui įvažiuojant į parką.\",\"arrive_by\":\"car\",\"transit\":\"\"},{\"name\":\"Pietūs Divjakės paplūdimyje\",\"lat\":40.9958,\"lon\":19.4705,\"arrive\":\"13:30\",\"depart\":\"14:30\",\"maps_query\":\"Plazhi i Divjakës, Divjakë, Albania\",\"google_maps_url\":\"https://www.google.com/maps/search/?api=1&query=Plazhi%20i%20Divjak%C3%ABs%2C%20Divjak%C3%AB%2C%20Albania\",\"notes\":\"Paplūdimio žuvies kioskai ir restoranėliai – šviežia žuvis ir jūros gėrybės.\",\"arrive_by\":\"car\",\"transit\":\"\"},{\"name\":\"Tiranos oro uostas (TIA) – automobilio grąžinimas ir skrydis namo\",\"lat\":41.4147,\"lon\":19.7206,\"arrive\":\"16:15\",\"depart\":\"19:05\",\"maps_query\":\"Tirana International Airport Nënë Tereza, Albania\",\"google_maps_url\":\"https://www.google.com/maps/search/?api=1&query=Tirana%20International%20Airport%20N%C3%ABn%C3%AB%20Tereza%2C%20Albania\",\"notes\":\"Automobilio grąžinimas (reikia iki 17:00) – atsargos laiko pakaks. Skrydis į Varšuvą išskrenda 19:05 – registracijai ir saugumo patikrai liks pakankamai laiko.\",\"arrive_by\":\"car\",\"transit\":\"\"}],\"driving_minutes\":170,\"overnight_city\":\"Nėra (skrydis namo)\"}]}",
  "day_routes": [
    {
      "day": 1,
      "title": "Atvykimas į Tiraną",
      "urls": [
        "https://www.google.com/maps/dir/?api=1&origin=Tirana+International+Airport+N%C3%ABn%C3%AB+Tereza,+Albania&destination=Apartament+Tirana8,+Rruga+e+Elbasanit,+Tirana,+Albania&travelmode=driving"
      ],
      "modes": [
        "car"
      ]
    },
    {
      "day": 2,
      "title": "Krujė, Belšo ežeras ir Beratas",
      "urls": [
        "https://www.google.com/maps/dir/?api=1&origin=Kalaja+e+Kruj%C3%ABs,+Kruj%C3%AB,+Albania&destination=Lili+Homemade+Food,+Berat,+Albania&travelmode=driving&waypoints=Liqeni+i+Belshit,+Belsh,+Albania",
        "https://www.google.com/maps/dir/?api=1&origin=Lili+Homemade+Food,+Berat,+Albania&destination=DD+Villa,+Rruga+Antipatrea,+Berat,+Albania&travelmode=walking&waypoints=Mangalem+Quarter,+Berat,+Albania|Kalaja+e+Beratit,+Berat,+Albania|Ura+e+Goric%C3%ABs,+Berat,+Albania"
      ],
      "modes": [
        "car",
        "walk"
      ]
    },
    {
      "day": 3,
      "title": "Osumio kanjonas ir Vlorės pakrantė",
      "urls": [
        "https://www.google.com/maps/dir/?api=1&origin=Kanioni+i+Osumit,+%C3%87orovod%C3%AB,+Albania&destination=Hotel+Liro+Adults+Only,+Rruga+Aleksand%C3%ABr+Moisiu,+Vlor%C3%AB,+Albania&travelmode=driving&waypoints=Marina+e+Vlor%C3%ABs,+Vlor%C3%AB,+Albania"
      ],
      "modes": [
        "car"
      ]
    },
    {
      "day": 4,
      "title": "Divjakė-Karavasta ir išvykimas",
      "urls": [
        "https://www.google.com/maps/dir/?api=1&origin=Qendra+e+Vizitor%C3%ABve+Divjak%C3%AB-Karavasta,+Divjak%C3%AB,+Albania&destination=Tirana+International+Airport+N%C3%ABn%C3%AB+Tereza,+Albania&travelmode=driving&waypoints=Plazhi+i+Divjak%C3%ABs,+Divjak%C3%AB,+Albania"
      ],
      "modes": [
        "car"
      ]
    }
  ],
  "logistics": {
    "legs": [
      {
        "day": 1,
        "from_stop": "Tiranos oro uostas (TIA)",
        "to_stop": "Hanna Apartment",
        "mode": "car",
        "distance_km": 19.0,
        "minutes": 31,
        "transit_kind": "",
        "transit": "",
        "road": "asfaltuotas kelias iš oro uosto į Tiraną, Rruga e Elbasanit rajoną, lygus reljefas",
        "icon": "🚗"
      },
      {
        "day": 2,
        "from_stop": "Krujos pilis ir Skenderbego muziejus bei Senasis bazaras",
        "to_stop": "Belšo ežeras (apžvalgos sustojimas)",
        "mode": "car",
        "distance_km": 91.0,
        "minutes": 92,
        "transit_kind": "",
        "transit": "",
        "road": "asfaltuotas kelias/greitkelis per Tiranos-Elbasano lygumą link Belšo",
        "icon": "🚗"
      },
      {
        "day": 2,
        "from_stop": "Belšo ežeras (apžvalgos sustojimas)",
        "to_stop": "Pietūs „Lili Homemade Food“",
        "mode": "car",
        "distance_km": 62.0,
        "minutes": 97,
        "transit_kind": "",
        "transit": "",
        "road": "asfaltuotas kelias per kalvas link Berato",
        "icon": "🚗"
      },
      {
        "day": 2,
        "from_stop": "Pietūs „Lili Homemade Food“",
        "to_stop": "Mangalemo senasis kvartalas",
        "mode": "walk",
        "distance_km": 0.1,
        "minutes": 1,
        "transit_kind": "",
        "transit": "",
        "road": "per senamiestį",
        "icon": "🚶"
      },
      {
        "day": 2,
        "from_stop": "Mangalemo senasis kvartalas",
        "to_stop": "Berato pilis (Kalaja e Beratit)",
        "mode": "walk",
        "distance_km": 1.0,
        "minutes": 14,
        "transit_kind": "",
        "transit": "",
        "road": "pėsčiųjų takas į kalvą prie pilies",
        "icon": "🚶"
      },
      {
        "day": 2,
        "from_stop": "Berato pilis (Kalaja e Beratit)",
        "to_stop": "Goricos tiltas ir kvartalas",
        "mode": "walk",
        "distance_km": 0.6,
        "minutes": 9,
        "transit_kind": "",
        "transit": "",
        "road": "pėsčiomis žemyn nuo pilies prie Goricos tilto",
        "icon": "🚶"
      },
      {
        "day": 2,
        "from_stop": "Goricos tiltas ir kvartalas",
        "to_stop": "DD Villa",
        "mode": "walk",
        "distance_km": 0.8,
        "minutes": 10,
        "transit_kind": "",
        "transit": "",
        "road": "pėsčiomis per tiltą atgal į Mangalemo kvartalą",
        "icon": "🚶"
      },
      {
        "day": 3,
        "from_stop": "Osumio kanjono apžvalgos aikštelė",
        "to_stop": "Pietūs Vlorės marina",
        "mode": "car",
        "distance_km": 153.0,
        "minutes": 171,
        "transit_kind": "",
        "transit": "",
        "road": "asfaltuotas kelias atgal pro Beratą ir toliau per Fierą (greitkelis) į Vlorę",
        "icon": "🚗"
      },
      {
        "day": 3,
        "from_stop": "Pietūs Vlorės marina",
        "to_stop": "Vlorės pakrantės promenada (Lungomare)",
        "mode": "walk",
        "distance_km": 0.0,
        "minutes": 1,
        "transit_kind": "",
        "transit": "",
        "road": "ta pati vieta Vlorės uoste",
        "icon": "🚶"
      },
      {
        "day": 3,
        "from_stop": "Vlorės pakrantės promenada (Lungomare)",
        "to_stop": "Hotel Liro – Adults Only",
        "mode": "car",
        "distance_km": 0.3,
        "minutes": 1,
        "transit_kind": "",
        "transit": "",
        "road": "ta pati vieta Vlorės pakrantėje",
        "icon": "🚗"
      },
      {
        "day": 4,
        "from_stop": "Karavastos lagūnos Lankytojų centras ir apžvalgos bokštas",
        "to_stop": "Pietūs Divjakės paplūdimyje",
        "mode":
… (sutrumpinta, iš viso 103650 simbolių)
```

Current page:
[HTML puslapis, 72 KB — nerodomas]

Reply with the complete HTML document itself as your entire answer, starting with <!DOCTYPE html>. Do not write files, and do not describe or summarise what you did.

</details>

<details><summary><b>Atsakymas</b></summary>

HTML puslapis sugeneruotas (72 KB).

</details>

### 10. Puslapis — 10:58:27 ✅

- **Modelis:** `claude-sonnet-5` · **Vykdė:** Native Claude (claude -p) · **Trukmė:** 376.8 s
- **Sistemos promptas:** `prompts/page_designer.md`

<details><summary><b>Užklausa</b></summary>

You are updating an already published trip page, not designing a new one. Below are the current page and the current data. Apply the listed changes and make every part of the page match the current data, but keep the design -- colors, layout, CSS, JS, section order -- and all wording that isn't affected exactly as it is. Keep the <!-- PACKING_LIST --> and <!-- TRIP_MAP --> lines where they are.

Changes:
Fix these review findings:
- Lili Homemade Food (Kur pavalgyti, Ką paragauti čia): show "Fërgesë (paprikų ir varškės troškinys)"
Updated data: Puslapis

**Current data:**

```json
{
  "language": "lt",
  "research": "# Research summary: Albania, TIA to TIA, 30 Oct – 2 Nov 2026 (4 people, nature focus)\n\n**Coverage:** Reddit is blocked for the crawler, and TripAdvisor forum threads returned 403. So I have no r/travel or r/albania posts and only TripAdvisor search snippets. Everything else comes from Wikivoyage, blogs and operator sites. Dates are the page's own date where visible, otherwise \"undated\". I did not verify any drive times myself.\n\n## 1. Candidate stops\n\n| # | Stop | Why recommended | Source (date) |\n|---|---|---|---|\n| 1 | **Berat** (UNESCO) | Ottoman old town, uncrowded off-season. About 2–3 h from Tirana. | [Wikivoyage Albania](https://en.wikivoyage.org/wiki/Albania) (undated); [TripAdvisor thread snippet](https://www.tripadvisor.com/ShowTopic-g294445-i4583-k6457473-Tirana_Berat_Gjirokastra_Saranda-Albania.html) (undated) |\n| 2 | **Osumi Canyon and Bogovë waterfall** (from Berat) | Best nature stop within reach of Berat. The road from Berat to Bogova village is paved (about 1 h), and a regular car is fine. The canyon viewpoint is reachable in a normal car, and the author parked at the top. | [Wander with Laura](https://wanderwithlaura.com/how-to-get-to-bogove-waterfall-and-osum-canyon/) (published Aug 2022, updated 10 Jan 2026) |\n| 3 | **Divjakë-Karavasta lagoon** (pelicans, flamingos) | Autumn is a best season for birds. About 1h40 from Tirana, 30 min north of Fier and Apollonia. | [Nomads Travel Guide](https://www.nomads-travel-guide.com/places/divjake-karavasta-national-park/) (undated); [Birdingplaces](https://www.birdingplaces.eu/en/birdingplaces/albania/divjake-karavasta-national-park) (undated) |\n| 4 | **Gjirokastër** (UNESCO) | Stone town, \"empty of summer crowds\" in November. About 3h20 from Tirana on Google, and about 4 h realistically. This is at your daily driving limit. | [thingstodoinalbania](https://thingstodoinalbania.com/month/november/) (undated); [TIC Rent Car](https://ticrentcar.com/tirana-to-gjirokastra/) (undated) |\n| 5 | **Blue Eye (Syri i Kaltër)** | Spring-fed pool, open year-round, 07:00–19:00, 50 LEK entry. It is 22 km from Sarandë and 35 km from Gjirokastër. The last 2 km of road are unpaved but \"doable\", followed by a 2 km walk. | [Laure Wanders](https://www.laurewanders.com/blue-eye-albania/) (29 Aug 2026) |\n| 6 | **Llogara Pass and Dhermi coast** | The old pass road is still open and paved. The new tunnel costs 250 LEK (from 16 Sep 2025) and saves about 30 min. Snow and ice risk is Dec–Feb, so fine for early November, though fog and rain are possible. | [Explorer Tom](https://explorertom.com/en/llogara-pass-albania/) (11 Jun 2026) |\n| 7 | **Shkodër, Rozafa Castle, Lake Shkodra** | Easy northern option, about 1h47 from Tirana on the A1. | [Travelmath / ViaMichelin results](https://www.travelmath.com/driving-time/from/Shkoder,+Albania/to/Tirana,+Albania) (undated) |\n| 8 | **Komani Lake ferry** (Koman to Fierza) | The most scenic northern option. See the caveats in section 2. | [Ferry operator](https://komanilakeferry.com/timetables-and-prices/) (undated) |\n| 9 | **Bënja thermal baths / Përmet / Vjosa valley** | About 1h15 north of Gjirokastër, on the paved main road. Year-round, and best in cold weather. | [Vjosa Rafting guide](https://vjosarafting.com/benja-thermal-baths-permet/) and [Himara.net](https://himara.net/blog/benja-thermal-baths-destination-guide) (both undated) |\n| 10 | Pogradec / Lake Ohrid (Albanian side) | Low confidence. It is 2.5–3 h from Tirana. I found nothing on Korçë or Voskopojë in autumn. | [Explorer Tom](https://explorertom.com/en/lake-ohrid-albanian-side/) (undated) |\n\n**Overrated or skippable:**\n- **Ksamil and the Riviera beach towns:** described as overrun and overpriced in season. In late October the coast is mostly shuttered, with Ksamil and Dhermi venues closed and \"finding restaurants between Vlorë and Sarandë is challenging\" ([thingstodoinalbania](https://thingstodoinalbania.com/month/november/), undated). Himarë is \"empty by end of October\" per a TripAdvisor snippet (undated).\n- **Bovilla lake and Dajti:** the Dajti cable car is closed on Tuesdays. Your dates fall on Fri–Mon, so this doesn't matter ([TripAdvisor FAQ](https://www.tripadvisor.com/FAQ-g294445-d4573567-Dajti_Ekspres_Cable_Car.html)).\n- **Not found:** I found no sourced opinion on Bunk'Art, Blloku or Durrës. Treat those as unresearched.\n\n## 2. Road and logistics warnings\n\n**Roads to exclude for a standard rental car** (all from [Localrent \"Prohibited routes\"](https://www.localrent.com/en/journal/albania/articles/prohibited-routes/), undated with 2023 file metadata):\n- **SH74 Berat–Përmet:** \"narrow unpaved mountain road covered with small stones\". This is the one your earlier projects flagged.\n- **Berat–Përmet through Osumi Canyon:** unpaved with potholes and large puddles.\n- **Memaliaj–Berat (Martallozi):** unpaved.\n- **Tirana–Qafë-Shtamë via Lake Bovilla:** unpaved serpentine. A regular car can reach the dam, but not beyond ([Localrent](https://www.localrent.com/en/journal/albania/articles/prohibited-routes/) and search results, undated).\n- **Krujë–Burreli:** \"terrible state of disrepair\".\n- **Theth–Valbona:** already excluded by you.\n- **Beach access roads off SH8:** unpaved.\n\nOsumi Canyon is fine only when approached from Berat, so don't continue from it onward to Përmet.\n\n**Komani ferry caveats:**\n- **Season end is unclear.** The operator says 15 Apr to 5 Nov, so 30 Oct – 2 Nov is inside the season. A search snippet from another page said 2 Nov, which I could not verify. Confirm directly with the operator.\n- **Timetable:** Koman 09:00 to Fierza (about 2.5 h), and Fierza 13:00 back to Koman ([operator](https://komanilakeferry.com/timetables-and-prices/); [Explorer Tom](https://explorertom.com/en/koman-lake-ferry-guide/), 2026).\n- **A same-day round trip returns after dark.** By my own arithmetic, the boat is back at Koman about 15:30, plus at least 2 h to Shkodër gives about 17:30, after sunset. This is my calculation, not from a source. It suggests sleeping near Shkodër or Koman.\n- **The car does not need to cross.** The ferry is a dead end, so you would leave the car at Koman and go as foot passengers. That avoids the vehicle-booking problem below.\n- **Car on the ferry:** online pre-booking is essential, priced at €7/m² ([Explorer Tom](https://explorertom.com/en/koman-lake-ferry-guide/)). One traveller in Nov 2025 had to upgrade to an SUV because of rental-company restrictions ([Perchance to Roam](https://perchancetoroam.com/2025/11/01/a-complete-guide-to-taking-albanias-komani-lake-ferry-with-or-without-a-car/), 1 Nov 2025). Check the rental terms.\n- **Road Shkodër to Koman (SH25):** about 60 km and about 2 h, with a narrow one-lane tunnel near the terminal ([Explorer Tom](https://explorertom.com/en/koman-lake-ferry-guide/)). It was in poor shape in Nov 2025, with the last 10 km \"completely ripped open\" ([Perchance to Roam](https://perchancetoroam.com/2025/11/01/a-complete-guide-to-taking-albanias-komani-lake-ferry-with-or-without-a-car/)). [inAlbania](https://www.inalbania.info/koman-road-transformed-to-boost-tourism-in-northern-albania/) (15 Sep 2026) reports the Vau i Dejës–Koman reconstruction as completed. It gives no surface or tunnel details, and the government page I tried to fetch was empty. I'd call this likely improved but not confirmed.\n\n**General driving:**\n- **Time estimates:** Google Maps underestimates mountain roads. Add 25% (\"2 h shows, allow 2.5\", [Endless Travellers](https://theendlesstravellers.com/driving-in-albania/), updated 22 Feb 2026). Tirana to Theth shows 3.5 h but takes about 5 h ([Along Dusty Roads](https://www.alongdustyroads.com/posts/driving-in-albania-car-hire), updated Jun 2025).\n- **Night driving:** avoid it. Village roads are unlit, with livestock and pedestrians (same Along Dusty Roads and Wikivoyage sources). You land at 20:30 on Friday, so keep the first night's drive short, and check that the rental desk is open at that hour (not researched).\n- **Flash floods:** flash flooding is possible in the Vjosa and Osum valleys after heavy rain, and the Lengarica canyon is inaccessible after heavy rain ([thingstodoinalbania](https://thingstodoinalbania.com/month/november/), undated, single source).\n- **Tolls:** the Llogara Tunnel and the A1 to Kosovo are tolled ([Endless Travellers](https://theendlesstravellers.com/driving-in-albania/)).\n- **Rules:** police speed checks are frequent, alcohol limit is 0.01% ([Wikivoyage](https://en.wikivoyage.org/wiki/Albania)).\n\n## 3. Seasonal notes (30 Oct – 2 Nov)\n\n- **Rain:** November is the rainiest month, about 12 rain days and 180 mm, with roughly 12–15 °C average temperatures ([Climates to Travel](https://www.climatestotravel.com/weatherbymonth/albania/november) and similar, undated).\n- **Unreliable figure:** thingstodoinalbania claims 25 °C highs and 2 in of rain in November. That contradicts every other source, so don't use its numbers.\n- **Snow:** snow is possible above 1,500 m before mid-November. Theth/Valbona is snow-covered ([thingstodoinalbania](https://thingstodoinalbania.com/month/november/), undated, single source).\n- **Fog:** persistent morning fog on Lake Shkodra and in the Korçë basin (same source).\n- **Lake Shkodra boats:** schedules shrink to weekends only (same source, unconfirmed). Your Sat and Sun fall on weekends.\n- **Daylight:** sources give sunset of 16:45–17:25 (Wanderlog and others, undated). Their sunrise figure of 05:46 is implausible, so I don't trust them. My own rough estimate for Tirana (CET, after clocks change on 25 Oct) is sunset about 16:30–16:40. That is earlier than your 17:00–17:30 assumption. The Weather/Season Agent should check this with Open-Meteo.\n- **Calendar:** 30 Oct is a Friday and 2 Nov a Monday, so the trip has two full days (Sat, Sun) plus the Friday-night arrival and the Monday return. Monday needs the car back at TIA by about 17:00.\n\n## 4. Route shapes for the Logistics Validator (not validated)\n\n- **Central/south:** Fri night near Tirana or Durrës. Sat via Karavasta and Apollonia to Berat. Sun via Osumi and Bogova to Gjirokastër. Mon Gjirokastër to TIA at about 3.5–4 h. The last leg is the tightest, needing an early start. Blue Eye and Përmet do not fit without dropping something.\n- **North (easier):** Fri night Tirana. Sat Shkodër, Rozafa and the lake. Sun Komani ferry from a Shkodër or Koman base. Mon return via the A1 (about 1h47).\n\nBoth fit the 3.5–4 h limit only if the Validator confirms the legs. The central/south option depends on avoiding SH74 and the Berat–Përmet canyon road.\n\n## 5. Gaps to close\n\n- Direct confirmation of the Komani ferry season end and whether foot passengers can get a seat in early November.\n- Rental terms: a 4-person vehicle, ferry carriage, and the airport desk's opening hours after a 20:30 landing.\n- Osumi Canyon water levels and access in early November. The one detailed source visited in summer.\n- Korçë and Voskopojë autumn conditions, if you want a southeastern alternative.",
  "accommodation": "## Nakvynės vietos (tik užsakytos)\n\nKeliautojas jau užsakė ir patvirtino konkrečius nakvynės objektus per booking.com nuorodas. Žemiau — tik šios užsakytos vietos, be papildomų alternatyvų.\n\n### 1. Tirana (penktadienis, 2026-10-30 → šeštadienis, 2026-10-31)\n\n**✅ Užsakyta — Hanna Apartment** — **51 €/naktį**\n- Rruga e Elbasanit, Tirana. Įvertinimas 9.0/10 (186 atsiliepimai).\n- Kondicionierius, nemokamas WiFi. Tinka 4 žmonėms (butas).\n- Nuoroda: https://www.booking.com/hotel/al/apartament-tirana8.lt.html\n\n### 2. Beratas (šeštadienis, 2026-10-31 → sekmadienis, 2026-11-01)\n\n**✅ Užsakyta — DD Villa** — **61 €/naktį**\n- Rruga Antipatrea, Beratas. Įvertinimas 8.8/10 (667 atsiliepimai).\n- Sodas, baras, bendra svetainė, miesto vaizdas, pusryčiai (bufetas/à la carte), privatus parkavimas (už papildomą mokestį), restoranas vietoje.\n- Nuoroda: https://www.booking.com/hotel/al/dd-villa.lt.html\n\n### 3. Vlorė / Radhimė (sekmadienis, 2026-11-01 → pirmadienis, 2026-11-02)\n\n**✅ Užsakyta — Hotel Liro – Adults Only** — **117 €/naktį**\n- Aleksandër Moisiu Street, Vlorė. Įvertinimas 8.6/10 (1295 atsiliepimai).\n- Privatus paplūdimio ruožas, lauko baseinas, nemokamas parkavimas, restoranas/baras, pusryčiai, vaizdas į jūrą nuo balkono. Autobusų stotelė priešais viešbutį.\n- Nuoroda: https://www.booking.com/hotel/al/liro.lt.html\n- ⚠️ Pastaba: \"Adults Only\" — jei grupėje yra vaikų, šią vietą reikėtų pakeisti.\n\n**Biudžeto suma nakvynėms (3 naktys, visai grupei):** 51 + 61 + 117 = **229 €**",
  "booking_search": [
    {
      "city": "Tirana",
      "name": "Hanna Apartment",
      "checkin": "2026-10-30",
      "checkout": "2026-10-31",
      "nights": 1,
      "price_per_night_eur": 51,
      "url": "https://www.booking.com/searchresults.html?ss=Hanna+Apartment%2C+Tirana&checkin=2026-10-30&checkout=2026-10-31&group_adults=4&group_children=0&no_rooms=1"
    },
    {
      "city": "Berat",
      "name": "DD Villa",
      "checkin": "2026-10-31",
      "checkout": "2026-11-01",
      "nights": 1,
      "price_per_night_eur": 61,
      "url": "https://www.booking.com/searchresults.html?ss=DD+Villa%2C+Berat&checkin=2026-10-31&checkout=2026-11-01&group_adults=4&group_children=0&no_rooms=1"
    },
    {
      "city": "Vlorë",
      "name": "Hotel Liro - Adults Only",
      "checkin": "2026-11-01",
      "checkout": "2026-11-02",
      "nights": 1,
      "price_per_night_eur": 117,
      "url": "https://www.booking.com/searchresults.html?ss=Hotel+Liro+-+Adults+Only%2C+Vlor%C3%AB&checkin=2026-11-01&checkout=2026-11-02&group_adults=4&group_children=0&no_rooms=1"
    }
  ],
  "stays": [
    {
      "url": "https://www.booking.com/hotel/al/apartament-tirana8.lt.html",
      "name": "Hanna Apartment",
      "address": "Rruga e Elbasanit, 1035 Tirana, Albanija, 1035, Rruga e Elbasanit, Albanija",
      "description": "Hanna Apartment is located in Tirana. This apartment provides air-conditioned accommodation with free WiFi.",
      "full_description": null,
      "facilities": null,
      "rating": 9.0,
      "rating_scale": 10,
      "review_count": 186,
      "photo_urls": [
        "https://cf.bstatic.com/xdata/images/hotel/max1024x768/633887464.jpg?k=b976c4febe171b551f477e9eee870608b6dc963117d876c793f0d9f4e74a10c1&o=&hp=1",
        "https://cf.bstatic.com/xdata/images/hotel/max1024x768/633887550.jpg?k=694dc1002849285d2f750017340c1edd34a96dd80c7fbc5b6481ab43eadda7c0&o=&hp=1",
        "https://cf.bstatic.com/xdata/images/hotel/max1024x768/633887291.jpg?k=4963ffaa4c10e0fd9f47b51e58b930fc53eff67747c24a914957854aecfefbc0&o=&hp=1",
        "https://cf.bstatic.com/xdata/images/hotel/max1024x768/633889677.jpg?k=5da3b33dfa81e6240d74fe7d36bf94844df25d861a8cfb0f6e6d273f1eb9459a&o=&hp=1",
        "https://cf.bstatic.com/xdata/images/hotel/max1024x768/651343123.jpg?k=5441b1e29d0d9b0725ae1274688a078b2e764fba7c641900e5a8cc9a87c5bc84&o=&hp=1"
      ],
      "photos": [
        {
          "stop_name": "Hanna Apartment",
          "local_path": "images/stay-hanna-apartment-1.jpg",
          "commons_filename": "",
          "license": "© apgyvendinimo įstaiga / Booking.com",
          "author": null,
          "source_url": "https://www.booking.com/hotel/al/apartament-tirana8.lt.html",
          "size_bytes": 110275
        },
        {
          "stop_name": "Hanna Apartment",
          "local_path": "images/stay-hanna-apartment-2.jpg",
          "commons_filename": "",
          "license": "© apgyvendinimo įstaiga / Booking.com",
          "author": null,
          "source_url": "https://www.booking.com/hotel/al/apartament-tirana8.lt.html",
          "size_bytes": 32003
        },
        {
          "stop_name": "Hanna Apartment",
          "local_path": "images/stay-hanna-apartment-3.jpg",
          "commons_filename": "",
          "license": "© apgyvendinimo įstaiga / Booking.com",
          "author": null,
          "source_url": "https://www.booking.com/hotel/al/apartament-tirana8.lt.html",
          "size_bytes": 55703
        },
        {
          "stop_name": "Hanna Apartment",
          "local_path": "images/stay-hanna-apartment-4.jpg",
          "commons_filename": "",
          "license": "© apgyvendinimo įstaiga / Booking.com",
          "author": null,
          "source_url": "https://www.booking.com/hotel/al/apartament-tirana8.lt.html",
          "size_bytes": 53502
        },
        {
          "stop_name": "Hanna Apartment",
          "local_path": "images/stay-hanna-apartment-5.jpg",
          "commons_filename": "",
          "license": "© apgyvendinimo įstaiga / Booking.com",
          "author": null,
          "source_url": "https://www.booking.com/hotel/al/apartament-tirana8.lt.html",
          "size_bytes": 54202
        }
      ]
    },
    {
      "url": "https://www.booking.com/hotel/al/dd-villa.lt.html",
      "name": "DD Villa",
      "address": "Rruga Antipatrea, 5001 Beratis, Albanija, 5001, Rruga Antipatrea, Albanija",
      "description": "Situated in Berat, DD Villa features a garden, a bar and a shared lounge. The property has city views. Private parking can be arranged at an extra charge.",
      "full_description": [
        "Situated in Berat, DD Villa features a garden, a bar and a shared lounge. The property has city views. Private parking can be arranged at an extra charge. The bed and breakfast will provide guests with air-conditioned units offering a wardrobe, a kettle, a dishwasher, a microwave, a safety deposit box, a flat-screen TV and a private bathroom with a bidet. Free WiFi is accessible to all guests, while certain rooms are equipped with a terrace. At the bed and breakfast, every unit is equipped with bed linen and towels. A buffet, à la carte or continental breakfast is available at the property. Guests are welcome to eat in the on-site family-friendly restaurant, which is open for dinner, lunch, brunch and high tea. Sightseeing tours are available around the property. Both a bicycle rental service and a car rental service are available at the bed and breakfast, while cycling can be enjoyed nearby. Tirana International Mother Teresa Airport is 120 km from the property, and the property offers a paid airport shuttle service."
      ],
      "facilities": [
        "Populiariausi patogumai",
        "Privati automobilių stovėjimo aikštelė",
        "Spartus nemokamas belaidis internetas (101 Mbps)",
        "Pervežimas iš / į oro uostą",
        "Numeriai nerūkantiems",
        "Numeriai šeimai",
        "Aptarnavimas numeriuose",
        "Restoranas",
        "Baras",
        "Nuostabūs pusryčiai"
      ],
      "rating": 8.8,
      "rating_scale": 10,
      "review_count": 667,
      "photo_urls": [
        "https://cf.bstatic.com/xdata/images/hotel/max1024x768/529582807.jpg?k=731fe174d8d2b7402280e7c8008fdd355a874d76e0b7f03f1f516ad3c92ccd4f&o=&hp=1",
        "https://cf.bstatic.com/xdata/images/hotel/max1024x768/921271115.jpg?k=714680e569beb3f835a5ab5f15daaf4460dda2cd2509890599543048e17af49a&o=&hp=1",
        "https://cf.bstatic.com/xdata/images/hotel/max1024x768/529582816.jpg?k=8c6581a00d3c484f9e62bbaa3ba21bf08b13e50ccda4cf1e32c52876fb08a13d&o=&hp=1",
        "https://cf.bstatic.com/xdata/images/hotel/max1024x768/544036358.jpg?k=03e5cee7c142331675268001c541cbe0e4cb64ba67f8d850dc1cf05be6ee1024&o=&hp=1",
        "https://cf.bstatic.com/xdata/images/hotel/max1024x768/529582821.jpg?k=58830e6a252b81f2a06faccae174fad12a474f063ed8162b382a1ac3626b93d9&o=&hp=1"
      ],
      "photos": [
        {
          "stop_name": "DD Villa",
          "local_path": "images/stay-dd-villa-1.jpg",
          "commons_filename": "",
          "license": "© apgyvendinimo įstaiga / Booking.com",
          "author": null,
          "source_url": "https://www.booking.com/hotel/al/dd-villa.lt.html",
          "size_bytes": 154626
        },
        {
          "stop_name": "DD Villa",
          "local_path": "images/stay-dd-villa-2.jpg",
          "commons_filename": "",
          "license": "© apgyvendinimo įstaiga / Booking.com",
          "author": null,
          "source_url": "https://www.booking.com/hotel/al/dd-villa.lt.html",
          "size_bytes": 69651
        },
        {
          "stop_name": "DD Villa",
          "local_path": "images/stay-dd-villa-3.jpg",
          "commons_filename": "",
          "license": "© apgyvendinimo įstaiga / Booking.com",
          "author": null,
          "source_url": "https://www.booking.com/hotel/al/dd-villa.lt.html",
          "size_bytes": 99758
        },
        {
          "stop_name": "DD Villa",
          "local_path": "images/stay-dd-villa-4.jpg",
          "commons_filename": "",
          "license": "© apgyvendinimo įstaiga / Booking.com",
          "author": null,
          "source_url": "https://www.booking.com/hotel/al/dd-villa.lt.html",
          "size_bytes": 99712
        },
        {
          "stop_name": "DD Villa",
          "local_path": "images/stay-dd-villa-5.jpg",
          "commons_filename": "",
          "license": "© apgyvendinimo įstaiga / Booking.com",
          "author": null,
          "source_url": "https://www.booking.com/hotel/al/dd-villa.lt.html",
          "size_bytes": 129326
        }
      ]
    },
    {
      "url": "https://www.booking.com/hotel/al/liro.lt.html",
      "name": "Hotel Liro - Adults Only",
      "address": "Aleksandër Moisiu Street, 9405 Vliorė, Albanija, 9405, Aleksandër Moisiu Street, Albanija",
      "description": "Located in Vlorë, Hotel Liro - Adults Only offers a private beach area with free-to-use sun loungers and parasols.",
      "full_description": [
        "Located in Vlorë, Hotel Liro - Adults Only offers a private beach area with free-to-use sun loungers and parasols. The on-site bar and restaurant offers a spacious terrace where guests can enjoy the Mediterranean dishes it serves. Free WiFi access is available throughout the property. All the rooms are air-conditioned and come with a furnished balcony overlooking the sea. Each room is equipped with satellite TV, a minibar and a safe. Featuring a shower, private bathrooms also come with a hairdryer and free toiletries. Hotel Liro - Adults Only offers an array of activities can be enjoyed on site or in the surroundings, including windsurfing. The cenre of Vlorë and the scenic outlook of Kuzum Baba can be found within a 6-km radius. The Archaeological Park of Oricum is 10 km from Liro Hotel. Llogara National Park is 25 km away. The local bus stop is right in front of the hotel. Tirana Airport is 150 km away. The property offers free parking."
      ],
      "facilities": [
        "Populiariausi patogumai",
        "Lauko baseinas",
        "Nemokama vieta automobiliui",
        "Šalia paplūdimio",
        "Nemokamas belaidis internetas",
        "Numeriai šeimai",
        "Restoranas",
        "Numeriai nerūkantiems",
        "Baras",
        "Privati paplūdimio dalis",
        "Nuostabūs pusryčiai"
      ],
      "rating": 8.6,
      "rating_scale": 10,
      "review_count": 1295,
      "photo_urls": [
        "https://cf.bstatic.com/xdata/images/hotel/max1024x768/506995294.jpg?k=23925d61528b241c35e7b43446d3f11a9faa202b08e9903c82a6e3cb2afa43d7&o=&hp=1",
        "https://cf.bstatic.com/xdata/images/hotel/max1024x768/506995475.jpg?k=8b2bd840a2ed21d4d6da7442afc978dd5073fc1eb1d9a567413fdab748546eac&o=&hp=1",
        "https://cf.bstatic.com/xdata/images/hotel/max1024x768/556057394.jpg?k=575cc81ebc625197b6b6c6af18c2ec9a6eda54fa3ed14e29ecef4935b13b27a6&o=&hp=1",
        "https://cf.bstatic.com/xdata/images/hotel/max1024x768/506995518.jpg?k=2db992e93cda20eb611af0c65c6d59f388efc2150e468dfbfae8e8e3fbb3b665&o=&hp=1",
        "https://cf.bstatic.com/xdata/images/hotel/max1024x768/506995661.jpg?k=d3755c0ed1215710923e75d5050056023d41ecd92820d69af21aa384123992dd&o=&hp=1"
      ],
      "photos": [
        {
          "stop_name": "Hotel Liro - Adults Only",
          "local_path": "images/stay-hotel-liro-adults-only-1.jpg",
          "commons_filename": "",
          "license": "© apgyvendinimo įstaiga / Booking.com",
          "author": null,
          "source_url": "https://www.booking.com/hotel/al/liro.lt.html",
          "size_bytes": 125824
        },
        {
          "stop_name": "Hotel Liro - Adults Only",
          "local_path": "images/stay-hotel-liro-adults-only-2.jpg",
          "commons_filename": "",
          "license": "© apgyvendinimo įstaiga / Booking.com",
          "author": null,
          "source_url": "https://www.booking.com/hotel/al/liro.lt.html",
          "size_bytes": 238091
        },
        {
          "stop_name": "Hotel Liro - Adults Only",
          "local_path": "images/stay-hotel-liro-adults-only-3.jpg",
          "commons_filename": "",
          "license": "© apgyvendinimo įstaiga / Booking.com",
          "author": null,
          "source_url": "https://www.booking.com/hotel/al/liro.lt.html",
          "size_bytes": 133915
        },
        {
          "stop_name": "Hotel Liro - Adults Only",
          "local_path": "images/stay-hotel-liro-adults-only-4.jpg",
          "commons_filename": "",
          "license": "© apgyvendinimo įstaiga / Booking.com",
          "author": null,
          "source_url": "https://www.booking.com/hotel/al/liro.lt.html",
          "size_bytes": 211665
        },
        {
          "stop_name": "Hotel Liro - Adults Only",
          "local_path": "images/stay-hotel-liro-adults-only-5.jpg",
          "commons_filename": "",
          "license": "© apgyvendinimo įstaiga / Booking.com",
          "author": null,
          "source_url": "https://www.booking.com/hotel/al/liro.lt.html",
          "size_bytes": 64880
        }
      ]
    }
  ],
  "itinerary": "{\"days\":[{\"number\":1,\"title\":\"Atvykimas į Tiraną\",\"stops\":[{\"name\":\"Tiranos oro uostas (TIA)\",\"lat\":41.4147,\"lon\":19.7206,\"arrive\":\"20:30\",\"depart\":\"21:00\",\"maps_query\":\"Tirana International Airport Nënë Tereza, Albania\",\"google_maps_url\":\"https://www.google.com/maps/search/?api=1&query=Tirana%20International%20Airport%20N%C3%ABn%C3%AB%20Tereza%2C%20Albania\",\"notes\":\"Skrydis iš Varšuvos nusileidžia 20:30. Automobilio nuomos (VW Tiguan ar panašus visureigis, tinka 4 žmonėms ir bagažui, su Papildomo vairuotojo ir pilnos apsaugos draudimu) atsiėmimas 21:00. Tą pačią vietą reikės grąžinti automobilį lapkričio 2 d. iki 17:00.\",\"arrive_by\":\"car\",\"transit\":\"\"},{\"name\":\"Hanna Apartment\",\"lat\":41.3192,\"lon\":19.8294,\"arrive\":\"21:20\",\"depart\":\"21:20\",\"maps_query\":\"Apartament Tirana8, Rruga e Elbasanit, Tirana, Albania\",\"google_maps_url\":\"https://www.google.com/maps/search/?api=1&query=Apartament%20Tirana8%2C%20Rruga%20e%20Elbasanit%2C%20Tirana%2C%20Albania\",\"notes\":\"Pirma nakvynė – butas Rruga e Elbasanit, kondicionierius, nemokamas WiFi, tinka 4 žmonėms. Kelias nuo oro uosto apie 20 min, vėlai vakare eismas ramus.\",\"arrive_by\":\"car\",\"transit\":\"\"}],\"driving_minutes\":20,\"overnight_city\":\"Tirana\"},{\"number\":2,\"title\":\"Krujė, Belšo ežeras ir Beratas\",\"stops\":[{\"name\":\"Krujos pilis ir Skenderbego muziejus bei Senasis bazaras\",\"lat\":41.5086,\"lon\":19.7919,\"arrive\":\"09:45\",\"depart\":\"10:30\",\"maps_query\":\"Kalaja e Krujës, Krujë, Albania\",\"google_maps_url\":\"https://www.google.com/maps/search/?api=1&query=Kalaja%20e%20Kruj%C3%ABs%2C%20Kruj%C3%AB%2C%20Albania\",\"notes\":\"Skenderbego muziejus pilies viduje, bilietas apie 200 lekų (~2 €). Žiemos darbo laikas apytiksliai 09:00–16:00 – darbo laiką verta pasitikrinti. Prie pilies – senasis bazaras su amatininkų dirbiniais ir suvenyrais.\",\"arrive_by\":\"car\",\"transit\":\"\"},{\"name\":\"Belšo ežeras (apžvalgos sustojimas)\",\"lat\":41.0931,\"lon\":19.8828,\"arrive\":\"12:02\",\"depart\":\"12:17\",\"maps_query\":\"Liqeni i Belshit, Belsh, Albania\",\"google_maps_url\":\"https://www.google.com/maps/search/?api=1&query=Liqeni%20i%20Belshit%2C%20Belsh%2C%20Albania\",\"notes\":\"Trumpas sustojimas pakeliui – gražus Dumrės plokščiakalnio ir ežerų vaizdas, proga kavai ir nuotraukai.\",\"arrive_by\":\"car\",\"transit\":\"\"},{\"name\":\"Pietūs „Lili Homemade Food“\",\"lat\":40.7064,\"lon\":19.9513,\"arrive\":\"13:54\",\"depart\":\"14:55\",\"maps_query\":\"Lili Homemade Food, Berat, Albania\",\"google_maps_url\":\"https://www.google.com/maps/search/?api=1&query=Lili%20Homemade%20Food%2C%20Berat%2C%20Albania\",\"notes\":\"Populiarus namų virtuvės restoranas Mangalemo kvartale, vietiniai patiekalai.\",\"arrive_by\":\"car\",\"transit\":\"\"},{\"name\":\"Mangalemo senasis kvartalas\",\"lat\":40.706,\"lon\":19.951,\"arrive\":\"14:55\",\"depart\":\"15:09\",\"maps_query\":\"Mangalem Quarter, Berat, Albania\",\"google_maps_url\":\"https://www.google.com/maps/search/?api=1&query=Mangalem%20Quarter%2C%20Berat%2C%20Albania\",\"notes\":\"Pasivaikščiojimas osmanų laikų gatvelėmis su garsiaisiais „tūkstančio langų“ namais.\",\"arrive_by\":\"walk\",\"transit\":\"\"},{\"name\":\"Berato pilis (Kalaja e Beratit)\",\"lat\":40.7014,\"lon\":19.9447,\"arrive\":\"15:29\",\"depart\":\"16:13\",\"maps_query\":\"Kalaja e Beratit, Berat, Albania\",\"google_maps_url\":\"https://www.google.com/maps/search/?api=1&query=Kalaja%20e%20Beratit%2C%20Berat%2C%20Albania\",\"notes\":\"Gyvenama pilis su bizantiškomis bažnyčiomis. Įėjimas į teritoriją laisvas, Onufrijaus muziejuje bilietas apie 200 lekų – darbo laiką verta pasitikrinti.\",\"arrive_by\":\"walk\",\"transit\":\"\"},{\"name\":\"Goricos tiltas ir kvartalas\",\"lat\":40.7021,\"lon\":19.9497,\"arrive\":\"16:38\",\"depart\":\"17:08\",\"maps_query\":\"Ura e Goricës, Berat, Albania\",\"google_maps_url\":\"https://www.google.com/maps/search/?api=1&query=Ura%20e%20Goric%C3%ABs%2C%20Berat%2C%20Albania\",\"notes\":\"Osmanų laikų akmeninis tiltas per Osumo upę – ypač gražus prieblandoje, puikus vaizdas į Mangalemą.\",\"arrive_by\":\"walk\",\"transit\":\"\"},{\"name\":\"DD Villa\",\"lat\":40.7057,\"lon\":19.952,\"arrive\":\"17:23\",\"depart\":\"17:23\",\"maps_query\":\"DD Villa, Rruga Antipatrea, Berat, Albania\",\"google_maps_url\":\"https://www.google.com/maps/search/?api=1&query=DD%20Villa%2C%20Rruga%20Antipatrea%2C%20Berat%2C%20Albania\",\"notes\":\"Nakvynė Berate – sodas, baras, pusryčiai, privatus parkavimas už papildomą mokestį.\",\"arrive_by\":\"walk\",\"transit\":\"\"}],\"driving_minutes\":180,\"overnight_city\":\"Berat\"},{\"number\":3,\"title\":\"Osumio kanjonas ir Vlorės pakrantė\",\"stops\":[{\"name\":\"Osumio kanjono apžvalgos aikštelė\",\"lat\":40.5044,\"lon\":20.227,\"arrive\":\"10:15\",\"depart\":\"11:00\",\"maps_query\":\"Kanioni i Osumit, Çorovodë, Albania\",\"google_maps_url\":\"https://www.google.com/maps/search/?api=1&query=Kanioni%20i%20Osumit%2C%20%C3%87orovod%C3%AB%2C%20Albania\",\"notes\":\"Vienas gražiausių gamtos vaizdų kelyje – kanjono apžvalgos aikštelė prie kelio, patogi stovėjimo vieta.\",\"arrive_by\":\"car\",\"transit\":\"\"},{\"name\":\"Pietūs Vlorės marina\",\"lat\":40.458,\"lon\":19.485,\"arrive\":\"13:51\",\"depart\":\"14:51\",\"maps_query\":\"Marina e Vlorës, Vlorë, Albania\",\"google_maps_url\":\"https://www.google.com/maps/search/?api=1&query=Marina%20e%20Vlor%C3%ABs%2C%20Vlor%C3%AB%2C%20Albania\",\"notes\":\"Vlorės uosto promenadoje daug žuvies restoranų – pasirinkite bet kurį su šviežia dienos žuvimi.\",\"arrive_by\":\"car\",\"transit\":\"\"},{\"name\":\"Vlorės pakrantės promenada (Lungomare)\",\"lat\":40.458,\"lon\":19.485,\"arrive\":\"14:51\",\"depart\":\"15:51\",\"maps_query\":\"Lungomare, Vlorë, Albania\",\"google_maps_url\":\"https://www.google.com/maps/search/?api=1&query=Lungomare%2C%20Vlor%C3%AB%2C%20Albania\",\"notes\":\"Pasivaikščiojimas pakrante, vaizdas į Jonų jūrą ir Sazano salą.\",\"arrive_by\":\"walk\",\"transit\":\"\"},{\"name\":\"Hotel Liro – Adults Only\",\"lat\":40.455,\"lon\":19.484,\"arrive\":\"16:01\",\"depart\":\"16:01\",\"maps_query\":\"Hotel Liro Adults Only, Rruga Aleksandër Moisiu, Vlorë, Albania\",\"google_maps_url\":\"https://www.google.com/maps/search/?api=1&query=Hotel%20Liro%20Adults%20Only%2C%20Rruga%20Aleksand%C3%ABr%20Moisiu%2C%20Vlor%C3%AB%2C%20Albania\",\"notes\":\"Nakvynė Vlorėje – privatus paplūdimio ruožas, lauko baseinas, vaizdas į jūrą nuo balkono. Tik suaugusiems.\",\"arrive_by\":\"car\",\"transit\":\"\"}],\"driving_minutes\":205,\"overnight_city\":\"Vlorë\"},{\"number\":4,\"title\":\"Divjakė-Karavasta ir išvykimas\",\"stops\":[{\"name\":\"Karavastos lagūnos Lankytojų centras ir apžvalgos bokštas\",\"lat\":40.979,\"lon\":19.466,\"arrive\":\"10:10\",\"depart\":\"13:20\",\"maps_query\":\"Qendra e Vizitorëve Divjakë-Karavasta, Divjakë, Albania\",\"google_maps_url\":\"https://www.google.com/maps/search/?api=1&query=Qendra%20e%20Vizitor%C3%ABve%20Divjak%C3%AB-Karavasta%2C%20Divjak%C3%AB%2C%20Albania\",\"notes\":\"Automobilį palikite Lankytojų centro aikštelėje – čia veda geras asfaltuotas/tvarkingas kelias, o čia pat yra apie 35 m aukščio apžvalgos bokštas su gražiu vaizdu į lagūną. Jei norite pasiekti giliau lagūnoje esantį bokštą, paskutinius 1–2 km (ir tiek pat atgal) reikia nueiti pėsčiomis – nuomotam automobiliui tas kelias po lietaus būna dumblinas ir netinkamas. Rudenį čia gerai matomi rausvieji pelikanai ir flamingai. Nedidelis mokestis automobiliui įvažiuojant į parką.\",\"arrive_by\":\"car\",\"transit\":\"\"},{\"name\":\"Pietūs Divjakės paplūdimyje\",\"lat\":40.9958,\"lon\":19.4705,\"arrive\":\"13:30\",\"depart\":\"14:30\",\"maps_query\":\"Plazhi i Divjakës, Divjakë, Albania\",\"google_maps_url\":\"https://www.google.com/maps/search/?api=1&query=Plazhi%20i%20Divjak%C3%ABs%2C%20Divjak%C3%AB%2C%20Albania\",\"notes\":\"Paplūdimio žuvies kioskai ir restoranėliai – šviežia žuvis ir jūros gėrybės.\",\"arrive_by\":\"car\",\"transit\":\"\"},{\"name\":\"Tiranos oro uostas (TIA) – automobilio grąžinimas ir skrydis namo\",\"lat\":41.4147,\"lon\":19.7206,\"arrive\":\"16:15\",\"depart\":\"19:05\",\"maps_query\":\"Tirana International Airport Nënë Tereza, Albania\",\"google_maps_url\":\"https://www.google.com/maps/search/?api=1&query=Tirana%20International%20Airport%20N%C3%ABn%C3%AB%20Tereza%2C%20Albania\",\"notes\":\"Automobilio grąžinimas (reikia iki 17:00) – atsargos laiko pakaks. Skrydis į Varšuvą išskrenda 19:05 – registracijai ir saugumo patikrai liks pakankamai laiko.\",\"arrive_by\":\"car\",\"transit\":\"\"}],\"driving_minutes\":170,\"overnight_city\":\"Nėra (skrydis namo)\"}]}",
  "day_routes": [
    {
      "day": 1,
      "title": "Atvykimas į Tiraną",
      "urls": [
        "https://www.google.com/maps/dir/?api=1&origin=Tirana+International+Airport+N%C3%ABn%C3%AB+Tereza,+Albania&destination=Apartament+Tirana8,+Rruga+e+Elbasanit,+Tirana,+Albania&travelmode=driving"
      ],
      "modes": [
        "car"
      ]
    },
    {
      "day": 2,
      "title": "Krujė, Belšo ežeras ir Beratas",
      "urls": [
        "https://www.google.com/maps/dir/?api=1&origin=Kalaja+e+Kruj%C3%ABs,+Kruj%C3%AB,+Albania&destination=Lili+Homemade+Food,+Berat,+Albania&travelmode=driving&waypoints=Liqeni+i+Belshit,+Belsh,+Albania",
        "https://www.google.com/maps/dir/?api=1&origin=Lili+Homemade+Food,+Berat,+Albania&destination=DD+Villa,+Rruga+Antipatrea,+Berat,+Albania&travelmode=walking&waypoints=Mangalem+Quarter,+Berat,+Albania|Kalaja+e+Beratit,+Berat,+Albania|Ura+e+Goric%C3%ABs,+Berat,+Albania"
      ],
      "modes": [
        "car",
        "walk"
      ]
    },
    {
      "day": 3,
      "title": "Osumio kanjonas ir Vlorės pakrantė",
      "urls": [
        "https://www.google.com/maps/dir/?api=1&origin=Kanioni+i+Osumit,+%C3%87orovod%C3%AB,+Albania&destination=Hotel+Liro+Adults+Only,+Rruga+Aleksand%C3%ABr+Moisiu,+Vlor%C3%AB,+Albania&travelmode=driving&waypoints=Marina+e+Vlor%C3%ABs,+Vlor%C3%AB,+Albania"
      ],
      "modes": [
        "car"
      ]
    },
    {
      "day": 4,
      "title": "Divjakė-Karavasta ir išvykimas",
      "urls": [
        "https://www.google.com/maps/dir/?api=1&origin=Qendra+e+Vizitor%C3%ABve+Divjak%C3%AB-Karavasta,+Divjak%C3%AB,+Albania&destination=Tirana+International+Airport+N%C3%ABn%C3%AB+Tereza,+Albania&travelmode=driving&waypoints=Plazhi+i+Divjak%C3%ABs,+Divjak%C3%AB,+Albania"
      ],
      "modes": [
        "car"
      ]
    }
  ],
  "logistics": {
    "legs": [
      {
        "day": 1,
        "from_stop": "Tiranos oro uostas (TIA)",
        "to_stop": "Hanna Apartment",
        "mode": "car",
        "distance_km": 19.0,
        "minutes": 31,
        "transit_kind": "",
        "transit": "",
        "road": "asfaltuotas kelias iš oro uosto į Tiraną, Rruga e Elbasanit rajoną, lygus reljefas",
        "icon": "🚗"
      },
      {
        "day": 2,
        "from_stop": "Krujos pilis ir Skenderbego muziejus bei Senasis bazaras",
        "to_stop": "Belšo ežeras (apžvalgos sustojimas)",
        "mode": "car",
        "distance_km": 91.0,
        "minutes": 92,
        "transit_kind": "",
        "transit": "",
        "road": "asfaltuotas kelias/greitkelis per Tiranos-Elbasano lygumą link Belšo",
        "icon": "🚗"
      },
      {
        "day": 2,
        "from_stop": "Belšo ežeras (apžvalgos sustojimas)",
        "to_stop": "Pietūs „Lili Homemade Food“",
        "mode": "car",
        "distance_km": 62.0,
        "minutes": 97,
        "transit_kind": "",
        "transit": "",
        "road": "asfaltuotas kelias per kalvas link Berato",
        "icon": "🚗"
      },
      {
        "day": 2,
        "from_stop": "Pietūs „Lili Homemade Food“",
        "to_stop": "Mangalemo senasis kvartalas",
        "mode": "walk",
        "distance_km": 0.1,
        "minutes": 1,
        "transit_kind": "",
        "transit": "",
        "road": "per senamiestį",
        "icon": "🚶"
      },
      {
        "day": 2,
        "from_stop": "Mangalemo senasis kvartalas",
        "to_stop": "Berato pilis (Kalaja e Beratit)",
        "mode": "walk",
        "distance_km": 1.0,
        "minutes": 14,
        "transit_kind": "",
        "transit": "",
        "road": "pėsčiųjų takas į kalvą prie pilies",
        "icon": "🚶"
      },
      {
        "day": 2,
        "from_stop": "Berato pilis (Kalaja e Beratit)",
        "to_stop": "Goricos tiltas ir kvartalas",
        "mode": "walk",
        "distance_km": 0.6,
        "minutes": 9,
        "transit_kind": "",
        "transit": "",
        "road": "pėsčiomis žemyn nuo pilies prie Goricos tilto",
        "icon": "🚶"
      },
      {
        "day": 2,
        "from_stop": "Goricos tiltas ir kvartalas",
        "to_stop": "DD Villa",
        "mode": "walk",
        "distance_km": 0.8,
        "minutes": 10,
        "transit_kind": "",
        "transit": "",
        "road": "pėsčiomis per tiltą atgal į Mangalemo kvartalą",
        "icon": "🚶"
      },
      {
        "day": 3,
        "from_stop": "Osumio kanjono apžvalgos aikštelė",
        "to_stop": "Pietūs Vlorės marina",
        "mode": "car",
        "distance_km": 153.0,
        "minutes": 171,
        "transit_kind": "",
        "transit": "",
        "road": "asfaltuotas kelias atgal pro Beratą ir toliau per Fierą (greitkelis) į Vlorę",
        "icon": "🚗"
      },
      {
        "day": 3,
        "from_stop": "Pietūs Vlorės marina",
        "to_stop": "Vlorės pakrantės promenada (Lungomare)",
        "mode": "walk",
        "distance_km": 0.0,
        "minutes": 1,
        "transit_kind": "",
        "transit": "",
        "road": "ta pati vieta Vlorės uoste",
        "icon": "🚶"
      },
      {
        "day": 3,
        "from_stop": "Vlorės pakrantės promenada (Lungomare)",
        "to_stop": "Hotel Liro – Adults Only",
        "mode": "car",
        "distance_km": 0.3,
        "minutes": 1,
        "transit_kind": "",
        "transit": "",
        "road": "ta pati vieta Vlorės pakrantėje",
        "icon": "🚗"
      },
      {
        "day": 4,
        "from_stop": "Karavastos lagūnos Lankytojų centras ir apžvalgos bokštas",
        "to_stop": "Pietūs Divjakės paplūdimyje",
        "mode":
… (sutrumpinta, iš viso 103650 simbolių)
```

Current page:
[HTML puslapis, 72 KB — nerodomas]

Reply with the complete HTML document itself as your entire answer, starting with <!DOCTYPE html>. Do not write files, and do not describe or summarise what you did.

</details>

<details><summary><b>Atsakymas</b></summary>

HTML puslapis sugeneruotas (72 KB).

</details>

