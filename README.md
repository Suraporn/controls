# Nate Puangpanbut: Advanced Process Control & Instrument Engineering Portfolio

**Live site → [suraporn.github.io/Nate-Control-Website](https://suraporn.github.io/Nate-Control-Website/)**

This is my portfolio as an advanced process control and instrument engineer. I have about 10 years of hands-on plant experience in DCS/PLC systems, control and interlock design, PID tuning, advanced process control, HVAC and field instrumentation.

## What's on the site

It's a single page:

- **Selected projects:** control and interlock design, VSD and boiler energy savings, adaptive and long-dead-time PID, control performance monitoring, analyzer upgrades, P&ID digitization, shutdown leadership, HVAC and instrument reliability.
- **Experience:** controls and instrumentation roles, plus a summary of my data science work.
- **Skills:** platforms, equipment, standards (IEC 61508/61511, Foundation Fieldbus) and project delivery.
- **Education & training**, and a downloadable résumé.

My data science portfolio is at [suraporn.github.io/Nate-DS-Website](https://suraporn.github.io/Nate-DS-Website/).

## Built with

Plain HTML and CSS, with no build step. It's hosted free on GitHub Pages.

```
home.html         The whole site (single page)
index.html        Redirects to home.html
style.css         Styles
images/           Profile photo, favicon
files/resume.pdf  Downloadable résumé
```

## Run it locally

```
python3 -m http.server 8000
```

Then open http://localhost:8000.

## Updating

- **Add a project:** copy one of the `<div class="card case">` blocks in `home.html`.
- **Update the résumé:** replace `files/resume.pdf`.
- **Style changes:** after editing `style.css`, bump the `?v=` number in its link.

## Contact

nate.puangpanbut@gmail.com · [LinkedIn](https://www.linkedin.com/in/suraporn/)
