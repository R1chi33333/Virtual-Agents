# VR Study: Identity Continuity & User Relationship with Multi-Form Virtual Agents

## Study Overview  
Four open-source VR demos are used, each featuring a different **agent form**.  
Identity continuity is manipulated between subjects.

| VR Demo | Agent Form | Scene Focus |
|---------|------------|-------------|
| **Escape Room** | Embodied (human) | Puzzle solving |
| **The World Beyond** | Animal partner | Companion exploration |
| **Phanto** | Object-based (weapon AI) | MR shooting / cleaning |
| **Whisperer (reworked)** | Voice-only | Dialogue-driven puzzle |

### Conditions
| Condition | Identity Treatment | Key Notes |
|-----------|-------------------|-----------|
| **C1 (identity discontinuous)** | Four different names, voices, color themes (A/B/C/D) | Each agent is a unique persona |
| **C2 (identity continuous)** | Same name, voice & signature color across all four demos | Minor cosmetic tweaks only |

---

## Research Question  
> Does keeping the **same identity** across visually different agents improve users’ **rapport**, **connectedness**, and **credibility** in VR?

---

## Hypotheses
| ID | Statement |
|----|-----------|
| **H1 (Rapport)** | Continuous identity → higher rapport scores than discontinuous identity. |
| **H2 (Connectedness)** | Continuous identity → higher connectedness scores than discontinuous identity. |

*(Credibility is explored qualitatively; no directional hypothesis tested.)*

---

## Measurements

| Construct | Method | Scale / Source | When collected |
|-----------|--------|----------------|----------------|
| **Rapport** | Quantitative | HARQ (7-point Likert) | **Immediately after each scene** (4 times) |
| **Connectedness / Closeness** | Quantitative | IOS (Inclusion of Other in Self) *or* RISC scale (7-point Likert) | **Immediately after each scene** (4 times) |
| **Credibility** | **Qualitative only** | Semi-structured exit interview (audio-recorded) | **Once, after all four scenes** |
| **Manipulation Check** | Single Likert item—“Were the agents the same individual?” | 7-point Likert | After final scene |

---

## Methodology

### 1. Participants  
- **Sample size:**   
- **Recruitment:** 
- **Assignment:** 

### 2. Design  
| Factor | Levels | Type |
|--------|--------|------|
| **Identity Continuity** | Continuous vs. Discontinuous | **Within-subjects** |

> Dependent variables: **Rapport score**, **Connectedness score** (scene-by-scene).  **Perceived trustworthiness** (exit interview).
> Qualitative outcome: **Perceived trustworthiness** (exit interview).

### 3. Apparatus & Materials  
- **Hardware:** 
- **VR demos:**  
  1. *Escape Room* – Embodied agent  
  2. *The World Beyond* – Animal agent  
  3. *Phanto* – Object-based agent (weapon AI)  
  4. *Whisperer* (re-scripted) – Voice-only agent  
- **Identity manipulation:**  
  - *Continuous* group: same name, same voice, same keyfeatures.  
  - *Discontinuous* group: unique names, voices, colors (A/B/C/D) per demo.  
- **Questionnaires:**  
  - **Rapport Scale**  HARQ (7-point Likert)
  - **Connectedness:** 
  - **Manipulation-check:** “These assistants felt like the same person” (1–7 Likert)

### 4. Procedure  
1. **Briefing & Consent** → demographic survey.  
2. Participants experience **all four demos**   
3. **After each demo** → Immediate Likert survey (Rapport + Connectedness).  
4. **Post block:**  
   - Manipulation-check item  
   - **Exit interview** (audio-recorded, 10 min): credibility, moments of high/low trust, impact of identity cues.  
5. **Debrief & compensation**.

### 5. Data Analysis  
- **Quantitative:** 2 (Identity) × 4 (Scene) mixed ANOVA (or linear mixed-effects) on Rapport & Connectedness.  
  - Post-hoc pairwise (Bonferroni) if interaction significant.  
  - Cronbach’s α to confirm Rapport scale reliability.  
- **Qualitative:**
- **Manipulation-check:**


> **Outcome:** This mixed-method design quantifies how identity continuity influences rapport & connectedness across four agent forms, and qualitatively explains the trust mechanisms behind those effects.





## Study Flow — Two Experimental Conditions

### Condition 1 – Identity Discontinuous
```mermaid
flowchart TD
    A["Briefing / Consent<br/>Discontinuous group"]
    S1["Scene 1<br/>Escape Room<br/>Agent A"]
    R1["Rapport Survey #1"]
    S2["Scene 2<br/>World Beyond<br/>Agent B"]
    R2["Rapport Survey #2"]
    S3["Scene 3<br/>Phanto<br/>Agent C"]
    R3["Rapport Survey #3"]
    S4["Scene 4<br/>Whisperer<br/>Agent D"]
    R4["Rapport Survey #4"]
    P["Post block<br/>Connectedness (IOS)<br/>Trust Interview"]
    D["Debrief"]
    A --> S1 --> R1 --> S2 --> R2 --> S3 --> R3 --> S4 --> R4 --> P --> D




### Condition 2 – Identity Continuous
```mermaid
flowchart TD
    A["Briefing / Consent<br/>Continuous group"]
    S1["Scene 1<br/>Escape Room<br/>Lumi"]
    R1["Rapport Survey #1"]
    S2["Scene 2<br/>World Beyond<br/>Lumi"]
    R2["Rapport Survey #2"]
    S3["Scene 3<br/>Phanto<br/>Lumi"]
    R3["Rapport Survey #3"]
    S4["Scene 4<br/>Whisperer<br/>Lumi"]
    R4["Rapport Survey #4"]
    P["Post block<br/>Connectedness (IOS)<br/>Trust Interview"]
    D["Debrief"]
    A --> S1 --> R1 --> S2 --> R2 --> S3 --> R3 --> S4 --> R4 --> P --> D


