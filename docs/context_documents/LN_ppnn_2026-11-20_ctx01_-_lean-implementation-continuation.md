*BEGIN: Context Document Header*

# CONTEXT DOCUMENT — Continuation

## Project

**Name:** Paper–Pencil Neural Networks (PPNN)

**Description:** A hands-on, manually executable neural-network learning system made from handwritten Kindle Scribe notebooks, laminated paper diagrams, reusable connectors, and editable SVG symbols. Learners write and calculate input values, weights, biases, pre-activations, activations, predictions, signed errors, losses, and aggregate cost by hand.

---

## Continuation Metadata

**Prepared at:** 2026-11-20 (America/Denver; MST, UTC−07:00; exact preparation time not recorded in this document)

**Continued from chat:** `Lean_PPNN_Implementation`

**Short project marker:** `ppnn`

**Repository:** [bballdave025/double-p-double-n](https://github.com/bballdave025/double-p-double-n)

**Working documentation branch:** `docs/ppnn-context-documents-readme`

**Also involving:** Kindle Scribe source notebooks; laminated physical teaching sheets; Google Drive diagram catalog; mathematical notation and backpropagation; Quick & Reckless (Q&R) development discipline.

---

## Author / Source

**User (GitHub):** @bballdave025

**Source basis:** Conversation `Lean_PPNN_Implementation`, user-shared photographs and screenshots, and repository documentation on the named branch. This document records decisions made during the chat; it does **not** claim a new page-by-page verification of all Kindle notebooks or an exhaustive audit of Drive contents.

---

## Intent for This Context

Resume the PPNN work in a fresh chat without reconstructing approved symbol geometry, mathematical conventions, provenance, repository state, or immediate priorities. Preserve the user's preference to learn and execute computations manually rather than having the assistant solve them in advance.

---

## Usage Instructions

- Treat **confirmed decisions** below as the current working design.
- Distinguish **original artifacts**, **approved SVG reconstructions**, **README-specific draft illustrations**, and **proposed future components**.
- Do not silently redesign approved symbols, upload unapproved materials, or assume public access to the Drive folder.
- Continue with minimal re-derivation, but inspect originals when exact handwriting, dates, geometry, or page-specific claims matter.
- The user prefers direct, practical collaboration and restrained humor; do not turn this into a cathedral-building exercise.

*ENDOF: Context Document Header*

---

# 1. Project identity and educational purpose

PPNN = **Paper–Pencil Neural Networks** (repository `double-p-double-n`). The project is both autodidactic and pedagogical: learn the computational internals of small neural networks by writing values and performing operations by hand. Its physical interface includes laminated sheets with designated writable areas and wet-erase markers. The first activation functions may be identity functions; later examples can expose nonlinear activations and backpropagation. Do **not** automatically calculate examples for the user: the point is for the learner to do the math, with the assistant checking or guiding when asked.

A key distinction is **conventional architecture drawing vs. physical working diagram**. A compact 3–4–2–1 network shows circles and edges without a forest of weight boxes; the laminated detailed sheets reveal the weights and operations. The user particularly likes this progression because abstraction becomes apparent through the materials rather than through an abstract lecture.

Development philosophy: **Quick & Reckless (Q&R)**, learned at The OCD and Anxiety Treatment Center, adapted as a project heuristic. The user contrasts a *lean-to* with a *cathedral*, and *taking off* with continually polishing the *runway*. Another analogy is trying to crop-dust with a lunar module versus landing on the Moon in a crop-dusting plane: match the apparatus to the actual task. Distinguish **trunk** (getting a small example working) from **branches** (interesting diversions). Preserve the useful work, but avoid polishing infrastructure indefinitely.

The runway metaphor came from *NOVA: Top Gun over Moscow* (1996), a documentary comparison of meticulously cleaned US airfields and Russian aircraft designed to tolerate rougher operating conditions. The discussed YouTube segment was **8:11–9:48** (491–588 seconds); reference video: https://youtu.be/HBT_GzR3P84?t=491 . This analogy is motivational, not a claim that careless physical safety procedures are desirable.

# 2. Repositories, branches, documentation, and access

- **PPNN repository:** https://github.com/bballdave025/double-p-double-n
- **Current documentation branch:** https://github.com/bballdave025/double-p-double-n/tree/docs/ppnn-context-documents-readme
- **Root README on branch:** https://github.com/bballdave025/double-p-double-n/blob/docs/ppnn-context-documents-readme/README.md
- **Context-document README:** `docs/context_documents/README.md` on the same branch.
- **Main PPNN Drive folder (restricted access):** https://drive.google.com/drive/folders/1vgHwM8zisOm1rzsQir6JARGiPAV9ngKV
- Another previously discussed PPNN preparation Drive folder: https://drive.google.com/drive/folders/11wt2eINq13FlepakBAJl9QacPYOXoJco
- **Context-template source:** https://github.com/bballdave025/dwb-ip-notes/blob/main/auxiliaries/template_ctx_doc_README.md

The documentation branch contains a newly instantiated `docs/context_documents/README.md`, a substantially expanded root README, and **three README-specific white-backed draft architecture SVGs** under `docs/images/`. These illustrations were introduced to render reliably on GitHub in light and dark modes; the user has noted some wrinkles and intends to revisit them. **Do not mistake these README-specific drafts for final approved canonical artwork.**

The Drive folder contains original materials and approved transparent SVG exports. Its access is currently limited to the user and spouse, so public README links must explicitly say *restricted access*. Preserve original filenames and source provenance. There is no requirement to publish the private original materials yet.

The original `dwb-ip-notes` template contained a hard-coded “Boston, MA time” note. The PPNN-specific context README uses **the author's current local time zone with a numeric UTC offset**, not a fixed Boston or Utah timezone. A corrected standalone template file was prepared for download; **no change to `dwb-ip-notes` was committed** because the user needs to merge other PRs and check conflicts.

# 3. Kindle Scribe and physical-source provenance

Four original Kindle Scribe notebook exports were discussed:

1. `Main_Paper_Pencil_Neural_Network_Notebook_01`: notes from approximately Feb 25–May 19, 2024.
2. `Main_Paper_Pencil_Neural_Network_Notebook_02`: approximately May 19–June 29, 2024.
3. `Main_Paper_Pencil_Neural_Network_03`: approximately June 29–July 14, 2024.
4. `Main_Paper_Pencil_Neural_Network_part_4`: approximately Oct 6–7, 2024.

These dates and descriptions come from earlier examination in the conversation and should be rechecked against the originals for scholarly or provenance-sensitive claims. **Handwritten diagrams must be inspected visually**: Kindle handwriting-to-text conversion does not reliably preserve spatial relationships, shapes, or mathematical figures.

Earlier Drive photographs with filenames such as `b_w_1_long_start__20230827-0910.jpg` and `b_w_3_to_4__20230827-0901.jpg` indicate PPNN physical/diagram work existed by Aug 27, 2023. The notebook is not necessarily the earliest project artifact.

A handwritten note in Part 3, page 23 (cumulative page 72), was previously interpreted as enumerating three physical networks: one-input/one-neuron, two-input/one-neuron, and 3–4–2–1. It also mentioned an early physical one-neuron drawing mistakenly containing two neurons. **Verify against the original page before quoting this as definitive transcription.** Earlier discussion also pointed to Part 1 pages 8–11 for expanding a neuron to show internal computation, and Part 2 pages 8–16 for dense-network weight-layout experiments; these page references likewise warrant direct inspection before publication.

Recent user photos show the physical sheets arranged in sequences: input/weight calculations, pre-activation and activation calculations, final prediction and target, signed difference, and cost. The user has several connector cards/strips, including long thin angled laminated pieces, and plans additional sheets for a vertical vector of perhaps four or five losses and a separate small sheet for the cost `J`. Some physical sheets were photographed at the user's parents' home. Do not infer exact photo creation dates without metadata or originals.

# 4. Canonical visual vocabulary (confirmed)

The user has approved these distinct *empty* symbols for the reusable visual alphabet:

| Component | Geometry and meaning |
| --- | --- |
| Input | Empty rounded rectangle / truncated-circle outline. Input values are **not neurons**. |
| Weight | Empty rectangle with a horizontal connecting line entering from the left and exiting right; lines stop at the rectangle boundary, not through its interior. |
| Bias | Empty parameter rectangle with **one vertical line exiting its top midpoint**. This is the canonical bias symbol. |
| Neuron | Empty oval. A **circle** is the same computational kind of node in compact/high-level schematics. |
| Prediction | Empty parallelogram, a separate writable copy of the output neuron's activation in its role as `ŷ`. |
| Target/truth | Empty trapezoid (British usage often “trapezium”). Visually distinct from prediction. |
| Conceptual neuron engulfing bias | Oval neuron boundary with a small lower circular lobe enclosing a smaller bias rectangle; the internal line connects at the top midpoint of that rectangle. **Explanatory only**, not a replacement for the ordinary bias rectangle. |

The user deliberately chose empty canonical symbols instead of filling them with `x_i`, `w`, `a`, etc. Values and indices can be overlaid in teaching examples. The visual distinction between a parameter box and a neuron is meaningful: a bias is a trainable parameter, but without its own activation it is **not** a full neuron.

For the **output neuron → prediction** symbol, the approved geometry is an oval with an incoming line from the left and a diagonal line descending rightward from the oval's lower-right boundary to the **midpoint of the top edge** of a prediction parallelogram. This was iterated carefully. Keep its placement unless asked to revise it.

Colors of approved SVG exports:

- **Day mode:** stroke RGB (35,35,35), hex `#232323`.
- **Night mode:** stroke RGB (220,220,220), hex `#DCDCDC`.
- **Both:** transparent background. README-only display illustrations may instead have opaque white backgrounds for reliable GitHub dark-mode rendering.

Approved SVGs have been uploaded to the main PPNN Drive folder, including:

`input.svg`, `weight.svg`, `bias.svg`, `neuron.svg`, `neuron_engulfing_bias.svg`, their `_nightmode.svg` counterparts, `output_neuron_prediction.svg`, and `output_neuron_prediction_nightmode.svg`.

Do not assume every GitHub renderer displays Unicode glyphs identically: the Google Drive preview showed an unsupported-glyph box for the vertical ellipsis. A future compatibility improvement is to draw three vector dots rather than rely on a font. This is **parked**, not urgent.

# 5. Mathematical conventions and conceptual decisions

The user wants **standard ML notation and a parallel, structurally meaningful Einstein-index notation**, not a premature forced choice. Their preference is to reason about vector/covector directions, contractions, and layer-to-layer maps, rather than merely memorizing `W_ij`. The Einstein-style scheme has **not** been finalized.

- **Layer number** is a label, not a covariant or contravariant tensor index. The agreed diagram convention puts it in a subscript with parentheses: `a_{(L)}` for the final-layer activation, leaving superscript space for vector-component indices. Avoid reverting to `a^{(L)}` in diagrams intended to follow the PPNN-specific convention.
- **Pre-activation:** `z`, the affine weighted sum before applying a nonlinear activation.
- **Activation:** `a = g(z)`.
- **Weight map:** a linear transformation between vector spaces, represented by a matrix in chosen bases; adding bias makes the pre-activation map **affine**, not linear in the strict linear-algebra sense. Nonlinearity comes from `g` (unless `g` is linear/identity).
- **Bias:** an additive trainable parameter associated with the neuron; conceptually inside the neuron, even if drawn externally in canonical diagrams. It is not a constant of integration.
- **Signed prediction error / residual (PPNN convention):** `r = ŷ − y` (**predicted minus actual**). This order is useful because the derivative of `(1/2)(ŷ−y)^2` with respect to `ŷ` is directly `ŷ−y`. Classical statistical residuals are often defined as `y−ŷ`; ML literature is not universally consistent, so define the sign explicitly.
- **Loss:** lowercase script ell `ℓ` for a per-example loss and `ℓ_1, ℓ_2, …, ℓ_N` for a vector of individual losses.
- **Cost:** `J` for an aggregate cost function (typically scalar). A vector of `J` values only makes sense when something such as training iteration or batch varies.
- **Prediction shape** and final neuron may contain the **same numerical value** but have different roles: activation vs. `ŷ`.
- A trapezoid is called a trapezium in much British educational usage, including the *Numberblocks* context that prompted the discussion.

The PPNN pedagogical computation flow is:

```text
final neuron a_(L)
        ↘
      parallelogram ŷ  −  trapezoid y
                         → [cloud containing ℓ]
                         → [vertical vector ℓ₁, ℓ₂, ⋮, ℓ_N]
                         → [square J]
```

The cloud is an *algebra/loss computation cloud*, inspired by the user's playful “algebra clouds” with fight effects. The approved version keeps **ℓ inside the cloud**, with three consistent horizontal arrows (target → cloud, cloud → loss vector, loss vector → cost), and gaps at both ends. The `ŷ` parallelogram and target trapezoid face one another with pleasing approximately matching side slopes, without needing exact parallelism.

The last approved files are `prediction_to_cost.svg` and `prediction_to_cost_nightmode.svg` in Drive. The Google Drive preview has a vertical-ellipsis glyph problem; the user explicitly deferred fixing it.

# 6. Network architectures and approved/reviewed diagrams

**One input → one neuron (1–1):** simplest intended manual network.

**Two inputs → one neuron (2–1):** independently weighted inputs converge on one neuron. User specifically requested that connecting lines **stop at weight rectangle boundaries** instead of passing through the rectangles. A later possible slope adjustment (smaller absolute slope) was discussed but explicitly deferred.

**Three inputs → four hidden → two hidden → one output (3–4–2–1):** high-level network diagram, with **no explicit weight rectangles**, intentionally providing a more abstract view. The user repeatedly expressed strong approval of this architecture drawing. The detailed physical working sheets reveal the weights.

For all three architectures, versions exist **with and without a prediction parallelogram**. The user approved a resized prediction parallelogram whose visual area is approximately that of one input node, and asked for those three revised `*_prediction.svg` files to be uploaded to Drive. Verified links:

- [network_1_1_prediction.svg](https://drive.google.com/file/d/1P2gcUBlRQLXQWAypfzwfk7VAheLOXMSN/view)
- [network_2_1_prediction.svg](https://drive.google.com/file/d/1ZIdb2vh-mIlQKb9R5RJZZIwieCikul_y/view)
- [network_3_4_2_1_prediction.svg](https://drive.google.com/file/d/1bXdwq5PwROH8A76LTLYNVKrywB1Yj0gI/view)

The three no-prediction SVGs were also created in the conversation, but do **not** assume they were uploaded to Drive unless independently verified.

**XOR:** The user wants to show a two-input network with a hidden layer, including an “everything-but-XOR” network and eventually XOR. The exact hidden-layer architecture, physical representation, and examples remain **to be supplied/confirmed**; do not invent or claim a finished XOR demonstration.

**Future extension:** append the target trapezoid, loss cloud, loss vector, and cost `J` to compact network diagrams. This is planned, not yet approved as a canonical set of combined SVGs.

# 7. Google Drive organization and catalog constraints

The user previously reorganized the Drive folder `My Drive/N/Neural_Network_-_Paper_and_Pencil`, creating:

- `Pre_Polishing_with_kamMA` for earlier subdirectories except `Screenshots_from_YouTube_Tutorials`;
- `useful_image_comparisons_with_kamMA` for selected immediate child image files, excluding PDFs and `img20250126_20360290.jpg`.

Those actions were discussed/executed earlier; **verify current Drive state before making further moves**. The current user wants to catalog input → first weights → first neuron laminated pages, distinguishing those with the first neuron's internal “guts” from sheets showing only a compact neuron indicator. Preserve original filenames and identify confirmed/plausible/unresolved matches separately. The user prefers a low-friction, non-destructive workflow and has explicitly rejected hyper-determined exhaustive searching when evidence is thin.

The user also discussed a separate workspace/site for cataloging the four notebook exports against Drive diagrams. Do not assume that workspace is the canonical source or that its records have been written to Drive.

# 8. README status and planned documentation improvements

The root README was expanded from a two-line description on branch `docs/ppnn-context-documents-readme`. It now explains the purpose, visual vocabulary, network variants, physical toolkit, restricted Drive assets, and current priorities. It includes three **white-backed README-specific draft architecture illustrations** in `docs/images/`. The user has reviewed the direction positively but said there are **wrinkles to iron out another night**. Do not silently “fix” those without user review.

`docs/context_documents/README.md` instantiates the template from `dwb-ip-notes`, with project marker `ppnn` and a portable local-time timestamp rule. This document is the first substantive continuation checkpoint under that directory.

The user plans to **review and merge a PR**; do not presume it has been merged. Work on the same branch unless told otherwise. The root README is a draft, not a final tutorial.

# 9. Immediate continuation plan

1. **First, let the user review this context document and the documentation branch/PR.** Apply requested corrections without re-deriving everything.
2. **Inspect forthcoming photographs** of the one-input/one-neuron physical net and the “everything-but-XOR” gate net. User intends to provide the 3–4–2–1 physical material **piece by piece**. Keep photograph provenance and distinguish user interpretation from inference.
3. **Catalog physical network parts** against the original Kindle notebooks and Drive assets. Inspect handwritten figures visually; do not rely solely on Kindle Scribe HTR.
4. **Review the three white-backed README-specific illustrations** for the known wrinkles, and eventually add reviewed SVGs to the repo with clear provenance and licensing/access decisions.
5. **Consider a 2-input hidden-layer XOR layout** only after reviewing the user's existing sheets and design intentions.
6. **Later:** build reusable physical connector/portrait loss-vector and cost sheets; consider a Tkinter visualizer, noting that Tkinter itself needs extra support to render SVG.
7. **Later:** formalize the parallel standard-ML / Einstein-index conventions, preserving the separation of vector-space structure, affine pre-activation, nonlinear activation, example indices, and layer labels.

# 10. Practical working style and pitfalls

- User wants to **do the calculations personally**; provide guidance/checks, not unsolicited full numeric solutions.
- Prefer clear diagrams, iterative small corrections, and **explicit visual approval before SVG finalization or Drive/GitHub upload**.
- Preserve established day/night colors, transparent backgrounds, and approved geometry.
- Be precise that **input nodes are not neurons**, and the conceptual engulfed-bias symbol is not the canonical bias symbol.
- Do not conflate **signed error**, **per-example loss**, and **aggregate cost**.
- Avoid turning the README into an exhaustive textbook before the first complete working example exists.
- If a new chat needs original handwritten source details, retrieve the original notebook pages or user photos instead of extrapolating from this checkpoint.
- No “Boston time” hard-coding. Use the author's current local time with explicit UTC offset.

---

*ENDOF: PPNN continuation context document*
