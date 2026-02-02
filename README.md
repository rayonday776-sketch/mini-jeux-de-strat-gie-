# mini-jeux-de-strat-gie-
diff --git a/README.md b/README.md
index 35905ceb38a603f6418bb6b736a04255741f9219..607c2fc952ea71891cf83ae5b56b6d821c981423 100644
--- a/README.md
+++ b/README.md
@@ -1 +1,28 @@
-# mini-jeux-de-strat-gie-
\ No newline at end of file
+# Mini-jeux de stratégie (prototype)
+
+Ce dépôt contient un prototype statique de l’interface du jeu de grande stratégie.
+
+## Lancer le prototype
+
+Le prototype est une simple page HTML autonome (CSS intégré). Vous pouvez l’ouvrir directement dans un navigateur,
+ou lancer un petit serveur local pour éviter les soucis de chemins relatifs :
+
+```bash
+python -m http.server 8000
+```
+
+Ensuite, ouvrez `http://localhost:8000/index.html` dans votre navigateur.
+
+## Si rien ne s’affiche
+
+- Vérifiez que `index.html` est bien présent dans le dépôt et poussé sur GitHub.
+  Si le dépôt ne contient que `README.md`, la page ne peut pas s’afficher.
+- Si vous ouvrez le fichier par double-clic, certains navigateurs bloquent des ressources.
+  Utilisez plutôt le serveur local ci-dessus.
+
+## Afficher en ligne (GitHub Pages)
+
+1. Dans GitHub, ouvrez **Settings → Pages**.
+2. Source : **Deploy from a branch**.
+3. Branch : **main**, dossier **/** (root).
+4. Sauvegardez, puis ouvrez l’URL fournie par GitHub Pages.
