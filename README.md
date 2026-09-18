# Linters i ESLint

## Que és? 

Els Linters són eines utilitzades per verificar codi. Serveixen per detectar errors inclosos els de format abans de l'execució, i també apliquen un format uniforme a tot el document. 

### Perquè serveix.

- Detecta Errors.
- Unifica l'estil.
- Millora la llegibilitat
- Estalvia temps.

## ESLint

ESLint és un Linter que serveix per als llenguatges JavaScript i TypeScript.

### Com per-ho servir

Primer necessitarem el ESLint en local després l'extensió de Visual Code.

Podem Instal·lar ESLint amb **npm install --save-dev eslint**.

Per fer la configuració d'inici fem servir la comanda **npx eslint --init**.

Podem fer una verificació manual al fitxer que volem amb la comanda **npx eslint fitxer.js**

Podem afegir regles editant el fitxer de eslint.config.mjs [Llista de regles](https://eslint.org/docs/latest/rules/).
