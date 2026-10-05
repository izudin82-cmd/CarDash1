# CarDash – Android OBD-II aplikacija

Jednostavna Android aplikacija koja prikazuje:

- **Brzinu** (km/h)
- **Temperaturu** rashladne tečnosti (°C)
- **Pređene kilometre**
- **Velike greške** (DTC kodove)

Ima i **Demo režim** da možeš da probaš bez OBD adaptera.

---

## Kako da dobiješ APK preko GitHub-a (preporučeno)

### 1. Napravi novi repository na GitHub-u
1. Idi na https://github.com/new
2. Repository name: `CarDash` (ili bilo šta)
3. Ostavi **Public**
4. **Ne** kvači "Add a README file"
5. Klikni **Create repository**

### 2. Uploaduj projekat
1. Na stranici novog repozitorijuma klikni **"uploading an existing file"**
2. Raspakuj `CarDash.zip` i prevuci **ceo sadržaj** foldera CarDash
3. Commit message: `Initial commit`
4. Klikni **Commit changes**

### 3. Sačekaj da se APK napravi
1. Idi na tab **Actions** (gore u meniju)
2. Klikni na workflow **Build APK**
3. Sačekaj 2–5 minuta dok ne postane zeleno
4. Kada završi, dole će pisati **Artifacts**
5. Klikni na **CarDash-APK** i preuzmi ZIP
6. Unutra je `.apk` fajl – prebaci na telefon i instaliraj

---

## Alternativa: Lokalno sa Android Studio
1. Otvori projekat u Android Studio
2. Build → Build Bundle(s) / APK(s) → Build APK(s)
3. APK se nalazi u `app/build/outputs/apk/debug/`

---

## Kako se koristi aplikacija
1. Upari OBD-II Bluetooth adapter sa telefonom
2. Ubaci adapter u auto
3. Upali kontakt / motor
4. Otvori app → **Poveži OBD** ili probaј **Demo režim**
