# Mtb-InhA-Drug-Design 

## 📋 Project Overview
This repository contains a computational biology and computer-aided drug design (CADD) study focusing on the **InhA enzyme** (Enoyl-[acyl-carrier-protein] reductase, Gene: `Rv1484`), a critical target for anti-tubercular therapeutics. The project explores the structural properties of the target protein, protein-protein interaction networks, active site pockets, and virtual screening of potential inhibitors.

* **Organism:** Mycobacterium tuberculosis (MT)
* **Protein:** InhA, also known as Enoyl-[acyl-carrier-protein] reductase
* **Gene:** Rv1484
* **Function:** InhA is an enzyme involved in fatty acid synthesis, specifically in the synthesis of mycolic acid which are long chain fatty acids unique to mycobacterial cell walls.

### **Vital Pathways:**
* InhA participates in the fatty acid elongation process of Type2 fatty acid synthase system (FAS-II).
* This system is critical for mycolic acids and essential components to the mycobacterial cell wall.
* Mycolic acids provides the cell wall with impermeability and resistance to host defence and antibiotics, crucial for MT’s virulence and survival.
* InhA catalyzes the NADH dependent reduction of enoyl-ACP, a critical step in fatty acid chain elongation.

### **Importance of InhA as a Drug Target:**
* InhA is the primary target of the frontline anti-TB drug isoniazid (INH) and second-line drug ethionamide.
* INH inhibits InhA by forming a complex after enzymatic activation, disrupting mycolic acid synthesis which compromises the bacterial cell wall, leading to bacterial death.
* Mutations in InhA or its promoter region are common mechanisms of INH resistance.
* Because humans do not synthesize mycolic acids and lack FAS-II, InhA is a selective and effective drug target.

### **Protein Data Bank (PDB) Information:**
* The crystal structure of InhA from M. tuberculosis has been solved by X-ray crystallography.
* **Example PDB IDs:** `1BVR`, `2NSD`, `4TRN`, `8OTN`
* Structures show InhA complexed with NADH, fatty acyl substrates, and various inhibitors, useful for drug design.

### **Properties and Key Features:**
* **Molecular Weight:** Approximately 29 kDa
* **Structure:** Homotetrameric enzyme with each subunit harboring a Rossmann fold binding NADH.
* **Active Site:** Hydrophobic pocket that binds enoyl-ACP substrates and inhibitors.
* Essential enzyme for mycolic acid biosynthesis, critical for cell wall integrity.

### **Methods to Identify and Study the Protein:**
* **Genetics**: Gene knockout and mutation studies confirm essentiality and resistance mechanisms.
* **Bioinformatics:** Annotated in Mycobrowser (Rv1484), STRING for interactions.
* **Structural Biology:** Numerous crystal structures for studying enzyme mechanism and inhibitor binding.
* **Drug screening:** Molecular docking and inhibitor design focused on the hydrophobic active site.

The protein structure selected for the study is `8OTN`.

---

## 📊 Key Results & Visualizations

### 1. Fasta Sequence

`>8OTN_1|Chains A, B, C, D|Enoyl-[acyl-carrier-protein] reductase [NADH]|Mycobacterium tuberculosis (1773)
GSHMTGLLDGKRILVSGIITDSSIAFHIARVAQEQGAQLVLTGFDRLRLIQRITDRLPAKAPLLELDVQNEEHLASLAGRVTEAIGAGNKLDGVVHSIGFMPQTGMGINPFFDAPYADVSKGIHISAYSYASMAKALLPIMNPGGSIVGMDFDPSRAMPAYNWMTVAKSALESVNRFVAREAGKYGVRSNLVAAGPIRTLAMSAIVGGALGEEAGAQIQLLEEGWDQRAPIGWNMKDATPVAKTVCALLSDWLPATTGDIIYADGGAHTQLL`

---

### 2. Retrieving PDB Structure

* The RCSB Protein Data Bank (https://www.rcsb.org/) was used to search for and download the 3D structure file of the target protein by entering the PDB ID (e.g., 8OTN) in the search bar.
* The structure file in PDB format was saved for further analyses and visualization.

![Structure](https://github.com/AryanPaste/Mtb-InhA-Drug-Design/blob/main/Images/8OTN%20-%20Structure.png)

![PDB](https://github.com/AryanPaste/Mtb-InhA-Drug-Design/blob/main/Images/8OTN%20-%20PDB.png)

![Ligands](https://github.com/AryanPaste/Mtb-InhA-Drug-Design/blob/main/Images/8OTN%20-%20Ligands.png)

---

### 3. Identifying Enzyme Domains with Pfam/InterPro

* The UniProt website (https://www.uniprot.org/) was used to obtain the protein sequence or UniProt accession number.
* This sequence was entered into the InterPro (https://www.ebi.ac.uk/interpro/) or Pfam tool (https://www.ebi.ac.uk/interpro/search/sequence/) and the search was run.
* The output listed all matched protein domains, which were downloaded in formats such as TSV, JSON, XML, or as a screenshot of the webpage.

![Enzyme Domains](https://github.com/AryanPaste/Mtb-InhA-Drug-Design/blob/main/Images/8OTN%20-%20InterPro.png)

---

### 4. Determining Physicochemical Properties with ProtParam

* The protein’s amino acid sequence was pasted into the ExPASy ProtParam tool (https://web.expasy.org/protparam/).
* On submission, the results page provided properties such as molecular weight, theoretical pI, composition, and stability indices.
```
Number of amino acids: 272
Theoretical pI: 5.87
Molecular weight: 28809.11

Amino acid composition: 
Ala (A)  36	 13.2%
Arg (R)  13	  4.8%
Asn (N)   8	  2.9%
Asp (D)  15	  5.5%
Cys (C)   1	  0.4%
Gln (Q)  10	  3.7%
Glu (E)  11	  4.0%
Gly (G)  29	 10.7%
His (H)   6	  2.2%
Ile (I)  20	  7.4%
Leu (L)  27	  9.9%
Lys (K)   9	  3.3%
Met (M)  10	  3.7%
Phe (F)   7	  2.6%
Pro (P)  13	  4.8%
Ser (S)  17	  6.2%
Thr (T)  13	  4.8%
Trp (W)   4	  1.5%
Tyr (Y)   6	  2.2%
Val (V)  17	  6.2%
Pyl (O)   0	  0.0%
Sec (U)   0	  0.0%

 (B)   0	  0.0%
 (Z)   0	  0.0%
 (X)   0	  0.0%
 
Total number of negatively charged residues (Asp + Glu): 26
Total number of positively charged residues (Arg + Lys): 22

Atomic composition:
Carbon      C	      1280
Hydrogen    H	      2044
Nitrogen    N	       354
Oxygen      O	       379
Sulfur      S	        11

Formula: C1280H2044N354O379S11
Total number of atoms: 4068

Extinction coefficients:
Extinction coefficients are in units of  M-1 cm-1, at 280 nm measured in water.
Ext. coefficient    30940
Abs 0.1% (=1 g/l)   1.074, assuming all pairs of Cys residues form cystines
Ext. coefficient    30940
Abs 0.1% (=1 g/l)   1.074, assuming all Cys residues are reduced

Estimated half-life:
The N-terminal of the sequence considered is G (Gly).
The estimated half-life is: 30 hours (mammalian reticulocytes, in vitro).
                            >20 hours (yeast, in vivo).
                            >10 hours (Escherichia coli, in vivo).
                            
Instability index:
The instability index (II) is computed to be 38.96
This classifies the protein as stable.
Aliphatic index: 98.75
Grand average of hydropathicity (GRAVY):0.135
```
---

### 5. Analyzing Protein-Protein Interactions with STRING

* The STRING database (https://string-db.org/) was accessed and the protein name or UniProt accession was entered in the search bar.
* The organism (e.g., Mycobacterium tuberculosis) was specified to filter relevant interactions.
* STRING displayed an interactive network with predicted protein-protein interactions and functional partners.

![STRING](https://github.com/AryanPaste/Mtb-InhA-Drug-Design/blob/main/Images/8OTN%20-%20STRING.png)

---

### 6. Identifying Active Sites with CASTp or DoGSiteScorer

* The CASTp server (http://sts.bioe.uic.edu/castp/) was opened and the PDB ID (e.g., 8OTN) was submitted.
* The server analyzed the structure and returned predicted active site pockets and residue information.

![Active Sites](https://github.com/AryanPaste/Mtb-InhA-Drug-Design/blob/main/Images/8OTN%20-%20ActiveSites.png)

---

### 7. Protein Structure Validation (Ramachandran Plot)

* The 3D structure file was obtained from Swiss-Model (https://swissmodel.expasy.org/interactive) or RAMPAGE (http://mordred.bioc.cam.ac.uk/~rapper/rampage.php) online servers.
* The Ramachandran plot was generated, displaying allowed/disallowed regions for protein backbone dihedral angles.

![Ramachandran Plot](https://github.com/AryanPaste/Mtb-InhA-Drug-Design/blob/main/Images/8OTN%20-%20RamachandranPlot.png)

---

### 8. Drug-Ligand Information Search (FDA Status)

* DrugBank (https://go.drugbank.com/) was used to search for the ligand (e.g., NAD, NADH, or small-molecule inhibitors).
* The official DrugBank entry for the ligand was checked for FDA approval status, mechanism of action, and clinical relevance.

![DrugBank](https://github.com/AryanPaste/Mtb-InhA-Drug-Design/blob/main/Images/8OTN%20-%20Drugbank.png)

---

### 9. Virtual Screening

* Online virtual screening tools (such as SwissDock: http://www.swissdock.ch/ or CB-Dock: https://cb-dock.shao.ac.cn/) were used.
* The protein structure and ligand files (in mol2 or SMILES) were uploaded.
* The docking job was submitted, and the results (binding poses, scores) were retrieved after the computational run was completed.

![Virtual Screening](https://github.com/AryanPaste/Mtb-InhA-Drug-Design/blob/main/Images/8OTN%20-%20LigandBinding.png)
