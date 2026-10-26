# Créatif — animation, 3D, art génératif

Compétences pour les projets visuels et ludiques : animations, scènes 3D, art génératif, effets.
Provenance exacte et commits dans `SOURCES.md`.

| Dossier | Contenu |
|---|---|
| `.claude/skills/` | 15 compétences |
| `references/bibliotheques.md` | Bibliothèques créatives (3D, son, jeux, cartes, schémas) |
| `inspirations/animations/` | 703 prompts d'animations réalisées avec Claude (HTML, Canvas, SVG, Three.js) |
| `licenses/`, `scripts/` | Licences ; `sources.txt` + `sync.sh` |

## Compétences
| Famille | Source | Compétences |
|---|---|---|
| Animation (officiel GreenSock) | greensock/gsap-skills | `gsap-core`, `gsap-timeline`, `gsap-scrolltrigger`, `gsap-plugins`, `gsap-utils`, `gsap-performance`, `gsap-frameworks` |
| Art génératif (officiel Anthropic) | anthropics/skills | `algorithmic-art` (p5.js), `canvas-design` (affiches, visuels PNG/PDF) |
| 3D, 2D, effets | freshtechbro/claudedesignskills | `threejs-webgl`, `pixijs-2d`, `animejs`, `lottie-animations`, `lightweight-3d-effects`, `scroll-reveal-libraries` |

## Sécurité
Chaque source a été vérifiée avant ajout (octobre 2026) : licence libre (MIT, Apache 2.0, domaine public), auteur identifié, projet actif.
Le code exécutable a été relu : pas de lecture de secrets, pas de consignes cachées, connexions réseau limitées à des CDN connus et à des banques d'images publiques.
Règle pour toute nouvelle source : même vérification avant de l'ajouter à `scripts/sources.txt`.

## Mise à jour
`bash scripts/sync.sh` puis commit.
