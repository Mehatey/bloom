# Bloom ✻

**A meditation that listens.**

MFA Design + Technology thesis · Parsons School of Design · 2026
Friday May 15 + Saturday May 16, 2026 · Room 1205

→ **Live thesis deliverable:** [mehatey.github.io/bloom](https://mehatey.github.io/bloom/)
→ **Project page:** [siddharthmehta.design/mandalas](https://siddharthmehta.design/mandalas)

---

## What this is

A seated installation in three parts:

1. **The chair** — a 6-minute body-driven visual journey. A BrainBit EEG senses stillness. A Kinect notices the body. A 75-inch screen unfolds fifteen procedurally-generated scenes across nine chapters — nebulae, mandalas, sand, lightning, breath. Each scene is tuned to the visitor's nervous system in real time.

2. **The cork wall** — visitors write one thing on a card after sitting. *Something beautiful. Their happy place or person. Something they fear.* By Saturday night the wall is the show's analog memory.

3. **The altar** — a glass cube on a turntable, flanked by two two-way mirrors creating an infinity tunnel. A Vision Pro offers a ninety-second image-tracked coda for visitors who want to stay longer.

The piece opens with a satirical overstimulation collage — wellness ads, news, surveillance, the popup *"You" Are Not Enough · Install*. The audience watches Install get pressed. What they receive is Bloom — a wellness app that holds them.

---

## The thesis

> What is being sold to you as presence,
> and what is presence when nothing is being sold?

Bloom is both a meditation and a critique. It builds a real body-responsive contemplative experience while interrogating the wellness-app industrial complex that has commodified silence into a subscription.

The two taglines coexist intentionally:
- **be better everyday.** — the satirical commercial voice
- **who are you, to you?** — the genuine introspection

---

## Repository contents

```
/                       The live thesis deliverable
  index.html            ↳ main page (video-heavy scrollable)
  mandala/              ↳ 27 compressed video + image assets

print_kit/              All physical install + print files
  TOMORROW.html         ↳ strategic build plan
  installation_brief.html ↳ Room 1205 overhead map
  attendant_script.html ↳ show-night helper script
  show_runbook.html     ↳ Friday minute-by-minute
  
  placard_why.html      ↳ entry placard — the concept
  placard_how.html      ↳ entry placard — the walkthrough
  cork_wall_plaque.svg  ↳ engraved cork-wall plaque
  bloom_logo_*.svg      ↳ logo files for laser + print
  business_card.html    ↳ business cards
  thank_you_card.html   ↳ visitor takeaway
  what_just_happened.html ↳ post-meditation reveal card
  sticker_sheet.html    ↳ 24 overstim notification stickers
  red_filter_reveals.html ↳ duo-color critique sheets
  die_cut_overlay.html  ↳ "be here now" clear-film overlay
  wall_quote_vinyl.svg  ↳ "you have always been bloom." vinyl
  door_sign.html        ↳ "open" / "in session" door sign
  shopping_list.html    ↳ Blick + Staples checklist

  cd_engravings/        ↳ 20 unique transparent-CD mandalas
  cube_engravings/      ↳ 4 cube faces + 2 mirror engraves
  mandala_svgs/         ↳ 5 mandala line drawings
  book_pages/           ↳ 24-page bound artist book
```

---

## Technical stack

- **HTML5 Canvas + Three.js + WebGL** for the generative scenes
- **BrainBit EEG** for stillness / focus / alpha rhythm
- **Microsoft Kinect** for hand position / body lean / motion energy
- **Apple Vision Pro** with USDZ assets + WebSocket word bridge for the coda
- **Python WebSocket bridges** for the BrainBit + Kinect streams
- **Adobe Premiere** for the overstimulation collage
- **Ultralytics YOLOv8 + ByteTrack** for the Times Square walker tracker

---

## Credits

- **Author:** Siddharth Mehta · [mehts818@newschool.edu](mailto:mehts818@newschool.edu)
- **Advisor:** Clarinda Mac Low
- **Cohort site:** [parsons.edu/dt-2026](https://parsons.edu/dt-2026/)

Sources used in the overstimulation collage: *Fight Club* (Fincher, 1999) · *2001: A Space Odyssey* (Kubrick, 1968) · *Idiocracy* (Judge, 2006) · Banksy "Christ with Shopping Bags" (2005) · Barbara Kruger "I shop therefore I am" (1987) · Roy Lichtenstein "Blonde Waiting" (1964) · Andy Warhol Campbell's Soup Cans (1962) · news, ads, and viral content under fair use for educational thesis work.

**Thank you:** Clarinda, Nancy, the cohort, everyone who sat in the chair, the people whose answers became this work.

---

*be better everyday.*
