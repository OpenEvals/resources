# OpenEvals Glossary

A shared vocabulary for building, running, and interpreting evaluations of AI systems.

> This glossary focuses on terms that are central to OpenEvals or used in different ways across AI evaluation. It reflects OpenEvals terminology and is intended as a practical shared vocabulary, not a formal standard or exhaustive taxonomy. Usage may differ across research communities and evaluation frameworks.

## Evaluation artifacts

| Term | Definition |
| --- | --- |
| **System** | The AI system being evaluated. A system may be a model, agent, application, workflow, or other AI-enabled system. |
| **Resource** | A guide, paper, taxonomy, tutorial, or other material that helps people design, run, or understand AI evaluations. |
| **Dataset** | A collection of evaluation items or recorded examples. It may contain prompts, references, scenarios, traces, trajectories, annotations, or other structured data used to run or analyze an evaluation. |
| **Item** | A single unit within a dataset used in an evaluation. An item may produce one or more system interactions, outputs, or scores. |
| **Task** | A unit of work or behavior that a system is asked to perform as part of an evaluation. A task may be represented by one item or instantiated across many items. |
| **Reference** | An expected output, target label, answer key, or other comparison target paired with an item. Evaluations may be reference-based or reference-free. |
| **Ground truth** | A trusted value or annotation treated as the best available representation of what is true or correct for an item. Some evaluation tasks, particularly subjective or open-ended ones, may not have meaningful ground truth. |
| **Annotation** | A label, judgment, reference, explanation, or other information added to an evaluation item or system behavior. |
| **Annotator** | A human or system that produces annotations. |
| **Scenario** | A structured situation in which a system is evaluated, often including context, goals, constraints, or a simulated counterpart. |
| **Trace** | A recorded representation of an AI system execution, including relevant inputs, outputs, intermediate events, tool calls, metadata, and timing. |
| **Trajectory** | The sequence of states, actions, tool calls, observations, and responses produced as a system progresses through a multi-step or interactive task. A trajectory describes the behavioral path; a trace is its recorded representation. |
| **Evaluator** | A component or procedure that assesses system behavior and produces a score, label, judgment, or feedback. Evaluators include graders, judges, critics, verifiers, and human evaluation procedures. |
| **Score** | A value or label assigned to an evaluation item, output, or trajectory by an evaluator. Scores may be aggregated into metrics. |
| **Metric** | A quantitative measure computed from scores, outputs, or other evaluation data, often by aggregating across items. |
| **Rubric** | A scoring standard defining the criteria and guidance used to assess system behavior. |
| **Grader** | An evaluator that assigns a score or label using a rubric, answer key, or comparison criteria. |
| **Judge** | A model used as an evaluator, typically scoring, labeling, or comparing outputs against specified criteria. A judge applying a rubric or answer key is a model-based grader. When the model is an LLM, this is commonly called LLM-as-a-judge. |
| **Critic / Critic agent** | A model or agent that inspects system behavior and identifies errors, weaknesses, or opportunities for improvement. Critics may produce feedback, scores, or both and are often used in iterative evaluation and refinement workflows. |
| **Verifier** | An evaluator that deterministically checks whether a specified property holds, using rules, tests, execution, constraints, or formal checks. |
| **Eval** | A reusable specification for measuring AI system behavior. It defines what is tested, how the system is run, how its behavior is evaluated, and how results are interpreted or aggregated. An eval may include a dataset or task definition, execution setup, evaluators, and a protocol. |
| **Benchmark** | An eval used as a shared point of comparison across systems. Benchmark status comes from its role in comparison—whether by design or through repeated community use—rather than from a particular technical structure. |
| **Protocol** | The specified procedure for running and interpreting an eval, including execution conditions, sampling, repetitions, scoring, aggregation, and reporting. |

## Execution and tooling

| Term | Definition |
| --- | --- |
| **Tooling** | Software used to build, execute, integrate, or analyze evaluations. |
| **Harness** | The execution layer that turns an evaluation item or task into a system interaction and captures the resulting behavior for evaluation. It may define prompt formatting, tools, environment access, context management, interaction loops, or other execution conditions.<br><br>*Usage note:* Some evaluation frameworks use *harness* to refer to the entire evaluation system; here it denotes the system-facing execution layer, distinct from the runner. |
| **Runner** | The orchestration layer that executes evaluations across items and systems, invokes the relevant harness and evaluators, and records results. |
| **Adapter** | A component that connects evaluation tooling to a particular model API, framework, provider, or runtime. |
| **Simulator** | A component that represents a user, environment, or other counterpart so interactive or multi-turn behavior can be evaluated. |

## What an eval measures

| Term | Definition |
| --- | --- |
| **Construct** | The underlying property an eval intends to measure, such as factuality, helpfulness, task success, or instruction following. |
| **Operationalization** | The concrete procedure used to measure a construct, including the items, execution conditions, evaluators, scoring rules, and aggregation method. |
| **Validity** | The degree to which available evidence supports the intended interpretation of an eval, including the claim that it measures its intended construct. |
| **Reliability** | The consistency of evaluation results under repeated or equivalent measurement conditions, such as repeated runs, alternative item samples, annotators, evaluators, or prompt variants. |
| **Capability evaluation** | Evaluation of what a system can do when given sufficient prompting, scaffolding, tools, or other support to demonstrate the capability. |
| **Propensity evaluation** | Evaluation of what a system tends to do, or how frequently it exhibits a behavior, under specified or representative conditions. |

## Evaluation quality

| Term | Definition |
| --- | --- |
| **Contamination** | Evaluation data appearing in a system's training data, directly or through derived or closely related versions. |
| **Leakage** | Information available during evaluation that would not legitimately be available in the intended use setting. Distinct from contamination, which concerns evaluation data appearing in training data. |
| **Saturation** | The point at which an eval no longer meaningfully distinguishes between stronger systems because performance has clustered near its ceiling. |
| **Disagreement** | Differences between evaluator or annotator judgments. Disagreement may indicate error, ambiguity, underspecified rubrics, subjective preference, or an underspecified or contested construct. |
| **Uncertainty** | Variation around an evaluation result arising from item sampling, model stochasticity, evaluator variation, prompt variation, or other sources. |

## Results and validation

| Term | Definition |
| --- | --- |
| **Result** | The output of running a specific version of an eval against a specific system under specified conditions. |
| **Baseline** | A reference result used to interpret another result, such as random performance, a previous system, or human performance. |
| **Reproduction** | Rerunning an existing eval or recreating its setup to determine whether its reported results or findings still hold. Reproductions should document what was held constant and what changed. |
| **Validation study** | A study designed to produce evidence about the validity of a specific evaluator or eval. |
| **Provenance** | The recorded origin and transformation history of an evaluation artifact, including sources, annotations, filtering, and licensing. |
| **Version** | A specific state of an evaluation artifact. Changes to datasets, rubrics, evaluators, or protocols can change what a result means and should therefore be versioned. |

---

## Contributing

To propose a new term or suggest a change to an existing definition, open an issue or pull request in the OpenEvals repository.

*Version 1.0 · September 2026*
