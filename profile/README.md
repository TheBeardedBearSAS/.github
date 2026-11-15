# The Bearded Bear

Open-source software built and maintained by [The Bearded Bear](https://the-bearded-bear.com).

## URSSAF PHP SDKs

One package per URSSAF API, with the same architecture, quality gate and conventions: framework-agnostic PSR client
and domain model, optional Symfony bundle and Doctrine integration.

| API | Package | Status |
|---|---|---|
| Tiers de prestations (immediate tax-credit advance) | [`thebeardedbear/urssaf-tiers-prestations`](https://github.com/TheBeardedBearSAS/urssaf-tiers-prestations) | Released (Packagist) |
| Attestations Vérification Code Sécurité (certificate verification) | [`thebeardedbear/urssaf-attestations-verification-code-securite`](https://github.com/TheBeardedBearSAS/urssaf-attestations-verification-code-securite) | Released (Packagist) |
| DPAE (pre-employment declaration) | `thebeardedbear/urssaf-dpae` | Coming soon |
| Mobilité internationale (posting of workers abroad) | `thebeardedbear/urssaf-mobilite-internationale` | Coming soon |
| Plateforme numérique (withholding of contributions by digital platforms) | `thebeardedbear/urssaf-plateforme-numerique` | Coming soon |
| Tierce Déclaration auto-entrepreneur | `thebeardedbear/urssaf-tierce-declaration-auto-entrepreneur` | Coming soon |
| Tierce Déclaration CESU | `thebeardedbear/urssaf-tierce-declaration-cesu` | Coming soon |
| Tierce Déclaration PAJE | `thebeardedbear/urssaf-tierce-declaration-paje` | Coming soon |

Every package is held to the same bar, and the proof is public on each repository: 100 % coverage (Codecov,
SonarQube Cloud), 100 % mutation score (Infection, Stryker Dashboard), PHPStan at level max, SonarQube Cloud quality
gate, OpenSSF Scorecard, benchmarks on every pull request.

These packages are unofficial: they are not developed, endorsed or supported by URSSAF.

## Other open-source projects

- [claude-craft](https://github.com/TheBeardedBearSAS/claude-craft) ([documentation](https://thebeardedbearsas.github.io/claude-craft/)):
  a framework for AI-assisted development with Claude Code, with standardized rules, agents and commands for multiple
  technology stacks.

## Professional support

The Bearded Bear helps software vendors and platforms with their URSSAF integrations: habilitation and homologation,
integration of the packages, support with a guaranteed response time, custom developments.

Contact: [the-bearded-bear.com](https://the-bearded-bear.com).
