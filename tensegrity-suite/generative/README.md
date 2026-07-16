# Tensegrity Generative Standards

<p align="center">
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="../../images/generative-cables-0_1_0-dark.svg">
  <img alt="The generative standards as the cables of a tensegrity figure: the continuous tension network that connects the rigid members and holds the whole in shape." src="../../images/generative-cables-0_1_0-light.svg" width="420">
</picture>
</p>

Three standards that specify the structural conditions under which coordination capacity develops and is sustained. Structural floors alone are not enough: a coordination system also needs conditions for shared understanding, participant capacity, and conflict transformation. These standards address that generative layer.

In the suite's tensegrity architecture these are the cables: the continuous tension network that connects everything and keeps the rigid members in relation. They are what make the [seven compressive standards](../compressive/) trustworthy in practice: several compressive audits produce false negatives when generative conditions are depleted, which is why the [detection reliability dependencies](../../README.md#how-the-standards-work-together) pair specific compressive standards with the generative conditions their detection depends on.

## The three standards

| Standard | Version | Provides | Text |
| --- | --- | --- | --- |
| **Sensemaking** | 1.1.23 | What sensemaking must structurally provide for coordination to remain self-correcting. Five structural invariants across three operational scales. | [Read](standards/standards-3_0-sensemaking-1_1_23.md) |
| **Four Batteries Capacity** | 0.3.7 | The structural conditions under which four orthogonal capacity dimensions (Personal, Relational, Contribution, Mission) enable coordination surplus rather than merely preventing failure. | [Read](standards/standards-3_0-four-batteries-capacity-0_3_7.md) |
| **Conflict Transformation** | 0.2.10 | The structural conditions under which a coordination system develops and sustains conflict transformation capacity, so conflict reorganizes the system instead of cycling. | [Read](standards/standards-3_0-conflict-transformation-0_2_10.md) |

Full architectural summaries for every standard are in the [suite README](../../README.md#the-three-tensegrity-generative-standards).

## Working with these standards

Each standard has an AI capacity-development prompt in [`prompts/`](prompts/) (one subfolder per standard) and a Claude skill in [`skills/`](skills/). The presence assessments are the designed entry point: copy one into any AI assistant and describe the coordination system to assess. The [prompt launcher site](https://coordination-structural-integrity-suite.github.io/ai/) serves all of them without navigating this repository.

The [Conflict Transformation Preconditions Specification](../compressive/specifications/conflict-transformation-preconditions-specification-0_1_0.md) is the operational companion for the Conflict Transformation Standard: six precondition domains assessed before deploying any specific process.
