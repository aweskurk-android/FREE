# UI Design System Implementation Guide (Android App)

## Objective

Standardize all UI spacing across the application using **Material Design 3 principles**, then extend it with a **future dynamic density control system** inside the Appearance settings.

This guide ensures a **consistent, professional, trading-terminal-style UI** across all screens.

---

## 1. Core Principle (Important)

Before applying any custom spacing logic:

> All UI components must first conform to **Material Design 3 standards** (Android industry standard).

Only after full standardization should the **custom density system** be introduced.

---

## 2. Base Spacing System (Mandatory Standard)

All UI spacing must follow an **8dp grid system**.

### Global Rules

- Minimum usable spacing: **4dp**
- Default system spacing: **8dp**
- Section spacing: **16dp – 24dp**
- Screen-level spacing: **24dp – 32dp**

---

## 3. Component-by-Component Standards

### 3.1 Text / Labels

- Line spacing: 4dp – 6dp  
- Label → field spacing: 4dp – 8dp  
- Section heading spacing: 16dp top / 8dp bottom  

---

### 3.2 Buttons

- Minimum height: 48dp  
- Vertical padding: 12dp  
- Horizontal padding: 16dp – 24dp  
- Button spacing: 8dp  

---

### 3.3 Textboxes / Input Fields

- Height: 48dp – 56dp  
- Inner padding:
  - Top: 12dp  
  - Bottom: 12dp  
  - Left/Right: 12dp – 16dp  
- Label spacing: 4dp – 8dp  
- Field spacing: 8dp  

---

### 3.4 CardViews / Panels

- Outer margin: 12dp – 16dp  
- Inner padding: 16dp  
- Section spacing: 8dp – 12dp  
- Card-to-card spacing: 16dp  

---

### 3.5 Side Menu (Navigation Drawer)

- Item height spacing: 12dp – 16dp  
- Icon → text spacing: 8dp  
- Group spacing: 16dp – 24dp  
- Remove excessive vertical padding  

---

### 3.6 Toggles / Checkboxes

- Height alignment: 40dp – 48dp  
- Text spacing: 8dp  
- Group spacing: 8dp – 12dp  

---

### 3.7 Sliders

- Track padding: 16dp horizontal  
- Label spacing: 8dp  
- Section spacing: 12dp – 16dp  

---

### 3.8 Icons

- Icon padding: 8dp  
- Icon → text spacing: 8dp  
- Toolbar icon spacing: 12dp  

---

### 3.9 Images

- Container padding: 8dp – 12dp  
- Align consistently with cards and panels  
- Avoid oversized margins unless section-based layout requires it  

---

## 4. Global Layout Rules

### Must Fix Across ALL Screens

- Remove excessive vertical spacing everywhere  
- Ensure consistent spacing between all elements  
- Prevent double margins or overlapping padding  

### Hard Limit Rules

- No component should exceed **16dp internal padding (default max)**  
- No inconsistent spacing values across screens  

---

## 5. Density System (Future Feature Requirement)

After full UI standardization, implement a **global density control system** in the Appearance settings.

---

### 5.1 Required Sliders

#### 1. UI Density (Global Master Control)
- Range: 4dp – 16dp  
- Default: 8dp  
- Affects entire application globally  

---

#### 2. Text Density
- Controls spacing between all text elements  
- Range: 4dp – 12dp  

---

#### 3. Button Density
- Controls padding and spacing of buttons  
- Range: 4dp – 12dp  

---

#### 4. Input Field Density
- Controls spacing between labels, inputs, and groups  
- Range: 4dp – 12dp  

---

#### 5. Card / Panel Density
- Controls internal and external spacing of CardViews  
- Range: 4dp – 16dp  

---

## 6. Implementation Order (Critical)

### Step 1 — Full Standardization First

Apply Material Design spacing across:

- Buttons  
- Text  
- Inputs  
- Panels  
- Sidebar  
- Tabs  
- Forms  
- Admin panels  
- Strategy editor  
- Logs  
- Charts  
- Bet history  

---

### Step 2 — Clean Up UI Inconsistencies

Remove:

- Overlapping margins  
- Double padding issues  
- Inconsistent spacing values  
- Excess vertical gaps  

---

### Step 3 — Align Everything to 8dp Grid

Ensure:

- Consistent rhythm across all screens  
- Tight but readable UI  
- No bulky or uneven layouts  

---

### Step 4 — Add Density System

Implement Appearance tab sliders for dynamic spacing control.

---

## 7. Final Expected Result

After full implementation:

- Professional trading/betting terminal UI feel  
- Clean, structured, minimal layout  
- Zero wasted space  
- Fully consistent spacing system  
- Future-ready dynamic UI density controls  

---

## Summary

This system ensures the app evolves from a **basic UI structure → industry-grade interface design system**, with full scalability and user-controlled density customization.