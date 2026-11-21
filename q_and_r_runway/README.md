# Q&R Runway — PPNN

A deliberately small working space for the **Quick & Reckless (Q&R)** approach to Paper–Pencil Neural Networks (PPNN). This directory records the metaphors and preserves pointers to the original evidence. It is **not** a prerequisite for running the first one-neuron network.

## The runway comparison

**Source:** *NOVA*, “Top Gun over Moscow” (1996), documentary episode. Reference copy: [YouTube, full video](https://youtu.be/HBT_GzR3P84); [start of the relevant segment, 8:11](https://youtu.be/HBT_GzR3P84?t=491). The intended stopping point is **9:48 (588 seconds)**; the cited interval is **8:11–9:48**. The segment contrasts U.S. airfield foreign-object-damage (FOD) sweeps with Russian airfields and aircraft engineered to tolerate rougher operating conditions, including protected engine intakes. The screenshots provided by the project author document this comparison; the original video is **linked, not redistributed**.

**PPNN analogy:** Don't keep gold-plating the runway's lane markers when the goal is to fly. Equally important: build the small aircraft so it can operate without a perfect runway. The analogy is about choosing the right degree and location of engineering, **not** rejecting safety or correctness.

## Two valid ways to get airborne

The metaphor works in either direction:

- **American approach:** Clean the runway so the aircraft doesn't need elaborate intake protection.
- **Russian approach:** Engineer the aircraft to tolerate a dirty runway.
- **PPNN approach:** Choose whichever requires less work to achieve a successful takeoff.

The trap is simultaneously building titanium intake grates, conducting meticulous FOD sweeps, and gold-plating the runway markings—all before the first flight.

**Don't minimize the complexity of an individual component. Minimize the complexity of the entire system needed to accomplish the objective.**

That's a particularly good expression of Quick & Reckless: not careless, not necessarily crude, but *appropriately sufficient*.

For PPNN, the objective is still beautifully modest: **one neuron, one genuine learning update, performed by hand.**

## Quick & Reckless (Q&R)

The author learned the phrase **Quick & Reckless** at The OCD and Anxiety Treatment Center (TOATC), in an outpatient program. Here it is a practical antidote to over-preparation: make a sufficiently safe, reversible, inspectable attempt rather than continually preparing for one. Q&R does **not** mean skipping mathematical checks, risking harm, or treating mistakes as correct.

Related metaphors from the author's discussions:

- **Crop-dusting plane versus lunar lander (LEM):** Trying to land on the Moon with a crop-dusting plane means underengineering a genuinely hard task; trying to crop-dust with the LEM means bringing full formal machinery to a problem where controlled approximations suffice. The author's undergraduate physics advisor and a mathematics professor ultimately supplied complementary perspectives. Choose a tool appropriate to the task.
- **Lean-to versus cathedral:** Build the smallest shelter that actually works before expanding it into an architectural monument. Keep the cathedral ideas in the archive, not on the critical path.
- **Take off versus improve the runway:** One verified forward pass and genuine parameter update are more valuable now than another polished diagram set.
- **Trunk versus branches:** Keep the main learning path short and working; branch into pedagogy, printable artwork, formal derivations, information theory, and energy arguments when the trunk can support them.

## Immediate PPNN trunk

1. One input, one neuron, one weight, optional explicit bias, identity activation.
2. One tiny target task (initially a constant output of 3).
3. One manually performed forward pass, loss, backpropagation, and parameter update.
4. Check the human arithmetic without replacing the human computation.
5. Repeat only enough to observe what happens; add complexity when the task requires it.

## Source and artifact staging

- The four original handwritten PPNN notebooks span February–October 2024; preserve their original exports unchanged.
- Earlier digital PPNN diagram files are documented in Google Drive as of August 27–28, 2023.
- Laminated sheets photographed in the parents' living room were discussed April 2, 2026. Proposed asset names: `room_full_01.jpg`, `room_full_02.jpg`, `room_full_03.jpg`, and `labeled_run_01.jpg`. These are **not yet verified as files in this directory**; April 2 is the discussion date, not a verified camera capture date.
- Further notes, original photos, and source-file provenance will be added separately after review. No unverified photos or downloaded YouTube video are included here.

## Repository workflow

This directory starts in `bballdave025/double-p-double-n` as a proposed PR. A separate ZIP with root directory `q_and_r_runway/` is prepared for **possible later** placement in `gtgtdd-sys`; do not treat the ZIP as already committed there.
