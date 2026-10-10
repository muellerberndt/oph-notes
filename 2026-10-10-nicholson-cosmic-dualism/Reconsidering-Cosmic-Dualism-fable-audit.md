# Audit of "Reconsidering Cosmic Dualism: A Two-Realm Framework"

Audited document: *Reconsidering Cosmic Dualism copilot.pdf* (John Glen Nicholson, Information Physics Institute, 55 pages, created 2026-10-10 from Microsoft Word). Page numbers below refer to that PDF.

Deliverables of this audit:

- `Reconsidering Cosmic Dualism-fable.md`: the corrected paper in Markdown, figures in `figures/`.
- `Reconsidering Cosmic Dualism-fable.pdf`: the corrected paper rendered in the original layout (Letter, 1-inch margins, Times New Roman 12 pt, bold-italic section headings, cover page, table of contents with page numbers, figures with captions, numbered references).
- `Reconsidering Cosmic Dualism-fable-audit.md` and `.pdf`: this report.

Method: every factual statement, equation, name, number and reference in the original was checked against the primary literature; 16 references were verified by web lookup (Greene et al. 2026, Jeon et al. 2026, Levin 2025, Komberg et al. 1996, DESI DR2, Shankar et al. 2009, ALPHA 2023, Popławski 2010, Renou et al. 2021, the CMB temperature history, the neutron lifetime measurements, Socas-Navarro 2019, Wu et al. 2015, and the Einstein, Bohm–Hiley and Marletto–Deutsch quotations). The framework's own hypotheses were left in place and labeled as hypotheses; statements that conflict with measurements were corrected; the reference list was rebuilt from 65 entries (with 4 duplicates, 2 empty, 1 truncated, 11 uncited) to 147 complete entries numbered in order of first citation.

## 1. Summary

The paper's central ideas (a paired antimatter realm with reversed time, singularities as transitions, dark matter and dark energy as the visible effects of the partner realm, information conserved across the pair, a cyclic flip) are preserved. Three of the paper's quantitative claims conflict with measurements and were rewritten: the dark-matter budget is not produced by black-hole processing over cosmic time; annihilation of matter and antimatter did occur; gravitational-wave detectors do not measure dark-matter density. Two equations were dimensionally or algebraically wrong and were replaced by their standard forms. Fourteen factual slips (names, particle content, instrument physics, history) were corrected. The reference list was repaired. A new Section 15 states the postulates as equations and places each next to the measurement that constrains it, which is the test the original paper (p. 6) says a strong version of the argument needs.

## 2. Claims that conflict with measurements

| Page | Original claim | Finding | Revision |
|---|---|---|---|
| 24–25 | "There was a 1:1 ratio [matter:antimatter] to begin with and this increased over time to the 5:1 ratio we observe today", driven by ordinary matter transitioning to dark matter through black holes (also pp. 45, 49). | Planck's acoustic peaks require Ω_c h² = 0.120 against Ω_b h² = 0.0224, a 5.4:1 dark-to-baryonic ratio, at z ≈ 1100, before any stellar black hole existed. The local black-hole mass density is (2–10) × 10⁵ M☉ Mpc⁻³ against a dark-matter density of 3.3 × 10¹⁰ M☉ Mpc⁻³: black holes have processed about 10⁻⁵ of the dark mass. | Section 8 and Section 15 state that the separation into the dark frame was complete at the flip and that black-hole transfer is a 10⁻⁵ correction (postulate P6). The corrected model predicts a constant dark-to-baryonic ratio since the flip, which the constancy of cluster baryon fractions supports. |
| 25 | "After all, there is no evidence for any annihilation events." | The 1.6 × 10⁹ photons per baryon in the microwave background (η ≈ 6.1 × 10⁻¹⁰) are the relic of near-total annihilation; the Sakharov conditions are needed to explain the survivors. | Section 8 gives the standard account and the model's reading (the partner separated into U⁻ before annihilation). Section 13 removes "annihilate rarely". |
| 26 | "We can now detect dark matter relative density in gravitational waves thanks to the LIGO collaboration [31]." | False. LIGO/Virgo constrain some candidates (primordial black holes) through the merger population; no dark-matter density is measured. | Rewritten with Carr and Kühnel (2020). |
| 13 | "Λ increases over time as we will show later." No derivation follows. | DESI DR2 (2025) with CMB and supernovae prefers w₀ ≈ −0.75, w_a ≈ −0.86 (DES-Y5 combination): dark-energy density rose until z ≈ 0.4 and declines since, 2.8–4.2σ from constant Λ depending on the supernova sample. | Stated as Hypothesis H-Λ; Table 15.1 records that the sign matches before z ≈ 0.4 and that the model needs a turnover after it. |
| 13 | Antimatter "is anti-gravitating but moving backwards in time, thus appearing to gravitate normally", citing a news item. | ALPHA measured (0.75 ± 0.13 ± 0.16) g for antihydrogen and excluded repulsion (Anderson et al., Nature 621, 716, 2023). | Primary source cited; the reading is kept as a hypothesis and Table 15.1 notes it predicts exactly g, so no precision measurement can support it. |
| 33 | "There is an observed symmetry between the anti-gravity force and the magnetic force. We can all see that for ourselves with magnetic levitation trains." | Maglev is magnetic repulsion or flux pinning; it is unrelated to gravity. | Sentence removed; the symmetry is kept as a hypothesis with "no observation supports it at present". |
| 32 | "Electrons are pulled into the cube by strong force but are pushed out to a distance by the weak nuclear force." | Electrons do not feel the strong force; they are bound electromagnetically and kept at a distance by the uncertainty relation and the exclusion principle. | Corrected. |
| 23 | "The weak force is considered weak because of the moderating stronger Strong nuclear force"; strong and weak ranges "the size of an atom". | The weak force is weak at low energy because the W and Z bosons are heavy (80 and 91 GeV); its range is about 10⁻¹⁸ m. The strong force acts on the nuclear scale, 10⁻¹⁵ m, five orders of magnitude below an atom. | Corrected; the gravity-moderated-by-anti-gravity claim is labeled a hypothesis. |
| 5, 37 | "The unknown process of neutron decay." | Free neutron decay is described by the weak interaction (d → u + W⁻ → u + e⁻ + ν̄_e). The open problem is the 4σ gap between beam (887.7 ± 2.2 s) and bottle (877.75 ± 0.3 s) lifetimes. | Problem list item 18 and Section 11 rewritten; the lifetime gap is offered in Section 15 as the model's cheapest test. |
| 5, 37 | Ultraluminous X-ray sources listed as of unknown origin. | Most are super-Eddington accretion onto neutron stars and black holes (Bachetti et al., Nature 514, 202, 2014). | Removed from the problem list; one sentence in Section 11. |
| 45 | "The CMB was predicted to be 50 Kelvin but was recorded as 3 Kelvin ... This discrepancy can be explained by the antimatter that had already shifted away." | Alpher and Herman predicted about 5 K in 1948; 50 K was a later Gamow estimate; the measured value is 2.7255 K. The early estimates differed because the baryon density and expansion history were unknown. The discrepancy carries no information about antimatter. | History corrected; inference removed. |
| 36 | "Galaxies are generally spherical." | Galaxies are disks and ellipsoids. | Corrected. |
| 16 | Electrons "orbiting the nucleus ... at light speed". | Orbital speeds are of order αc ≈ c/137. | Corrected. |
| 19 | Atomic clocks "work by atomic decay". | They run on the caesium hyperfine transition. | Corrected. |
| 35 | "The flatness problem is that galaxy distribution is uniform." | That is the horizon problem. The flatness problem is Ω_k = 0.0007 ± 0.0019 (Planck 2018). | Both problems defined correctly in Section 11; the model's readings kept. |
| 37 | UHECR "ankle energy ... roughly 10¹⁹ eV". | The ankle is near 5 × 10¹⁸ eV. | Corrected; the Auger dipole and starburst correlation are added as what the focal-point hypothesis must reproduce. |
| 48 | "Thanks to Reinhard Genzel and Andrea Ghez we now know that supermassive black holes exist, they observed Sagittarius A directly." | Their groups tracked stellar orbits around Sgr A*; the shadow was imaged by the EHT in 2022. | Corrected. |
| 48 | M–σ relation attributed to Minkowski (1962) and described as "dispersion velocities that are developed between them". | The relation is between black-hole mass and the stellar velocity dispersion of the host bulge (Ferrarese and Merritt 2000; Gebhardt et al. 2000). Minkowski 1962 is an early dispersion measurement. | Corrected; Minkowski kept for the measurement history. |
| 48 | "Anisotropy observed at the largest scales ... is explained." | Whether large quasar groups violate homogeneity is disputed; Nadathur (2013) shows the largest is consistent with random fluctuations. | "Explained" changed to "addressed"; Section 15 asks for a statistic. |
| 27 | Oppoverse fluid "surface tension keeps the dark matter particles from contacting ordinary matter"; Section 14 ejects dark matter from black holes "at light speed". | Dark matter passes through colliding clusters with σ/m below 1.25 cm² g⁻¹ (Randall et al. 2008), and the Lyman-α forest excludes a thermal relic lighter than 5.3 keV (Iršič et al. 2017); relativistic ejecta would be hot dark matter. | Both constraints stated in Sections 9, 14 and Table 15.1. |

## 3. Internal contradictions

| Page | Contradiction | Revision |
|---|---|---|
| 43–44 | "There is no need for inflation." followed by "The most satisfying explanation for inflation is that a torsion was applied to a seed." | "There is no inflaton field in this picture. The rapid early expansion is the release of torsion." Popławski's Einstein–Cartan bounce (Phys. Lett. B 694, 181, 2010; ApJ 832, 96, 2016) is cited as the existing mathematics for this idea. |
| 13 | ρ_vac = P⁻V⁻ = P⁺V⁺ = Λ/κ = −ρ_vac. A pressure-volume product (energy) is equated to an energy density, and ρ = −ρ forces ρ = 0. | Replaced by ρ_Λ = Λc⁴/(8πG) ≈ 5 × 10⁻¹⁰ J m⁻³, p_Λ = −ρ_Λ, with P4 identifying the pressure-volume products separately. |
| 28 | F_gc = −∇Λ + ∇ × F_g. Λ is a constant, so ∇Λ = 0; the Newtonian field is a gradient, so ∇ × F_g = 0. Both terms vanish identically. | Replaced by the gravitoelectromagnetic decomposition of the weak-field limit (Mashhoon 2003) with the Λ term: F = m[−∇Φ + (Λc²/3) r + v × B_g]. This is the author's "gravity and anti-gravity like E and B" made exact. |
| 13 | "For U⁺ then E = Mc² ≠ Info. For U⁻ then E + Mc² = Info_total." Energy equated to information with no conversion constant. | Postulate P5: ε_I I⁻ = E⁻ + M⁻c², ε_I an energy per bit, with Landauer and Vopson as candidate scales. |
| 50 | "We may have reached a limit in our ability to continue to use math" followed two paragraphs later by the demand for a coherent mathematical model. | The first paragraph now says that physics is not mathematics alone and that error bars limit what mathematics can claim; the demand for the model stands. |
| 15 | A paragraph discusses "the record-player example" that no longer appears in the text. | A two-sentence record example restored before the caveat. |
| 10 | "the three quarks (down, down, up) that form protons and neutrons" as the example of a stable particle. | udd is the neutron, which is unstable; the proton is uud. Corrected. |
| 10 | "gravity is the action and entropy is the reaction per Newtons 2nd law." | Third law. Corrected. |

## 4. Factual slips corrected

- Ernst Mach (not "Ernest"); Roger Penrose (not "Robert", refs 21 and 51); Glashow (not "Glasgow"); Peskin (not "Peskinn"); Ratra (not "Rhatra"); Brandenberger (not "Brandenburger"); Parampreet Singh (not "Parampree"); Jamie S. Farnes (not "Jaime"); Schwarzschild (not "Schwarzchild").
- Schwarzschild published his solution in 1916 (Sitzungsberichte, pp. 189–196) and died that year; "Einstein collaboration, unpublished 1916-1920" is wrong.
- The Klein bottle is Felix Klein's 1882 surface. Kaluza–Klein theory is Oskar Klein's 1926 five-dimensional theory. Page 26 conflates them ("Klein also proposed a 3d+1 equivalent as the surface of a Klein bottle"); Kaluza–Klein is five-dimensional, string theory is ten-dimensional.
- Émilie du Châtelet did not "empirically prove that energy is conserved"; she argued from 's Gravesande's collision experiments that the conserved quantity is proportional to mv².
- Dirac did no experiments; the three-polarizer discussion is in *The Principles of Quantum Mechanics* (1930), not in the 1939 notation paper.
- "Black holes create an Einstein-Rosen bridge, just as they hypothesized": Einstein and Rosen (1935) were modeling particles; the bridge as a feature of the extended Schwarzschild geometry is Kruskal (1960), and its non-traversability is Fuller and Wheeler (1962).
- Noether's theorem associates a conserved quantity with each continuous symmetry of the action; the original "if differentiable symmetry exists in a quantity than that quantity was conserved" is garbled.
- Spin is intrinsic angular momentum; chirality and helicity are distinct. The original "spin ... does not describe its movement or angular velocity" is kept as the model's geometric reading, with the standard meaning stated.
- Dark matter was inferred by Zwicky (1933) and Rubin and Ford (1970), before the CMB-smoothness argument (Peebles 1982); the original attributes its origin to the CMB argument.
- Superposition of large molecules (25 kDa) has been observed (Fein et al. 2019); "there is no evidence for superposition as fundamental" is replaced by the decoherence account, which is compatible with the Bohmian reading the paper adopts.
- "Many Worlds theory, perhaps SM-theory" (p. 8): "SM-theory" is undefined; read as string theory (M-theory) and rewritten.
- Electroweak symmetry breaks when the Higgs field acquires its value at about 160 GeV; the strong force is present throughout and its confinement transition (about 150 MeV) is a separate, later event. The original has electroweak symmetry breaking "when things cool down enough for the strong force to emerge".
- Decoupling at "379,000 years" kept (Planck: about 378,000 years).
- Deceleration-to-acceleration transition: about six billion years ago (z ≈ 0.6–0.7), not five.
- The quasar record cited through a news item: the ten-billion-solar-mass claim is Wu et al. (Nature 518, 512, 2015, 1.2 × 10¹⁰ M☉ at z = 6.30); the news item concerned Wang et al. 2021 (1.6 × 10⁹ M☉ at z = 7.64).

## 5. Citation problems

| Original ref | Problem | Resolution |
|---|---|---|
| 2 "Bayesian Analysis" | Empty entry, never cited. | Dropped. |
| 5 Everett, Wheeler, and Dewitt 1973 | The 1973 book is edited by DeWitt and Graham; Everett's paper is 1957. | Both cited. |
| 7 and 43 | Duplicate (Marletto and Deutsch 2015). | Merged; Deutsch 2013 added for the quoted idea. |
| 9 Greene et al. 2026 | Verified: Phys. Rev. D 113, 063576 (2026), arXiv:2511.23447. | Kept; arXiv id added. |
| 12 and 31 | Duplicate; title has "spin-processing" for "spin-precessing"; used on p. 26 for a false claim. | Title fixed; discovery paper (PRL 116, 061102) added; the p. 26 use replaced. |
| 14 Schwarzschild "unpublished 1916-1920" | Wrong. | Replaced by the 1916 paper. |
| 15 Castelvecchi, Nature news | News item for a primary result. | Replaced by Anderson et al. (ALPHA), Nature 621, 716 (2023). |
| 18 Burk, "Remembering Grace Murray Hopper" | Never cited; the nanosecond illustration it supported is absent. | Dropped. |
| 19 Lee et al., "Exact post-selection inference with the lasso" | A statistics paper on the lasso, unrelated to quantum post-selection. | Replaced by Aharonov, Albert and Vaidman (1988) and Aharonov, Bergmann and Lebowitz (1964). |
| 20.2 "Maudlin" | Incomplete. | Maudlin, *Quantum Non-Locality and Relativity*, 3rd ed. (2011). |
| 21 Penrose 1989 | Cited for "the smoothing mechanism of a bouncing cyclic Universe theory", which is not in that book. | Penrose, *Cycles of Time* (2010) and Steinhardt and Turok (2002) cited for the bounce; 1989 kept for the Gödel argument. |
| 25 | Duplicate of 20. | Merged. |
| 26 "Wheeler, John. Dewitt, Bryce. Quantum Theory of Gravity" | That paper is by DeWitt alone and does not contain the quotation. "Spacetime tells matter how to move..." is from Wheeler and Ford, *Geons, Black Holes, and Quantum Foam* (1998). | Corrected. |
| 33 Kaluza and Klein 1926 | The 1926 Nature paper is Klein's alone; Kaluza's paper is 1921. | Both cited. |
| 36 Dirac 1939 | Wrong source for the polarizer discussion. | Dirac 1930. |
| 47 "Smollen" | Empty; cited for "the central configuration". The context (universe natural selection, genetic algorithms) points to Lee Smolin, *The Life of the Cosmos* (1997). | Smolin 1997 cited for cosmological natural selection; the "central configuration" sentence now stands without a citation. Author to confirm. |
| 49 Planck "Reveals an Almost Perfect Universe" | Press release. | Planck 2018 results VI (A&A 641, A6). |
| 52 "A. Einstein and N. Ros" | Truncated duplicate of 46. | Replaced by Kruskal 1960 and Fuller and Wheeler 1962. |
| 56 van Marle et al. | Conference paper cited for the Eddington limit. | Kept; Eddington 1926 added. |
| 57 Maldacena 2003 | Cited for AdS/CFT in general. | Maldacena 1998 added. |
| 58 "Ghez and Genzel ... 2008" | Genzel is not an author of Ghez et al. 2008. | Ghez et al. 2008 and Gillessen et al. 2009 cited; EHT 2022 added. |
| 59 Komberg et al. "1998" | MNRAS 282, 713 (1996); arXiv:astro-ph/9602090. | Year corrected; Clowes et al. 2013 and Nadathur 2013 added. |
| 60 Minkowski 1962 | Not the M–σ relation. | Ferrarese and Merritt 2000, Gebhardt et al. 2000, Kormendy and Ho 2013 added. |
| 61 Temming, Science News 2021 | News item; the number in the text (10¹⁰ M☉) belongs to a different object. | Wu et al. 2015 and Wang et al. 2021. |
| 64 Weinberg, *Dreams of a Final Theory* | Never cited. | Dropped. |
| 65 Levin 2025 | URL broken by a space; verified as PsyArXiv, doi:10.31234/osf.io/5g2xj. | Corrected. |
| 17, 26.1, 27.1, 41.1, 49.1, 55, 8.1, 20.1 | Listed but never cited in the text. | Cited where relevant (Heisenberg in Section 6; Ashtekar in Section 13; Peebles and Ratra in Section 8; Swartz in Section 11; Brandenberger in Section 1; Bueno Sánchez in Section 13; Morgan in Section 3; Bell in Sections 6 and 7). |
| p. 6, Bohm and Hiley quotation | The exact sentence could not be found in the cited book or in Hiley's papers. | Converted to a paraphrase with the citation. Author to supply the page number if a verbatim quotation is wanted. |
| p. 8, Marletto and Deutsch quotation | Not verbatim; matches a popular paraphrase of Deutsch's 2013 principle. | Converted to a paraphrase citing Deutsch 2013 and Deutsch and Marletto 2015. |
| p. 7, Einstein quotation | Attributed in quotation collections to Viereck, *Glimpses of the Great* (1930); the remark is also recorded for 1927 in Kessler's diary. Not in the Saturday Evening Post interview. | Cited to Viereck with the Kessler note. |

New references added (not in the original): Alpher and Herman 1948; Ashtekar et al. 2006 (now cited); Auger 2017, 2018; Bachetti 2014; Bahé 2021; Blandford and Znajek 1977; Bohm 1952; Bousso 2002; Boyle, Finn and Turok 2018; Bromm and Loeb 2003; Bush 2015; Carr and Kühnel 2020; Clowe 2006; Clowes 2013; Couder 2005; Cruz 2005; DESI DR2 2025; Deutsch 2013; Eddington 1926; EHT 2022; Everett 1957; Fein 2019; Ferrarese and Merritt 2000; Feynman 1960; Fixsen 2009; Fuller and Wheeler 1962; Gamow 1961; Gebhardt 2000; Gillessen 2009; Glashow 1961; Gödel 1931; Gott and Li 1998; Guth 1981; Hawking 1975; Iršič 2017; Kaluza 1921; Klein F. 1882; Klein O. 1926; Kormendy and Ho 2013; Kruskal 1960; Landauer 1961; Li 2022; LIGO 2016 (PRL); Lynden-Bell 1969; Madau and Dickinson 2014; Maldacena 1998; Mashhoon 2003; Matthee 2024; Nadathur 2013; Oppenheimer and Snyder 1939; Pacucci 2023; Peebles 1982; Penrose 1965, 2010; Planck 2013, 2018; Popławski 2010, 2016; Randall 2008; Renou 2021; Rindler 2006; Robertson 2021; Rubin and Ford 1970; Sakharov 1967; Salam 1968; Schrödinger 1935; Schwarzschild 1916; Shankar 2009; Smolin 1997, 2006; Socas-Navarro 2019; Sołtan 1982; Steinhardt and Turok 2002; Steinhauer 2016; Susskind 1995; 't Hooft 1993; UCNτ 2021; Viereck 1930; Wang 2021; Weinberg 1967, 1989; Wheeler and Ford 1998; Wu 2015; Yue 2013; Zurek 2003; Zwicky 1933.

## 6. Unsupported assertions kept as labeled hypotheses

These are the paper's own ideas. They are kept, named, and placed where the reader can see what would test them: time-reversed antimatter that appears to gravitate normally (H-antimatter, Section 5); Λ growing with time (H-Λ, Section 5); the neutrino as information carrier and complete record of the past (H-ν, Section 6); hot antimatter in superposition (Section 8); negative-curvature dark matter visible only at focal points (Section 11); the chirality reading of neutron decay (Section 11); gravito-strong and Λ-magnetic symmetries (Section 10); the clogged-throat reading of quasars, gamma-ray bursts and jets (Section 14); halos filled by black-hole ejecta and filaments as hydraulic pistons (Section 14); the torsion-release origin of the early expansion (Section 13); the recycling event within a few billion years (Section 13, stated as parameter-dependent since no calculation was given).

Two statements were removed because nothing in the paper or the literature supports them and they carry no model content: "This crystal object was strangely on the same scale as human beings in positive space" (p. 43), and "Prime numbers and their properties may not be a coincidence with this line of thinking" (p. 17).

## 7. Editorial changes

- Sentence fragments and broken sentences repaired: "Maintains the law." (p. 10); "Illustration of neutron stream collided with other objects as back reaction." (p. 19); "Universe natural selection, genetic algorithms." (p. 18); "Simultaneity." (p. 23); "Relativistic, perhaps find the equivalent vector field..." (p. 29); "There is no further. / annihilation from this point on" (pp. 45–46); "Bubble constructs shape the design of the / Dualverse, soap bubbles..." (p. 27); "self-similarity at different scales and scale invariant, and we would expect..." (p. 39).
- Rhetorical asides removed: "He was right." / "She was right." (seven occurrences); "Every culture on Earth accepts the idea ... It would be arrogant of us not to consider this as important." (p. 7); "None of this is a radical idea when you consider some of the strangest theories of physics that have already been proven." (p. 8); "and possibly much more!" (p. 6); "Understanding why that is, is what more cosmologists should be thinking about." (p. 17).
- The p. 17 sentence on scientists never reporting an exact amount rewritten as "No measurement reports an exact value."
- The string-theory objection (p. 17) rewritten in one sentence with a citation (Smolin 2006).
- Figure labels unified as "Figure N.M" (the original mixes Abstract, Image, Diagram, Chart, Graph); numbering preserved so that cross-references survive, including the gap at 12.1 (Table 12.1). Third-party image credits kept in captions. Diagram 13.3 credits (Kriger, Austin, Pascher) kept.
- "Backpropagation" in the keywords and the Figure 7.1 caption changed to "back-reaction"; the original word is a machine-learning term.
- "Sagittarius A" corrected to "Sagittarius A*"; "dual-verse" to "Dualverse"; "neurotology" read as "neurology"; "Goedel" to "Gödel".
- The Feynman "plenty of room at the bottom" quotation closed and attributed.
- Section 13's "This theory works on a 10-dimensional string theory landscape" replaced by a pointer to the higher-dimensional construction of Greene et al. 2026, which is the only such construction the paper cites.
- Page numbers added at the foot of each page (the original has none; its table of contents refers to page numbers nonetheless).
- "The relation between the period of relativistic jets and their accretion disks" (problem 13) shortened to "relativistic jets and their accretion disks"; no periodicity claim is made anywhere in the text.

## 8. Additions

- Section 15 (new): postulates P1–P6 and hypotheses H-Λ, H-ν as equations; Table 15.1 with ten measurements; three explicit falsifiers; one prediction of the corrected model (constant dark-to-baryonic ratio since the flip).
- Section 5: the Newtonian limit with Λ, a(r) = −GM/r² + (Λc²/3) r, as the exact content of "anti-gravity pushes outward" (Rindler 2006), and the gravitoelectromagnetic decomposition (Mashhoon 2003) as the exact content of "gravity and anti-gravity like electric and magnetic fields".
- Section 6: the two-state vector formalism and weak values as the correct home of the "negative probability" idea; Renou et al. 2021 for the role of complex numbers; Zurek 2003 and Fein 2019 for decoherence and large-molecule interference.
- Section 7: walking-droplet pilot-wave hydrodynamics (Couder 2005; Bush 2015) as a physical system with the two-way wave–particle coupling the paper postulates.
- Section 13: Einstein–Cartan torsion cosmology (Popławski 2010, 2016) as existing mathematics for the torsion bounce and for a universe born inside a black hole; loop quantum cosmology (Ashtekar 2006) as a second bounce mechanism.
- Section 14: JWST overmassive black holes (Pacucci 2023) and the z > 6 ten-billion-solar-mass quasars (Wu 2015; Wang 2021) as observations in the direction of the paper's "black hole before halo" claim; Penrose's Weyl curvature hypothesis (1979) as the standard statement of the low-entropy puzzle.
- Abstract: one sentence naming the constraints in Section 15.

## 9. Figure permissions

Before publication the following third-party images need a licence or replacement: Figure 4.1 (Gott model, "Wikipedia": the file and its licence must be identified); Figures 4.2 and 9.3 (Bazett, *The beautiful geometry of bubbles*); Figure 9.1 (ESA/Springel et al./Virgo Consortium, and the bubble-cluster photograph credited to Lawrence Lawry/Science Source, which is a stock agency); Figure 8.1 (the pie chart, source not stated, probably ESA/Planck). The author's own drawings (3.1, 5.1, 6.1–6.3, 7.1, 8.2, 9.2, 10.1–10.3, 11.1–11.3, 12.2, 13.1–13.3, 14.1) are unaffected.

## 10. Decisions left to the author

1. Whether to keep Figure 8.1 with Planck 2013 values or redraw it with Planck 2018 values (68.5 / 26.5 / 4.9).
2. Whether "Smollen" (old ref 47) was Lee Smolin; if another author was meant, the "central configuration" sentence needs its source.
3. The charge bookkeeping across the transition (electrons becoming positrons, Section 14) is flagged as open in Sections 14 and 15; a rule is needed.
4. Whether to commit, in Table 15.1, to the beam or the bottle neutron lifetime. The model gains its first quantitative prediction by doing so.
5. The Bohm–Hiley sentence: supply a page reference to restore it as a verbatim quotation.
6. Diagram 13.3 names three collaborators; an acknowledgements line would be the usual place for them.

## 11. Reference renumbering (original number to new number)

| Original | Entry | New number(s) |
|---|---|---|
| 1 | Feynman, The Character of Physical Law | 1 |
| 2 | "Bayesian Analysis" (empty) | dropped |
| 3 | Mach 1883 | 3 |
| 4 | Bohm and Hiley 1993 | 4 |
| 5 | Everett, Wheeler and DeWitt 1973 | 5, 6 |
| 6 | Higgs 1964 | 8 |
| 7 | Marletto and Deutsch 2015 | 10, 9 |
| 8 | Croom 1989 | 11 |
| 8.1 | Morgan 2016 | 12 |
| 9 | Greene, Kabat, Levin, Porrati 2026 | 13 |
| 10 | du Châtelet 1740 | 15 |
| 11 | Boyle and Turok 2021 | 17, 16 |
| 12 | LIGO/Virgo PRX 2016 | 20, 19 |
| 13 | EHT 2019 | 21 |
| 14 | Schwarzschild "unpublished 1916-1920" | 23 |
| 15 | Castelvecchi, Nature news 2023 | 27 |
| 16 | Annett 2005 | 32 |
| 17 | Heisenberg 1927 | 33 |
| 18 | Burk, Grace Hopper (uncited) | dropped |
| 19 | Lee et al., lasso post-selection | 37, 36 |
| 20 | Bohm 1951 | 42 |
| 20.1 | Bell 1964 | 43 |
| 20.2 | "Maudlin" | 44 |
| 21 | Penrose 1989 | 145, 50, 49 |
| 22 | Wolfram 2020 | 51 |
| 23 | Tegmark 2014 | 52 |
| 24 | Vopson 2019 | 31 |
| 25 | Bohm 1951 (duplicate) | 42 |
| 26 | "Wheeler, DeWitt 1967" | 55 |
| 26.1 | Ashtekar et al. 2006 | 100 |
| 27 | Aharonov et al. 2018 | 38 |
| 27.1 | Peebles and Ratra 2003 | 65 |
| 28 | Frieman et al. 2008 | 64 |
| 29 | Canetti et al. 2012 | 67 |
| 30 | Nelson and Wilson-Ewing 2011 | 68 |
| 31 | LIGO/Virgo PRX 2016 (duplicate) | 69 |
| 32 | Meneghetti et al. 2020 | 70 |
| 33 | "Kaluza and Klein 1926" | 73, 74 |
| 34 | Farnes 2018 | 77 |
| 35 | Almgren and Taylor 1976 | 79 |
| 36 | Dirac 1939 | 41 |
| 37 | Newsome 2020 | 84 |
| 38 | Lorentz 1904 | 85 |
| 39 | Pauli 1980 | 86 |
| 40 | Watson, Mortlock, Jaffe 2011 | 87 |
| 41 | Kotera and Olinto 2011 | 88 |
| 41.1 | Swartz et al. 2004 | 91 |
| 42 | Peskin and Schroeder 1995 | 56 |
| 43 | Marletto and Deutsch (duplicate) | 10 |
| 44 | Noether 1918 | 95 |
| 45 | Hook and Hall | 96 |
| 46 | Einstein and Rosen 1935 | 97 |
| 47 | "Smollen" | 48 |
| 48 | Mitchell, genetic algorithms | 101 |
| 49 | Planck press release 2013 | 29 |
| 49.1 | Brandenberger 2004 | 2 |
| 50 | Tanabashi (PDG) 2018 | 104 |
| 51 | Penrose 1979 | 113, 112 |
| 52 | "A. Einstein and N. Ros" | 114, 115 |
| 53 | Jeon et al. 2026 | 117 |
| 54 | Caputo et al. 2017 | 118 |
| 55 | Bueno Sánchez 2014 | 108 |
| 56 | van Marle et al. 2008 | 120, 119 |
| 57 | Maldacena 2003 | 122, 121 |
| 58 | "Ghez and Genzel" 2008 | 125, 126 |
| 59 | Komberg et al. "1998" | 129 |
| 60 | Minkowski 1962 | 135, 132, 133 |
| 61 | Temming, Science News 2021 | 136, 137 |
| 62 | Hamilton 1999 | 139 |
| 63 | Wright 2004 | 105 |
| 64 | Weinberg, Dreams of a Final Theory (uncited) | dropped |
| 65 | Levin 2025 | 146 |
