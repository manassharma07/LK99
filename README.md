# Structure files of LK99 and related materials (CIFs & POSCARs)
This repo provides the structure files of LK99 and related materials reported in the literature. Hopefully, it will be useful to Computational Material Scientists.

The discovery of [room-temperature superconductivity at ambient pressure in Cu-substituted apatite](https://arxiv.org/abs/2307.12008) (‘LK99’) has sent shockwaves through the scientific community. Social media platforms are abuzz with discussions, and experimentalists and theoreticians alike are diving headfirst into unraveling the secrets of this remarkable phenomenon.

As a computational materials scientist, I understand the excitement and the challenges that come with starting your own exploration. One common hurdle is obtaining accurate starting structures for simulations or modeling real materials for your own Density Functional Theory (DFT) simulations. But worry not! I've done some legwork to make your journey smoother.

In this blog post, I share a collection of CIF and POSCAR files containing the reported structures (atomic coordinates and lattice parameters) of the LK99 material to date. I hope to save you from the hassle of searching the literature, downloading supplementary PDFs, and manually extracting data. Therefore, I provide you with a one-stop solution.

Let's save time and effort together!

## LK99

Apatites are materials with the general formula $A_{10}(TO_{4})_{6} X_(2 \pm x)$, where A = alkaline or rare earth metal; T = Ge, Si, or P; and X = halide, O, or OH [1]. Lk99 is supposed to be a copper (Cu) doped Lead Apatite with the formula Pb9CuP6O25 or Pb9Cu(PO4)6O [2]. The undoped form is Pb10(PO4)6O. So essentially, a Pb atom is replaced/doped with the Cu atom in LK99.

A study from India was able to synthesize the Cu-doped Lead Apatite from the precursors: Cu3P and Pb2SO5 [3]. Their experimental x-ray diffraction pattern indeed matched well with the theoretical structure obtained by DFT optimization. [3]

## Reported Structures

### 1. Origin of correlated isolated flat bands in copper-substituted lead phosphate apatite
**Author**: [Sinéad M. Griffin](https://twitter.com/sineatrix)
**Link**: [https://arxiv.org/abs/2307.16892](https://arxiv.org/abs/2307.16892)

#### Structures provided in the Supporting Information:
**CIFs:**
1. [LK99-Pb9P6CuO25_Cu_on_Pb(1)](https://github.com/manassharma07/LK99/blob/main/Griffin_arxiv/LK99-Pb9P6CuO25_Cu_on_Pb(1).cif) (page 12) (This is the actual LK99 material as the simulated XRD pattern compares well with [3])
2. [LK99-Pb9P6CuO25_Cu_on_Pb(2)](https://github.com/manassharma07/LK99/blob/main/Griffin_arxiv/LK99-Pb9P6CuO25_Cu_on_Pb(2).cif) (page 13) (Cu substitution on Pb(2) does not result in flat bands so it is not probably LK99)
3. [LK99-Pb9P6CuO26H2_Cu_on_Pb(1)](https://github.com/manassharma07/LK99/blob/main/Griffin_arxiv/LK99-Pb9P6CuO26H2_Cu_on_Pb(1).cif) (page 11) (This is also a candidate for LK99 but with a slightly different formula)
4. [LK99-Pb9P6CuO26H2_Cu_on_Pb(2)](https://github.com/manassharma07/LK99/blob/main/Griffin_arxiv/LK99-Pb9P6CuO26H2_Cu_on_Pb(2).cif) (page 12) (Again, Cu substitution on Pb(2) is not useful)

**POSCARs:**

### 2. First-principles study on the electronic structure of Pb10−xCux(PO4)6O (x = 0, 1)
**Authors**: Junwen Lai, Jiangxu Li, Peitao Liu, Yan Sun, Xing-Qiu Chen
**Link**: [https://doi.org/10.1016/j.jmst.2023.08.001](https://doi.org/10.1016/j.jmst.2023.08.001)

#### Structures provided in the Supporting Information:
**CIFs:**
1. [Lead_apatite_undoped-Pb10P6O25](https://www.bragitoff.com/wp-content/uploads/2023/08/Lead_apatite_undoped-Pb10P6O25.cif) (This is the undoped or pure lead apatitie. Substituting one Pb here with Cu results in LK99)
2. [LK99-Pb9P6CuO25_Lai](https://www.bragitoff.com/wp-content/uploads/2023/08/LK99-Pb9P6CuO25_Lai.cif) (This is the Cu substituted lead apatitie. This has the same formula as LK99 but with slightly different lattice parameters than reported by [1])
3. [Pb9P6AuO25_Lai](https://www.bragitoff.com/wp-content/uploads/2023/08/Pb9P6AuO25_Lai.cif) (Au doped Lead Apatite)
4. [Pb9P6NiO25_Lai](https://www.bragitoff.com/wp-content/uploads/2023/08/Pb9P6NiO25_Lai.cif) (Ni doped Lead Apatite)
5. [Pb9P6ZnO25_Lai](https://www.bragitoff.com/wp-content/uploads/2023/08/Pb9P6ZnO25_Lai.cif) (Zn doped Lead Apatite)
6. [Pb9P6AgO25_Lai](https://www.bragitoff.com/wp-content/uploads/2023/08/Pb9P6AgO25_Lai.cif) (Ag doped Lead Apatite)

**POSCARs:**
1. [Lead_apatite_undoped-Pb10P6O25](https://www.bragitoff.com/wp-content/uploads/2023/08/Lead_apatite_undoped-Pb10P6O25.poscar)
2. [LK99-Pb9P6CuO25_Lai](https://www.bragitoff.com/wp-content/uploads/2023/08/LK99-Pb9P6CuO25_Lai.poscar)
3. [Pb9P6AgO25_Lai](https://www.bragitoff.com/wp-content/uploads/2023/08/Pb9P6AgO25_Lai.poscar)
4. [Pb9P6AuO25_Lai](https://www.bragitoff.com/wp-content/uploads/2023/08/Pb9P6AuO25_Lai.poscar)
5. [Pb9P6NiO25_Lai](https://www.bragitoff.com/wp-content/uploads/2023/08/Pb9P6NiO25_Lai.poscar)
6. [Pb9P6ZnO25_Lai](https://www.bragitoff.com/wp-content/uploads/2023/08/Pb9P6ZnO25_Lai.poscar)

### 3. Structures of Precursors (Cu3P and Pb2SO5)
**Source**: [MaterialsProject](https://next-gen.materialsproject.org/)

**(a) Cu3P** ([mp-7463: Cu3P (Hexagonal, P6_3cm, 185)](https://next-gen.materialsproject.org/materials/mp-7463?formula=Cu3P))
- **CIF**: [Cu3P_P63cm_mp-7463](https://github.com/manassharma07/LK99/blob/main/Precursors/Cu3P_P63cm_mp-7463.cif)

**(b) Pb2SO5** ([mp-21497: Pb2SO5 (Monoclinic, C2/m, 12)](https://next-gen.materialsproject.org/materials/mp-21497?formula=Pb2SO5))
- **CIF**: [Pb2SO5_mp-21497](https://github.com/manassharma07/LK99/blob/main/Precursors/Pb2SO5_mp-21497.cif)

## References:
[1] [2307.16892] [Origin of correlated isolated flat bands in copper-substituted lead phosphate apatite](https://arxiv.org/abs/2307.16892)

[2] [LK-99 - Wikipedia](https://en.wikipedia.org/wiki/LK-99)

[3] [2308.03544] [Absence of superconductivity in LK-99 at ambient conditions](https://arxiv.org/abs/2308.03544)
