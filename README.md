# Robot Umanoid Mergător - Modelare Cinematică și Control PID

Proiect dezvoltat în cadrul disciplinei **Dinamica Sistemelor Mecatronice** (FIMM, UPB).

## 📌 Descriere Proiect
Proiectul se concentrează pe analiza cinematică și controlul unui robot umanoid biped simplificat. Obiectivul principal este generarea unei mișcări de mers stabile prin coordonarea a două articulații rotaționale per picior (șold și genunchi).

## 🚀 Module Tehnice

### 1. Modelare Cinematică
- **Convenția Denavit-Hartenberg:** Utilizată pentru definirea sistemelor de coordonate și calculul cinematicii directe.
- **Cinematică Inversă:** Implementarea soluțiilor analitice pentru determinarea unghiurilor articulare necesare atingerii unei poziții țintă a tălpii.
- **Matricea Jacobiană:** Calculată pentru transformarea vitezelor și analiza spațiului de lucru.

### 2. Controlul Mișcării
- **Controller PID:** Implementat independent pentru fiecare grad de libertate (4 DOF în total).
- **Model Dinamic:** Consideră momentul de inerție (I = 0.08 kg*m²) și frecarea vâscoasă (b = 0.02) pentru un comportament realist în simulare.
- **Reglaj Parametric:** Proces riguros de acordare a câștigurilor (Kp, Kd, Ki) pentru minimizarea oscilațiilor și a erorii de urmărire.

### 3. Simulare MATLAB
Proiectul include un script MATLAB care rulează o simulare numerică discretă ($dt=0.001s$), generând grafice pentru evoluția unghiulară a articulațiilor în timpul unui ciclu de mers.

## 🛠 Tehnologii
- **MATLAB:** Simulare numerică și vizualizare date.
- **Concepte:** DH Parameters, Jacobian Matrix, PID Control, Bipedal Locomotion.

---
*Autor: Neagu Mihnea – Student Mecatronică și Robotică*
