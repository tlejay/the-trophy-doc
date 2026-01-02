# THE TROPHY: Quick Reference Design Guide

**Quick access guide for designers and developers**
**Based on:** The_Trophy_Vibe_Design_v1.md
**Version:** 1.0
**Date:** January 2, 2026

---

## Design Philosophy in 3 Words

**Achievement Made Visible**

---

## Core Colors (Copy-Paste Ready)

### Neutrals (Brand-Agnostic)
```css
--midnight-charcoal: #1A1D29;
--slate-gray: #2E3440;
--steel-blue-gray: #4C566A;
--silver-mist: #D8DEE9;
--pearl-white: #ECEFF4;
--snow-white: #FFFFFF;
```

### Accents (Default)
```css
--vibrant-indigo: #6366F1;
--electric-purple: #8B5CF6;
--sunset-gold: #F59E0B;
--energy-orange: #F97316;

--primary-gradient: linear-gradient(135deg, #6366F1, #8B5CF6);
--secondary-gradient: linear-gradient(135deg, #F59E0B, #EF4444);
```

### Semantic
```css
--success-green: #27AE60;
--warning-amber: #F39C12;
--error-red: #E74C3C;
--info-blue: #3498DB;
```

### Trophy Metals
```css
--platinum-shine: #E5E4E2;
--champion-gold: #FFD700;
--silver-medal: #C0C0C0;
--bronze-glow: #CD7F32;
```

---

## Typography Stack

### Fonts
```css
/* Headings */
font-family: 'Inter', 'Sarabun', sans-serif;
font-weight: 600-700;

/* Body */
font-family: 'Inter', 'Sarabun', sans-serif;
font-weight: 400-500;

/* Numbers/Data */
font-family: 'JetBrains Mono', monospace;
font-weight: 500;

/* Celebration */
font-family: 'Poppins', 'Bai Jamjuree', sans-serif;
font-weight: 600-700;
```

### Type Scale (Mobile)
```css
--display-xl: 32px / 40px;
--heading-1: 24px / 32px;
--heading-2: 20px / 28px;
--heading-3: 18px / 24px;
--body-large: 16px / 24px;
--body-regular: 14px / 20px;
--body-small: 12px / 16px;
--caption: 11px / 14px;
```

---

## Spacing Scale (8pt Grid)

```css
--space-xs: 4px;
--space-sm: 8px;
--space-md: 12px;
--space-base: 16px;
--space-lg: 24px;
--space-xl: 32px;
--space-2xl: 48px;
--space-3xl: 64px;
```

---

## Border Radius

```css
--radius-xs: 4px;   /* Input fields */
--radius-sm: 8px;   /* Buttons, cards */
--radius-md: 12px;  /* Mission/reward cards */
--radius-lg: 16px;  /* Modals */
--radius-xl: 24px;  /* Hero cards */
--radius-pill: 999px; /* Tags, badges */
```

---

## Shadows (Elevation)

```css
--shadow-0: none;
--shadow-1: 0 1px 3px rgba(0,0,0,0.08);
--shadow-2: 0 4px 12px rgba(0,0,0,0.12);
--shadow-3: 0 8px 24px rgba(0,0,0,0.16);
--shadow-4: 0 16px 48px rgba(0,0,0,0.20);
```

---

## Key Components Quick Specs

### Primary Button
```css
height: 48px;
border-radius: 8px;
background: linear-gradient(135deg, #6366F1, #8B5CF6);
color: #FFFFFF;
font-weight: 500;
box-shadow: 0 1px 3px rgba(0,0,0,0.08);

/* Hover */
box-shadow: 0 4px 12px rgba(0,0,0,0.12);

/* Active */
transform: scale(0.98);
```

### Mission Card
```css
width: calc(100% - 32px);
max-width: 360px;
border-radius: 12px;
background: #FFFFFF;
box-shadow: 0 1px 3px rgba(0,0,0,0.08);
padding: 16px;

/* Mission type indicator: 4px colored left border */
border-left: 4px solid [mission-type-color];
```

### Wallet Balance Card
```css
aspect-ratio: 1.58;
border-radius: 16px;
background: linear-gradient(135deg, #6366F1, #8B5CF6);
box-shadow: 0 4px 12px rgba(0,0,0,0.12);
padding: 20px;
color: #FFFFFF;

/* Balance number */
font-size: 32px;
font-family: 'JetBrains Mono', monospace;
```

---

## Icon Specifications

### Sizes
- Small: 16px
- Standard: 24px
- Large: 32px
- Feature: 48px

### Style
- Line weight: 2px (2.5px for primary actions)
- Corner radius: 3px (rounded inner corners)
- Outlined for navigation, Filled for active states

---

## Animation Timings

```css
--duration-quick: 100-200ms;
--duration-standard: 250-350ms;
--duration-slow: 400-600ms;

--easing-in: cubic-bezier(0.4, 0, 1, 1);
--easing-out: cubic-bezier(0, 0, 0.2, 1);
--easing-in-out: cubic-bezier(0.4, 0, 0.2, 1);
```

### Common Animations
```css
/* Button tap */
transition: transform 200ms ease-out, box-shadow 200ms ease-out;
transform: scale(0.98);

/* Page transition */
transition: transform 300ms ease-out;
transform: translateX(100%); /* for slide in from right */

/* Modal open */
transition: opacity 250ms ease-out, transform 250ms ease-out;
transform: scale(0.9);
opacity: 0;
```

---

## Mission Type Color Coding

```css
--location-mission: #3B82F6; /* Blue */
--photo-mission: #8B5CF6;    /* Purple */
--purchase-mission: #F97316; /* Orange */
--social-mission: #10B981;   /* Green */
--time-mission: #F59E0B;     /* Amber */
```

---

## Tier System Colors

```css
/* Standard Tier */
--standard-color: #C0C0C0; /* Silver */

/* Exclusive Tier */
--exclusive-color: #FFD700; /* Gold */
--exclusive-gradient: linear-gradient(135deg, #FFD700, #E5E4E2);
```

---

## Point Display Formats

### Small (Mission Cards)
```
🪙 50 pts
font-size: 14px;
color: #F59E0B;
```

### Medium (Wallet Balance)
```
💎 12,450 Points
font-size: 28px;
font-family: 'JetBrains Mono';
color: #FFFFFF;
```

### Transaction
```
+ 100 pts (earning - green #10B981)
- 200 pts (spending - orange #F97316)
⬆️ 1,000 pts (transfer out - blue #3B82F6)
⬇️ 500 pts (transfer in - blue #3B82F6)
```

---

## Breakpoints

```css
/* Mobile */
--mobile-sm: 320px;
--mobile-md: 375px; /* Primary design target */
--mobile-lg: 414px;

/* Tablet */
--tablet: 768px;

/* Desktop */
--desktop-sm: 1024px;
--desktop-lg: 1440px; /* Admin console primary */
```

---

## Touch Targets

```css
--touch-min: 44px; /* Minimum (Apple HIG) */
--touch-recommended: 48px; /* Recommended */
--touch-gap: 8px; /* Minimum spacing between targets */
```

---

## Accessibility Standards

### Contrast Ratios (WCAG AA)
- Body text: 4.5:1 minimum
- Large text (18px+): 3:1 minimum
- UI components: 3:1 minimum

### Focus States
```css
outline: 2px solid #6366F1;
outline-offset: 2px;
```

### Reduced Motion
```css
@media (prefers-reduced-motion: reduce) {
  * {
    animation-duration: 0.01ms !important;
    transition-duration: 0.01ms !important;
  }
}
```

---

## Thai Language Considerations

### Typography
- Use Sarabun or Noto Sans Thai
- Line-height: Add 2-4px for Thai text
- No all-caps for Thai text
- Test with actual Thai content

### Date Format
```
English: Jan 2, 2026
Thai: 2 ม.ค. 2569 (Buddhist calendar)
```

### Currency
```
฿1,234.56 OR 1,234.56 บาท
No decimal for whole: ฿1,234
```

---

## Component States Checklist

For every interactive component, design these states:
- [ ] Default
- [ ] Hover (desktop)
- [ ] Active/Pressed
- [ ] Focus (keyboard navigation)
- [ ] Disabled
- [ ] Loading
- [ ] Success (if applicable)
- [ ] Error (if applicable)

---

## File Naming Conventions

### Screens
```
[App]_[Screen]_[State]_[Platform]_v[Version].ext

Examples:
Customer_Home_Default_Mobile_v1.fig
Admin_Dashboard_Loading_Desktop_v2.fig
```

### Components
```
[ComponentName]_[Variant]_v[Version].ext

Examples:
Button_Primary_v1.svg
MissionCard_LocationActive_v1.fig
```

### Assets
```
icon_[name]_[size].svg
illustration_[name]_[variant].svg
image_[description]_[resolution].png

Examples:
icon_trophy_24.svg
illustration_empty_missions.svg
image_hero_reward_2x.png
```

---

## Quick Design Decisions

### When to use gradients?
- Wallet balance card: YES
- Primary CTAs: YES (or solid accent)
- Achievement celebrations: YES
- Mission cards: NO (use solid colors)
- Admin console: MINIMAL (data tables should be neutral)

### When to animate?
- User actions (button taps, swipes): YES
- Achievement unlocks: YES (celebratory)
- Data loading: YES (skeleton/spinner)
- Page transitions: YES (smooth)
- Decorative only: NO (respect reduced-motion)

### When to use icons vs text?
- Navigation: Icons + Labels (never icon-only)
- CTAs: Text primary, icon optional
- Status indicators: Icons + Text for clarity
- Mission types: Icons for visual scanning, text for context

---

## Design System Status

### Phase 1 (POC) - In Progress
- [ ] Color palette defined ✓
- [ ] Typography specs ✓
- [ ] Core components (buttons, cards, inputs)
- [ ] Essential screens (5 customer, 2 partner, 2 admin)
- [ ] Icon set (30-40 icons)

### Phase 2 (MVP) - Planned
- [ ] Complete component library
- [ ] All screen designs
- [ ] Full icon library (100+)
- [ ] Illustration set
- [ ] Animation specs
- [ ] Design tokens export

---

## Common Design Patterns

### Loading States
1. Skeleton screens for initial loads
2. Spinners for in-context loading
3. Progress bars for known-duration tasks
4. Pull-to-refresh for data refresh

### Empty States
1. Friendly illustration (trophy + ?)
2. Encouraging headline (H3)
3. Helpful description (body text)
4. Actionable CTA (explore elsewhere)

### Error States
1. Error icon (red, 64px)
2. "Oops!" headline (not harsh)
3. Explanation + suggestion
4. "Try Again" CTA

### Celebrations
1. Achievement unlock: Full-screen modal + confetti
2. Mission complete: Card-level animation
3. Tier upgrade: Epic full-screen celebration
4. Point earning: Coin fly animation to wallet

---

## Design Tools & Resources

### Required Software
- Figma (primary design tool)
- Adobe Illustrator (icon creation)
- Principle/ProtoPie (animation prototyping)

### Font Resources
- Inter: [Google Fonts](https://fonts.google.com/specimen/Inter)
- Sarabun: [Google Fonts](https://fonts.google.com/specimen/Sarabun)
- JetBrains Mono: [JetBrains](https://www.jetbrains.com/lp/mono/)
- Poppins: [Google Fonts](https://fonts.google.com/specimen/Poppins)

### Icon Resources
- Heroicons (for base reference)
- Custom icons (designed in-house)
- SF Symbols (iOS reference)
- Material Icons (Android reference)

---

## Contact for Design Questions

**Design Lead:** Nitipong (OHM) - Head of Design
**Project Owner:** Jakapong (TLE) - COO

**Design Files Location:**
`/Users/tlej/Works (Local)/Vibe Docs/The Trophy (C Rewards)/Design/`

**Main Vibe Document:**
`The_Trophy_Vibe_Design_v1.md`

---

**Last Updated:** January 2, 2026
**Next Update:** After Phase 1 (POC) design completion
