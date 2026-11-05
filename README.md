# Mbongo — Cryptomonnaie native sur blockchain à preuve d'enjeu (Cosmos SDK)

Projet du cours Blockchain et Cryptomonnaie — M1 Informatique, UNIKIN, Groupe 28.

## Équipe
- INGELE DWAMA Exauce
- LOBOTA SAMBI Akim
- KONGAWI DAGWA Jacques
- WAKA NGONGO Divin
## Description
Chaîne applicative (app-chain) créée avec Ignite CLI et le Cosmos SDK, utilisant le consensus CometBFT (preuve d'enjeu). Préfixe d'adresses : `mbongo`.

## Contenu du dépôt
Le projet est fourni dans l'archive `mbongo.zip` (à extraire avant utilisation).

## Lancer la chaîne en local
Prérequis : Go, Ignite CLI.

    unzip mbongo.zip
    cd mbongo
    ignite chain serve

## Modules utilisés
bank, staking, distribution, mint, slashing, gov (modules standard du Cosmos SDK).

## Tests réalisés
- Transfert de jetons entre deux comptes (module bank) : réussi.
- Délégation (staking) vers le validateur : réussie.
- Récompenses de staking : non nulles après délégation.

## État d'avancement
- Fait : chaîne lancée localement avec 1 validateur, transferts, délégation, récompenses.
- À faire : 3 validateurs, test de gouvernance, faucet, explorateur, déploiement cloud, documentation tokenomics.
