# Wajid Hussain — Personal Website

Source for my personal website: **[wajidengg.github.io](https://wajidengg.github.io)**

I'm a Chartered Electrical Engineer (C.Eng) and MEP coordinator with an MS in Cyber-Physical Systems (IoT) from Northeastern University. The site brings together my engineering experience, projects, education and skills, with a focus on smart buildings, industrial IoT and solar energy systems.

## What's on the site

- **About:** background, interests and the kind of engineering and research work I'm looking for
- **Projects:** [ISPOS](https://github.com/wajidengg/ispos), a weather-aware solar panel orientation system, and an MQTT-based industrial telemetry pipeline
- **Experience:** ten years of electrical and MEP coordination in Saudi Arabia, plus graduate teaching at Northeastern University
- **Education, registration and skills**
- **Contact:** email, LinkedIn, GitHub and a downloadable CV

## Built with

The site is a single static HTML page with inline CSS and a few lines of plain JavaScript. There is no framework, build step or dependency to install.

- Responsive layout for desktop and mobile
- Light and dark mode, following the visitor's device setting by default and remembering their choice
- Fonts: Source Serif 4 and Source Sans 3 from Google Fonts
- Email address assembled in the browser to reduce spam from scrapers
- Hosted on GitHub Pages

## Repository structure

```
.
├── index.html        # The whole site: content, styles and scripts
├── cv.pdf            # Downloadable CV linked from the header
├── images/
│   └── wajid.jpg     # Profile photo (initials are shown if missing)
└── README.md
```

## Updating the site

- **Content:** edit the text directly in `index.html`. Each section (`about`, `projects`, `experience`, `education`, `skills`, `contact`) is marked with its own `<section>` tag.
- **Photo:** replace `images/wajid.jpg` with a portrait-oriented image, ideally at least 600 × 750 px.
- **CV:** replace `cv.pdf` with the latest version, keeping the same file name.
- **Last updated date:** change the date in the footer at the bottom of `index.html`.

## Deployment

Changes pushed to the `main` branch are published automatically by GitHub Pages, usually within a minute or two.

## Contact

- Email: wajidengg [at] gmail [dot] com
- LinkedIn: [linkedin.com/in/whussain](https://www.linkedin.com/in/whussain)
- GitHub: [github.com/wajidengg](https://github.com/wajidengg)

## License

The code in this repository may be reused under the MIT License. The written content, CV and photo are © Wajid Hussain, all rights reserved.
