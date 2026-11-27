# SAFA Foresight Skills

Nine Claude skills for running a participatory foresight workshop: horizon scanning, critical uncertainties, scenarios, a shared vision and first priorities. By Ariella Helfgott and SA Futures Agency.

## Whose work this is

The method, the workshop design and the knowledge written into these skills are the intellectual work of Ariella Helfgott and SA Futures Agency. Ariella has built this practice over more than 20 years of foresight work in 26 countries, and SA Futures Agency, which she directs with Stavroula Adameitis, runs it with governments, businesses and communities.

We bring this method into the projects we work on. No single project, client or funder created it or owns it. We are sharing it here for public benefit.

You are welcome to use and adapt all of it. When you do, please say whose work it is. [How to credit and cite](#how-to-credit-and-cite) explains how.

## Why we are sharing it

A method like this lives mostly in the heads of the people who run it. We wrote ours down as Claude skills so that the steps, the checks, the wording and the reasons behind them travel in a form a new team can use on the day. We are publishing the skills openly because a method improves when more people use it and say where it falls short.

## How the day and a half runs

| When | What happens |
|---|---|
| Day 1, half a day | The room scans the horizon, agrees the critical uncertainties, and each table writes the ways one uncertainty could turn out by the target year. These are the end states. |
| Between the days | The facilitation team works out which end states can be true together, removes the combinations that cannot, and chooses one scenario skeleton for each table. |
| Day 2, full day | Each table builds and names a scenario from its skeleton and reports back. The whole room then builds one shared vision and names first priorities. |

## The nine skills, in the order you use them

| | Skill | What it does |
|---|---|---|
| 1 | `foresight-workshop-setup` | Plans a workshop for a new country or topic: run sheet, roles, checklists, fact base outline, provocations and Mentimeter questions. |
| 2 | `foresight-workshop-materials` | Makes the slides and the A3 placemats. |
| 3 | `day1-capture-to-end-states` | Turns the day 1 flipcharts, notes and Mentimeter results into critical uncertainties and clearly written end states. |
| 4 | `compatibility-matrix` | Rates every pair of end states, with reasons, and prepares the team review. |
| 5 | `morphological-analysis` | Builds every combination of end states, removes those that cannot be true together, and tests the ratings the team disagreed on. |
| 6 | `scenario-families` | Groups the combinations that remain into families and shortlists one candidate from each. |
| 7 | `scenario-set-selection` | Starts from one anchor the team picks, builds the set of skeletons from it, one for each table, and writes them up. |
| 8 | `scenario-day2-materials` | Makes the day 2 materials: recap and skeleton slides, placemat 2 for each table, facilitator packs and read-aloud descriptions. |
| 9 | `scenarios-vision-writeup` | Writes the guided visualisation script, and after the workshop writes up the scenarios, lessons, shared vision and priorities. |

Skills 4 to 7 are the work between the two days. They share one small program, `morph.py`, and one workshop data file.

## How to use them

1. Download the nine zip files from the [`dist`](dist) folder. Do not unzip them.
2. Add each one to Claude as a skill. Anthropic's help page *Use skills in Claude* gives the current steps: <https://support.claude.com/en/articles/12512180-use-skills-in-claude>
3. Start a conversation, attach what you have, and say what you need in ordinary words. For example: "We are planning a foresight workshop on public transport on 9 and 10 March. Please help us set it up." Claude chooses the skill.
4. To see what each skill tells Claude to do, unzip a copy and read its `SKILL.md`. Each zip is a plain folder: `SKILL.md`, a `references` folder of guides, and the programs in `scripts`. Nothing is hidden.

## The example file and the illustrations

Every skill carries `assets/example/example.workshop.json`. It is a made-up workshop file, complete at every stage. Its wording is placeholder text that says what belongs in each field, and its ratings are made up so that the programs have something to run on.

The short illustrations in the guides are about public transport in a made-up country called Northland. They are invented to show the reasoning. No material from any workshop we have run for a client is in this repository.

The host and partner logo files in `assets/brand` are placeholders. Replace them with your own organisation's logos. `references/brand.md` in each skill explains how.

## What to know before you rely on them

- This is version 1.0. The skills write down a workshop format we run ourselves. No other team has run a live workshop with them yet.
- The programs are tested from the zip files, on the made-up example and on a larger made-up workshop with six uncertainties and 1,296 combinations. All 77 checks pass.
- The skills prepare drafts and show their reasoning. The ratings, the choice of skeletons and the wording of end states stay with the facilitation team.
- The slide deck is not included. The materials skill gives its outline, section by section, and the placemats are built by a program in the same skill.
- We wrote the skills with Claude's help and checked them against our own practice and the published work on each step.

## Where the method comes from

The workshop design and the way the steps fit together are Ariella Helfgott's and SA Futures Agency's. The format descends from the regional scenarios program of the CGIAR research program on Climate Change, Agriculture and Food Security, where Ariella Helfgott, Joost Vervoort and colleagues developed it with partners in East and West Africa, South and Southeast Asia and Latin America. The step that chooses a small, diverse set of scenarios follows Lord, Helfgott and Vervoort (2016), "Choosing diverse sets of plausible scenarios in multidimensional exploratory futures techniques", *Futures* 77.

The method also stands on many other people's work, and the skills name it. `references/method-background.md` in skills 4 to 7 gives the sources for the between-the-days steps: morphological analysis and cross-consistency assessment, consistency analysis and cross-impact balance, field anomaly relaxation, and the wider research on choosing scenario sets.

## How to credit and cite

These skills are shared freely, and the work in them remains Ariella Helfgott's and SA Futures Agency's. If you use the skills, or the method they carry, please do three things.

1. Keep the credit line on what you make: **Foresight method and materials: SA Futures Agency**. The skills put it in the footer of slides, placemats and packs.
2. In a report or paper, add an acknowledgement and cite:

   > Helfgott, A. and Adameitis, S. (2026). *SAFA Foresight Skills* (version 1.0). SA Futures Agency. https://github.com/djariella/safa-foresight-skills

   GitHub's "Cite this repository" button gives the same reference in other formats.
3. Tell us. Open an issue called "Used in ..." and say where and how it went. We would like to know, and it helps the next team.

## Licence

Copyright 2026 Ariella Helfgott and SA Futures Agency.

- The text, guides, templates and example data are licensed under [Creative Commons Attribution 4.0 International](LICENSE-docs.md). You may share and adapt them for any purpose, as long as you give credit.
- The programs are licensed under the [Apache License 2.0](LICENSE). Keep the copyright and [NOTICE](NOTICE) with any copy or adaptation.
- The SA Futures Agency name, logo and illustrations are ours. Use them to give credit and in materials made with these skills. Please do not use them in a way that suggests we ran or endorsed your workshop.

## Feedback

We want to hear what does not work. Open an [issue](../../issues) and tell us:

- where a step or an instruction was unclear
- where a program failed, with the message it gave
- where the method did not fit your country, topic or group, and what you changed
- what you would add

[CONTRIBUTING.md](CONTRIBUTING.md) says how to propose a change.
