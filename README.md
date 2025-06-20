
# 📌 Documentația proiectului OncoPath
  

## 🔍 Descrierea problemei  
În România, în fiecare ora, aproximativ 6 oameni primesc un diagnostic de cancer. La nivelul anului 2022, peste 100.000 de cazuri noi au fost raportate, iar rata mortalității rămâne una dintre cele mai ridicate din Uniunea Europeană. Dincolo de cifre, însă, fiecare caz înseamnă o familie care se frânge, un om care trebuie să învețe să trăiască altfel, o viață care se reconstruiește din temelii.  
Pacientul oncologic nu are doar nevoie de tratament, ci și de informație clară, sprijin emoțional și un cadru de siguranță în care să fie auzit. În România, acest sprijin este adesea limitat la interacțiunile clinice, iar digitalizarea în domeniul oncologiei rămâne superficială sau inaccesibilă celor mai vulnerabili. Mulți pacienți nu știu unde să caute răspunsuri sau ce întrebări ar trebui să pună.  
Cancerul este o boală a trupului. Dar vindecarea trece întotdeauna și prin suflet. Iar în spațiul digital, OncoPath devine un loc în care pacientul e privit ca om, nu ca statistică.

💡 Descrierea soluției propuse  
OncoPath este o aplicație mobilă construită pentru a oferi sprijin emoțional, informativ și comunitar pacienților oncologici. Într-un context în care tehnologia poate deveni o punte între suferință și reziliență, OncoPath îmbină funcționalități cheie cu o interfață intuitivă, accesibilă și empatica. Aceasta combină trei dimensiuni majore:  
• Suport emoțional (jurnal, starea mea, comunitate, interviuri reale)  
• Educație medicală clară și accesibilă (dieta, tratamente, întrebări frecvente, factori de risc)  
• Jocuri (călătoria celulei, îngrijire cu suflet)  

Prin intermediul OncoPath, utilizatorii își pot monitoriza zilnic starea, pot primi mesaje de încurajare, pot afla detalii relevante despre tipul lor de tratament (în România și în alte țări) și pot interacționa cu alți pacienți. Această combinație dintre informație validată și suport emoțional oferă un cadru de sprijin autentic, lipsit de superficialitate.

🎯 Public țintă  
Publicul nostru țintă include:  
• Pacienți oncologici din România, de toate vârstele( în viitor plănuim o extindere si in alte țări)  
• Familii și aparținători care doresc să înțeleagă mai bine prin ce trece o persoană apropiata  
• Medici care vor să-și sprijine pacienții  

Membrii echipei  
Balan Julianna s-a ocupat în principal de cercetare, gestionarea feedback-ului primit și structurarea conținutului în aplicație.  
Stanciu Mihaela s-a ocupat de partea de dezvoltare efectivă a aplicației în Thunkable și design-ul acesteia.

⚙ Funcționalitățile aplicației  
Funcționalitățile sunt grupate în trei secțiuni mari:

I. Suport  
- Jurnal personal – utilizatorul își poate nota gândurile, trăirile, și poate urmări cum evoluează emoțional;  
- Comunitate – acces la situații reale, perspective diferite, și la un spațiu sigur pentru exprimare;  
- Interviuri – videoclipuri scurte, autentice, cu un medic oncolog, o pacienta diagnosticată cu cancer și cu fiica acesteia;  
- Starea mea – utilizatorul selectează cum s-a simțit azi și primește un mesaj personalizat de încurajare, într-un limbaj cald și empatic.  

II. Educație  
- Informații despre tratament – atât din România, cât și din alte țări;  
- Factori de risc – Prezentare organizată și clară a principalilor factori de risc în apariția cancerului, explicată în termeni simpli.   
- Dieta – Recomandări alimentare adaptate pacienților oncologici, însoțite de explicații clare. Sursele folosite sunt verificate (Institutul Oncologic, OMS etc.).  
- Întrebări frecvente despre cancer – oferim claritate acolo unde alții oferă jargon medical. Funcționalitate care permite utilizatorilor să primească răspunsuri la întrebări frecvente, într-un limbaj accesibil. În viitor, se va putea extinde către o funcție de chatbot sau integrare cu IA.  

III. Jocuri simbolice, cu sens educativ si funcție dublă: educație prin empatie și reflecție personală.  
- În primul joc, utilizatorul îngrijește un copil bolnav de cancer.  
- În al doilea, trebuie să se ferească de celule canceroase   
Aceste jocuri nu sunt acolo „pentru distracție”. Sunt acolo pentru că să înțelegi boala poate începe și prin joc.

🧱 Arhitectura aplicației  
OncoPath a fost construită în Thunkable, o platformă no-code care ne-a permis să ne concentrăm pe experiența utilizatorului și să iterăm rapid în funcție de nevoile reale ale celor care au testat aplicația. Deși nu am scris linii de cod tradiționale, am construit cu mare atenție fiecare ecran, fiecare buton, fiecare tranziție, ghidate de principii solide de UI și UX.  
Am acordat o atenție specială interfeței: tema vizuală este caldă, blândă, prietenoasă, o alegere conștientă într-un context dominat, de obicei, de termeni medicali reci. Culoarea principală este roz, simbol internațional al luptei împotriva cancerului, iar logo-ul aplicației este gândit să comunice din primul moment ideea de sprijin și încredere.  
În ceea ce privește gestionarea datelor, aplicația este minim invazivă. Singurul spațiu în care se păstrează date este în tab-ul Comunitate, unde utilizatorul își poate introduce un nume (chiar fictiv) și opțional o fotografie, fără a fi nevoie de înregistrare sau cont. Restul funcționalităților se folosesc în mod anonim, în siguranță, păstrând intimitatea utilizatorului.  
Am ales simplitatea și accesibilitatea, nu ca un compromis, ci ca un principiu de arhitectură, pentru că aplicația noastră nu se adresează doar utilizatorilor tineri sau tehnici, ci și pacienților în vârstă sau în momente dificile, care au nevoie de un mediu clar, liniștitor și ușor de folosit.

🧩 Interfață și experiență de utilizare (UI/UX)  
•	UI (User Interface): Am urmărit o interfață aerisită, intuitivă, cu butoane vizibile și fonturi lizibile.  
•	UX (User Experience): Fluxul aplicației este clar, iar fiecare funcționalitate este gândită pentru a fi accesibilă inclusiv pentru utilizatori fără experiență digitală.  


💎 Elemente distinctive și puncte forte
1.Colaborare directă cu clinica Neolife Iași, una dintre cele mai mari clinici oncologice din România. Această colaborare ne-a permis:
• să testăm aplicația pe parcursul dezvoltării cu pacienți reali;
• să primim feedback imediat și valoros;
• să includem în aplicatie interviuri autentice cu medici, pacienți și aparținători;
• să prioritizăm ce contează cu adevărat în funcționalitățile oferite.
2.Empatie – aplicația a pornit dintr-o experiență personală și a fost construită gândindu-ne constant la pacient, nu doar la funcționalitate.
3. Accent pe accesibilitate și adaptare culturală. Spre deosebire de majoritatea aplicațiilor oncologice disponibile (în limba engleză, generaliste sau supraspecializate), OncoPath este:
• scrisă într-un limbaj clar, uman și în limba română;
• gândită pentru pacienții din România, cu informații despre tratamente disponibile atât local cât și internațional;
• validată de medici români și explicată ca din perspectiva unui pacient român, nu a unui protocol abstract.

3. Stabilitate și funcționalități testate – aplicația noastră are:
zero erori critice în testare;
salvare de date doar acolo unde este absolut necesar 

4.Unicitate în peisajul digital românesc – Nu există în acest moment pe piața din România o aplicație oncologică care să combine:
funcții medicale validate;
componentă emoțională personalizată;
interviuri reale;
și jocuri simbolice, gândite cu grijă, ca formă de reconectare la sine.
5. Implementare complet funcțională și testată – OncoPath este deja o aplicație viabilă, stabilă și testată în colaborare cu pacienți reali. Nu este doar un concept, ci o soluție activă, cu funcționalități diverse implementate, feedback integrat și compatibilitate cross-platform.
6. OncoPath este construită cu pacienții, nu doar „pentru” pacienți. Avem interviuri reale, conținut umanizat și o abordare empatică – dar informat medical.

🧰Ghid de instalare și configurare:
• Aplicația poate fi vizualizată din link-ul Thunkable URL: 
https://x.thunkable.com/projectPage/6776f6bc978a4939bcf10a43 
• Este nevoie doar de un cont google care să se conecteaze la aplicația Thunkable.
✅ Justificarea tehnologiilor alese
Thunkable poate părea o alegere „simplă” în comparație cu alte framework-uri moderne, dar pentru noi a fost instrumentul potrivit pentru misiunea potrivită. Am ales Thunkable pentru că:
• Ne-a permis să ne concentrăm pe utilitate și accesibilitate, nu pe complexitate inutilă
• Am putut construi rapid un MVP funcțional și fără erori, testabil pe dispozitive reale
• Am putut modifica ușor interfața în funcție de feedbackul pacienților, fără să pierdem săptămâni în debugging
Functionalitatile oferite de thunkable au fost suficiente pentru a atinge scopul aplicației: de a sprijini pacienții. Alte posibile functionalitati, oferite de alte limbaje de programare nu au fost necesare în cazul nostru, iar alegerea de a nu le folosi a fost conștientă și justificată de scopul aplicației. 
Realitatea e simplă: nu toate proiectele reușesc prin complexitatea tehnologică. Unele reușesc prin impactul real pe care îl au. OncoPath oferă exact ceea ce trebuie, într-un format accesibil oricui, fără bariere de utilizare.
🌐 Posibilități de extindere

OncoPath nu este un proiect închis, ci o platformă deschisă viitorului. Planurile de dezvoltare includ:

- Integrarea unui chatbot bazat pe Inteligență Artificială pentru răspunsuri personalizate;
- Traducerea aplicației în limba engleză și extinderea către alte țări;
- Colaborări cu alte clinici oncologice din România și Europa;
- Îmbunătățirea jocurilor prin elemente interactive educative (realitate augmentată, de exemplu);
- Implementarea unei funcționalități de notificări pentru mesaje de sprijin sau sfaturi zilnice;
- Lansarea pe Google Play Store și App Store într-un format public și accesibil larg.


 Opinia echipei despre ideea proiectului și utilitatea sa

Poate cel mai important lucru pe care l-am învățat lucrând la OncoPath e că atunci când faci un proiect cu adevărat necesar, înveți să te ții de el nu pentru o notă, nu pentru validare, ci pentru că nu ai voie să-l abandonezi.
Cancerul nu e doar un diagnostic. E o întrebare care apasă în fiecare zi: „Cum trec peste asta?”. Poate ca aplicația noastră nu are încă toate răspunsurile,  și suntem conștiente de asta. Dar e o mână întinsă, un loc sigur în care un pacient sau o fiică îngrijorată poate găsi o propoziție care contează, o întrebare la care altcineva a răspuns deja, o poveste în care să se regăsească.
Ne-am dat seama, în timp, că OncoPath nu e doar o aplicație, ci o formă de reacție umană. Am pornit de la un gând simplu: „Cum aș vrea să fiu ajutată dacă aș fi eu în locul lor?” și am construit mai departe. Asta ne face să credem cu tot sufletul în utilitatea acestui proiect.
Nu suntem cea mai avansată echipă din punct de vedere tehnic. Dar suntem o echipă sinceră, atentă, care a reușit sa-si implementeze deja aplicatia, care a testat fiecare funcționalitate nu doar în fața unui ecran, ci în fața unor oameni reali. Când cineva de la Neolife ne spune „asta chiar ar ajuta”, nu e un compliment, e un semn că ceea ce facem merită dus mai departe.
Credem că OncoPath e valoros nu doar prin ceea ce este acum, ci prin ceea ce poate deveni, și mai ales prin motivul pentru care a fost creat: să pună omenia acolo unde, de multe ori, lipsește.

🗺 Roadmap
• Ianuarie 2024: ideea a luat naștere, inspirată de o experiență personală
• Februarie - Aprilie 2024: brainstorming, definirea nevoilor și cercetare pe cazuri reale
• Mai 2024: primele schițe de interfață + decizia de a lucra în Thunkable
• Iulie 2024: începutul colaborării cu clinica Neolife – testare directă cu pacienți reali, obținerea de interviuri
• August - Octombrie 2024: implementarea funcționalităților de bază (jurnal, starea mea, secțiunea educație)
• Noiembrie 2024 - Februarie 2025: feedback și testare + perfecționarea mesajelor de încurajare
• Martie - Iunie 2025: finalizarea interviurilor video, testare extinsă, optimizări
• Iunie 2025 - prezent: pregătire pentru lansarea publică, scrierea documentației
🗣 Testimoniale
„Am ascultat un interviu din aplicație și, pentru prima dată în multe luni, am simțit că sunt înțeles. A fost o liniște greu de explicat.”
— Mihai, 26 ani

 „M-am jucat acel minijoc cu evitarea celulelor și, deși simplu, m-a făcut să râd. A fost prima dată când am simțit că mă distrez fără vină, de când sunt bolnava.”
— Irina, 14 ani

 „Aplicația nu m-a vindecat, dar m-a ținut aproape de mine. A fost ca o pauză de la tot ce e greu.”
— Andreea, 18 ani

Testimonial – Dr. Ioana Radu, medic oncolog pediatru:
„Cred cu tărie că, dincolo de tratamentul propriu-zis, pacienții au nevoie de sprijin emoțional și de instrumente care să-i ajute să se simtă din nou oameni, nu doar cazuri medicale. Această aplicație face exact asta: oferă informație validă, dar și un spațiu sigur, empatic și viu. E o inițiativă rară, cu suflet, care completează actul medical acolo unde el nu mai ajunge.”


💼 Implementare și scalare pe piața reală

 Validarea deja obținută, prin testări directe cu pacienți reali în colaborare cu clinica Neolife Iași, ne oferă deja un avantaj competitiv solid și un punct de plecare pentru implementare largă.

🔹 Potențial de adopție ridicat:
În România trăiesc peste 600.000 de pacienți oncologici, iar incidența cazurilor noi depășește 100.000 anual (Globocan, 2023). Dintre aceștia, peste 60% declară că nu primesc suficient suport psihologic sau informațional (Raportul Coaliției Organizațiilor Pacienților). Aplicația răspunde direct acestor lipsuri, prin comunitate, conținut adaptat cultural și sprijin constant.

🔹 Strategie de penetrare a pieței:
Parteneriate cu clinici și asociații oncologice pentru diseminare (avem deja Neolife ca prim pas concret)
Prezentarea aplicației în spitale, la cabinete de psihologie oncologică și la conferințe medicale
Promovare digitală pe grupuri de pacienți și în campanii de informare

🔹 Barieră tehnică redusă = accesibilitate imediată:
Fiind realizată în Thunkable, OncoPath poate fi distribuită rapid pe Android și iOS. Nu necesită cont sau autentificare dificilă: pacientul se poate conecta direct cu aplicația, fără stres suplimentar. Tehnologia e simplă, dar bine gândită: aplicația funcționează stabil, nu colectează date sensibile și e deja testată de zeci de utilizatori fără erori critice.

Componente ale proiectului care nu au fost realizare de noi:
Informațiile au fost preluate, sintetizate și traduse din cărțile de specialitate Anticancer: A New Way of Life de Dr. David Servan-Schreiber și Nutrition and Cancer: Prevention and Survival de Neal D. Barnard sau de pe siteurile oficiale Institutul Oncologic, OMS
pdf urile cu informatii au fost preluate de pe site ul WHO: World Health Organisation
Pozele au fost preluate din gama pozelor publicate de unsplash, reshot, pexels și respectiv create de noi cu ajutorul picrew.
🎖 OncoPath – Nu ești singur. Nici în tratament, nici în procesul de a înțelege, nici în frică.
