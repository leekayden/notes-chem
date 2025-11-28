Notes on **Conjugation**, assumed grasp of basic organic chemistry (bonding, Lewis structures, and hybridization).

---

# Topic: Conjugation and Electron Delocalization

## 1. Core Definition
Conjugation is not merely "alternating double and single bonds."
**Definition:** A conjugated system is a continuous segment of overlapping parallel p-orbitals on adjacent atoms, allowing for the delocalization of $\pi$-electron density across the entire system.

### The Physical Requirement
*   **Orbitals:** Must have unhybridized p-orbitals.
*   **Geometry:** Atoms must be roughly **planar** to allow orbital overlap. If sterics force the molecule out of planarity, conjugation is broken (Steric Inhibition of Resonance).
*   **Hybridization:** Atoms involved are usually $sp^2$ or $sp$ hybridized.

---

## 2. Recognizing Conjugated Systems (Common Motifs)

Do not just look for $C=C-C=C$. Look for **three or more adjacent atoms** with p-orbitals.

### A. $\pi - \sigma - \pi$ (The Classic)
*   **Example:** 1,3-Butadiene ($CH_2=CH-CH=CH_2$).
*   **Structure:** Two $\pi$ bonds separated by exactly one $\sigma$ bond.
*   **Result:** The $C_2-C_3$ single bond has partial double bond character.

### B. $\pi - \sigma - \text{Lone Pair}$
*   **Example:** Allylic Anion, Vinyl Ether, Amides.
*   **Key Concept:** An atom with a lone pair next to a $\pi$ bond will **rehybridize** from $sp^3$ to $sp^2$ to put that lone pair into a p-orbital, establishing conjugation.
*   **Amide Example:** The Nitrogen in an amide is $sp^2$, not $sp^3$, creating resonance stability and making the $C-N$ bond significantly stronger/shorter.

### C. $\pi - \sigma - \text{Empty p-orbital}$ (Cation)
*   **Example:** Allylic Cation ($CH_2=CH-CH_2^+$).
*   **Significance:** Positive charge is delocalized over terminal carbons.

### D. $\pi - \sigma - \text{Radical}$
*   **Example:** Allylic Radical.
*   **Significance:** Unpaired electron is delocalized, stabilizing the radical intermediate.

---

## 3. Consequences of Conjugation

### A. Thermodynamic Stability
Conjugated systems are lower in energy than their isolated counterparts.
*   **Evidence:** Heat of Hydrogenation ($\Delta H^\circ_{hyd}$).
    *   1,4-Pentadiene (Isolated): $\approx -254 \text{ kJ/mol}$
    *   1,3-Pentadiene (Conjugated): $\approx -226 \text{ kJ/mol}$
    *   *Difference:* The conjugated diene releases less heat because it started at a lower energy state. This difference is the **Resonance Energy**.

### B. Bond Lengths
*   Single bonds in conjugated systems are **shorter** than standard alkane single bonds ($sp^2-sp^2$ overlap is shorter than $sp^3-sp^3$, plus partial $\pi$-character).
*   Double bonds are slightly **longer** than isolated alkenes due to electron delocalization.

### C. Spectroscopy (UV-Vis)
*   **HOMO-LUMO Gap:** As the length of conjugation increases, the energy gap ($\Delta E$) between the Highest Occupied Molecular Orbital (HOMO) and Lowest Unoccupied Molecular Orbital (LUMO) **decreases**.
*   **Wavelength:** Lower energy gap $\to$ longer wavelength of light absorbed ($\lambda_{max}$).
*   **Visible Region:** If conjugation is long enough (approx. 8+ conjugated double bonds), the molecule absorbs visible light and appears colored (e.g., $\beta$-carotene involves 11 conjugated double bonds $\to$ appears orange).

---

## 4. Molecular Orbital (MO) Theory Crash Course
*   **Nodes:** As you go up in energy ($\psi_1 \to \psi_2 \dots$), the number of vertical nodes increases.
*   **1,3-Butadiene:**
    *   $\psi_1$ (0 nodes): All p-orbitals in phase.
    *   $\psi_2$ (1 node): HOMO.
    *   $\psi_3$ (2 nodes): LUMO.
    *   $\psi_4$ (3 nodes): Highest energy.
*   **Frontier Orbitals:** Chemical reactions are defined by the interaction of the **HOMO** of the nucleophile and the **LUMO** of the electrophile.

---

## 5. Reactions of Conjugated Dienes

### A. Electrophilic Addition (H-X)
When HBr is added to 1,3-butadiene, two products form due to the resonance-stabilized allylic carbocation intermediate.

1.  **Direct Addition (1,2-Product):** H and Br add to adjacent carbons.
2.  **Conjugate Addition (1,4-Product):** H and Br add to the ends of the system; the double bond shifts to the middle.

#### Kinetic vs. Thermodynamic Control
*   **Low Temp (-80°C) $\to$ Kinetic Control:** The 1,2-product dominates. It forms faster because the Bromide ion attacks the $C_2$ cation immediately (proximity effect) closer to where the H added. The transition state energy is lower.
*   **High Temp (40°C) $\to$ Thermodynamic Control:** The 1,4-product dominates. The reaction is reversible at high heat. The system equilibrates to the most stable product. The 1,4-product is a **disubstituted alkene** (more stable per Zaitsev’s rule) compared to the monosubstituted 1,2-product.

### B. Pericyclic Reactions: The Diels-Alder
*   **Type:** [4+2] Cycloaddition.
*   **Reactants:** Conjugated Diene (4 $\pi$ e-) + Dienophile (2 $\pi$ e-).
*   **Mechanism:** Concerted (one step), cyclic transition state.
*   **Stereochemistry:** Retained. (Cis dienophile $\to$ cis substituent product).
*   **Requirement:** The Diene must be in the **s-cis** conformation (single bond cis). If the diene is locked in s-trans (e.g., in a rigid ring), it cannot undergo Diels-Alder.

---

## 6. Distinctions to Remember

1.  **Isolated Dienes:** Double bonds separated by $sp^3$ carbon(s). No orbital overlap. React like two separate alkenes.
2.  **Cumulated Dienes (Allenes):** $C=C=C$.
    *   The central carbon is $sp$ hybridized.
    *   The two $\pi$ systems are orthogonal (perpendicular) to each other.
    *   **NOT conjugated.**
3.  **Cross-Conjugation:**
    *   Example: Benzophenone or the divinyl ketone structure ($C=C-C(=O)-C=C$).
    *   The two double bonds conjugate with the central carbonyl, but not with each other directly. Less stable than linear conjugation.

## 7. Aromaticity (The "Gold Standard" of Conjugation)
While a separate topic, remember that Aromaticity is a specific, highly stable subset of conjugation.
*   **Criteria:** Cyclic, Planar, Fully Conjugated, Hückel's Rule ($4n+2$ $\pi$ electrons).
*   **Note:** If a system is conjugated and cyclic but has $4n$ electrons, it is **Anti-aromatic** (highly unstable).
