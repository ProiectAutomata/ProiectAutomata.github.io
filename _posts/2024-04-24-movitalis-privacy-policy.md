---
layout: post
title: "Politica de confidențialitate"
author: "David Manda"
categories: article
tags: [movitalis-privacy]
image: politica-de-confidentialitate-1.webp
duration: 4
---

Ultima modificare: 6 Iulie, 2026

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

Nu vom folosi datele tale Apple Health în scopuri de marketing. Datele brute Apple Health (antrenamente individuale, mostre de puls, pași, distanță, data nașterii, sexul biologic) sunt accesate doar local pe dispozitivul tău și nu sunt transmise către serverele noastre. Aplicația nu poate citi date din Apple Health fără acordul tău.

Singura excepție o reprezintă sincronizarea opțională a datelor agregate, descrisă în secțiunea 1-2, care are loc doar cu consimțământul tău explicit.

## 1-2. Sincronizarea opțională a datelor agregate de sănătate

Dacă activezi sincronizarea progresului (dezactivată implicit, disponibilă în Profil → Detalii cont), aplicația va sincroniza în contul tău următoarele date **agregate**, derivate din datele Apple Health:

- Valorile VO₂ max și data măsurătorii
- Minutele săptămânale de antrenament pe categorii (Zona 2, VO₂ max, forță și mobilitate)
- Seriile de antrenament (streaks) și realizările deblocate

Aceste date sunt stocate în Firebase Firestore (Google) și sunt asociate contului tău. Scopul sincronizării este păstrarea progresului tău în siguranță și accesul la el de pe mai multe dispozitive.

**Important:**
- Datele brute (mostre de puls, antrenamente individuale) NU sunt sincronizate niciodată.
- Sincronizarea are loc doar după consimțământul tău explicit, exprimat în aplicație (baza legală: art. 9 alin. (2) lit. (a) GDPR — consimțământ explicit pentru date privind sănătatea).
- Poți retrage consimțământul oricând din aceeași secțiune a aplicației; la retragere, datele sincronizate sunt șterse de pe servere.

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

Aceste date sunt folosite pentru funcționarea contului, sincronizarea între dispozitive și verificarea abonamentului. Ele sunt șterse integral la ștergerea contului din aplicație.

## 1-6. Comunicări prin email

La crearea contului îți poți exprima acordul pentru a primi ocazional emailuri cu noutăți despre aplicație și sfaturi de fitness. Pentru trimiterea emailurilor folosim serviciul Resend, care primește adresa ta de email și numele afișat.

Te poți dezabona oricând folosind linkul de dezabonare din orice email. La ștergerea contului, adresa ta este eliminată și din lista de emailuri.

## 1-7. Servicii Terțe

Aplicația folosește următoarele servicii terțe:

1. **Firebase Authentication (Google)** - pentru autentificare
2. **Firebase Analytics (Google)** - pentru analiza utilizării
3. **Firebase Firestore (Google)** - pentru sincronizarea datelor între dispozitive
4. **Google Sign-In** - pentru autentificare
5. **Apple Sign-In** - pentru autentificare
6. **RevenueCat** - pentru gestionarea achizițiilor și abonamentelor; primește informații despre tranzacțiile tale din App Store și identificatorul contului tău
7. **Resend** - pentru trimiterea de emailuri (adresa de email și numele afișat)
8. **Facebook SDK** - pentru evenimente de conversie publicitară

Aceste servicii pot colecta date conform propriilor politici de confidențialitate:
- Firebase Privacy: [https://firebase.google.com/support/privacy](https://firebase.google.com/support/privacy)
- Google Privacy: [https://policies.google.com/privacy](https://policies.google.com/privacy)
- RevenueCat Privacy: [https://www.revenuecat.com/privacy](https://www.revenuecat.com/privacy)
- Resend Privacy: [https://resend.com/legal/privacy-policy](https://resend.com/legal/privacy-policy)

## 1-8. Partajarea Datelor

**Datele tale sunt partajate cu:**
- **Firebase/Google**: evenimente de utilizare, stare premium, autentificare, datele sincronizate (răspunsurile la chestionar, planul de antrenament și — doar cu consimțământul tău explicit — datele agregate de sănătate din secțiunea 1-2)
- **RevenueCat**: tranzacțiile de achiziție și identificatorul contului, pentru validarea și gestionarea abonamentelor
- **Resend**: adresa de email și numele afișat, pentru comunicări prin email
- **Facebook**: evenimente de achiziție (pentru optimizarea publicitară)

**Important:** Datele brute Apple Health (mostre de puls, antrenamente individuale) rămân pe dispozitivul tău și NU sunt partajate niciodată. Datele agregate descrise în secțiunea 1-2 sunt sincronizate doar dacă activezi explicit această opțiune.

## 1-9. Reținerea Datelor

- **Datele Apple Health**: stocate local, șterse la dezinstalare
- **Datele agregate sincronizate (secțiunea 1-2)**: reținute până la retragerea consimțământului sau ștergerea contului — oricare survine prima
- **Datele Firebase (autentificare, premium status, chestionar, plan de antrenament)**: reținute până la ștergerea contului
- **Datele RevenueCat (istoric achiziții)**: reținute conform politicii RevenueCat, cât timp contul există
- **Adresa de email (Resend)**: reținută până la dezabonare sau ștergerea contului
- **Datele de analiză**: reținute conform politicii Firebase (maxim 14 luni pentru rapoarte)

# 2. Securitate

Securitatea informațiilor tale este importantă pentru noi, dar nicio modalitate electronică de stocare a informațiilor nu este 100% sigură. Vom folosi standarde acceptate comercial de protejare a datelor tale, dar nu putem garanta siguranța absolută a acestora.

# 3. Drepturile Tale

**Ai următoarele drepturi:**
- Poți șterge contul tău și toate datele asociate direct din aplicație (Profil → Detalii cont → Șterge contul); ștergerea include datele din Firebase, datele agregate sincronizate și adresa din lista de emailuri
- Poți exporta datele stocate în contul tău direct din aplicație (Profil → Detalii cont → Exportă datele mele)
- Poți retrage oricând consimțământul pentru sincronizarea datelor agregate de sănătate (Profil → Detalii cont → Sincronizare progres); datele sincronizate vor fi șterse de pe servere
- Poți dezactiva colectarea de date prin Apple Settings → Privacy → Analytics & Improvements
- Datele de analiză sunt anonimizate și nu pot fi folosite pentru a te identifica personal

# 4. Conformitate GDPR

**Pentru utilizatorii din Uniunea Europeană:**

Baza legală pentru procesare: consimțământ și interes legitim. Pentru datele agregate de sănătate (secțiunea 1-2), baza legală este consimțământul explicit conform art. 9 alin. (2) lit. (a) GDPR, pe care îl poți retrage oricând.

**Drepturile tale conform GDPR:**
- Dreptul la acces: poți solicita o copie a datelor tale personale (sau folosi exportul din aplicație)
- Dreptul la rectificare: poți corecta datele inexacte
- Dreptul la ștergere: poți solicita ștergerea datelor tale (sau folosi ștergerea contului din aplicație)
- Dreptul la portabilitate: poți solicita transferul datelor tale
- Dreptul de retragere a consimțământului: pentru sincronizarea datelor agregate de sănătate, direct din aplicație

**Contact pentru cereri GDPR:** davidmanda1998@gmail.com

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
davidmanda1998@gmail.com
