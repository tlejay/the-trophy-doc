# C-REWARDS Mobile Site Mockup - Vibe Code Prompt

## Project Overview

Create a **mobile-first web application mockup** for **C-REWARDS**, a gamified loyalty and engagement platform. This is a **UI/UX demonstration prototype** with all features clickable and functional in the frontend, but **without any backend/database connections**.

**Tech Stack:**
- Vite + React (or Next.js)
- Vanilla CSS (no TailwindCSS)
- Local state management (useState/useContext)
- Mock data stored in JSON files

**Design Requirements:**
- Mobile-first (375px width as primary, responsive up to tablet)
- Premium, modern aesthetic with glassmorphism effects
- Dark mode as default with optional light mode toggle
- Smooth micro-animations on all interactions
- Thai language primary, English secondary

---

## Color Palette

```css
:root {
  --primary: #6366F1;      /* Indigo */
  --primary-light: #818CF8;
  --primary-dark: #4F46E5;
  --accent: #F59E0B;        /* Amber for points/rewards */
  --accent-glow: #FBBF24;
  --success: #10B981;       /* Emerald */
  --warning: #F97316;       /* Orange */
  --error: #EF4444;         /* Red */
  --bg-dark: #0F172A;       /* Slate 900 */
  --bg-card: #1E293B;       /* Slate 800 */
  --bg-glass: rgba(30, 41, 59, 0.7);
  --text-primary: #F8FAFC;
  --text-secondary: #94A3B8;
  --border: rgba(148, 163, 184, 0.2);
}
```

---

## Application Structure

### 1. Bottom Navigation Bar (Fixed)
- **Home** (🏠) - Dashboard
- **Missions** (🎯) - Mission Center
- **Scan** (📷) - QR Scanner (center, prominent)
- **Rewards** (🎁) - Reward Catalog
- **Profile** (👤) - User Profile

---

## Screen Specifications

### Screen 1: Splash Screen
- Full-screen gradient background (primary to dark)
- Animated C-REWARDS logo (fade in + scale)
- Loading spinner
- Auto-transition to Login after 2 seconds

### Screen 2: Login/Registration
**Login Tab:**
- Phone number input with +66 prefix
- OTP request button
- Social login buttons (LINE, Facebook, Google)
- "New user? Register" link

**Register Tab:**
- Phone number
- Full name (Thai)
- Email (optional)
- Date of birth
- Terms & conditions checkbox
- Register button

**OTP Verification:**
- 6-digit OTP input (auto-focus next)
- Countdown timer (60 seconds)
- Resend OTP link
- Verify button

### Screen 3: Home Dashboard
**Header:**
- User avatar (circle) + greeting "สวัสดี, [Name]"
- Notification bell icon with badge
- Current tier badge (Standard/Exclusive)

**Points Card (Hero):**
- Large point balance with animated counter
- "฿ equivalent" display (e.g., "≈ ฿250")
- Tier progress bar (if Standard, show progress to Exclusive)
- Glassmorphism card effect with subtle gradient border

**Quick Actions (Grid 2x2):**
- Check-in Now (📍)
- Scan QR (📷)
- View Missions (🎯)
- My Rewards (🎁)

**Active Missions Section:**
- Horizontal scrollable cards
- Each card: Mission image, title, points reward, deadline badge
- "View All" link

**Nearby Partners Section:**
- Vertical list (3 items visible)
- Partner logo, name, distance, available points
- "See More" link

**Recent Activity:**
- Timeline style list
- Icons for earn/burn
- Points +/- with timestamp
- Transaction description

### Screen 4: Mission Center
**Header:**
- "ภารกิจ" title
- Filter icon (opens bottom sheet)

**Filter Bottom Sheet:**
- Mission Type: All, Location, Photo, Event, Purchase, Social
- Status: Available, In Progress, Completed
- Sort: Newest, Ending Soon, Highest Points

**Tabs:**
- Available | In Progress | Completed

**Mission Cards (List):**
- Mission thumbnail image
- Title + brief description
- Point reward badge
- Deadline countdown
- Distance (if location-based)
- Progress indicator (if multi-step)
- "Start Mission" / "Continue" / "View Details" CTA

**Mission Detail Modal (Full Screen Overlay):**
- Hero image
- Mission title + description
- Requirements list with checkboxes
- Point reward (large, prominent)
- Validity period
- Partner info (if applicable)
- Location map preview (if location-based)
- "Start Mission" / "Check-in" / "Upload Photo" CTA
- Share button

### Screen 5: QR Scanner
**Camera View:**
- Full-screen camera preview (simulated with gradient)
- Scanning frame overlay (animated corners)
- Flash toggle button
- Close (X) button

**Scan Result (Bottom Sheet):**
- Success/Error icon with animation
- Result message
- Points earned (if applicable)
- "Done" button

**Manual Entry Option:**
- "Enter code manually" link
- Text input for coupon/mission code

### Screen 6: Reward Catalog
**Header:**
- "รางวัล" title
- Search icon
- Points balance badge

**Categories (Horizontal Scroll):**
- All | Exclusive Experiences | VIP Access | Partner Discounts | Merchandise

**Reward Cards (Grid 2 columns):**
- Reward image
- Title
- Point cost badge
- Stock remaining (if limited)
- Partner logo (small)
- "Exclusive" badge (if tier-locked)

**Reward Detail Modal:**
- Hero image gallery (swipeable)
- Title + full description
- Point cost (large)
- Terms & conditions (expandable)
- Validity period
- Redemption instructions
- "Redeem Now" button (with confirmation modal)
- Stock counter

**Redemption Confirmation Modal:**
- Summary of reward
- Points to be deducted
- Final balance after redemption
- "Confirm" / "Cancel" buttons

**Redemption Success Screen:**
- Success animation (confetti)
- QR code (for partner scanning)
- Coupon code text
- Expiry date
- "Add to Wallet" / "Share" buttons
- Instructions for use

### Screen 7: My Coupons (Sub-screen of Rewards)
**Tabs:**
- Active | Used | Expired

**Coupon Cards:**
- Reward image thumbnail
- Title
- Expiry countdown
- QR code preview (tap to enlarge)
- "Use Now" button

**Coupon Detail:**
- Full QR code display
- Coupon code (tap to copy)
- Usage instructions
- Partner location (with map link)

### Screen 8: User Profile
**Header:**
- Cover image (editable)
- Avatar (circle, editable)
- Name + tier badge
- Member since date

**Stats Summary (Horizontal):**
- Total Points Earned
- Missions Completed
- Rewards Redeemed

**Tier Section:**
- Current tier visual (Standard/Exclusive)
- Benefits list for current tier
- Progress to next tier (if applicable)
- "Learn More" link

**Menu List:**
- 📝 Edit Profile
- 🔔 Notification Settings
- 📜 Transaction History
- ❓ Help & Support
- 📄 Terms & Conditions
- 🔒 Privacy Policy
- 🌐 Language (TH/EN)
- 🌙 Dark/Light Mode Toggle
- 🚪 Logout

### Screen 9: Transaction History
**Filter Tabs:**
- All | Earned | Redeemed

**Transaction List:**
- Icon (+ for earn, - for redeem)
- Description
- Points amount (green for +, red for -)
- Date & time
- Status badge (Completed/Pending)

**Transaction Detail Modal:**
- Full details of transaction
- Reference number
- Related mission/reward info

### Screen 10: Notification Center
**Notification List:**
- Icon based on type
- Title + preview text
- Timestamp
- Read/unread indicator (dot)
- Swipe to delete

**Notification Types:**
- New mission available
- Mission expiring soon
- Points earned
- Reward redeemed
- System announcement
- Tier upgrade

### Screen 11: Leaderboard (Optional)
**Header:**
- "Leaderboard" title
- Period selector (Week/Month/All Time)

**Top 3 Podium:**
- Visual podium with avatars
- Name + points

**Ranking List:**
- Rank number
- Avatar
- Name
- Points
- Highlight current user's row

---

## Mock Data Structure

### users.json
```json
{
  "currentUser": {
    "id": "u001",
    "name": "สมชาย ใจดี",
    "phone": "0891234567",
    "email": "somchai@email.com",
    "avatar": "/avatars/default.png",
    "tier": "Standard",
    "points": 2500,
    "totalEarned": 5000,
    "totalRedeemed": 2500,
    "missionsCompleted": 15,
    "memberSince": "2024-06-15",
    "tierProgress": 65
  }
}
```

### missions.json
```json
{
  "missions": [
    {
      "id": "m001",
      "type": "location",
      "title": "Check-in ที่สนามฝึกซ้อม",
      "description": "เช็คอินที่สนามฝึกซ้อมทีมเพื่อรับแต้มพิเศษ",
      "points": 100,
      "image": "/missions/training-ground.jpg",
      "deadline": "2025-12-31",
      "status": "available",
      "requirements": ["อยู่ในพื้นที่สนาม", "กดปุ่ม Check-in"],
      "location": { "lat": 13.7563, "lng": 100.5018 }
    },
    {
      "id": "m002",
      "type": "photo",
      "title": "ถ่ายรูปกับ Mascot",
      "description": "ถ่ายรูปคู่กับ Mascot และอัพโหลดเพื่อรับแต้ม",
      "points": 200,
      "image": "/missions/mascot.jpg",
      "deadline": "2025-12-28",
      "status": "available",
      "requirements": ["ถ่ายรูปที่มี Mascot ในภาพ", "อัพโหลดรูปภาพ"]
    },
    {
      "id": "m003",
      "type": "event",
      "title": "เข้าชมแมตช์วันเสาร์",
      "description": "เข้าชมเกมการแข่งขันในสนามเพื่อรับแต้มสะสม",
      "points": 300,
      "image": "/missions/match-day.jpg",
      "deadline": "2025-12-27",
      "status": "in_progress"
    },
    {
      "id": "m004",
      "type": "purchase",
      "title": "ช้อปที่ร้านค้าพาร์ทเนอร์",
      "description": "ซื้อสินค้าที่ร้านพาร์ทเนอร์และสแกน QR เพื่อรับแต้ม",
      "points": 50,
      "image": "/missions/partner-shop.jpg",
      "deadline": "2025-12-30",
      "status": "available"
    },
    {
      "id": "m005",
      "type": "social",
      "title": "แชร์บนโซเชียล",
      "description": "แชร์โพสต์ทีมบน Facebook และรับแต้มทันที",
      "points": 25,
      "image": "/missions/social-share.jpg",
      "deadline": "2025-12-31",
      "status": "completed"
    }
  ]
}
```

### rewards.json
```json
{
  "rewards": [
    {
      "id": "r001",
      "title": "เข้าชมสนามฝึกซ้อม VIP",
      "description": "สิทธิ์เข้าชมการฝึกซ้อมแบบ VIP พร้อมของที่ระลึก",
      "category": "exclusive",
      "points": 5000,
      "image": "/rewards/vip-training.jpg",
      "stock": 10,
      "tierRequired": "Exclusive",
      "validUntil": "2026-03-31"
    },
    {
      "id": "r002",
      "title": "ส่วนลด 20% ร้านกาแฟ",
      "description": "รับส่วนลด 20% ที่ร้านกาแฟพาร์ทเนอร์ทุกสาขา",
      "category": "discount",
      "points": 200,
      "image": "/rewards/coffee-discount.jpg",
      "stock": 100,
      "tierRequired": null,
      "validUntil": "2025-12-31"
    },
    {
      "id": "r003",
      "title": "เสื้อทีมลิมิเต็ด",
      "description": "เสื้อทีมรุ่นพิเศษ Limited Edition",
      "category": "merchandise",
      "points": 3000,
      "image": "/rewards/limited-jersey.jpg",
      "stock": 50,
      "tierRequired": null,
      "validUntil": "2026-06-30"
    },
    {
      "id": "r004",
      "title": "ที่จอดรถ VIP",
      "description": "สิทธิ์ที่จอดรถ VIP สำหรับวันแข่ง 1 นัด",
      "category": "vip",
      "points": 500,
      "image": "/rewards/vip-parking.jpg",
      "stock": 20,
      "tierRequired": "Standard",
      "validUntil": "2025-12-31"
    }
  ]
}
```

### partners.json
```json
{
  "partners": [
    {
      "id": "p001",
      "name": "Central Department Store",
      "logo": "/partners/central.png",
      "distance": "1.2 km",
      "pointsAvailable": 100
    },
    {
      "id": "p002",
      "name": "CafeAmazon",
      "logo": "/partners/cafe-amazon.png",
      "distance": "0.5 km",
      "pointsAvailable": 50
    },
    {
      "id": "p003",
      "name": "Car Wash Pro",
      "logo": "/partners/carwash.png",
      "distance": "2.0 km",
      "pointsAvailable": 75
    }
  ]
}
```

### transactions.json
```json
{
  "transactions": [
    {
      "id": "t001",
      "type": "earn",
      "description": "Check-in ที่สนาม",
      "points": 100,
      "date": "2025-12-24T14:30:00",
      "status": "completed"
    },
    {
      "id": "t002",
      "type": "redeem",
      "description": "แลกส่วนลดกาแฟ",
      "points": -200,
      "date": "2025-12-23T10:15:00",
      "status": "completed"
    }
  ]
}
```

---

## Component Library

### Buttons
- Primary (filled, gradient)
- Secondary (outlined)
- Ghost (text only)
- Icon button (circular)
- Floating Action Button (for QR scan)

### Cards
- Mission Card
- Reward Card
- Partner Card
- Stats Card
- Transaction Card

### Inputs
- Text input with floating label
- Phone input with country code
- OTP input (6 separate boxes)
- Search input with icon
- Toggle switch

### Modals/Overlays
- Bottom sheet (draggable)
- Full screen modal
- Confirmation dialog
- Toast notifications

### Navigation
- Bottom nav bar (fixed)
- Top header with back button
- Tab navigation

### Feedback
- Loading spinner
- Skeleton loaders
- Empty states
- Error states
- Success animations (confetti, checkmark)

---

## Animations

### Page Transitions
- Slide in from right (push)
- Slide in from bottom (modal)
- Fade in (overlays)

### Micro-interactions
- Button press scale (0.95)
- Card hover lift (translateY -4px + shadow)
- Points counter increment animation
- Progress bar fill animation
- Tab indicator slide
- Skeleton shimmer effect
- Pull-to-refresh spinner

---

## File Structure

```
/src
  /assets
    /images
    /icons
  /components
    /common
      Button.jsx
      Card.jsx
      Input.jsx
      Modal.jsx
      BottomSheet.jsx
      Toast.jsx
      Skeleton.jsx
    /layout
      BottomNav.jsx
      Header.jsx
      PageContainer.jsx
    /missions
      MissionCard.jsx
      MissionDetail.jsx
      MissionFilter.jsx
    /rewards
      RewardCard.jsx
      RewardDetail.jsx
      CouponCard.jsx
      QRDisplay.jsx
    /profile
      TierBadge.jsx
      StatsGrid.jsx
      ProfileMenu.jsx
  /pages
    Splash.jsx
    Login.jsx
    Home.jsx
    Missions.jsx
    Scanner.jsx
    Rewards.jsx
    MyCoupons.jsx
    Profile.jsx
    TransactionHistory.jsx
    Notifications.jsx
    Leaderboard.jsx
  /data
    users.json
    missions.json
    rewards.json
    partners.json
    transactions.json
    notifications.json
  /context
    UserContext.jsx
    ThemeContext.jsx
  /hooks
    useLocalStorage.js
    useToast.js
  /styles
    index.css
    variables.css
    animations.css
  /utils
    formatters.js
    mockDelay.js
  App.jsx
  main.jsx
```

---

## Implementation Notes

1. **No Backend Required:** All data comes from JSON files in `/src/data/`

2. **State Persistence:** Use localStorage to persist user actions (completed missions, redeemed rewards) across page refreshes

3. **Simulated Delays:** Add 500-1500ms delays on actions to simulate API calls

4. **QR Scanner:** Display a camera-like gradient animation, not actual camera access

5. **Location Check-in:** Show a mock "location verified" message after 2 seconds

6. **Photo Upload:** Accept file input but just preview locally, no actual upload

7. **Responsive:** Primary target is 375px width (iPhone SE), scale up to 768px (tablet)

8. **Thai Language:** All UI text in Thai, with English translations in comments

9. **Accessibility:** Include proper ARIA labels and focus states

10. **Performance:** Lazy load images, use skeleton loaders during transitions

---

## Deliverables Checklist

- [ ] Splash screen with animation
- [ ] Login/Register flow with OTP
- [ ] Home dashboard with all sections
- [ ] Mission Center with filtering
- [ ] Mission detail view
- [ ] QR Scanner simulation
- [ ] Reward catalog with categories
- [ ] Reward redemption flow
- [ ] My Coupons section
- [ ] User profile with all menus
- [ ] Transaction history
- [ ] Notification center
- [ ] Dark/Light mode toggle
- [ ] Thai/English language toggle
- [ ] All navigation working
- [ ] Animations on all interactions
- [ ] Mock data populated
- [ ] Responsive design (375px-768px)

---

**Character Count Target:** Under 50,000 characters
**Current Character Count:** ~20,000 characters

---
