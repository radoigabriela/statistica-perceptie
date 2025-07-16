# Proiect 8 – Percepția studenților asupra statisticii (analiză în R)

Acest repository conține o cercetare aplicată în R, având ca obiectiv analiza statistică a modului în care studenții percep statistica în funcție de variabile educaționale și cognitive. Lucrarea combină analiza descriptivă, testarea ipotezelor și construcția de modele statistice (regresii liniare și logistice).

## Structura cercetării

Cercetarea este împărțită în mai multe secțiuni, fiecare ilustrând o etapă distinctă a procesului științific:

- analiza descriptivă a variabilelor (medie, mediană, abatere standard)
- testarea distribuției normale cu Kolmogorov-Smirnov
- testarea ipotezelor de asociere (chi-pătrat, Spearman)
- regresie liniară multiplă pentru a estima influența gândirii critice și superstițioase asupra gândirii conspiraționiste
- regresie logistică pentru a analiza probabilitatea unui răspuns corect la un silogism
- evaluarea modelelor prin grafice de diagnoză, testul VIF și curba ROC

## Obiectivele proiectului

- Să investigăm relația dintre atitudinea față de statistică, relația cu profesorii, experiența tehnologică și performanța academică
- Să testăm corelații între competențele numerice și autoeficacitatea în matematică
- Să construim modele de predicție privind gândirea conspiraționistă și raționamentul logic

## Ce am aplicat în proiect

- funcții de bază pentru analiza datelor (mean, median, sd, summary, describe)
- teste de semnificație statistică: `chisq.test()`, `ks.test()`, `cor.test()`
- construcția și interpretarea unui model de regresie liniară: `lm()`
- construcția și interpretarea unui model de regresie logistică: `glm(family = binomial)`
- evaluarea modelelor: diagramele de reziduuri, VIF (`car`), curba ROC și AUC (`pROC`)

## Fișiere

- cod_analiza .R – scriptul R complet cu toate analizele  
- date_prelucrare_excel.xlsx – fișierul cu datele prelucrate folosite în analiză

## Proiect realizat în echipă
