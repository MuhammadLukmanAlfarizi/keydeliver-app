---
name: Academic Key Operations
colors:
  surface: '#f8f9ff'
  surface-dim: '#cbdbf5'
  surface-bright: '#f8f9ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#eff4ff'
  surface-container: '#e5eeff'
  surface-container-high: '#dce9ff'
  surface-container-highest: '#d3e4fe'
  on-surface: '#0b1c30'
  on-surface-variant: '#464555'
  inverse-surface: '#213145'
  inverse-on-surface: '#eaf1ff'
  outline: '#777587'
  outline-variant: '#c7c4d8'
  surface-tint: '#4d44e3'
  primary: '#3525cd'
  on-primary: '#ffffff'
  primary-container: '#4f46e5'
  on-primary-container: '#dad7ff'
  inverse-primary: '#c3c0ff'
  secondary: '#0058be'
  on-secondary: '#ffffff'
  secondary-container: '#2170e4'
  on-secondary-container: '#fefcff'
  tertiary: '#005338'
  on-tertiary: '#ffffff'
  tertiary-container: '#006e4b'
  on-tertiary-container: '#67f4b7'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#e2dfff'
  primary-fixed-dim: '#c3c0ff'
  on-primary-fixed: '#0f0069'
  on-primary-fixed-variant: '#3323cc'
  secondary-fixed: '#d8e2ff'
  secondary-fixed-dim: '#adc6ff'
  on-secondary-fixed: '#001a42'
  on-secondary-fixed-variant: '#004395'
  tertiary-fixed: '#6ffbbe'
  tertiary-fixed-dim: '#4edea3'
  on-tertiary-fixed: '#002113'
  on-tertiary-fixed-variant: '#005236'
  background: '#f8f9ff'
  on-background: '#0b1c30'
  surface-variant: '#d3e4fe'
typography:
  display-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 36px
    fontWeight: '700'
    lineHeight: 44px
    letterSpacing: -0.025em
  display-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 28px
    fontWeight: '700'
    lineHeight: 36px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 28px
    fontWeight: '700'
    lineHeight: 36px
    letterSpacing: -0.02em
  headline-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 22px
    fontWeight: '700'
    lineHeight: 28px
    letterSpacing: -0.015em
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 22px
    fontWeight: '600'
    lineHeight: 28px
    letterSpacing: -0.015em
  headline-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 18px
    fontWeight: '600'
    lineHeight: 24px
    letterSpacing: -0.01em
  title-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 16px
    fontWeight: '600'
    lineHeight: 22px
    letterSpacing: -0.005em
  body-lg:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
    letterSpacing: 0em
  body-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
    letterSpacing: 0em
  body-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 16px
    letterSpacing: 0.01em
  label-lg:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.005em
  label-md:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.02em
  label-sm:
    fontFamily: Inter
    fontSize: 10px
    fontWeight: '700'
    lineHeight: 14px
    letterSpacing: 0.05em
  data-mono:
    fontFamily: Inter
    fontSize: 13px
    fontWeight: '500'
    lineHeight: 18px
    letterSpacing: 0.02em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1.5rem
  gutter-mobile: 0.75rem
  margin: 2rem
  margin-mobile: 1rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2rem
---

## Brand & Style

The design system establishes a high-precision, utilitarian operational environment for academic institutions managing classroom logistics, security, and key handovers. The visual tone balances administrative authority with frictionless daily usability. It delivers immediate cognitive clarity to facility coordinators, security personnel, lecturers, and student staff who must assess room availability and key custody at a glance.

The aesthetic blends **Modern Corporate SaaS** with **Tactile Utility UI**. High-density data tables and status-driven card matrices are structured through slate grey surface tiers, eliminating visual clutter while highlighting operational state changes. Primary branding utilizes concentrated indigo and cobalt tones to emphasize administrative actions, while vivid semantic indicators provide unmistakable signals for real-time occupancy. Interactions feel instantaneous, durable, and engineered for high-frequency daily routines across both front-desk monitors and mobile handheld devices.

## Colors

The palette is engineered around clean slate neutrals paired with assertive signal colors for key and room telemetry.

### Core Architecture
- **Primary Indigo (`#4F46E5`)**: Primary workflows, key dispatch confirmation, active navigation states, and dominant focal points.
- **Secondary Cobalt (`#3B82F6`)**: Secondary operations, active filters, informational badges, and interactive links.
- **Neutral Foundation**: Built on the slate spectrum. Light mode surfaces utilize Slate-50 (`#F8FAFC`) for page canvases, Slate-100 (`#F1F5F9`) for nested containers and disabled elements, Slate-200 (`#E2E8F0`) for structural borders, Slate-800 (`#1E293B`) for headings, and Slate-900 (`#0F172A`) for high-contrast labels.

### Semantic Telemetry
- **Available / "KOSONG" (`#10B981`)**: Pure emerald green paired with a subtle tinted surface (`#ECFDF5`) and border (`#A7F3D0`). Signifies key available in cabinet or room unoccupied.
- **Occupied / "TERPAKAI" (`#F43F5E`)**: Rose red paired with tinted surface (`#FFF1F2`) and border (`#FECDD3`). Signifies active checkout, lecture in progress, or unreturned custody.
- **Pending / In Transit (`#F59E0B`)**: Amber caution indicator for keys undergoing handover, scheduled transfer, or overdue grace periods.

Dark mode reverses the hierarchy, applying Slate-900 (`#0F172A`) as the base canvas, Slate-800 (`#1E293B`) as the card surface, and Slate-700 (`#334155`) for borders, ensuring identical semantic legibility under night operations.

## Typography

The type system pairs **Plus Jakarta Sans** for structural headlines with **Inter** for data grids, telemetry tokens, body text, and forms. 

Plus Jakarta Sans brings modern, geometric precision with welcoming terminal curves, avoiding the sterile austerity common in academic legacy software. Inter serves as the workhorse for dense logistical listings: its tall x-height, clear numeric tabular spacing, and distinction between glyphs ensure mistake-free reading of classroom numbers (e.g., distinguishing "B-101" from "B-I01") and student ID digits.

All status badges (`label-sm`) leverage uppercase tracking (`0.05em`) and bold weights to guarantee instantaneous visual parsing under ambient glare or quick handheld glance.

## Layout & Spacing

The design system operates on an 8-point base spatial grid, using a 4-point subgrid for fine component alignment, icon pairing, and tight data cells.

### Grid Architecture
- **Desktop (≥1280px)**: 12-column fluid grid, 2rem margins, 1.5rem gutters. Dedicated fixed-width left navigation rail (260px) and contextual drawer panel (380px) for key custody tracking.
- **Tablet (768px - 1279px)**: 8-column layout, 1.5rem margins, 1rem gutters. Left rail collapses to a compact icon dock (72px).
- **Mobile (<768px)**: 4-column layout, 1rem margins, 0.75rem gutters. Bottom-anchored action bar replaces sidebar navigation for thumb-friendly handovers and scanning operations.

### Data Densities
- **Compact Matrix View**: Used in high-throughput key cabinets; 0.5rem cell padding (`space-sm`) and 0.5rem gap to fit maximum rooms per viewport.
- **Standard Card View**: Used in delivery schedules and room profiles; 1rem padding (`space-md`) with 1rem grid gap.

## Elevation & Depth

Visual hierarchy uses a refined hybrid of **tonal surface separation** and **ambient low-opacity elevation**, keeping the interface crisp, utilitarian, and glare-free.

- **Level 0 (Canvas Base)**: `#F8FAFC` (Slate-50). The master background layer. Flat with zero shadow.
- **Level 1 (Card & Row Surfaces)**: `#FFFFFF`. Paired with a 1px solid border in Slate-200 (`#E2E8F0`) and an ambient shadow: `0 1px 3px 0 rgba(15, 23, 42, 0.05)`. Used for key inventory tiles, room status cards, and table bodies.
- **Level 2 (Hover & Filter Popovers)**: `#FFFFFF`. Border in Slate-200, elevated with `0 4px 6px -1px rgba(15, 23, 42, 0.07), 0 2px 4px -2px rgba(15, 23, 42, 0.05)`. Indicates interactive engagement or active dropdown selects.
- **Level 3 (Modals & Delivery Slips)**: `#FFFFFF`. Border in Slate-200, elevated with `0 20px 25px -5px rgba(15, 23, 42, 0.1), 0 8px 10px -6px rgba(15, 23, 42, 0.04)`. Anchors key checkout confirmation dialogs, QR scanners, and incident reports.

Dark mode substitutes Slate-900 canvas, Slate-800 card containers, and Slate-700 borders, elevating surfaces using light tonal shifts rather than cast shadows.

## Shapes

The design system standardizes on a balanced **Level 2 (Rounded)** shape scale. 

- **Base Controls (`0.5rem` / 8px)**: Form inputs, standard buttons, badge chips, dropdown items, and cabinet slot indicators.
- **Large Surfaces (`1rem` / 16px)**: Room overview cards, metric stat containers, QR delivery slips, and floating modals.
- **Extra Large Containers (`1.5rem` / 24px)**: Outer dashboard layout splitters, slide-over sheets, and contextual drawers.
- **Fully Rounded / Pill (`9999px`)**: Telemetry state badges (`KOSONG`, `TERPAKAI`), user avatars, and quick-filter pills.

Borders are razor-thin (1px), never obtrusive, providing clean definition between high-density operational data points.

## Components

### Buttons
- **Primary**: Solid Indigo (`#4F46E5`) with pure white text, font weight 600, radius `0.5rem`. Hover state transitions to `#4338CA`. Active state scales subtly (`0.98`).
- **Secondary**: Slate-100 (`#F1F5F9`) background with Slate-800 text and Slate-200 border. Transitions to Slate-200 on hover.
- **Destructive**: Rose Red (`#F43F5E`) surface with white text, reserved for overdue flaggers, missing key declarations, and checkout cancellations.

### Status Chips (Room & Key State)
- **KOSONG (Available)**: Background `#ECFDF5`, border 1px solid `#A7F3D0`, text `#065F46`. Accompanied by a 6px solid emerald pulsating dot.
- **TERPAKAI (Occupied)**: Background `#FFF1F2`, border 1px solid `#FECDD3`, text `#9F1239`. Accompanied by a 6px solid rose dot.
- **PENDING (Handover in Progress)**: Background `#FEF3C7`, border 1px solid `#FDE68A`, text `#92400E`.

### Cards & Key Tiles
- Standard room cards incorporate a 3-zone structure:
  1. **Header**: Classroom code (e.g., `LAB-302`, `R-104`) in `headline-sm`, paired with the live status chip.
  2. **Body**: Key custodian name, lecturer title, and scheduled time slot in `body-sm`.
  3. **Footer**: One-tap action ("Serahkan Kunci" / Handover Key) or return scan trigger.

### Tables (Inventory & Logbook)
- Sticky headers using Slate-100 background and Slate-700 `label-md` typography.
- Rows use 1px bottom border in Slate-200, alternating hover states in Slate-50.
- Columns align room codes and timestamps with tabular mono numbers to ensure vertical scannability.

### Form Inputs & Search
- Inputs feature Slate-50 surface, Slate-200 border, and Slate-900 text.
- Focus state reveals a 2px outer ring in Indigo (`#4F46E5`) with an offset of 2px.
- Specialized barcode/QR input fields feature a dedicated scanning indicator icon and immediate validation styling.

### Domain-Specific Components
- **Key Ring Pin**: A miniature badge component showing physical cabinet slot coordinates (e.g., `Slot A-14`).
- **Delivery Log Stepper**: A vertical trace component tracking checkout request, security clearance, lecturer receipt, and return verification.