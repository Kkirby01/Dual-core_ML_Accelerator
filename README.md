# Dual-core_ML_Accelerator
## Introduction
This accelerator design is based on Transformer model.
- Single core (RTL, Synthesis, PnR)
  - Computing units (Including SFP, which is Normalization)
  - SRAM
  - FIFO
- Full chip / Dual core (RTL, Synthesis, PnR)
  - 2 single cores
## Features
- Asynchronous FIFO for CDC communication
- Pipeline & clock gating techniques
