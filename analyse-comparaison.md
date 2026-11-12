# Blockchain publique, registre permissionné ou base de données classique ?

Étude comparative appliquée à un cas concret : **le transfert d'argent de la diaspora marocaine vers le Maroc**.

Auteur : Khaoula Boudarja, Master en Finance appliquée (option Fintech), Université Cadi Ayyad, Marrakech

---

## 1. Le cas étudié

Un Marocain résidant à l'étranger envoie régulièrement de l'argent à sa famille au Maroc. Aujourd'hui, ce transfert passe par des banques ou des sociétés de transfert, avec plusieurs intermédiaires. Les points sensibles sont les frais, les délais, la transparence du taux de change et le respect de la réglementation (identification des clients, lutte contre le blanchiment).

**Question** : parmi les trois technologies ci-dessous, laquelle conviendrait le mieux pour enregistrer et suivre ces transferts ?

## 2. Les trois options

| Option | Principe | Exemple |
|---|---|---|
| **Blockchain publique** | Registre ouvert à tous, sans autorité centrale. Chacun peut lire et vérifier. | Bitcoin, Ethereum |
| **Registre distribué permissionné** | Registre partagé entre des membres connus et autorisés (banques, régulateur). | Hyperledger Fabric |
| **Base de données classique** | Registre tenu par une seule organisation, qui contrôle tout. | Base SQL d'une banque |

## 3. Comparaison selon des critères concrets

| Critère | Blockchain publique | Registre permissionné | Base de données classique |
|---|---|---|---|
| Qui contrôle ? | Personne (réseau ouvert) | Un groupe de membres connus | Une seule organisation |
| Confiance nécessaire entre les acteurs | Très faible | Moyenne | Forte (on fait confiance à l'organisation) |
| Transparence | Très forte (tout est public) | Contrôlée (selon les droits) | Faible (interne) |
| Confidentialité des clients | Faible (données visibles) | Bonne (accès restreint) | Bonne |
| Identification des clients (KYC) | Difficile (pseudonymes) | Possible | Possible |
| Rapidité et coût | Variable, frais selon la congestion | Rapide, coûts maîtrisés | Très rapide, peu coûteux |
| Modification de l'historique | Quasi impossible | Très difficile | Possible par l'administrateur |
| Conformité réglementaire | Délicate | Plus facile à encadrer | Facile |

## 4. Analyse

**Blockchain publique.** Elle apporte la transparence et supprime les intermédiaires. Mais les données sont visibles de tous, l'identification des clients est difficile et la volatilité des cryptomonnaies (par exemple Bitcoin) est un risque pour un transfert d'argent du quotidien. Elle convient mal à des virements bancaires réglementés.

**Registre permissionné.** Il permet à plusieurs banques et au régulateur de partager un même registre fiable, sans qu'une seule partie ne le contrôle seule. Les participants sont identifiés, ce qui facilite le respect de la réglementation. Son inconvénient est qu'il demande de la coordination entre les membres et une gouvernance claire.

**Base de données classique.** Elle est simple, rapide et peu coûteuse. Elle suffit si une seule organisation gère tout. Mais quand plusieurs banques doivent se faire confiance, chacune garde son propre registre, ce qui crée des rapprochements, des délais et des litiges.

## 5. Conclusion

Pour ce cas, le **registre permissionné** semble le meilleur compromis : plusieurs acteurs (banque d'envoi, banque de réception, régulateur) partagent un registre commun, vérifiable et difficile à modifier, tout en gardant l'identification des clients et la confidentialité.

La **blockchain publique** reste pertinente pour d'autres usages (preuve d'existence, actifs numériques). La **base de données classique** reste le bon choix quand une seule organisation gère le processus.

## 6. Limites de l'étude

- C'est une analyse théorique, sans test sur un vrai système.
- Les coûts et les délais dépendent des réseaux et des partenaires et doivent être vérifiés avec des données récentes.
- Le cadre réglementaire marocain sur les actifs numériques évolue : il faut le vérifier auprès de sources officielles (par exemple Bank Al-Maghrib).

## 7. Sources

- Satoshi Nakamoto, *Bitcoin: A Peer-to-Peer Electronic Cash System* (2008), bitcoin.org
- Documentation Hyperledger Fabric, hyperledger-fabric.readthedocs.io
- Cours Blockchain, Master Fintech, UCA (A. Elbasri)
- - Office des changes, bulletin des indicateurs mensuels des échanges extérieurs (30 octobre 2026), relayé par allAfrica : « Maroc : L'apport des MRE en transferts et en tourisme… », https://fr.allafrica.com/stories/202611030228.html
- Hespress FR, « Actifs numériques : ce que prévoit le projet de loi 42.25 », 9 novembre 2025, https://fr.hespress.com/449112-actifs-numeriques-ce-que-prevoit-le-projet-de-loi-42-25.html

## 8. Outils utilisés

Rédaction assistée par un assistant d'IA (Claude) pour structurer le plan et le tableau comparatif, puis relue et adaptée par l'auteur.
