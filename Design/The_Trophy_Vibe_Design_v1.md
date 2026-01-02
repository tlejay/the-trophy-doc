# THE TROPHY: Vibe Design Document

**Project:** The Trophy - Gamified Loyalty & Engagement Ecosystem
**Document Type:** Visual Identity & Design Direction
**Version:** 1.0
**Date:** January 2, 2026
**Prepared by:** Stitch Design (DOS)
**Design Folder:** `/Users/tlej/Works (Local)/Vibe Docs/The Trophy (C Rewards)/Design/`

---

## Executive Summary

This Vibe Design document establishes the visual identity, emotional tone, and design foundation for The Trophy platform - a white-label gamified loyalty ecosystem for sports organizations and their partners. The design balances enterprise-grade professionalism with engaging gamification, targeting Thai users with bilingual (Thai/English) support.

**Core Design Philosophy:**
> "Achievement Made Visible, Engagement Made Effortless"

The Trophy's design language celebrates user accomplishments while maintaining simplicity and accessibility across all user types - from passionate sports fans to busy partner staff to data-focused administrators.

---

## 1. Visual Identity Vibe

### 1.1 Overall Mood & Aesthetic Direction

**Primary Vibe: "Premium Sports Achievement"**

The Trophy should feel like opening a high-quality sports magazine meets unlocking achievement badges in your favorite game - sophisticated yet playful, aspirational yet accessible.

**Emotional Tone:**
- **Empowering:** Users feel recognized and rewarded for their actions
- **Energetic:** Dynamic, movement-oriented, never static
- **Trustworthy:** Enterprise-grade reliability for B2B confidence
- **Inclusive:** Welcoming to all engagement levels (casual to hardcore fans)
- **Celebratory:** Every achievement is a moment worth highlighting

**Aesthetic Direction:**
- **Modern Minimalism with Depth:** Clean interfaces with strategic use of depth, shadows, and gradients to create hierarchy
- **Sports-Inspired but Not Literal:** Energy and dynamism of sports without relying on clichés (no generic stadiums or jersey patterns)
- **Data-Driven but Human:** Numbers and progress are prominent but always connected to human achievement
- **Thai Market Alignment:** Comfortable for LINE-first users, consideration for Thai visual preferences (not overly sparse Western minimalism)

### 1.2 Brand-Neutral White-Label Approach

**Critical Design Constraint:** The platform MUST remain completely brand-neutral - no specific club logos, team colors, or organizational branding in the core UI.

**White-Label Strategy:**
- **Neutral Foundation:** Gray-scale base with accent colors that work with any partner brand
- **Customizable Accent Zones:** Specific areas (mission cards, reward cards, tier badges) can accept brand colors via configuration
- **Universal Iconography:** Trophy, medal, star, and achievement symbols that transcend specific sports
- **Content-Level Branding:** Organization-specific branding appears only in mission descriptions, reward images, and content cards - never in core navigation or UI chrome

**Visual Solution:**
- Primary UI uses sophisticated neutrals (charcoal, slate, pearl white)
- Secondary elements use customizable accent colors (defaults to energetic gradient palette)
- Tertiary elements for achievements use universal gold/silver/bronze metaphors

---

## 2. Design System Foundation

### 2.1 Color Palette

**Base Neutral Palette (Brand-Agnostic Core)**

```
Primary Neutrals:
- Midnight Charcoal: #1A1D29 (main backgrounds, headers)
- Slate Gray: #2E3440 (secondary backgrounds, cards)
- Steel Blue-Gray: #4C566A (borders, dividers, inactive states)
- Silver Mist: #D8DEE9 (secondary text, disabled states)
- Pearl White: #ECEFF4 (primary text on dark, bright backgrounds)
- Snow White: #FFFFFF (cards on light mode, highlights)

Semantic Colors (System-Wide):
- Success Green: #27AE60 (mission completion, approvals)
- Warning Amber: #F39C12 (pending status, cautions)
- Error Red: #E74C3C (rejections, errors, alerts)
- Info Blue: #3498DB (informational messages, tips)
```

**Accent Palette (Configurable per Organization)**

```
Default Accent Gradient (Used when no org-specific colors):
- Primary Gradient: Linear from #6366F1 (Vibrant Indigo) to #8B5CF6 (Electric Purple)
- Secondary Gradient: Linear from #F59E0B (Sunset Gold) to #EF4444 (Energy Red)

Default Accent Solids:
- Vibrant Indigo: #6366F1 (primary CTAs, active states)
- Electric Purple: #8B5CF6 (secondary CTAs, highlights)
- Energy Orange: #F97316 (notifications, urgency)
- Sunset Gold: #F59E0B (achievements, rewards)
```

**Gamification Palette (Universal Achievement System)**

```
Trophy Metals (Cross-Cultural Achievement Markers):
- Platinum Shine: #E5E4E2 (exclusive tier, top achievements)
- Champion Gold: #FFD700 (high achievements, exclusive rewards)
- Silver Medal: #C0C0C0 (mid-tier achievements)
- Bronze Glow: #CD7F32 (entry achievements, welcome rewards)

Point Economy Colors:
- Point Green: #10B981 (earning points, positive transactions)
- Point Purple: #8B5CF6 (point balance displays)
- Redemption Orange: #F97316 (spending points, redemption)
- Transfer Blue: #3B82F6 (Trophy Wallet transfers)
```

**Light vs. Dark Mode**

```
Light Mode (Default for Customer App):
- Background: #F8F9FA
- Surface Cards: #FFFFFF
- Primary Text: #1A1D29
- Secondary Text: #4C566A

Dark Mode (Optional, Premium Feel):
- Background: #1A1D29
- Surface Cards: #2E3440
- Primary Text: #ECEFF4
- Secondary Text: #D8DEE9

Note: Partner and Admin apps default to Light Mode for clarity during operations.
```

### 2.2 Typography Direction

**Font Philosophy:** Bilingual excellence - fonts must excel in both Latin (English) and Thai scripts with consistent personality.

**Primary Typeface: Inter (Latin) + Sarabun (Thai)**

```
Headings & Display:
- Family: Inter (English) / Sarabun (Thai)
- Weight: Bold (700) for H1-H2, SemiBold (600) for H3-H4
- Characteristics: Modern, geometric, excellent readability at all sizes
- Usage: Page titles, section headers, card titles, achievement names

Body & Interface:
- Family: Inter (English) / Sarabun (Thai)
- Weight: Regular (400) for body, Medium (500) for emphasis
- Characteristics: Neutral, professional, optimized for screens
- Usage: Mission descriptions, reward details, form labels, navigation

Data & Numbers:
- Family: JetBrains Mono (monospaced, universal)
- Weight: Medium (500)
- Characteristics: Tabular figures, fixed-width for alignment
- Usage: Point balances, transaction amounts, leaderboard stats, countdown timers

Accent & Celebration:
- Family: Poppins (English) / Bai Jamjuree (Thai)
- Weight: SemiBold (600) to Bold (700)
- Characteristics: Friendly, energetic, slightly playful
- Usage: Achievement unlocked messages, mission complete celebrations, CTAs
```

**Type Scale (Mobile-First)**

```
Display XL (Achievement Announcements): 32px / 40px line-height
Heading 1 (Page Titles): 24px / 32px line-height
Heading 2 (Section Headers): 20px / 28px line-height
Heading 3 (Card Titles): 18px / 24px line-height
Body Large (Mission Descriptions): 16px / 24px line-height
Body Regular (Default Text): 14px / 20px line-height
Body Small (Metadata, Timestamps): 12px / 16px line-height
Caption (Helper Text): 11px / 14px line-height

Point Balance Display: 28px / 32px line-height (JetBrains Mono)
Leaderboard Numbers: 16px / 20px line-height (JetBrains Mono)
```

**Thai Language Considerations:**
- Sarabun was chosen for excellent Thai vowel/tone mark rendering
- Slightly increased line-height for Thai text (add 2-4px)
- Avoid all-caps for Thai text (causes rendering issues)
- Test all UI states with actual Thai content, not Lorem Ipsum

### 2.3 Iconography Style

**Icon System: "Modern Line Art with Playful Fills"**

**Visual Characteristics:**
- **Line Weight:** 2px standard, 2.5px for primary actions
- **Corner Radius:** Rounded (3px radius on inner corners)
- **Style:** Outlined (line art) for navigation/UI, Filled for active states and achievements
- **Size System:** 16px (small), 24px (standard), 32px (large), 48px (feature)
- **Color Treatment:** Single-color (inherit from context) with optional gradient fills for special states

**Icon Categories:**

```
Navigation & System Icons (Outlined):
- Home, Profile, Missions, Rewards, Wallet (Tab bar)
- Settings, Notifications, Help, Search (Utility)
- Back, Close, Menu, More (Controls)
- Style: Clean line art, 24px standard

Mission Type Icons (Filled when active):
- Location Pin (location-based missions)
- Camera (photo missions)
- Clock/Calendar (time-based missions)
- Shopping Bag (purchase missions)
- Share Node (social missions)
- Style: Outlined default, filled gradient when mission type is active

Achievement & Trophy Icons (Always filled, celebratory):
- Trophy (overall achievements)
- Medal (mission completion)
- Star (favorites, ratings)
- Badge (tier status)
- Crown (exclusive tier)
- Sparkles (new achievements)
- Style: Filled with gold/silver/bronze gradients, animated on reveal

Partner & Service Icons (Industry-specific):
- Restaurant, Coffee, Car Wash, Retail, Entertainment, etc.
- Style: Simple line art, 32px in mission cards
- Approach: Use universal symbols, not brand-specific logos

Wallet & Transaction Icons:
- Wallet (Trophy Wallet home)
- Arrow Up (outbound transfer)
- Arrow Down (inbound transfer)
- Plus (earning points)
- Minus (spending points)
- Swap (exchange/transfer)
- Style: Bold line art, 24px, inherit accent color
```

**Icon Animation Principles:**
- Scale bounce on tap (1.0 → 1.2 → 1.0, 200ms)
- Fill transition for state changes (100ms ease-in-out)
- Rotate for loading states (continuous, 800ms linear)
- Celebration confetti burst for achievement unlocks

**Accessibility:**
- All icons paired with text labels (never icon-only CTAs)
- Sufficient color contrast (4.5:1 minimum)
- Touch targets minimum 44x44px
- Haptic feedback on important interactions

### 2.4 Visual Elements & Components

**Elevation & Depth System**

```
Level 0 (Base): No shadow, flush with background
- Usage: Page backgrounds, inline content

Level 1 (Raised): 0 1px 3px rgba(0,0,0,0.08)
- Usage: Cards, input fields, default state

Level 2 (Floating): 0 4px 12px rgba(0,0,0,0.12)
- Usage: Floating action buttons, dropdown menus

Level 3 (Modal): 0 8px 24px rgba(0,0,0,0.16)
- Usage: Modals, dialogs, bottom sheets

Level 4 (Popup): 0 16px 48px rgba(0,0,0,0.20)
- Usage: Achievement celebrations, important notifications
```

**Border Radius System**

```
Extra Small (Elements): 4px - Input fields, small buttons
Small (Cards): 8px - Standard cards, containers
Medium (Panels): 12px - Mission cards, reward cards
Large (Modals): 16px - Modal dialogs, bottom sheets
Extra Large (Special): 24px - Hero cards, featured content
Pill (Full): 999px - Tags, badges, status indicators
```

**Spacing Scale (8pt Grid)**

```
4px - Tight spacing (icon-label gaps)
8px - Small gaps (within cards)
12px - Medium gaps (between related elements)
16px - Standard gaps (card padding, section spacing)
24px - Large gaps (between sections)
32px - Extra large gaps (major sections)
48px - Spacious (hero sections, feature spacing)
64px - Maximum (page-level spacing)
```

**Card Components**

```
Mission Card:
- Size: Full-width - 16px margin (mobile), 360px max-width (tablet)
- Radius: 12px
- Shadow: Level 1 default, Level 2 on hover/active
- Structure:
  - Header: Icon (32px) + Mission Title (H3) + Points Badge
  - Body: Description (Body Regular, 2-line clamp)
  - Footer: Progress bar + Distance/Time metadata
  - CTA: Primary button or Status indicator

Reward Card:
- Size: 160px x 220px (grid layout, 2 columns mobile)
- Radius: 12px
- Shadow: Level 1
- Structure:
  - Image: 160px x 100px (16:10 ratio)
  - Title: H4, 2-line clamp
  - Point Cost: Prominent, JetBrains Mono, gradient text
  - Availability: Small text, gray

Achievement Toast (Celebration):
- Size: Full-width - 16px margin
- Radius: 16px
- Shadow: Level 4
- Background: Gradient (context-aware)
- Animation: Slide down from top + bounce
- Structure:
  - Icon: 48px trophy/medal (animated)
  - Title: "Achievement Unlocked!" (H3)
  - Description: Achievement name + points earned
  - Auto-dismiss: 4 seconds
```

**Progress Indicators**

```
Point Progress Bar:
- Height: 8px
- Radius: 999px (pill)
- Background: Light gray (#E5E7EB)
- Fill: Gradient (primary accent)
- Animation: Smooth fill on update (300ms ease-out)

Tier Progress Ring (Circular):
- Diameter: 120px (profile view)
- Stroke Width: 12px
- Background Stroke: Light gray
- Progress Stroke: Gradient (tier-specific)
- Center Content: Tier icon + percentage

Mission Completion Steps:
- Style: Horizontal stepper
- Active Step: Filled circle (accent color)
- Completed: Check icon (success green)
- Pending: Outlined circle (gray)
- Connection Line: 2px solid, gray/accent
```

**Buttons & CTAs**

```
Primary Button (Main Actions):
- Background: Gradient (primary accent) OR solid accent
- Text: White, Medium weight
- Height: 48px (mobile), 44px (desktop)
- Radius: 8px
- Shadow: Level 1
- Hover: Slight lift (Level 2 shadow)
- Active: Scale down (0.98)

Secondary Button (Alternative Actions):
- Background: Transparent
- Border: 2px solid accent color
- Text: Accent color, Medium weight
- Height: 48px
- Radius: 8px
- Hover: Filled with accent (10% opacity)

Text Button (Tertiary Actions):
- Background: None
- Text: Accent color, Medium weight
- Underline: On hover only
- Usage: "Learn More", "Cancel", "Skip"

Floating Action Button (FAB):
- Size: 56px diameter
- Radius: 999px (circle)
- Shadow: Level 2
- Icon: 24px, white
- Background: Gradient accent
- Position: Fixed bottom-right (16px margins)
- Usage: Quick mission scan, new reward
```

---

## 3. Key Screen Concepts (Design Direction)

### 3.1 Customer Mobile App (User Super App)

**3.1.1 Home Dashboard Screen**

**Vibe:** "Your Personal Achievement Hub"

**Layout Direction:**
```
Structure (Top to Bottom):
┌─────────────────────────────────────┐
│ [Status Bar]                        │
│ ┌─────────────────────────────────┐ │
│ │ Welcome Back, [Name]!           │ │ <- Personalized greeting
│ │ Trophy Wallet: [12,450] pts 💎  │ │ <- Prominent point balance (gradient background)
│ └─────────────────────────────────┘ │
│                                     │
│ 🎯 Active Missions (3)              │ <- Section header
│ ┌─────────────────┐ ┌─────────────┐ │
│ │ [Mission Card]  │ │ [Mission]   │ │ <- Horizontal scroll, featured missions
│ └─────────────────┘ └─────────────┘ │
│                                     │
│ 🏆 Tier Progress                    │
│ [Circular Progress Ring: 65%]       │ <- Current tier advancement
│ "850 pts to Exclusive Tier"         │
│                                     │
│ 🎁 Nearby Rewards                   │
│ [Map Preview with 3 closest pins]   │ <- Interactive map snippet
│ "12 rewards within 5km"             │
│                                     │
│ ⚡ Quick Actions                    │
│ [Scan QR] [Browse Rewards] [Wallet]│ <- Large button grid
└─────────────────────────────────────┘
[Bottom Tab Navigation]
```

**Visual Treatment:**
- Background: Subtle gradient (midnight charcoal to slate gray, top to bottom)
- Wallet Card: Vibrant gradient background, white text, prominent balance (28px)
- Mission Cards: White cards with Level 1 shadow, color-coded by mission type
- Tier Progress: Animated ring with current tier icon in center (gold/silver/bronze)
- Map Preview: Rounded corners (16px), pins use accent colors
- Quick Actions: Grid of 3 large buttons (icon + label), accent backgrounds

**Interaction States:**
- Pull-to-refresh reveals animation of trophy icon spinning
- Mission cards swipe to dismiss or "Save for Later"
- Tap wallet card → smooth transition to Trophy Wallet detail
- Parallax scroll effect on wallet card (slight movement on scroll)

---

**3.1.2 Mission Center Screen**

**Vibe:** "Gamified Quest Board"

**Layout Direction:**
```
┌─────────────────────────────────────┐
│ [Header: "Missions"]                │
│ [Filter Chips: All | Near Me | New]│ <- Horizontal scroll filters
│                                     │
│ Available Missions (12)             │
│ ┌─────────────────────────────────┐ │
│ │ 📍 Check-in at Partner Café     │ │
│ │ "Visit within 2km radius"       │ │
│ │ ━━━━━━━━━━━━━━━━━ 0/1          │ │ <- Progress bar
│ │ 🪙 50 pts • 1.2 km away         │ │
│ │ [Start Mission] →               │ │
│ └─────────────────────────────────┘ │
│                                     │
│ ┌─────────────────────────────────┐ │
│ │ 📸 Photo with Barista           │ │
│ │ "Take a selfie at coffee bar"   │ │
│ │ ━━━━━━━━━━━━━━━━━ 0/1          │ │
│ │ 🪙 100 pts • Manual verify      │ │
│ │ [Start Mission] →               │ │
│ └─────────────────────────────────┘ │
│                                     │
│ Completed Missions (5)              │
│ [Collapsed list, tap to expand]     │
└─────────────────────────────────────┘
```

**Visual Treatment:**
- Filter Chips: Pill-shaped (999px radius), outlined default, filled when active
- Mission Cards: Full-width, 12px radius, icon badge (32px) in top-left
- Mission Type Color Coding:
  - Location: Blue gradient left border (4px)
  - Photo: Purple gradient left border
  - Purchase: Orange gradient left border
  - Social: Green gradient left border
- Progress Bar: Point green gradient fill on white background
- Point Badge: Circular, gold background, white text with coin icon
- Distance Indicator: Gray text with location pin icon

**Micro-interactions:**
- Filter chip tap: Bounce animation + haptic
- Mission card tap: Expand to show full description + map (if location-based)
- "Start Mission" button: Ripple effect from center
- Completed missions: Checkmark animation + confetti burst on first view

---

**3.1.3 Trophy Wallet Screen**

**Vibe:** "Your Financial Command Center (Gamified)"

**Layout Direction:**
```
┌─────────────────────────────────────┐
│ [Trophy Wallet Header]              │
│ ┌─────────────────────────────────┐ │
│ │  💎 Current Balance              │ │
│ │     12,450 Points               │ │ <- Large, centered (28px JetBrains Mono)
│ │  ≈ THB 6,225 value              │ │ <- Conversion rate (gray, smaller)
│ └─────────────────────────────────┘ │ <- Gradient background card
│                                     │
│ Quick Actions                       │
│ ┌─────┐ ┌─────┐ ┌─────┐ ┌─────┐  │
│ │ ⬆️  │ │ ⬇️  │ │ 🔄  │ │ 📜  │  │ <- Icon buttons
│ │Send │ │Recv │ │Swap │ │Hist │  │
│ └─────┘ └─────┘ └─────┘ └─────┘  │
│                                     │
│ 📊 Point Activity (This Month)      │
│ [Bar Chart: Earned vs Spent]       │
│ Earned: +2,450 | Spent: -1,200     │
│                                     │
│ Recent Transactions                 │
│ ┌─────────────────────────────────┐ │
│ │ + 100 pts • Café Check-in       │ │
│ │ 2 hours ago                     │ │
│ └─────────────────────────────────┘ │
│ ┌─────────────────────────────────┐ │
│ │ - 500 pts • VIP Parking Reward  │ │
│ │ Yesterday                       │ │
│ └─────────────────────────────────┘ │
│ [View All Transactions] →           │
└─────────────────────────────────────┘
```

**Visual Treatment:**
- Balance Card: Vibrant gradient (indigo to purple), rounded 16px, Level 2 shadow
- Balance Number: Large, bold, white, JetBrains Mono for tabular clarity
- Quick Action Buttons: Circular (56px), white background, accent icon, labeled below
- Activity Chart: Minimal bar chart, green (earned) vs orange (spent), 7-day view
- Transaction List:
  - Earning (+): Green "+" icon, green accent text
  - Spending (-): Orange "-" icon, orange accent text
  - Transfer (⬆️⬇️): Blue swap icon, blue accent
- Timestamps: Small gray text (12px)

**Special Features:**
- Point Transfer Flow:
  - Tap "Send" → Modal with amount input + recipient selection
  - Visual: Amount input has large numeric keypad, real-time validation
  - Confirmation: Shows transfer summary with animated point movement graphic
- Swipe Transaction Item: Reveal "Export" or "Share Receipt" action

---

**3.1.4 Reward Catalog Screen**

**Vibe:** "Shopping Discovery + Achievement Gallery"

**Layout Direction:**
```
┌─────────────────────────────────────┐
│ [Header: "Rewards"]                 │
│ [Search Bar]                        │
│ [Toggle: Grid View | Map View]     │
│                                     │
│ Categories (Horizontal Scroll)      │
│ [VIP] [Merch] [Food] [Experience]  │ <- Chip filters
│                                     │
│ Featured Rewards                    │
│ ┌────────┐ ┌────────┐             │
│ │[Image] │ │[Image] │             │ <- 2-column grid
│ │VIP Seat│ │Jersey  │             │
│ │🪙 2,000│ │🪙 800  │             │
│ └────────┘ └────────┘             │
│ ┌────────┐ ┌────────┐             │
│ │[Image] │ │[Image] │             │
│ │Parking │ │Cafe 50%│             │
│ │🪙 500  │ │🪙 200  │             │
│ └────────┘ └────────┘             │
│                                     │
│ [Load More...]                      │
└─────────────────────────────────────┘

Map View Alternative:
┌─────────────────────────────────────┐
│ [Interactive Map with Reward Pins]  │
│ ┌─────────────────────────────────┐ │
│ │ [Google Maps view]              │ │
│ │ 📍 Multiple reward locations    │ │
│ │ Clustered by proximity          │ │
│ └─────────────────────────────────┘ │
│                                     │
│ [Bottom Sheet: Reward Details]      │
│ Slides up on pin tap                │
└─────────────────────────────────────┘
```

**Visual Treatment:**
- Search Bar: Rounded (999px), light gray background, search icon left, "Find rewards..." placeholder
- View Toggle: Segmented control, rounded 8px, filled active state
- Category Chips: Pill-shaped, icon + label, outlined default, gradient when selected
- Reward Cards (Grid):
  - Image: 16:10 ratio, rounded top corners (12px)
  - Overlay gradient on image (bottom): Dark gradient for text readability
  - Title: White text on gradient overlay (H4)
  - Point Cost: Prominent, gold coin icon + amount, JetBrains Mono
  - Availability Badge: If limited stock, "Only 5 left!" in warning amber
- Map View:
  - Pins: Custom trophy icon pins, color-coded by category
  - Clusters: Numbered circles for multiple rewards in same area
  - Bottom Sheet: Card-style (rounded top 24px), reward preview with image + "View Details" CTA

**Interaction States:**
- Reward Card Tap: Expand to full-screen detail with hero image + redemption flow
- Map Pin Tap: Bounce animation + bottom sheet slide-up
- Category Filter: Cross-fade transition between filtered results (300ms)
- "Redeem Now" Button: Generates QR code modal with animated reveal

---

**3.1.5 Profile & Tier Status Screen**

**Vibe:** "Personal Achievement Dashboard"

**Layout Direction:**
```
┌─────────────────────────────────────┐
│ [Profile Header]                    │
│ ┌─────────────────────────────────┐ │
│ │ [Avatar] [Name]                 │ │
│ │ Exclusive Member 👑             │ │ <- Tier badge
│ │ Member since Jan 2026           │ │
│ └─────────────────────────────────┘ │
│                                     │
│ 🏆 Achievement Stats                │
│ ┌──────┐ ┌──────┐ ┌──────┐        │
│ │ 124  │ │  15  │ │  8   │        │ <- Stats grid
│ │Points│ │ Compl│ │Redeem│        │
│ │ Earned││Missions│Rewards│        │
│ └──────┘ └──────┘ └──────┘        │
│                                     │
│ 📈 Tier Progress                    │
│ [Circular Progress Ring]            │
│ Current: Exclusive (Platinum)       │
│ Next Milestone: Champion (5,000 pts)│
│                                     │
│ 🎖️ Badges & Achievements (12)      │
│ ┌───┐ ┌───┐ ┌───┐ ┌───┐          │
│ │🏅 │ │⭐ │ │🔥 │ │💎 │          │ <- Badge grid, 4 columns
│ │First│Early│Streak│VIP │          │
│ └───┘ └───┘ └───┘ └───┘          │
│ [View All →]                        │
│                                     │
│ ⚙️ Settings                         │
│ [Notifications] [Privacy] [Language]│
│ [Change Mobile Number] [Logout]     │
└─────────────────────────────────────┘
```

**Visual Treatment:**
- Profile Header: Gradient background matching tier (gold for Exclusive, silver for Standard)
- Avatar: 80px circle with border (tier color), default user icon if no photo
- Tier Badge: Inline crown emoji + tier name, bold text
- Stats Grid: 3 cards with large numbers (JetBrains Mono, 32px), icons above, labels below
- Tier Progress Ring: Same as home screen, 120px diameter, animated fill
- Badge Grid: Circular badges (64px), full-color icons, grayscale for locked badges
- Settings: List items with right arrow, neutral background

**Special Elements:**
- Tier Upgrade Animation: When threshold reached, confetti burst + modal with new tier badge reveal
- Badge Unlock: Shimmer effect on newly unlocked badges
- Leaderboard Integration: Optional "My Rank: #47" card with "View Leaderboard" link

---

### 3.2 Partner Mobile App (Validation & Service Tool)

**Vibe:** "Efficient Utility with Clear Feedback"

**Design Approach:**
- **Simplicity First:** Partner staff may not be tech-savvy; UI must be intuitive at a glance
- **Large Touch Targets:** Minimum 56px buttons, generous spacing
- **Clear Status Indicators:** Green/red/amber color coding for action results
- **Minimal Navigation:** Single-purpose screens, no deep hierarchies

**3.2.1 Partner Dashboard (Home)**

**Layout Direction:**
```
┌─────────────────────────────────────┐
│ [Partner Logo Area]                 │ <- Org-specific branding
│ Partner: "Café Mocha"               │
│ Location: Central Bangkok           │
│                                     │
│ 📊 Today's Stats                    │
│ ┌─────────────────────────────────┐ │
│ │ Customers Served: 24            │ │
│ │ Points Awarded: 1,200           │ │
│ │ Rewards Redeemed: 8             │ │
│ └─────────────────────────────────┘ │
│                                     │
│ Quick Actions                       │
│ ┌─────────────────────────────────┐ │
│ │  📷 SCAN QR CODE                │ │ <- Primary CTA (huge button)
│ └─────────────────────────────────┘ │
│                                     │
│ ┌──────────────┐ ┌──────────────┐  │
│ │ ✅ Approve   │ │ 📜 History   │  │ <- Secondary actions
│ │ Missions     │ │ View Txns    │  │
│ └──────────────┘ └──────────────┘  │
└─────────────────────────────────────┘
```

**Visual Treatment:**
- Clean white background (high contrast for outdoor/bright light usage)
- Stats Card: Light gray background, large numbers (28px), icons colored
- Scan QR Button: Full-width, tall (64px), vibrant gradient background, camera icon
- Secondary Buttons: Grid 2-column, white background, colored icons, Level 1 shadow
- Font: Extra readable (16px minimum body text)

---

**3.2.2 QR Scanner Screen**

**Layout Direction:**
```
┌─────────────────────────────────────┐
│ [Camera Viewfinder]                 │
│ ┌─────────────────────────────────┐ │
│ │                                 │ │
│ │    [QR Code Frame Overlay]      │ │ <- Animated scanning line
│ │         [Scan Area]             │ │
│ │                                 │ │
│ └─────────────────────────────────┘ │
│                                     │
│ "Align QR code within frame"        │ <- Instruction text
│                                     │
│ [Cancel] [Toggle Flash]             │ <- Bottom actions
└─────────────────────────────────────┘

After Successful Scan:
┌─────────────────────────────────────┐
│ ✅ User Verified                    │
│                                     │
│ Name: Somchai P.                    │
│ Tier: Exclusive Member              │
│ Points Balance: 1,450 pts           │
│                                     │
│ Select Action:                      │
│ ┌─────────────────────────────────┐ │
│ │ ➕ Award Points (Mission)       │ │ <- Green background
│ └─────────────────────────────────┘ │
│ ┌─────────────────────────────────┐ │
│ │ ✅ Redeem Reward                │ │ <- Orange background
│ └─────────────────────────────────┘ │
│                                     │
│ [Cancel]                            │
└─────────────────────────────────────┘
```

**Visual Treatment:**
- Viewfinder: Full-screen camera feed, darkened edges (vignette effect)
- Scan Frame: Rounded square outline (16px radius), animated corners (pulsing)
- Scanning Line: Horizontal blue line moving top-to-bottom, subtle glow
- Success Modal: Slide-up from bottom, white card with Level 3 shadow
- User Info: Large, clear text, tier badge shown with icon
- Action Buttons: Full-width, tall (56px), color-coded, icon + text

**Interaction Flow:**
1. Scan QR → Verify user identity → Present action choice
2. Award Points Flow:
   - Select mission from dropdown
   - Confirm point amount (pre-filled)
   - Tap "Award" → Success animation → Return to home
3. Redeem Reward Flow:
   - Show reward details (name, point cost)
   - Confirm redemption
   - Deduct points → Success animation → Return to home

---

**3.2.3 Mission Approval Screen (Photo Verification)**

**Layout Direction:**
```
┌─────────────────────────────────────┐
│ Pending Approvals (5)               │
│                                     │
│ ┌─────────────────────────────────┐ │
│ │ [Photo Thumbnail]               │ │
│ │ Mission: "Selfie with Barista"  │ │
│ │ User: Somchai P.                │ │
│ │ Submitted: 10 mins ago          │ │
│ │                                 │ │
│ │ [View Photo] [✅ Approve] [❌ Reject]│
│ └─────────────────────────────────┘ │
│                                     │
│ [Next Mission...]                   │
└─────────────────────────────────────┘

Photo View (Full Screen):
┌─────────────────────────────────────┐
│ [Full-Screen Photo]                 │
│                                     │
│ [Pinch to zoom, swipe to dismiss]   │
│                                     │
│ [Bottom Action Bar]                 │
│ ┌──────────┐ ┌──────────┐          │
│ │ ✅ Approve│ │ ❌ Reject │          │
│ └──────────┘ └──────────┘          │
└─────────────────────────────────────┘
```

**Visual Treatment:**
- Mission Card: White background, photo thumbnail (square, 80px), mission details to right
- Approve Button: Green background, checkmark icon
- Reject Button: Red background, X icon
- Photo View: Dark background (black), photo centered, zoom controls
- Status Indicators: Timestamp in gray, urgency marker if >24hrs old (amber warning)

**Workflow:**
- Tap "View Photo" → Full-screen overlay
- Approve → Points auto-awarded to user, notification sent, card dismissed with slide animation
- Reject → Modal asking for reason (dropdown: "Not clear", "Wrong location", "Other"), user notified

---

### 3.3 Admin Console (Central Command & Control)

**Vibe:** "Data-Driven Command Center with Executive Polish"

**Design Approach:**
- **Desktop-First:** Designed for large screens (1440px+), responsive down to tablets
- **Information Density:** More data visible without scrolling compared to mobile apps
- **Advanced Data Visualization:** Charts, graphs, heatmaps for analytics
- **Professional Tone:** Enterprise-grade UI suitable for stakeholder presentations

**3.3.1 Admin Dashboard (Home)**

**Layout Direction (Desktop):**
```
┌─────────────────────────────────────────────────────────────────┐
│ [Top Navigation Bar]                                            │
│ The Trophy Admin | [Dashboard] [Missions] [Rewards] [Partners] │
│ [Search] [Notifications] [Profile]                             │
├─────────────────────────────────────────────────────────────────┤
│ Dashboard Overview                                              │
│ ┌──────────┐ ┌──────────┐ ┌──────────┐ ┌──────────┐          │
│ │ 👥 5,234 │ │ 🎯 12,450│ │ 💰 3.2M  │ │ 🏪 28    │          │ <- KPI Cards
│ │ Active   │ │ Missions │ │ Points   │ │ Partners │          │
│ │ Users    │ │ Completed│ │ Awarded  │ │ Active   │          │
│ └──────────┘ └──────────┘ └──────────┘ └──────────┘          │
│                                                                 │
│ ┌─────────────────────────────────┐ ┌──────────────────────┐  │
│ │ 📊 Point Economy (7-day trend)  │ │ 🎯 Mission Performance│ │
│ │ [Line Chart: Awarded vs Redeemed]│ [Bar Chart: Completion]│ │
│ └─────────────────────────────────┘ └──────────────────────┘  │
│                                                                 │
│ ┌─────────────────────────────────┐ ┌──────────────────────┐  │
│ │ 🗺️ User Activity Heatmap        │ │ ⚠️ Fraud Alerts (3)  │ │
│ │ [Geographic map with clusters]  │ │ [Alert list]         │ │
│ └─────────────────────────────────┘ └──────────────────────┘  │
└─────────────────────────────────────────────────────────────────┘
```

**Visual Treatment:**
- Top Nav: Dark background (midnight charcoal), white text, accent underline on active section
- KPI Cards: White background, large numbers (36px JetBrains Mono), icon (32px), trend arrow (up/down)
- Charts: High-contrast colors (blue for earned, orange for spent), gridlines subtle (light gray)
- Heatmap: Google Maps integration, custom styling (dark mode map, accent color clusters)
- Alert Panel: Warning amber header, list of suspicious activities with "Review" CTA

**Responsive Behavior:**
- Desktop: 2-column chart layout
- Tablet: Single-column charts, stacked
- Mobile: Admin console discourages mobile use; shows "Use desktop for best experience" banner

---

**3.3.2 Mission Management Screen**

**Layout Direction:**
```
┌─────────────────────────────────────────────────────────────────┐
│ Missions                           [+ Create New Mission] ←──┐  │
│                                                              │  │
│ [Search Missions] [Filter: All | Active | Expired]          │  │
│                                                              │  │
│ ┌──────────────────────────────────────────────────────────┐│  │
│ │ Mission Name          | Type      | Points | Status       ││  │
│ ├──────────────────────────────────────────────────────────┤│  │
│ │ Café Check-in         | Location  | 50     | Active ●    ││  │
│ │ Barista Selfie        | Photo     | 100    | Active ●    ││  │
│ │ Stadium Tour          | Location  | 200    | Expired     ││  │
│ │ Share on Social       | Social    | 25     | Active ●    ││  │
│ └──────────────────────────────────────────────────────────┘│  │
│                                                              │  │
│ [Pagination: 1 2 3 ... 10]                                  │  │
└─────────────────────────────────────────────────────────────────┘

Create/Edit Mission Modal:
┌─────────────────────────────────────┐
│ Create New Mission                  │
│                                     │
│ Mission Name*                       │
│ [Input field]                       │
│                                     │
│ Mission Type*                       │
│ [Dropdown: Location | Photo | ...]  │
│                                     │
│ Point Reward*                       │
│ [Number input]                      │
│                                     │
│ Description (Thai)*                 │
│ [Textarea]                          │
│                                     │
│ Description (English)*              │
│ [Textarea]                          │
│                                     │
│ [If Location selected:]             │
│ Geofence Location                   │
│ [Map picker + KML upload]           │
│                                     │
│ [Cancel] [Save Mission]             │
└─────────────────────────────────────┘
```

**Visual Treatment:**
- Data Table: Striped rows (alternating white/light gray), hover highlight (accent tint)
- Status Indicators: Green dot (active), gray dot (expired), amber dot (pending)
- Create Button: Primary accent gradient, top-right corner, prominent
- Modal: Level 4 shadow, centered overlay, dark backdrop (60% opacity)
- Form Fields: Clear labels, validation messages below fields (red for errors)
- Map Picker: Embedded Google Maps with drawing tools for polygon selection

**Special Features:**
- Bulk Actions: Select multiple missions → "Activate", "Deactivate", "Delete" actions
- Mission Analytics: Click row → Slide-out panel showing completion rates, user engagement
- KML Upload: Drag-and-drop zone for uploading geofence files

---

**3.3.3 Trophy Wallet Admin Screen**

**Layout Direction:**
```
┌─────────────────────────────────────────────────────────────────┐
│ Trophy Wallet Management                                        │
│                                                                 │
│ ┌──────────┐ ┌──────────┐ ┌──────────┐ ┌──────────┐          │
│ │ 💰 Total │ │ ⬆️ Outbound│ │ ⬇️ Inbound│ │ ⚖️ Liability│       │
│ │ 3.2M pts │ │ 45K pts  │ │ 32K pts  │ │ 1.6M THB │          │
│ │ Circulation│ This Week│  This Week│  Est. Value│          │
│ └──────────┘ └──────────┘ └──────────┘ └──────────┘          │
│                                                                 │
│ 📊 Economic Health                                              │
│ ┌─────────────────────────────────┐                            │
│ │ Burn Rate: 68% ✅ (target 60-80%)│                           │
│ │ [Progress bar]                  │                            │
│ │                                 │                            │
│ │ Point Velocity: 12 days ✅      │                            │
│ │ (avg. time to redemption)       │                            │
│ └─────────────────────────────────┘                            │
│                                                                 │
│ 🔄 Recent Transfers (Requires Approval)                        │
│ ┌──────────────────────────────────────────────────────────┐  │
│ │ User          | Type     | Amount | Status    | Action   │  │
│ ├──────────────────────────────────────────────────────────┤  │
│ │ Somchai P.    | Outbound | 1,000  | Pending   | [Approve]│  │
│ │ Maria K.      | Inbound  | 500    | Approved  | —        │  │
│ └──────────────────────────────────────────────────────────┘  │
│                                                                 │
│ ⚙️ Transfer Settings                                           │
│ [Daily Limit] [Monthly Limit] [Transfer Fee] [Auto-Approve]   │
└─────────────────────────────────────────────────────────────────┘
```

**Visual Treatment:**
- Economic Health Card: Large metrics with status indicators (checkmark/warning icon)
- Progress Bars: Color-coded (green if in healthy range, amber if borderline, red if critical)
- Transfer Table: Similar to mission table, status column color-coded
- Settings Panel: Inline editors with save confirmation, validation for numeric limits

**Special Features:**
- Real-Time Monitoring: WebSocket updates for live transfer requests
- Alert System: Browser notifications for large transfers (>5,000 pts)
- Export Functionality: Download transaction history as CSV or PDF

---

## 4. Gamification Visual Language

### 4.1 Point Representation

**Visual Philosophy:** Points should feel valuable, collectible, and celebratory - not just numbers.

**Primary Point Icon: "Trophy Coin"**
- Design: Circular coin with trophy emblem in center
- Color: Gradient gold (Champion Gold #FFD700 to Sunset Gold #F59E0B)
- Size Variations: 16px (inline), 24px (standard), 32px (emphasis), 48px (celebration)
- Animation: Rotate on earn (360° spin, 400ms), subtle float on hover

**Point Display Formats:**

```
Small Context (Mission Cards):
🪙 50 pts

Medium Context (Wallet Balance):
💎 12,450 Points

Large Context (Achievement Celebration):
You Earned
🎉 100 POINTS 🎉
(Animated confetti burst)

Transaction Context:
+ 50 pts (green, upward arrow icon)
- 200 pts (orange, downward arrow icon)
```

**Point Animation Patterns:**
- Earning: Coins fly from action location to wallet icon in top-right (bezier curve path, 600ms)
- Spending: Wallet icon pulses, points counter animates down (number odometer effect)
- Transfer: Points flow between two wallet icons (animated arc path)

### 4.2 Tier System Visualization

**Two-Tier System: Standard & Exclusive**

**Standard Tier:**
- Icon: Silver medal with "S" emblem
- Color: Silver Medal (#C0C0C0) with cool gray undertones
- Badge Shape: Circular with subtle radial gradient
- Progress Ring: Silver fill
- Benefits Display: Listed with checkmarks, neutral tone

**Exclusive Tier:**
- Icon: Crown/trophy combination with "E" emblem OR platinum/gold star
- Color: Champion Gold (#FFD700) to Platinum Shine (#E5E4E2) gradient
- Badge Shape: Shield or crown silhouette with shimmer effect
- Progress Ring: Gold gradient fill with animated shimmer
- Benefits Display: Premium styling with gold accent borders

**Tier Progression Visual:**
```
Standard → Exclusive
[Silver Badge] ━━━━━━━━━━━━━ 65% ━━━━━ → [Gold Badge]
"850 points to Exclusive"
```

**Tier Upgrade Celebration:**
1. Screen darkens (modal overlay)
2. New tier badge animates in from top (scale + bounce)
3. Confetti burst (gold colors)
4. Sound effect (optional): Triumphant chime
5. Text reveals: "Congratulations! You're now Exclusive!"
6. Benefits list slides in from bottom
7. CTA: "Explore Exclusive Rewards" button

### 4.3 Mission Achievement States

**Mission Card State Design:**

**Not Started (Default):**
- Background: White
- Border: Light gray (1px)
- Icon: Full-color mission type icon
- CTA Button: "Start Mission" (accent gradient)
- Progress: Empty bar (0%)

**In Progress:**
- Background: White
- Border: Accent color (2px, pulsing animation)
- Icon: Full-color with subtle glow
- Badge: "In Progress" pill (amber background)
- Progress: Partially filled bar (animated)
- CTA Button: "Continue" (accent solid)

**Pending Verification:**
- Background: Light amber tint
- Border: Amber (2px)
- Icon: Clock icon overlay on mission icon
- Badge: "Awaiting Approval" pill
- Progress: Full bar (amber color)
- Status Text: "Partner reviewing..." (gray text)

**Completed:**
- Background: Light green tint
- Border: Success green (2px)
- Icon: Checkmark badge overlay on mission icon
- Badge: "Completed ✓" pill (green background)
- Progress: Full bar (green color)
- Points Display: "+ 100 pts" (bold, green)
- Animation on First View: Confetti burst from card

**Expired/Unavailable:**
- Background: Light gray
- Opacity: 60%
- Icon: Grayscale
- Badge: "Expired" pill (gray background)
- No CTA button

### 4.4 Achievement Badge Design System

**Badge Categories:**

**Welcome Achievements (Bronze):**
- First Mission, First Check-in, Profile Complete
- Icon Style: Simple line art
- Background: Bronze glow gradient
- Border: 2px bronze

**Milestone Achievements (Silver):**
- 10 Missions, 100 Points Earned, 5 Rewards Redeemed
- Icon Style: Detailed line art with fill
- Background: Silver gradient with subtle shine
- Border: 2px silver with glow

**Elite Achievements (Gold):**
- 100 Missions, 10,000 Points, Tier Upgrade, Partner Champion
- Icon Style: Complex design with multiple colors
- Background: Gold gradient with animated shimmer
- Border: 3px gold with animated glow

**Special/Hidden Achievements (Platinum):**
- Easter eggs, rare accomplishments, exclusive events
- Icon Style: Unique custom designs
- Background: Platinum shine with rainbow shimmer
- Border: 3px platinum with animated rainbow glow
- Unlock Animation: Extra celebratory (full-screen takeover)

**Badge Display Formats:**
```
Locked State:
[Grayscale icon silhouette]
"???" (question marks)
Lock icon overlay

Unlocked State:
[Full-color icon]
Badge name
Date earned (small text)
Tap to view details

Grid View (Profile):
4 columns on mobile
6 columns on tablet/desktop
Circular badges (64px diameter)
Locked badges: 30% opacity
```

**Badge Detail Modal:**
```
[Large Badge Icon - 120px]
Achievement Name (H2)
"Rarity: Rare (12% of users)" (small text)
Description of achievement
Date Earned: Jan 2, 2026
[Share Button] [Close]
```

### 4.5 Leaderboard Design (Optional Feature)

**Leaderboard Visual Approach:**

**Philosophy:** Friendly competition, not toxic ranking. Celebrate top performers without shaming lower ranks.

**Layout:**
```
Top 3 Podium View:
    [2nd]     [1st]     [3rd]
  Silver 🥈  Gold 🥇  Bronze 🥈
  User B     User A    User C
  2,450 pts  3,100 pts 2,200 pts

Ranked List (4th onwards):
4. User D - 2,000 pts
5. User E - 1,850 pts
...
47. You - 1,200 pts (highlighted row)
...
```

**Visual Treatment:**
- Podium: 3D-style podium illustration, top 3 users have avatars with medal overlays
- Your Rank: Highlighted row (accent gradient background), larger text
- Rank Numbers: JetBrains Mono, gray color
- Point Totals: Bold, accent color
- Avatar Frames: Bronze/silver/gold borders for top 3
- Refresh Indicator: "Updated 5 mins ago" (small gray text)

**Privacy Consideration:**
- Default: Show only first name + last initial (e.g., "Somchai P.")
- User Setting: Opt-in to show full name or nickname
- Option to hide from leaderboard entirely

---

## 5. Trophy Wallet Design Vibe (Expanded)

### 5.1 Wallet as "Financial Hub" Metaphor

**Design Concept:** The Trophy Wallet should feel like a premium digital wallet (think Apple Pay meets crypto wallet) but gamified and friendly.

**Visual Identity:**
- **Card-Based Design:** Main balance displayed on a "card" that looks like a premium credit/debit card
- **Gradient Backgrounds:** Each wallet function (balance, transfer, history) gets its own gradient card
- **Secure Feeling:** Subtle lock icons, shield imagery, trust badges to emphasize security
- **Playful Accents:** Trophy and coin iconography to maintain gamification connection

### 5.2 Balance Card Design

**Visual Specification:**
```
┌─────────────────────────────────────┐
│ TROPHY WALLET                       │ <- Small header text (white, 11px)
│                                     │
│     💎 12,450                       │ <- Large balance (white, 32px, JetBrains Mono)
│     Points                          │ <- Label (white, 14px)
│                                     │
│ ≈ THB 6,225                         │ <- Conversion (white 60% opacity, 12px)
│                                     │
│ [Chip graphic]        [Trophy icon] │ <- Card details (subtle, white outlines)
└─────────────────────────────────────┘
Background: Gradient (Indigo to Purple, 45° angle)
Shadow: Level 2
Radius: 16px
Aspect Ratio: ~1.58 (credit card proportion)
```

**Interactive States:**
- Default: Gradient background, Level 2 shadow
- Tap: Slight scale down (0.98), expand to full wallet detail view
- Balance Update: Number animates (odometer rolling effect, 400ms)

### 5.3 Point Transfer Visual Flow

**Transfer Initiation Screen:**
```
┌─────────────────────────────────────┐
│ Transfer Points                     │
│                                     │
│ Current Balance: 💎 12,450 pts      │
│                                     │
│ Transfer Type:                      │
│ [●Outbound  ○Inbound]              │ <- Radio buttons
│                                     │
│ Amount:                             │
│ [  _______  ] pts                   │ <- Large number input
│                                     │
│ Recipient/Source:                   │
│ [Dropdown: Partner Systems]         │
│                                     │
│ Transfer Fee: 25 pts (2%)           │ <- Auto-calculated, gray text
│ You'll Send/Receive: 1,025 pts      │ <- Bold
│                                     │
│ [Cancel] [Preview Transfer]         │
└─────────────────────────────────────┘
```

**Transfer Confirmation Modal:**
```
┌─────────────────────────────────────┐
│ Confirm Transfer                    │
│                                     │
│ ┌─────────────────────────────────┐ │
│ │  [Your Wallet Icon]             │ │
│ │         ⬇️                      │ │ <- Animated arrow
│ │  [Recipient Icon]               │ │
│ └─────────────────────────────────┘ │
│                                     │
│ Amount: 1,000 pts                   │
│ Fee: 25 pts                         │
│ Total: 1,025 pts                    │
│                                     │
│ Recipient: Credit Card Rewards      │
│                                     │
│ [ ] I confirm this transfer         │ <- Checkbox
│                                     │
│ [Cancel] [Confirm Transfer]         │
└─────────────────────────────────────┘
```

**Transfer Success Animation:**
1. Modal content fades out
2. Animated points flow from source to destination (particle effect)
3. Success checkmark animates in (scale bounce)
4. "Transfer Successful!" message
5. Updated balance displays
6. CTA: "View Transaction History"

### 5.4 Transaction History Design

**List Item Format:**
```
┌─────────────────────────────────────┐
│ + 100 pts                           │ <- Large, green (earning)
│ Café Check-in Mission               │ <- Description, H4
│ 2 hours ago • Transaction #12345    │ <- Metadata, small gray
└─────────────────────────────────────┘

┌─────────────────────────────────────┐
│ - 500 pts                           │ <- Large, orange (spending)
│ VIP Parking Reward Redeemed         │
│ Yesterday • Transaction #12344      │
└─────────────────────────────────────┘

┌─────────────────────────────────────┐
│ ⬆️ 1,000 pts                        │ <- Large, blue (transfer out)
│ Transfer to Credit Card Rewards     │
│ 3 days ago • Transaction #12343     │
└─────────────────────────────────────┘
```

**Filters & Search:**
- Filter Chips: "All", "Earned", "Spent", "Transfers"
- Date Range Picker: "Last 7 days", "Last 30 days", "Custom"
- Search: Text input for transaction description search
- Export: "Download CSV" button in header

**Visual Treatment:**
- Alternating row backgrounds (white/light gray)
- Icon badges for transaction type (left side of amount)
- Swipe actions: Swipe left to reveal "Share Receipt" button
- Infinite scroll with loading indicator

### 5.5 Economic Health Indicators (User-Facing)

**Point Value Transparency:**
```
Your Points Are Worth:
💰 1 point ≈ THB 0.50

Based on reward catalog average
[Info icon tooltip]
```

**Point Expiry Warning:**
```
⚠️ 450 points expiring soon!
Expire on: Feb 28, 2026 (25 days)
[View Expiring Points] [Redeem Now]

Visual: Warning amber background card, clock icon
```

**Savings Tracker:**
```
💵 You've Saved THB 3,250
From reward redemptions this year

[View Savings Breakdown]

Visual: Success green background card, chart icon
```

---

## 6. Interaction Patterns & Micro-Animations

### 6.1 Navigation Transitions

**Screen-to-Screen Transitions:**
- **Forward Navigation:** Slide from right (300ms ease-out)
- **Back Navigation:** Slide to right (300ms ease-in)
- **Modal Open:** Fade in + scale from 0.9 to 1.0 (250ms ease-out)
- **Modal Close:** Fade out + scale from 1.0 to 0.95 (200ms ease-in)
- **Bottom Sheet:** Slide up from bottom (300ms ease-out)

**Tab Switching:**
- Icon: Scale pulse (1.0 → 1.15 → 1.0, 200ms)
- Label: Fade from gray to accent color (150ms)
- Indicator: Slide to new tab position (250ms ease-in-out)

### 6.2 Button & CTA Interactions

**Primary Button:**
- Tap Down: Scale 0.98, slight shadow reduction (100ms)
- Release: Scale back to 1.0 (150ms), shadow back to Level 1
- Loading State: Button text fades, spinner fades in (200ms), button disabled (gray)
- Success State: Checkmark icon replaces text (300ms), green background flash

**Icon Button:**
- Tap: Scale bounce (1.0 → 1.2 → 1.0, 200ms)
- Ripple Effect: Circular ripple from tap point (400ms, accent color 20% opacity)
- Haptic Feedback: Light impact on tap

**Toggle Switch:**
- Slide Animation: 200ms ease-in-out
- Color Change: Background fades from gray to accent (200ms)
- Haptic: Medium impact on toggle

### 6.3 List & Card Interactions

**Card Tap:**
- Tap Down: Scale 0.98, Level 1 shadow
- Release: Scale 1.0, Level 2 shadow
- Hover (Desktop): Lift effect (translate Y -2px, Level 2 shadow, 200ms)

**Swipe Actions:**
- Swipe Threshold: 30% of card width
- Reveal Animation: Action button slides in from edge (150ms)
- Delete Swipe: Swipe >60% → Card slides out + fade (300ms) → List animates up to fill gap

**Pull to Refresh:**
- Pull Indicator: Trophy icon rotates as user pulls
- Release Threshold: 80px pull distance
- Refresh Animation: Trophy spins 360° continuously until data loads
- Completion: Trophy animates to checkmark, brief pause, fade out

### 6.4 Achievement Celebrations

**Mission Complete Animation:**
1. Mission card border pulses (accent color, 2 cycles)
2. Checkmark icon animates in (scale bounce from center)
3. Points earned badge slides in from right
4. Confetti burst from card edges (300ms)
5. Card background tints green (subtle, 20% opacity)

**Achievement Unlock (Full-Screen):**
1. Screen dims (80% black overlay, 200ms)
2. Badge icon scales in from 0 to 1.2 to 1.0 (400ms, bounce easing)
3. Confetti particles fall from top (1000ms, continuous)
4. Text reveals: "Achievement Unlocked!" (fade + slide up, 300ms)
5. Badge name appears (fade in, 200ms delay)
6. Sound effect: Triumphant chime (optional)
7. Auto-dismiss after 3s OR user tap

**Tier Upgrade (Epic Celebration):**
1. Screen dims (90% dark overlay)
2. Current tier badge scales out (300ms)
3. New tier badge emerges with golden shimmer (600ms)
4. Radial gold particles burst outward (800ms)
5. Text: "You've Reached Exclusive Tier!" (bold, large, fade + scale in)
6. Benefits list slides in from bottom (staggered, 100ms delays)
7. CTA: "Explore Exclusive Rewards" button (prominent, gradient)
8. Manual dismiss required (X button in corner)

### 6.5 Loading States

**Skeleton Screens:**
- Use for initial page loads
- Gray shapes (placeholder boxes) matching content layout
- Shimmer effect: Gradient moves left to right (1200ms loop)
- Example: Mission cards show gray rectangles with shimmer before data loads

**Spinner:**
- Trophy icon rotating 360° (800ms linear loop)
- Used for in-context loading (e.g., button loading, modal waiting)
- Color: Accent gradient

**Progressive Loading:**
- Load critical content first (e.g., wallet balance)
- Secondary content fades in as it loads (staggered, 100ms delays)
- Images: Low-res placeholder → full-res fade in (200ms)

### 6.6 Error & Empty States

**Error Message:**
```
┌─────────────────────────────────────┐
│        [Error Icon - 64px]          │ <- Red circular icon with X
│                                     │
│    Oops! Something went wrong       │ <- H3, centered
│                                     │
│  We couldn't load your missions.    │ <- Body text, gray
│  Please check your connection.      │
│                                     │
│        [Try Again Button]           │
└─────────────────────────────────────┘
```

**Empty State:**
```
┌─────────────────────────────────────┐
│    [Empty State Illustration]       │ <- Friendly graphic (trophy + ?)
│                                     │
│    No Missions Yet                  │ <- H3
│                                     │
│ Check back soon for new missions!   │ <- Body text
│                                     │
│    [Explore Rewards Instead]        │ <- Secondary CTA
└─────────────────────────────────────┘
```

**Visual Style:**
- Illustrations: Simple line art, accent color, friendly tone
- No harsh "error" language, use encouraging copy
- Always provide actionable CTA

---

## 7. Responsive Design Principles

### 7.1 Mobile-First Breakpoints

```
Mobile (Small): 320px - 374px
Mobile (Medium): 375px - 414px (primary design target - iPhone SE to iPhone Pro)
Mobile (Large): 415px - 767px (large phones, small tablets)
Tablet: 768px - 1023px (iPad portrait)
Desktop (Small): 1024px - 1439px
Desktop (Large): 1440px+ (primary admin console target)
```

### 7.2 Touch Target Guidelines

**Minimum Touch Target:** 44x44px (Apple HIG standard)
**Recommended:** 48x48px for primary actions
**Spacing Between Targets:** Minimum 8px gap

**Examples:**
- Tab bar icons: 56px tall (icon + label)
- Primary buttons: 48px height
- List items: 64px minimum height
- Form inputs: 48px height

### 7.3 Typography Scaling

**Mobile (375px base):**
- Display XL: 32px
- H1: 24px
- H2: 20px
- Body: 14px

**Tablet (768px):**
- Scale +10%: Display XL: 36px, H1: 26px, etc.

**Desktop (1440px):**
- Scale +20%: Display XL: 40px, H1: 28px, etc.
- Wider line-length requires larger text for readability

### 7.4 Layout Adaptations

**Navigation:**
- Mobile: Bottom tab bar (5 items max)
- Tablet: Bottom tab bar OR left sidebar (user preference)
- Desktop (Admin): Top horizontal nav + left sidebar

**Card Grids:**
- Mobile: Single column (full-width cards)
- Tablet: 2 columns (reward cards), single column (mission cards)
- Desktop: 3-4 columns depending on card size

**Modals:**
- Mobile: Full-screen or bottom sheet
- Tablet: Centered modal (max 600px width)
- Desktop: Centered modal (max 800px width)

---

## 8. Accessibility Considerations

### 8.1 Color Contrast

**WCAG 2.1 AA Compliance (Minimum):**
- Body Text: 4.5:1 contrast ratio
- Large Text (18px+): 3:1 contrast ratio
- UI Components: 3:1 contrast ratio

**Testing:**
- All text on gradient backgrounds must pass contrast on darkest part of gradient
- Provide alternative contrast modes if needed

### 8.2 Typography Accessibility

**Font Size:**
- Minimum body text: 14px (never go below)
- Support system font scaling (iOS/Android)
- Test all UI at 200% font size

**Line Height:**
- Minimum 1.5x font size for body text
- 1.3x for headings

**Language Support:**
- Thai text: Ensure proper diacritical mark rendering
- Test with actual Thai content (vowels above/below)
- Allow slightly more line-height for Thai text

### 8.3 Interactive Elements

**Focus States:**
- Keyboard navigation: Visible focus ring (2px accent color outline, 2px offset)
- Skip to main content link (for screen readers)
- Logical tab order

**Screen Reader Support:**
- All images have alt text
- Icons paired with labels (aria-label if icon-only)
- Form inputs have associated labels
- Announce dynamic content changes (ARIA live regions)

**Touch & Motor:**
- Large touch targets (48px minimum)
- No double-tap required interactions
- Sufficient spacing between interactive elements
- Support for one-handed use (key actions within thumb reach)

### 8.4 Motion & Animation

**Respect User Preferences:**
- Detect `prefers-reduced-motion` system setting
- If enabled: Disable decorative animations, keep functional transitions (page changes)
- Never use auto-playing videos/animations without controls

**Avoiding Seizure Triggers:**
- No flashing content >3 times per second
- No bright strobing effects

---

## 9. Platform-Specific Considerations

### 9.1 iOS Design Alignment

**Following Apple Human Interface Guidelines:**
- Use SF Symbols where appropriate (system icons)
- Respect iOS safe areas (notch, home indicator)
- Native iOS gestures: Swipe back from left edge
- Modal presentation: Sheet style with drag-to-dismiss
- Haptic feedback: Use UIImpactFeedbackGenerator for key interactions

**iOS-Specific Elements:**
- Large Titles: Page headers can use large title style (scrolls to inline)
- Blur Effects: Use iOS blur views for overlays (vibrancy)
- System Fonts: Optionally allow system font (SF Pro) as alternative to Inter

### 9.2 Android Design Alignment

**Following Material Design 3 Principles:**
- Floating Action Button (FAB): Use for primary quick actions
- Navigation Drawer: Optional left sidebar for secondary navigation
- Snackbar: Use for brief notifications (vs iOS toast)
- Ripple Effects: Material ripple on button/card taps
- Elevation System: Use Material elevation levels

**Android-Specific Elements:**
- Bottom Sheets: Use Material bottom sheet component
- System Navigation: Support gesture navigation (Android 10+)
- Adaptive Icons: Provide adaptive icon for app launcher

### 9.3 Web (Admin Console) Specifics

**Browser Support:**
- Modern browsers: Chrome, Firefox, Safari, Edge (latest 2 versions)
- No IE11 support required

**Web-Specific Interactions:**
- Hover states for all interactive elements
- Keyboard shortcuts for power users (e.g., Cmd+K for search)
- Right-click context menus where appropriate
- Print-friendly styles for reports

---

## 10. Thai Market & Cultural Considerations

### 10.1 Thai User Preferences

**Visual Preferences:**
- Thai users appreciate vibrant colors (not overly minimal/sparse)
- Gold is culturally significant (auspicious, premium)
- Friendly, approachable design > overly corporate/cold
- LINE-style interface familiarity (chat bubbles, stickers as visual language)

**Content Hierarchy:**
- Thai users scan differently (top-to-bottom, right-to-left possible for certain content)
- Important information should be prominent and repeated
- Visual aids (icons, illustrations) aid comprehension

### 10.2 Thai Language UI Considerations

**Typography:**
- Thai text requires more vertical space (vowels/tone marks)
- Avoid all-caps for Thai (causes rendering issues)
- Use Sarabun or Noto Sans Thai (excellent web fonts)
- Test with actual Thai content, not placeholders

**Text Length:**
- Thai translations often 20-30% longer than English
- Design flexible layouts that accommodate text expansion
- Avoid fixed-width containers that cut off Thai text

**Date & Time Formats:**
- Buddhist calendar option (2569 vs 2026)
- Thai date format: วัน/เดือน/ปี (day/month/year)
- Time: 24-hour format common in Thailand

### 10.3 PDPA & Privacy Compliance

**Consent UI:**
- Clear, prominent consent checkboxes during registration
- Privacy policy in Thai language (required)
- "ฉันยอมรับข้อกำหนดและเงื่อนไข" (I accept terms and conditions)

**Data Management:**
- "Delete My Data" option in settings
- "Export My Data" functionality (PDPA right to data portability)
- Clear privacy indicators (lock icons, "Your data is secure" messaging)

### 10.4 Payment & Currency

**Thai Baht (THB) Display:**
- Format: ฿1,234.56 OR 1,234.56 บาท
- No decimal for whole amounts: ฿1,234
- Use comma thousand separators

**Point-to-Currency Conversion:**
- Always show clear conversion rates
- Example: "1,000 points = ฿500 value"

---

## 11. Implementation Notes for Developers

### 11.1 Design System Handoff

**Figma/Sketch Files (To Be Created):**
- Component library with all buttons, cards, inputs
- Color palette with hex codes and semantic naming
- Typography scale with font specs
- Icon library (SVG exports)
- Screen mockups for all key flows

**Design Tokens (JSON Format):**
```json
{
  "colors": {
    "primary": {
      "500": "#6366F1",
      "gradient": "linear-gradient(135deg, #6366F1, #8B5CF6)"
    },
    "neutral": {
      "900": "#1A1D29",
      "100": "#ECEFF4"
    }
  },
  "spacing": {
    "xs": "4px",
    "sm": "8px",
    "md": "16px"
  },
  "typography": {
    "heading1": {
      "fontSize": "24px",
      "lineHeight": "32px",
      "fontWeight": "700"
    }
  }
}
```

### 11.2 Animation Specifications

**Easing Functions:**
- `ease-out`: UI elements entering view
- `ease-in`: UI elements exiting view
- `ease-in-out`: Transitions between states
- `spring`: Bounce animations (use platform-specific spring curves)

**Standard Durations:**
- Quick: 100-200ms (micro-interactions, hovers)
- Standard: 250-350ms (page transitions, modal open/close)
- Slow: 400-600ms (celebrations, important animations)

**CSS Example:**
```css
.button {
  transition: transform 200ms ease-out, box-shadow 200ms ease-out;
}
.button:active {
  transform: scale(0.98);
}
```

### 11.3 Component Reusability

**Atomic Design Approach:**
- **Atoms:** Buttons, inputs, icons, typography
- **Molecules:** Search bar (input + icon), stat card (icon + number + label)
- **Organisms:** Mission card, reward card, navigation bar
- **Templates:** Screen layouts (mission center, wallet, profile)
- **Pages:** Fully populated screens with real content

**Naming Convention:**
- Use BEM (Block Element Modifier) for CSS classes
- Component files: PascalCase (e.g., `MissionCard.tsx`)
- Props/variables: camelCase

---

## 12. Design Deliverables & Next Steps

### 12.1 Phase 1 (POC) Design Scope

**Essential Screens (High-Fidelity Mockups):**
1. Customer App:
   - Home Dashboard
   - Mission Center (list view)
   - Mission Detail (location-based)
   - Trophy Wallet (balance view)
   - Profile (basic)
2. Partner App:
   - Dashboard
   - QR Scanner
3. Admin Console:
   - Dashboard (desktop)
   - Mission Management (list)

**Design Assets:**
- Color palette definition
- Typography specs
- Primary icon set (30-40 icons)
- Component library (buttons, cards, inputs)

### 12.2 Phase 2 (MVP) Design Scope

**Complete Design System:**
- All screens for Customer, Partner, Admin apps
- Full component library (Figma/Sketch)
- Icon library (100+ icons)
- Illustration set (empty states, onboarding)
- Animation specifications document
- Design tokens (JSON/code export)

**Additional Screens:**
- Onboarding flow (customer app)
- All mission types (photo, purchase, social)
- Reward redemption flow
- Tier upgrade screens
- Complete Trophy Wallet (transfers, history)
- Partner approval workflows
- Admin analytics screens

### 12.3 Design Review Process

**Stakeholder Reviews:**
1. **Initial Concept Review:** Present mood boards, color palettes, typography choices
2. **Wireframe Review:** Validate layouts and information architecture
3. **High-Fidelity Review:** Review detailed mockups and interactions
4. **Prototype Testing:** Interactive prototype user testing (5-8 users)
5. **Design Approval:** Final sign-off before development handoff

**Design Iteration:**
- Allow 2 rounds of revisions per screen set
- Major changes beyond 2 rounds = scope change (additional budget)

### 12.4 Design-to-Development Handoff

**Deliverables to Dev Team:**
- Figma/Sketch files with developer mode access
- Exported assets (SVG icons, PNG images @1x, @2x, @3x)
- Design tokens JSON file
- Animation specifications document
- Component documentation (usage guidelines)
- Accessibility checklist

**Developer Support:**
- Design QA during development (weekly reviews)
- Clarifications and adjustments (minor tweaks included)
- Responsive breakpoint guidance

---

## 13. Conclusion & Design Vision Summary

The Trophy platform's visual identity strikes a careful balance:

**🏆 Achievement-Focused:** Every interaction celebrates user progress and accomplishments through thoughtful animations, color-coded states, and trophy/medal metaphors.

**⚖️ Brand-Neutral Foundation:** The white-label architecture ensures the platform serves any sports organization while maintaining a cohesive, premium aesthetic through sophisticated neutrals and configurable accent colors.

**🇹🇭 Thai Market Excellence:** Bilingual design consideration, cultural color preferences, and PDPA compliance are baked into every screen and component.

**💼 Enterprise-Grade Quality:** The admin console and partner tools feel professional and data-driven, suitable for B2B presentations and stakeholder confidence.

**🎮 Gamification Mastery:** Points feel valuable, tiers feel aspirational, and missions feel engaging through carefully crafted visual language and micro-animations.

**📱 Mobile-First, Accessible:** Touch-optimized interfaces, generous spacing, high contrast, and respect for user preferences (reduced motion, font scaling) ensure inclusivity.

This Vibe Design document serves as the foundation for all visual design work on The Trophy platform. It should be referenced during every design decision, updated as the platform evolves, and maintained as a living document throughout the project lifecycle.

---

**Document Version:** 1.0
**Last Updated:** January 2, 2026
**Next Review:** Upon completion of Phase 1 (POC) designs
**Owner:** Stitch Design Team (DOS)

**Related Documents:**
- The Trophy Proposal (Deliverables/Proposal.md)
- Stitch Prompt Guide (Kuekan/00 Preparation/Stitch Prompt Guide.md)
- Feature List (To be created)
- Technical Specifications (To be created)

---

**Ready to Build:**
This comprehensive vibe design provides clear direction for:
- UI/UX designers creating mockups
- Frontend developers implementing components
- Product managers validating features
- Stakeholders reviewing design decisions

**Next Action:** Begin high-fidelity mockup creation for Phase 1 (POC) screens using this vibe as the foundation.
