# CELL AND MOLECULAR BIOLOGY LABORATORY
## From Gene Mutation to Disease
Investigating How DNA Sequence Changes Affect Protein Products and Human Phenotypes

**Name:** Obiñeta, Inah Marie
**Course/Section:** BIO 300 – B
**Assigned gene:** SERPINA1 (Alpha-1 antitrypsin deficiency)
**Instructors:** Ma’am Lilibeth Bucol & Sir Abner Bucol

---

## Background
Alpha-1 antitrypsin deficiency (AATD) is a genetic disorder causing low levels or a dysfunctional form of alpha-1 antitrypsin (A1AT), a protein that normally protects lung tissue by inhibiting neutrophil elastase (Stoller & Aboussouan, 2012). Deficient or misfolded A1AT leads to two distinct problems: unchecked lung damage causing early-onset emphysema and COPD, and toxic accumulation of misfolded protein inside liver cells, causing cirrhosis and increased liver cancer risk. AATD is inherited in an autosomal codominant pattern, with the homozygous Pi*ZZ genotype producing the most severe disease.

---

## Part I. Select a Human Disease and Gene

| Item | Value |
|---|---|
| Disease/Phenotype | Alpha-1 antitrypsin deficiency (AATD) |
| Gene | SERPINA1 |

---

## Part II. Research the Disease

### A. Disease
| Field | Answer |
|---|---|
| Disease or phenotype | Alpha-1 antitrypsin deficiency (AATD) |
| Major clinical characteristics | Lungs: Early-onset emphysema, COPD, and bronchiectasis.<br>Liver: Neonatal jaundice, adult cirrhosis, and liver cancer risk.<br>Skin: Rare inflammatory nodules (panniculitis). |
| Cells, tissues, or organs are mainly affected | Organs: Primary damage occurs in the lungs and liver.<br>Tissues/Cells: Alveolar lung tissue degrades. Hepatocytes accumulate misfolded proteins. |
| Genetic basis | Pathogenic mutations in the SERPINA1 gene on chromosome. |
| Inheritance pattern, if applicable | The Z allele causes abnormal protein polymerization. Inherited in an autosomal codominant pattern. The homozygous PiZZ genotype results in the most severe symptoms. |

### B. Gene and Normal Protein
| Field | Answer |
|---|---|
| official gene symbol | SERPINA1 |
| Chromosome human gene location | Chromosome 14 (specifically at the long arm position 14q32.13) |
| What the gene normally encodes | The Alpha-1 antitrypsin (AAT) protein, a major serine protease inhibitor (serpin). |
| Normal biological function | Protects tissues from breakdown by inhibiting proteolytic enzymes, primarily neutrophil elastase, which is released by white blood cells during inflammation. |
| Normal cellular/subcellular location | Synthesized in the rough endoplasmic reticulum (RER) and Golgi apparatus of hepatocytes before being secreted into the bloodstream to function extracellularly. |
| Pathway/cellular process | Protease–antiprotease balance protecting lung tissue; protein secretory pathway |

### C. Documented Mutation
| Field | Value |
|---|---|
| Gene | SERPINA1 |
| Reference transcript | NM_000295.5 |
| Nucleotide change | c.1096G>A |
| Protein change (current HGVS numbering) | p.Glu366Lys |
| Protein change (legacy/mature-protein numbering) | p.Glu342Lys ("E342K") |
| Common name | Z allele |
| dbSNP rsID | rs28929474 |
| ClinVar accession | VCV000017967 |
| Mutation type | Missense |
| Clinical interpretation | Pathogenic |
| Key references | Nukiwa, T., Brantly, M., Garver, R., Paul, L., Courtney, M., LeCocq, J. P., & Crystal, R. G. (1986). Evaluation of "at risk" alpha 1-antitrypsin genotype SZ with synthetic oligonucleotide gene probes. Journal of Clinical Investigation, 77(2), 528–537. https://doi.org/10.1172/JCI112333 |

---

## Part III. Obtain the Normal Reference Sequence

| Item | Accession |
|---|---|
| Reference transcript (mRNA) | NM_000295.5 |
| Reference protein | NP_000286.3 |
| Gene ID | 5265 |
| CDS coordinates (within the mRNA) | 262..1518 |
| Filename | SERPINA1_WT_CDS.fasta |

---

## Part IV. Import the Normal Sequence into Galaxy
Figure 1: Uploaded wild-type coding sequence of the human SERPINA1 gene (SERPINA1_WT_CDS.fasta) in Galaxy

---

## Part V. Establish the Wild-Type Control

| Item | Answer |
|---|---|
| CDS length | 1,257 bp |
| Predicted protein length | 418 amino acids |
| Start codon | ATG |
| Stop codon | TAA |
| First 10 amino acids | MPSSVSWGIL |
| Last 10 amino acids | MGKVVNPTQK |
| Reading frame | Frame 1 |
| Comparison with reference protein | Matches NCBI reference protein NP_000286.3 (confirmed via the CDS /translation annotation on NM_000295.4). WT control validated. |
| Galaxy tool used | Transeq — Translate nucleic acid sequences |
| Output filename | SERPINA1_WT_protein.fasta |

---

## Part VI. Formulate a Mutation Hypothesis

| Item | Prediction |
|---|---|
| Mutation and exact nucleotide change | c.1096G>A (GAG-AAG) |
| Number of nucleotide(s) affected | 1 nucleotide |
| Predicted mutation type | Missense mutation |
| Predicted effect on the reading frame | None (In-frame substitution) |
| Predicted effect on protein length | No change (same number of amino acids) |
| Predicted effect on protein function | Leads to protein misfolding, intracellular accumulation, and polymerization (Alpha-1 Antitrypsin Deficiency) |

---

## Part VII. Create the Mutant Sequence

| Item | Recorded Information |
|---|---|
| Original nucleotide position(s) | c.1096 |
| Original nucleotide sequence | TCCGAGGTC (at codon 366) |
| Mutant nucleotide sequence | TCCAAGGTC (at codon 366) |
| Number of bases inserted / deleted / substituted | 1 base substituted (G → A) |
| Mutation type | Missense substitution (single nucleotide variant) |

---

## Part VIII. Translate the Mutant Sequence

| Item | Recorded Information |
|---|---|
| Mutant CDS length | 1,257 bp |
| Mutant protein length | 418 amino acids |
| Reading frame | Frame 1 — intact, no frameshift |
| Location of first amino acid difference | Position 366 |
| Premature stop codon? | Absent |
| Approximate number of amino acids affected | 1 amino acid only |

### Amino Acid Change Detail
| Position | Wild-Type | Mutant |
|---|---|---|
| 366 | Codon: GAG → Glutamic acid (Glu / E) — acidic | Codon: AAG → Lysine (Lys / K) — basic |
| All other positions | Identical to WT | Identical to WT |

---

## Part IX. Compare WT and Mutant Proteins

| Question / Parameter | Result / Answer |
|---|---|
| 1. First amino-acid difference position | Position 366 |
| 2. Number of amino acids affected | Yes, only position 366 changed |
| 3. Downstream amino acid changes | No, all positions after 366 are identical |
| 4. Deletion or insertion of amino acid | No, no deletion or insertion occurred |
| 5. Premature stop codon production | No, full-length protein; stop codon remains at position 418 |
| 6. Reading frame change | No, single base substitution preserves the reading frame |
| 7. Protein length change | No, both WT and mutant are 418 amino acids long |
| 8. Mutation type | Missense (changes one amino acid to a different amino acid) |

---

## Part X. Explain the Molecular Consequence

**Mutation → DNA sequence change:**
The PiZ mutation in the SERPINA1 gene is a single base substitution at coding position c.1096. The wild-type sequence at this site is GAG; the mutant sequence is AAG where only one nucleotide was replaced, no insertion, deletion nor frameshift.

**→ Codon or reading-frame change:**
The substitution alters the first base of codon 366 from G to A. The reading frame remains intact because no bases are gained or lost; the mutation is a substitution only.

**→ Protein sequence change:**
At the protein level, codon 366 changes from GAG, a glutamic acid and negatively charged amino acid to AAG, lysine, a positively charged amino acid. All other 417 amino acids in the 418-residue protein are identical between wild-type and mutant.

**→ Possible structural or functional change:**
Position 366 were located within the critical region for proper folding and function of α₁-antitrypsin. The replacement of negative charged glutamic acid with positive charged lysine disrupts local electrostatic interactions and hydrogen bonding. This causes the mutant protein to misfold; instead of adopting its active conformation, it forms long, insoluble polymer chains within the endoplasmic reticulum (ER) of liver cells.

**→ Cellular consequence:**
Misfolded polymers accumulate inside hepatocytes and are not secreted into the bloodstream. Very little functional α₁-antitrypsin reaches body tissues. Moreover, in the lungs, the absence of this protein means neutrophil elastase where an enzyme that breaks down connective tissue and no longer inhibited.

**→ Disease or phenotype:**
Unchecked elastase progressively destroys the alveolar walls of the lungs, causing emphysema, which develops earlier and more severely in individuals who smoke. In the liver, accumulated protein aggregates cause cellular stress and can lead to cirrhosis. Together, these effects define the clinical phenotype of α₁-antitrypsin deficiency (PiZ).

---

## Part XI. Second Experiment: Create Your Own Mutation
**Option chosen:** One-nucleotide deletion

| | Prediction Before Translation | Result After Translation |
|---|---|---|
| Change made | Delete 1 nucleotide (C) at c.298 | Deletion confirmed, sequence ACCCTTT → ACCTTT |
| Reading frame | Will shift | Shifted — altered from codon 100 |
| Protein length | Shorter than 418 aa | 123 aa — truncated |
| Premature stop codon | Expected | Present |
| Amino acids affected | All from position 100 onward | 319 residues completely changed |
| Mutation type | Frameshift deletion | Frameshift deletion; severe loss-of-function |

---

## Part XII. Compare the Documented and Artificial Mutations

| Feature | Wild-Type | Documented Mutation (PiZ c.1096G>A) | Artificial Mutation (1-bp deletion c.298) |
|---|---|---|---|
| CDS length | 1257 bp | 1257 bp | 1256 bp |
| Protein length | 418 aa | 418 aa | ~123 aa (truncated) |
| Mutation type | — | Missense substitution | Frameshift deletion |
| Reading frame changed? | — | No | Yes; shifted from codon 100 |
| Premature stop codon? | — | No | Yes; appears early |
| Amino acids affected | — | 1 (position 366 only) | 319 (positions 100–418 completely changed) |
| Functional consequence | Normal protein secreted; protects lungs | E366K → misfolding → ER retention → low secretion → lung emphysema + liver injury | Massive sequence change → truncated protein → non-functional → complete loss of activity |

Both the documented PiZ variant and the artificial one-nucleotide deletion alter the SERPINA1 coding sequence and ultimately reduce functional alpha-1 antitrypsin, so both are harmful. However, they damage the protein through very different mechanisms: PiZ damages function through toxic misfolding of an otherwise full-length protein caused by a single amino acid substitution, while the frameshift deletion destroys function by scrambling the entire downstream amino acid sequence.

---

## Part XIII. Interpretation Questions

**1. Why does the exact location of a mutation matter?**
The location dictates whether the change hits a critical functional domain, active site, or binding pocket. A mutation in a vital region can completely destroy protein function, whereas the exact same substitution in a non-essential loop or terminal region might be completely harmless.

**2. Why can deleting three nucleotides produce a different result from deleting one or two nucleotides?**
Because codons are read in groups of three so deleting exactly three nucleotides removes a whole codon (or amino acid) without disrupting the downstream reading frame. Deleting one or two nucleotides shifts the reading frame entirely, altering every subsequent codon.

**3. Does every mutation change the amino-acid sequence? Explain.**
No. Due to the redundancy (degeneracy) of the genetic code, multiple codons can code for the same amino acid. A substitution in the third position of a codon can results in a synonymous mutation that leaves the protein sequence unchanged.

**4. Does every amino-acid substitution destroy protein function? Explain.**
No. If a substituted amino acid has similar chemical properties (e.g., swapping one hydrophobic residue for another, like leucine for isoleucine) or sits outside a critical domain, the protein may retain normal or near-normal folding and function.

**5. Why can a frameshift affect many amino acids even if only one nucleotide was deleted?**
Ribosomes translate mRNA by reading continuous, non-overlapping triplets. Deleting a single base shifts the grouping of all downstream nucleotides, misaligning every subsequent codon and changing every downstream amino acid until a stop codon is awkwardly reached.

**6. Why might a premature stop codon produce a nonfunctional protein?**
A premature stop codon truncates the protein early, cutting off crucial functional domains, binding sites, or structural elements needed for stability. These truncated transcripts are often targeted and degraded by cellular quality control pathways like nonsense-mediated decay.

**7. Could a mutation affect protein function without greatly changing protein length?**
Yes. Missense mutations, small in-frame insertions/deletions, or single amino acid swaps change protein function or stability entirely without altering the overall length of the protein (as seen in the SERPINA1 PiZ variant).

**8. Could a mutation cause disease without changing the protein sequence? Give a possible molecular mechanism.**
Yes. A mutation in a non-coding region (such as a promoter, enhancer, or splice site) can disrupt transcription factor binding, alter mRNA splicing efficiency, or reduce translation rates, leading to a severe deficiency of normal protein levels.

**9. What evidence from your analysis supports the proposed molecular mechanism of your disease?**
Our computational translation and alignment showed a precise single-residue substitution (Glu-to-Lys) in the SERPINA1 coding sequence while keeping the reading frame intact. Combined with published literature, this explains how the resulting electrostatic clash triggers intracellular polymer accumulation and disease.

**10. Which conclusions are supported directly by your computational results, and which require evidence from published experimental studies?**
- Directly supported conclusions: Computational results explicitly verify the nucleotide sequence change, codon modification, reading frame preservation, protein length, and the exact position of the predicted amino acid substitution.
- Required experimental evidence: Determining whether the protein is actually expressed in cells, observing 3D structural misfolding, and linking intracellular polymer accumulation to clinical phenotypes like emphysema and cirrhosis require published experimental studies.

---

## Limitations
- The artificial deletion was predicted computationally no actual in vivo effect may include nonsense-mediated mRNA decay
- Only one frameshift position tested; severity could vary by location
- Protein structure prediction not performed experimentally
- No clinical data available for the artificial variant

---

## Conclusion
Both mutations reduce functional α₁-antitrypsin, but by fundamentally different mechanisms and with unequal severity. The PiZ missense substitution changes a single amino acid that preserves the length and reading frame resulting in a protein that misfolds but is otherwise nearly intact. The 1-bp deletion causes a frameshift that rewrites hundreds of amino acids and terminates early, producing a truncated product with no biological function. Frameshift mutations are far more disruptive because they alter the entire downstream sequence, demonstrating that deletion size and position determine whether a variant causes partial dysfunction or complete loss of protein activity.

---

## Part XIV. Documentations

| Resource | Link |
|---|---|
| Galaxy Link | https://usegalaxy.org/u/inah.obineta2/h/obiñeta-disease-gene-mutation-lab |
| GitHub Repository Link | https://github.com/iinahmariee/OBINETA_Disease_Gene_Mutation_Lab/tree/GROUP-4 |

---

## References

Lomas, D. A., Evans, D. L., Finch, J. T., & Carrell, R. W. (1992). The mechanism of Z α₁-antitrypsin accumulation in the liver. *Nature, 357*(6379), 605–607.  
https://doi.org/10.1038/357605a0

National Center for Biotechnology Information. (n.d.). *ClinVar: VCV000017967.3 — Alpha-1 antitrypsin, SERPINA1, c.1096G>A (p.Glu366Lys)*. U.S. National Library of Medicine. Retrieved September 16, 2026.  
https://www.ncbi.nlm.nih.gov/clinvar/variation/17967/

National Center for Biotechnology Information. (n.d.). *NCBI Nucleotide: SERPINA1 serpin family A member 1 [Homo sapiens], transcript variant 1, mRNA*. Accessed September 16, 2026.  
https://www.ncbi.nlm.nih.gov/nuccore/NM_000295.4

Online Mendelian Inheritance in Man. (n.d.). *#613490 – Alpha-1-antitrypsin deficiency; A1ATD*. McKusick-Nathans Institute of Genetic Medicine, Johns Hopkins University. Retrieved September 16, 2026.  
https://omim.org/entry/613490

Stoller, J. K., & Aboussouan, L. S. (2005). α₁-antitrypsin deficiency. *The Lancet, 365*(9478), 2225–2236.  
https://doi.org/10.1016/S0140-6736(05)66781-5
