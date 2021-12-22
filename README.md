# AllSky

Interactive visualizations of the celestial sphere using different all-sky datasets:
 - The unWISE layers of infrared all-sky imaging © [unWISE / NASA/JPL-Caltech / D.Lang (Perimeter Institute)](https://www.legacysurvey.org/acknowledgment/)
 - The SFD dust map using the far infrared, from [Schlafly & Finkbeiner (2011)](http://adsabs.harvard.edu/abs/2011ApJ...737..103S) and [Schlegel, Finkbeiner & Davis (1998)](http://adsabs.harvard.edu/abs/1998ApJ...500..525S)
 - The Planck 2018 cosmic microwave background temperature anisotropy © [ESA / Planck Collaboration](https://sci.esa.int/web/planck/-/60505-planck-s-cosmic-microwave-background-equirectangular-projection).

Try the demo [here](https://dkirkby.github.io/allsky/) and experiment with the mouse / touch controls.

The data sources above are each transformed into an all-sky equirectangular projection then applied as environmental textures in WebGL using the [THREE.js framework](https://threejs.org/).  The unWISE and SFD projections are assembled from about 200 TAN projections using [this notebook](#).
