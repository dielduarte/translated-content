---
title: "console : méthode statique error()"
slug: Web/API/console/error_static
l10n:
  sourceCommit: 022399901bdc60df947ee15e11a49be029e290d0
---

{{APIRef("Console API")}}

La méthode **`console.error()`** permet d'afficher un message d'erreur dans la console.

{{AvailableInWorkers}}

## Syntaxe

```js-nolint
error(obj1)
error(obj1, /* …, */ objN)
error(msg)
error(msg, subst1, /* …, */ substN)
```

### Paramètres

- `obj1` … `objN`
  - : Une liste d'objets JavaScript à afficher. Les représentations en chaînes de caractères de ces objets sont concaténés dans l'ordre et affichés dans la console.
- `msg`
  - : Une chaîne de caractères JavaScript qui contient zéro ou plusieurs chaînes de substitution qui seront remplacées par `subst1` … `substN` dans l'ordre.
- `subst1` … `substN`
  - : Des objets JavaScript avec lesquels remplacer les chaînes de substitution dans `msg`. Ce paramètre permet un contrôle supplémentaire sur le format de ce qui est affiché. Voir [la page sur les chaînes de caractères de substitution avec `console`](/fr/docs/Web/API/console#utiliser_les_caractères_de_substitution) pour plus de détails.

Voir [Afficher du texte dans la console](/fr/docs/Web/API/console#afficher_du_texte_dans_la_console) pour plus de détails.

### Valeur de retour

Aucune ([`undefined`](/fr/docs/Web/JavaScript/Reference/Global_Objects/undefined)).

## Spécifications

{{Specifications}}

## Compatibilité des navigateurs

{{Compat}}

## Voir aussi

- [La documentation Edge sur `console.error()`](https://learn.microsoft.com/en-us/microsoft-edge/devtools-guide-chromium/console/api#error)
- [La documentation Chrome sur `console.error()`](https://developer.chrome.com/docs/devtools/console/api/#error)
