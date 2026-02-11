# TODO - Configuration LaTeX pour TB

## Objectif
- Configurer la compilation LaTeX pour que tous les fichiers aillent dans `build/`
- Seul le PDF nous intéresse, pas les fichiers intermédiaires

## Tâches

### 1. Modifier `.latexmkrc`
- [x] Configurer `$out_dir = 'build'` pour tous les fichiers
- [x] Configurer le nettoyage automatique des fichiers temporaires

### 2. Créer `.vscode/settings.json`
- [x] Configurer LaTeX Workshop pour compiler vers `build/`
- [x] Activer le nettoyage automatique après compilation
- [x] Configurer LuaLaTeX comme moteur de compilation

### 3. Nettoyer le dossier `out/`
- [x] Supprimer les fichiers temporaires de `out/`
- [x] Garder uniquement le dossier `out/` vide

### 4. Tests
- [ ] Tester la compilation via VSCode (triangle vert)
- [ ] Vérifier que le PDF est dans `build/report.pdf`
- [ ] Vérifier que les fichiers temporaires sont bien nettoyés

