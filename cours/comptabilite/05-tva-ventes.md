# Chapitre 5 — La TVA et les Ventes

**Matiere :** Comptabilite Generale
**Chapitre :** 5
**Niveau :** BTS CG
**Date :** 2026-06-21

---

## 1. Les Taux de TVA en France

| Taux | Secteur d'application |
|------|----------------------|
| 20% | Taux normal — la plupart des biens et services |
| 10% | Taux intermediaire — travaux, restauration, hotel |
| 5,5% | Taux reduit — alimentation, livres, equipementenergetique |
| 2,1% | Taux super-reduit — medicaments, presse |

---

## 2. TVA Deductible et Collectee

### TVA Deductible (compte 4456)

Enregistree sur les **achats** et autres depenses.

| Date | N° | Compte | Libelle | Debit | Credit |
|------|----|--------|---------|-------|--------|
| 10/01 | A01 | 607 | Achat marchandises | 5 000 | |
| | | 44566 | TVA ded. 20% | 1 000 | |
| | | 401 | Fournisseurs | | 6 000 |

### TVA Collectee (compte 4457)

Enregistree sur les **ventes**.

| Date | N° | Compte | Libelle | Debit | Credit |
|------|----|--------|---------|-------|--------|
| 15/01 | V01 | 411 | Clients | 12 000 | |
| | | 707 | Ventes marchandises | | 10 000 |
| | | 44571 | TVA coll. 20% | | 2 000 |

---

## 3. Le Reglement de la TVA

| Type | Taux | Montant |
|------|------|---------|
| TVA ded. | — | 8 000 |
| TVA coll. | — | 15 000 |
| **TVA a decaisser** | — | **7 000** |

**Ecriture de liquidation :**

| Date | N° | Compte | Libelle | Debit | Credit |
|------|----|--------|---------|-------|--------|
| 31/01 | L01 | 44571 | TVA coll. 20% | 15 000 | |
| | | 44566 | TVA ded. 20% | | 8 000 |
| | | 44551 | TVA a decaisser | | 7 000 |

**Ecriture de paiement :**

| Date | N° | Compte | Libelle | Debit | Credit |
|------|----|--------|---------|-------|--------|
| 19/02 | P01 | 44551 | TVA a decaisser | 7 000 | |
| | | 512 | Banque | | 7 000 |

---

## 4. Les Factures de Doit et Avoir

### Facture de Doit (classique)

| Designation | QT | PU HT | Total HT | TVA 20% | Total TTC |
|------------|----|----|---------|--------|-----------|
| Materiel A | 5 | 100 | 500 | 100 | 600 |
| **Total** | | | **500** | **100** | **600** |

### Facture d'Avoir (retour ou ristourne)

| Designation | QT | PU HT | Total HT | TVA 20% | Total TTC |
|------------|----|----|---------|--------|-----------|
| Retour article | 2 | 100 | 200 | 40 | 240 |
| **Total** | | | **200** | **40** | **240** |

**Ecriture d'avoir :**

| Date | N° | Compte | Libelle | Debit | Credit |
|------|----|--------|---------|-------|--------|
| 20/01 | AV01 | 401 | Fournisseurs | 240 | |
| | | 607 | RBA marchandises | | 200 |
| | | 44566 | TVA ded. 20% | | 40 |

---

## 5. Les Acomptes

Lorsqu'un acompte est recu ou verse sur une commande.

| Date | N° | Compte | Libelle | Debit | Credit |
|------|----|--------|---------|-------|--------|
| 01/02 | A01 | 512 | Banque | 1 200 | |
| | | 4191 | Clients - Acomptes | | 1 000 |
| | | 44571 | TVA coll. 20% | | 200 |

---

## A Retenir

> **TVA collectee — TVA deductible = TVA a decaisser** (si positive)
> **TVA a decaisser — TVA a reporter** (si negative)
> **TVA exigeable** : a la livraison pour les ventes de biens, au paiement pour les services
