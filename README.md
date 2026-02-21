<h1 align="center">CycleWise (CycleCare) 🎯</h1>

## Basic Details
* **Team Name:FAAAAHHHH
* **Team Members:**
  * Member 1: Malavika.P - St.Joseph's College(Autonomous) Devagiri
  * Member 2: Likitha A S-  St.Joseph's College(Autonomous) Devagiri
* **Hosted Project Link:**https://cyclecare-dun.vercel.app

## Project Description
CycleWise is an intelligent, emotionally-aware menstrual cycle tracker and travel survival guide. It moves beyond traditional clinical tracking to provide actionable, phase-specific insights for travel readiness, food intelligence, and emergency preparedness.

## The Problem statement
Standard period trackers are often overly clinical, infantilizing, or focused strictly on fertility and dates. People who menstruate, especially when traveling or managing health conditions (like PCOS, Endometriosis, or Anemia), lack non-judgmental, practical guidance on what to pack, what to eat depending on their location, and how to handle sudden symptoms safely on the road.

## The Solution
CycleWise fixes this by shifting the focus to **actionable intelligence**. Based on a user's cycle phase, travel mode (e.g., Backpacking, Train, Flight), and health profile, it provides:
* **Smart Kit Generation:** Dynamically builds a packing list.
* **Food Intelligence:** Tells you exactly what to eat at a roadside stall vs. a cafe depending on your hormonal needs.
* **Red Flag Guides:** Helps distinguish between normal discomfort and medical emergencies.

## Technical Details
### Technologies/Components Used
**For Software:**
* **Languages used:** HTML5, CSS3, Vanilla JavaScript
* **Frameworks used:** None (Pure Vanilla Implementation for maximum speed and portability)
* **Libraries used:** None
* **Tools used:** Git, GitHub

**For Hardware:**
* Not applicable for this software project.

## Features
* **Feature 1: Smart Kit Generator:** Dynamically generates personalized travel packing lists based on the user's cycle phase, travel duration, transport mode, and specific health conditions.
* **Feature 2: Venue-Aware Food Intelligence:** Provides phase-specific dietary recommendations mapped directly to common travel environments (Railway Stations, Hostels, Cafes, Roadside).
* **Feature 3: Emergency & SOS Mode:** Offers immediate, clear action steps for severe symptoms and a one-click simulated SOS UI for extreme safety situations.
* **Feature 4: Condition-Specific Filtering:** Users can toggle health conditions (like Heavy Bleeding or PCOS) to instantly filter and adapt travel safety tips and food recommendations.

## Implementation
### For Software:

#### Installation
This is a lightweight client-side application. No package installation is required.
```bash
git clone https://github.com/aslikitha16-hub/cyclecare.git
cd cyclecare
```

#### Run
Simply open the main file in any modern web browser:
```bash
# On Windows
start "index.html" 

# On Mac
open "index.html"
```
*(Tip: You may want to rename `cycle-tracker (7).html` to `index.html` for easier hosting!)*

## Project Documentation
### For Software:

**Screenshots**

(https://drive.google.com/file/d/1r8FQUk7Z1ePRtvDZ_OXyr0gbqll5soOS/view?usp=drive_link) 
*Caption: The main mobile-first dashboard showing Live Cycle Status and Travel Readiness.*

https://drive.google.com/file/d/1_nK6D4ig-TlgLIJuzTL-AGZEhWP5Dj7P/view?usp=drive_link

https://drive.google.com/file/d/1R1CQljF3c0r6HV2-nZPtrnZtujC450Sy/view?usp=drive_link
## Diagrams
### System Architecture:
Because CycleWise is a highly portable client-side application designed to be instantly accessible even with poor internet connectivity, the architecture currently consists of a unified structure where HTML, CSS, and Vanilla JavaScript execute entirely within the DOM. 

* **Data Flow:** User Input (Toggles, Dropdowns) ➡️ JS Logic Engine ➡️ DOM Manipulation (showing/hiding relevant HTML panels and updating active tokens). 

### Application Workflow:
1. **User lands on Dashboard** ➡️ Views current Phase hero card and active Cycle status.
2. **User Navigates to Tools** ➡️ Interacts with the Kit Generator by selecting travel mode and conditions.
3. **JS Engine evaluates parameters** ➡️ Generates a customized packing checklist dynamically.
4. **User references Food Intelligence** ➡️ Selects current venue type ➡️ Receives filtered dietary advice without reloading the page.

---
*Generated for tink-her-hack*
