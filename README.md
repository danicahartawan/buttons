# Buttons

Buttons is an interactive prototype for configuring a simple four-key controller. It pairs a tactile hardware view with a visual workflow editor so each physical button can be assigned, tested, and customized.

## What is included

- A four-button hardware controller view
- A workflow canvas for each button
- Editable button labels and light colors
- Recent-run history and workflow step details
- Simulated workflow runs, zoom controls, and chat-based editing
- Responsive layouts for desktop and smaller screens

## Run locally

This prototype uses plain HTML, CSS, and JavaScript, so no dependency installation is required.

```bash
python3 -m http.server 4174
```

Then open [http://127.0.0.1:4174](http://127.0.0.1:4174).

Open the workflow view directly at:

```text
http://127.0.0.1:4174/?screen=workflow
```

## Tests

```bash
node --test wireframe.test.mjs
```

## Project structure

```text
index.html          Interface structure
styles.css          Visual system, layout, and motion
app.mjs             Interaction and workflow state
assets/             Fonts and interface icons
wireframe.test.mjs  Prototype behavior tests
```

## Status

This repository is an evolving design prototype. External services shown in the workflow editor are mocked for interaction design and testing.
