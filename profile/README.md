<div align="center">

<img src="https://raw.githubusercontent.com/OntosWorld/.github/main/assets/ontos-hero.svg" width="100%" alt="Ontos — Physical Intelligence for Machines" />

<br/>

# Ontos

### Physical intelligence for machines.

Helping machines understand the real world, reason about what is happening, and decide what to do next.

<br/>

[**Website**](https://www.ontos.ws/) &nbsp;&nbsp;·&nbsp;&nbsp;
[**P37 Neuro**](https://github.com/OntosWorld/P37-Neuro) &nbsp;&nbsp;·&nbsp;&nbsp;
[**Sense**](https://github.com/OntosWorld/Sense) &nbsp;&nbsp;·&nbsp;&nbsp;
[**X / Twitter**](https://x.com/OntosWorld)

</div>

---

## Intelligence for the physical world

AI systems have become very good at understanding text, images and software.

Robots have a different problem.

They need to understand **space, motion, objects, machine state, physical constraints and change over time** — then turn that understanding into useful action.

Ontos is building the models and infrastructure for that layer.

<div align="center">

### SEE → UNDERSTAND → REASON → ACT → LEARN

</div>

<img src="https://raw.githubusercontent.com/OntosWorld/.github/main/assets/ontos-stack.svg" width="100%" alt="Ontos Physical Intelligence Stack" />

---

## What we're building

<table>
<tr>
<td width="50%" valign="top">

### P37 Neuro

**Shared intelligence across different robot bodies.**

P37 Neuro is Ontos' general-purpose robot intelligence program.

It is designed to let one learned system understand different embodiments, tasks and environments instead of requiring a completely separate intelligence stack for every robot.

It connects perception, embodiment understanding, task context, long-term physical memory, high-level reasoning, low-level control, simulation and real-world learning.

[**Explore P37 Neuro →**](https://github.com/OntosWorld/P37-Neuro)

</td>
<td width="50%" valign="top">

### Sense

**What can this machine actually do right now?**

Sense turns raw machine telemetry into validated, normalized and explainable capability context.

Instead of only reporting sensor values, Sense helps other systems understand whether a machine is currently:

`AVAILABLE` · `DEGRADED` · `UNAVAILABLE` · `UNKNOWN`

with structured evidence explaining why.

Supports machine data from ROS 2, MQTT, HTTP, simulation and connected machine ecosystems.

[**Explore Sense →**](https://github.com/OntosWorld/Sense)

</td>
</tr>
</table>

<table>
<tr>
<td width="50%" valign="top">

### Verify

**Trust the information machines produce.**

Verify is developer infrastructure for attaching verifiable evidence to machine-generated data and physical-system events.

```bash
npm i @ontosworld/verify
```

Useful when machine information needs to move between systems without relying entirely on the source saying: trust me.

[**View package →**](https://www.npmjs.com/package/@ontosworld/verify)

</td>
<td width="50%" valign="top">

### World Reasoning Models

**Models built to reason about the physical world.**

Ontos is researching models focused on the intelligence machines need outside of screens.

Areas include spatial reasoning, physics, mathematics, geometry, object behaviour, motion, machine state and physical cause and effect.

Our model program includes smaller open models and larger service-based systems.

</td>
</tr>
</table>

---

## One intelligence layer. Different machines.

<img src="https://raw.githubusercontent.com/OntosWorld/.github/main/assets/embodiments.svg" width="100%" alt="Ontos intelligence across robot embodiments" />

A useful physical-intelligence system should not assume that every machine has the same body.

A humanoid, robotic arm, mobile robot or industrial system may have completely different joints, sensors, actuators, control rates, limits, kinematics and capabilities.

The intelligence layer should understand those differences rather than being rebuilt from scratch around them.

That is one of the main ideas behind our work.

---

## Physical intelligence needs more than perception

<table>
<tr>
<td width="25%" valign="top">

### 01 / World

Understand what exists, where it is and how things relate.

</td>
<td width="25%" valign="top">

### 02 / Machine

Understand the body, sensors, limits and current capability of the machine.

</td>
<td width="25%" valign="top">

### 03 / Reasoning

Understand what should happen next given the goal and physical state.

</td>
<td width="25%" valign="top">

### 04 / Trust

Know whether the observations, machine state and resulting actions can be relied on.

</td>
</tr>
</table>

---

## From observation to action

```text
                         physical world
                               │
                               ▼
                    ┌────────────────────┐
                    │     perception     │
                    │ sensors + context  │
                    └─────────┬──────────┘
                              │
                              ▼
                    ┌────────────────────┐
                    │ world understanding│
                    │ objects · geometry │
                    │ motion · state     │
                    └─────────┬──────────┘
                              │
              machine context │
                    ┌─────────▼──────────┐
                    │     reasoning      │
                    │ goal · history     │
                    │ physics · intent   │
                    └─────────┬──────────┘
                              │
                              ▼
                    ┌────────────────────┐
                    │       action       │
                    │ policy + control   │
                    └─────────┬──────────┘
                              │
                              ▼
                            robot
                              │
                              └──────────────► learn
```

---

## Start here

| If you want to... | Start with |
|---|---|
| Build intelligence that can work across different robot bodies | [**P37 Neuro →**](https://github.com/OntosWorld/P37-Neuro) |
| Understand what a machine can currently do | [**Sense →**](https://github.com/OntosWorld/Sense) |
| Verify machine-generated data | [**Verify →**](https://www.npmjs.com/package/@ontosworld/verify) |
| Explore manufacturer-neutral robot communication | [**UMP →**](https://github.com/promiseeuler/UMP) |
| Understand the wider Ontos vision | [**ontos.ws →**](https://www.ontos.ws/) |

---

## Languages

Our current robotics and machine infrastructure spans:

**Python** · **C++** · **Bash** · **CMake**

Python drives much of the model, SDK and tooling layer, while C++ is used for performance-sensitive robot runtime work, including the P37 Neuro C++ runtime and ROS 2 integration.

---

## Open infrastructure

Some parts of Ontos are being built in the open because physical intelligence will require more than one company, one robot manufacturer or one machine architecture.

We are especially interested in collaboration around:

**robot learning · world models · simulation · cross-embodiment intelligence · spatial reasoning · machine context · verification · robot infrastructure**

---

<div align="center">

## Machines should understand more than what they can see.

### We're building the intelligence layer for the physical world.

<br/>

[**Explore Ontos →**](https://www.ontos.ws/)

<br/>

[GitHub](https://github.com/OntosWorld) &nbsp;&nbsp;·&nbsp;&nbsp;
[X](https://x.com/OntosWorld)

<br/><br/>

<sub>Ontos · Physical Intelligence</sub>

</div>
