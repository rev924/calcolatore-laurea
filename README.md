
# Calcolo del voto di laurea

Una semplice applicazione web per calcolare la media ponderata degli esami (includendo la lode che pesa il CFU per 33), la base di laurea in centodecimi e una stima del voto finale, includendo un bonus legato ai CFU acquisiti entro il 30 settembre del terzo anno, ovvero un moltiplicatore del numero di CFU per 0.035.

## Funzionalità

- Inserimento dei voti di 19 esami universitari.
- Gestione del 30L, considerato equivalente a 33 nel calcolo della media.
- Calcolo automatico della media ponderata.
- Conversione della media in base di laurea su 110.
- Calcolo del bonus CFU.
- Aggiornamento automatico dei risultati quando si modificano i dati.
- Interfaccia responsive, utilizzabile da computer, tablet e smartphone.
- Nessuna installazione richiesta.

## Formule utilizzate

**Media ponderata**

La media viene calcolata utilizzando i CFU associati a ciascun esame, con un totale di 169 CFU ponderati.

**Base di laurea**

Base di laurea = Media ponderata × (110 / 30)

**Bonus CFU**

Bonus = CFU acquisiti entro il 30 settembre del terzo anno di iscrizione × 0,035

**Voto finale stimato**

Voto finale = Base di laurea + Bonus CFU

I risultati sono indicativi e devono essere verificati rispetto al regolamento ufficiale del proprio corso di laurea.

## Come utilizzare il sito

1. Apri il sito web.
2. Inserisci i voti dei 19 esami, utilizzando valori da 18 a 30 oppure `30L`.
3. Inserisci i CFU acquisiti entro settembre del terzo anno.
4. Consulta la media ponderata, la base di laurea, il bonus e il voto finale stimato.

## Tecnologie

- HTML
- CSS
- JavaScript
- GitHub Pages

## Privacy

I calcoli vengono eseguiti direttamente nel browser. I voti inseriti non vengono inviati a un server né salvati automaticamente in un database.

## Disclaimer

Questo progetto è uno strumento informativo e non sostituisce i criteri ufficiali di calcolo del voto di laurea stabiliti dall'università.
