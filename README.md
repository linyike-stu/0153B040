# Scientist’s Mission (0153B040 林宜可)
## Who Stole TP53’s Superpower? Searching for the Key to Unlock Cancer
### Using AI to Uncover the Secrets of TP53–DNA Interactions

---

### 1. 【The LEGO Assembly Line】
**What type of bond links amino acids together to form a protein? Which amino acids form hydrogen bonds with each other?**

**Answer:**

![TP53 Structure](image/image_1.png)

#### 1. The Bond Linking Amino Acids: Peptide Bonds
* **Type:** Covalent amide bond.
* **Formation:** Formed via a dehydration synthesis (condensation) reaction between the carboxyl group (COOH) of one amino acid and the amino group (NH₂) of another, releasing a water molecule.

#### 2. Hydrogen Bonds in Proteins & TP53
Hydrogen bonding is crucial for protein structure and function, particularly in the TP53 tumor suppressor protein:
* **Backbone Hydrogen Bonds:** Formed between C=O and N-H groups, driving secondary structures (α-helices and β-sheets).
* **Side-Chain Hydrogen Bonds:** Formed between polar/charged R-groups to stabilize tertiary structure.
* **TP53-DNA Binding:**
  * Key Arginine residues (like Arg273 and Arg248) project into DNA grooves to form essential hydrogen bonds.
  * Mutations like R273H disrupt these bonds, leading to a cancer-associated loss of function.
* **TP53 Internal Stability:**
  * Core stability is maintained by internal hydrogen-bonding networks (e.g., Thr253 and Tyr236).
  * This works alongside a zinc-binding motif (Cys176, Cys238, Cys242, His179) and salt bridges (E171-R249) to ensure proper folding.

---

### 2. 【The Double-Track Highway of Life’s Blueprint】
**How do nucleotides assemble to form double-stranded DNA? What are the basic structural components of DNA? Is DNA right-handed or left-handed? List the names of the four DNA bases. Which bases form hydrogen bonds with each other?**

**Answer:**

![Nucleotide Structure](image/image_2.png)

#### 1. How Nucleotides Assemble into Double-Stranded DNA
* **Single Strand:** Joined by phosphodiester bonds between sugars and phosphates to form the backbone.
* **Double Strand:** Two antiparallel strands connect via hydrogen bonds between bases and twist into a double helix.

#### 2. Basic Components of DNA
* Phosphate group
* Deoxyribose sugar
* Nitrogenous base

#### 3. Handedness of DNA
* Standard B-DNA is right-handed.

#### 4. Four DNA Bases
* Adenine (A)
* Thymine (T)
* Cytosine (C)
* Guanine (G)

#### 5. Base Pairing & Hydrogen Bonds
* A pairs with T (2 hydrogen bonds).
* C pairs with G (3 hydrogen bonds).

---

### 3. 【Searching for My One-and-Only Soulmate in the Universe: A 20-Base-Pair Love Code Hidden Among 3 Billion DNA Base Pairs】
**The source of molecular stability and specificity: hydrogen bonding — How do TP53 and DNA recognize each other?**  
**Using the structure 3KMD, identify one pair of an amino acid and a DNA base that interact with each other.**

**Answer:**

Based on the structural characteristics of the p53 tumor suppressor protein and its interaction with DNA (such as in PDB ID: 3KMD):

#### How TP53 and DNA Recognize Each Other
TP53 recognizes and binds sequence-specifically to DNA primarily through its central DNA-binding domain (DBD). This recognition relies on:
* **Groove Insertion:** Key amino acid side chains (particularly positively charged residues like Arginine) project directly into the major and minor grooves of the DNA double helix.
* **Hydrogen Bonding and Electrostatic Interactions:** Specific hydrogen bonds form between polar/charged amino acid residues and the hydrogen bond donors/acceptors on the DNA bases and sugar-phosphate backbone, ensuring high binding specificity and stability.

#### Interacting Pair Example (from 3KMD)
* **Amino Acid:** Arg280 (Arginine 280)
* **DNA Base:** Guanine (G)
* **Interaction:** Arg280 projects into the major groove of the DNA and forms bidentate hydrogen bonds with an invariant Guanine base, which is critical for sequence-specific recognition and structural stability.

---

### 4. 【Return to the Crime Scene】
**Why can a mutation (change) in just one amino acid of a protein sometimes lead to a serious human disease? Give one specific example of such a disease.**

**Answer:**

---

### 5. 【Return to the Crime Scene: Searching for Clues】
**Using the TP53–DNA structure (3KMD), identify one TP53 amino acid mutation that can lead to uncontrolled cell division and contribute to the development of cancer.**  
**Then examine this amino acid in ChimeraX. Based on its three-dimensional position, determine whether the mutated amino acid is located directly at the protein–DNA interface or somewhere else in the protein.**

**Answer:**

#### 1. TP53 Amino Acid Mutation Associated with Cancer
* **Mutation:** Arg273 (commonly mutated to R273H or R273C).
* **Impact:** Arg273 is one of the most frequent hotspot mutation sites in human cancers. When Arginine at position 273 is mutated to Histidine (R273H), it loses its ability to form essential hydrogen bonds and electrostatic interactions with the DNA backbone, causing p53 to lose its sequence-specific DNA-binding ability. This leads to a loss of tumor suppressor function and uncontrolled cell proliferation.

#### 2. Location Analysis in ChimeraX (Structure 3KMD)
If you examine position 273 in the 3KMD structure using UCSF ChimeraX:
* **Position:** It is located directly at the protein-DNA interface.
* **Structural Context:** As a classic "DNA-contact residue," Arg273 projects outward from the core domain directly into the DNA groove, anchoring the protein to the DNA molecule.

```text
open 3kmd
sel :273
style sel ball
color sel byelement
focus sel
```

a. Paste a screenshot of your ChimeraX visualization here.  
b. Save your ChimeraX session file as `StudentID.cxs`.
