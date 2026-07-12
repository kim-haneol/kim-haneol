# Haneol Kim

**Principal Researcher | Mathematical AI & Efficient Computing**

`algebraic structure → numerical algorithms → AI systems`

I am a Principal Researcher at the **AI R&D Center, iTrix**
and a Ph.D. Candidate in Mathematics at Seoul National University.

I study how **algebraic structure and numerical linear algebra** can be used to
reformulate expensive learning and inference procedures into direct, stable,
and hardware-efficient computation.

At work, I focus on **small language model fine-tuning, post-training,
evaluation, and hardware-aware inference**.

## ∑ Research Program

My current research follows a common computational theme:

> represent structure algebraically, reduce it to well-conditioned operators,
> and replace repeated iteration with direct numerical computation.

- **Algebraic and structured computation**
  — representations of noncommutative and hypercomplex operations as
  structured linear operators

- **Realification and SPD reduction**
  — transforming complex or structured operator problems into stable
  real-valued linear algebra kernels

- **Solve-based learning**
  — inverse and resolvent formulations for implicit models, differentiation,
  optimization, and learning

- **Structure-preserving numerics**
  — conservative discrete computation for dynamical systems and PDEs,
  including integer-transfer formulations

## λ Frameworks in Development

- **AXIOM–ALH–CRE**  
  An algebra-to-computation pipeline connecting structured algebraic
  representations, realification, and SPD-based numerical kernels.

- **FQNM**  
  A structure-preserving numerical framework based on conservative integer
  transfer, aimed at stable and efficient simulation of dynamical systems.

Rather than treating these as separate projects, I view them as parts of a
single program for turning mathematical structure into efficient computation.

## ⚙ Language Model Systems

I also work on practical systems for efficient language-model development and
deployment:

- Fine-tuning, post-training, and evaluation of small language models
- Long-context local inference with `vLLM` and `llama.cpp`
- Quantization and reasoning-model failure modes
- Hardware-aware inference across GPUs and on-device accelerators
- Local coding agents and reproducible evaluation pipelines

## ↩ Earlier Work

My previous research focused on:

- Offline and goal-conditioned reinforcement learning
- Hierarchical policies for long-horizon decision making
- Flow matching and generative models for policy construction
- Kernel and value-based methods for offline control

These remain important application domains for my current work on structured
and solve-based learning.

## ⌨ Technical Practice

- **Machine learning research:** Python, PyTorch, JAX
- **Numerical computing:** NumPy/SciPy, BLAS/LAPACK, direct linear solvers
- **LLM inference experimentation:** long-context serving, quantization,
  GPU memory optimization, `vLLM`, and `llama.cpp`
- **On-device ML:** Core ML and Apple Neural Engine experiments

## ⌁ Contact

[Email](mailto:haneol.kijm@gmail.com) ·
[X](https://x.com/haneol_kijm)
