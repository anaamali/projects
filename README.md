# Real-World Data Configurator: Demo

A working replica of an internal tool that lets Customer Success configure,
review and release data extracts for enterprise clients, replacing hand-coded
specs with a reviewed, versioned and auditable path.

**Live demo:** <(https://anaamali.github.io/projects/)>

## The problem
Extract specs were typed by hand into code before each delivery. One typo
meant a wrong delivery to a customer. In the 12 months before the tool, there
were 9 redeliveries.

## What the tool does
- A CSM enters the spec in a UI instead of editing code.
- A second person reviews it. You can't approve your own work.
- The approved parameters feed the pipeline automatically.
- A TAM checks the extract, and the CSM publishes it with one click.
- Every version and sign-off is recorded.

## What's in this repo
- `index.html`: the whole demo, one self-contained file. No build step.

## Try it
Open `index.html` in a browser, or use the live demo link. In the Demo Build
section, follow the guided steps and switch roles when prompted.

## Notes
- All company, customer and project names are fictional.
- Figures on the page are illustrative
- The UI is modeled on the real product's designs. It has no backend, and
  all behavior is simulated in the browser.
- Built with plain HTML, CSS and JavaScript. Charts use Chart.js from a CDN.

## My role
I was the product owner. I spotted the problem and owned the work from discovery through rollout:
- Discovery: mapped how a delivery moved across four teams and counted the redeliveries it caused.
- Requirements: defined what the tool had to do, including the review step that stops people approving their own work.
- Prioritization: decided what shipped first and what waited.
- Rollout: moved deliveries onto the new path.
- Demo: created this walkthrough so the workflow can be shown without exposing internal systems.
