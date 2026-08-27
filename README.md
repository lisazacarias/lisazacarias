## Lisa Zacarias

LCLS-II SRF Engineer/Physicist at SLAC National Accelerator Laboratory. I build and own the
production Python that operators use to run a superconducting linear accelerator.

**Most of my work lives in the [`slaclab`](https://github.com/slaclab) organization, not on this
profile** — the repositories here are mostly my forks of it.

- **[slaclab/sc_linac_physics](https://github.com/slaclab/sc_linac_physics)** — I created this project
  and author most of its commits. Operator displays, analysis tools, and CLI for the LCLS-II
  superconducting linac: 296 superconducting RF cavities today, expanding to 480. ~100 automated
  releases, and an 80% branch-coverage gate enforced on every pull request.
- **[slaclab/lcls-tools](https://github.com/slaclab/lcls-tools)** — SLAC's shared Python library for
  accelerator controls and data analysis. Top contributor of 15, over five years.
- **Auto setup** — hierarchical automation of RF cavity characterization, from a single cavity up to
  the whole machine. Replaced a multi-hour manual procedure with a 20-minute automated one;
  recognized with a SLAC Technology Excellence Award. Originally
  [slaclab/srf_auto_setup](https://github.com/slaclab/srf_auto_setup), since migrated into
  `sc_linac_physics` and substantially improved — it's still the tool operators use.

### Physics

First author on *Measuring Q₀ in LCLS-II Cryomodules Using Helium Liquid Level*
([SRF'23](https://doi.org/10.18429/JACoW-SRF2023-MOPMB090)) — a measurement method developed at
Jefferson Lab during cryomodule acceptance testing, then used in the tunnel at SLAC. Co-author on
three further SRF papers.

### Side projects

Built with Claude Code. I bring the requirements, the domain, and the testing; the implementation
is agent-written.

- **[candy-dance-case-study](https://github.com/lisazacarias/candy-dance-case-study)** — how the
  CAN.dy membership platform works and why: bylaws enforced as Postgres constraints, triggers and
  RLS policies, built in five days against a real deadline. Includes what the approach cost and a
  straight account of which decisions were mine and which were Claude's. Application source is
  private; this is the write-up.
- **[static-apps](https://github.com/lisazacarias/static-apps)** — a monorepo of small personal web
  apps ([live](https://lisazacarias.github.io/static-apps/)) under one constraint: no build step,
  no bundler, nothing from npm at runtime. A piano sight-reading trainer, an algae bloom tracker,
  and a Hayward election results tracker.

### Elsewhere

I mentor a summer intern every year (DOE SULI, SJSU SPARK, Foothill College) and have volunteered
with SAGE Camp — Science Accelerating Girls' Engagement in STEM — since 2020.
