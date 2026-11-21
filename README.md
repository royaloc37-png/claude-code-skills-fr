# 20 skills Claude Code en français

Les 20 skills que j'utilise avec Claude Code pour construire les outils de mon entreprise, et que je montre aux dirigeants et aux indépendants que je forme. Gratuits, en français, prêts à installer.

Par **Jean-Baptiste Roy**, fondateur de [BuildYourSaaS](https://buildyoursaas.tech).

## Un skill, c'est quoi ?

Un skill est un dossier qui contient un fichier `SKILL.md` : des instructions que Claude Code charge tout seul quand votre demande correspond à sa description. Vous pouvez aussi l'appeler par son nom, par exemple `/securite`. Le détail est dans la [documentation officielle d'Anthropic](https://code.claude.com/docs/en/skills), et je l'explique sans jargon dans [cet article](https://buildyoursaas.tech/blog/un-skill-claude-code-c-est-quoi-l-explication-des-lacets.html).

## Installer les skills

Pour les avoir dans tous vos projets :

```bash
git clone https://github.com/royaloc37-png/claude-code-skills-fr.git
mkdir -p ~/.claude/skills
cp -R claude-code-skills-fr/skills/* ~/.claude/skills/
```

Pour un seul projet, copiez les dossiers voulus dans le dossier `.claude/skills/` du projet. Pour un seul skill, copiez seulement son dossier. Relancez ensuite Claude Code.

## Les 20 skills

| N° | Skill | Domaine | À quoi il sert |
|---|---|---|---|
| 01 | [Réducteur de coûts](skills/reducteur-de-couts/SKILL.md) | Infrastructure | Analyse les serveurs, les API et les services cloud d'un projet pour repérer les coûts inutiles et proposer des alternatives moins chères, chiffrées en euros par mois. |
| 02 | [Automatisation n8n](skills/automatisation-n8n/SKILL.md) | Workflow | Conçoit des workflows n8n qui relient les outils entre eux (CRM, mails, Slack, bases de données), avec gestion d'erreurs, et génère le JSON prêt à importer. |
| 03 | [Scalabilité](skills/scalabilite/SKILL.md) | Backend | Audite l'architecture d'une application web pour trouver ce qui casse quand le trafic augmente, puis propose et applique les optimisations dans l'ordre (base de données, cache, mise à l'échelle). |
| 04 | [Sécurité](skills/securite/SKILL.md) | Critique | Audite le code et l'infrastructure (OWASP Top 10, dépendances vulnérables, en-têtes HTTP, secrets exposés, droits d'accès) et rend un rapport classé par criticité avec les correctifs. |
| 05 | [Design front-end](skills/design-front-end/SKILL.md) | UI et UX | Transforme une idée ou une maquette en interface web propre, moderne et responsive, pensée mobile d'abord, avec contraste WCAG AA et animations discrètes. |
| 06 | [Prompt engineering](skills/prompt-engineering/SKILL.md) | IA | Analyse et réécrit les prompts d'une application IA (exemples, raisonnement par étapes, rôle, format de sortie imposé, contre-exemples) pour réduire les erreurs et le coût des appels. |
| 07 | [Recherche avancée](skills/recherche-avancee/SKILL.md) | Data | Mène une recherche sur le web et dans des documents, croise les sources, distingue les faits des opinions, date chaque information et rend une synthèse qui commence par les conclusions. |
| 08 | [Support client IA](skills/support-client-ia/SKILL.md) | Business | Crée un agent de support qui répond aux clients à partir d'une base de connaissances, sans jamais inventer, et qui passe la main à un humain quand il ne sait pas. |
| 09 | [Mémoire totale (CLAUDE.md)](skills/memoire-totale/SKILL.md) | Contexte | Crée et tient à jour le fichier CLAUDE.md d'un projet (stack, architecture, règles, déploiement, contexte métier, décisions prises) pour que Claude Code connaisse le projet par cœur à chaque session. |
| 10 | [Tâches planifiées (Trigger.dev)](skills/taches-planifiees/SKILL.md) | Cron | Crée des tâches automatiques qui tournent en arrière-plan à intervalles réguliers (rapports, synchronisations, relances, nettoyage), avec délai maximal, journal, idempotence et alerte en cas d'échec. |
| 11 | [Copywriting](skills/copywriting/SKILL.md) | Contenu | Rédige des textes qui font agir (pages de vente, mails, posts, fiches produit) avec les cadres AIDA, PAS, BAB et 4U, des phrases courtes et un seul appel à l'action par page. |
| 12 | [Expert de la stack technique](skills/expert-stack-technique/SKILL.md) | Configuration | Fait de Claude un expert de la stack précise d'un projet : il lit les dépendances, comprend le rôle de chacune, vérifie les versions et documente les choix techniques. |
| 13 | [SEO automatisé](skills/seo-automatise/SKILL.md) | Croissance | Audite et améliore le référencement d'un site sur Google et dans les moteurs de réponse IA : technique, mots-clés, titres et descriptions, données structurées, sitemap et robots.txt. |
| 14 | [Composio](skills/composio/SKILL.md) | Intégrations | Relie Claude Code à des centaines d'applications (Gmail, Slack, Notion, Google Drive, Shopify, Stripe…) par Composio, avec une connexion OAuth et des droits limités au strict nécessaire. |
| 15 | [Auto-correction (self-healing)](skills/auto-correction/SKILL.md) | Le préféré | Fait relire à Claude son propre code après chaque génération : il détecte l'erreur, cherche la cause, corrige, vérifie qu'il n'a rien cassé, et demande de l'aide après trois échecs. |
| 16 | [Scripts vidéo](skills/scripts-video/SKILL.md) | Contenu | Écrit des scripts vidéo prêts à tourner (reels, stories, YouTube) : accroche en moins de trois secondes, une seule idée, relances régulières de l'attention et appel à l'action mesurable. |
| 17 | [Analyse des concurrents](skills/analyse-concurrents/SKILL.md) | Croissance | Analyse les concurrents d'une entreprise (site, offres, prix, contenu, outils, avis clients), construit une matrice comparative et propose des actions concrètes pour se différencier. |
| 18 | [Landing page](skills/landing-page/SKILL.md) | Conversion | Construit une landing page complète qui convertit (structure, texte, design responsive, suivi), du titre à l'appel à l'action final, prête à mettre en ligne. |
| 19 | [Carrousel Instagram](skills/carrousel-instagram/SKILL.md) | Instagram | Crée des carrousels Instagram de 5 à 10 slides (sujet, texte slide par slide, design, rendu HTML) où chaque slide donne envie de passer à la suivante. |
| 20 | [Analyse du tunnel de vente](skills/analyse-tunnel-de-vente/SKILL.md) | Business | Audite un tunnel de vente de bout en bout avec le cadre AARRR (acquisition, activation, rétention, revenu, recommandation), trouve où les prospects se perdent et classe les corrections par gain en euros. |

## Qui suis-je

Je suis Jean-Baptiste Roy, français, ancien commercial de terrain, sans diplôme d'informatique. J'ai appris Claude Code seul, jusqu'à faire tourner toute mon entreprise dessus : CRM, pages, tableaux de bord, assistant sur Telegram, publication automatique de vidéos.

- Mon site : [buildyoursaas.tech](https://buildyoursaas.tech)
- Le blog, plus de 130 articles sur Claude Code pour les entreprises : [buildyoursaas.tech/blog](https://buildyoursaas.tech/blog/)
- Les formations Claude Code en France, comparées : [le comparatif 2026](https://buildyoursaas.tech/formations-claude-code-comparatif.html)
- Mes vidéos, où je construis à l'écran : [YouTube @JB_ROY](https://www.youtube.com/@JB_ROY)
- Les mêmes skills, à copier en un clic : [buildyoursaas.tech/skills-pack.html](https://buildyoursaas.tech/skills-pack.html)

## Licence

MIT : vous pouvez les utiliser, les modifier et les partager librement.
