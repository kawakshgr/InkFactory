# 🖋 Ink Factory — Guide d'utilisation

Application web de gestion pour la convention **Ink Factory 2026** à Lyon (18-19-20 Septembre).

---

## 📲 Accès à l'application

L'app est accessible à cette adresse :
**https://kawakshgr.github.io/InkFactory/**

### Ajouter à l'écran d'accueil iPhone

1. Ouvre l'URL dans **Safari** (important : pas dans une autre app)
2. Appuie sur le bouton **Partager** ↑ en bas
3. Fais défiler et choisis **"Sur l'écran d'accueil"**
4. Confirme avec **"Ajouter"**

Tu auras maintenant une icône d'app comme n'importe quelle autre application. À chaque ouverture, l'app se lance en plein écran sans la barre Safari.

### Compatibilité

- ✅ Safari iPhone / iPad (recommandé)
- ✅ Chrome / Safari / Firefox sur Mac
- ✅ Fonctionne hors-ligne une fois ouverte

---

## 📥 Premier import des données

L'app est livrée vide. La première étape est d'importer le fichier `.json` contenant les **287 artistes de la convention**.

### Procédure

1. Récupère le fichier **`inkfactory-artists-2026.json`**
2. Ouvre l'app
3. Appuie sur **💾 Données** en haut à droite
4. Appuie sur **⬆️ Importer**
5. Sélectionne le fichier `.json`
6. Confirme l'import

⚠️ **Important** : l'import remplace toutes les données existantes. Si tu as déjà des fiches enregistrées, exporte-les d'abord en sauvegarde.

---

## 🗂 Les onglets

L'app est organisée en 4 onglets :

### 📍 Aujourd'hui
Le tableau de bord du jour, avec :
- La date et le jour en grand
- Le nombre d'artistes présents aujourd'hui (selon leurs disponibilités)
- Le prochain événement avec compte à rebours
- Les autres événements de la journée
- Tes favoris présents aujourd'hui

### 🎨 Artistes
Toutes les fiches d'artistes :
- Photo, nom, studio
- Style(s) de tatouage
- Nationalité
- Emplacement dans le salon
- Disponibilités (vendredi, samedi, dimanche × matin/après-midi)
- Pitch de présentation
- Prononciation du nom
- Tags personnalisés
- Notes libres

### 🏪 Stands
Toutes les fiches de stands non-tatouage :
- Boutiques de vêtements
- Food trucks
- Galeries d'art
- Vendeurs d'objets
- etc.

### 📅 Événements
Tous les événements programmés :
- Démonstrations, concours, conférences, meet & greet
- Date et heure de début/fin
- Lieu et intervenant
- Rappels avec notifications iOS

---

## ⭐ Favoris

Sur chaque carte d'artiste ou de stand, une **étoile** en haut à droite te permet de marquer les fiches importantes.

Cas d'usage typiques :
- Têtes d'affiche à présenter en priorité
- Artistes avec qui tu as un rendez-vous
- Stands à ne pas manquer

**Astuce** : un filtre **"⭐ Favoris"** apparaît automatiquement au-dessus de la liste dès que tu as au moins un favori.

---

## 🏷 Tags

Tu peux ajouter des tags personnalisés à chaque artiste pour t'organiser.

### Comment ajouter un tag

1. Ouvre une fiche artiste, appuie sur **✏️ Modifier**
2. Descends jusqu'à **🏷 Tags**
3. Soit tu tapes ton tag et tu appuies sur **Entrée**
4. Soit tu tapes sur l'une des **suggestions** en dessous

### Tags suggérés automatiquement

- Interview prévue
- À présenter
- Tête d'affiche
- Concours
- VIP
- Photo OK
- Vu

Tu peux aussi créer tes propres tags (ex : "Samedi 14h scène A", "Vu lundi", etc.).

### Filtrer par tag

Une fois qu'un tag existe, il apparaît dans la barre de filtre au-dessus de la liste d'artistes. Tape dessus pour ne voir que les artistes avec ce tag.

---

## 🎤 Mode présentation

Pour ton rôle de speaker, c'est **la fonction principale** de l'app.

### Comment l'utiliser

1. Ouvre une fiche d'artiste
2. En bas, tape sur **🎤 Mode présentation**
3. L'écran passe en plein écran avec :
   - Photo en grand format carré
   - Nom en très gros (lisible à 1-2 mètres)
   - Prononciation en italique doré
   - Style, nationalité, emplacement
   - **Pitch de présentation** dans un cadre lisible
4. Le fond reprend la photo de l'artiste, floutée et zoomée
5. L'écran ne s'éteint pas pendant que tu parles (wake lock automatique)

### Remplir le pitch et la prononciation

Pour profiter pleinement du mode présentation, remplis ces deux champs sur chaque fiche d'artiste prioritaire :

- **🎤 Pitch de présentation** : 3-4 lignes que tu liras au micro. Soigne le texte, c'est ce que tu diras en public.
- **🗣 Prononciation** : indication phonétique pour les noms étrangers. Exemples :
  - Sören Sangkuhl → "So-renn Sang-cool"
  - Horishige → "Ho-ri-shi-gué"
  - Şükrü Erdem → "Chu-krou Er-dem"

---

## ⏰ Événements et rappels

### Créer un événement

1. Va sur l'onglet **📅 Événements**
2. Appuie sur le **＋** en bas à droite
3. Remplis le titre, la catégorie, la date/heure, le lieu
4. Dans la section **⏰ Rappels**, ajoute autant de rappels que tu veux

### Options de rappels disponibles

- Au moment de l'événement
- 5 / 15 / 30 minutes avant
- 1 heure / 2 heures avant
- La veille à 9h

### Pour que les notifications fonctionnent

1. Au premier rappel créé, Safari va demander la permission de notifier
2. Accepte
3. **Garde l'app ouverte en arrière-plan** ou ajoute-la à l'écran d'accueil

⚠️ Les notifications web sur iPhone sont limitées : l'app doit être ouverte (au moins en arrière-plan) pour que le rappel se déclenche.

---

## 🗺 Plan du salon

Le bouton **🗺 Plan** affiche une représentation simplifiée du salon avec 3 halls (A, B, C) et une scène.

### Comment ça marche

1. Chaque hall contient 16 stands numérotés (A01 à A16, B01 à B16, C01 à C16)
2. Si dans la fiche d'un artiste tu mets **A05** ou **Hall A – Stand A05** dans le champ **Emplacement**, le stand correspondant sur le plan devient violet
3. Si l'artiste est dans tes favoris ⭐, le stand devient doré
4. Tape sur n'importe quel stand pour voir qui s'y trouve

### Légende
- **Gris** : stand vide
- **Violet** : un artiste y est
- **Doré** : un favori y est

---

## 📊 Vue d'ensemble (Stats)

Le bouton **📊 Stats** affiche les statistiques globales :

- Nombre d'artistes / stands / événements / favoris / tagués / pays
- **Présence par jour** : combien d'artistes le vendredi, samedi, dimanche
- **Top nationalités** : les 8 pays les plus représentés
- **Top styles** : les 8 styles les plus représentés

Ces chiffres peuvent te servir au micro pour présenter la convention.

### Historique

Depuis la vue Stats, tu peux accéder à l'**🕐 Historique** : les 50 dernières modifications avec horodatage (créé, modifié, supprimé).

---

## 💾 Sauvegarder et restaurer

L'app stocke toutes les données **localement** dans ton navigateur. Pour éviter de tout perdre :

### Exporter une sauvegarde

1. Appuie sur **💾 Données**
2. Appuie sur **⬇️ Exporter**
3. Un fichier `.json` est téléchargé avec la date du jour
4. **Sur iPhone** : choisis "Enregistrer dans Fichiers" → **iCloud Drive** pour le retrouver sur tous tes appareils Apple

### Importer une sauvegarde

1. Appuie sur **💾 Données**
2. Appuie sur **⬆️ Importer**
3. Sélectionne le fichier `.json`
4. Confirme

⚠️ L'import **remplace toutes les données existantes**. Exporte avant d'importer si tu as des changements récents.

### Quand exporter ?

- **Avant chaque mise à jour de l'app** (au cas où)
- Pour transférer tes données entre Mac et iPhone
- Pour partager ta version enrichie avec d'autres speakers/organisateurs
- En sauvegarde de sécurité, régulièrement

---

## 📥 Import Excel

Pour ajouter beaucoup de fiches d'un coup, utilise l'import Excel.

### Procédure

1. Appuie sur **📥 Import** en haut
2. Choisis le type : Artistes / Stands / Événements
3. Tape sur **⬇️ Télécharger le modèle Excel** pour avoir le bon format
4. Remplis le fichier `.xlsx` sur ton ordinateur
5. Reviens dans l'app, tape sur la zone d'import et sélectionne ton fichier
6. Un aperçu s'affiche, vérifie, puis **Importer**

### Colonnes attendues

**Pour les artistes** : Nom, Style, Nationalité, Emplacement, Boutique, Instagram, Notes

**Pour les stands** : Nom, Ville, Emplacement, Spécialités, Contact, Notes

**Pour les événements** : Titre, Catégorie, Début (AAAA-MM-JJThh:mm), Fin, Lieu, Artiste, Notes

⚠️ Les **photos** et **disponibilités** ne sont pas importables par Excel — il faut les renseigner à la main dans l'app.

---

## 🎙 Recherche vocale

Dans l'onglet Artistes ou Stands, tape sur le **🎙** à droite de la barre de recherche pour dicter ta recherche en français.

Pratique quand tu cours dans la convention avec les mains prises.

---

## 🌊 Changer de thème

Le bouton 🌊 / 🌑 en haut à droite permet de basculer entre :

- **🖤 Studio Pro** (par défaut) : noir profond + accents rouge sang
  - Optimisé pour la batterie sur iPhone OLED (jusqu'à 40% d'autonomie en plus)
  - Plus discret en intérieur sombre
  - Plus confortable pour les yeux sur la durée

- **🌊 Irezumi** : crème papier ancien + indigo + vermillon
  - Esthétique japonaise traditionnelle
  - Plus chaleureux
  - À privilégier hors-convention (consomme plus sur OLED)

Ta préférence est sauvegardée.

---

## 🔄 Synchronisation entre appareils

L'app ne synchronise **pas automatiquement** entre tes appareils (pas de serveur, c'est voulu pour la confidentialité).

### Méthode manuelle via iCloud Drive

1. Sur ton Mac : export → enregistre le `.json` dans **iCloud Drive**
2. Sur ton iPhone : ouvre l'app → 💾 Données → ⬆️ Importer → sélectionne le même `.json`
3. Les données sont synchronisées

À refaire dans le sens inverse quand tu modifies sur l'iPhone et veux retrouver sur le Mac.

### Méthode rapide (AirDrop)

1. Export depuis l'appareil source
2. AirDrop le `.json` vers l'autre appareil
3. Import sur l'appareil cible

---

## 🚀 Workflow recommandé pour la convention

### Avant la convention (1-2 semaines avant)

1. Sur ton **Mac**, importe le `.json` initial avec les 287 artistes
2. Pour chaque artiste prioritaire :
   - Rédige le **pitch de présentation** au calme
   - Ajoute la **prononciation** si le nom est complexe
   - Marque en **⭐ favori**
   - Ajoute des **🏷 tags** ("Interview prévue", "Tête d'affiche"...)
3. Crée tes événements personnels avec rappels
4. Exporte ta sauvegarde et envoie-toi le `.json` par mail/AirDrop
5. Sur ton **iPhone**, importe le `.json`
6. Ajoute l'app à l'écran d'accueil

### Pendant la convention

- Utilise **📍 Aujourd'hui** comme dashboard principal
- Pour présenter quelqu'un au micro : ouvre sa fiche → **🎤 Mode présentation**
- Pour t'orienter : **🗺 Plan**
- Pour les photos avec les artistes : prend-les directement et ajoute-les via ✏️ Modifier

### Après chaque journée

- Exporte une sauvegarde le soir, au cas où

---

## 📞 Besoin d'aide ?

L'app est en constante évolution. Si tu veux :
- Ajouter des fonctionnalités
- Signaler un bug
- Mettre à jour les données

→ Contacte le développeur (toi ou Claude).

---

**Bonne convention InkFactory 2026 🖋**
