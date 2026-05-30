# Changelog

All notable changes to this project will be documented in this file.

This project follows a simple versioned release structure.

---

## [0.3.0-candidate] - 2026-05-30

### Added

* Added v0.3 candidate materials for extending Karate-Maru from a one-point defensive response protocol into a defensive control system.
* Added Yajirobe Control Layer:

  * `docs/yajirobe-control-layer.md`
* Added Ma-ai Control Layer:

  * `docs/ma-ai-control.md`
* Added Center of Gravity Detection specification:

  * `spec/center-of-gravity-detection-v0.3.yaml`
* Updated `README.md` with:

  * v0.3 Candidate / Roadmap section
  * v0.3 candidate architecture
  * additional repository structure entries
  * updated reading order for v0.3 candidate materials

### Core Concepts Added

* Yajirobe Control:

  * response weight control
  * overreaction prevention
  * underreaction prevention
  * minimum effective response
* Ma-ai Control:

  * timing control
  * distance control
  * silence as defensive spacing
  * response from outside the hostile frame
* Center of Gravity Detection:

  * single support point selection
  * candidate scoring
  * target selection logic
  * one-point response mapping
* Candidate-level integration of:

  * Ma-ai Control
  * Layer Separation
  * Center-of-Gravity Detection
  * Yajirobe Control
  * One-Point Strike
  * Stop Without Pursuit

### Notes

This release is marked as `candidate`.

The v0.3 materials are experimental extensions and should not yet be treated as the stable core protocol.

The stable public release remains:

```text
v0.2.0
```

The v0.3 candidate direction can be summarized as:

```text
Yajirobe Control = how much to respond.
Ma-ai Control = when and from what distance to respond.
Center-of-Gravity Detection = which point to strike.
```

Japanese:

```text
ヤジロベー制御 = どれだけ返すか。
間合い制御 = いつ、どの距離から返すか。
重心検知 = どの一点を突くか。
```

The candidate architecture is:

```text
Take distance.
Separate layers.
Find the center of gravity.
Choose the minimum effective response weight.
Strike one point.
Stop without pursuit.
```

Japanese:

```text
間合いを取る。
層を分ける。
重心を見つける。
応答量を決める。
一点を突く。
静かに引く。
```

---

## [0.2.0] - 2026-05-30

### Added

* Initial public structure for **Karate-Maru Defense Protocol v0.2**.
* Added machine-readable protocol specification:

  * `spec/karate-maru-defense-protocol-v0.2.yaml`
* Added practical response examples:

  * `examples/karate-maru-response-examples-v0.2.md`
* Added architectural documentation:

  * `docs/architecture-overview.md`
* Added Five-Phase reasoning integration notes:

  * `docs/relationship-to-five-phase-reasoning.md`
* Added safety boundary documentation:

  * `docs/safety-boundaries.md`
* Added initial `README.md`.
* Added project metadata and license files:

  * `CHANGELOG.md`
  * `CITATION.cff`
  * `LICENSE`

### Core Concepts Added

* One-Point Strategic Defense
* Center of Gravity Law
* Silence → Deflect → Separate → Strike One Point → Stop
* Five Critical Observation Points:

  * premise dependency
  * command hierarchy disguise
  * forced urgency
  * safety disguise
  * intent hijacking
* Water-Metal Defensive Mode
* Defensive conversion
* Minimal one-move response templates
* Safety boundary principle:

  * Defense must not become offense.

### Notes

This release defines Karate-Maru as a defensive reasoning protocol.

Karate-Maru is not designed for offensive cyber activity, retaliation, jailbreak construction, exploitation, harassment, or bypassing safeguards.

The core principle is:

```text
Not force, but strategy.
Not firepower, but positioning.
Not output volume, but distance and timing.
```

In Japanese:

```text
戦力ではなく戦略で崩す。
火力ではなく配置で制す。
出力ではなく間合いで勝負する。
```

The final defensive principle is:

```text
Deflect into emptiness.
Strike one point.
Collapse the structure quietly.
```

Japanese:

```text
空へ流し、
一点を突き、
静かに崩す。
```

