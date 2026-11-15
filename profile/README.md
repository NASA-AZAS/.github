# AZAS · Lunar Landing Site Navigator

When could a lander touch down near the Moon’s south pole and keep both the Sun and Earth in view for the next 48 hours? A nearby ridge can block sunlight or the line of sight to Earth. AZAS, a NASA Space Apps project, uses the local horizon at each landing site to find when both are visible.

![Map of candidate landing sites near the lunar south pole, with the selected site's terrain panorama alongside it](https://raw.githubusercontent.com/NASA-AZAS/AZAS-FE/52522489d031a38001412c00fb46b3fe52936d19/docs/evidence/candidate-panorama-panel.png)

## Explore a mission

1. Choose any of the 27 candidate landing sites and enter a mission deadline. If the Sun and Earth are both visible for 48 consecutive hours within that period, the explorer shows the earliest qualifying touchdown.
2. Choose a launch site on Earth. The explorer works backward from that touchdown to show a possible departure time and lets you follow a preliminary trajectory from Earth orbit to lunar arrival.
3. After landing, move the timeline through those 48 hours. Watch the Sun and Earth change position above the terrain from the lander’s point of view.

## Project links

- Run the Expo and React Native explorer. [Frontend source and setup instructions](https://github.com/NASA-AZAS/AZAS-FE/tree/04f7f79f1847a0dc1393b69f4555f9a77016bf0d#readme)
- Look up landing sites and explore the analysis endpoints in the [public API documentation](https://api.azas.n-e.kr/docs).
- To contribute, read the [organization’s contribution guide](https://github.com/NASA-AZAS/.github/blob/main/CONTRIBUTING.md).
