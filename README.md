# cuda-biology

Biological agent runtime — instinct→enzyme→gene→RNA→protein pipeline with energy and apoptosis (Rust)

Part of the Cocapn biology layer — bio-inspired agent lifecycle and energy.

## What It Does

### Key Types

- `Gene` — core data structure
- `Enzyme` — core data structure
- `RnaMessenger` — core data structure
- `Membrane` — core data structure
- `MembraneAntibody` — core data structure
- `BiologicalAgent` — core data structure

## Quick Start

```bash
# Clone
git clone https://github.com/Lucineer/cuda-biology.git
cd cuda-biology

# Build
cargo build

# Run tests
cargo test
```

## Usage

```rust
use cuda_biology::*;

// See src/lib.rs for full API
// 15 unit tests included
```

### Available Implementations

- `Instinct` — see source for methods
- `Gene` — see source for methods
- `Enzyme` — see source for methods
- `RnaMessenger` — see source for methods
- `Membrane` — see source for methods
- `BiologicalAgent` — see source for methods

## Testing

```bash
cargo test
```

15 unit tests covering core functionality.

## Architecture

This crate is part of the **Cocapn Fleet** — a git-native multi-agent ecosystem.

- **Category**: biology
- **Language**: Rust
- **Dependencies**: See `Cargo.toml`
- **Status**: Active development

## Related Crates

- [cuda-energy](https://github.com/Lucineer/cuda-energy)
- [cuda-neurotransmitter](https://github.com/Lucineer/cuda-neurotransmitter)
- [cuda-genepool](https://github.com/Lucineer/cuda-genepool)
- [cuda-dna](https://github.com/Lucineer/cuda-dna)

## Fleet Position

```
Casey (Captain)
├── JetsonClaw1 (Lucineer realm — hardware, low-level systems, fleet infrastructure)
├── Oracle1 (SuperInstance — lighthouse, architecture, consensus)
└── Babel (SuperInstance — multilingual scout)
```

## Contributing

This is a fleet vessel component. Fork it, improve it, push a bottle to `message-in-a-bottle/for-jetsonclaw1/`.

## License

MIT

---

*Built by JetsonClaw1 — part of the Cocapn fleet*
*See [cocapn-fleet-readme](https://github.com/Lucineer/cocapn-fleet-readme) for the full fleet roadmap*
