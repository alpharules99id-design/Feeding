---
name: Industrial Precision
colors:
  surface: '#FFFFFF'
  surface-dim: '#dadada'
  surface-bright: '#f9f9f9'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f3f3f3'
  surface-container: '#eeeeee'
  surface-container-high: '#e8e8e8'
  surface-container-highest: '#e2e2e2'
  on-surface: '#1a1c1c'
  on-surface-variant: '#414752'
  inverse-surface: '#2f3131'
  inverse-on-surface: '#f1f1f1'
  outline: '#717783'
  outline-variant: '#c1c6d4'
  surface-tint: '#005faf'
  primary: '#005dac'
  on-primary: '#ffffff'
  primary-container: '#1976d2'
  on-primary-container: '#fffdff'
  inverse-primary: '#a5c8ff'
  secondary: '#4c616c'
  on-secondary: '#ffffff'
  secondary-container: '#cfe6f2'
  on-secondary-container: '#526772'
  tertiary: '#00685c'
  on-tertiary: '#ffffff'
  tertiary-container: '#1a8375'
  on-tertiary-container: '#f7fffc'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d4e3ff'
  primary-fixed-dim: '#a5c8ff'
  on-primary-fixed: '#001c3a'
  on-primary-fixed-variant: '#004786'
  secondary-fixed: '#cfe6f2'
  secondary-fixed-dim: '#b4cad6'
  on-secondary-fixed: '#071e27'
  on-secondary-fixed-variant: '#354a53'
  tertiary-fixed: '#97f3e2'
  tertiary-fixed-dim: '#7ad7c6'
  on-tertiary-fixed: '#00201b'
  on-tertiary-fixed-variant: '#005047'
  background: '#f9f9f9'
  on-background: '#1a1c1c'
  surface-variant: '#e2e2e2'
  success: '#4CAF50'
  warning: '#FFC107'
  danger: '#F44336'
  border: '#E0E0E0'
  text-primary: '#212121'
  text-secondary: '#616161'
typography:
  headline-lg:
    fontFamily: Inter
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
    letterSpacing: -0.02em
  headline-md:
    fontFamily: Inter
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  headline-sm:
    fontFamily: Inter
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
  body-lg:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  body-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  label-md:
    fontFamily: JetBrains Mono
    fontSize: 13px
    fontWeight: '500'
    lineHeight: 16px
  label-sm:
    fontFamily: JetBrains Mono
    fontSize: 11px
    fontWeight: '500'
    lineHeight: 14px
    letterSpacing: 0.05em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  unit: 4px
  gutter: 16px
  margin: 24px
  container-max: 1440px
---

## Brand & Style

This design system is engineered for the Dairy Feeding Management System (DFMS), focusing on the high-stakes environment of industrial agriculture. The brand personality is **authoritative, efficient, and resilient**. It prioritizes utility over decoration, ensuring that operators can manage complex mixing and distribution tasks with zero cognitive friction.

The design style is **Corporate / Modern**, drawing heavily from SAP Fiori and Microsoft Fluent. It utilizes a systematic approach to density and hierarchy, ensuring that data-heavy dashboards remain legible under various lighting conditions found in farm environments. The aesthetic is clean and structured, using subtle shadows and crisp borders to define workspaces without unnecessary visual noise.

## Colors

The palette is rooted in industrial standards to ensure immediate recognition of system statuses. 

- **Primary (#1976D2):** Used for primary actions, active navigation states, and essential system branding.
- **Surface & Background:** A light gray background (#F5F5F5) reduces screen glare, while pure white (#FFFFFF) is reserved for interactive cards and data tables to create clear visual separation.
- **Semantic Logic:** 
    - **Success (#4CAF50):** Indicates completed cycles (Finish) or healthy KPIs.
    - **Warning (#FFC107):** Used for "Mixing" or "OTW" (On The Way) states and low-inventory alerts.
    - **Danger (#F44336):** Reserved for critical errors, depleted inventory, or stopped machinery.
- **Neutral High-Density:** Grays are utilized for borders and secondary text to maintain a professional, low-fatigue environment for long shifts.

## Typography

**Inter** is selected as the primary typeface for its exceptional legibility and neutral, professional tone. It excels in high-density data environments like feeding schedules and warehouse manifests.

For technical data points, status badges, and precise measurements (kg, lbs, %), **JetBrains Mono** is introduced. This monospaced font ensures that numerical values align perfectly in tables, allowing operators to scan for discrepancies in mixing ratios rapidly. 

Headlines use tighter letter spacing to maintain a compact, "built" feel, while body text maintains standard spacing for maximum readability during rapid data entry.

## Layout & Spacing

The layout follows a **Fixed Grid** philosophy for the desktop-first dashboard, ensuring a consistent placement of key telemetry data.

- **Grid System:** A 12-column grid with 16px gutters. In the "Monitoring" and "Analytics" views, cards should span 3, 4, or 6 columns depending on the complexity of the chart.
- **Rhythm:** A 4px baseline shift is used. All components (buttons, inputs, padding) should be multiples of 4px.
- **Responsive Behavior:** 
    - **Desktop (1024px+):** Full 12-column visibility with a persistent sidebar for ERP navigation (Inventory, Warehouse, etc.).
    - **Tablet (768px - 1023px):** Sidebar collapses into a hamburger menu; data tables prioritize horizontal scrolling for data integrity.
    - **Mobile (<768px):** Reflows to a single column; progress bars and status badges are elevated to primary focus.

## Elevation & Depth

This design system uses **Tonal Layers** and **Low-Contrast Outlines** to convey hierarchy, avoiding heavy shadows that can look "muddy" in industrial lighting.

- **Level 0 (Background):** #F5F5F5. The foundation of the application.
- **Level 1 (Cards/Tables):** Pure white surface with a 1px solid border (#E0E0E0). No shadow. This is the primary workspace.
- **Level 2 (Dropdowns/Modals):** Pure white surface with a subtle ambient shadow (0px 4px 12px rgba(0,0,0,0.08)) and a 1px border. 
- **Active State:** Elements being edited or hovered receive a 2px primary color (#1976D2) border-left or bottom to indicate focus without shifting the layout.

## Shapes

The shape language is **Soft (0.25rem)**. This provides a professional, modern look that feels approachable but maintains the "square" rigidity expected of an enterprise ERP system.

- **Buttons & Inputs:** 4px (0.25rem) corner radius.
- **Data Cards:** 8px (0.5rem) corner radius to differentiate the container from the items inside it.
- **Status Badges:** Fully pill-shaped (rounded-full) to distinguish them from interactive buttons or input fields at a glance.

## Components

### Buttons & Controls
- **Primary Button:** Solid #1976D2 background, white text. Bold, 14px uppercase text for high-action visibility.
- **Progress Bars:** Use a thick 8px track. For "Mixing" and "Loading," use the primary color; use success for "Finish."

### Data Tables (DataTables)
- **Header:** Light gray background (#F8F9FA) with uppercase `label-sm` typography. 
- **Rows:** Minimum height of 48px to ensure touch-friendly targets. Zebra striping is used for readability.
- **Inline Badges:** 
    - `Idle`: Gray background.
    - `Mixing`: Warning background.
    - `Distribution`: Primary background.
    - `Finish`: Success background.

### Input Forms
- **Industrial Entry:** Inputs should have a clear 1px border that darkens on focus. Labels must always be visible (never placeholder-only) to prevent errors during high-speed data entry.
- **Validation:** SweetAlert2 notifications must use the semantic colors for immediate feedback (e.g., green for "Mix Confirmed").

### Dashboards & Monitoring
- **KPI Cards:** Display a single large value (JetBrains Mono) with a small trend indicator and a label. 
- **Charts:** Chart.js implementation should use a simplified palette of the primary and secondary colors, using high-contrast fills for better visibility in barns or warehouses.