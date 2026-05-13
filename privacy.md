# Politique de Confidentialité — IzyPrix
Dernière mise à jour : 24 mai 2024

L’application **IzyPrix** (package : `com.izysuite.izyprix`), développée par **IzySuite**, est un outil professionnel destiné à la gestion des prix au sein du magasin ProAlim (Elsau).  
Nous accordons une importance capitale à la protection de votre vie privée.

---

## 1. Données collectées et accès

### 1.1. Caméra (Scanner de codes-barres)
IzyPrix demande l'accès à la caméra uniquement pour scanner les codes-barres EAN-13 des produits.

- **Traitement local :** L’analyse de l’image est effectuée directement sur l’appareil via la bibliothèque Google ML Kit.  
- **Confidentialité :** Aucune image ou vidéo n’est enregistrée, stockée ou transmise à des tiers.

---

### 1.2. État du réseau et Wi-Fi
L’application vérifie uniquement si l’appareil est connecté à un réseau Wi‑Fi.

- **Usage :** Cette vérification sert uniquement à s’assurer que l’appareil peut communiquer avec le serveur local et l’imprimante du magasin ProAlim.  
- **Vie privée :** IzyPrix ne collecte aucune donnée de localisation et ne lit pas le nom (SSID) du réseau Wi‑Fi.

---

### 1.3. Communications Serveur
- **Serveur local :** L’application communique avec l’adresse IP locale du magasin (192.168.x.x) pour récupérer les informations produits et envoyer les ordres d’impression.  
- **Configuration dynamique :** Au démarrage, l’application effectue une unique requête vers un fichier texte sécurisé hébergé sur GitHub (Gist) afin d’obtenir l’adresse IP actuelle du serveur du magasin.  
  Aucune donnée personnelle n’est envoyée lors de cette requête.

---

## 2. Utilisation des données
Les données manipulées par l’application (codes-barres, noms de produits, prix) sont utilisées exclusivement pour :

- identifier les articles en rayon,  
- afficher les informations produits,  
- imprimer des étiquettes de prix physiques.

Aucune donnée n’est utilisée à d’autres fins.

---

## 3. Stockage et Conservation
- **Données personnelles :** Aucune donnée personnelle n’est collectée (pas de compte utilisateur, pas de nom, pas d’email).  
- **Données locales :** Seules les préférences d’affichage (ex : limite de caractères des étiquettes) sont stockées dans la mémoire privée de l’application sur l’appareil.

Ces données sont supprimées automatiquement lors de la désinstallation de l’application.

---

## 4. Partage avec des tiers
IzyPrix est une application **sans publicité** et **sans traqueur**.

- Aucune donnée n’est vendue ou partagée avec des régies publicitaires.  
- Aucune donnée n’est transmise à des services d’analyse tiers.

---

## 5. Sécurité
Bien que l’application utilise le protocole HTTP pour la communication locale (nécessaire pour les serveurs internes), l’accès est strictement limité au réseau privé du magasin ProAlim.

Aucune communication externe non documentée n’est effectuée.

---

## 6. Contact
Pour toute question ou demande concernant vos données :

📧 **izysuite.dev@gmail.com**

---

# Privacy Policy — IzyPrix
Last updated: May 24, 2024

The **IzyPrix** application (package: `com.izysuite.izyprix`), developed by **IzySuite**, is a professional tool used for price management inside the ProAlim store (Elsau).  
We are committed to protecting your privacy and ensuring transparent data practices.

---

## 1. Data Collected and Access

### 1.1. Camera (Barcode Scanner)
IzyPrix requests access to the device camera solely to scan EAN‑13 product barcodes.

- **Local processing:** All image analysis is performed directly on the device using Google ML Kit.  
- **Privacy:** No images or videos are recorded, stored, or transmitted to any third party.

---

### 1.2. Network State and Wi‑Fi
The application only checks whether the device is connected to a Wi‑Fi network.

- **Purpose:** This check ensures that the device can communicate with the store’s local server and label printer.  
- **Privacy:** IzyPrix does **not** collect location data and does **not** read the Wi‑Fi network name (SSID).

---

### 1.3. Server Communications
- **Local server:** The application communicates with the store’s local IP address (192.168.x.x) to retrieve product information and send print commands.  
- **Dynamic configuration:** On startup, the app performs a single request to a secure GitHub Gist text file to obtain the current server IP address.  
  No personal data is sent during this request.

---

## 2. Use of Data
The data handled by the application (barcodes, product names, prices) is used exclusively to:

- identify products on shelves,  
- display product information,  
- print physical price labels.

No data is used for any other purpose.

---

## 3. Storage and Retention
- **Personal data:** None. The app does not collect names, emails, accounts, or any personal identifiers.  
- **Local data:** Only display preferences (e.g., label character limits) are stored locally in the app’s private storage.

All locally stored data is removed when the app is uninstalled.

---

## 4. Sharing with Third Parties
IzyPrix is an application **without advertising** and **without tracking**.

- No data is sold or shared with advertising networks.  
- No data is transmitted to analytics services or external partners.

---

## 5. Security
Although the application uses HTTP for local communication (required for internal store servers), access is strictly limited to the private ProAlim network.

No undocumented external communication is performed.

---

## 6. Contact
For any questions or requests regarding your data:

📧 **izysuite.dev@gmail.com**
