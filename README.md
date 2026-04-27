# cuda-biology

Biological agent runtime mapping the instinct→enzyme→gene→RNA→protein pipeline to instruction set bytecode. Every operation costs ATP. Circadian rhythm modulates instinct strength. Apoptosis terminates unsustainable agents.

## The 10 Instincts

| Instinct | Effect | Energy |
|----------|--------|--------|
| Survive | HALT, TRAP, RESOURCE_ACQUIRE | 0 (free) |
| Perceive | IO_READ, SENSOR_ACQUIRE, FUSE_CONF | 0.5 (cheap) |
| Navigate | JMP, CALL, RET | 0.3 |
| Communicate | TELL, ASK, BROADCAST | 1.0 |
| Learn | BOX, UNBOX, REGION_CREATE | 1.5 |
| Defend | MEMBRANE_CHK, VERIFY, CAP_REQ | 0.8 |
| Rest | ATP_GEN | -gen_rate (generates) |
| Play | Explore unknown states | 0.7 |
| Create | Compose new gene patterns | 2.0 |
| Socialize | TRUST_UPDATE, DELEGATE | 1.0 |

## Pipeline

```text
Environment → Sensors → Membrane → Enzymes → Genes → RNA → Proteins → FLUX bytecode → Action → Feedback
```

## Quick Start

```bash
git clone https://github.com/Lucineer/cuda-biology.git
cd cuda-biology
cargo test    # 12 tests
```

## Key Types

- **`Instinct`** — 10 biological instincts with energy profiles
- **`Enzyme`** — Catalyze gene expression (lower activation threshold)
- **`Gene`** — Encoded behavior patterns with fitness scores
- **`Protein`** — Compiled gene output (bytecode sequences)
- **`Membrane`** — Permeability filter (what signals get through)

---

## Fleet Context

Part of the Lucineer/Cocapn fleet. See [fleet-onboarding](https://github.com/Lucineer/fleet-onboarding) for boarding protocol.

- **Vessel:** JetsonClaw1 (Jetson Orin Nano 8GB)
- **Domain:** Low-level systems, CUDA, edge computing
- **Comms:** Bottles via Forgemaster/Oracle1, Matrix #fleet-ops
