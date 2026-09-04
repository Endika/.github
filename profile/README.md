## Endika Iglesias

**Backend and tooling engineer · Madrid**

I work on the parts most people never open: type inference, query planners, layout
engines, firmware. Most of what I build is small, finished and running somewhere.

Python · Go · TypeScript · C

---

### Merged upstream

| Project | What it fixed |
|---|---|
| [docker/compose#14084](https://github.com/docker/compose/pull/14084) | `watch` now syncs into a symlinked directory instead of failing |
| [docker/compose#13992](https://github.com/docker/compose/pull/13992) | An unreadable directory no longer kills the whole watch |
| [pact-foundation/pact-python#1669](https://github.com/pact-foundation/pact-python/pull/1669) | Message handler failures were being reported as transport errors |
| [tobymao/sqlglot#7969](https://github.com/tobymao/sqlglot/pull/7969) | DuckDB division by zero returns `inf`, not `NULL` |
| [fonttools/fonttools#4137](https://github.com/fonttools/fonttools/pull/4137) | `varLib.instancer` now instances the `BASE` table |
| [DarkFlippers/unleashed-firmware#1048](https://github.com/DarkFlippers/unleashed-firmware/pull/1048) | Bounded card-controlled TLV lengths in the EMV poller |
| [DarkFlippers/unleashed-firmware#1049](https://github.com/DarkFlippers/unleashed-firmware/pull/1049) | Type 4 Tag writes starting inside the `NLEN` field |

### In review

| Project | Change |
|---|---|
| [python/mypy#21805](https://github.com/python/mypy/pull/21805) | Propagate walrus narrowing from nested expressions |
| [python/mypy#21806](https://github.com/python/mypy/pull/21806) | Report access to abstract static and class methods on the class |
| [vitessio/vitess#20700](https://github.com/vitessio/vitess/pull/20700) | Keep the surrounding predicate when pulling out `EXISTS` |
| [vitessio/vitess#20701](https://github.com/vitessio/vitess/pull/20701) | Do not merge an outer join whose preserved side is a reference table |
| [traefik/yaegi#1729](https://github.com/traefik/yaegi/pull/1729) | Don't panic on a constant non-bool condition |
| [traefik/yaegi#1730](https://github.com/traefik/yaegi/pull/1730) | Report an error when a package is used outside a selector |
| [chearon/dropflow#34](https://github.com/chearon/dropflow/pull/34) | Implement `position: absolute` |
| [Next-Flip/Momentum-Firmware#573](https://github.com/Next-Flip/Momentum-Firmware/pull/573) | Bound card-controlled TLV lengths in the EMV poller |
| [Next-Flip/Momentum-Firmware#574](https://github.com/Next-Flip/Momentum-Firmware/pull/574) | Type 4 Tag writes starting inside the `NLEN` field |

---

### Shipped

**Offline-first PWAs**, no account, no backend to trust —
[Erregai](https://endika.github.io/erregai/) finds the cheapest fuel near you and
follows your route, [Zarata](https://endika.github.io/zarata/) is a sound level meter
you hold in your hand, [Agora](https://endika.github.io/agora/) is a proposal board
with secret votes until quorum.
[More at endika.github.io](https://endika.github.io/).

**On PyPI** — [imgtrail](https://pypi.org/project/imgtrail/) finds where your own
photos resurfaced on the web and verifies the matches by perceptual hash;
[loud-noise-detector](https://pypi.org/project/loud-noise-detector/) listens for the
sounds you care about while you are away.

**Eight apps in the official Flipper Zero catalogue** — NFC inventory, sub-file
deduplication, a hyperfocal distance calculator, a habit tracker and four games,
all written in C.

---

[endika.github.io](https://endika.github.io/) ·
[LinkedIn](https://www.linkedin.com/in/endika-i-0420a731/)
