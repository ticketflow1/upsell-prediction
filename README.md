# Predikcija upsell-a - stablo odlucivanja i Random Forest

Prediktivni model koji na osnovu profila korisnika telekomunikacione kompanije
predvidja da li ce korisnik prilikom obnove ugovora preci na visi tarifni paket (upsell).

## Struktura

- `A1.ipynb` - kompletan tok: ucitavanje, priprema podataka, stablo odlucivanja,
  Random Forest, evaluacija i lift analiza
- `data/upsell_diplomski.xlsx` - skup podataka
- `lista_za_kampanju.xlsx` - izlaz modela: 5.000 korisnika sa najvisom procenjenom
  verovatnocom upsell-a, rangiranih opadajuce (user_id, Probability, Prediction)
- `requirements.txt` - potrebni paketi
