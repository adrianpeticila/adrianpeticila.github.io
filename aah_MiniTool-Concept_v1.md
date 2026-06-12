# aah.monster — Free Mini-Tool Concept
**Sursa:** Lecție din marketingideas.com ($0 marketing) + positioning Adrian
**Data:** 30 Mai 2026

---

## Conceptul: "The B2B Bullshit Detector"

**URL propus:** `aah.monster/bullshit` sau `aah.monster/detector`

**One-liner:** Paste your copy. Find out how corporate you sound.

**Ce face:**
Utilizatorul lipește copy-ul lui (website, LinkedIn, email, pitch deck) și primește:
1. **Bullshit Score** — 0-100 (cu cât mai mare, cu atât mai rău)
2. **Cuvinte flagged** — highlight pe: leverage, synergy, seamlessly, dive into, scalable, innovative, best-in-class, thought leader, holistic, ecosystem, strategic, robust, streamline, empower, disruptive + lista completă
3. **Top 3 cele mai grave fraze** — cu rewrite sugestii în limbaj uman
4. **CTA hard:** "Vrei fix complet? Adrian rescrie tot." → link booking

**De ce funcționează pentru aah.monster:**
- Problema rezolvată = exact ce face Adrian (anti-corporate speak)
- Gratuit, zero friction (fără email, fără cont)
- Fiecare utilizator = lead calificat (are copy de reformat = are nevoie de Adrian)
- SEO natural: "b2b copy checker", "corporate jargon detector", "linkedin bio checker"
- Viral sharing: oamenii vor testa și vor trimite colegilor / vor posta scorul

**Cum se construiește (MVP):**
- Static HTML + JavaScript — regex pe lista de cuvinte flagged
- Fără backend, fără baze de date
- Deploy pe `aah.monster/bullshit` cu header + CTA Adrian

**Efort estimat:** 2-4 ore cu Claude Code (HTML/JS/CSS)
**Efort marketing:** 0 — tool-ul se distribuie singur

---

## Upgrade path (după MVP)
- v2: Readability score (Flesch-Kincaid)
- v2: "Human score" pe fiecare paragraf
- v3: API Claude care generează rewrite complet (premium / paid feature)

---

## Product Hunt angle
- Categoria: Marketing Tools
- Tagline: "How corporate does your copy sound?"
- Launch după ce ai 50+ utilizatori organici

---

## Note pentru implementare
- Rulează `/design-shotgun` → `/design-html` când începi build-ul
- Copy-ul tool-ului: vocea Adrian — nu "helpful", ci judecă fără menajamente
- Exemplu tone: "Your copy scored 73/100. That's pharmaceutical-grade corporate speak."
- Nu cere email pe tool — zero friction e regula #1
