# MnO₂ Nanoparticle Pseudocapacitive Energy Storage Device

Fabrication and electrochemical characterisation of a low-cost MnO₂ nanoparticle supercapacitor prototype.
Interdisciplinary Project Based Learning (1BPRJ208), Dept. of ECE, Dayananda Sagar College of Engineering, Bengaluru (2025–26).

## Overview

MnO₂ nanoparticles are synthesised by reducing potassium permanganate (KMnO₄), mixed into an electrode slurry with PVDF binder and carbon black, coated onto a glass substrate with copper foil as the current collector, and mounted on a 3D-printed frame. The device uses 1 M Na₂SO₄ aqueous electrolyte and is characterised with an oscilloscope and function generator by measuring output voltage and phase angle against frequency.

## Team

| Name | USN | Role |
|---|---|---|
| Baleshwar S | 1DS25EC071 | 3D frame design (CAD), current collector, structural testing |
| D Bhumith | 1DS25EC075 | MnO₂ chemical synthesis and powder characterisation |
| Anagha Natraj | 1DS25CH006 | Slurry optimisation, coating, literature review |
| Sreelakshmi Y H | 1DS25CH051 | Electrical characterisation and result analysis |

Guides: Dr. Basavaraj S S (ECE) and Dr. Seema Sakkara (Chemical Engineering).

## Repository Structure

```
.
├── README.md
├── report/            # Project report (.docx)
├── figures/           # Snapshots, flowchart, frequency and phase plots
└── datasets/          # Oscilloscope readings for 100, 200 and 300 mg electrodes (add here)
```

## Method

1. **Synthesis:** KMnO₄ is chemically reduced to MnO₂ nanoparticles.
2. **Slurry:** MnO₂, carbon black and PVDF binder are mixed into a homogeneous slurry.
3. **Electrode:** The slurry is coated on glass; copper foil is attached as the current collector.
4. **Assembly:** Electrodes are mounted on a 3D-printed PLA/PETG frame and 1 M Na₂SO₄ is introduced.
5. **Characterisation:** Output voltage and phase angle are measured over a frequency sweep.

## Results Summary

| Parameter | 100 mg | 200 mg | 300 mg |
|---|---|---|---|
| Peak phase angle | 32.6° | 32.04° | 32.67° |
| Peak phase frequency | ~80 kHz | ~100–200 kHz | ~100 kHz |
| Flat band region | 200 Hz – 10 kHz | 500 Hz – 50 kHz | 500 Hz – 80 kHz |
| High-frequency roll-off onset | ~100 kHz | ~200 kHz | ~200 kHz |
| Capacitive stability | Moderate | Good | Best |

All three loadings show pseudocapacitive behaviour in the measured range, and the flat-band region widens with mass loading.

## Bill of Materials

| Item | Cost (Rs.) |
|---|---|
| XRD characterisation | 500 |
| SEM characterisation | 600 |
| PVDF binder (50 g) | 850 |
| Copper foil roll | 500 |
| 3D-printed frame (PLA/PETG) | 100 |
| **Total** | **2,550** |

## Limitations and Next Steps

- Characterisation so far is frequency response only. Cyclic voltammetry (CV), galvanostatic charge–discharge (GCD) and electrochemical impedance spectroscopy (EIS) are needed to report capacitance, energy density and ESR properly.
- Capacitance values are not yet calculated.
- Planned work: plant-based reducing agents, MnO₂/rGO or activated-carbon composites, flexible substrates, asymmetric cell design, and series/parallel integration.

## References

1. R. Huang et al., "Green synthesis of MnO₂ nanoparticles using plant extract and their electrochemical properties," *J. Alloys Compd.*, 820, 2020.
2. R. Vijay et al., "Flavonoid-mediated biogenic synthesis of manganese oxide nanoparticles," *Mater. Lett.*, 280, 2021.
3. P. Kumar et al., "Green synthesized MnO nanoparticles for supercapacitor electrode applications," *Electrochim. Acta*, 405, 2022.
4. A. Singh et al., "Oregano extract as a reducing agent in metal oxide nanoparticle synthesis," *J. Mater. Sci.*, 54(12), 2019.
5. S. Biswas et al., "Organic Supercapacitors as the Next Generation Energy Storage Device," *ChemPhysChem*, 23(15), 2022.
6. B. E. Conway, *Electrochemical Supercapacitors*, Kluwer/Plenum, 1999.
<img width="769" height="432" alt="image" src="https://github.com/user-attachments/assets/91395804-40a4-486d-acfe-ea2905943033" />

## License

Add a license before public release. Academic project; contact the team for reuse.
