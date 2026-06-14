# RadarWise Tester Checklist

Please report:

- Home Assistant version
- HACS version
- RadarWise version, such as `v0.7.0`
- Browser/device
- Weather entity used
- Country/radar provider
- Layout preset and dashboard type, such as Sections, Masonry, Panel, wall tablet, or phone
- Whether you installed from HACS custom repository, manual resource, or CDN
- Screenshot of any layout issue
- Browser console errors, if any

Basic checks:

1. Install RadarWise from HACS custom repository.
2. Add the card from the dashboard card picker.
3. Open the visual editor.
4. Select a weather entity.
5. Save.
6. Refresh the dashboard.
7. Confirm current weather, forecast rows, and stats load.
8. Confirm dew point appears automatically or works with a selected dew point sensor.
9. Test Environment sensors with Home Assistant sensors if available.
10. Test Environment source set to Open-Meteo and confirm AQI/pollen appears beside the clock/date.
11. Test `theme_mode: radarwise`.
12. Test `theme_mode: auto`.
13. Test the layout tiles: `auto`, `wide_panel`, `stacked`, `radar_bottom`, and `compact`.
14. Drag panel order in the visual editor and confirm it persists after save/refresh.
15. Adjust panel widths and confirm the total stays at 100%.
16. Test `stack_below` by resizing or using a narrow dashboard column.
17. Test `timeline_autoscroll` with more forecast rows than fit onscreen.
18. Test radar on desktop and phone.
19. Test with `show_radar: false`.
20. Screenshot or copy any errors.
