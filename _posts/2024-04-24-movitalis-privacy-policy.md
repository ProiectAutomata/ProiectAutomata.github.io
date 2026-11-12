---
layout: post
title: "Politica de confidențialitate Movitalis"
author: "David Manda"
categories: article
tags: [movitalis-privacy]
image: politica-de-confidentialitate-1.webp
duration: 4
---

Ultima modificare: 12 Noiembrie, 2026

David Manda este operatorul aplicației iOS Movitalis ("aplicația").

Folosind aplicația, ești de acord cu colectarea și folosirea datelor în concordanță cu această politică de confidențialitate.

# 1. Colectarea și folosirea datelor

## 1-1. Date Apple Health

Aplicația folosește API-urile Apple pentru a citi sau a scrie anumite date din/în aplicația Apple Health de pe dispozitivul tău ("Date Apple Health"). Aceste informații includ:

- Antrenamente
- Puls
- Distanță
- Număr pași
- Data nașterii
- Sexul biologic

Vom folosi aceste date Apple Health pentru a-ți arăta statistici legate de antrenamentele tale și pentru a-ți da indicații despre cum să te antrenezi.

Nu vom folosi datele tale Apple Health în scopuri de marketing. Implicit, datele Apple Health sunt accesate doar local, pe dispozitivul tău, și nu sunt transmise către serverele noastre. Aplicația nu poate citi date din Apple Health fără acordul tău.

Excepțiile sunt doar cele pe care le activezi tu: sincronizarea opțională a datelor de sănătate (secțiunea 1-2) și conectarea contului Strava (secțiunea 1-7).

## 1-2. Sincronizarea opțională a datelor de sănătate

Dacă activezi sincronizarea progresului (dezactivată implicit, disponibilă în Profil → Detalii cont), aplicația sincronizează în contul tău următoarele date, derivate din Apple Health:

**Date agregate:**
- Valorile VO₂ max și data măsurătorii
- Minutele săptămânale de antrenament pe categorii (Zona 2, VO₂ max, forță și mobilitate)
- Seriile de antrenament (streaks) și realizările deblocate
- Profilul de antrenament: vârsta, pulsul maxim estimat, limitele zonelor de puls și ținta săptămânală

**Antrenamente individuale din ultimele 6 luni:**
- Rezumatul fiecărui antrenament: tipul, data și durata, categoria și minutele pe categorii, distanța, pulsul mediu și maxim, caloriile, ritmul, diferența de nivel, rezultatul față de țintă, parcursul pe kilometri, intervalele pe zone și pauzele
- Seria de puls a antrenamentului (cu o limită de puncte per antrenament)
- Traseul GPS (latitudine, longitudine, altitudine), dacă antrenamentul are unul
- Seria de distanță a antrenamentului

Aceste date sunt stocate în Firebase Firestore (Google) și sunt asociate contului tău. Scopul sincronizării este păstrarea progresului tău în siguranță, accesul de pe mai multe dispozitive și, doar dacă le aprobi explicit, citirea lor de către integrări precum Claude (secțiunea 1-8).

**Important:**
- Sincronizarea are loc doar după consimțământul tău explicit, exprimat în aplicație (baza legală: art. 9 alin. (2) lit. (a) GDPR — consimțământ explicit pentru date privind sănătatea).
- Antrenamentele mai vechi de 6 luni, precum și cele șterse din Apple Health, sunt eliminate de pe servere la următoarea sincronizare.
- Datele citite din Strava (secțiunea 1-7) nu fac parte din această sincronizare.
- Poți retrage consimțământul oricând din aceeași secțiune a aplicației; la retragere, toate datele sincronizate sunt șterse de pe servere.

## 1-3. Date Forță și Mobilitate

Aplicația oferă o serie de teste de forță și mobilitate. Aceste date sunt introduse manual de către tine.

Vom folosi aceste date pentru a-ți arăta statistici legate de antrenamentele tale și pentru a-ți da indicații despre cum să te antrenezi.

Nu vom folosi datele tale de Forță și Mobilitate în scopuri de marketing. Datele tale vor fi accesate doar local de pe dispozitivul tău și vor fi stocate de aplicație. Datele tale nu vor fi transmise către serverele noastre. Datele vor fi șterse la dezinstalarea aplicației.

## 1-4. Colectarea de Date de Utilizare și Analiză

Aplicația folosește Firebase Analytics (furnizat de Google) pentru a înțelege cum este utilizată aplicația și pentru a îmbunătăți experiența utilizatorilor.

**Date colectate automat:**
- Evenimentele de autentificare (înregistrare și autentificare prin Apple/Google)
- Paginile vizitate în aplicație (Weekly, Plan, Analysis, Profile)
- Achizițiile de abonamente premium
- Starea abonamentului (utilizator gratuit sau premium)
- Identificator unic de utilizator (Firebase UID)

Aceste date sunt transmise către serverele Firebase (Google) și sunt stocate conform politicii de confidențialitate Google Firebase.

**Datele de analiză nu includ:**
- Datele tale Apple Health
- Rezultatele testelor de forță și mobilitate
- Informații personale identificabile (nume, email) — acestea sunt stocate separat, în contul tău (vezi secțiunea 1-5)

Pentru mai multe informații despre cum Google procesează datele, consultați: [https://firebase.google.com/support/privacy](https://firebase.google.com/support/privacy)

## 1-5. Datele contului

La crearea contului (prin Apple Sign-In sau Google Sign-In), stocăm în Firebase Firestore următoarele date asociate contului tău:

- Adresa de email și numele afișat
- Data creării contului și data ultimei autentificări
- Răspunsurile tale la chestionarul inițial (nivel de activitate, obiective de sănătate)
- Planul tău de antrenament și istoricul modificărilor acestuia
- Starea abonamentului premium

Aceste date sunt folosite pentru funcționarea contului, sincronizarea între dispozitive și verificarea abonamentului. Ele sunt șterse la ștergerea contului din aplicație, cu o singură excepție: pentru a preveni folosirea repetată a perioadei de probă gratuite, păstrăm o amprentă criptografică (hash SHA-256) a adresei tale de email, împreună cu data la care ai folosit perioada de probă. Din această amprentă adresa de email nu poate fi reconstituită; ea servește doar pentru a recunoaște aceeași adresă la o nouă înregistrare (baza legală: interesul legitim de a preveni abuzul).

## 1-6. Comunicări prin email

La crearea contului îți poți exprima acordul pentru a primi ocazional emailuri cu noutăți despre aplicație și sfaturi de fitness. Pentru trimiterea emailurilor folosim serviciul Resend, care primește adresa ta de email și numele afișat.

Te poți dezabona oricând folosind linkul de dezabonare din orice email. La ștergerea contului, adresa ta este eliminată și din lista de emailuri.

## 1-7. Integrarea cu Strava (opțională)

Dacă îți conectezi contul Strava (Profil → Strava), aplicația folosește API-ul Strava, doar cu permisiunile pe care le aprobi pe pagina de autorizare Strava:

- **Trimiterea antrenamentelor:** antrenamentele înregistrate cu Movitalis sunt încărcate în contul tău Strava: tipul activității, ora, durata, distanța, caloriile, pulsul și traseul GPS, plus titlul și descrierea pe care le alegi în setările Strava din aplicație. Poți opri oricând încărcarea automată.
- **Completarea analizei:** pentru antrenamentele înregistrate cu alte ceasuri (de ex. COROS, Garmin), aplicația citește din Strava activitatea corespunzătoare (puls, perioadele de pauză, traseul GPS), ca analiza să fie completă. Dacă îți dai permisiunea, pulsul este salvat și în Apple Health.
- Datele brute citite din Strava sunt stocate doar local, pe dispozitivul tău. Nu sunt trimise către serverele noastre și nu sunt transmise către instrumente de inteligență artificială sau către alți terți.
- Tokenurile de acces Strava sunt păstrate în Keychain-ul dispozitivului.
- **Deconectarea:** din Profil → Strava → Deconectează Strava. Accesul aplicației este revocat la Strava, iar datele citite din Strava sunt șterse de pe dispozitiv. Activitățile deja încărcate rămân în contul tău Strava, de unde le poți șterge. Pulsul salvat în Apple Health rămâne acolo până îl ștergi din aplicația Sănătate.

Datele trimise către Strava sunt procesate conform politicii de confidențialitate Strava: [https://www.strava.com/legal/privacy](https://www.strava.com/legal/privacy)

## 1-8. Integrarea cu Claude (opțională)

Poți conecta asistentul Claude (dezvoltat de Anthropic) la contul tău Movitalis, ca să-i poți pune întrebări despre antrenamentele tale. Conexiunea pornește din Claude și devine activă doar după ce o aprobi explicit în aplicația Movitalis.

- Claude are acces **doar la citire** la datele sincronizate în contul tău (secțiunea 1-2): profilul de antrenament și antrenamentele din ultimele 6 luni. Nu poate modifica sau șterge date.
- Datele sunt citite doar când pui o întrebare în Claude; prelucrarea lor de către Anthropic este guvernată de politica de confidențialitate Anthropic și de setările contului tău Claude.
- Datele citite din Strava nu sunt niciodată transmise către Claude.
- **Declarație de transparență privind inteligența artificială:** Claude este un sistem de inteligență artificială. Dacă ai conectat Garmin Connect™ (secțiunea 1-9), antrenamentele sincronizate pot include date provenite de la dispozitivele Garmin (pulsul, pauzele, traseul), marcate ca atare. Claude le prelucrează doar după consimțământul tău explicit (aprobarea conexiunii în aplicație) și doar pentru a-ți răspunde la întrebări; nici Movitalis, nici datele tale nu sunt folosite pentru antrenarea modelelor de inteligență artificială. Îți poți retrage consimțământul oricând, cu un singur pas: Profil → Detalii cont → Claude → Revocă.
- Poți revoca accesul oricând (Profil → Detalii cont → Claude); revocarea, retragerea consimțământului pentru sincronizare sau ștergerea contului șterg tokenurile de acces.

## 1-9. Integrarea cu Garmin Connect™ (opțională)

Dacă îți conectezi contul Garmin Connect™ (Profil → Garmin Connect™), aplicația primește de la Garmin, prin Garmin Connect Developer Program, activitățile pe care le sincronizezi după conectare, doar cu permisiunile pe care le aprobi pe pagina de autorizare Garmin.

- **Ce date primim:** pentru fiecare activitate: ora de început, tipul activității, modelul dispozitivului, pulsul înregistrat, perioadele de pauză ale cronometrului și traseul GPS (cu altitudinea). Nu primim istoricul dinainte de conectare și nu primim alte date Garmin (somn, stres, date zilnice etc.).
- **Cum le folosim:** doar pentru analiza antrenamentelor tale în aplicație: minutele în Zona 2 și VO₂max, durata activă fără pauze, harta traseului și cardurile de partajare. Dacă îți dai permisiunea, pulsul este salvat și în Apple Health. Oriunde apar, datele sunt marcate „Garmin [modelul dispozitivului]”.
- **Unde sunt procesate:** Garmin trimite activitățile către serverele noastre (Google Firebase: Cloud Functions în SUA, Firestore în Uniunea Europeană), unde păstrăm o copie compactă în contul tău, de unde aplicația o descarcă pe dispozitiv. Tokenurile de acces Garmin sunt păstrate doar pe servere, inaccesibile aplicației și altor utilizatori.
- **Cine mai primește datele:** Google Firebase, ca furnizor de găzduire, și — doar dacă aprobi explicit integrarea cu Claude (secțiunea 1-8) — Anthropic, care le poate citi la cererea ta. Nu vindem și nu partajăm datele Garmin cu alți terți și nu le folosim pentru publicitate.
- **Inteligență artificială:** vezi declarația de transparență din secțiunea 1-8. Datele Garmin și cele derivate din ele nu sunt folosite niciodată pentru antrenarea, evaluarea sau îmbunătățirea modelelor de inteligență artificială.
- **Păstrare:** fiecare activitate primită este păstrată pe servere cel mult 6 luni de la data ei, sau până la deconectare, retragerea permisiunii în Garmin Connect™ sau ștergerea contului — oricare survine prima.
- **Deconectarea:** din Profil → Garmin Connect™ → Deconectează, sau din Garmin Connect™ → Setări → Aplicații conectate. În ambele cazuri, înregistrarea aplicației este retrasă la Garmin, iar datele primite de la Garmin sunt șterse de pe servere și de pe dispozitiv. Pulsul salvat în Apple Health rămâne acolo până îl ștergi din aplicația Sănătate.

Datele din contul tău Garmin sunt procesate de Garmin conform politicii de confidențialitate Garmin: [https://www.garmin.com/privacy/connect/](https://www.garmin.com/privacy/connect/)

## 1-10. Servicii Terțe

Aplicația folosește următoarele servicii terțe:

1. **Firebase Authentication (Google)** - pentru autentificare
2. **Firebase Analytics (Google)** - pentru analiza utilizării
3. **Firebase Firestore (Google)** - pentru sincronizarea datelor între dispozitive
4. **Google Sign-In** - pentru autentificare
5. **Apple Sign-In** - pentru autentificare
6. **RevenueCat** - pentru gestionarea achizițiilor și abonamentelor; primește informații despre tranzacțiile tale din App Store și identificatorul contului tău
7. **Resend** - pentru trimiterea de emailuri (adresa de email și numele afișat)
8. **Facebook SDK** - pentru evenimente de conversie publicitară
9. **Strava** (opțional, doar dacă îți conectezi contul) - pentru trimiterea antrenamentelor și completarea analizei (vezi secțiunea 1-7)
10. **Claude (Anthropic)** (opțional, doar dacă aprobi conexiunea) - citește antrenamentele sincronizate pentru a răspunde întrebărilor tale (vezi secțiunea 1-8)
11. **Garmin Connect™** (opțional, doar dacă îți conectezi contul) - trimite activitățile tale Garmin pentru analiza antrenamentelor (vezi secțiunea 1-9)

Aceste servicii pot colecta date conform propriilor politici de confidențialitate:
- Firebase Privacy: [https://firebase.google.com/support/privacy](https://firebase.google.com/support/privacy)
- Google Privacy: [https://policies.google.com/privacy](https://policies.google.com/privacy)
- RevenueCat Privacy: [https://www.revenuecat.com/privacy](https://www.revenuecat.com/privacy)
- Resend Privacy: [https://resend.com/legal/privacy-policy](https://resend.com/legal/privacy-policy)
- Strava Privacy: [https://www.strava.com/legal/privacy](https://www.strava.com/legal/privacy)
- Anthropic Privacy: [https://www.anthropic.com/legal/privacy](https://www.anthropic.com/legal/privacy)
- Garmin Privacy: [https://www.garmin.com/privacy/connect/](https://www.garmin.com/privacy/connect/)

## 1-11. Partajarea Datelor

**Datele tale sunt partajate cu:**
- **Firebase/Google**: evenimente de utilizare, stare premium, autentificare, datele sincronizate (răspunsurile la chestionar, planul de antrenament și — doar cu consimțământul tău explicit — datele de sănătate din secțiunea 1-2)
- **RevenueCat**: tranzacțiile de achiziție și identificatorul contului, pentru validarea și gestionarea abonamentelor
- **Resend**: adresa de email și numele afișat, pentru comunicări prin email
- **Facebook**: evenimente de achiziție (pentru optimizarea publicitară)
- **Strava** (doar dacă îți conectezi contul): antrenamentele înregistrate cu Movitalis, inclusiv pulsul și traseul GPS (secțiunea 1-7)
- **Claude / Anthropic** (doar dacă aprobi conexiunea): antrenamentele și profilul de antrenament sincronizate (secțiunea 1-8), citite la cererea ta, inclusiv datele Garmin marcate ca atare dacă ai conectat Garmin Connect™
- **Garmin**: nu trimitem date către Garmin; doar primim de la Garmin activitățile pe care alegi să le partajezi (secțiunea 1-9)

**Important:** Datele Apple Health rămân pe dispozitivul tău, cu excepția celor pe care alegi tu să le trimiți: datele de sănătate sincronizate (secțiunea 1-2, doar cu consimțământul tău explicit), antrenamentele trimise în contul tău Strava (secțiunea 1-7) și citirea datelor sincronizate de către integrările pe care le aprobi (secțiunea 1-8). Nu vindem datele tale și nu le folosim în scopuri de marketing.

## 1-12. Reținerea Datelor

- **Datele Apple Health**: stocate local, șterse la dezinstalare
- **Datele de sănătate sincronizate (secțiunea 1-2)**: antrenamentele individuale pentru o perioadă mobilă de 6 luni; toate datele sincronizate, până la retragerea consimțământului sau ștergerea contului — oricare survine prima
- **Conexiunile cu integrări (Claude)**: tokenurile de acces sunt șterse la revocarea conexiunii sau la ștergerea contului
- **Datele primite de la Garmin (secțiunea 1-9)**: cel mult 6 luni de la data fiecărei activități, pe servere și pe dispozitiv; șterse imediat la deconectare, la retragerea permisiunii în Garmin Connect™ sau la ștergerea contului, împreună cu tokenurile de acces
- **Amprenta (hash) adresei de email pentru perioada de probă**: reținută și după ștergerea contului, pentru prevenirea abuzului (secțiunea 1-5)
- **Datele Firebase (autentificare, premium status, chestionar, plan de antrenament)**: reținute până la ștergerea contului
- **Datele RevenueCat (istoric achiziții)**: reținute conform politicii RevenueCat, cât timp contul există
- **Adresa de email (Resend)**: reținută până la dezabonare sau ștergerea contului
- **Datele de analiză**: reținute conform politicii Firebase (maxim 14 luni pentru rapoarte)
- **Datele citite din Strava**: stocate doar local, șterse la deconectarea Strava sau la dezinstalare; activitățile trimise către Strava rămân în contul tău Strava până le ștergi de acolo

# 2. Securitate

Securitatea informațiilor tale este importantă pentru noi, dar nicio modalitate electronică de stocare a informațiilor nu este 100% sigură. Vom folosi standarde acceptate comercial de protejare a datelor tale, dar nu putem garanta siguranța absolută a acestora.

# 3. Drepturile Tale

**Ai următoarele drepturi:**
- Poți șterge contul tău și datele asociate direct din aplicație (Profil → Detalii cont → Șterge contul); ștergerea include datele din Firebase, datele de sănătate sincronizate, conexiunile cu integrări și adresa din lista de emailuri (rămâne doar amprenta descrisă în secțiunea 1-5)
- Poți exporta datele stocate în contul tău direct din aplicație (Profil → Detalii cont → Exportă datele mele)
- Poți retrage oricând consimțământul pentru sincronizarea datelor de sănătate (Profil → Detalii cont → Sincronizare progres); datele sincronizate vor fi șterse de pe servere
- Poți revoca oricând accesul unei integrări (Profil → Detalii cont → Claude)
- Poți deconecta Strava oricând (Profil → Strava → Deconectează Strava); accesul aplicației este revocat și datele citite din Strava sunt șterse de pe dispozitiv
- Poți deconecta Garmin Connect™ oricând (Profil → Garmin Connect™ → Deconectează sau din Garmin Connect™ → Setări → Aplicații conectate); datele primite de la Garmin sunt șterse de pe servere și de pe dispozitiv. Poți cere oricând o copie a lor, corectarea sau ștergerea lor la adresa de contact
- Poți dezactiva colectarea de date prin Apple Settings → Privacy → Analytics & Improvements
- Datele de analiză sunt anonimizate și nu pot fi folosite pentru a te identifica personal

# 4. Conformitate GDPR

**Pentru utilizatorii din Uniunea Europeană:**

Baza legală pentru procesare: consimțământ și interes legitim. Pentru datele de sănătate sincronizate (secțiunea 1-2), baza legală este consimțământul explicit conform art. 9 alin. (2) lit. (a) GDPR, pe care îl poți retrage oricând.

**Drepturile tale conform GDPR:**
- Dreptul la acces: poți solicita o copie a datelor tale personale (sau folosi exportul din aplicație)
- Dreptul la rectificare: poți corecta datele inexacte
- Dreptul la ștergere: poți solicita ștergerea datelor tale (sau folosi ștergerea contului din aplicație)
- Dreptul la portabilitate: poți solicita transferul datelor tale
- Dreptul de retragere a consimțământului: pentru sincronizarea datelor de sănătate, direct din aplicație

**Contact pentru cereri GDPR:** dmanda@automata.ltd

# 5. Schimbări aduse acestei Politici de Confidențialitate

Este posibil să actualizăm Politica de Confidențialitate în viitor. Te vom înștiința de orice schimbări postând informațiile noi pe această pagină.

Te indemnăm să verifici periodic această Politica de Confidențialitate pentru orice schimbări. Orice schimbare adusă Politicii de Confidențialitate intră în vigoare când este reflectată pe această pagină.

Nu vom schimba acest acord pentru a permite colectarea datelor tale personale sau pentru a face orice alte schimbări semnificative fără să primim acordul tău.

# 6. Declinarea responsabilității

Nu putem face nicio garanție legat de caracterul adecvat al acestei aplicații pentru utilizator, sau pentru oricare dintre funcționalitățile ei, preț, acuratețe sau utilitate, și nu vom fi considerați reposinsabili pentru eventualele daune cauzate.

Rezervăm dreptul să schimbăm aplicația sau să o retragem. Nu vom fi considerați responsabili dacă aplicația este scoasă din uz, schimbată sau devine neutilizabilă într-un alt fel și datele ei sunt pierdute sau stricate ca și rezultat, sau dacă dispozitivul în sine este stricat, sau dispozitivul în sine susține daune cauzate de altă aplicație.

# 7. Contact

Dacă ai orice întrebări legate de această Politică de Confidențialitate, te rugăm să ne contactezi.

David Manda
dmanda@automata.ltd
