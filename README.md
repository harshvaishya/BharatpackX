::: {align="center"}
# 📦 BharatPackX

### AI-Based Intelligent Food Packaging Material Recommendation System for Food Commodities

**Smart India Hackathon 2026 · SIH26236**

```{=html}
<p>
```
`<img src="https://img.shields.io/badge/Smart%20India%20Hackathon-2026-0B6B43?style=for-the-badge" alt="Smart India Hackathon 2026">`{=html}
`<img src="https://img.shields.io/badge/Problem%20Statement-SIH26236-F28C28?style=for-the-badge" alt="SIH26236">`{=html}
`<img src="https://img.shields.io/badge/Theme-Agriculture%20%7C%20FoodTech%20%7C%20Rural%20Development-2E8B57?style=for-the-badge" alt="Theme">`{=html}
`<img src="https://img.shields.io/badge/Category-Software-4A5568?style=for-the-badge" alt="Software">`{=html}
```{=html}
</p>
```
> **Sahi Packaging • Better Shelf Life • Smarter Decisions**

BharatPackX is an AI-assisted decision-support platform that recommends
suitable food-packaging materials by combining **food commodity
properties, packaging-material characteristics, storage conditions,
cost, sustainability, shelf-life requirements, and local material
availability**.
:::

------------------------------------------------------------------------

## 🧭 Quick Navigation

-   [🎬 Project Demo](#-project-demo)
-   [💡 Why BharatPackX?](#-why-bharatpackx)
-   [🎯 Problem](#-problem)
-   [🚀 Solution](#-solution)
-   [✨ Key Features](#-key-features)
-   [🔄 How It Works](#-how-it-works)
-   [🏗️ Technical Architecture](#️-technical-architecture)
-   [🤖 AI & Recommendation Engine](#-ai--recommendation-engine)
-   [🧰 Technology Stack](#-technology-stack)
-   [📊 Recommendation Output](#-recommendation-output)
-   [🔁 Local Availability Feedback](#-local-availability-feedback)
-   [🗃️ Knowledge & Data Sources](#️-knowledge--data-sources)
-   [🛡️ Validation & Reliability](#️-validation--reliability)
-   [📁 Project Structure](#-project-structure)
-   [⚙️ Getting Started](#️-getting-started)
-   [🗺️ Roadmap](#️-roadmap)
-   [🌱 Expected Impact](#-expected-impact)
-   [📚 References](#-references)
-   [👥 Team](#-team)

------------------------------------------------------------------------

## 🎬 Project Demo

### ▶️ Watch BharatPackX in action

> **Add your YouTube video below.** Replace `YOUR_VIDEO_ID` with the ID
> from your YouTube URL.

```{=html}
<p align="center">
```
`<a href="https://www.youtube.com/watch?v=YOUR_VIDEO_ID">`{=html}
`<img src="https://img.youtube.com/vi/YOUR_VIDEO_ID/maxresdefault.jpg" alt="BharatPackX project demo" width="720">`{=html}
`</a>`{=html}
```{=html}
</p>
```
```{=html}
<p align="center">
```
`<a href="https://www.youtube.com/watch?v=YOUR_VIDEO_ID">`{=html}
`<img src="https://img.shields.io/badge/▶%20Watch%20Project%20Demo-YouTube-FF0000?style=for-the-badge" alt="Watch project demo on YouTube">`{=html}
`</a>`{=html}
```{=html}
</p>
```
**Demo video:**\
`https://www.youtube.com/watch?v=YOUR_VIDEO_ID`

```{=html}
<details>
```
```{=html}
<summary>
```
🎥 What the demo should cover
```{=html}
</summary>
```
1.  Select a food commodity
2.  Enter or upload commodity properties
3.  Use image upload / voice description
4.  Process the commodity information
5.  View recommended packaging materials
6.  Compare OTR / WVTR, thickness, cost and sustainability
7.  View shelf-life and MAP-related information
8.  View material photos and supplier details
9.  Mark a material as unavailable locally
10. View alternative-material recommendations

```{=html}
</details>
```
> **GitHub note:** GitHub supports rich Markdown and HTML formatting,
> but embedded YouTube players are not reliably rendered directly inside
> README pages. A clickable YouTube thumbnail is therefore used here as
> the portable approach.

------------------------------------------------------------------------

## 💡 Why BharatPackX?

Packaging selection is not simply a material-selection problem.

A packaging material must match the **commodity**, its **moisture and
oxygen sensitivity**, **respiration behaviour**, **storage conditions**,
**transportation environment**, **required shelf life**, **cost
constraints**, and **sustainability requirements**.

BharatPackX brings these factors together into one recommendation
workflow.

``` text
Food Commodity
      │
      ▼
Commodity Properties ──► Packaging Requirements
      │                         │
      ▼                         ▼
Storage & Transport ──► AI Recommendation Engine
                                │
                 ┌──────────────┼──────────────┐
                 ▼              ▼              ▼
             Technical        Cost       Sustainability
             Suitability    Comparison      Analysis
                 │              │              │
                 └──────────────┼──────────────┘
                                ▼
                    Best-Fit Recommendation
                                │
                                ▼
                    Local Availability Check
                                │
                       ┌────────┴────────┐
                       ▼                 ▼
                    Available       Not Available
                       │                 │
                       ▼                 ▼
                 Final Output      Alternatives
```

------------------------------------------------------------------------

## 🎯 Problem

The SIH problem statement identifies several operational gaps:

-   Packaging selection depends heavily on expert knowledge.
-   Different commodities require different packaging properties.
-   Incorrect packaging can contribute to moisture absorption, spoilage
    and ageing.
-   Oxygen and moisture permeability can be difficult to evaluate.
-   Fresh produce has changing respiration rates.
-   Farmers and small food businesses may lack packaging expertise.
-   Sustainable alternatives can be difficult to compare.
-   Manual packaging selection is time-consuming.
-   Real-world market availability of suitable materials can be
    difficult to establish.

------------------------------------------------------------------------

## 🚀 Solution

BharatPackX proposes an **AI-based packaging recommendation engine**
supported by a structured packaging knowledge database.

The platform:

**Collects → Validates → Analyses → Matches → Optimizes → Recommends**

### The system considers

  Input / Factor   Example
  ---------------- ----------------------------------------------
  Food commodity   Tomato, grains, meat, dairy, etc.
  Moisture         Moisture content / sensitivity
  Oil / fat        Oil or fat content
  pH               Commodity pH
  Respiration      Respiration rate
  Shelf life       Required storage duration
  Temperature      Storage temperature
  Humidity         Relative humidity
  Transport        Transportation conditions
  Packaging        Material and barrier properties
  Market           Local availability
  Sustainability   Recyclability / environmental considerations
  Cost             Material and packaging cost

------------------------------------------------------------------------

## ✨ Key Features

### 🍅 1. Smart Commodity Input

Users can provide information through:

-   Commodity selection
-   Manual property input
-   📷 Commodity image upload
-   🎙️ Voice description using speech-to-text
-   Storage and transportation conditions

### 🧠 2. AI-Based Recommendation

The recommendation layer combines:

-   Machine-learning models
-   Rule-based decision logic
-   Material-property matching
-   Pattern recognition
-   Packaging knowledge
-   Multi-criteria optimization

### 🧪 3. Food Property Analysis

The system can consider:

-   Nutritional / chemical properties
-   Physical properties
-   Respiration behaviour
-   Storage behaviour
-   Moisture sensitivity
-   Oxygen sensitivity

### 📦 4. Packaging Material Database

The knowledge base can contain:

-   Packaging material types
-   Barrier properties
-   OTR / WVTR data
-   Technical specifications
-   Film thickness
-   Mechanical properties
-   Sealability
-   Storage conditions
-   Sustainability information

### ⚖️ 5. Multi-Criteria Decision Support

Candidate materials can be compared using:

-   Technical suitability
-   Cost
-   Sustainability
-   Shelf-life requirements
-   MAP suitability
-   Mechanical requirements
-   Local availability

### 🔄 6. Alternative Material Recommendation

If a user reports that a recommended material is **not available in
their area**, BharatPackX can use that feedback to suggest alternative
materials that satisfy the relevant packaging requirements.

### 🏪 7. Material & Supplier Information

The recommendation result can include:

-   Material photographs
-   Material specifications
-   Listed supplier / market details
-   Availability information
-   Cost comparison

------------------------------------------------------------------------

## 🔄 How It Works

### 01 --- User / Food Commodity Input

``` text
Commodity
   +
Properties
   +
Image / Voice
   +
Storage & Transport Conditions
```

### 02 --- Data Processing

``` text
Validation
   ↓
Normalization
   ↓
Feature Extraction
```

### 03 --- Food Property Analysis

``` text
Chemical Properties
Physical Properties
Respiration
Storage Behaviour
```

### 04 --- AI Recommendation Engine

``` text
ML Models
   +
Pattern Recognition
   +
Material Matching
   +
Rule-Based Logic
```

### 05 --- Packaging Knowledge Database

``` text
Materials
Barrier Properties
OTR / WVTR
Technical Specifications
Storage Conditions
Sustainability Data
```

### 06 --- Optimization & Decision Logic

``` text
Multi-Criteria Analysis
        ↓
Cost Optimization
        ↓
Sustainability Check
        ↓
Best-Fit Selection
        ↓
Availability Feedback
        ↓
Alternative Material Suggestion
```

### 07 --- Recommendation Output

``` text
Recommended Material
        +
Technical Specifications
        +
Cost
        +
Sustainability
        +
Shelf-Life Estimate
        +
Photos / Supplier Details
```

------------------------------------------------------------------------

## 🏗️ Technical Architecture

``` mermaid
flowchart TB

    U[👥 Users<br/>Farmers · Food Processors · Startups · Packaging Professionals]

    subgraph FRONT["🌐 Presentation Layer"]
        UI[Web / Mobile Interface]
        INPUT[Commodity & Parameter Input]
        DASH[Recommendation Dashboard]
    end

    subgraph BACK["⚙️ Backend Layer"]
        API[FastAPI / REST API]
        LOGIC[Business Logic]
        ENGINE[Recommendation Engine]
    end

    subgraph AI["🤖 AI / ML Layer"]
        MATCH[Material Matching]
        BARRIER[Barrier Property Analysis]
        LIFE[Shelf-Life Estimation]
        OPT[Cost & Sustainability Optimization]
    end

    subgraph DATA["🗃️ Data Layer"]
        FOOD[Food Commodity Data]
        PACK[Packaging Material Data]
        PROP[OTR / WVTR & Material Properties]
        HIST[Historical Recommendations]
    end

    OUT[📊 Recommendation Output]

    U --> UI
    UI --> INPUT
    INPUT --> API
    API --> LOGIC
    LOGIC --> ENGINE

    ENGINE --> MATCH
    ENGINE --> BARRIER
    ENGINE --> LIFE
    ENGINE --> OPT

    MATCH <--> PACK
    BARRIER <--> PROP
    LIFE <--> FOOD
    OPT <--> HIST

    ENGINE --> OUT
    OUT --> DASH
```

------------------------------------------------------------------------

## 🤖 AI & Recommendation Engine

BharatPackX is designed around a **hybrid recommendation approach**
rather than relying only on a single ML model.

### Hybrid Intelligence

``` text
                  ┌─────────────────────┐
                  │     User Input      │
                  └──────────┬──────────┘
                             │
              ┌──────────────┴──────────────┐
              ▼                             ▼
       Rule-Based Logic                 ML Models
              │                             │
              │                    Classification /
              │                    Regression /
              │                    Prediction
              │                             │
              └──────────────┬──────────────┘
                             ▼
                    Material Matching
                             │
                             ▼
                  Multi-Criteria Ranking
                             │
                             ▼
                    Final Recommendation
```

### Why a hybrid approach?

Some packaging decisions require explicit technical constraints or
rules, while other relationships can be learned from historical or
experimental data.

The final system can therefore combine:

-   **Rules** for hard constraints and compliance-oriented checks
-   **ML models** for prediction and pattern discovery
-   **Database knowledge** for material specifications
-   **Optimization logic** for balancing multiple objectives

------------------------------------------------------------------------

## 🧰 Technology Stack

### Core Technologies

  Layer              Technologies             Purpose
  ------------------ ------------------------ ---------------------------------
  Frontend           React / Next.js          User web application
  Backend            FastAPI                  REST API and backend services
  AI / ML            Python                   Model development
  ML Models          Scikit-learn / XGBoost   Recommendation and prediction
  Image Processing   OpenCV                   Commodity image processing
  Speech             Whisper                  Voice-to-text input
  Data Processing    Pandas / NumPy           Cleaning and feature processing
  Database           PostgreSQL               Commodity & packaging data
  Deployment         Docker                   Environment and deployment
  Integration        Cloud & REST APIs        Hosting and external data

### Technology Flow

``` text
React / Next.js
       │
       ▼
FastAPI / REST API
       │
       ▼
Python Business Logic
       │
       ├──────────────► Scikit-learn / XGBoost
       │
       ├──────────────► OpenCV
       │
       ├──────────────► Whisper
       │
       ▼
PostgreSQL
       │
       ▼
Docker / Cloud Deployment
```

------------------------------------------------------------------------

## 📊 Recommendation Output

A recommendation is intended to be more than a material name.

### Example output structure

``` text
┌─────────────────────────────────────────────┐
│          RECOMMENDED PACKAGING              │
├─────────────────────────────────────────────┤
│ Material:          [Recommended Material]   │
│ OTR Range:         [Value / Range]          │
│ WVTR Range:        [Value / Range]          │
│ Film Thickness:    [Value / Range]          │
│ Gas Permeability:  [Specification]         │
│ Sealability:       [Rating / Details]       │
│ Mechanical Strength:[Rating / Details]      │
│ MAP Suitability:   [Suitable / Not suitable]│
│ Sustainability:    [Option / Details]       │
│ Cost:              [Comparison]             │
│ Shelf-Life:        [Estimate]               │
│                                             │
│ 📷 Material Photos                          │
│ 🏪 Supplier / Market Details                │
└─────────────────────────────────────────────┘
```

------------------------------------------------------------------------

## 🔁 Local Availability Feedback

One of the practical additions to BharatPackX is the ability to account
for **real-world material availability**.

``` mermaid
flowchart LR
    A[Recommended Material] --> B{Available in User Area?}
    B -->|Yes| C[Continue with Recommendation]
    B -->|No| D[User Feedback]
    D --> E[Search Suitable Alternatives]
    E --> F[Compare Technical Properties]
    F --> G[Compare Cost & Sustainability]
    G --> H[Alternative Recommendation]
```

This creates a feedback loop between the **technical recommendation**
and the **actual local market**.

------------------------------------------------------------------------

## 🗃️ Knowledge & Data Sources

The project presentation identifies the following sources /
organizations for relevant technical and regulatory knowledge:

### FSSAI

Food-contact packaging requirements, packaging materials, multilayer
packaging and safety requirements.

### BIS

Indian standards related to food packaging materials and their safe use.

### FAO

Food loss, post-harvest handling, food preservation and shelf-life
background.

### CSIR-CFTRI

Food technology, food packaging technology, food protection and safety
research.

### CSIR-CIFT

Food processing, preservation and packaging-related research,
particularly for fish and seafood.

> Regulatory and technical data should always be checked against the
> latest official publication before being used for a production
> recommendation.

------------------------------------------------------------------------

## 🛡️ Validation & Reliability

Packaging recommendations can affect food quality and safety. Therefore,
BharatPackX should treat AI outputs as **decision support**, not as a
replacement for regulatory or expert validation.

### Validation strategy

``` text
AI Prediction
     ↓
Technical Rule Check
     ↓
Regulatory / Standard Check
     ↓
Confidence Score
     ↓
Expert Validation
     ↓
Recommendation
```

### Important considerations

-   Validate material properties against reliable technical sources.
-   Verify food-contact compliance.
-   Validate shelf-life predictions against appropriate data or
    experiments.
-   Account for actual storage and transportation conditions.
-   Distinguish predicted values from experimentally verified values.
-   Keep regulatory information updated.

------------------------------------------------------------------------

## ⚠️ Challenges & Mitigation

  -----------------------------------------------------------------------
  Challenge                           Proposed Strategy
  ----------------------------------- -----------------------------------
  Limited packaging-property data     Verified packaging knowledge
                                      database

  Commodity-specific requirements     Commodity-specific feature models

  Shelf-life prediction               Historical data + validated models

  Cost vs sustainability              Multi-criteria optimization

  Changing storage conditions         Condition-based recommendations

  Need for technical validation       Expert validation + confidence
                                      scoring

  Local material availability         User feedback + alternative
                                      suggestions

  Changing regulations                Periodic verification of official
                                      sources
  -----------------------------------------------------------------------

------------------------------------------------------------------------

## 📁 Project Structure

``` text
BharatPackX/
│
├── frontend/
│   ├── components/
│   ├── pages/
│   ├── services/
│   └── assets/
│
├── backend/
│   ├── api/
│   ├── services/
│   ├── business_logic/
│   └── schemas/
│
├── ml/
│   ├── preprocessing/
│   ├── training/
│   ├── models/
│   └── inference/
│
├── database/
│   ├── schemas/
│   └── seed_data/
│
├── data/
│   ├── commodities/
│   └── packaging/
│
├── docs/
│
├── tests/
│
├── docker/
│
├── README.md
└── LICENSE
```

------------------------------------------------------------------------

## ⚙️ Getting Started

> The commands below are a suggested development structure. Update them
> to match the actual repository implementation.

### Prerequisites

-   Python 3.x
-   Node.js
-   PostgreSQL
-   Git
-   Docker

### Clone

``` bash
git clone https://github.com/YOUR_USERNAME/BharatPackX.git
cd BharatPackX
```

### Backend

``` bash
cd backend

python -m venv venv
```

Activate the environment:

**Windows**

``` bash
venv\Scripts\activate
```

**Linux / macOS**

``` bash
source venv/bin/activate
```

Install dependencies:

``` bash
pip install -r requirements.txt
```

Run the API using the project's FastAPI entry point.

### Frontend

``` bash
cd frontend
npm install
npm run dev
```

### Database

Create a PostgreSQL database and configure the connection through
environment variables.

Example:

``` env
DATABASE_URL=postgresql://USER:PASSWORD@HOST:PORT/DATABASE
```

> Never commit API keys, passwords, database credentials, or other
> secrets to GitHub.

------------------------------------------------------------------------

## 🔐 Environment Variables

A typical deployment may use:

``` env
DATABASE_URL=
API_BASE_URL=
MODEL_PATH=
STORAGE_URL=
```

Only include variables actually required by the implementation.

------------------------------------------------------------------------

## 🗺️ Roadmap

### ✅ Concept / Prototype

-   [x] Problem identification
-   [x] Technical flow
-   [x] AI recommendation concept
-   [x] Packaging knowledge-base concept
-   [x] User interface concept
-   [x] Local availability feedback concept

### 🔄 Development

-   [ ] Commodity database
-   [ ] Packaging-material database
-   [ ] Rule-based recommendation engine
-   [ ] ML recommendation models
-   [ ] Image upload pipeline
-   [ ] Speech-to-text pipeline
-   [ ] Cost comparison
-   [ ] Sustainability scoring
-   [ ] Shelf-life prediction
-   [ ] Supplier / market information

### 🚀 Validation & Deployment

-   [ ] Expert validation
-   [ ] Regulatory-data verification
-   [ ] Model evaluation
-   [ ] Real-world availability feedback
-   [ ] Security testing
-   [ ] Production deployment
-   [ ] Continuous data updates

------------------------------------------------------------------------

## 🌱 Expected Impact

BharatPackX aims to support:

-   📦 Better packaging-material selection
-   ⏱️ Faster packaging decisions
-   🧪 Commodity-specific recommendations
-   🛡️ Better packaging decision support
-   🕒 Improved shelf-life management
-   💰 Cost comparison
-   ♻️ Sustainability comparison
-   🔎 Better material-market search
-   👨‍🌾 Decision support for farmers
-   🏭 Support for small food businesses and startups

------------------------------------------------------------------------

## 📚 References

The project presentation identifies the following organizations as
research/reference sources:

-   **FSSAI** --- Food safety and food-contact packaging requirements
-   **BIS** --- Indian standards for packaging materials
-   **FAO** --- Food loss, preservation and post-harvest information
-   **CSIR-CFTRI** --- Food technology and packaging research
-   **CSIR-CIFT** --- Food processing, preservation and packaging
    research

------------------------------------------------------------------------

## 🎥 Add Your YouTube Video Later

When your final project video is uploaded:

### 1. Copy the YouTube URL

Example:

``` text
https://www.youtube.com/watch?v=ABC123XYZ
```

### 2. Extract the Video ID

``` text
ABC123XYZ
```

### 3. Replace these two values in README.md

``` text
YOUR_VIDEO_ID
```

with:

``` text
ABC123XYZ
```

The README will then show a clickable preview thumbnail and a **Watch
Project Demo** button.

------------------------------------------------------------------------

## 👥 Team

**Team ID:** 140579\
**Event:** Smart India Hackathon 2026\
**Problem Statement:** SIH26236

### BharatPackX

> **AI-Based Intelligent Food Packaging Material Recommendation System
> for Food Commodities**

------------------------------------------------------------------------

## 📄 Project Status

**Status:** Prototype / Development

This repository is intended to document the BharatPackX concept,
technical approach, prototype, AI recommendation workflow, supporting
datasets, and future implementation.

------------------------------------------------------------------------

::: {align="center"}
### 📦 BharatPackX

**Smarter Packaging Decisions for Better Food Protection**

**Smart India Hackathon 2026 · SIH26236**
:::
