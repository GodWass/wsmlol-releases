# Politique de confidentialité — WSMLol

_Dernière mise à jour : 2026-09-30. Affichée dans l'app (écran À propos → Politique de confidentialité)._

## Données collectées

- **Riot ID** (`gameName#tagLine`) que tu saisis ou qui est lu depuis ton client LoL local, pour identifier ton compte.
- **PUUID** (identifiant Riot pseudonymisé), utilisé pour interroger l'API Riot en ton nom.
- **Région / plateforme** (ex. `euw1`), pour router les requêtes vers les bons serveurs Riot.
- **Données de partie publiques** (champion joué, résultat, statistiques de la partie) via l'API officielle match-v5. Pour l'historique de partie, cela inclut le Riot ID et les statistiques des 9 autres joueurs de chaque partie consultée — les mêmes informations que le client officiel League of Legends affiche déjà après chaque partie. Quand tu ouvres l'analyse complète d'une partie, WSMLol affiche aussi le **rang classé actuel** de ces joueurs (API officielle league-v4), comme le font les sites de statistiques et le récapitulatif de fin de partie. Aucune autre information de profil n'est consultée, et rien de tout cela n'est fait pendant le champ select.
- **Historique de rang** : à chaque rafraîchissement de ton profil, WSMLol enregistre ton rang, tes LP et ton nombre de victoires/défaites en classé (Riot ne fournit pas d'historique de LP). Sert uniquement à afficher ta courbe de LP.
- **Coéquipiers de tes parties de la saison** (« Duos de la saison ») : Riot ID, poste et champion des joueurs qui étaient dans TON équipe, tels qu'affichés dans tes propres récapitulatifs de fin de partie. Leur identifiant Riot interne (PUUID) n'est jamais transmis à l'application : seul un identifiant anonymisé sert à regrouper un même joueur.
- **Joueurs que tu recherches** (barre de recherche) : quand tu tapes un Riot ID complet (`Pseudo#TAG`), WSMLol affiche le profil public de ce joueur (rang, parties récentes, saison) via les mêmes API officielles, comme les sites de statistiques. Ces données publiques sont mises en cache sur notre serveur comme les tiennes. La recherche n'est jamais faite automatiquement, et jamais sur les joueurs d'un champ select. Pendant la saisie, WSMLol propose des joueurs déjà présents dans nos données publiques (profils déjà consultés, joueurs vus dans des récapitulatifs de partie) et tes dernières recherches, gardées uniquement sur ton ordinateur.
- **Partie en cours (écran de chargement)** : une fois ta partie lancée, WSMLol affiche pour les 10 joueurs (dont les noms sont alors affichés par le jeu lui-même) leur rang classé, leur winrate de la saison et leur maîtrise du champion joué, via les API officielles spectator-v5, league-v4 et champion-mastery-v4. Rien n'est consulté pendant le champ select.
- **Alliés en champ select, hors parties classées** : en normale, ARAM ou partie personnalisée, le client affiche les noms de tes alliés ; WSMLol affiche alors leur rang (API officielle league-v4) et permet d'ouvrir leur profil. En classé, où le client masque les noms, WSMLol n'affiche aucune identité.
- **Résumé de la chronologie d'une partie** (achats, objectifs, morts) que tu ouvres dans l'analyse post-game, via l'API officielle match-v5.

## Ce que nous ne collectons pas

- Aucune donnée cachée par le client officiel (identités masquées en champ select ranked).
- Aucune donnée issue de la mémoire du jeu ou d'une injection quelconque.
- Aucune donnée de paiement dans ce MVP (pas de fonctionnalité premium implémentée).

## Pourquoi ces données

Pour afficher ton profil, ton historique de parties, l'évolution de tes LP, tes duos de la saison, l'analyse de tes parties, et te fournir des suggestions de pick/ban/matchup pertinentes pour ton niveau et ta région.

## Combien de temps tes données sont conservées

- Profil (rang, icône, niveau) : mis en cache 10 minutes, puis re-demandé à Riot.
- Historique de parties : mis en cache de façon permanente une fois une partie terminée — Riot lui-même ne fait jamais changer le résultat d'une partie déjà jouée, ce n'est donc pas une donnée qui a besoin d'être rafraîchie. Ce cache accélère l'app et réduit les appels à l'API Riot, il ne sert à rien d'autre.
- Historique de rang : conservé pour afficher ta courbe de LP dans le temps, jusqu'à ta demande de suppression.
- Chronologie de partie (résumé) : mise en cache de façon permanente, comme l'historique (une partie terminée ne change plus).
- Localement sur ton ordinateur : tes Riot ID liés et tes préférences (thème, langue, région, couleur) restent stockés tant que tu ne les effaces pas.

## Comment supprimer tes données

- **Localement** : Paramètres → Comptes liés → « Retirer ce compte » efface ce Riot ID de ton ordinateur, immédiatement.
- **Côté serveur** (cache de ton profil/historique, historique de rang) : écris-nous à l'adresse ci-dessous en précisant ton Riot ID, on supprime les lignes correspondantes sous 30 jours. Pas encore de suppression en libre-service depuis l'app dans ce MVP — prévu pour une version ultérieure.

## Contact

Pour toute question ou demande de suppression de tes données : **abdiwassim4@gmail.com** (réponse sous 30 jours).
