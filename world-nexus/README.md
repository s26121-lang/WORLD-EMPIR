# WORLD NEXUS

**Build Cities. Connect Nations.**

A browser-based 2D global transport and city management simulation.

## Play
Open the GitHub Pages site after Pages deployment is enabled:
`https://s26121-lang.github.io/WORLD-EMPIR/world-nexus/`

## Phase 1 features
- Responsive management dashboard
- World map using Natural Earth projection and World Atlas country geometry (with a built-in fallback map)
- 19 real-world and fictional cities
- City selection and city information
- Station construction with costs
- Railway routes between owned stations
- Daily passenger revenue, maintenance costs and company valuation
- Population growth, company XP and levels
- Simulation speed controls and pause
- Browser save/load using localStorage

## Controls
1. Select a city marker to inspect it.
2. Choose **駅を建設** and click a city to build a station.
3. Build stations in two cities, choose **路線を接続**, then click both cities.
4. Use drag to pan and + / − to zoom.
5. Save data is stored in the current browser.

## Deployment
The repository workflow in `.github/workflows/deploy-world-nexus.yml` publishes this folder to GitHub Pages when the Pages site is configured to use GitHub Actions.

## Roadmap
1. Foundation: world map, cities, time, finance
2. Transport: rail, road, shipping and aviation
3. City growth and population simulation
4. AI companies and world economy
5. Underwater cities and ocean transport
6. Research, rankings, cloud saves and multiplayer groundwork
