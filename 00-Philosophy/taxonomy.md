# 🏷️ Knowledge Graph Taxonomy (知识图谱标签系统)

This project uses a **MECE (Mutually Exclusive Collectively Exhaustive)** tagging system to track cognitive growth.

## 1. How to use (如何操作)

### Method A: File-Level Tags (YAML Frontmatter)
Use this at the very top of your `.md` files to define the overall focus of the day or week.

```yaml
---
tags:
  - NumberSense
  - Apply
  - ZoneOfProximal
date: 2025-11-20
---
```

### Method B: Item-Level Tags (Inline)
Use these tags next to specific problems to track performance on a granular level.

> **Example**:
> 1. $27 + 15 = ?$ `#NumberSense` `#Apply` `#ZoneOfProximal`

---

## 2. Tag Definitions (标签定义)

### Dimension 1: Competency (能力维度)
*What domain of knowledge is this?*
- `#NumberSense` (数感): Operations, estimation, place value.
- `#Spatial` (空间): Geometry, rotation, maps.
- `#Logic` (逻辑): Patterns, deduction, sudoku.
- `#Verbal` (语言): Vocabulary, storytelling, comprehension.

### Dimension 2: Bloom's Taxonomy (认知深度)
*How deep is the thinking process?*
- `#Remember` (记忆): Recalling facts (e.g., multiplication table).
- `#Apply` (应用): Using rules in new situations (e.g., word problems).
- `#Analyze` (分析): Breaking down complex problems (e.g., multi-step logic).
- `#Create` (创造): Designing new problems or patterns (Highest Level).

### Dimension 3: State (学习状态)
*Is this the right difficulty level?*
- `#Fluency` (熟练区): Too easy. 100% correct, fast. -> **Action**: Skip/Compress.
- `#ZoneOfProximal` (最近发展区): The "Goldilocks" zone. Needs some help but can solve. -> **Action**: Focus here.
- `#Panic` (恐慌区): Too hard. Frustration. -> **Action**: Scaffolding/Downgrade.
