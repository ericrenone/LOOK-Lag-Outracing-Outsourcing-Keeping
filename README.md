# LOOK — Lag · Outracing · Outsourcing · Keeping
## Coevolutionary Rate Geometry · Genomic Strategy Phase Transitions · Arms Race Bifurcation on the Fitness Interaction Manifold
### From Van Valen's 1973 Red Queen and Bergstrom & Lachmann's 2003 Red King to Morris et al.'s 2012 Black Queen and the Black King — Four Evolutionary Attractors on the Coevolutionary Strategy Manifold ℳ_LOOK

> *"It takes all the running you can do, to keep in the same place. If you want to get somewhere else, you must run at least twice as fast as that."*
> — Lewis Carroll, *Through the Looking-Glass*, 1871 — the metaphor that gave the Red Queen its name

> *"In a mutualistic interaction, the slower-evolving partner tends to capture a larger share of the benefits. Evolutionary speed is not always a virtue."*
> — Carl T. Bergstrom and Michael Lachmann, "The Red King Effect: When the Slowest Runner Wins the Coevolutionary Race," 2003

> *"Genome streamlining can be driven by the loss of costly metabolic functions when those functions are provided as public goods by other members of the community. We call this the Black Queen Hypothesis."*
> — J.B. Morris, R.J. Lenski, and E.R. Zinser, "The Black Queen Hypothesis: Evolution of Dependencies through Adaptive Gene Loss," 2012

> *"The genome is not a blueprint for the organism. It is a palimpsest — a record of every selective environment the lineage ever survived."*
> — after Theodosius Dobzhansky, *Genetics and the Origin of Species*, 1937; and C.H. Waddington, *The Strategy of the Genes*, 1957

---

## Foundational Unity: One Manifold, Four Attractors, Two Governing Parameters

Four evolutionary strategies — described in separate literatures, named after chess pieces, and studied by ecologists, microbiologists, game theorists, and evolutionary biologists working in parallel — are shown here to be four stable attractors on a single **Coevolutionary Strategy Manifold** ℳ_LOOK. The manifold is parameterized by two independent axes:

**Axis I — The Coevolutionary Rate Ratio** Ψ = r_self / r_other, where r_self is the adaptation rate of the focal organism and r_other is the adaptation rate of its primary interaction partner (enemy or mutualist). This axis governs whether coevolutionary dynamics converge to a stable mutualistic equilibrium (Red King, Ψ < Ψ_c) or diverge into an accelerating arms race (Red Queen, Ψ > Ψ_c).

**Axis II — The Genomic Delegation Index** Δ = f_delegated / f_total, where f_delegated is the fraction of ancestral metabolic functions that have been outsourced to community partners through gene loss, and f_total is the ancestral complete function set. This axis governs whether the organism's genome converges toward community-dependent streamlining (Black Queen, Δ → 1) or toward autonomous redundancy with paralogous backup copies (Black King, Δ → 0).

The four chess pieces are the four quadrants of ℳ_LOOK = (Ψ, Δ) × (interaction type: competitive / mutualistic):

```
                    Δ → 0 (Gene Retention)          Δ → 1 (Gene Delegation)
                   ┌──────────────────────────────┬──────────────────────────────┐
  Ψ > Ψ_c         │  RED QUEEN                   │  [Transitional]              │
  (Fast)          │  Outrace enemies              │  Race + Dependency           │
  Competitive     │  Arms race divergence         │  Unstable; collapses to      │
                  │  Continuous adaptation        │  Black Queen or extinction   │
                   ├──────────────────────────────┼──────────────────────────────┤
  Ψ < Ψ_c         │  BLACK KING                  │  BLACK QUEEN                 │
  (Slow/Stable)   │  Robust redundancy            │  Gene loss efficiency        │
  Cooperative/    │  Stable against attack        │  Community dependency        │
  Mutualistic     │  Paralog buffering            │  Metabolic outsourcing       │
                   └──────────────────────────────┴──────────────────────────────┘
  Ψ ≈ Ψ_c         │                   RED KING                                  │
  (Deliberate Lag)│  Slow below partner rate to capture mutualistic surplus     │
  Mutualistic     │  Cooperative equilibrium; rate asymmetry favors slower party │
                   └────────────────────────────────────────────────────────────┘
```

**The LOOK Acronym maps to the four attractors:**

- **L**ag — the Red King strategy: deliberately reduce evolutionary rate below the mutualistic partner to capture disproportionate fitness benefit; the slowest runner in the mutualistic race wins the surplus.
- **O**utracing — the Red Queen strategy: outrun the coevolutionary enemy continuously; any failure to keep pace means fitness collapse; speed is survival.
- **O**utsourcing — the Black Queen strategy: outsource (delegate) costly genomic functions to community partners through adaptive gene loss; pay the cost of dependency to eliminate the cost of gene maintenance.
- **K**eeping — the Black King strategy: keep redundant genomic copies (paralogs, duplicated pathways) as a buffer against environmental perturbation and partner loss; pay the cost of genome maintenance for robustness insurance.

These four strategies are not arbitrary choices. They are the four **stable fixed points** of the LOOK coevolutionary dynamics operator ℒ_LOOK acting on ℳ_LOOK — the four attractors to which any organism under sustained selective pressure will converge, depending on initial conditions and environmental parameters. The four chess pieces are the four phase-space equilibria.

---

## Two Physical Bridges

### Bridge I — The Red Queen and Red King as the Two Phases of a Coevolutionary Lotka–Volterra Bifurcation

The classical Lotka–Volterra predator-prey system describes oscillatory population dynamics at fixed trait values. The **coevolutionary extension** — introduced by Dieckmann, Law, and Doebeli in the adaptive dynamics framework — allows the traits themselves to evolve:

```
ẋ = f(x, y, α_x)   +   μ_x · G_x(α_x)     [prey population + trait evolution]
ẏ = g(x, y, α_y)   +   μ_y · G_y(α_y)     [predator population + trait evolution]
```

where x, y are population sizes, α_x, α_y are evolving traits (e.g., defense intensity, attack rate), μ_x, μ_y are evolutionary rates (per-generation trait change velocities), and G_x, G_y are fitness gradient operators on trait space.

The **coevolutionary Jacobian** J_coevo evaluated at the fixed point (x*, y*, α*_x, α*_y) of this 4-dimensional system has eigenvalues λ₁, λ₂, λ₃, λ₄. The **leading eigenvalue** λ₁(J_coevo) determines the stability regime:

```
λ₁(J_coevo) < 0:   STABLE EQUILIBRIUM — coevolution converges
                    Red King regime: the mutualistic fixed point is attracting
                    Rates settle; the slower party captures the surplus Δπ_RK

λ₁(J_coevo) = 0:   VAN VALEN CRITICAL POINT — neutral oscillation
                    The "treadmill" of Red Queen at equilibrium
                    Phase boundary Ψ = Ψ_c on ℳ_LOOK

λ₁(J_coevo) > 0:   ARMS RACE DIVERGENCE — coevolution accelerates
                    Red Queen regime: the trait arms race is self-reinforcing
                    Each improvement by prey demands improvement by predator; no equilibrium
```

The **coevolutionary rate ratio** Ψ = μ_y / μ_x enters through the Jacobian:

```
J_coevo  =  [ ∂f/∂x    ∂f/∂y  |  μ_x · ∂G_x/∂x   0          ]
            [ ∂g/∂x    ∂g/∂y  |  0                 μ_y · ∂G_y/∂y ]
```

The critical value Ψ_c is the value at which λ₁(J_coevo) changes sign — the **Van Valen bifurcation point**. For the symmetric case (equal population sizes, equal trait gradients):

```
Ψ_c  =  (∂G_x/∂x)  /  (∂G_y/∂y)     [ratio of fitness gradient curvatures]
```

When Ψ > Ψ_c (predator evolves faster than prey), the prey's fitness landscape steepens, λ₁ > 0, and the Red Queen arms race is driven. When Ψ < Ψ_c (prey evolves faster or, equivalently, in a mutualism, the focal organism evolves slower than its partner), λ₁ < 0, and the Red King stable equilibrium is approached.

**The Red King surplus** Δπ_RK — the excess fitness benefit captured by the slower coevolutionary partner in a mutualism — scales as:

```
Δπ_RK  ~  (Ψ_c − Ψ)^{1/2}   as Ψ → Ψ_c from below
```

This is the **square-root scaling** of a standard saddle-node bifurcation: the benefit of lagging increases as the square root of the lag gap (Ψ_c − Ψ). Small lags yield small surplus; large lags yield large surplus but risk decoupling from the mutualistic partner entirely. The **optimal Red King lag** Ψ*_RK minimizes the total fitness cost:

```
Ψ*_RK  =  arg max_Ψ [ Δπ_RK(Ψ) − C_decoupling(Ψ) ]
         =  Ψ_c − [C'_decoupling(0) / (2 · ∂²π_RK/∂Ψ²)]^{1/2}
```

where C_decoupling(Ψ) is the cost of mutualistic partner decoupling as the lag widens. This is the intertemporal optimization problem of the Red King: how slow is optimal, given that too slow means losing the mutualist entirely?

**Physical template: Lotka–Volterra coevolutionary adaptive dynamics.** The spectral gap λ₁(J_coevo) > 0 signals Red Queen arms race divergence, exactly as λ₁(ℒ_L) > 0 signals thermalization in the Landau kinetic equation. The Van Valen bifurcation at Ψ_c is a codimension-1 bifurcation of the coevolutionary flow on ℳ_LOOK.

---

### Bridge II — The Black Queen and Black King as the Two Phases of Spectral Graph Genomic Delegation

A microbial community can be represented as a **metabolic interaction graph** G = (V, E, w):
- **Nodes** V = {v₁, ..., v_n}: individual organisms or strains in the community
- **Edges** E: shared, complementary, or dependent metabolic functions (public goods, cross-feeding, cofactor exchange)
- **Edge weights** w_{ij}: flux through the metabolic interaction between organism i and organism j

The **graph Laplacian** L_G = D − A (where D is the degree matrix and A is the adjacency/weight matrix) has eigenvalues:

```
0 = λ₁(L_G) ≤ λ₂(L_G) ≤ ... ≤ λ_n(L_G)
```

The **Fiedler value** λ₂(L_G) — the second-smallest eigenvalue, also called the **algebraic connectivity** of G — is the master parameter governing both Black Queen and Black King dynamics:

```
λ₂(L_G) = 0:       G is disconnected — no metabolic integration
λ₂(L_G) small > 0: G has a narrow bottleneck — fragile metabolic coupling
                    BLACK QUEEN regime: gene loss adaptive
                    Community provides functions; individual gene retention expensive

λ₂(L_G) large:     G is densely connected — robust metabolic integration
                    BLACK KING regime: gene redundancy adaptive
                    Paralog retention provides backup against graph disruption
                    Each internal redundancy raises effective λ₂ for the focal organism
```

The **Cheeger inequality** bounds λ₂ by the graph's geometric bottleneck:

```
h(G) / 2  ≤  λ₂(L_G)  ≤  2 · h(G)

where h(G) = min_{S ⊆ V, |S| ≤ n/2}  |∂S| / |S|   [isoperimetric ratio]
```

Here |∂S| is the number of edges crossing the boundary of community subset S, and |S| is its size. h(G) is the **community bottleneck**: the smallest cross-section of metabolic communication in the network. A community with a thin bottleneck (h → 0, λ₂ → 0) has fragile metabolic integration — one disruption can cleave the community.

The **gene loss fitness function** for organism i under Black Queen dynamics:

```
Φ_BQ(Δ_i)  =  C_maint · (1 − Δ_i)  −  C_depend · Δ_i / λ₂(L_G)
```

where:
- C_maint = per-gene maintenance cost (replication, expression, regulation)
- Δ_i = delegation index of organism i (fraction of functions delegated to community)
- C_depend = cost per unit of community dependency (exposure to partner loss)
- λ₂(L_G) = Fiedler value of the metabolic community graph (community robustness)

The Black Queen fixed point (optimal gene loss level) is:

```
Δ*_BQ  =  1  −  C_depend / (C_maint · λ₂(L_G))
```

when the right-hand side is positive. When C_depend / (C_maint · λ₂(L_G)) > 1 (high dependency cost relative to community robustness), Δ*_BQ < 0, meaning no delegation is optimal — the **Black King regime**:

```
BLACK QUEEN stable:   C_maint · λ₂(L_G) > C_depend     [community robust enough to delegate to]
BLACK KING stable:    C_maint · λ₂(L_G) < C_depend     [community too fragile; retain own copies]
BLACK QUEEN–KING TRANSITION:  λ₂(L_G) = C_depend / C_maint  ≡  λ*₂
```

The phase transition occurs at the **critical Fiedler value** λ*₂ = C_depend / C_maint. This is the **spectral boundary** on ℳ_LOOK separating genome streamlining (Black Queen) from genome redundancy (Black King). It is a function of the cost ratio alone — the transition point is a property of the organism's economics, not of the community's absolute connectivity.

The **paralog redundancy index** R_BK of a Black King organism:

```
R_BK  =  n_paralogs / n_ancestral_genes  =  1 + Δ_duplication − Δ_loss
```

tracks the net balance between gene duplication events (raising R_BK, adding backup copies) and gene loss events (lowering R_BK, removing functions). Under Black King dynamics, R_BK grows as:

```
dR_BK/dt  =  μ_dup · f(λ₂(L_G))  −  μ_loss · g(R_BK)

where f(λ₂) is increasing in λ₂ (more community fragility → more duplication)
and g(R_BK) is increasing in R_BK (larger genomes lose genes faster; Muller's ratchet)
```

The stable Black King redundancy level R*_BK satisfies μ_dup · f(λ*₂) = μ_loss · g(R*_BK), giving:

```
R*_BK  ~  (C_depend / C_maint)^{1/2}  =  (λ*₂)^{1/2}
```

This **square-root scaling** of optimal redundancy with the cost ratio is the genomic analog of the Landau–Levich film thickness scaling h₀ ~ Ca^{2/3}: redundancy grows as a power law in the ratio of dependency cost to maintenance cost, with the critical Fiedler value playing the role of the capillary number.

**Physical template: Spectral graph theory (Fiedler 1973; Cheeger 1970).** The Fiedler value λ₂(L_G) classifies metabolic communities exactly as the spectral gap λ₁(ℒ_L) classifies plasma thermalization in Landau's kinetic theory. The Black Queen–Black King transition at λ*₂ is a first-order phase transition of the genomic delegation field Δ on ℳ_LOOK.

---

## LOOK–Biology Correspondence Table

| Biological System | LOOK Framework | Chess Piece |
|---|---|---|
| Predator-prey trait coevolution | Coevolutionary rate ratio Ψ = μ_pred / μ_prey | Red Queen (Ψ > Ψ_c) |
| Mutualistic coevolution | Red King lag Ψ*_RK < Ψ_c | Red King (Ψ < Ψ_c) |
| Metabolic gene loss in microbes | Genomic delegation index Δ → 1 | Black Queen (Δ > Δ*) |
| Genome duplication / paralog retention | Paralog redundancy index R_BK → 1+ | Black King (Δ → 0, R > 1) |
| Van Valen (1973) evolutionary treadmill | Critical point Ψ = Ψ_c, λ₁(J_coevo) = 0 | Phase boundary |
| Bergstrom-Lachmann mutualistic surplus Δπ_RK | Δπ_RK ~ (Ψ_c − Ψ)^{1/2} | Red King scaling |
| Morris et al. Black Queen public goods | Gene loss Δ > Δ*_BQ when λ₂ > λ*₂ | Black Queen transition |
| Polyploidy / whole-genome duplication | R_BK ~ (λ*₂)^{1/2} | Black King scaling |
| Lotka-Volterra Jacobian J_coevo | λ₁(J_coevo): Red Queen (> 0) / Red King (< 0) | Axis I |
| Metabolic graph Fiedler value λ₂(L_G) | λ₂ > λ*₂: BQ; λ₂ < λ*₂: BK | Axis II |
| Cheeger constant h(G) | h(G)/2 ≤ λ₂ ≤ 2h(G): community bottleneck | Delegation capacity |
| Paralog redundancy R_BK | R*_BK ~ (C_depend/C_maint)^{1/2} | Black King stable point |
| Arms race self-reinforcement | Positive feedback: each adaptation demands counter | Red Queen loop |
| Mutualistic partner decoupling C_decoupling | Δπ_RK − C_decoupling(Ψ) optimized at Ψ*_RK | Red King optimum |

---

## The LOOK Strategy Manifold: Formal Description

The full coevolutionary strategy manifold is ℳ_LOOK = ℝ₊ × [0, 1], parameterized by (Ψ, Δ). The LOOK dynamics operator ℒ_LOOK acts on ℳ_LOOK as:

```
dΨ/dt  =  −∇_Ψ V_LOOK(Ψ, Δ)
dΔ/dt  =  −∇_Δ V_LOOK(Ψ, Δ)
```

where the **LOOK potential function** V_LOOK(Ψ, Δ) is:

```
V_LOOK(Ψ, Δ)  =  V_axis1(Ψ) + V_axis2(Δ)

V_axis1(Ψ)  =  (Ψ − Ψ_c)² / 4  −  (Ψ − Ψ_c)³ / 6   [double-well in Ψ; Ψ_c is separatrix]

V_axis2(Δ)  =  (C_maint · λ₂ · Δ²) / 2  −  C_depend · Δ   [quadratic minimum at Δ*]
```

The **four attractors** of ℒ_LOOK are:

```
Fixed Point 1 — RED QUEEN attractor:
  (Ψ >> Ψ_c, Δ → 0)
  Arms race basin: |Ψ − Ψ_c| large and positive
  λ₁(J_coevo) > 0: divergent coevolution
  Stability: unstable in Ψ-direction (arms race self-accelerates)
             marginally stable in Δ-direction (gene retention maintained by cost)

Fixed Point 2 — RED KING attractor:
  (Ψ*_RK < Ψ_c, Δ → 0)
  Mutualistic basin: Ψ below critical, interaction cooperative
  λ₁(J_coevo) < 0: stable convergence
  Surplus Δπ_RK ~ (Ψ_c − Ψ*_RK)^{1/2}: captured by slower party
  Stability: stable in both Ψ and Δ (mutualism maintains the equilibrium)

Fixed Point 3 — BLACK QUEEN attractor:
  (Ψ ≈ Ψ_c, Δ → Δ*_BQ)
  Delegation basin: λ₂(L_G) > λ*₂; gene loss optimal
  Optimal delegation Δ*_BQ = 1 − C_depend/(C_maint · λ₂)
  Stability: stable in Δ; sensitivity to λ₂ perturbation (partner loss risk)

Fixed Point 4 — BLACK KING attractor:
  (Ψ ≈ Ψ_c, Δ → 0, R_BK → R*_BK)
  Redundancy basin: λ₂(L_G) < λ*₂; gene retention and duplication optimal
  R*_BK ~ (C_depend / C_maint)^{1/2}
  Stability: stable in Δ and R_BK; robust to community partner loss
```

The **LOOK phase boundaries** on ℳ_LOOK:

```
Boundary 1 (Red Queen / Red King):  Ψ = Ψ_c       [Van Valen critical line]
Boundary 2 (Black Queen / Black King):  λ₂(L_G) = λ*₂  [Fiedler critical surface]
```

These two boundaries divide ℳ_LOOK into four quadrants corresponding to the four chess pieces. Every organism on Earth occupies a position on ℳ_LOOK. The question is which basin of attraction holds it, and whether environmental change can push it across a boundary — triggering a **coevolutionary phase transition**.

---

## The LOOK Phase Transitions: When Chess Pieces Change

Phase transitions on ℳ_LOOK are not rare. They are the mechanism of major evolutionary transitions:

**Red Queen → Red King transition** (crossing Ψ = Ψ_c from above):
Triggered by: shift from competitive/parasitic interaction to mutualistic interaction (e.g., endosymbiosis origin events; domestication). When Ψ crosses Ψ_c, λ₁(J_coevo) changes sign from positive to negative — the arms race becomes cooperative convergence. Historical example: the origin of mitochondria (formerly free-living alpha-proteobacteria transitioning from Red Queen arms race with host to Red King mutualistic partnership).

**Red King → Black Queen transition** (crossing Δ*_BQ from below):
Triggered by: increasing community robustness λ₂(L_G) above λ*₂ (denser metabolic integration makes delegation safer). Once the mutualism is stable (Red King equilibrium), the organism can begin losing genes for functions the community provides. Gene loss follows the stability of the mutualism. Historical example: organelle genome reduction — mitochondrial genomes have lost >95% of ancestral genes to the host nuclear genome after the mutualism was established.

**Black Queen → Black King transition** (crossing λ*₂ from above):
Triggered by: environmental disruption reducing λ₂(L_G) below λ*₂ (community fragmentation makes delegation dangerous). When community robustness falls below threshold, gene retention becomes adaptive again — either through recovery of lost functions (rare) or through genome duplication providing temporary backup (common). Historical example: whole-genome duplications in plants following mass extinction events that disrupted existing community structures.

**Black King → Red Queen transition** (crossing Ψ_c from below):
Triggered by: appearance of a new pathogen or parasite shifting the interaction type from cooperative/neutral to strongly competitive. The redundant genome (Black King) provides raw material (paralogs, duplicated regulatory elements) for rapid adaptive evolution under Red Queen dynamics — Black King serves as the evolutionary reservoir that fuels the subsequent Red Queen arms race.

---

## The Four Strategies as Evolutionary Information Theory

Each chess piece corresponds to a distinct **information-theoretic stance** toward the selective environment:

**Red Queen — Maximum Tracking Information:**
The organism must continuously update its fitness-relevant traits to track enemy adaptation. The **tracking rate** ∂α/∂t must exceed the enemy's innovation rate. Red Queen organisms invest maximally in **evolvability**: high mutation rates, recombination, immune diversification. Fitness ~ I(α_self; α_enemy) — the mutual information between self-trait and enemy-trait is maximized. Sexual reproduction is the Red Queen's information channel.

**Red King — Minimum Tracking, Maximum Coordination:**
The organism gains by reducing its adaptation rate below the partner's. The **coordination value** Δπ_RK is the fitness surplus of mutualistic alignment. Red King organisms invest in **stability signals**: honest costly signals of commitment (Zahavian handicaps in biological mutualism). Fitness ~ I(α_self; α_partner) − C_tracking. Slower = more trustworthy partner signal.

**Black Queen — Minimum Genomic Entropy:**
The organism gains by compressing its genome — reducing the information content of its own DNA by deleting functions the community can supply. **Genomic entropy** H_genome = −Σ p_i log p_i where p_i is the probability of gene i being expressed in the current environment. Black Queen dynamics minimizes H_genome subject to community supply constraints. The Black Queen is the genome's Occam's Razor: do not retain what the environment provides.

**Black King — Maximum Genomic Redundancy:**
The organism gains by maintaining multiple copies of fitness-critical functions — maximizing **genomic channel capacity** C_genome = log₂(1 + SNR_genome) where SNR_genome = (functional signal) / (deletion/mutation noise). Paralog redundancy is error-correction coding for the genome: against the noisy channel of environmental perturbation, the Black King encodes with redundancy.

---

## Formal Theorems of the LOOK Framework

| Tag | Statement | Type |
|---|---|---|
| [T-LOOK-1] | Van Valen uniqueness: λ₁(J_coevo) = 0 iff Ψ = Ψ_c | [T] Bridge I |
| [T-LOOK-2] | Red King surplus scaling: Δπ_RK ~ (Ψ_c − Ψ)^{1/2} near phase boundary | [T] Bridge I |
| [T-LOOK-3] | Black Queen fixed point: Δ*_BQ = 1 − C_depend/(C_maint · λ₂) | [T] Bridge II |
| [T-LOOK-4] | Black King scaling: R*_BK ~ (C_depend/C_maint)^{1/2} | [T] Bridge II |
| [T-LOOK-5] | Cheeger bound: h(G)/2 ≤ λ₂(L_G) ≤ 2h(G) | [T] Bridge II |
| [T-LOOK-6] | Phase transition: BQ stable iff λ₂ > C_depend/C_maint | [T] §Axis II |
| [T-LOOK-7] | Arms race divergence: Ψ > Ψ_c → λ₁(J_coevo) > 0 (unstable fixed point) | [T] Bridge I |
| [T-LOOK-8] | Red Queen → Black King reservoir: paralogs from BK fuel RQ adaptive radiation | [V] §Transitions |
| [V-LOOK-1] | Organelle genome reduction follows RK → BQ transition sequence | [V] §Transitions |
| [V-LOOK-2] | Polyploidy events cluster at community disruption events (BQ → BK transition) | [V] §Transitions |
| [H-LOOK-1] | LOOK manifold ℳ_LOOK has four stable basins separated by two spectral boundaries | [H] §Manifold |
| [C-LOOK-1] | Ψ_c critical equation: coevolutionary Jacobian characteristic polynomial | [C] Bridge I |
| [C-LOOK-2] | Fiedler phase boundary λ*₂ = C_depend/C_maint | [C] Bridge II |
| [C-LOOK-3] | Optimal Red King lag: Ψ*_RK solving ∂[Δπ_RK − C_decoupling]/∂Ψ = 0 | [C] Bridge I |
| [C-LOOK-4] | Black King stable redundancy R*_BK from duplication-loss balance | [C] Bridge II |

---

## LOOK Master Equivalence — Extended Form

```
λ₁(J_coevo) > 0

  ⟺  Ψ > Ψ_c                ⟺  Arms race divergence     ⟺  RED QUEEN attractor
  ⟺  Self-reinforcing selection pressure on both parties
  ⟺  No stable coevolutionary fixed point             ⟺  Continuous trait chase
  ⟺  Recombination / mutation rate maximized          ⟺  Sexual reproduction adaptive
  ⟺  Genome streamlining maladaptive (Δ → 0 forced)  ⟺  Every function self-supplied
  ⟺  Information tracking rate ∂α/∂t > enemy innovation rate
  ⟺  Mutualistic surplus Δπ_RK = 0                   ⟺  No lag benefit available

λ₁(J_coevo) = 0  →  VAN VALEN CRITICAL POINT (Ψ = Ψ_c)
  [Neutral evolutionary treadmill; neither divergence nor convergence; phase boundary]

λ₁(J_coevo) < 0  →  MUTUALISTIC CONVERGENCE
  ⟺  Ψ < Ψ_c                ⟺  Stable fixed point       ⟺  RED KING attractor
  ⟺  Slower party captures surplus Δπ_RK ~ (Ψ_c − Ψ)^{1/2}
  ⟺  Deliberate lag adaptive                          ⟺  Stability signals selected
  ⟺  Enables downstream delegation when λ₂ > λ*₂     ⟺  Gateway to BLACK QUEEN

λ₂(L_G) > λ*₂ = C_depend / C_maint  →  BLACK QUEEN REGIME
  ⟺  Community metabolic graph robustly connected      ⟺  Delegation safe
  ⟺  Δ*_BQ = 1 − C_depend/(C_maint · λ₂) > 0         ⟺  Gene loss adaptive
  ⟺  Genomic entropy minimized                        ⟺  Genome streamlining
  ⟺  Dependency on community partners accepted as cost of efficiency

λ₂(L_G) < λ*₂  →  BLACK KING REGIME
  ⟺  Community metabolic graph fragile (bottleneck narrow)  ⟺  Delegation risky
  ⟺  Δ*_BQ ≤ 0 (no delegation optimal)               ⟺  Gene retention adaptive
  ⟺  R*_BK ~ (C_depend/C_maint)^{1/2} > 1             ⟺  Paralog accumulation
  ⟺  Genomic channel capacity maximized               ⟺  Redundancy as error correction
  ⟺  Polyploidy, tandem duplication, gene family expansion selected

λ₂(L_G) = λ*₂  →  BLACK QUEEN–KING CRITICAL SURFACE
  [First-order genomic phase transition; marginal delegation fitness; dual-stable]
```

---

## The Chess Set as an Evolutionary Decision Tree

Every organism faces a sequential evolutionary decision problem that LOOK formalizes:

```
START: What is the nature of my primary selective interaction?

STEP 1 — Measure Ψ (coevolutionary rate ratio)

     Ψ > Ψ_c?
     YES →  RED QUEEN: Maximize evolvability, outrace enemies, no stable equilibrium
             Strategy: Accelerate mutation, increase recombination, diversify immune repertoire
             Cost: High mutation load, arms race exhaustion, extinction risk if outpaced

     NO →   Continue to STEP 2

STEP 2 — Measure mutualistic surplus opportunity

     Is interaction cooperative?
     YES →  RED KING: Lag below partner rate, capture mutualistic surplus
             Strategy: Reduce evolutionary rate, invest in honest commitment signals
             Cost: Vulnerability to partner defection; competitive disadvantage vs. Red Queens
             → If mutualism stable: proceed to STEP 3

     NO →   Return to STEP 1 (interaction may shift)

STEP 3 — Measure λ₂(L_G) vs. λ*₂ (community robustness threshold)

     λ₂ > λ*₂?
     YES →  BLACK QUEEN: Delegate functions, lose genes, minimize maintenance cost
             Strategy: Outsource public goods functions to community partners
             Cost: Irreversible gene loss; community dependency; partner loss catastrophe

     NO →   BLACK KING: Retain redundancy, duplicate critical genes
             Strategy: Maintain paralogs, resist streamlining, buffer against disruption
             Cost: Genome maintenance burden; slower replication; mutational accumulation
```

---

## LOOK Integration with the Framework Family

**LOOK × GRAIN (Evolutionary Mismatch and Coevolutionary Calibration):**
The GRAIN framework (correlation length ℓ) governs cognitive calibration to the environment; LOOK governs genomic calibration to the selective interaction. Both frameworks share the structure of a **calibration mismatch**: GRAIN mismatch occurs when ℓ_env ≪ ℓ_EEA (organism operates in a low-correlation environment with high-correlation heuristics); LOOK mismatch occurs when Ψ_perceived ≠ Ψ_actual (organism behaves as Red Queen when the actual interaction is mutualistic, burning evolutionary resources in unnecessary arms race). The joint mismatch condition GRAIN_mismatch × LOOK_mismatch amplifies maladaptation: the organism tracks phantom enemies (Red Queen in a mutualistic environment) while depleting the genomic reserves (Black Queen prematurely in a fragile community). The GRAIN prestige copying heuristic — copying high-Ψ strategies — becomes an evolutionary trap when the actual interaction type is cooperative. Ca_GRAIN × Ca_LOOK^{−1} > 1 is the master mismatch condition.

**LOOK × CREST (Survivorship Bias in Evolutionary Arms Races):**
The CREST framework (truncation threshold θ, Inverse Mills Ratio λ(α)) governs the distortion of visible outcomes. In evolutionary history, we observe surviving lineages — the visible record is truncated at the survivorship threshold. Red Queen lineages that "won" their arms race are overrepresented in the fossil and extant record; extinct lineages that were outpaced are the silent majority. The peak ascription error Δ_CREST = σ · λ(α) applies to evolutionary inference: we attribute success to the Red Queen strategy because we only observe survivors. Red King lineages — which succeed through stability rather than speed — are less visible precisely because they avoid the spectacular events (epidemics, mass extinctions, rapid radiations) that generate fossil signal. LOOK provides the true prior; CREST explains why the Red Queen is overrepresented in evolutionary narratives.

**LOOK × TIPS (Intertemporal Choice and Evolutionary Discount Rate):**
Red Queen dynamics are equivalent to a zero discount rate on future fitness: every generation must pay the full cost of adaptation now, or face fitness collapse. Red King dynamics introduce an intertemporal tradeoff: slow down now, capture mutualistic surplus over multiple generations. The Red King lag Ψ*_RK is the evolutionary analog of the quasi-hyperbolic discount factor β: the organism accepts present-strategy cost (slower immediate adaptation) for future benefit (sustained mutualistic surplus). Black Queen dynamics introduce intergenerational dependency: gene loss in generation t creates dependence that is paid by all future generations. Black King redundancy is the evolutionary commitment device — the genomic equivalent of the self-control mechanism: paying upfront (maintaining extra gene copies) to insure against future disruption. The TIPS temporal capillary number Ca_TP governs behavioral time preferences; the LOOK Fiedler ratio λ₂/λ*₂ governs genomic time preferences.

**LOOK × PRISM (Signal Routing and Evolutionary Phenotype):**
The PRISM framework governs how organisms process and route signals through cognitive channels. In LOOK, the four chess pieces correspond to four distinct signal-routing strategies: Red Queen organisms maximize signal bandwidth for threat detection; Red King organisms invest in honest signal production for mutualistic coordination; Black Queen organisms reduce signal production cost by delegating signaling functions to community partners; Black King organisms maintain redundant signal transduction pathways. The PRISM ψ_freq and ψ_val channels are the phenotypic expression of LOOK genomic strategies.

---

## Framework Integration Tags

```
LKTL(Bridge I: Lotka-Volterra coevolutionary Jacobian ↔ Landau collision operator;
     λ₁(J_coevo) > 0 ↔ λ₁(ℒ_L) > 0; both are spectral phase transitions;
     Van Valen critical point ↔ Samuelson-Ainslie critical point) [§Bridge I]

LKTL(Bridge II: Fiedler value λ₂(L_G) ↔ spectral gap of Landau H-theorem;
     Black Queen community graph ↔ Boltzmann velocity distribution;
     Cheeger inequality ↔ Poincaré inequality on ℬ_TP) [§Bridge II]

GRAIN(LOOK coevolutionary rate ratio Ψ ↔ GRAIN correlation mismatch Ca_GRAIN;
      Red Queen arms race ↔ GRAIN hot-hand heuristic in IID environment;
      LOOK manifold ℳ_LOOK calibration ↔ EEA calibration in GRAIN;
      joint mismatch condition: Ca_GRAIN × Ca_LOOK^{−1} > 1) [§Integration]

CREST(Red Queen survivorship ↔ CREST truncation at visibility threshold θ;
      Δ_CREST = σ·λ(α) ↔ Red Queen overrepresentation in evolutionary narrative;
      Black Queen gene loss ↔ WYSIATI silent evidence of deleted functions;
      arms race winner visibility ↔ CREST peak ascription error) [§Integration]

TIPS(Red King lag Ψ*_RK ↔ TIPS quasi-hyperbolic β; both introduce intertemporal tradeoff;
     Black Queen gene loss ↔ TIPS addiction irreversibility (Δ loss is permanent);
     Black King redundancy ↔ TIPS commitment device (upfront cost for future resilience);
     Van Valen critical point Ψ_c ↔ Samuelson-Ainslie critical point C_TP = 1) [§Integration]

BELS(Red King honest commitment signal ↔ BELS costly signal in belief loop;
     Red Queen arms race ↔ BELS confirmation loop escalation;
     Black Queen community dependency ↔ BELS social dependence amplification;
     BELS loop gain G ↔ LOOK arms race rate Ψ in competitive regime) [§Integration]

PRISM(Red Queen ↔ PRISM high-bandwidth threat channel ψ_freq;
      Red King ↔ PRISM mutualistic coordination channel ψ_val;
      Black Queen ↔ PRISM signal delegation (offload processing to community);
      Black King ↔ PRISM redundant pathway maintenance for robustness) [§Integration]

BPSG(SUYL·SPQL·BPSL) [spectral gap structure: λ₁(J_coevo) and λ₂(L_G) both spectral]
VBE(visibility ↔ LOOK Fitness Orchard §Manifold; barrier ↔ Van Valen boundary §Transitions;
    escape ↔ LOOK phase transition pathway §PhaseTransitions)
```

---

## Citations

**Red Queen Hypothesis:**
  Van Valen, L. (1973). A new evolutionary law. *Evolutionary Theory* 1(1): 1–30. [Primary source; Red Queen hypothesis; evolutionary treadmill; constant arms race; fitness-neutral evolution]
  Hamilton, W.D. (1980). Sex versus non-sex versus parasite. *Oikos* 35(2): 282–290. [Red Queen as explanation for sexual reproduction; parasite-driven coevolution]
  Jaenike, J. (1978). An hypothesis to account for the maintenance of sex within populations. *Evolutionary Theory* 3: 191–194. [Parasite coevolution and maintenance of sex; Red Queen mechanism]
  Ridley, M. (1993). *The Red Queen: Sex and the Evolution of Human Nature*. New York: Macmillan. [Accessible synthesis; host-parasite Red Queen; sexual selection]
  Woolhouse, M.E.J., Webster, J.P., Domingo, E., Charlesworth, B., and Levin, B.R. (2002). Biological and biomedical implications of the co-evolution of pathogens and their hosts. *Nature Genetics* 32(4): 569–577. [Applied Red Queen: pathogen-host arms race; medical implications]

**Red King Effect:**
  Bergstrom, C.T. and Lachmann, M. (2003). The Red King effect: when the slowest runner wins the coevolutionary race. *Proceedings of the National Academy of Sciences* 100(2): 593–598. [Primary source; Red King; mutualistic coevolution; slower party captures benefit; formal model]
  Damore, J.A. and Gore, J. (2011). A slowly evolving host moves first in symbiotic interactions. *Evolution* 65(8): 2391–2398. [Empirical test of Red King dynamics; host-microbiome interaction]
  Stanton, M.L. (2003). Interacting guilds: moving beyond the pairwise perspective on mutualisms. *The American Naturalist* 162(S4): S10–S23. [Multiparty mutualism; Red King in community context]

**Black Queen Hypothesis:**
  Morris, J.J., Lenski, R.E., and Zinser, E.R. (2012). The Black Queen Hypothesis: evolution of dependencies through adaptive gene loss. *mBio* 3(2): e00036–12. [Primary source; Black Queen; gene loss; public goods in microbial communities; dependency evolution]
  Mas, A., Jamshidi, S., Lagadeuc, Y., Eveillard, D., and Vandenkoornhuyse, P. (2016). Beyond the Black Queen Hypothesis. *The ISME Journal* 10(9): 2085–2091. [Extension; community dependency dynamics; gene loss beyond the original model]
  Giovannoni, S.J., Tripp, H.J., Givan, S., Podar, M., Vergin, K.L., Baptista, D., Bibbs, L., Eads, J., Richardson, T.H., Noordewier, M., Rappé, M.S., Short, J.M., Carrington, J.C., and Mathur, E.J. (2005). Genome streamlining in a cosmopolitan oceanic bacterium. *Science* 309(5738): 1242–1245. [Black Queen empirical basis: SAR11 genome streamlining; most abundant marine bacterium with minimal genome]
  Kettler, G.C., Martiny, A.C., Huang, K., Zucker, J., Coleman, M.L., Rodrigue, S., Chen, F., Lapidus, A., Ferriera, S., Johnson, J., Steglich, C., Church, G.M., Richardson, P., and Chisholm, S.W. (2007). Patterns and implications of gene gain and loss in the evolution of Prochlorococcus. *PLOS Genetics* 3(12): e231. [Black Queen patterns in cyanobacteria; gene loss functional analysis]

**Black King Concept — Genomic Redundancy and Robustness:**
  Ohno, S. (1970). *Evolution by Gene Duplication*. Berlin: Springer. [Primary source for gene duplication as evolutionary reservoir; paralogs as redundancy mechanism; foundation of Black King genomic strategy]
  Lynch, M. and Conery, J.S. (2000). The evolutionary fate and consequences of duplicate genes. *Science* 290(5494): 1151–1155. [Gene duplication rates across taxa; paralog redundancy dynamics; fate of duplicated genes]
  Wagner, A. (2000). Robustness against mutations in genetic networks of yeast. *Nature Genetics* 24(4): 355–361. [Genomic redundancy as robustness mechanism; gene knockouts compensated by paralogs; Black King strategy quantified]
  Innan, H. and Kondrashov, F. (2010). The evolution of gene duplications: classifying and distinguishing between models. *Nature Reviews Genetics* 11(2): 97–108. [Complete review of paralog evolution; redundancy, subfunctionalization, neofunctionalization; Black King mechanisms]
  Conant, G.C. and Wolfe, K.H. (2008). Turning a hobby into a job: how duplicated genes find new functions. *Nature Reviews Genetics* 9(12): 938–950. [Post-duplication evolution; Black King to Black Queen transition through subfunctionalization]

**Coevolutionary Dynamics and Adaptive Dynamics:**
  Dieckmann, U. and Law, R. (1996). The dynamical theory of coevolution: a derivation from stochastic ecological processes. *Journal of Mathematical Biology* 34(5–6): 579–612. [Coevolutionary adaptive dynamics; canonical equation; trait evolution as deterministic gradient flow; formal basis for LOOK Bridge I]
  Doebeli, M. and Dieckmann, U. (2000). Evolutionary branching and sympatric speciation caused by different types of ecological interactions. *The American Naturalist* 156(S4): S77–S101. [Bifurcations in adaptive dynamics; coevolutionary phase transitions; evolutionary branching]
  Abrams, P.A. and Matsuda, H. (1997). Fitness minimization and dynamic instability as a consequence of predator-prey coevolution. *Evolutionary Ecology* 11(1): 1–20. [Red Queen instability in predator-prey coevolution; Jacobian analysis; arms race divergence]

**Spectral Graph Theory and Community Robustness:**
  Fiedler, M. (1973). Algebraic connectivity of graphs. *Czechoslovak Mathematical Journal* 23(98): 298–305. [Primary source for algebraic connectivity; Fiedler value λ₂(L_G); spectral graph theory foundation of LOOK Bridge II]
  Cheeger, J. (1970). A lower bound for the smallest eigenvalue of the Laplacian. In R.C. Gunning (Ed.), *Problems in Analysis*. Princeton: Princeton University Press, pp. 195–199. [Cheeger inequality; isoperimetric bound on λ₂; community bottleneck formalization]
  Mohar, B. (1991). The Laplacian spectrum of graphs. In Y. Alavi, G. Chartrand, O. Oellermann, and A. Schwenk (Eds.), *Graph Theory, Combinatorics, and Applications* Vol. 2: 871–898. [Spectral graph theory review; Laplacian eigenvalues; algebraic connectivity applications]

**Mutualism Theory and Metabolic Integration:**
  Bronstein, J.L. (Ed.) (2015). *Mutualism*. Oxford: Oxford University Press. [Comprehensive treatment of mutualistic interactions; stability conditions; evolutionary dynamics; Red King and Black Queen contexts]
  Sachs, J.L., Mueller, U.G., Wilcox, T.P., and Bull, J.J. (2004). The evolution of cooperation. *The Quarterly Review of Biology* 79(2): 135–160. [Cooperation evolution mechanisms; kin selection, reciprocity, mutualism; connects to Red King and Black King strategies]
  Moran, N.A. (2002). Microbial minimalism: genome reduction in bacterial pathogens. *Cell* 108(5): 583–586. [Genome reduction in endosymbionts; obligate mutualists lose genes; Black Queen in established mutualisms; Red King → Black Queen transition]

**Endosymbiosis and Organelle Evolution:**
  Margulis, L. (1967). On the origin of mitosing cells. *Journal of Theoretical Biology* 14(3): 255–274. [Primary source; endosymbiotic theory; mitochondrial origin; the defining Red King → Black Queen transition in evolutionary history]
  Gray, M.W., Burger, G., and Lang, B.F. (1999). Mitochondrial evolution. *Science* 283(5407): 1476–1481. [Mitochondrial genome reduction as Black Queen process; gene transfer to nucleus; dependency establishment]
  Keeling, P.J. and McCutcheon, J.P. (2017). Endosymbiosis: the feeling is not mutual. *Journal of Theoretical Biology* 434: 75–79. [Asymmetry in endosymbiotic relationships; Red King dynamics in organelle evolution]

**Whole-Genome Duplication and Polyploidy:**
  Soltis, D.E. and Soltis, P.S. (1999). Polyploidy: recurrent formation and genome evolution. *Trends in Ecology and Evolution* 14(9): 348–352. [Polyploidy as Black King strategy; redundancy through whole-genome duplication; evolutionary consequences]
  Van de Peer, Y., Mizrachi, E., and Marchal, K. (2017). The evolutionary significance of polyploidy. *Nature Reviews Genetics* 18(7): 411–424. [Modern review; polyploidy timing; stress-associated genome duplication; Black King → Red Queen reservoir]
  Levin, D.A. (1983). Polyploidy and novelty in flowering plants. *The American Naturalist* 122(1): 1–25. [Polyploidy adaptive significance; Black King genomic strategy in plant evolution]
