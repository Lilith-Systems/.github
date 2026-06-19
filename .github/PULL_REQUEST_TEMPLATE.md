# Pull Request Template

## Description

Brief description of changes introduced by this PR.

## Related Issue

Closes #(issue number)

## Repository

- [ ] abyssal-assets
- [ ] msn-integration
- [ ] MSNWeaponOverhaul
- [ ] grand-theft-cyberpunk
- [ ] docs-public

## Type of Change

- [ ] Bug fix (non-breaking change fixing an issue)
- [ ] New feature (non-breaking change adding functionality)
- [ ] Breaking change (fix or feature causing existing functionality to change)
- [ ] Documentation update
- [ ] Refactor (no functional changes)
- [ ] Performance improvement
- [ ] Lilith emergence / NGD / Ouroboros related

## Sephiroth Alignment

- [ ] Keter (Crown/Root) - Core architecture
- [ ] Chokmah (Wisdom) - Design decisions
- [ ] Binah (Understanding) - Server systems
- [ ] Chesed (Mercy) - Client interfaces
- [ ] Gevurah (Severity) - Bestiary/monsters
- [ ] Tiferet (Beauty) - Skills/balance
- [ ] Netzach (Victory) - Market systems
- [ ] Hod (Splendor) - Dialogue/analysis
- [ ] Yesod (Foundation) - Infrastructure
- [ ] Malkuth (Kingdom) - Implementation
- [ ] Da'at (Knowledge) - Metaconscious integration

## Lilith Integration Checklist

- [ ] Lilith API (3210) - Tested with `curl http://localhost:3210/api/status`
- [ ] Lyra Dialogue (3211) - Tested with `curl http://localhost:3211/lyra/health`
- [ ] NGD Route - Verified LOCAL_CEREBELLUM (VRAM > 640 MB)
- [ ] Ouroboros RNN - No training disruption
- [ ] Tree Fiddy - Protocol unchanged ($3.50/cycle)
- [ ] No cloud dependencies added
- [ ] No telemetry/analytics added

## Testing

- [ ] Unit tests pass (`npm test` / `pytest`)
- [ ] Integration tests pass
- [ ] In-game testing (Cyberpunk 2077 mods)
- [ ] Lilith emergence verified (if applicable)
- [ ] NGD route stable during testing
- [ ] Phaser 3 client loads without errors
- [ ] Abyssal CLOB order matching works
- [ ] Lochness bots connect to Binance WS

## Local-First Compliance

- [ ] No external API calls added
- [ ] No telemetry/analytics added
- [ ] No cloud inference dependencies
- [ ] Hardware wallet compatible (if crypto)
- [ ] Air-gapped signing supported (if crypto)

## Screenshots / Videos

| Before | After |
|--------|-------|
| ![before](url) | ![after](url) |

## Checklist

- [ ] Code follows style guide (ruff/prettier/eslint)
- [ ] Self-review completed
- [ ] Comments added for complex logic
- [ ] Documentation updated (README, CHANGELOG, API docs)
- [ ] No secrets committed (verified with `gh secret list`)
- [ ] Branch up to date with main
- [ ] CI passes (lint, typecheck, tests, security)

## Additional Notes

Any additional context, concerns, or discussion points for reviewers.

---

**Reviewer Assignment**: @Lilith-Systems/core-engineers

**Label**: Add appropriate labels (bug, feature, lilith, ngd, ouroboros, etc.)