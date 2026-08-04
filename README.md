# Portail pédagogique — Association de la Fraternité d'Elne

Page d'accueil donnant accès aux manuels scolaires d'éducation islamique (5 cycles, 8 années) et aux applications pédagogiques associées.

## Structure

```
index.html                          page d'accueil
assets/                              css du portail
manuels/
  cycle1/annee1/, cycle1/annee2/     manuels élève (HTML + images/ séparées)
  cycle2/annee1/, cycle2/annee2/     manuels élève (HTML + images/ séparées)
  cycle3/                            manuel élève (année unique) + référentiel
  cycle4/, cycle5/                   référentiels pédagogiques (manuels à venir)
  ressources_cycle1/                 guide enseignant + livret ressources
```

Les manuels élève étaient initialement livrés en HTML unique avec images encodées en base64 (40-55 Mo par fichier). Elles ont été extraites en fichiers image séparés (`extract-images.js`) pour rester compatibles avec GitHub / GitHub Pages.

## Applications liées

- [Hourouffi — niveau 1](https://enseignementelne-spec.github.io/Hourouffi-niveau-1/) — apprentissage de l'arabe en jouant.

## Licence

Contenus sous licence [CC BY-NC-SA 4.0](LICENSE) — partage et adaptation libres, usage non commercial, attribution requise, partage dans les mêmes conditions.
