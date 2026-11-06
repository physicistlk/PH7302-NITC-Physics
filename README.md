# PH 7302: Condensed Matter Physics

[![Institution](https://img.shields.io/badge/NIT%20Calicut-Department%20of%20Physics-143264?style=for-the-badge&logo=googlescholar&logoColor=white)](https://nitc.ac.in)
[![Course](https://img.shields.io/badge/Course-PH7302E%20%2F%20PH7302-8C281E?style=for-the-badge)](syllabus/PH7302_Condensed_Matter_Physics_Syllabus.pdf)
[![Program](https://img.shields.io/badge/Program-M.Sc.%20Physics-117A65?style=for-the-badge)](https://nitc.ac.in)
[![Status](https://img.shields.io/badge/Edition-2026--27%20Publication%20Grade-C77C02?style=for-the-badge)](notes/)
[![LaTeX](https://img.shields.io/badge/Typeset%20with-pdfLaTeX%20%2B%20TikZ-6A3D9A?style=for-the-badge&logo=latex&logoColor=white)](sources/)

Welcome to the official repository for **PH 7302 / PH 7302E: Condensed Matter Physics**, a core postgraduate course offered to Master of Science (M.Sc.) in Physics students at the **Department of Physics, National Institute of Technology Calicut (NITC)**.

This repository provides comprehensive, publication-grade student editions of lecture notes, complete worked solution manuals, native TikZ vector diagrams, computational physics demonstrations, and official examination question papers with detailed step-by-step solutions.

---

## 📑 Table of Contents
- [Quick Access: Student Lecture Notes](#-quick-access-student-lecture-notes)
- [Course Syllabus & Modular Breakdown](#-course-syllabus--modular-breakdown)
- [Tutorial Assignments & Worked Solutions](#-tutorial-assignments--worked-solutions)
- [Examinations & Assessment Materials](#-examinations--assessment-materials)
- [Repository Architecture](#-repository-architecture)
- [Recommended Textbooks & References](#-recommended-textbooks--references)
- [Building from LaTeX Source](#-building-from-latex-source)

---

## 📚 Quick Access: Student Lecture Notes

All lecture notes are prepared in a unified, professional NIT Calicut palette (`#143264` deep navy, `#8C281E` deep maroon, `#117A65` teal, `#C77C02` amber) featuring customized callout environments (`keybox`, `physbox`, `probbox`, `solbox`, `pitbox`), embedded native vector graphics, and step-by-step worked problems.

| Module | Core Subject | Pages | Key Highlights & Diagrams | Direct PDF Link | LaTeX Source |
| :--- | :--- | :---: | :--- | :---: | :---: |
| **Module 1** | **Crystal Physics & Reciprocal Lattice** | 25 | 6 TikZ vector figures: 3D unit cells, Wigner-Seitz cells, Miller planes, Ewald sphere, Brillouin zones, BCC extinctions; 24 worked problems | [📥 Module 1 PDF](notes/PH7302_Module1_Crystal_Physics_Student_Copy.pdf) | [Sources](sources/module1/) |
| **Module 2** | **Lattice Vibrations & Thermal Properties** | 38 | 18 vector figures: 1D mono/diatomic chains, acoustic/optical branches, Debye & Einstein heat capacity ($T^3$ law), phonon thermal conductivity | [📥 Module 2 PDF](notes/PH7302_Module2_Lattice_Vibrations_and_Thermal_Properties_Student_Copy.pdf) | [Sources](sources/module2/) |
| **Module 3** | **Free Electron Theory of Metals** | 85 | Classical Drude model, Sommerfeld quantum theory, Fermi-Dirac statistics, electronic heat capacity, electrical & thermal conductivity, Wiedemann-Franz law | [📥 Module 3 PDF](notes/PH7302_Module3_Free_Electron_Theory_Student_Copy.pdf) | [Sources](sources/module3/) |
| **Module 4** | **Energy Bands & Semiconductors** | 48 | 18 vector figures: Bloch theorem, Kronig-Penney model, reduced/extended zone schemes, effective mass ($m^*$), intrinsic & extrinsic semiconductors | [📥 Module 4 PDF](notes/PH7302_Module4_Energy_Band_Theory_and_Semiconductors_Student_Copy.pdf) | [Sources](sources/module4/) |
| **Module 5A** | **Magnetic Properties of Materials** | 46 | Dia-, para-, ferro-, antiferro-, and ferrimagnetism; Curie & Curie-Weiss laws, quantum Hund's rules, Heisenberg exchange, domains, B-H hysteresis | [📥 Module 5A PDF](notes/PH7302_Module5A_Magnetism_Student_Copy.pdf) | [Sources](sources/module5A/) |
| **Module 5B** | **Dielectrics, Ferroelectrics & Optical Response** | 32 | Macroscopic Maxwell fields, Clausius-Mossotti relation, polarizability mechanisms, ferroelectric phase transitions (LST relation), optical phonons | [📥 Module 5B PDF](notes/PH7302_Module5B_Dielectrics_Ferroelectrics_Optical_Properties_Student_Copy.pdf) | [Sources](sources/module5B/) |

---

## 🎯 Course Syllabus & Modular Breakdown

The official course structure is mapped across 39 lecture sessions as outlined in the [Course Syllabus](syllabus/PH7302_Condensed_Matter_Physics_Syllabus.pdf):

### Module 1: Crystal Physics & Reciprocal Lattice
- **Symmetry and Real-Space Lattices:** Bravais lattices, 7 crystal systems, 14 three-dimensional space lattices, primitive vs. conventional unit cells, Wigner-Seitz cell construction.
- **Miller Indices & Geometry:** Indexing crystal directions $[uvw]$ and plane families $(hkl)$, interplanar spacing $d_{hkl}$, cubic, tetragonal, and orthorhombic metrics.
- **Reciprocal Lattice:** Mathematical definition $\mathbf{a}_i \cdot \mathbf{b}_j = 2\pi\delta_{ij}$, geometric duality (reciprocal of BCC is FCC and vice versa), 1st Brillouin zone construction.
- **Diffraction Physics:** Geometric Bragg formulation ($2d\sin	heta = n\lambda$), von Laue vector condition ($\Delta\mathbf{k} = \mathbf{G}$), Ewald sphere construction, geometric structure factor $F_{hkl}$, atomic form factor, and systematic extinctions (BCC, FCC, Diamond, Zinc Blende, NaCl, CsCl).
- **Crystal Symmetry & Tensors:** Point groups, space groups, crystallographic restriction theorem ($n=1,2,3,4,6$), and Neumann's Principle applied to dielectric and piezoelectric tensors.

### Module 2: Lattice Vibrations & Thermal Properties
- **Harmonic Dynamics:** 1D monoatomic chain dispersion, 1D diatomic lattice with acoustic and optical branches, Brillouin zone boundaries, group vs. phase velocity.
- **Phonons & Quantization:** Phonon momentum, inelastic neutron scattering, experimental phonon dispersion curves.
- **Lattice Heat Capacity:** Classical Dulong-Petit failure, Einstein model (high- and low-$T$ limits), Debye continuum model ($T^3$ low-temperature law), Debye frequency $\omega_D$ and temperature $\Theta_D$.
- **Thermal Transport:** Anharmonic lattice interactions, Umklapp vs. Normal phonon scattering processes, lattice thermal conductivity ($\kappa = rac{1}{3} C_v v \ell$).

### Module 3: Free Electron Theory of Metals
- **Drude Classical Model:** DC and AC conductivity, relaxation time $	au$, Hall effect, Hall coefficient $R_H$, Wiedemann-Franz ratio and Lorenz number.
- **Sommerfeld Quantum Theory:** Fermi-Dirac distribution $f(E)$, density of states $g(E)$ in 1D, 2D, and 3D, Fermi energy $E_F$, Fermi temperature $T_F$, Fermi surface geometry.
- **Electronic Specific Heat:** Linear low-temperature electronic specific heat ($C_{	ext{el}} = \gamma T$), total low-$T$ specific heat ($C = \gamma T + eta T^3$), experimental determination of Sommerfeld coefficient $\gamma$.

### Module 4: Energy Band Theory & Semiconductors
- **Band Formulation:** Electrons in a periodic potential, Bloch's theorem, crystal momentum $\hbar\mathbf{k}$, central equation, nearly-free electron approximation.
- **Kronig-Penney Model:** Exact transcendental dispersion relation, origin of forbidden energy gaps, reduced, periodic, and extended zone representations.
- **Effective Mass Theory:** Dynamic response to external electric fields, effective mass tensor $m^* = \hbar^2 (d^2E/dk^2)^{-1}$, physical meaning of negative effective mass, concept of holes.
- **Semiconductor Physics:** Intrinsic carrier concentrations $n_i = p_i$, Fermi level location, extrinsic donors and acceptors, temperature dependence of carrier concentration, electrical conductivity and mobility.

### Module 5: Magnetic, Dielectric & Optical Properties of Solids
- **Module 5A (Magnetism):**
  - Classification of magnetic materials: diamagnetism (Langevin classical and quantum Larmor precession), paramagnetism (Curie's law, Brillouin function, Van Vleck temperature-independent paramagnetism, Pauli spin paramagnetism).
  - Ferromagnetism: Weiss molecular field theory, Curie-Weiss law, spontaneous magnetization, quantum exchange interaction (Heisenberg Hamiltonian), Bloch $T^{3/2}$ spin-wave (magnon) law.
  - Antiferromagnetism & Ferrimagnetism: Néel temperature $T_N$, sublattices, susceptibility below and above $T_N$.
  - Magnetic domains, Bloch domain walls, anisotropy, magnetostriction, and B-H hysteresis loops.
- **Module 5B (Dielectrics, Ferroelectrics & Optical Properties):**
  - Local electric field (Lorentz field $E_{	ext{loc}} = E + rac{P}{3\epsilon_0}$), dielectric constant and polarizability, Clausius-Mossotti equation.
  - Electronic, ionic, and orientational (dipolar) polarizabilities, frequency dependence and dielectric loss.
  - Ferroelectricity: Displacive vs. order-disorder transitions, Landau phenomenological theory, perovskite titanates ($	ext{BaTiO}_3$), polarization catastrophe, Lyddane-Sachs-Teller (LST) relation $rac{\epsilon(0)}{\epsilon(\infty)} = rac{\omega_{	ext{TO}}^2}{\omega_{	ext{LO}}^2}$.
  - Optical properties: Interaction of electromagnetic waves with lattice vibrations (polaritons), reststrahlen band, plasma oscillations and plasmons.

---

## 📝 Tutorial Assignments & Worked Solutions

Every module includes a consolidated, upfront tutorial problem set designed for continuous evaluation and midterm/endterm exam preparation:

| Document | Description | Problems Covered | Direct Link |
| :--- | :--- | :---: | :---: |
| **Module 1 Solution Rubric** | Complete solutions with point rubrics and common student pitfalls for Assignment 1 | 24 Problems | [📄 Module 1 Solutions Manual](notes/PH7302_Module1_Crystal_Physics_Worked_Solutions.pdf) |
| **Module 1 In-Text Solboxes** | Step-by-step worked proofs and numerical derivations integrated directly inside the lecture text | Integrated | [📖 Module 1 Notes](notes/PH7302_Module1_Crystal_Physics_Student_Copy.pdf) |
| **Module 2 Tutorial Boxes** | Practice problems on 1D monoatomic/diatomic chains and Debye heat capacity | Integrated | [📖 Module 2 Notes](notes/PH7302_Module2_Lattice_Vibrations_and_Thermal_Properties_Student_Copy.pdf) |
| **Module 3 Practice Sets** | Problems on Fermi-Dirac integrals, Drude relaxation, and Sommerfeld expansion | Integrated | [📖 Module 3 Notes](notes/PH7302_Module3_Free_Electron_Theory_Student_Copy.pdf) |
| **Module 4 Exercises** | Practice on Kronig-Penney band gaps, effective mass calculations, and carrier statistics | Integrated | [📖 Module 4 Notes](notes/PH7302_Module4_Energy_Band_Theory_and_Semiconductors_Student_Copy.pdf) |
| **Module 5 Problem Sets** | Problems on Curie-Weiss temperatures, Langevin diamagnetism, and Clausius-Mossotti | Integrated | [📖 Module 5A Notes](notes/PH7302_Module5A_Magnetism_Student_Copy.pdf) |

---

## 🎓 Examinations & Assessment Materials

Official examination question papers along with full solution manuals and marking schemes:

### Mid-Semester Examination
- 📄 [PH7302 Midterm Question Paper (PDF)](examinations/midterm/PH7302_Midterm_Question_Paper.pdf)
- 📝 [PH7302 Midterm Solutions Manual (PDF)](examinations/midterm/PH7302_Midterm_Solutions_Manual.pdf)
- 💻 [Midterm LaTeX Sources](sources/examinations/midterm2.tex)

### End-Semester Examination
- 📄 [PH7302E Endterm Question Paper (PDF)](examinations/endterm/PH7302E_Endterm_Question_Paper.pdf)
- 📝 [PH7302E Endterm Solutions Manual (PDF)](examinations/endterm/PH7302E_Endterm_Solutions_Manual.pdf)
- 💻 [Endterm LaTeX Sources](sources/examinations/PH7302E_Endterm_Question_Paper.tex)

---

## 📂 Repository Architecture

```text
PH7302-NITC-Physics/
├── README.md                                          # Master hyperlinked course guide and index
├── .gitignore                                         # Build and credential ignore rules
├── syllabus/
│   └── PH7302_Condensed_Matter_Physics_Syllabus.pdf   # Official 39-session lecture syllabus
├── notes/
│   ├── PH7302_Module1_Crystal_Physics_Student_Copy.pdf
│   ├── PH7302_Module1_Crystal_Physics_Worked_Solutions.pdf
│   ├── PH7302_Module2_Lattice_Vibrations_and_Thermal_Properties_Student_Copy.pdf
│   ├── PH7302_Module3_Free_Electron_Theory_Student_Copy.pdf
│   ├── PH7302_Module4_Energy_Band_Theory_and_Semiconductors_Student_Copy.pdf
│   ├── PH7302_Module5A_Magnetism_Student_Copy.pdf
│   └── PH7302_Module5B_Dielectrics_Ferroelectrics_Optical_Properties_Student_Copy.pdf
├── examinations/
│   ├── midterm/
│   │   ├── PH7302_Midterm_Question_Paper.pdf
│   │   └── PH7302_Midterm_Solutions_Manual.pdf
│   └── endterm/
│       ├── PH7302E_Endterm_Question_Paper.pdf
│       └── PH7302E_Endterm_Solutions_Manual.pdf
└── sources/
    ├── module1/                                       # LaTeX source & 6 TikZ vector figures
    │   ├── module1_student_copy.tex
    │   ├── module1_student_copy_sol.tex
    │   └── figures/
    ├── module2/
    │   └── module2_student_copy.tex
    ├── module3/
    │   └── module3_student_copy.tex
    ├── module4/
    │   └── module4_2_final.tex
    ├── module5A/
    │   └── module5_student_copy.tex
    ├── module5B/
    │   └── module5b_student_copy.tex
    └── examinations/
        ├── midterm2.tex
        ├── midterm2_sol.tex
        ├── PH7302E_Endterm_Question_Paper.tex
        └── PH7302E_Endterm_Solutions_Manual.tex
```

---

## 📖 Recommended Textbooks & References

1. **Charles Kittel**, *Introduction to Solid State Physics*, 8th Edition, John Wiley & Sons (Primary Text).
2. **Neil W. Ashcroft and N. David Mermin**, *Solid State Physics*, Cengage Learning (Comprehensive Reference).
3. **J. R. Christman**, *Fundamentals of Solid State Physics*, John Wiley & Sons.
4. **J. R. Hook and H. E. Hall**, *Solid State Physics*, 2nd Edition, Manchester Physics Series, John Wiley & Sons.
5. **M. Ali Omar**, *Elementary Solid State Physics: Principles and Applications*, Pearson.
6. **A. J. Dekker**, *Solid State Physics*, Macmillan India.

---

## ⚙️ Building from LaTeX Source

All notes and question papers can be compiled directly from the `sources/` directory using standard TeX Live (2022 or later) with `pdflatex`:

```bash
# Clone the repository
git clone https://github.com/physicistlk/PH7302-NITC-Physics.git
cd PH7302-NITC-Physics

# Example: Compile Module 1 Student Notes
cd sources/module1
pdflatex -interaction=nonstopmode module1_student_copy.tex
pdflatex -interaction=nonstopmode module1_student_copy.tex
```

---

*Curated for students and scholars of Condensed Matter Physics at the National Institute of Technology Calicut.*
