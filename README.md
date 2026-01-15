# Naming convention — `client / projet / phase / composant` (uniquement `-`)

Objectif : avoir des noms **cohérents**, **lisibles** et **compatibles** avec **Git** et **Cloudflare**.

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
