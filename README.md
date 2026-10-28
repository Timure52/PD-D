Timur Nefedov, Veronica Pilupa
🌲 1. Ievads un projekta vīzija
Laipni lūdzam Latvijas mežu projektu repozitorijā! Šī dokumentācija ir izstrādāta, lai sniegtu pilnīgu priekšstatu par mūsu iniciatīvu, kuras mērķis ir dokumentēt, analizēt un veicināt sabiedrības izpratni par Latvijas mežu bagātībām.

Latvija ir viena no zaļākajām un mežainākajām valstīm Eiropā — vairāk nekā puse no mūsu valsts teritorijas (ap 52%) ir klāta ar mežiem. Šis projekts kalpo kā digitāla platforma pētniekiem, dabas mīļotājiem, izstrādātājiem un vides aktīvistiem, kuri vēlas apvienot tehnoloģijas ar dabas zinātnēm. Mēs apkopojam ģeotelpiskos datus, veidojam floras un faunas katalogus, kā arī analizējam mežu ekosistēmu veselību un klimata pārmaiņu ietekmi.

📂 2. Repozitorija arhitektūra un struktūra
Mūsu projekts ir strukturēts tā, lai nodrošinātu ērtu koda uzturēšanu, datu glabāšanu un sadarbību starp dažādu jomu speciālistiem:

Plaintext
latvian-forests/
├── 📁 data/                  # Datu bāzes un ģeotelpiskie dati (GIS shapefiles, sugu saraksti)
├── 📁 docs/                  # Padziļināti ceļveži, pētījumi un metodoloģija
├── 📁 src/                   # Pirmkods (tīmekļa lietotnes, datu analīzes skripti Python/R)
├── 📁 assets/                # Multivides faili (kartes, fotogrāfijas, ikonas, logotipi)
├── 📁 scripts/               # Automatizācijas un datu apstrādes skripti
├── 📄 README.md              # Projekta galvenais apraksts un instrukcijas
├── 📄 CONTRIBUTING.md        # Detalizētas vadlīnijas jaunajiem dalībniekiem
├── 📄 CODE_OF_CONDUCT.md     # Kopienas ētikas kodekss
└── 📄 LICENSE                # Atvērtā pirmkoda licences noteikumi
🚀 3. Uzstādīšana un darba vides sagatavošana
Lai sāktu darbu ar projektu savā vietējā datorā, lūdzu, izpildiet šos soļus:

Sistēmas prasības
Pārliecinieties, ka jūsu datorā ir instalēti sekojoši rīki:

Git (versija 2.30 vai jaunāka)

Node.js (versija 18.x vai jaunāka) — tīmekļa saskarnes un rīku darbināšanai

Python (versija 3.10 vai jaunāka) — datu analīzei un ģeotelpiskajiem skriptiem

Instalācijas soļi
Klonējiet repozitoriju no GitHub:

Bash
git clone https://github.com/your-username/latvian-forests.git
Pārvietojieties uz projekta mapi:

Bash
cd latvian-forests
Instalējiet Node.js atkarības (ja strādājat ar frontend daļu):

Bash
npm install
Iestatiet Python virtuālo vidi un instalējiet datu bibliotēkas (ja nepieciešams):

Bash
python -m venv venv
source venv/bin/activate   # Uz Windows: venv\Scripts\activate
pip install -r requirements.txt
🗺️ 4. Galvenie moduļi un datu avoti
Projekts sastāv no vairākiem savstarpēji saistītiem virzieniem:

Mežu tipoloģija un kartēšana: Izmantojot satelītdatus un atvērtos ģeotelpiskos avotus, mēs izsekojam dažādu mežu tipu izplatību (priežu sils, egļu damji, ošauti, jauktie meži).

Bioloģiskā daudzveidība: Apkopoti dati par aizsargājamām sugām, mikroliegumiem un dabas parkiem, sadarbojoties ar publiski pieejamām dabas datu bāzēm (piemēram, Dabas dati).

Rekreācijas infrastruktūra: Apkopota informācija par tūrismmalām, pastaigu takām, skatu torņiem un labiekārtotām ugunskuru vietām, ko uztur AS "Latvijas Valsts meži" un Dabas aizsardzības pārvalde.

🤝 5. Kā pievienoties un piedalīties izstrādē?
Mēs ticam atvērtā koda un kopienas spēkam! Ja vēlaties palīdzēt projekta attīstībā:

Izveidojiet sava konta kopiju (Fork) šim repozitorijam.

Izveidojiet jaunu atzaru (branch) savam uzdevumam:

Bash
git checkout -b feature/SuguKatalogsUzlabojums
Veiciet nepieciešamās izmaiņas un saglabājiet tās:

Bash
git commit -m "Pievienoti jauni dati par priežu mežu aizsardzību"
Nosūtiet izmaiņas uz savu GitHub kontu:

Bash
git push origin feature/SuguKatalogsUzlabojums
Atveriet Pull Request mūsu galvenajā repozitorijā ar izmaiņu aprakstu.

Pirms koda iesniegšanas, lūdzu, iepazīstieties ar CONTRIBUTING.md failu, lai ievērotu vienotus koda stilu un dokumentēšanas standartus.

📄 6. Licence
Šis projekts tiek izplatīts saskaņā ar MIT licenci. Tas nozīmē, ka jūs varat brīvi izmantot, modificēt un izplatīt šī projekta materiālus, norādot sākotnējo autorību. Sīkāku informāciju skatiet LICENSE failā.
