# TP Figma

## Inspection des travaux

Ajout des fichiers vides `index.html` et `style.css`

```sh
pnpm install --save-dev reload
```

Puis ajout aux scripts

```json
{
  "devDependencies": {
    "reload": "^3.3.0"
  },
  "scripts": {
    "reload": "reload ."
  }
}
```

C'est parti.

```sh
pnpm reload
```
