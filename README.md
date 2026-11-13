# Seagrass Meadow · 海底草原

An interactive, single-file science page about Hong Kong's seagrass beds — told from Tung Chung and San Tau (䃟頭) on Lantau Island.

以香港大嶼山東涌、䃟頭為起點的互動科普頁，認識海草床是甚麼、為何重要、面對甚麼威脅，以及我們可以做甚麼。

## What's inside

- **An underwater opening scene** — seagrass blades, light shafts and fish drawn entirely in SVG and animated with CSS
- **Seagrass vs. seaweed vs. mangrove** — comparison cards plus a click-to-sort mini game
- **Ecosystem services** — four expandable panels, with an area-to-carbon calculator
- **A map of Hong Kong sites** — San Tau, Tung Chung estuary, Pak Nai, Lai Chi Wo, Yan Chau Tong
- **Species cards** — 3D flip cards for horseshoe crabs, pipefish, crabs, snails and juvenile fish
- **Threats → impacts → actions** flow, a conservation pledge list, and an 8-question quiz

## Technical notes

- Single page: `index.html` plus a folder of photographs in `assets/`. No build step, no framework, no network requests at runtime.
- Photographs are CC-licensed works from Wikimedia Commons and Flickr, resized and cropped for the page. Every image is credited in the footer with its author, licence and a link to the original — please keep that block if you reuse this page.
- The map is a deliberately schematic diagram (not to scale, not a navigational map), labelled as such on the page.
- Pledge state is stored in `localStorage`; nothing leaves the browser.

## Sources

- [Hong Kong Biodiversity Information Hub — habitats](https://bih.gov.hk/en/habitats/index-id-5.html)
- [CEDD — nature conservation and biodiversity](https://sslo.cedd.gov.hk/sc/exploring-more/nature-conservation/environment-biodiversity/index.html)
- [HKU Knowledge Exchange — seagrass research](https://www.ke.hku.hk/story/innovation/seagrasses)

Content is a simplified summary for educational use. Figures in the calculator are illustrative estimates, not field measurements.

## Image credits

Fourteen CC-licensed photographs, credited in full in the page footer. Non-commercial educational use only — check each licence (some are BY-NC / BY-NC-SA) before reusing them commercially.

## Run locally

Open `index.html` in any browser, or serve the folder:

```bash
python3 -m http.server 8000
```
