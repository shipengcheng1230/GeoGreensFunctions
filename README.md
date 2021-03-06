# GeoGreensFunction

[![CI](https://github.com/shipengcheng1230/GeoGreensFunctions.jl/workflows/CI/badge.svg)](https://github.com/shipengcheng1230/GeoGreensFunctions.jl/actions?query=workflow%3ACI)
[![codecov](https://codecov.io/gh/shipengcheng1230/GeoGreensFunctions.jl/branch/master/graph/badge.svg)](https://codecov.io/gh/shipengcheng1230/GeoGreensFunctions.jl)
[![](https://img.shields.io/badge/docs-stable-blue.svg)](https://shipengcheng1230.github.io/GeoGreensFunctions.jl/stable)
[![](https://img.shields.io/badge/docs-dev-blue.svg)](https://shipengcheng1230.github.io/GeoGreensFunctions.jl/dev/)

Commonly used Green's function in geoscience.

- [Line (2 nodes) antiplane dislocation](https://press.princeton.edu/books/ebook/9781400833856/earthquake-and-volcano-deformation)

- [Line (2 nodes) inplane dislocation](https://press.princeton.edu/books/ebook/9781400833856/earthquake-and-volcano-deformation) (check [Errata](https://cdfm.stanford.edu/sites/g/files/sbiybj14411/f/errata_0.pdf))

- [Rectangular (4 nodes) dislocation](https://www.bosai.go.jp/e/dc3d.html) (limited rotational freedom)

- [Triangular (3 nodes) dislocation](http://volcanodeformation.com/software.html) (singularity avoided)

- [Rectangular (4 nodes) dislocation](http://volcanodeformation.com/software.html) (fully rotational freedom)

- [Rectangular (4 nodes) antiplane strain](https://bitbucket.org/sbarbot/bssa-2016237/src/master/matlab/computeDisplacementAntiplaneDippingShearZone.m)

- [Rectangular (4 nodes) inplane strain](https://bitbucket.org/sbarbot/bssa-2016237/src/master/matlab/computeDisplacementPlaneStrainShearZone.m)

- [Triangular (3 nodes) antiplane strain](https://bitbucket.org/sbarbot/bssa-2018058/src/default/matlab/computeDisplacementAntiplaneTriangleShearZone.m)

- [Triangular (3 nodes) inplane strain](https://bitbucket.org/sbarbot/bssa-2018058/src/default/matlab/computeDisplacementPlaneStrainTriangleShearZone.m)

- [Hexahedron (8 nodes) volume strain](https://bitbucket.org/sbarbot/bssa-2016237/src/master/matlab/computeDisplacementVerticalShearZone.m)

- [Tetrahedron (4 nodes) volume strain](https://bitbucket.org/sbarbot/bssa-2018058/src/default/matlab/computeDisplacementTetrahedronShearZoneGauss.m)

## Reference

Okada, Y. (1992). Internal deformation due to shear and tensile faults in a half-space. Bulletin of the Seismological Society of America, 82(2), 1018–1040.

SEGALL, P. (2010). Earthquake and Volcano Deformation (STU-Student edition). Princeton University Press. Retrieved from http://www.jstor.org/stable/j.ctt7sg19

Nikkhoo, M., & Walter, T. R. (2015). Triangular dislocation: an analytical, artefact-free solution. Geophysical Journal International, 201(2), 1119–1141. https://doi.org/10.1093/gji/ggv035

Nikkhoo, M., Walter, T. R., Lundgren, P. R., & Prats-Iraola, P. (2017). Compound dislocation models (CDMs) for volcano deformation analyses. Geophysical Journal International, 208(2), 877–894. https://doi.org/10.1093/gji/ggw427

Barbot, S., Moore, J. D. P., & Lambert, V. (2017). Displacement and Stress Associated with Distributed Anelastic Deformation in a Half‐Space. Bulletin of the Seismological Society of America, 107(2), 821–855. https://doi.org/10.1785/0120160237

Barbot, S. (2018). Deformation of a Half‐Space from Anelastic Strain Confined in a Tetrahedral Volume. Bulletin of the Seismological Society of America, 108(5A), 2687–2712. https://doi.org/10.1785/0120180058
