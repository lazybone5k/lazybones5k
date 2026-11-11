# Lazybones to 5K

**From the couch to 5K. One run at a time, with all the numbers on the table.**

Website: [lazybones5k.no](https://lazybones5k.no)
Vlog: [youtube.com/@Lazybonesto5k](https://www.youtube.com/@Lazybonesto5k)

<!--
  Building quality code with Chemex 16:1 Ratio - 45g coffee 720g water- 70g water bloom 40sec - target time 5:30
-->

## What is this?

This repository holds the website for *Lazybones to 5K*: a personal log of someone who hadn't run in over 20 years, working through a Couch to 5K program. The plan is based on Runner's World Norway's [«Fra sofa til 5 km»](https://runnersworld.no/fra-sofa-til-5km/).

The site is not a product or a template. It's a diary with graphs: every run, the good days and the heavy ones, straight from a sports watch and a heart rate strap. Part of the project is a surprise for some people I care about, so I'm not telling who I am. Not yet.

## What you'll find on the site

- **The journey:** progress through the 8-week plan, run by run.
- **Run by run:** elevation profile, pace, heart rate and recovery, cadence, running power and breathing for every interval, plus a short diary entry and how the run felt.
- **Progress:** heart rate, recovery, distance and how it felt over time.
- **Nerd corner:** efficiency factor, heart rate drift, running dynamics, VO2 max, heart rate zones, training effect and records.
- **Training calendar:** planned vs. completed runs, plus strength sessions for injury prevention.

The site is in English, with a Norwegian version available from the EN/NO button in the top right corner.

## How it's built

- **One static HTML file.** No framework, no build tools on the server, no database. All graphs are drawn with plain JavaScript and SVG.
- **Data from the watch.** After each run, the Garmin FIT file is processed offline into a small, anonymized data set that is embedded in the page. Only selected numbers are published.
- **Self-hosted fonts.** Anton, Barlow and Barlow Condensed are stored in `/fonts` (SIL Open Font License, see the license files in that folder).
- **Hosted on GitHub Pages** with a custom domain and HTTPS.

## Privacy by design

- No cookies, no analytics, no tracking scripts and no third-party requests.
- YouTube videos only load when a visitor clicks to play them (via youtube-nocookie.com).
- The language choice is stored only in the visitor's own browser.
- The training data contains no maps, GPS tracks, locations or times of day. Elevation is shown only as relative to the start.
- GitHub Pages keeps standard server logs (IP address and time). See the privacy section on the site for details.

## A note on the clone stats

If you're wondering why this small repository gets cloned so often: most clones of public repositories come from automated systems such as search indexers, code archives and security scanners, which typically pick up new commits within hours. So the clone numbers say more about the internet than about the number of readers. If you're a real person reading this: welcome, and thanks for following along!

## Files

| File | What it is |
|---|---|
| `index.html` | The entire website: layout, graphs and the training data |
| `CNAME` | Tells GitHub Pages to serve the site on lazybones5k.no |
| `fonts/` | Self-hosted fonts and their licenses |

## Credits

Built with help from Claude (Anthropic). Running done the hard way.

---

## På norsk

*Lazybones to 5K* er en personlig logg fra en som ikke hadde løpt på over 20 år, og som nå jobber seg gjennom «Fra sofa til 5 km». Siden viser hver økt med tall rett fra klokka og pulsbeltet, sammen med en kort dagbok. Den er bygget som én enkel HTML-fil uten informasjonskapsler, sporing eller statistikkverktøy. Kart, steder og klokkeslett er holdt utenfor med vilje.

Følg reisen på [lazybones5k.no](https://lazybones5k.no) eller på [YouTube](https://www.youtube.com/@Lazybonesto5k).
