# Research Engineering Portfolio

A roadmap for **30 independent, reproducible research prototypes**, starting
with three CPU-runnable projects. This is a staged plan, not a claim that 30
repositories or scientific discoveries already exist.

## First implementation batch

| Repository | Research question | Scope |
|---|---|---|
| [vision-invariance-lab](https://github.com/Shereen20112003/vision-invariance-lab) | How does augmentation change learned shape representations under nuisance shifts? | Synthetic vision, linear/deep baselines, representation analysis |
| [release-shift-bench](https://github.com/Shereen20112003/release-shift-bench) | Do curve surrogates and simultaneous uncertainty bands generalize across a formulation-feature shift? | Synthetic release dynamics, surrogate baselines, conformal calibration |
| [contextual-inventory-lab](https://github.com/Shereen20112003/contextual-inventory-lab) | When does a quantile decision outperform mean prediction in a capacity-constrained newsvendor? | Synthetic demand, exact oracle, cost and regret evaluation |

Each project is separate, MIT licensed, and includes tests, dependency locking,
CLI experiments, measured example outputs, and explicit limitations.
GitHub Actions templates are retained locally pending permission to publish
workflows; hosted CI is not yet enabled. Local tests passed for all three projects.
The links are publication destinations; consult each repository for its actual
implementation and checks. The remaining projects below are **planned only**:
no empty placeholder repositories are needed to inflate the count.

## Research alignment, not affiliation

- [James DiCarlo](https://dicarlolab.mit.edu/): neural mechanisms of visual
  intelligence. Synthetic invariance experiments are relevant preparation, not
  evidence of neural predictivity or human-like cognition.
- [Robert Langer](https://langerlab.mit.edu/): delivery materials and controlled
  release, including mathematical modeling. Toy simulators cannot establish
  delivery efficacy, toxicity, or clinical utility.
- [Caroline Uhler](https://www.carolineuhler.com/): multimodal learning, causal
  relationships, and cellular regulatory programs. Causal projects require
  explicit assumptions and interventional/observational distinctions.
- [Regina Barzilay](https://www.rbg.mit.edu/): molecular interactions,
  biomolecular design, and clinical ML. Molecular prediction is a different
  task from material release prediction; do not conflate them.
- [Georgia Perakis](https://mitsloan.mit.edu/faculty/directory/georgia-perakis):
  optimization and ML for pricing, revenue management, supply chains, and more.
- [MIT Media Lab Personal Robots](https://www.media.mit.edu/groups/personal-robots/overview/):
  human-agent interaction, learning, and responsible design. Synthetic-agent
  evaluation does not substitute for consented human studies.
- [Pramod Viswanath](https://ece.princeton.edu/people/pramod-viswanath):
  the multi-agent/information-constrained track below is a proposed fit to
  investigate. The profile could not be retrieved during planning, so no
  specific current lab project or paper alignment is asserted.
- **Princeton "Suma" remains unidentified.** Do not attribute work to a guessed
  person. Confirm the full name and official research page before refining fit.

No affiliation, endorsement, admission advantage, new theorem, or novel scientific
result is claimed. Faculty names contextualize themes, not repository branding.

## Thirty-project roadmap

All rows after the first three are proposals, not completed contributions.
Default acceptance: deterministic CLI, independent evaluation data, at least
one meaningful baseline, negative/edge-case tests, measured output, a license,
and documented failure modes.

| # | Repository / track | Testable question or deliverable | Baseline and evaluation |
|---|---|---|---|
| 1 | `vision-invariance-lab` / cognition + DL | Does augmentation improve shifted object recognition and representation stability? | Linear pixels vs two-hidden-layer network; accuracy, RSA, seed variation |
| 2 | `release-shift-bench` / delivery | How do formulation covariate shifts affect release prediction and uncertainty? | Mean/ridge/trees; curve MAE, simultaneous coverage, projection ablation |
| 3 | `contextual-inventory-lab` / IEOR | Does a cost-aligned quantile policy reduce expected inventory regret? | Mean/global quantile/calibrated reserve/quantile boosting; exact feasible oracle |
| 4 | `occlusion-recurrence-bench` / cognition | Does iterative refinement help at matched parameter and compute budgets? | Feedforward vs recurrent tiny network; occlusion curves, latency, ablations |
| 5 | `synthetic-neural-encoding` / cognition | When do feature similarity and held-out neural encoding disagree? | Simulated neurons, ridge probes; cross-validated encoding, noise ceilings |
| 6 | `active-vision-budget` / cognition | Can uncertainty-guided glimpses reduce observations without hiding compute? | Random/fixed/active glimpses; accuracy per glimpse and total operations |
| 7 | `release-design-active-learning` / delivery | Which uncertainty strategy reduces queries to a toy simulator? | Random vs ensemble uncertainty; best-found objective vs simulator calls |
| 8 | `delivery-transport-identifiability` / delivery + theory | Can distinct parameters produce indistinguishable diffusion curves? | Analytic toy diffusion, grid fitting; profile likelihood, recovery error |
| 9 | `perturbation-causal-recovery` / Uhler-oriented | Which interventions distinguish observationally equivalent cell networks? | Synthetic structural causal models; edge recovery and intervention cost |
| 10 | `morphology-transcript-alignment` / bioinformatics | Can representations align morphology with expression without batch leakage? | Synthetic paired modalities first; retrieval, batch-held-out accuracy |
| 11 | `molecular-scaffold-calibration` / molecular AI | How much does random splitting overstate calibration relative to scaffold splits? | Licensed public molecular data after review; linear fingerprints vs trees, coverage |
| 12 | `docking-pose-symmetry-tests` / molecular AI | Do pose metrics incorrectly penalize equivalent molecular symmetries? | Small synthetic geometries; rigid-transform and atom-permutation invariance tests |
| 13 | `pricing-elasticity-shift` / IEOR | What happens when fitted elasticity is wrong under constrained prices? | Fixed-price vs plug-in/robust pricing; simulated revenue regret |
| 14 | `promotion-confounding-lab` / IEOR + causality | When does association-based promotion allocation fail? | Synthetic confounding; randomized oracle, naive regression, policy value |
| 15 | `capacity-allocation-fairness` / IEOR | What is the measurable efficiency/fairness tradeoff under scarce capacity? | Small exact solver vs heuristic; feasibility, welfare, group allocation gaps |
| 16 | `energy-demand-decision-lab` / IEOR | Does probabilistic forecasting improve reserve decisions? | Synthetic seasonality; point vs quantile forecasts, shortage cost, temporal splits |
| 17 | `accessible-gesture-lab` / Media Lab + vision | How sensitive is gesture recognition to viewpoint and missing landmarks? | Synthetic landmarks, linear vs temporal model; per-condition accuracy, latency |
| 18 | `consent-first-social-agent-sim` / Media Lab | Can a simulated assistant respect explicit opt-out and interruption rules? | Scripted vs learned policy; rule violations, task success, no human inference claims |
| 19 | `creative-feedback-diversity` / Media Lab | Can constrained feedback avoid repetitive suggestions in a toy creative task? | Template/random vs diversity-aware selection; novelty and explicit rule checks |
| 20 | `conformal-shift-counterexamples` / theory | Construct distributions where marginal coverage fails under shift. | Exact small distributions plus Monte Carlo; derived vs empirical coverage |
| 21 | `performative-fixed-point-lab` / theory | When does repeated predictive retraining converge or cycle? | Linear feedback models; spectral-radius argument, numerical residuals |
| 22 | `decision-regret-bound-checker` / theory | How tight are Lipschitz forecast-error-to-decision-regret bounds? | Hand-derived finite examples; exhaustive search and adversarial counterexamples |
| 23 | `communication-budget-agents` / multi-agent | Which messages matter under explicit bandwidth constraints? | No communication/full communication/compressed messages; reward per bit |
| 24 | `decentralized-consensus-lab` / multi-agent | How do graph topology and delay affect consensus? | Average consensus/push-sum; convergence rate, connectivity assumptions |
| 25 | `agent-delegation-budget` / multi-agent | Can uncertainty-aware task allocation beat fixed delegation under query limits? | Scripted synthetic agents first; success, query cost, correlated-error ablation |
| 26 | `robot-localization-shift` / robotics | How robust are localization filters to misspecified sensor noise? | 2D simulator, EKF vs particle filter; RMSE, consistency, lost-track rate |
| 27 | `safe-grid-navigation` / robotics | Does a safety shield trade off progress and collision avoidance? | Grid-world planner vs shielded policy; collisions, completion, deadlocks |
| 28 | `vision-grasp-geometry` / robotics + vision | How do camera perturbations alter analytic grasp proposals? | Synthetic depth primitives; geometry baseline, calibration errors, no hardware claims |
| 29 | `cell-segmentation-shift` / bioinformatics + CV | Does synthetic morphology variation improve out-of-domain segmentation? | Threshold/watershed vs small network; instance IoU, split/merge counts |
| 30 | `spatial-cell-graph-lab` / biochemistry + CV | How do segmentation errors propagate into cell-neighborhood statistics? | Synthetic tissues; nearest-neighbor vs radius graphs, interaction estimation error |

## Staging

1. **Foundation:** finish, test, and publish projects 1-3; inspect actual results.
2. **Breadth:** choose one from each of Media Lab, multi-agent, robotics, and
   bioinformatics (17, 23, 26, 29 are suggested).
3. **Depth:** add stronger datasets and ablations to existing work before
   expanding the repository count. Confirm dataset redistribution rights.
4. **Theory:** implement 20-22 with stated assumptions, derivations, counterexamples,
   and numerical checks. Numerical experiments are not mathematical proofs.
5. **Expansion:** build the remaining proposals only with the same quality bar.

Every inference-backed project should also have an offline deterministic fixture
for tests. Provider adapters must read credentials from the environment, record
model IDs and usage metadata without secrets, and make spending explicit.
No hosted model is necessary for the first three scientific benchmarks.

## Open-source contribution plan

External PRs require the owner's approval before submission. These are candidate
ecosystems, **not claims of accepted work or currently open suitable issues**:

| Ecosystem | Bounded contribution to investigate | Evidence before a PR |
|---|---|---|
| [Brain-Score](https://github.com/brain-score/vision) | Reproducible small test for a metric or benchmark adapter | Read contribution guide; reproduce a real issue; no invented neural data |
| [DeepChem](https://github.com/deepchem/deepchem) | Dataset-split or uncertainty tutorial regression test | Confirm supported API, fixture licensing, and existing tests |
| [scikit-learn](https://github.com/scikit-learn/scikit-learn) | Minimal documented metric/quantile edge-case example | Reproduce on supported version; discuss scope before adding features |
| [PettingZoo](https://github.com/Farama-Foundation/PettingZoo) | Multi-agent environment contract regression test | Use official environment tests; reproduce a documented bug |
| [scikit-image](https://github.com/scikit-image/scikit-image) | Small synthetic segmentation edge-case test | Quantify expected behavior; check duplicate issues/PRs |

Workflow: inspect maintainers' guidance and current issues, obtain approval for
the specific PR, reproduce, make a surgical fix, run targeted upstream tests,
and describe provenance honestly. Follow each project's AI-assistance disclosure
rules. No Copilot co-author trailer is added at the portfolio owner's request;
that does not waive upstream policies or justify misleading authorship claims.

## What this portfolio does not contain

Private workplace code, internal documentation, credentials, clinical data,
proprietary model weights, or fabricated research results. A local development
tool's authentication configuration is not part of any published repository.

MIT licensed. Copyright 2026 Shereen20112003.
