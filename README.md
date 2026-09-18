# OpenEvals

OpenEvals builds the open evaluation layer for AI: reusable datasets, evals, benchmarks, and tooling. We are an open community focused on advancing how AI systems, from models and agents to applications and workflows, are tested, measured, and understood.

We build and curate:

* **Resources**: Guides, research, taxonomies, and learning materials
* **Datasets**: Test cases, scenarios, trajectories, and annotations
* **Evals & Benchmarks**: Evaluation tasks, suites, metrics, rubrics, graders, judges, and validation methods
* **Tooling**: Frameworks, harnesses, runners, adapters, simulators, and infrastructure

Evaluation results, reproductions, and validation studies can be published alongside these artifacts.

**Open** means that the artifacts, methods, and knowledge we produce are publicly available, inspectable, and reusable.

## Contributing

OpenEvals welcomes contributions across the four categories above.

| Category               | What belongs here                                                                               | Simple test                                                  | Example                                                         |
| ---------------------- | ----------------------------------------------------------------------------------------------- | ------------------------------------------------------------ | --------------------------------------------------------------- |
| **Resources**          | Knowledge that helps people understand, design, or improve AI evaluation                        | Does it teach, explain, or synthesize evaluation practice?   | Guide to LLM-as-a-judge                                         |
| **Datasets**           | Structured data used to test or analyze AI systems                                              | Is this data an evaluation can operate on?                   | Annotated safety scenarios                                      |
| **Evals & Benchmarks** | Evaluation tasks, suites, benchmarks, metrics, rubrics, graders, judges, and validation methods | Does it define or perform the assessment of system behavior? | Multi-turn instruction-following eval with rubric-based grading |
| **Tooling**            | Software for building, running, integrating, or analyzing evaluations                           | Does it make evaluation easier to build or run?              | Evaluation harness or runner                                    |

These categories are intentionally broad and do not need to be mutually exclusive. An eval may include a dataset, rubric, grader, reference results, and supporting code.

When something fits more than one category, choose the category that best describes the **primary contribution**.

### Ways to contribute

You can:

* add or improve a resource
* contribute a dataset
* publish an eval or benchmark
* contribute a metric, rubric, grader, judge, or validation method
* build or improve evaluation tooling
* reproduce an existing evaluation
* run a validation study
* improve documentation, examples, or workflows

You do not need to build something from scratch. Improving, reproducing, documenting, or validating existing work is just as useful. For larger contributions, open an issue first so the community can discuss the idea before you invest a lot of time.

## Contribution principles

We value work that is:

**Useful**:
It should help someone evaluate or better understand an AI system.

**Transparent**:
People should be able to understand what is being measured and how.

**Reusable**:
Where practical, contributions should be structured so others can use, adapt, or extend them.

**Reproducible**:
Methods, assumptions, versions, and execution conditions should be documented well enough for someone else to repeat the work.

**Honest about limitations**:
An eval does not need to measure everything. It should be clear about what it does and does not tell us.

## Results, reproductions, and validation

Evaluation results, reproductions, and validation studies are welcome alongside the artifacts they relate to.

Results should be tied to a specific version of the eval and include enough information about the system and execution conditions to make them interpretable.

Reproductions and validation work are especially valuable, including cases where results do not reproduce or where an evaluation turns out to have important limitations.

## Community Code of Conduct

OpenEvals is a collaborative community built around rigorous work, open discussion, and good-faith contribution.

Please follow a few simple expectations:

* critique the work, not the person
* be constructive and explain your reasoning
* give credit, document provenance, and respect licenses
* contribute work that is relevant, reviewable, and of sufficient quality for others to understand or use
* respect privacy and do not contribute improperly obtained, proprietary, confidential, or otherwise restricted data
* use AI tools responsibly: review and verify generated content before contributing it, and avoid low-quality or bulk-generated submissions
* do not submit fabricated, malicious, deceptive, or intentionally misleading artifacts, data, results, or claims
* no harassment, discrimination, spam, or other abusive behavior

We welcome disagreement, competing approaches, failed experiments, negative results, and critical findings when they help improve how AI systems are evaluated.

