# DST vs PES vs EXP: Which Embroidery File Format Do You Actually Need?

*Disclosure: the author is on the 5Bucks Digitizing team, writing about our own free tools and $5.99 digitizing service. This guide is meant to save you a ruined sew-out, not to sell you anything — every checking tool mentioned below is free and needs no account.*

If you have ever downloaded an embroidery design, unzipped it, and stared at a folder full of three-letter extensions wondering which one your machine wants, you are not alone. The **DST file**, the **PES file**, and the **EXP format** cause more beginner confusion — and more ruined garments — than almost anything else in machine embroidery. Pick the wrong one and your machine either refuses to read it or, worse, sews garbage.

This guide explains what each format actually is, which machines use which, how to convert between them, and how to preview any of them free in your browser before you stitch a single thread.

## The short answer

- **Tajima DST (.dst)** — the commercial-industry standard. If you run a Tajima, Barudan, SWF, or most multi-needle commercial machines, DST is your format. Almost every professional **embroidery digitizing service** delivers DST by default.
- **Brother PES (.pes)** — the home-machine standard. If you sew on a Brother, Babylock, or Bernina Deco machine, you need PES. It carries thread-color information that DST famously drops.
- **Melco EXP (.exp)** — the Melco/Bernina commercial format. Common on Melco machines and older Bernina commercial setups; also widely used as an exchange format because it preserves more data than DST.

When in doubt: **commercial machine → DST; Brother/Babylock home machine → PES; Melco machine → EXP.** And always keep a copy of whatever the digitizer originally sent you.

## What is a DST file? (Tajima DST explained)

The **DST file** (Tajima DST, extension `.dst`) dates back to Tajima's 1980s punched-tape systems, and it has survived as the lingua franca of commercial embroidery for one reason: everything reads it. Every commercial machine, every digitizing program, every service bureau speaks DST.

Technically, a DST file is a pure stitch file — a list of needle penetrations, jumps, trims, and color *changes* (not color names). That last detail matters. DST records "stop and change thread here" but **not which color to change to**. Your machine's screen will show generic color blocks, and you assign the real thread colors at the machine. Professionals handle this with a printed color sheet or run sheet that accompanies the DST.

Strengths of Tajima DST:

- Universally compatible with commercial machines and software
- Compact and robust — decades of tooling understand it
- The default delivery format of nearly every digitizing service, including ours at [5BucksDigitizing](https://5bucksdigitizing.com/)

Weaknesses:

- No embedded thread colors — you need the color sheet
- No design metadata, no object data — it is stitches only, so editing means re-digitizing, not tweaking
- Stitch-level scaling beyond ~10% degrades quality (density changes with size)

## What is a PES file? (Brother PES explained)

The **PES file** (Brother PES, extension `.pes`) is the native format for Brother and Babylock home embroidery machines, plus Bernina's Deco line. Unlike DST, a PES file stores actual thread color information, design size, and hoop positioning data — which is why home embroiderers generally have an easier time: what you preview is much closer to what you sew.

Versions matter with PES. Brother has revised the format several times (versions 1 through 11+), and older machines cannot always read files written for newer versions. If your Brother machine says "file unreadable" for a PES that previews fine on your computer, version mismatch is suspect number one — ask your digitizer to save down to an older PES version.

Strengths of Brother PES:

- Embedded thread colors and design metadata
- Deep support across home digitizing software (PE-Design, Embrilliance, SewWhat-Pro, Ink/Stitch)
- Easy to preview, resize slightly, and reposition

Weaknesses:

- Useless on commercial machines — a Tajima will not read PES
- Newer PES versions break compatibility with older Brother machines
- Like DST, it is still a stitch file, not editable object data

## What is the EXP format? (Melco EXP explained)

The **EXP format** (Melco EXP, extension `.exp`) is the native stitch format of Melco commercial machines and is also accepted by Bernina commercial systems. It sits somewhere between DST and PES in capability: it carries stitch data plus color-stop information in a form Melco machines understand natively.

EXP shows up a lot in professional workflows even for non-Melco shops, because several digitizing programs (notably Wilcom and Hatch) use EXP-family files as intermediates that preserve color sequencing better than DST. If a digitizer sends you "DST + EXP," the EXP is often the one with the more faithful color stops.

Strengths of EXP format:

- Native to Melco machines; good color-stop fidelity
- Common exchange format in Wilcom/Hatch professional workflows
- More widely readable than most people expect

Weaknesses:

- Not a home-machine format — your Brother cannot use it
- Multiple EXP variants exist (Melco vs. Bernina ART-derived), so confirm with your machine manual
- Same stitch-file editing limits as DST and PES

## DST vs PES vs EXP: side-by-side comparison

| Feature | DST (Tajima) | PES (Brother) | EXP (Melco) |
|---|---|---|---|
| Machine family | Commercial multi-needle | Brother/Babylock/Bernina Deco home | Melco, Bernina commercial |
| Thread colors embedded | No (color changes only) | Yes | Color stops |
| Design metadata | Minimal | Yes (size, hoop) | Partial |
| Industry role | Default pro delivery | Default home delivery | Pro exchange / Melco native |
| Editable objects | No | No | No |
| Free browser preview | [Yes — viewer](https://5bucksdigitizing.com/tools/embroidery-viewer/) | [Yes — viewer](https://5bucksdigitizing.com/tools/embroidery-viewer/) | [Yes — viewer](https://5bucksdigitizing.com/tools/embroidery-viewer/) |

The practical rule: **use the native format of your machine, and treat conversions as a necessary evil, not a routine step.** Every conversion between stitch formats is lossy in some small way — colors remap, trims shift, metadata drops. Convert only when you must.

## How to convert between DST, PES, and EXP

Common real-world conversions:

1. **Digitizer sent DST, but your Brother needs PES.** This is the single most common conversion in home embroidery. You need software that reads DST and writes the correct PES version for your machine.
2. **You own PES designs, but your new commercial machine needs DST.** Expect to lose embedded color names; keep a color chart and reassign threads at the machine.
3. **EXP to DST or back** inside a Melco/Wilcom workflow — usually the cleanest conversion of the three, since both are commercial stitch formats.

Free and paid conversion routes:

- **Free browser tools first.** Before installing anything, [preview your file in the free embroidery viewer](https://5bucksdigitizing.com/tools/embroidery-viewer/) to confirm what you actually have — extension lies happen (a renamed file with the wrong extension is a classic failure).
- **Format converter walkthroughs.** Our [embroidery converter guide](https://5bucksdigitizing.com/tools/embroidery-converter/) walks through DST ↔ PES ↔ EXP conversion step by step, including the PES-version gotcha above.
- **Desktop software** (Embrilliance Essentials, SewWhat-Pro, Wilcom Truesizer, Ink/Stitch) for batch or version-specific conversion.
- **Ask your digitizer.** Any decent service will re-export another format for free or cheap — we do it routinely for our [$5.99 digitizing orders](https://5bucksdigitizing.com/).

Never "convert" by renaming the extension. A `.dst` renamed to `.pes` is still a DST inside, and your machine will reject it or mis-sew it.

## How to check any embroidery file free before you sew

The cheapest ruined garment is the one you never sew. Before every sew-out:

1. **Preview the design** in the [free online embroidery viewer](https://5bucksdigitizing.com/tools/embroidery-viewer/) — check size, stitch count, color blocks, and overall shape. No install, no signup.
2. **Confirm the format matches your machine** (DST for commercial, PES for Brother/Babylock, EXP for Melco).
3. **Check the stitch count against the design size** — absurdly high counts on small designs signal density problems (more on this in our guide to [5 embroidery file mistakes that ruin sew-outs](https://github.com/deggimatt/5bucksdigitizing-tools/blob/main/blog/embroidery-file-mistakes.md)).
4. **Sew a test on scrap** with the same fabric + stabilizer combo.

## When the file itself is the problem

Sometimes the format is right but the digitizing is wrong: birdnesting, gaps, bulletproof patches of thread. That is usually not a format issue at all — it is a digitizing-quality issue. Our honest comparison of [auto digitizing vs professional hand digitizing](https://github.com/deggimatt/5bucksdigitizing-tools/blob/main/blog/auto-digitizing-vs-hand-digitizing.md) shows sew-out tests of both so you can tell which one your design needs, and our [mistakes checklist](https://github.com/deggimatt/5bucksdigitizing-tools/blob/main/blog/embroidery-file-mistakes.md) covers the five file defects that wreck sew-outs regardless of format.

## FAQ

**Can I use a DST file on a Brother machine?** Not directly — convert DST to the right PES version first, then verify the PES in a preview before sewing.

**Why does my DST show wrong colors on screen?** Normal. DST stores color *changes*, not color names. Follow the digitizer's color sheet when threading.

**PES version: which one do I need?** Check your machine manual for the newest PES version it reads; when ordering digitizing, tell the digitizer your machine model so they export correctly.

**Is EXP better than DST?** Neither is "better" — they are native to different machines. Use whichever your machine reads natively.

---

*About the author: this post was written by a member of the 5Bucks Digitizing team. We run [5BucksDigitizing.com](https://5bucksdigitizing.com/) — professional hand digitizing from $5.99, based in Nashua, NH — plus free tools including the [online embroidery viewer](https://5bucksdigitizing.com/tools/embroidery-viewer/) and [format converter guide](https://5bucksdigitizing.com/tools/embroidery-converter/). When auto tools are not enough, [order digitizing here](https://5bucksdigitizing.com/).*
