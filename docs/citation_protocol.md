# **Citation Protocol — Critique Layer**

**Critique → Gradient → RTT/1**

Citation in Critique is not academic.  
It is **structural provenance** — a record of where an idea came from, how it was expressed, and what sources shaped its initial form.

Critique citations ensure that every idea entering Gradient has:

- a clear origin  
- a traceable influence surface  
- a minimal provenance chain  
- a stable handoff into alignment  

---

## **1. Citation Declaration**

```
citation_protocol:
  layer: critique
  purpose: structural provenance
  mode: S/R/E compatible
  output: citation_packet
```

---

## **2. What Counts as a Citation in Critique**

Critique recognizes three types of citations:

### **(1) Origin Citation**
Where the idea came from.

```
origin:
  source: <person | document | conversation | artifact>
  context: <where the idea emerged>
```

### **(2) Influence Citation**
What shaped the idea before submission.

```
influences:
  - source: <book | article | video | model output | conversation>
    role: <informative | inspirational | corrective>
```

### **(3) Constraint Citation**
What limits or bounds the idea.

```
constraints:
  - source: <rule | requirement | boundary>
    effect: <how it shapes the idea>
```

---

## **3. Citation Packet Structure**

This is the object Critique produces and hands off to Gradient.

```
citation_packet:
  origin: <origin object>
  influences: <list>
  constraints: <list>
  clarity_links: <optional references>
```

The packet is intentionally minimal — Gradient expands it during alignment.

---

## **4. Interaction with S/R/E Modes**

Citation interacts with Critique’s triad:

### **S‑mode (Structure)**  
Citations reveal the structural frame of the idea.

### **R‑mode (Resonance)**  
Citations reveal conceptual frequencies and influences.

### **E‑mode (Energy)**  
Citations reveal activation forces and motivational sources.

---

## **5. Handoff to Gradient**

The citation packet is passed directly into:

**Gradient — Alignment Layer**  
`gradient/docs/attunement_template.md`

Gradient uses the packet to:

- stabilize coherence  
- bound drift  
- declare paradox  
- prepare the idea for RTT/1  

---

## **6. Output Format**

```
citation_output:
  layer: critique
  packet: <citation_packet>
  ready_for: gradient
```

---

## **7. License**

Open educational use permitted.
