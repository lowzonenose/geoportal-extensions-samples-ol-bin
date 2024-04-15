# Publication Netlify

> deploiement auto sur la branche `main` uniquement

* Configuration du projet Netlify :
  <https://app.netlify.com/sites/geoportal-extensions-samples/overview>

* URL de deploiement :
  <https://geoportal-extensions-samples.netlify.app>

* Process :

1. Sur le projet *geoportal-extensions-openlayers-samples* :
    ```sh
    # build en mode dev
    npm run build -- --mode=development
    ```
2. Puis, on copie le contenu du réperoire `dist/` sur le dépôt 
3. Et, on *push* sur la branche `main`

**TODO**
> Ajouter une github action sur le depôt des exemples !