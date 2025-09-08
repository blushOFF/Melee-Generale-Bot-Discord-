# LoL Arena — Bot Lobbies (Privé)

👋 Bienvenue !  
Ce bot Discord sert à organiser des **lobby d'Arena privés** sur *League of Legends* entre membres de la communauté, facilement et sans prise de tête.  

✔️ Trouve des joueurs rapidement  
✔️ Lance une partie quand tu veux  
✔️ Profite de règles claires et d’un système anti-abus  

ℹ️ **Le bot est privé (non open-source) et réservé à notre serveur.**

---

## 🚀 Pourquoi ce bot est utile

- **Trouver des games rapidement** : annonces de lobbies + bouton `Rejoindre`.  
- **Parties plus propres** : vérification Riot, filtres de rang, bans simples.  
- **Progression & fun** : leaderboard et historique de parties.  
- **Fair-play protégé** : signalements faciles, sanctions graduelles, anti-contournement de ban.  

---

## 🎮 Comment jouer

### 1) Vérifie ton compte
- Quand tu rejoins le serveur, le bot te demandera ton **RiotID#TAG** et de changer ton **icône de profil**.  
- Si ça échoue : va dans **#Vérification**, ouvre un fil et mentionne un modérateur.  
➡️ Objectif : éviter les *smurfs* et l’évasion de sanctions.  

### 2) Rejoins un lobby
- Consulte le salon **d’annonces** et clique `Rejoindre le lobby`.  
- Si le lobby est plein/fermé/en cours → bouton grisé.  
- Besoin de partir ? Utilise `/leave`.  

### 3) Règles simples
- Respecte les bans (catégories + champions spécifiques).  
- Suis les instructions du **host**.  
- Signale un comportement avec `/report @user reason:`  

---

## 🏠 Héberger un lobby (Host)

1. Va dans **#Host** et appuie sur `Host`.  
2. Clique sur `Personnaliser` pour ouvrir le panel éphémère :  
   - **Rangs autorisés** (UNRANKED, GOLD, DIAMOND…).  
   - **Bans** : catégories (Ranged, Changeformes…) + champions.  
3. Ouvre le lobby → une annonce est publiée avec `Rejoindre`.  
4. Les rôles de rang sont pingés selon règles :  
   - UNRANKED + autre rang → ping UNRANKED seulement.  
   - Tous les rangs → ping UNRANKED seulement.  
5. Tu peux **Fermer / Rouvrir** le lobby à tout moment (le message d’annonce s’actualise).  

---

## 🚨 Signalements & Fair-play

### Signaler un joueur
```bash
/report @user reason:
```

➡️ Transmis dans un salon staff dédié.  
➡️ Confirmation envoyée en message privé.  

### Barème des sanctions
- **Infractions légères** (ex : ban d’un champion)  
  ⚠️ Warn → Warn → 🔇 Mute 6h → 🔇 Mute 2j → Grave.  

- **Infractions graves** (ex : bravery, pick interdit)  
  🔇 Mute 5j → 🔇 1 semaine → 🔇 1 mois → 🔨 Ban permanent.  

🚫 **Interdit bot** : le joueur reste sur le serveur mais ne peut plus utiliser le bot.  
🛡️ Le bot détecte l’évasion via la vérification Riot (PUUID).  

---

## 🏆 Leaderboard & Résultats

Après chaque partie, le bot lit le match via Riot **Match-V5** et met à jour :  
- Le **leaderboard** (points, parties jouées).  
- Les infos du lobby (complet, en cours, fermé).  
- L’annonce (joueurs, état du bouton).  

---

## 🔧 Commandes utiles

- `/leave` → quitter le lobby.  
- `/report @user reason:` → signaler un joueur.  

*Les autres actions (host, personnalisation, fermeture…) se font via les boutons du lobby.*  

---

## ❓ FAQ

**Je ne peux pas cliquer sur “Rejoindre le lobby”.**  
➡️ Lobby plein/fermé/en cours.  
➡️ Ton rang n’est pas autorisé.  
➡️ Tu es déjà dans un lobby.  
➡️ Tu es interdit d’utiliser le bot (contacte le staff).  

**La vérification par icône échoue.**  
➡️ Choisis l’icône demandée, clique `J’ai changé`.  
➡️ Sinon → contacte un staff.  

**J’ai été mute/banni.**  
➡️ Lis la raison en DM et contacte poliment le staff pour un recours.  

---

## 🔒 Données & Confidentialité

- Stockage minimal : **Discord ID, PUUID Riot, stats, historique sanctions**.  
- Pas de partage externe.  
- Consultation/suppression possible (selon contraintes de modération).  

---

## 🆘 Support

- Ouvre un ticket dans **#help**.  
- DM le staff avec **contexte + capture** si bug.  

---

## 📖 À propos

- Utilise les API Riot : Account-V1, Summoner-V4, League-V4, Match-V5.  
- Projet privé → améliorer l’expérience de jeu en Arène.  

[![Discord](https://img.shields.io/badge/Rejoindre-Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white)]((https://discord.gg/UbByf6w9kh))

