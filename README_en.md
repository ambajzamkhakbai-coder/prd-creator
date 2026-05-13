# prd-creator

> An intelligent tool that guides users from zero to a complete PRD document through a three-step progressive methodology

[English](README_en.md) | [简体中文](README.md)

---

## ✨ Features

- 📋 **Structured Requirements** - Say goodbye to vague requirements and broken logic
- 🔄 **Step-by-Step Confirmation** - Strict confirmation at each step ensures quality
- 📄 **Three-Stage Output** - Requirements Logic → UI/Interaction Design → PRD.md
- 📊 **Mermaid Visualization** - Flowcharts and state diagrams for clearer documentation
- 🎯 **Complete PRD Structure** - Professional-grade PRD document format

---

## 🚀 Quick Start

### Installation

Place the `prd-creator` folder into the designated directory.

### Usage

**Method 1: Active Trigger**
Select `prd-creator` Skill in conversation

**Method 2: Keyword Trigger**
```
write PRD
create PRD
product requirements
prd
```

### Example

```
Help me write a PRD for a community group-buying mini-program with core features of group buying and order management
```

---

## 📖 Workflow

```
┌─────────────────────────────────────────────────────────────┐
│                      prd-creator                            │
│               Three-Step Progressive Methodology              │
└─────────────────────────────────────────────────────────────┘
                              │
                              ▼
┌─────────────────────────────────────────────────────────────┐
│  Step 1: Requirements Logic Discussion                       │
│  ┌──────────────┐   ┌──────────────┐   ┌───────────────┐   │
│  │ Scope Define │ → │ Module Logic │ → │Requirements  │   │
│  │              │   │     Def      │   │Logic.md      │   │
│  └──────────────┘   └──────────────┘   └───────────────┘   │
└─────────────────────────────────────────────────────────────┘
                              │ (User Confirm)
                              ▼
┌─────────────────────────────────────────────────────────────┐
│  Step 2: UI + Interaction Design                           │
│  ┌──────────────────┐  ┌──────────────────┐               │
│  │ Page Structure & │→ │  UI & Interaction │               │
│  │ Navigation Flow  │  │     Design.md    │               │
│  └──────────────────┘  └──────────────────┘               │
└─────────────────────────────────────────────────────────────┘
                              │ (User Confirm)
                              ▼
┌─────────────────────────────────────────────────────────────┐
│  Step 3: Generate Final PRD                                 │
│  ┌──────────────┐   ┌──────────────┐   ┌──────────────┐    │
│  │Requirements  │ + │UI & Interact │ = │   PRD.md   │    │
│  │Logic.md      │   │  Design.md   │   │             │    │
│  └──────────────┘   └──────────────┘   └──────────────┘    │
└─────────────────────────────────────────────────────────────┘
```

### Step 1: Requirements Logic Discussion

1. **Scope Definition** - Define MVP feature boundaries and priorities
2. **Module Logic Definition** - Discuss requirements logic module by module (one at a time)
3. **Output**: `RequirementsLogic.md`

### Step 2: UI + Interaction Design

1. **Page Structure & Navigation** - List pages, draw navigation flowcharts
2. **UI & Interaction Design** - Discuss interaction design for core pages
3. **Output**: `UIInteractionDesign.md`

### Step 3: Generate Final PRD

Integrate documents from previous steps into a complete PRD:

- Product Overview
- MVP Scope
- Functional Requirements
- UI & Interaction Design
- Non-Functional Requirements
- Data Requirements
- Risks & Dependencies

---

## 📁 Project Structure

```
prd-creator/
├── SKILL.md                              # Core instruction file
├── references/
│   ├── requirement-logic-guide.md        # Requirements logic guide
│   ├── ui-interaction-guide.md           # UI & interaction design guide
│   ├── prd-structure-guide.md            # PRD structure reference
│   └── discussion-techniques.md           # Discussion guidance techniques
└── assets/
    ├── requirement-logic-template.md     # Requirements logic template
    ├── page-navigation-template.md      # Page structure & navigation template
    ├── ui-interaction-template.md       # UI & interaction design template
    └── prd-template.md                   # PRD final template
```

---

## 🎨 PRD Output Example

```markdown
# [Product Name] Product Requirements Document (PRD)

## Document Info
| Field | Content |
|---|---|
| Product Name | [Product Name] |
| Version | v1.0 |

## 1. Product Overview
## 2. MVP Scope
## 3. Functional Requirements
## 4. UI & Interaction Design
## 5. Non-Functional Requirements
## 6. Data Requirements
## 7. Risks & Dependencies
## 8. Appendix
```

---

## 🔧 Technical Implementation

- **Architecture Pattern**: Complete Workflow Type (Pattern E)
- **Freedom Level**: Medium - Strict process framework, flexible content
- **Trigger Mechanism**: Keywords + Active Selection
- **Tool Support**: AskUserQuestion, Write, Read, SearchCodebase, WebSearch

---

## 📝 Background

This Skill was created using the standard `skill-creator` framework, leveraging the SOLO MTC mode for rapid construction. Core design principles:

1. **Discuss Before Output** - Multi-round dialogue ensures accurate understanding
2. **Confirm Before Proceeding** - Avoid rework, improve efficiency
3. **Traceable Intermediate Outputs** - RequirementsLogic + UIInteractionDesign retained

---

## 🤝 Contributing

Issues and Pull Requests are welcome!

For significant changes, please open an Issue first to discuss what you'd like to change.

---

## 📄 License

[MIT License](LICENSE)

---

## 🙏 Acknowledgments

- Created based on [skill-creator](https://github.com/your-org/skill-creator) framework
- Diagrams rendered with [Mermaid](https://mermaid.js.org/)
