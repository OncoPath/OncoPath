##  OncoPath – Sprijin digital pentru pacienții de cancer

## Descriere generală

**OncoPath** este o aplicație mobilă construită pentru a oferi sprijin emoțional, informativ și comunitar pacienților oncologici. Într-un context în care tehnologia poate deveni o punte între suferință și reziliență, OncoPath îmbină funcționalități cheie cu o interfață intuitivă, accesibilă și empatică.

Pentru dezvoltarea aplicației, am optat pentru **Thunkable** – o platformă de tip no-code, bazată pe interacțiuni vizuale drag-and-drop. Această alegere a fost **conștientă și justificată**: Thunkable ne-a permis să ne concentrăm pe ceea ce contează cu adevărat – **funcționalitatea aplicației și experiența utilizatorului (UX)** – fără a fi necesare linii de cod complexe.


## 🔧 Tehnologie și motivația alegerii

Am ales **Thunkable** pentru:
- **Rapiditatea prototipării** și a iterării funcționalităților.
- Posibilitatea de **deploy nativ** atât pentru Android, cât și pentru iOS.
- Suportul integrat pentru **testare live**, care ne-a permis să identificăm și să corectăm erorile în timp real, în toate etapele dezvoltării.
- Gestionarea eficientă a resurselor aplicației: aplicația finală are **doar 49 MB**, un aspect esențial pentru accesibilitate pe dispozitive variate.

Deși platforma nu permite integrarea clasică de CI/CD sau testare automată unitară, am compensat prin:
- **Testare continuă manuală**, bazată pe feedback rapid și corectarea erorilor la fiecare build.
- Semnalizări vizuale și mesaje de eroare integrate, pentru creșterea robusteții aplicației.

---

## 📦 Funcționalități cheie

OncoPath oferă un set coerent și integrat de funcționalități:

### 📝 Jurnal personal
Utilizatorii își pot nota zilnic gândurile, emoțiile și detalii despre tratament, într-un spațiu confidențial, personalizat.

### 😄 Mood Tracker (monitorizare emoțională)
Aplicația permite înregistrarea stării de spirit zilnice, alături de detalii despre cum a decurs tratamentul. Utilizatorii primesc un mesaj motivațional personalizat în funcție de starea selectată.

### ❓ Centru de întrebări și răspunsuri
Funcționalitate care permite utilizatorilor să primească răspunsuri la întrebări frecvente, într-un limbaj accesibil. În viitor, se va putea extinde către o funcție de chatbot sau integrare cu IA.

### 👥 Comunitate activă
Secțiune de tip forum și chat, unde utilizatorii se pot conecta, pot forma grupuri de suport și pot schimba idei sau resurse utile.

### 🗺️ Hartă interactivă
Integrare cu locații ale centrelor oncologice din România. Datele sunt ușor de actualizat, cu posibilitatea extinderii internaționale.

### 🎮 Jocuri educativ-empatice
- **„Grijă pentru copilul bolnav”** – joc simbolic ce dezvoltă empatia și reziliența.
- **„Fugi de celulele canceroase”** – simulare metaforică a luptei cu boala, în format gamificat.

### 🥗 Informații despre nutriție
Recomandări alimentare adaptate pacienților oncologici, însoțite de explicații clare. Sursele folosite sunt verificate (Institutul Oncologic, OMS etc.).

### ⚠️ Factori de risc
Prezentare organizată și clară a principalilor factori de risc în apariția cancerului, explicată în termeni simpli.

### 🎤 Mini-interviuri
Scurte materiale inspiraționale cu pacienți sau medici care oferă exemple reale de reziliență, speranță și adaptare.


## 🧪 Testare și robustețe

Deși Thunkable nu permite testare automată (unit testing), am adoptat o strategie alternativă:
- **Testare manuală pe mai multe dispozitive**, în fiecare etapă de dezvoltare.
- **Simulare de fluxuri de utilizare** pentru fiecare funcționalitate principală.
- **Mesaje de feedback și semnalare a erorilor** în interfață, pentru a ghida utilizatorii și a preveni blocajele aplicației.


## 🗂️ Structură și organizare

Aplicația este construită modular, cu pagini dedicate pentru fiecare funcționalitate:
- Fiecare ecran este clar denumit și organizat.
- Codul bloc este ordonat în secțiuni logice, reutilizabil și ușor de urmărit.
- Setările globale sunt centralizate pentru ușurința mentenanței.


## ♻️ Versionare

Deși Thunkable nu oferă un sistem de versionare clasic precum Git, am lucrat organizat, **salvând aplicația în etape esențiale de dezvoltare**:
- După finalizarea fiecărei funcționalități
- Înaintea oricărei restructurări majore
- După feedback și testare

Această abordare ne-a permis să păstrăm controlul asupra versiunilor și să revenim cu ușurință la o variantă funcțională în caz de regres.


## 🧩 Interfață și experiență de utilizare (UI/UX)

- UI (User Interface): Am urmărit o interfață aerisită, intuitivă, cu butoane vizibile și fonturi lizibile.
- UX (User Experience): Fluxul aplicației este clar, iar fiecare funcționalitate este gândită pentru a fi accesibilă inclusiv pentru utilizatori fără experiență digitală.


## 💡 Alegerea platformei: justificare

În raport cu scopul aplicației – **sprijin și empatie pentru pacienți oncologici** – folosirea unui limbaj de programare complex nu ar fi adus beneficii suplimentare. Thunkable oferă:
- Toate funcționalitățile necesare
- Stabilitate și control
- Posibilitate de export rapid și fără costuri suplimentare
- Flexibilitate pentru adăugiri viitoare

Prin urmare, **alegerea platformei a fost rațională, adaptată publicului țintă și resurselor disponibile**, fără a compromite calitatea aplicației.



<!--
**OncoPath/OncoPath** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
