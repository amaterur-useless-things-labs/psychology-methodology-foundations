# Course Material Status System

## Status Badges

All course materials must be marked with one of the following badges at the beginning of the file:

### 🤖 **AI-Generated**
**Status:** Initial  
**Description:** Content created with AI assistance, requires expert review.

**Format:**
```markdown
---
**Material Status:** 🤖 AI-Generated — requires review
**Date Created:** [date]
**Date Reviewed:** not reviewed
---
```

---

### 🔍 **Under Review**
**Status:** In Progress  
**Description:** Material is currently being reviewed by an expert.

**Format:**
```markdown
---
**Material Status:** 🔍 Under Review
**Reviewer:** [First Name Last Name], [Academic Degree], [Position]
**Review Start Date:** [date]
---
```

**Example:**
```markdown
---
**Material Status:** 🔍 Under Review
**Reviewer:** John Smith, Ph.D. in Psychology, Associate Professor
**Review Start Date:** 2024-01-15
---
```

---

### ⚠️ **Partially Reviewed**
**Status:** Partial  
**Description:** Material is partially reviewed, some sections verified.

**Format:**
```markdown
---
**Material Status:** ⚠️ Partially Reviewed
**Reviewed by:** [First Name Last Name], [Academic Degree], [Position]
**Reviewed Sections:** [list of sections]
**Review Date:** [date]
**Notes:** [if any]
---
```

**Example:**
```markdown
---
**Material Status:** ⚠️ Partially Reviewed
**Reviewed by:** John Smith, Ph.D. in Psychology, Associate Professor
**Reviewed Sections:** Introduction, Problem Statement, sections 3.1-3.3
**Review Date:** 2024-01-20
**Notes:** Sections 3.4-3.5 require additional review
---
```

---

### ✅ **Reviewed**
**Status:** Complete  
**Description:** Material is fully reviewed and approved by an expert.

**Format:**
```markdown
---
**Material Status:** ✅ Reviewed
**Reviewed by:** [First Name Last Name], [Academic Degree], [Position/Title]
**Review Date:** [date]
**Version:** [version, if applicable]
**Notes:** [if any]
---
```

**Example:**
```markdown
---
**Material Status:** ✅ Reviewed
**Reviewed by:** Jane Doe, Ph.D. in Psychology, Professor of Psychology
**Review Date:** 2024-02-01
**Version:** 1.0
**Notes:** Material ready for use
---
```

---

## Academic Degrees and Titles (References)

When indicating the reviewer, use the following abbreviations:

### Academic Degrees
- **Ph.D. in Psychology** — Doctor of Philosophy in Psychology
- **Ph.D. in Philosophy** — Doctor of Philosophy in Philosophy
- **Ph.D. in Biology** — Doctor of Philosophy in Biology
- **M.A. in Psychology** — Master of Arts in Psychology
- **M.Sc. in Psychology** — Master of Science in Psychology

### Academic Titles
- **Associate Professor** — Associate Professor
- **Professor** — Professor
- **Senior Research Fellow** — Senior Research Fellow

### Examples of Correct References

**Option 1 (Full):**
```
Reviewed by: John Smith, Ph.D. in Psychology, Professor of Psychology
```

**Option 2 (Brief):**
```
Reviewed by: J. Smith, Ph.D., Professor
```

**Option 3 (with institution):**
```
Reviewed by: Jane Doe, Ph.D., Associate Professor, Harvard University
```

---

## Status Update Process

1. **Initially:** All materials have status 🤖 **AI-Generated**
2. **When review starts:** Status changes to 🔍 **Under Review** with reviewer information
3. **When partially reviewed:** Status changes to ⚠️ **Partially Reviewed** with reviewed sections indicated
4. **When review completed:** Status changes to ✅ **Reviewed** with full review information

---

## Template for Lecture File Header

Copy this template to the beginning of each lecture file:

```markdown
---
**Material Status:** 🤖 AI-Generated — requires review
**Date Created:** [date]
**Date Reviewed:** not reviewed
**Reviewed by:** not reviewed
---

# [Lecture Title]
```

After review, update the template accordingly.

---

## Review Checklist

When reviewing material, the expert should check:

- [ ] Accuracy of facts and statements
- [ ] Correctness of literature references
- [ ] Content relevance to lecture topic
- [ ] Logical structure of material
- [ ] Clarity of exposition
- [ ] Compliance with academic standards
- [ ] Presence of all necessary sections (according to structure)
- [ ] Correctness of terminology
- [ ] Absence of contradictions

After review, fill in the material status with review results.

