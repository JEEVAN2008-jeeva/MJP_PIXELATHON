---
name: SevaEase Health
colors:
  surface: '#f9f9ff'
  surface-dim: '#cadaff'
  surface-bright: '#f9f9ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f1f3ff'
  surface-container: '#e8edff'
  surface-container-high: '#e0e8ff'
  surface-container-highest: '#d7e2ff'
  on-surface: '#041b3c'
  on-surface-variant: '#424750'
  inverse-surface: '#1d3052'
  inverse-on-surface: '#edf0ff'
  outline: '#737781'
  outline-variant: '#c2c6d2'
  surface-tint: '#2e5fa1'
  primary: '#003469'
  on-primary: '#ffffff'
  primary-container: '#124b8c'
  on-primary-container: '#95bdff'
  inverse-primary: '#a8c8ff'
  secondary: '#006a65'
  on-secondary: '#ffffff'
  secondary-container: '#89f1e8'
  on-secondary-container: '#006f69'
  tertiary: '#6d0a00'
  on-tertiary: '#ffffff'
  tertiary-container: '#971200'
  on-tertiary-container: '#ffa492'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d5e3ff'
  primary-fixed-dim: '#a8c8ff'
  on-primary-fixed: '#001b3c'
  on-primary-fixed-variant: '#084687'
  secondary-fixed: '#8cf4eb'
  secondary-fixed-dim: '#6ed7cf'
  on-secondary-fixed: '#00201e'
  on-secondary-fixed-variant: '#00504c'
  tertiary-fixed: '#ffdad3'
  tertiary-fixed-dim: '#ffb4a6'
  on-tertiary-fixed: '#3f0300'
  on-tertiary-fixed-variant: '#8f1100'
  background: '#f9f9ff'
  on-background: '#041b3c'
  surface-variant: '#d7e2ff'
typography:
  headline-xl:
    fontFamily: Plus Jakarta Sans
    fontSize: 40px
    fontWeight: '800'
    lineHeight: 52px
    letterSpacing: -0.02em
  headline-xl-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 30px
    fontWeight: '800'
    lineHeight: 40px
    letterSpacing: -0.01em
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 44px
    letterSpacing: -0.01em
  headline-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 26px
    fontWeight: '700'
    lineHeight: 36px
    letterSpacing: 0em
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 24px
    fontWeight: '700'
    lineHeight: 34px
  headline-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 20px
    fontWeight: '700'
    lineHeight: 30px
  body-xl:
    fontFamily: Plus Jakarta Sans
    fontSize: 20px
    fontWeight: '500'
    lineHeight: 32px
  body-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 18px
    fontWeight: '500'
    lineHeight: 28px
  body-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 16px
    fontWeight: '500'
    lineHeight: 26px
  label-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 18px
    fontWeight: '700'
    lineHeight: 24px
    letterSpacing: 0.01em
  label-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 16px
    fontWeight: '600'
    lineHeight: 22px
    letterSpacing: 0.01em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1.5rem
  gutter-mobile: 1rem
  margin: 2rem
  margin-mobile: 1.25rem
  space-xs: 0.5rem
  space-sm: 0.75rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2rem
---

## Brand & Style

This design system delivers a civic healthcare experience rooted in dignity, radical clarity, and effortless access for older adults and multi-generational caregivers. Drawing inspiration from major public health infrastructure models like PM-JAY and Ayushman Bharat, the aesthetic balances institutional authority with empathetic warmth. 

The visual language blends **Accessible Civic Modernism** with **Tactile Softness**:
- **Clarity over Ornamentation:** Eliminates decorative ambiguity, low-contrast gradients, and abstract iconography. Every element serves an explicit, discoverable function.
- **Physical Affordance:** Interactive elements feature pronounced hit boundaries, distinct resting-state borders, and clear state transitions to reassure users with varying degrees of digital literacy, motor control, or visual acuity.
- **Dignity & Calm:** The UI rejects clinical coldness in favor of reassuring, grounded geometry, generous spatial breathing room, and clear linguistic hierarchy.

## Colors

The palette is engineered to surpass WCAG AAA contrast ratios (minimum 7:1 for normal text, 4.5:1 for large text and key graphics) against both pure white and soft tinted surfaces.

- **Primary (`#124B8C` - Deep Trustworthy Healthcare Blue):** Represents institutional reliability, navigational anchors, and principal actions.
- **Secondary (`#008C85` - Warm Medical Teal):** Conveys restorative care, validation badges, wellness journeys, and secondary affirmative tasks.
- **Tertiary (`#D9381E` - Urgent Alert Red):** Reserved strictly for critical medical notices, SOS/emergency hospital dispatches, and irreversible confirmations.
- **Neutral (`#172B4D` - Deep Navy Slate):** High-density ink replacement for off-black body copy, establishing razor-sharp edge contrast without ocular harshness.
- **Canvas & Surface Tier:**
  - Base Background: `#FFFFFF`
  - Soft Surface / Containers: `#F1F6FC` (Soft ice blue)
  - Success State: `#0E8345` (Vibrant therapeutic green)
  - Accessibility High Contrast Mode: Maps surfaces to `#0A111E` and active elements to `#FFFFFF` / `#FFD600` when the user triggers the High Contrast toggle.

## Typography

Typography is set exclusively in **Plus Jakarta Sans**, chosen for its tall x-height, open apertures, wide counters, and unambiguous glyph distinctions (e.g., distinguishing uppercase `I`, lowercase `l`, and number `1`). 

- **Minimum Size Floor:** No text across the core system falls below `16px`. Secondary explanatory labels are clamped at `16px`, standard body defaults to `18px`, and primary instructional guidance scales up to `20px`.
- **Easy View Scaling:** When the persistent "Easy View (Large Text)" mode is enabled by the senior user, all `body-*` and `headline-*` tokens scale upward uniformly by an additional 125% factor without breaking card boundaries.
- **Reading Rhythm:** Generous line heights (1.5x to 1.6x the font size) prevent line-jumping fatigue for aging eyes. Letter-spacing remains neutral to slightly open to eliminate visual crowding.

## Layout & Spacing

The layout is built upon an uncompromising **8px base grid rhythm**, optimizing for high motor tolerance and effortless scanning.

- **Responsive Grid:**
  - **Desktop (1024px+):** 12-column layout, max-width `1200px` centered, 24px (`1.5rem`) gutters, 32px (`2rem`) margins.
  - **Tablet (768px - 1023px):** 8-column layout, 24px gutters, 24px margins.
  - **Mobile (320px - 767px):** 4-column single-stack flow, 16px (`1rem`) gutters, 20px (`1.25rem`) margins.
- **Motor Control Safe Bounds:** Every tappable target maintains an absolute minimum hit box of `48px × 48px`, prioritizing standard targets of `56px` height. Inter-action spacing requires at least `12px` of empty boundary (`space-sm` or greater) to prevent accidental double taps or unintended misclicks.

## Elevation & Depth

To avoid visual disorientation caused by heavy floating dropshadows or complex blur passes, this design system relies on **Tonal Grounding combined with Low-Contrast Crisp Borders**:

- **Ground Plane (Level 0):** Pure `#FFFFFF` canvas for primary content reading and forms.
- **Layered Plane (Level 1):** `#F1F6FC` tinted containers paired with a solid `1.5px` border of `#D3E2F2` (soft ice blue border) to physically define content boundaries for users with diminished edge contrast perception.
- **Elevated Interactive Plane (Level 2):** Focused cards and active actionable modules use a very subtle, grounded ambient shadow (`0px 4px 12px rgba(18, 75, 140, 0.08)`) accompanied by a distinct structural border (`#BACFEE`).
- **Emergency Overlay / Floating Assist (Level 3):** Reserved for persistent senior utility bars (Voice Reader Bar, SOS triggers). Elevated via `0px 8px 24px rgba(23, 43, 77, 0.14)` and anchored to screen perimeters.

## Shapes

The shape system employs `roundedness: 2` (base `8px`, with interactive components scaled to `12px` to `16px`). 

- **Buttons & Interactive Controls:** Employ `rounded-lg` (`16px` border-radius) creating a reassuring, approachable touchpoint that looks explicitly clickable and soft to the touch without devolving into a hyper-condensed full pill.
- **Cards, Panels & Modal Containers:** Use `rounded-xl` (`24px` border-radius) to naturally cradle information groups and avoid harsh sharp corners that create visual noise.
- **Badges, Tags & Utility Toggles:** Maintain `8px` to `12px` corner radii to maintain consistent internal hierarchy against circular avatars and icons.

## Components

### Persistent Accessibility Utility Bar
Pinned directly to the top header or persistent floating footer:
- **Easy View (Large Text) Switch:** High-affordance dual toggle button with prominent magnifying glass icon and text "Text Size: Normal / Large".
- **High Contrast Toggle:** High-contrast badge toggle ("Black & White / Normal") that shifts all surfaces to high-vis dark navy and yellow outlines.
- **Web Speech Voice Guidance Reader:** Prominent speaker icon with an active "Read Screen Aloud" button (`52px` tall, `#008C85` teal border), enabling instantaneous audio synthesis of section titles and instructional text.

### Buttons
- **Primary Buttons:** Minimum height of `56px`, background `#124B8C`, text `#FFFFFF` (Plus Jakarta Sans `18px Bold`), `16px` radius. Hover/active states show a visible darken shift with a `2px` focus ring in `#008C85`.
- **Secondary Buttons:** Minimum height of `56px`, background `#FFFFFF`, text `#124B8C`, border `2px solid #124B8C`, `16px` radius.
- **Emergency / SOS Action:** Minimum height of `60px`, background `#D9381E`, text `#FFFFFF`, bold `20px` typography, flanked by a prominent siren or cross icon.

### Form Inputs & Selectors
- **Input Fields:** Generous height (`56px`), large placeholder and input text (`18px`), solid `2px` outline in `#A5C0E2` resting state, shifting to `3px` solid `#124B8C` upon focus.
- **Labels:** Always persistently positioned *above* the input field (never floating or replacing placeholder text), set in `18px` bold `#172B4D` with immediate explanatory helper text below.

### Checkboxes & Radio Buttons
- **Touch Bounds:** Touch target expands to `48px × 48px`, with the visual square/circle sized at `28px × 28px` (substantially larger than standard 16px controls).
- **Indicators:** High contrast fill (`#124B8C`) with a crisp, thick white checkmark (minimum `3px` stroke) for instant confirmation.

### Content Cards & Civic Health Badges
- **Cards:** Built on `#F1F6FC` surfaces with a `1.5px` border in `#D3E2F2`, `20px` internal padding (`space-lg`), containing clear visual chunking for doctor profiles, scheme benefits (e.g., Ayushman Golden Card eligibility), and appointment timelines.
- **Status Chips:** Height `40px`, pill-shaped or `8px` rounded, with explicit status icons (e.g., green check inside circle) alongside `16px` semi-bold text. Never rely on color alone to communicate state.