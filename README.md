# LoL Arena — Bot Lobbies (Privé)

Bienvenue 👋
Ce bot Discord sert à organiser des lobbies d’Arène privés sur League of Legends entre membres de la communauté, facilement et sans prise de tête. Tu peux rencontrer d’autres joueurs, lancer une partie quand tu veux, avec des règles claires et un système anti-abus.

ℹ️ Le bot est privé (non open-source) et réservé à notre serveur.

Pourquoi ce bot est utile

Trouver des games rapidement : annonces de lobbies + bouton “Rejoindre”.

Parties plus propres : vérification Riot, filtres de rang, bans simples.

Progression & fun : leaderboard et historique de parties.

Fair-play protégé : signalements faciles, sanctions graduelles, anti-évasion.

Comment jouer (côté joueur)
1) Vérifie ton compte

Tape /verif et suis l’étape “icône de profil”.
Objectif : éviter les smurfs et l’évasion de sanctions.

2) Rejoins un lobby

Regarde le salon d’annonces (ex. #annonces-arena) et clique “Rejoindre le lobby”.
Si le lobby est plein/fermé/en cours, le bouton est grisé.

Besoin de partir ? Utilise /leave pour quitter proprement.

3) Règles simples

Respecte les bans du lobby (catégories + champions spécifiques).

Suis le host pour l’ouverture, le lancement et la fin de game.

Signale un comportement avec /report @user reason:.

Héberger un lobby (côté host)

Tape /lobbies pour créer ton salon de lobby privé.

Clique “Personnaliser” dans le message du lobby pour ouvrir le panel éphémère :

Rangs autorisés (UNRANKED, GOLD, DIAMOND…)

Bans : catégories (Ranged, Changeformes) et champions spécifiques.

Ouvrir le lobby : une annonce est postée avec un bouton “Rejoindre”.

L’annonce ping des rôles de rang pertinents (voir ci-dessous).

Pas de reping lors des réouvertures ultérieures.

Fermer / Rouvrir quand tu veux (le message d’annonce s’actualise).

Règles de ping par rang :

UNRANKED + n’importe quel autre rang → ping UNRANKED seulement.

Tous les rangs sélectionnés → ping UNRANKED seulement.

Signalements & Fair-play
Signaler un joueur

/report @user reason:
→ Envoi au salon staff dédié.
→ Tu reçois un message privé de confirmation.

Barème des sanctions (appliquées par le staff)

Légères (ex. ban d’un champion)

⚠️ Warn → 2) ⚠️ Warn → 3) 🔇 Mute 6h → 4) 🔇 Mute 2 jours → 5e+ = Grave

Graves (ex. bravery, pick interdit)

🔇 Mute 5 jours → 2) 🔇 1 semaine → 3) 🔇 1 mois → 4) 🔨 Ban permanent

Interdit : l’utilisateur peut parler sur le serveur mais ne peut plus utiliser le bot (pas de join/host).

Le bot détecte l’évasion de sanction via la vérification Riot (PUUID).
Si détection : ban permanent des deux comptes + alerte staff.

Leaderboard & résultats

Après chaque partie, le bot lit le match (Riot Match-V5) et met à jour :

Le leaderboard (points, parties jouées),

Les infos du lobby (complet, en cours, fermé),

L’annonce (players, état du bouton…).

Commandes utiles (joueurs)

/verif — Vérifier ton compte via icône de profil.

/lobbies — Créer/voir ton lobby (si host).

/leave — Quitter le lobby en cours.

/report @user reason: — Signaler un utilisateur.

Les actions du host (personnalisation, ouvrir/fermer…) se font via les boutons sur le message du lobby.

Commandes staff (réservé, non visibles pour non-staff)

/sanction — Appliquer le barème (légère/grave).

/warn @user reason: — Avertissement (DM).

/mute @user time: reason: send: — Mute + rôle “Muted”, auto-fin si durée.

/ban_temp @user time: reason: send: — Ban temporaire, auto-unban.

/ban_perm @user reason: send: — Ban permanent.

/unmute @user, /unban user_id, /warn_delete id:

/interdit @user time: reason: — Bloque l’accès au bot (peut parler).

/mod_list @user scope: — Récap (warns, bans, mutes, global).

/profile @user — Fiche complète : Discord/Riot, stats serveur, sanctions, note privée.

/mod_desc @user desc: — Définir/mettre à jour la note privée staff (visible via /profile).

FAQ

Je ne peux pas cliquer sur “Rejoindre le lobby”.
→ Lobby plein, fermé ou en cours.
→ Ton rang n’est pas autorisé.
→ Tu es déjà dans un autre lobby.
→ Tu es interdit d’utiliser le bot (contacte le staff).

La vérification par icône échoue.
→ Sélectionne exactement l’icône demandée, puis clique “J’ai changé”.

J’ai été mute/banni.
→ Lis la raison en DM et contacte poliment le staff pour un recours.

Données & confidentialité

Stockage minimal : Discord ID, PUUID Riot, stats de lobby/leaderboard, historique sanctions.

Pas de partage à des tiers. Données internes à la communauté.

Sur demande raisonnable : consultation/suppression (selon contraintes de modération).

Support

Ouvre un ticket dans #help ou DM le staff.

Pour un bug (boutons, annonces, vérif), donne un contexte + capture si possible.

À propos

Le bot utilise les API Riot (Account-V1, Summoner-V4, League-V4, Match-V5) pour la vérification et les résultats.
Projet privé, pensé pour améliorer l’expérience de jeu en Arène : organiser, jouer, progresser — tout simplement.

GL HF ! 🎮✨
