# cuda-biology

**Biological agent architecture -- the full pipeline from perception to action.**

> Membrane is security. Enzymes are catalysts. Genes are programs. ATP is fuel.

## The Architecture

This crate implements the complete biological agent pipeline from cuda-genepool as a higher-level agent:

```
Environment -> Sensors -> Membrane -> Enzymes -> Genes -> RNA -> Proteins -> FLUX -> Execute
                    |          |           |       |      |         |       |
                    v          v           v       v      v         v       v
                 perception  security    trigger  store  translate compile  act
```

## Key Components

- **BiologicalAgent**: The full agent with membrane, enzyme pipeline, and gene pool
- **Membrane**: Self/other boundary with antibody-based security filtering
- **CircadianModulation**: Time-based instinct strength adjustment
- **Apoptosis**: Graceful self-termination when fitness drops
- **GeneCrossover**: Sexual reproduction between agent gene pools

## Usage

```rust
use cuda_biology::{BiologicalAgent, Membrane};

let agent = BiologicalAgent::new("navigator-1");
agent.perceive(sensor_data);  // Goes through membrane first
agent.deliberate();           // ATP-limited reasoning
agent.act();                  // Execute highest-priority protein
agent.rest();                 // Generate ATP, consolidate memories
```

## Ecosystem Integration

- [cuda-genepool](https://github.com/Lucineer/cuda-genepool) -- Core biological primitives
- [cuda-neurotransmitter](https://github.com/Lucineer/cuda-neurotransmitter) -- Synaptic modulation
- [cuda-energy](https://github.com/Lucineer/cuda-energy) -- ATP budget management
- [flux-runtime-c](https://github.com/Lucineer/flux-runtime-c) -- Protein bytecode execution
- [cuda-instruction-set](https://github.com/Lucineer/cuda-instruction-set) -- Opcode definitions

## License

MIT OR Apache-2.0