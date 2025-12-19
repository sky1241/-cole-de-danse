# Haoyan Wuying — Site vitrine (HTML/CSS/JS statique)

**Live :** https://haoyanwuying.com  
Public cible : parents/élèves (Chine, mobile-first)

## Contact rapide (Chine)
- Téléphone : `+86 155-2830-2653` (lien `tel:` actif)
- WeChat : ID **Sspark_** (bouton “复制微信号” + QR intégré)
- Formulaire : copie automatique du message, invite à coller dans WeChat (aucun envoi serveur)

## Fonctionnalités principales
- One-page HTML/CSS/JS (no build, no backend)
- Scroll fluide, animations, bouton retour haut, boutons flottants mobile (WeChat + appel)
- Carte Baidu (iframe) + lien externe Baidu Maps
- Données structurées (schema.org DanceSchool), sitemap + robots
- Domaine custom : `haoyanwuying.com` (CNAME GitHub Pages)

## État SEO / Suivi
- Canonical + sitemap/robots OK
- **Baidu verification** : non configuré (nécessite compte Baidu + numéro chinois)
- Analytics : aucun (Baidu Analytics en placeholder)

## À faire (priorité)
1) (Optionnel) **Baidu Webmaster** : obtenir le code de vérif depuis un compte Baidu (numéro chinois requis)  
2) Ajouter des **photos réelles** (cours/salle/élèves) + avis réels  
3) Si besoin d’un vrai formulaire/email : brancher Formspree ou un backend  
4) Si lenteur en Chine : envisager hébergement HK/SG ou Mainland (ICP)

## Structure
```
-cole-de-danse/
├─ index.html            # Page unique
├─ README.md             # Ce fichier
├─ robots.txt
├─ sitemap.xml
├─ CNAME                 # haoyanwuying.com
├─ elle/                 # Assets (photos, QR)
├─ p1.png p2.png p3.png  # Galerie
└─ 33393039-dancing-girl...jpg # Silhouette
```

## Développement local
Ouvrir `index.html` dans le navigateur (pas de dépendances).
