# Arif Setiawan

Product manager for **[Tetrate Agent Router](https://tetrate.io/agent-router-product)** — an
enterprise AI gateway for agents, models and MCP servers. I run the product loop end to end:
customer conversations, PRDs, through the build, validating features before they ship, and the
docs that go with them. I build as well as specify.

### [evals](https://github.com/arifsetiawan/evals)

Evaluations of how AI models do real work, and how they fail. Four suites across four models, with
negative controls, and the null results kept in rather than quietly deleted.

The finding that keeps repeating: the dangerous failures do not look like failures. A model that
answers a question it should have refused, or reports a fix its own tests contradict, passes every
check that asks "is this accurate?"

### Manaira Labs

**[Bicara.ai](https://bicara.ai)** — an ERP for Indonesian small businesses. Thirty modules, plus a
WhatsApp agent that answers stock, pricing and order questions from live business data rather than
templates, in Bahasa Indonesia.

**[bicara-skills](https://github.com/manairalabs/bicara-skills)** — Claude skills for Indonesian
business operations: invoice and faktur pajak extraction to structured JSON, with NPWP validation
and PPN/PPh handling.

**[id-locale](https://github.com/manairalabs/id-locale)** — Indonesian locale utilities on npm.
IDR formatting, NPWP/NIK validation, phone normalization, tax math, `terbilang`.

### Real-time avatar engine

An open reimplementation of a published architecture, targeting under 500 ms from speech to a
rendered face. The voice pipeline works; the rendering does not — the lip-sync model needs video
input rather than a single photo, which gives a mean pixel difference of 3.7 and effectively no
mouth movement. That only surfaced from building it and measuring.

### Before

Lead developer. MSc in computer vision, BSc in physics. Still in the code.

Bandung, Indonesia.
