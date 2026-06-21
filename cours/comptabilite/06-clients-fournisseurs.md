---
title: "Comptabilité Clients et Fournisseurs"
subject: "Comptabilité"
difficulty: "Intermédiaire"
timestamp: "2026-06-20T23:00:00+0200"
---

# Chapitre 6 : Comptabilité Clients et Fournisseurs

La comptabilisation des clients et fournisseurs est centrale en comptabilité générale. Elle couvre :
- Les opérations d'achat (classe 40)
- Les opérations de vente (classe 41)
- Le suivi des règlements

## 1. Les Comptes de Tiers (Classe 4)

La classe 4 regroupe les comptes de tiers, c'est-à-dire toutes les personnes physiques ou morales en relation financière avec l'entreprise.

### 1.1 Principaux comptes utilisés

| Numéro | Intitulé |
|--------|----------|
| 401 | Fournisseurs |
| 4011 | Fournisseurs - Achats de biens et services |
| 4091 | Fournisseurs - Créances |
| 4094 | Fournisseurs - Avances |
| 4096 | Fournisseurs - Factures non parvenues |
| 4097 | Fournisseurs - Autres avoirs |
| 411 | Clients |
| 4111 | Clients - Ventes de biens et services |
| 4191 | Clients - Acomptes |
| 4194 | Clients - Factures à établir |
| 4197 | Clients - Autres créances |
| 4198 | Clients - Factures contestables |

### 1.2 Nature des comptes de tiers

- **Comptes créditeurs** (classe 40) : dettes envers les fournisseurs
- **Comptes débiteurs** (classe 41) : créances sur les clients
- **Comptes de régularisation** : 408, 409, 418, 419

---

## 2. Opérations d'Achat (Classe 40)

### 2.1 Enregistrement d'une facture d'achat

**Exemple** : Achat de marchandises 500€ HT, TVA 20%, paiement à 30 jours.

| Date | N° | Compte | Libellé | Débit | Crédit |
|------|-----|---------|---------|-------|--------|
| 05/03 | FAC001 | 607 | Achats marchandises | 500 | |
| | | 44566 | TVA déductible 20% | 100 | |
| | | 401 | Fournisseurs X | | 600 |

*Total TTC : 600€ (500 + 100)*

### 2.2 Écriture d'avoir (retour marchandises)

**Exemple** : Retour de marchandises pour 100€ HT, TVA 20%.

| Date | N° | Compte | Libellé | Débit | Crédit |
|------|-----|---------|---------|-------|--------|
| 15/03 | AV001 | 401 | Fournisseurs X | 120 | |
| | | 607 | RBA marchandises | | 100 |
| | | 44566 | TVA déductible 20% | | 20 |

### 2.3 Avance versée au fournisseur

**Exemple** : Avance de 300€ TTC sur commande (TVA 20%).

| Date | N° | Compte | Libellé | Débit | Crédit |
|------|-----|---------|---------|-------|--------|
| 01/03 | A001 | 4094 | Fournisseurs - Avances | 250 | |
| | | 44566 | TVA déductible 20% | 50 | |
| | | 512 | Banque | | 300 |

### 2.4 Facture non parvenue (FNP)

Lorsque la marchandise est reçue mais pas la facture en fin de mois.

**Exemple** : Réception 200€ HT non facturée au 31/03.

| Date | N° | Compte | Libellé | Débit | Crédit |
|------|-----|---------|---------|-------|--------|
| 31/03 | FNP | 607 | Achats marchandises | 200 | |
| | | 44566 | TVA déductible 20% | 40 | |
| | | 4096 | Fournisseurs - FNP | | 240 |

**À l'inverse, au 01/04 (contre-passation)** :

| Date | N° | Compte | Libellé | Débit | Crédit |
|------|-----|---------|---------|-------|--------|
| 01/04 | CP | 4096 | Fournisseurs - FNP | 240 | |
| | | 607 | Achats marchandises | | 200 |
| | | 44566 | TVA déductible 20% | | 40 |

---

## 3. Opérations de Vente (Classe 41)

### 3.1 Enregistrement d'une facture de vente

**Exemple** : Vente de produits finis 800€ HT, TVA 20%, paiement à 30 jours.

| Date | N° | Compte | Libellé | Débit | Crédit |
|------|-----|---------|---------|-------|--------|
| 10/03 | FAC002 | 411 | Clients Y | 960 | |
| | | 701 | Ventes produits finis | | 800 |
| | | 4431 | TVA collectée 20% | | 160 |

*Total TTC : 960€ (800 + 160)*

### 3.2 Avoir sur vente

**Exemple** : Avoir accordé 150€ HT, TVA 20%.

| Date | N° | Compte | Libellé | Débit | Crédit |
|------|-----|---------|---------|-------|--------|
| 20/03 | AV002 | 701 | RBA ventes produits | 150 | |
| | | 4431 | TVA collectée 20% | 30 | |
| | | 411 | Clients Y | | 180 |

### 3.3 Acompte reçu du client

**Exemple** : Acompte de 600€ TTC sur commande (TVA 20%).

| Date | N° | Compte | Libellé | Débit | Crédit |
|------|-----|---------|---------|-------|--------|
| 01/03 | A002 | 512 | Banque | 600 | |
| | | 4191 | Clients - Acomptes | | 500 |
| | | 4431 | TVA collectée 20% | | 100 |

### 3.4 Facture à établir (FAE)

Lorsque la prestation est réalisée mais la facture pas encore émise en fin de mois.

**Exemple** : Prestation 300€ HT comptabilisée au 31/03.

| Date | N° | Compte | Libellé | Débit | Crédit |
|------|-----|---------|---------|-------|--------|
| 31/03 | FAE | 4194 | Clients - FAE | 360 | |
| | | 706 | Prestations de services | | 300 |
| | | 4431 | TVA collectée 20% | | 60 |

**À l'inverse, au 01/04 (contre-passation)** :

| Date | N° | Compte | Libellé | Débit | Crédit |
|------|-----|---------|---------|-------|--------|
| 01/04 | CP | 706 | Prestations de services | 300 | |
| | | 4431 | TVA collectée 20% | 60 | |
| | | 4194 | Clients - FAE | | 360 |

---

## 4. Règlements et Escomptes

### 4.1 Règlement d'une facture achat

**Exemple** : Paiement 600€ par virement.

| Date | N° | Compte | Libellé | Débit | Crédit |
|------|-----|---------|---------|-------|--------|
| 30/03 | R001 | 401 | Fournisseurs X | 600 | |
| | | 512 | Banque | | 600 |

### 4.2 Encaissement d'une facture vente

| Date | N° | Compte | Libellé | Débit | Crédit |
|------|-----|---------|---------|-------|--------|
| 15/04 | E001 | 512 | Banque | 960 | |
| | | 411 | Clients Y | | 960 |

### 4.3 Escompte de règlement

**Exemple** : Escompte de 2% pour paiement anticipé sur facture de 1000€ HT.

| Date | N° | Compte | Libellé | Débit | Crédit |
|------|-----|---------|---------|-------|--------|
| 05/04 | E002 | 411 | Clients Z | 1200 | |
| | | 706 | Produits accessoires | | 20 |
| | | 4431 | TVA collectée 20% | | 4 |
| | | 701 | Ventes produits | | 980 |

**Au paiement (1200 - 24 = 1176€)** :

| Date | N° | Compte | Libellé | Débit | Crédit |
|------|-----|---------|---------|-------|--------|
| 10/04 | P001 | 512 | Banque | 1176 | |
| | | 665 | Escomptes accordés | | 24 |
| | | 411 | Clients Z | | 1200 |

---

## 5. Cas Particuliers

### 5.1 Créances douteuses

Lorsqu'un client est en défaut de paiement.

| Date | N° | Compte | Libellé | Débit | Crédit |
|------|-----|---------|---------|-------|--------|
| 31/12 | D001 | 654 | Pertes sur créances | 500 | |
| | | 491 | Provision créances douteuses | | 500 |

*(Ou via compte 654 directement si irrécouvrable)*

### 5.2 Règlements par effets de commerce

**Remise à l'escompte** :

| Date | N° | Compte | Libellé | Débit | Crédit |
|------|-----|---------|---------|-------|--------|
| 20/03 | REM | 5113 | Billets à escompter | 5000 | |
| | | 411 | Clients - Effets à recevoir | | 5000 |

**À l'échéance** :

| Date | N° | Compte | Libellé | Débit | Crédit |
|------|-----|---------|---------|-------|--------|
| 30/03 | ECH | 512 | Banque | 4950 | |
| | | 627 | Agios et commissions | 50 | |
| | | 5113 | Billets à escompter | | 5000 |

### 5.3 Règlement par chèque non provisionné

| Date | N° | Compte | Libellé | Débit | Crédit |
|------|-----|---------|---------|-------|--------|
| 15/04 | NP | 4118 | Clients - Chèques non provisionnés | 2000 | |
| | | 512 | Banque | | 2000 |

---

## 6. Suivi des Soldes - Balance Agée

### 6.1 Principe

La balance âgée classe les créances (clients) et dettes (fournisseurs) par durée d'échéance :
- Échu < 0 jour (non échu)
- Échu 0 à 30 jours
- Échu 31 à 60 jours
- Échu 61 à 90 jours
- Échu > 90 jours

### 6.2 Tableau de suivi clients

| Client | Solde | Non échu | 0-30 j | 31-60 j | 61-90 j | > 90 j |
|--------|-------|----------|--------|---------|---------|--------|
| Client A | 5 000 | 2 000 | 1 500 | 1 000 | 500 | 0 |
| Client B | 3 000 | 0 | 0 | 1 000 | 1 000 | 1 000 |
| **Total** | **8 000** | **2 000** | **1 500** | **2 000** | **1 500** | **1 000** |

---

## 7. A Retenir

- **Classe 40** = Dettes fournisseurs (comptes créditeurs)
- **Classe 41** = Créances clients (comptes débiteurs)
- **TVA** : 4456 (déductible) côté achet, 4431/4432 (collectée) côté vente
- **FNP / FAE** : Comptes de régularisation en fin de période
- **Acomptes** : compte 4094 (fournisseurs) ou 4191 (clients)
- **Balance âgée** : outil de suivi des échéances
- **Effets de commerce** : suivis dans les sous-comptes 411/401
- **Créances douteuses** : provision ou perte directe
- **Escomptes** : 665 (accordés) ou 765 (obtenus)

---

## 8. QCM

**1. Quel compte utiliser pour enregistrer un fournisseurs ?**
- a) 411
- b) 401
- c) 706
- *Réponse : b*

**2. Un avoir accordé à un client => le compte 411 est :**
- a) Débit
- b) Crédit
- c) Aucun effet
- *Réponse : b*

**3. La FNP est utilisée quand :**
- a) La facture est établie mais pas encore envoyée
- b) La marchandise est reçue mais pas encore facturée
- c) Le paiement n'a pas encore été effectué
- *Réponse : b*

**4. La balance âgée permet de :**
- a) Calculer la TVA dû
- b) Suivre les échéances de créances et dettes
- c) Faire le bilan de l'entreprise
- *Réponse : b*

**5. Quel compte pour les acomptes versés aux fournisseurs ?**
- a) 4191
- b) 4094
- c) 4456
- *Réponse : b*
