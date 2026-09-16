# CELL AND MOLECULAR BIOLOGY LABORATORY
## From Gene Mutation to Disease: Investigating How DNA Sequence Changes Affect Protein Products and Human Phenotypes

**Name:** Obiñeta, Inah Marie
**Course/Section:** BIO 300 – B
**Assigned Gene:** SERPINA1 (Alpha-1 Antitrypsin Deficiency)
**Instructors:** Ma’am Lilibeth Bucol & Sir Abner Bucol
**Date:** September 16, 2026

---

## Background
Alpha-1 antitrypsin deficiency (AATD) is a genetic disorder causing low levels or a dysfunctional form of alpha-1 antitrypsin (A1AT), a protein that normally protects lung tissue by inhibiting neutrophil elastase (Stoller & Aboussouan, 2012). Deficient or misfolded A1AT leads to two distinct problems: unchecked lung damage causing early-onset emphysema and COPD, and toxic accumulation of misfolded protein inside liver cells, causing cirrhosis and increased liver cancer risk. AATD is inherited in an autosomal codominant pattern, with the homozygous Pi*ZZ genotype producing the most severe disease.

---

## Part I. Select a Human Disease and Gene

| Item | Value |
|---|---|
| Disease / Phenotype | Alpha-1 antitrypsin deficiency (AATD) |
| Gene | SERPINA1 |

---

## Part II. Research the Disease

### A. Disease
| Field | Answer |
|---|---|
| Disease / Phenotype | Alpha-1 antitrypsin deficiency (AATD) |
| Major clinical characteristics | **Lungs:** Early-onset emphysema, COPD, and bronchiectasis<br>**Liver:** Neonatal jaundice, adult cirrhosis, and liver cancer risk<br>**Skin:** Rare inflammatory nodules (panniculitis) |
| Organs / tissues / cells affected | **Organs:** Lungs and liver<br>**Tissues/Cells:** Alveolar lung tissue degrades; hepatocytes accumulate misfolded proteins |
| Genetic basis | Pathogenic mutations in the *SERPINA1* gene on chromosome 14 |
| Inheritance pattern | Autosomal codominant. The Z allele causes abnormal protein polymerization. Homozygous PiZZ produces the most severe symptoms. |

### B. Gene and Normal Protein
| Field | Answer |
|---|---|
| Official gene symbol | SERPINA1 |
| Chromosome location | 14q32.13 |
| Normal product | Alpha-1 antitrypsin (AAT) — a serine protease inhibitor (serpin) |
| Normal biological function | Inhibits neutrophil elastase released during inflammation → protects tissues from breakdown |
| Cellular location | Synthesized in rough ER and Golgi of hepatocytes → secreted into bloodstream → functions extracellularly |
| Pathway / process | Protease–antiprotease balance protecting lung tissue; protein secretory pathway |

### C. Documented Mutation
| Field | Value |
|---|---|
| Gene | SERPINA1 |
| Reference transcript | NM_000295.5 |
| Nucleotide change | c.1096G>A |
| Protein change (HGVS) | p.Glu366Lys |
| Protein change (legacy) | p.Glu342Lys ("E342K") |
| Common name | Z allele (PiZ) |
| dbSNP rsID | rs28929474 |
| ClinVar accession | VCV000017967 |
| Mutation type | Missense |
| Clinical interpretation | Pathogenic |

---

## Part III. Obtain the Normal Reference Sequence

| Item | Accession / Detail |
|---|---|
| Reference transcript (mRNA) | NM_000295.5 |
| Reference protein | NP_000286.3 |
| Gene ID | 5265 |
| CDS coordinates | 262..1518 |
| Filename | `SERPINA1_WT_CDS.fasta` |

---

## Part IV. Import the Normal Sequence into Galaxy
- Uploaded wild-type coding sequence: `SERPINA1_WT_CDS.fasta` ✅

---

## Part V. Establish the Wild-Type Control

| Item | Answer |
|---|---|
| CDS length | 1,257 bp |
| Predicted protein length | 418 amino acids |
| Start codon | `ATG` |
| Stop codon | `TAA` |
| First 10 amino acids | `MPSSVSWGIL` |
| Last 10 amino acids | `MGKVVNPTQK` |
| Reading frame | Frame 1 — intact |
| Reference match | Matches NP_000286.3 ✅ |
| Tool used | `transeq` (Translate nucleic acid sequences) |
| Output file | `SERPINA1_WT_protein.fasta` |

---

## Part VI. Formulate a Mutation Hypothesis

| Item | Prediction |
|---|---|
| Mutation & change | c.1096G>A — `GAG` → `AAG` |
| Nucleotides affected | 1 |
| Mutation type | Missense |
| Reading frame effect | None — in-frame substitution |
| Protein length effect | No change — still 418 aa |
| Functional effect | Protein misfolding → intracellular accumulation → polymerization → Alpha-1 Antitrypsin Deficiency |

---

## Part VII. Create the Mutant Sequence

| Item | Recorded Information |
|---|---|
| Position | c.1096 |
| WT sequence | `TCCGAGGTC` (codon 366: `GAG`) |
| Mutant sequence | `TCCAAGGTC` (codon 366: `AAG`) |
| Change | 1 base substituted: `G` → `A` |
| Type | Missense substitution |

---

## Part VIII. Translate the Mutant Sequence

| Item | Result |
|---|---|
| Mutant CDS length | 1,257 bp |
| Mutant protein length | 418 aa |
| Reading frame | Frame 1 — intact |
| First changed residue | Position 366 |
| Premature stop | Absent |
| Residues altered | 1 only |

### Amino Acid Change
| Position | Wild-Type | PiZ Mutant |
|---|---|---|
| **366** | Glutamic acid (Glu/E) — acidic, negatively charged | Lysine (Lys/K) — basic, positively charged |
| All others | Identical | Identical |

---

## Part IX. Compare WT and Mutant Proteins

| # | Question | Answer |
|---|---|---|
| 1 | First amino acid difference | Position 366 |
| 2 | Number of residues affected | 1 only — position 366 |
| 3 | Downstream changes | None — positions 367–418 identical |
| 4 | Deletion/insertion? | No — substitution only |
| 5 | Premature stop? | No — full length, stop at 418 |
| 6 | Reading frame change? | No — preserved |
| 7 | Protein length change? | No — both 418 aa |
| 8 | Mutation type | Missense |

---

## Part X. Explain the Molecular Consequence

**Mutation → DNA change:** Single base substitution at c.1096 — `G` → `A`. No insertion, deletion, or frameshift.

**→ Codon/reading frame:** `GAG` → `AAG` at codon 366. Reading frame intact — no bases gained or lost.

**→ Protein sequence:** Glu (negative) → Lys (positive) at position 366. Remaining 417 residues identical.

**→ Structural change:** Position 366 lies in a critical folding region. Charge reversal disrupts salt bridges and hydrogen bonding → protein misfolds → forms insoluble polymers in ER.

**→ Cellular effect:** Misfolded protein retained in hepatocytes → not secreted → low circulating A1AT. Neutrophil elastase in lungs unchecked → destroys alveolar walls → emphysema. Liver aggregates → cirrhosis risk.

**→ Disease/phenotype:** Autosomal codominant AAT deficiency — early COPD, liver disease.

---

## Part XI. Second Experiment: Create Your Own Mutation
**Option chosen:** One-nucleotide deletion

| Item | Prediction (Before) | Result (After) |
|---|---|---|
| Change made | Delete C at c.298 | `ACCCTTT` → `ACCTTT` ✅ confirmed |
| Reading frame | Will shift | Shifted — codon 100 onward ✅ |
| Protein length | Shorter than 418 aa | ~123 aa — truncated ✅ |
| Premature stop | Expected | Present at ~aa 123 ✅ |
| Amino acids affected | Positions 100–418 | ~319 residues completely changed ✅ |
| Mutation type | Frameshift deletion | Frameshift deletion — severe loss-of-function ✅ |

---

## Part XII. Compare the Documented and Artificial Mutations

| Feature | Wild-Type | PiZ (c.1096G>A) | 1-bp Deletion (c.298del) |
|---|---|---|---|
| CDS Length | 1257 bp | 1257 bp | 1256 bp |
| Protein Length | 418 aa | 418 aa | ~123 aa |
| Mutation Type | — | Missense substitution | Frameshift deletion |
| Reading Frame Changed? | — | No | **Yes** — codon 100 |
| Premature Stop? | — | No | **Yes** — ~aa 123 |
| Amino Acids Altered | — | 1 (pos 366) | ~319 (pos 100–418) |
| Functional Consequence | Normal — secreted, protects lungs | E366K → misfolding → ER retention → low secretion → emphysema + liver injury | Massive sequence change → truncated → non-functional → complete loss of activity |

**Summary:** Both mutations reduce functional α₁-antitrypsin, but through different mechanisms. PiZ changes one amino acid — protein is full-length but misfolds and accumulates. The 1-bp deletion shifts the frame, rewrites hundreds of residues, stops early — product is severely truncated and non-functional. Frameshifts are far more disruptive.

---

## Part XIII. Interpretation Questions

| # | Question & Answer |
|---|---|
| 1 | **Why does location matter?**<br>Determines whether the change hits a critical domain, active site, or binding pocket. Same substitution in a vital region = loss of function; in a non-essential region = harmless. |
| 2 | **Why 3 nt ≠ 1–2 nt deletion?**<br>Codons are read in triplets. Delete 3 → remove one amino acid, frame intact. Delete 1 or 2 → shift frame → every downstream codon altered. |
| 3 | **Does every mutation change the protein?**<br>No. Genetic code is redundant — third-base substitutions can be synonymous (silent) with no amino acid change. |
| 4 | **Does every substitution destroy function?**<br>No. Similar-property swaps (hydrophobic → hydrophobic) or changes outside critical domains often preserve function. |
| 5 | **Why frameshift affects so many residues?**<br>Ribosomes read fixed triplets. One base deleted shifts the grouping for all downstream triplets → every subsequent amino acid differs. |
| 6 | **Why premature stop = nonfunctional?**<br>Truncates before critical domains, binding sites, or structural elements are complete. Often degraded by nonsense-mediated decay. |
| 7 | **Can function change without length change?**<br>Yes — missense substitutions alter folding/stability while keeping length identical (PiZ example). |
| 8 | **Can disease occur without protein sequence change?**<br>Yes — non-coding mutations (promoter, enhancer, splice site) can reduce transcription, alter splicing, or lower translation → insufficient normal protein produced. |
| 9 | **Evidence supporting PiZ mechanism**<br>Computational translation confirms Glu→Lys at 366 with intact frame. Published work links this charge change to ER polymerization and clinical deficiency. |
| 10 | **Computational vs published evidence**<br>✅ *Directly supported:* Sequence change, codon modification, reading frame preservation, protein length, position of change<br>📚 *Requires published work:* In vivo expression, 3D structure, cellular trafficking, clinical phenotype correlation |

---

## Limitations
- Artificial deletion assessed computationally — actual in vivo effect may include nonsense-mediated mRNA decay
- Only one frameshift position tested; severity could vary by location
- Protein structure prediction not performed experimentally
- No clinical data available for the artificial variant

---

## Conclusion
Both mutations reduce functional α₁-antitrypsin, but by fundamentally different mechanisms and with unequal severity. The PiZ missense substitution changes a single amino acid — preserving length and reading frame — resulting in a protein that misfolds but is otherwise nearly intact. The 1-bp deletion causes a frameshift that rewrites hundreds of amino acids and terminates early, producing a truncated product with no biological function. Frameshift mutations are far more disruptive because they alter the entire downstream sequence, demonstrating that deletion size and position determine whether a variant causes partial dysfunction or complete loss of protein activity.

---

## Part XIV. Documentation

| Resource | Link |
|---|---|
| Galaxy History | https://usegalaxy.org/u/inah.obineta2/h/obiñeta-disease-gene-mutation-lab |
| GitHub Repository | https://github.com/iinahmariee/OBINETA_Disease_Gene_Mutation_Lab/tree/GROUP-4 |

---

## References

Lomas, D. A., Evans, D. L., Finch, J. T., & Carrell, R. W. (1992). The mechanism of Z α₁-antitrypsin accumulation in the liver. *Nature, 357*(6379), 605–607.  
https://doi.org/10.1038/357605a0

National Center for Biotechnology Information. (n.d.). *ClinVar: VCV000017967 — SERPINA1 c.1096G>A (p.Glu366Lys)*. U.S. National Library of Medicine. Retrieved September 16, 2026.  
https://www.ncbi.nlm.nih.gov/clinvar/variation/17967/

National Center for Biotechnology Information. (n.d.). *NM_000295.4 — SERPINA1 transcript variant 1, mRNA*. Retrieved September 16, 2026.  
https://www.ncbi.nlm.nih.gov/nuccore/NM_000295.4

Online Mendelian Inheritance in Man. (n.d.). *#613490 — Alpha-1-antitrypsin deficiency*. McKusick-Nathans Institute of Genetic Medicine, Johns Hopkins University. Retrieved September 16, 2026.  
https://omim.org/entry/613490

Stoller, J. K., & Aboussouan, L. S. (2005). α₁-antitrypsin deficiency. *The Lancet, 365*(9478), 2225–2236.  
https://doi.org/10.1016/S0140-6736(05)66781-5
