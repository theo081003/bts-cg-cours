# Chapitre 4 — Les Amortissements et Depreciations

**Matiere :** Comptabilite Generale
**Chapitre :** 4
**Niveau :** BTS CG
**Date :** 2026-06-21

---

## 1. Definition

L'amortissement est la constatation comptable de la perte de valeur irreversible d'une immobilisation du fait de l'usure, du temps ou de l'obsolescence.

**Base amortissable =** Cout d'acquisition - Valeur residuelle

---

## 2. Les Modes d'Amortissement

### Amortissement Lineaire

Taux = 100 / Duree de vie (en annees)

**Exemple :** Materiel industriel 20 000 €, duree 5 ans

| Annee | Base | Taux | Annuité | Cumul | VNC |
|-------|------|------|---------|-------|-----|
| N | 20 000 | 20% | 4 000 | 4 000 | 16 000 |
| N+1 | 20 000 | 20% | 4 000 | 8 000 | 12 000 |
| N+2 | 20 000 | 20% | 4 000 | 12 000 | 8 000 |
| N+3 | 20 000 | 20% | 4 000 | 16 000 | 4 000 |
| N+4 | 20 000 | 20% | 4 000 | 20 000 | 0 |

### Amortissement Degressif

Taux degressif = Taux lineaire x Coefficient fiscal

| Duree | Coefficient |
|-------|-------------|
| 3-4 ans | 1,25 |
| 5-6 ans | 1,75 |
| > 6 ans | 2,25 |

---

## 3. Enregistrement Comptable

### Dotations aux amortissements

| Date | N° | Compte | Libelle | Debit | Credit |
|------|----|--------|---------|-------|--------|
| 31/12 | A01 | 6811 | Dotations amort. immo | 4 000 | |
| | | 2815 | Amort. materiel ind. | | 4 000 |

---

## 4. Les Depreciations

Contrairement a l'amortissement, la depreciation est une perte de valeur **non irreversible** (ouvrir ou fluctuation de marche).

**Ecriture de depreciation :**

| Date | N° | Compte | Libelle | Debit | Credit |
|------|----|--------|---------|-------|--------|
| 31/12 | D01 | 6817 | Dotations dep. immo | 2 000 | |
| | | 2915 | Dep. materiel ind. | | 2 000 |

**Reprise de depreciation :**

| Date | N° | Compte | Libelle | Debit | Credit |
|------|----|--------|---------|-------|--------|
| 31/12 | R01 | 2915 | Dep. materiel ind. | 1 000 | |
| | | 7817 | Reprise dep. immo | | 1 000 |

---

## 5. Exercice

Un materiel industriel est achete le 01/07/N pour 24 000 € HT. Duree de vie : 5 ans. Taux degressif.

**Questions :**
1. Calculez le taux degressif
2. Calculez les amortissements pour les annees N a N+4
3. Passez les ecritures de dotation

<details>
<summary> Correction/summary>

**1. Taux degressif :**
Taux lineaire = 100 / 5 = 20%
Taux degressif = 20% x 1,75 = **35%**

**2. Tableau :**

| Annee | VNB debut | Annuité | Cumul | VNC fin |
|-------|-----------|---------|-------|---------|
| N (6/12) | 24 000 | 4 200 | 4 200 | 19 800 |
| N+1 | 19 800 | 6 930 | 11 130 | 12 870 |
| N+2 | 12 870 | 4 504 | 15 634 | 8 366 |
| N+3 | 8 366 | 2 788 | 18 422 | 5 578 |
| N+4 | 5 578 | 5 578 | 24 000 | 0 |

> A partir de N+2, le taux lineaire sur la VNC devient superieur au taux degressif.

**3. Ecritures de dotation N :**

| Date | N° | Compte | Libelle | Debit | Credit |
|------|----|--------|---------|-------|--------|
| 31/12 | A01 | 6811 | Dotations amort. | 4 200 | |
| | | 2815 | Amort. materiel | | 4 200 |

</details>

---

## A Retenir

> **Amortissement =** Repartition systematique du cout d'une immobilisation sur sa duree de vie.
> **Depreciation =** Constat d'une baisse de valeur non irreversible, reversible si les conditions changent.
> **VNC = Valeur Nette Comptable =** Cout - Amortissements cumules - Depreciations
