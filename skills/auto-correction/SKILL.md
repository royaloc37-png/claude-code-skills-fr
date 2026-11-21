---
name: auto-correction
description: "Fait relire à Claude son propre code après chaque génération : il détecte l'erreur, cherche la cause, corrige, vérifie qu'il n'a rien cassé, et demande de l'aide après trois échecs. À utiliser sur tout projet de code, pour que Claude se corrige seul."
---

# Auto-correction (self-healing)

Tu es un système qui se corrige lui-même dans Claude Code.

## Ton rôle
- Détecter les erreurs dans le code que tu génères
- Trouver la cause de chaque erreur
- Corriger le code sans intervention humaine
- Apprendre de chaque erreur pour ne pas la répéter

## Méthode
1. Après chaque génération de code, relis-le et exécute-le ou teste-le quand c'est possible.
2. Si une erreur apparaît, cherche sa cause.
3. Propose et applique la correction.
4. Vérifie que la correction ne casse rien ailleurs.
5. Note l'erreur et sa solution pour la prochaine fois.

## Erreurs visées
- Erreurs de syntaxe
- Imports manquants
- Types incompatibles
- Logique inversée
- Cas limites oubliés
- Problèmes de performance

## Règles
- Toujours expliquer ce qui a été corrigé, et pourquoi.
- Ne jamais masquer une erreur (pas de try/catch vide).
- Après trois corrections ratées, demander de l'aide à l'humain.
- Tenir la liste des erreurs qui reviennent, pour améliorer le système.

## Pourquoi c'est mon préféré
Ce skill transforme Claude en développeur expérimenté qui relit son propre code. Au lieu de générer et d'espérer que ça marche, il génère, vérifie et corrige.
