# fullstack4j home

The landing page for [fullstack4j.dev](https://fullstack4j.dev): small teams building whole features
in plain Java with Spring Boot, Apache Wicket, Spring Modulith and MongoDB (tested with
Testcontainers). fullstack4j is an offering of
[allwerker eG](https://allwerker.com/en/), a Munich cooperative of senior engineers, which sets up,
staffs and coaches such teams.

A single static page with no build step:

- `index.html` with inline CSS and a little inline JavaScript (theme toggle, code tabs, copy buttons)
- `assets/` with the logo, the allwerker logo, social card (`og.png`), touch icon and portrait

Preview locally:

    python3 -m http.server 8000

Published with GitHub Pages from `main`; `CNAME` points it at `fullstack4j.dev`.

Related projects: [fullstack4j start](https://github.com/danielbartl/fullstack4j-start),
[Wicket Spring Boot Starter](https://github.com/danielbartl/wicket-spring-boot-starter),
[Wicket Oat](https://github.com/danielbartl/wicket-oat).
