# rgevolve.wet.jms

Package providing Renormalization Group Evolution matrices for the
**WET** in the **JMS** basis, following the
[wcxf](https://wcxf.github.io/) conventions for Wilson coefficient
bases.

It is a sub-package of the **rgevolve** ecosystem — a set of Python
namespace packages for fast renormalization group evolution of Wilson
coefficients in the SMEFT and the WET using the evolution matrix
formalism. See the [rgevolve organization](https://github.com/rgevolve)
for the full ecosystem and the
[`rgevolve` meta-package](https://github.com/rgevolve/rgevolve) for
installation in lockstep with the core and all companions.

<!-- BEGIN: auto-generated from data.h5 by .github/scripts/generate-readme.py — do not edit by hand -->

## Contents

This distribution bundles RG evolution matrices precomputed at
**13 scales** between **2** and
**91.1876** GeV:

| scale (GeV) |
| ----------- |
| 2 |
| 4.2 |
| 4.8 |
| 5 |
| 5.91248 |
| 8.32321 |
| 11.7169 |
| 16.4942 |
| 23.2195 |
| 32.6869 |
| 46.0145 |
| 64.7761 |
| 91.1876 |

Matrices are organised into **219 sectors** covering a total
of **4277 Wilson coefficients** (counting the real and imaginary
parts of complex coefficients separately):

| sector | # Wilson coefficients |
| ------ | --------------------- |
| `cbbnue` | 4 |
| `cbbnumu` | 4 |
| `cbbnutau` | 4 |
| `cbenue` | 10 |
| `cbenumu` | 10 |
| `cbenutau` | 10 |
| `cbmunue` | 10 |
| `cbmunumu` | 10 |
| `cbmunutau` | 10 |
| `cbtaunue` | 10 |
| `cbtaunumu` | 10 |
| `cbtaunutau` | 10 |
| `ccbe` | 8 |
| `ccbmu` | 8 |
| `ccbtau` | 8 |
| `ccde` | 8 |
| `ccdmu` | 8 |
| `ccdtau` | 8 |
| `ccse` | 8 |
| `ccsmu` | 8 |
| `ccstau` | 8 |
| `cdbnue` | 10 |
| `cdbnumu` | 10 |
| `cdbnutau` | 10 |
| `cddnue` | 4 |
| `cddnumu` | 4 |
| `cddnutau` | 4 |
| `cdenue` | 10 |
| `cdenumu` | 10 |
| `cdenutau` | 10 |
| `cdmunue` | 10 |
| `cdmunumu` | 10 |
| `cdmunutau` | 10 |
| `cdsnue` | 10 |
| `cdsnumu` | 10 |
| `cdsnutau` | 10 |
| `cdtaunue` | 10 |
| `cdtaunumu` | 10 |
| `cdtaunutau` | 10 |
| `csbnue` | 10 |
| `csbnumu` | 10 |
| `csbnutau` | 10 |
| `csenue` | 10 |
| `csenumu` | 10 |
| `csenutau` | 10 |
| `csmunue` | 10 |
| `csmunumu` | 10 |
| `csmunutau` | 10 |
| `cssnue` | 4 |
| `cssnumu` | 4 |
| `cssnutau` | 4 |
| `cstaunue` | 10 |
| `cstaunumu` | 10 |
| `cstaunutau` | 10 |
| `cu` | 228 |
| `cucu` | 16 |
| `cuemu` | 20 |
| `cuetau` | 20 |
| `cumue` | 20 |
| `cumutau` | 20 |
| `cunuinui` | 12 |
| `cunumunue` | 8 |
| `cunumunutau` | 8 |
| `cunutaunue` | 8 |
| `cutaue` | 20 |
| `cutaumu` | 20 |
| `dF=0` | 463 |
| `db` | 228 |
| `dbcu` | 40 |
| `dbdb` | 16 |
| `dbds` | 20 |
| `dbemu` | 20 |
| `dbetau` | 20 |
| `dbmue` | 20 |
| `dbmutau` | 20 |
| `dbnuinui` | 12 |
| `dbnumunue` | 8 |
| `dbnumunutau` | 8 |
| `dbnutaunue` | 8 |
| `dbsb` | 20 |
| `dbtaue` | 20 |
| `dbtaumu` | 20 |
| `dbuc` | 40 |
| `etauemu` | 12 |
| `ffnuinui` | 48 |
| `ffnumunue` | 32 |
| `ffnumunutau` | 32 |
| `ffnutaunue` | 32 |
| `mue` | 148 |
| `muemue` | 10 |
| `muemutau` | 12 |
| `muenuenumu` | 4 |
| `muenuenutau` | 4 |
| `muenuinui` | 12 |
| `muenumunue` | 4 |
| `muenumunutau` | 4 |
| `muenutaunue` | 4 |
| `muenutaunumu` | 4 |
| `mutau` | 148 |
| `mutaunuenumu` | 4 |
| `mutaunuenutau` | 4 |
| `mutaunuinui` | 12 |
| `mutaunumunue` | 4 |
| `mutaunumunutau` | 4 |
| `mutaunutaunue` | 4 |
| `mutaunutaunumu` | 4 |
| `nuenutaunuenumu` | 2 |
| `nuinuinujnuj` | 6 |
| `numunuenuinui` | 6 |
| `numunuenumunue` | 2 |
| `numunuenumunutau` | 2 |
| `numunutaunuinui` | 6 |
| `nutaunuenuinui` | 6 |
| `nutaunuenutaunue` | 2 |
| `nutaunuenutaunumu` | 2 |
| `nutaunumunutaunumu` | 2 |
| `sb` | 228 |
| `sbcu` | 40 |
| `sbemu` | 20 |
| `sbetau` | 20 |
| `sbmue` | 20 |
| `sbmutau` | 20 |
| `sbnuinui` | 12 |
| `sbnumunue` | 8 |
| `sbnumunutau` | 8 |
| `sbnutaunue` | 8 |
| `sbsb` | 16 |
| `sbsd` | 20 |
| `sbtaue` | 20 |
| `sbtaumu` | 20 |
| `sbuc` | 40 |
| `sd` | 228 |
| `sdcu` | 40 |
| `sdemu` | 20 |
| `sdetau` | 20 |
| `sdmue` | 20 |
| `sdmutau` | 20 |
| `sdnuinui` | 12 |
| `sdnumunue` | 8 |
| `sdnumunutau` | 8 |
| `sdnutaunue` | 8 |
| `sdsd` | 16 |
| `sdtaue` | 20 |
| `sdtaumu` | 20 |
| `sduc` | 40 |
| `taue` | 148 |
| `tauenuenumu` | 4 |
| `tauenuenutau` | 4 |
| `tauenuinui` | 12 |
| `tauenumunue` | 4 |
| `tauenumunutau` | 4 |
| `tauenutaunue` | 4 |
| `tauenutaunumu` | 4 |
| `tauetaue` | 10 |
| `tauetaumu` | 12 |
| `taumutaumu` | 10 |
| `ubbnue` | 4 |
| `ubbnumu` | 4 |
| `ubbnutau` | 4 |
| `ubenue` | 10 |
| `ubenumu` | 10 |
| `ubenutau` | 10 |
| `ubmunue` | 10 |
| `ubmunumu` | 10 |
| `ubmunutau` | 10 |
| `ubtaunue` | 10 |
| `ubtaunumu` | 10 |
| `ubtaunutau` | 10 |
| `ucbe` | 20 |
| `ucbmu` | 20 |
| `ucbtau` | 20 |
| `ucde` | 20 |
| `ucdmu` | 20 |
| `ucdtau` | 20 |
| `ucse` | 20 |
| `ucsmu` | 20 |
| `ucstau` | 20 |
| `udbnue` | 10 |
| `udbnumu` | 10 |
| `udbnutau` | 10 |
| `uddnue` | 4 |
| `uddnumu` | 4 |
| `uddnutau` | 4 |
| `udenue` | 10 |
| `udenumu` | 10 |
| `udenutau` | 10 |
| `udmunue` | 10 |
| `udmunumu` | 10 |
| `udmunutau` | 10 |
| `udsnue` | 10 |
| `udsnumu` | 10 |
| `udsnutau` | 10 |
| `udtaunue` | 10 |
| `udtaunumu` | 10 |
| `udtaunutau` | 10 |
| `usbnue` | 10 |
| `usbnumu` | 10 |
| `usbnutau` | 10 |
| `usenue` | 10 |
| `usenumu` | 10 |
| `usenutau` | 10 |
| `usmunue` | 10 |
| `usmunumu` | 10 |
| `usmunutau` | 10 |
| `ussnue` | 4 |
| `ussnumu` | 4 |
| `ussnutau` | 4 |
| `ustaunue` | 10 |
| `ustaunumu` | 10 |
| `ustaunutau` | 10 |
| `uube` | 8 |
| `uubmu` | 8 |
| `uubtau` | 8 |
| `uude` | 8 |
| `uudmu` | 8 |
| `uudtau` | 8 |
| `uuse` | 8 |
| `uusmu` | 8 |
| `uustau` | 8 |

<!-- END: auto-generated -->

## Installation

```bash
pip install rgevolve.wet.jms
```

To install the core package together with all available EFT/basis
companion packages at once, use the meta-package:

```bash
pip install rgevolve
```

## License

`rgevolve.wet.jms` is licensed under the MIT License — see [`LICENSE`](LICENSE).
