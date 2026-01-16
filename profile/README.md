# Naming convention — `client / projet / phase / composant` (uniquement `-`)

Objectif : avoir des noms **cohérents**, **lisibles** et **compatibles** avec **Git** et **Cloudflare**.

https://aistudio.google.com/app/prompts?state=%7B%22ids%22:%5B%22104GhGVRuYI6fUpp9bu4L2BheSLyiHpG5%22%5D,%22action%22:%22open%22,%22userId%22:%22106376433399550293492%22,%22resourceKeys%22:%7B%7D%7D&usp=sharing

---

## Structure logique


Comme on n’utilise **que des `-`**, on encode cette structure dans un seul slug :


✅ Un seul séparateur partout : `-`

---

## Règles (strictes)

### Slugs
- ✅ **minuscules uniquement**
- ✅ **mots séparés par `-`**
- ❌ pas d’espaces
- ❌ pas d’accents
- ❌ pas de majuscules
- ⚠️ pas de `_` (underscore) : Cloudflare peut le convertir en `-` → risque de collisions et incohérences

### Exemple de transformation
- `IA soudure` → `ia-soudure`  
- `Retour client par IA vocale` → `retour-client-par-ia-vocale`

> Si tu ne veux pas de `ia-soudure`, alors choisis un projet en **1 mot** (ex: `soudure`) ou une forme compacte (ex: `iasoudure`).  
> L’important : **pas d’espace**.

---


Exemples :
- `manitou-soudure-poc-docs`
- `acme-support-portal-prod-web`
- `internal-templates-mvp-docs`
