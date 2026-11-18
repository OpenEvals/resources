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

## Our Mission

OpenEvals is an open, community-led research initiative dedicated to making AI evaluation more rigorous, representative, and accessible.

We bring together people with diverse expertise, languages, cultures, and perspectives to evaluate AI systems in the contexts that matter to them. Through participatory research, we develop and share open datasets, evaluations, methods, and tools that help us better understand AI capabilities, limitations, and real-world behavior.

Our goal is to understand where AI works, where it fails, for whom, and why. Above all, we value genuine curiosity, independent thinking, research integrity, and thoughtful collaboration.

## Community Code of Conduct

OpenEvals is a collaborative community built around rigorous research, open discussion, and good-faith contributions.

### Community Discussion Guidelines

We welcome open discussion, constructive criticism, and diverse perspectives. To keep discussions productive:

- **Understand the context.** Review relevant materials, objectives, and scope before providing feedback. Ask questions when something is unclear.
- **Be constructive.** Provide specific, actionable feedback supported by clear reasoning and, where possible, evidence or examples.
- **Think critically.** Distinguish observations, opinions, and proposals. Challenge assumptions and remain open to different perspectives.
- **Stay focused.** Keep contributions relevant, concise, and meaningful. Use GitHub issues or discussions for extensive proposals.
- **Respect others.** Engage in good faith, welcome disagreement, and be mindful of everyone's time and effort. Any form of harassment, discrimination, spam, and abusive behavior are prohibited.

### Contribution Guidelines

We welcome contributions of resources, datasets, evaluations, benchmarks, tools, reproductions, validation studies, and documentation. We also welcome failed experiments, negative results, and critical findings that advance our collective understanding.

We value contributions that are:

- **Useful and relevant.** Help others evaluate or better understand AI systems.
- **Transparent and reproducible.** Clearly document methods, assumptions, provenance, results, and limitations.
- **Reusable.** Structure work so others can understand, validate, adapt, or extend it.
- **Responsible.** Give credit, respect licenses and consent, and protect privacy. Never share improperly obtained, confidential, proprietary, or restricted data.
- **Honest and trustworthy.** Ensure the accuracy and integrity of contributions. Fabricated, deceptive, malicious, or intentionally misleading data, results, artifacts, and claims are prohibited.

### Responsible AI Usage

We encourage using AI tools to support research, brainstorming, coding, writing, and other community activities. Contributions should reflect your own understanding, reasoning, and judgment.

- **Bring your own perspective.** Human judgement and experience are core to OpenEvals. Bring your own perspective and critically assess AI-generated suggestions.
- **Prioritize quality.** Avoid lengthy, unreviewed, or bulk-generated AI content. Share concise, relevant insights that add value to the discussion.
- **Be transparent.** Acknowledge substantial AI-generated contributions.
- **Take responsibility.** Verify the accuracy, relevance, and quality of everything you share.
