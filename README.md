# MMIGED — GED MMI : classement, indexation et gestion des documents.

> Module Dolibarr **MMIGED** (version 1.0), branche `20.0`.

## Fonctionnalités

### Fonctionnalités principales

- Classement, indexation et gestion électronique des documents.
- Menus et configuration GED.

### Pages

- `admin/about.php`
- `admin/setup.php`
- `mmigedindex.php`

### Configuration

| Constante | Type | Rôle |
|---|---|---|
| `MMIGED_PRODUCT_DOC` | yesno | Champs produit pour associer des docs techbnique & BDC fournisseur |

### Classes et composants

- `lib/mmiged.lib.php`

## Prérequis

- Dolibarr >= 11.0 (branche `20.0` : Dolibarr 20.0).
- Modules MMI : `mmicommon`. **`mmicommon` doit être activé en premier.**
- Modules cœur : `eCM`.

## Installation

1. Copier le module dans `htdocs/custom/mmiged` :

   ```sh
   cd htdocs/custom
   git clone <dépôt> mmiged
   ```

2. Dans Dolibarr : **Configuration → Modules**, activer d'abord `mmicommon`, puis ce module.
3. Vérifier les permissions dans la fiche des utilisateurs concernés.

## Licence

GPLv3 ou ultérieure — voir `COPYING`. Documentation sous GFDL.

## Changelog

Voir [CHANGELOG.md](CHANGELOG.md) (évolutions datées).
