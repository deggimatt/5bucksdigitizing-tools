# 5 Embroidery File Mistakes That Ruin Sew-Outs (and How to Check Free)

*Disclosure: the author is on the 5Bucks Digitizing team — we sell $5.99 hand digitizing, and we give away the checking tools below for free with no account. Use them on anyone's files, including competitors'. A clean sew-out matters more than where the file came from.*

Most "bad luck" sew-outs are not bad luck. They are one of five predictable **embroidery file mistakes**, and every one of them is visible *before* you load the hoop — if you know where to look. Below: the five killers, what causes each, and a free check for every one. Total prevention cost: about ten minutes and zero dollars.

## Mistake 1: Wrong stitch density (the bulletproof patch and the gappy mess)

**Stitch count** that is too high for the design size produces the infamous bulletproof patch: a stiff, puckered slab of thread that warps the garment, breaks needles, and feels like cardboard. Too low, and you get gappy coverage with fabric grinning through.

Rules of thumb:

- Standard tatami fill runs roughly 4–5 stitches per mm of density (about 0.4 mm spacing). Much denser on medium fabrics causes puckering and thread breaks.
- Small designs need *relatively lower* density, not higher — a classic beginner error is cranking density up on a 2-inch logo.
- **Stitch count** should scale sensibly with area: a 4×4-inch filled design at normal density lands in the tens of thousands of stitches. If your viewer shows 60,000 stitches for a 2-inch patch, something is wrong.

**Free check:** open the file in the [free embroidery viewer](https://5bucksdigitizing.com/tools/embroidery-viewer/) and read the stitch count against the design dimensions. Absurd count-to-size ratios mean density problems. Compare with the format basics in our [DST vs PES vs EXP guide](https://github.com/deggimatt/5bucksdigitizing-tools/blob/main/blog/dst-vs-pes-vs-exp.md) — wrong-format conversions sometimes duplicate or corrupt density data.

## Mistake 2: Satin stitch vs tatami in the wrong places

**Satin stitch vs tatami** is the most consequential stitch-type decision in digitizing, and auto-digitized files get it wrong constantly:

- **Satin stitch** (zigzag columns) is for narrow elements: lettering, borders, columns up to ~7–10 mm wide. Wider than that, satin snags, loops, and wears badly.
- **Tatami** (filled rows, also called fill stitch) is for broad regions: backgrounds, large shapes, wide areas. Using tatami for 3 mm lettering gives mushy, illegible text.

The mistake in both directions:

- Wide satin columns (>10 mm) that catch, pull, and unravel — the file needed tatami with a proper pattern.
- Tiny tatami-filled text that fills in solid — the file needed satin or a redraw at stitchable size.
- No split strategy: professional files split wide satins or convert them to tatami with satin borders.

**Free check:** preview the design large in the [embroidery viewer](https://5bucksdigitizing.com/tools/embroidery-viewer/) and eyeball every region wider than a fingertip — if it is rendered as one unbroken satin sheen, be suspicious. If small text looks blobby in preview, it will sew worse than it looks. When the whole file is suspect, compare against our [auto vs hand digitizing sew-out comparison](https://github.com/deggimatt/5bucksdigitizing-tools/blob/main/blog/auto-digitizing-vs-hand-digitizing.md) — stitch-type misuse is the signature defect of auto-digitized files.

## Mistake 3: Missing (or wrong) underlay and pull compensation

Underlay is the foundation stitching laid down before the visible top layer. It stabilizes the fabric, lifts the top stitches for coverage, and anchors edges. Pull compensation is extra width added to counteract thread tension pulling edges inward. Skip either and you get:

- Gapping edges on knits and stretch fabrics
- Registration failures: outlines that no longer meet their fills
- Thin, sunken coverage that looks starved

This mistake is invisible in a flat preview and devastating on real fabric — which is exactly why it survives until sew-out. Auto-digitized files are the worst offenders: most apply one generic underlay (or none) regardless of fabric.

**Free check (two parts):**

1. Ask what fabric the file was digitized for. A file digitized "generically" with no fabric target is a red flag on knits, performance wear, towels, and fleece.
2. Test-sew on the *actual* fabric + stabilizer combo — never on a different scrap and assume transfer. If edges gap or outlines drift, the file needs underlay/pull-compensation work, which means professional re-digitizing ([from $5.99 here](https://5bucksdigitizing.com/)).

## Mistake 4: Chaos sequencing — jumps, trims, and color order

Every jump stitch is a thread tail waiting to snag; every unnecessary trim is machine time and a cut-thread risk; every bad color sequence multiplies both. Symptoms of chaos sequencing:

- Long jump threads spanning the design (should have been trimmed or sequenced away)
- Machine trimming dozens of times on a simple design
- Same-color regions sewn in separated passes instead of one continuous path
- Start/end points stranded in the middle of fills

Hand digitizers engineer the sew path: grouping same colors, minimizing travel, placing jumps where trims clean them. Auto tools typically sew region-by-region in image order — maximally inefficient.

**Free check:** in the [embroidery viewer](https://5bucksdigitizing.com/tools/embroidery-viewer/), step through or inspect the color-block sequence. Dozens of blocks for a 3-color design, or same colors scattered across many separated blocks, means bad sequencing. Also confirm you are viewing the right format for your machine — sequencing data can degrade across conversions (see [DST vs PES vs EXP](https://github.com/deggimatt/5bucksdigitizing-tools/blob/main/blog/dst-vs-pes-vs-exp.md)).

## Mistake 5: 3D puff digitizing done like flat digitizing

**3D puff digitizing** (raised foam embroidery, usually caps and jackets) fails more often than any other specialty — because flat files get run on foam with zero adaptation. Real puff files require:

- Widened satin columns (foam needs wider coverage than flat thread)
- Higher density to grip and cut the foam cleanly
- Open column ends so excess foam tears away
- Correct sequencing: foam placed, sewn over immediately, trimmed promptly
- Lettering designed for puff from the start — ordinary small text does not puff

A flat file sewn on foam gives: foam poking through stitches, torn columns, shredded edges, and caps that look chewed. If someone offers to "just run your regular logo on foam," decline.

**Free check:** look at the file's satin widths in the [viewer](https://5bucksdigitizing.com/tools/embroidery-viewer/) — puff columns should read visibly wider than their flat equivalents, with clean open ends. No widening = not a puff file. Puff is hand-digitizer territory exclusively (see our [auto vs hand comparison](https://github.com/deggimatt/5bucksdigitizing-tools/blob/main/blog/auto-digitizing-vs-hand-digitizing.md)); if you need it, [order puff-capable digitizing](https://5bucksdigitizing.com/) and say "3D puff on caps" explicitly.

## The 10-minute free pre-sew checklist

Run this on *every* file, from any source, before it touches a garment:

1. [ ] Open in the [free embroidery viewer](https://5bucksdigitizing.com/tools/embroidery-viewer/) — confirm design, size, stitch count, color blocks
2. [ ] Stitch count sane for the size? (Mistake 1)
3. [ ] Wide areas tatami, narrow elements satin? (Mistake 2 — [satin stitch vs tatami](https://5bucksdigitizing.com/tools/))
4. [ ] File built for your actual fabric? Underlay adequate? (Mistake 3)
5. [ ] Color blocks efficient, jumps minimal? (Mistake 4)
6. [ ] Format matches your machine — DST commercial, PES Brother, EXP Melco? ([format guide](https://5bucksdigitizing.com/tools/embroidery-converter/))
7. [ ] Puff jobs: widened columns, open ends? (Mistake 5)
8. [ ] Test-sew on identical fabric + stabilizer scrap

Files that fail checks 1–6 from an auto tool can often be replaced in seconds via the [free auto-digitizer](https://5bucksdigitizing.com/tools/auto-digitizer/) with better settings — or escalated to hand digitizing when the design genuinely needs it.

## FAQ

**What stitch count is normal?** It scales with filled area and density, not design "complexity." Be suspicious of counts wildly out of proportion to size in either direction — verify in the [viewer](https://5bucksdigitizing.com/tools/embroidery-viewer/).

**Satin or tatami for text?** Satin for normal lettering; tiny text may need simplified satin or redraw; large display letters get tatami fill with satin borders.

**Why does foam show through my puff?** Density too low, columns too narrow, or ends closed — the file was not digitized for puff. Needs a proper [3D puff digitizing](https://5bucksdigitizing.com/) job.

**Can I fix a bad file myself?** Stitch files (DST/PES/EXP) carry no editable objects — real fixes mean re-digitizing, not tweaking. Minor issues (format, version) are convertible via the [converter guide](https://5bucksdigitizing.com/tools/embroidery-converter/); structural issues need a new file.

---

*About the author: written by a member of the 5Bucks Digitizing team. We run [5BucksDigitizing.com](https://5bucksdigitizing.com/) — pro hand digitizing from $5.99, Nashua, NH — with free tools: [embroidery viewer](https://5bucksdigitizing.com/tools/embroidery-viewer/), [converter guide](https://5bucksdigitizing.com/tools/embroidery-converter/), and [auto-digitizer](https://5bucksdigitizing.com/tools/auto-digitizer/). Check free, sew confident.*
