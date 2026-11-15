# AZAS · Lunar Landing Site Navigator

When could a lander touch down near the Moon’s south pole and keep both the Sun and Earth in view for the next 48 hours? A nearby ridge can block sunlight or the line of sight to Earth. AZAS, a NASA Space Apps project, uses the local horizon at 27 candidate landing sites to find when both are visible.

![Map of 27 candidate sites near the lunar south pole, with Site01 selected and its terrain panorama shown alongside the map](https://raw.githubusercontent.com/NASA-AZAS/AZAS-FE/52522489d031a38001412c00fb46b3fe52936d19/docs/evidence/candidate-panorama-panel.png)

## Explore a mission

1. Choose a landing site and enter a mission deadline. The explorer finds the earliest touchdown that allows 48 hours of sunlight and a clear view of Earth.
2. Choose a launch site on Earth. The explorer works backward from that touchdown to show a possible departure time and lets you follow a preliminary trajectory from Earth orbit to lunar arrival.
3. After landing, move the timeline through those 48 hours. Watch the Sun and Earth change position above the terrain from the lander’s point of view.

## Example flight to DM2

For a mission deadline of January 31, 2027, the first qualifying touchdown at **DM2** is **January 11 at 03:30 UTC**. The model gives the following schedule for a departure from Kennedy Space Center. [View the launch options for this example](https://api.azas.n-e.kr/api/v1/analyses/7a2123b7-69ed-40f8-909e-c52a21488a79/launch-options)

| Mission event | Time in UTC |
| --- | --- |
| Launch from Kennedy Space Center | Jan 6, 2027 at 00:03:27 |
| Trans-lunar injection (departure from Earth orbit) | Jan 6, 2027 at 02:03:27 |
| Lunar arrival | Jan 10, 2027 at 21:30:00 |
| Touchdown at DM2 | Jan 11, 2027 at 03:30:00 |

## Project links

- Run the Expo and React Native explorer used in the DM2 example. [Frontend source and setup instructions](https://github.com/NASA-AZAS/AZAS-FE/tree/04f7f79f1847a0dc1393b69f4555f9a77016bf0d#readme)
- Look up landing sites and explore the analysis endpoints in the [public API documentation](https://api.azas.n-e.kr/docs).
- To contribute, read the [organization’s contribution guide](https://github.com/NASA-AZAS/.github/blob/main/CONTRIBUTING.md).
