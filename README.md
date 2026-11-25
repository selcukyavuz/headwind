# Headwind

Interactive calculator that shows how wind direction and strength affect a road cyclist: required watts at a given speed, or speed at a given power. Includes a top-down live airflow view, a 3D scene, a polar chart and a 3D surface (wind direction × strength). Turkish and English.

**Live:** https://selcukyavuz.github.io/headwind/

Share button encodes all settings into a 12-character code in the URL hash (e.g. `#0fkigtDBUZWG`), so shared links open with the same settings — no backend or database.

Physics: F = ½ · ρ · CdA · V_apparent · V_axial, plus rolling resistance and gravity; 97% drivetrain efficiency; air density from temperature and altitude. Flow lines in the 3D scene are illustrative, not CFD.
