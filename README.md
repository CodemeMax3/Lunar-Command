# LUNAR COMMAND — Mission Survival Simulator

A browser-based educational game for the NASA Space Apps Challenge prompt “Build a Junior Astronaut Mission Trainer”.

## Run
Open `index.html` in a modern browser. No server, install, account, or API key is required. The app works offline after download.

## Gameplay
- Lead a four-person simulated lunar outpost for up to 30 sols.
- Manage oxygen, water, food, battery power, radiation shielding, thermal comfort and crew safety.
- Choose one action per sol: recycle, deploy solar array, run greenhouse, add regolith shielding, conserve resources, or maintain systems.
- Daily consumption and periodic random events create trade-offs.
- Finish with a mission debrief and score.

## NASA references
- NASA Moon Base Systems: https://www.nasa.gov/moonbase-systems/
- NASA Lunar South Pole Environment: https://www.nasa.gov/reference/moonbase-environment/
- From Apollo to Artemis: https://www.nasa.gov/moonbase-environment-visualization/
- NASA Science — Weather on the Moon: https://science.nasa.gov/moon/weather-on-the-moon/

NASA references inform the learning scenario. The numerical resource units, action costs, event probabilities and scoring are simplified original game-design assumptions; they are not NASA mission specifications or operational data.

## Repository contents
- `index.html` — complete playable simulator
- `Project_Submission_Text.md` — copy-ready text for the NASA project page
- `UPLOAD_CHECKLIST.md` — final submission checklist
- `README.md` — setup and project notes

The seven-slide PowerPoint demo is included in the complete submission ZIP package, available separately from the repository.

## Publish as a live website
A GitHub Actions deployment workflow is included at `.github/workflows/deploy-pages.yml`. To activate GitHub Pages for this repository, open **Settings → Pages** and set **Build and deployment → Source** to **GitHub Actions**. The workflow then publishes the root `index.html` after a push to `main`; the expected site address is `https://codememax3.github.io/Lunar-Command/`.

## Suggested improvements before judging
Test the game in Chrome on laptop and mobile, capture screenshots of gameplay, and once Pages is enabled, test the public website link. Replace the team/member placeholders in the slide deck and submission text with your actual details. Do not claim features or testing you have not completed.
