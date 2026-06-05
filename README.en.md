# Nutrition Science | Hyperuricemia & Gout Dietary Guide

English version translated from the existing Chinese README.

An AI popular-science conversation assistant based on the **Dietary and Nutrition Guide for Adults with Hyperuricemia and Gout (2024 Edition)** issued by the **General Office of the National Health Commission**. | Nutrition Science Skill

> 🌱 I am new to AI and hope to use AI to share nutrition knowledge and help more people. If anything is insufficient, feedback is welcome. I will keep working on more nutrition-science skills. If you find this useful, please consider giving it a ⭐ Star. Thank you!

---

## Guideline Source

- **Full title**: *Dietary and Nutrition Guide for Adults with Hyperuricemia and Gout (2024 Edition)*
- **Issuing organization**: General Office of the National Health Commission

## Features

- **Purine data coverage**: 400+ foods with mg/100 g purine values and traffic-light classification
- **Stage-specific dietary guidance**: asymptomatic stage vs. acute flare stage, with different strategies for different phases
- **Dietary-nutrition principles**: 8 official principles centered on purine control, alcohol restriction, and drinking more water
- **TCM dietary support**: 4 syndrome patterns (damp turbidity / damp heat / phlegm-stasis / spleen-kidney deficiency) plus 24 formulas (9 teas + 15 medicated meals)
- **Regional menus**: 3 regions (inland/coastal/plateau) × 4 seasons × 2 stages × 3 energy levels = 72 sets
- **Food exchange tables**: 7 food categories for flexible meal planning
- **Popular-science style**: plain language, concrete quantities, and myth correction—precise without being condescending

## Quick Reference

| Item | Recommendation | Plain-language explanation |
|------|----------------|----------------------------|
| Daily water intake | ≥2000 mL | About 8 cups; supports uric-acid excretion |
| Purine intake (acute stage) | <150 mg/day | Less purine than in one egg |
| Purine intake (remission stage) | <300 mg/day | Control the total amount; it does not mean eating none |
| Alcohol | No alcohol during acute flares | Beer is the riskiest, spirits next |
| High-fructose beverages | Avoid or drink less | Fructose metabolism directly produces uric acid |
| Salt | <5 g/day | About one beer-bottle cap |
| Cooking oil | ≤25 g/day | No more than about two tablespoons |
| Serum uric acid target | <360 μmol/L without tophi / <300 μmol/L with tophi | Reaching target matters |

## Knowledge System

| KPK ID | Topic | Source section |
|--------|-------|----------------|
| KPK-01~08 | Eight dietary-nutrition principles | Dietary-nutrition principles chapter |
| KPK-09~15 | Appendix knowledge: purine table, exchange tables, menus, formulas | Appendices 1–7 |
| KPK-16~18 | Disease background and Q&A | Preface + disease characteristics + Q&A version |

## File Structure

```text
- gout-SKILL.md: Main skill entry file
- gout-system_prompt.md: System prompt with 7-module configuration
- gout-skill.yaml: Skill metadata
- gout-knowledge_base.md: Knowledge-base overview index
- gout-kpk_principles.md: KPK-01~07 dietary-nutrition principles
- gout-kpk_appendix.md: KPK-08~15 appendix knowledge
- gout-kpk_disease.md: KPK-16~18 disease background + Q&A
- gout-recipes_*.md: 3 regions × 24 menus
- gout-dietary_formulas.md: 24 dietary formulas
- README.md: Chinese README
- install.sh: Linux/macOS install script
- install.bat: Windows install script
```

## Statement

**Disclaimer**:
1. All content comes from the guideline above and is for dietary-nutrition popular-science reference only; it does not replace medication treatment or professional medical diagnosis.
2. It mainly targets adult patients without major complications such as renal insufficiency.
3. People with complications should use it under physician or nutrition guidance.
4. Consult professionals before using food-medicine substances.
5. This skill was built with AI assistance. Although it aims to stay faithful to the original guideline, paraphrasing errors may exist. If there is any doubt, please refer to the official published guideline text.


## Creator

**Runyuan Wang**
- Chinese Registered Dietitian
- M.S. in Nutrition and Food Hygiene, Kunming Medical University
- Built with WorkBuddy

## License

MIT

<!-- Maintainer update: Runyuan Wang (9s5bz2jvd2-lang). -->
