# Weekli
## Product Requirements Document (PRD)
*Weekly Meal Planning — Simplified*

**Version 2.0 | June 2026 | Prepared by Lisha Thomas**

---

## 1. Product Overview

| Attribute | Detail |
|---|---|
| Product Name | Weekli |
| Version | 2.0 |
| Date | June 2026 |
| Prepared by | Lisha Thomas — UX Designer |
| Platform | iOS Mobile App (iPhone) |
| Status | Design Phase |
| Previous name | Grocart |

### Product Summary
Weekli is a focused mobile app that helps users plan their meals for the week by selecting from a personal recipe library. Users build their own recipe collection, categorise recipes by meal type, and plan their weekly meals with ease — Breakfast, Lunch and Dinner for every day of the week.

### Tagline
*"Plan your week, one meal at a time."*

---

## 2. Problem Statement

Most people struggle with deciding what to eat every day. The questions "what's for breakfast?", "what should I cook for dinner?" repeat every single day — causing decision fatigue, wasted time and unhealthy last minute choices.

**Weekli solves this by:**
- Giving users a personal recipe library they build over time
- Making weekly meal planning fast and effortless
- Showing only relevant recipes for each meal type — no confusion

### Current Workarounds & Their Gaps

| Workaround | Gap |
|---|---|
| Google Keep / Notes app | No structure, no categories, no weekly view |
| Paper and pen | Not accessible, easy to lose, no recipe library |
| Memory | Inconsistent, leads to repetitive meals or decision fatigue |
| Meal Planner | Closest inspiration for Weekli — strong weekly planning and clean UI, but no personal recipe library or meal type pinning |
| Mealime | Recipe database focused, not personal recipe library |

---

## 3. Target Users

### Primary Users
- Housewives and homemakers managing weekly family meals
- Couples planning meals together
- Individuals living alone who want to eat intentionally
- Busy professionals who want to plan their week ahead

### User Persona — Lisha

| Attribute | Detail |
|---|---|
| Name | Kiara |
| Age | 30 |
| Location | Dubai, UAE |
| Situation | Married, plans family meals every weekend |
| Current tool | Writes meals for the week on the fridge. Keeps the shopping list separately on Google Keep — the two are never in one place. |
| Pain point | Meals are on the fridge, shopping list is on the phone — when at the supermarket she has to cross-reference both. No single place to plan and manage it all. |
| Goal | Plan all meals for the week in one place using her own recipes |

---

## 4. Product Goals

### User Goals
- Build a personal recipe library organised by meal type
- Plan meals for all 7 days of the week quickly
- See the week's meal plan at a glance
- Reuse favourite recipes without retyping
- Pin a meal type (Breakfast, Lunch or Dinner) to favourite recipes for faster planning
- Add new recipes to the library as they discover them

### Business Goals
- Build a focused, well designed meal planning app
- Demonstrate strong UX design process for portfolio case study
- Show ability to scope a product clearly and execute it well

---

## 5. Core Features

### Feature 1 — Recipe Library

| Detail | Description |
|---|---|
| What it does | User builds a personal collection of recipes |
| Categories | Breakfast, Lunch, Dinner — separate lists |
| Add recipe | User types recipe name and assigns to a category |
| Delete recipe | User removes recipes they no longer want |
| Categorise | User can tag a recipe to multiple meal types |
| Pin meal type | User can pin a meal type (Breakfast, Lunch or Dinner) to a recipe — pinned recipes appear at the top of the list when planning that meal slot |
| Access | Available via Meals icon in bottom nav |

### Feature 2 — Meal Planner

| Detail | Description |
|---|---|
| What it does | User plans Breakfast, Lunch and Dinner for each day of the week |
| How it works | User taps "+ Add" on any meal slot — selects from recipe library |
| Recipe filtering | Only relevant recipes shown — Breakfast slot shows Breakfast recipes |
| Week view | All 7 days visible and scrollable |
| Week reset | App auto advances to new empty week every Monday |

### Feature 3 — Add Meal Flow

**First time user**

| Detail | Description |
|---|---|
| Step 1 | User taps the Add CTA on any meal slot |
| Step 2 | Bottom sheet slides up with a simple text field |
| Step 3 | User types the meal name and taps Add |
| Output | Meal is instantly added to that slot on the home screen |

**Returning user**

| Detail | Description |
|---|---|
| Step 1 | User taps "+ Add" on any meal slot |
| Step 2 | Bottom sheet opens — 3 options: Add, Clean, See recipes |
| Add | Opens relevant recipe list filtered to meal type — user selects a saved recipe |
| Clean | Opens recipe list — user deletes unwanted recipes |
| See recipes | Opens full recipe library — user categorises and tags recipes |

---

## 6. App Screens

| Screen | Section | Purpose |
|---|---|---|
| Onboarding | — | Welcome new users — show app goals |
| Home Screen — Empty State | Home | First time user — no meals planned yet |
| Home Screen — Active State | Home | Week overview — all 7 days with meals |
| Meal Planner — Empty State | Home | No meals planned for the week |
| Meal Planner — Active State | Home | Week with meals filled in |
| Bottom Sheet — Add/Clean/See | Home | 3 action options when user taps "+ Add" |
| Recipe List Screen | Home | Breakfast/Lunch/Dinner specific recipe list |
| Recipe Library Screen | Meals | Full recipe collection — categorise, add, delete |
| Settings Screen | Settings | App preferences and profile |

---

## 7. Key User Flows

### Flow 1 — First Time User
- Opens app → Onboarding screen
- Taps "Get Started" → Meal Planner Empty State
- Taps Add CTA on Monday Breakfast → Bottom sheet slides up with text field
- Types meal name → Taps Add → Meal added to Monday Breakfast on home screen
- Repeats for Lunch and Dinner slots across the week
- Home Screen shows completed week plan

### Flow 2 — Returning User (New Week)
- Opens app on Monday → New empty week (auto reset)
- Taps "+ Add" on any meal slot → Bottom sheet opens with 3 options: Add, Clean, See recipes
- Taps "Add" → Recipe list opens filtered to that meal type
- Selects a saved recipe → Meal added to slot instantly
- Repeats for remaining slots — planning gets faster as the recipe library grows

---

## 8. Competitive Analysis

| Feature | Weekli | Meal Planner | Mealime | Google Keep |
|---|---|---|---|---|
| Weekly meal planner | ✅ | ✅ | ✅ | ❌ |
| Simple minimal UI | ✅ | ✅ | ✅ | ✅ |
| Meal type categorisation | ✅ | ✅ | ✅ | ❌ |
| Personal recipe library | ✅ | ✅ | ❌ | ❌ |
| Meal type pinning | ✅ | ✅ | ❌ | ❌ |
| Cross meal type tagging | ✅ | ✅ | ❌ | ❌ |
| No recipe database needed | ✅ | ✅ | ❌ | ✅ |
| Gender neutral design | ✅ | ❌ | ✅ | ✅ |


---

## 9. Design Principles
- **Focused** — one job, done well — plan your week with your own recipes
- **Personal** — your recipes, your meals, your week
- **Simple** — every action takes 3 taps or less
- **Calm** — no overwhelming features or cluttered screens
- **Inclusive** — clean minimal design for all users

---

## 10. Success Metrics

| Metric | Target |
|---|---|
| Time to plan a full week | Under 5 minutes |
| Taps to add a meal | 3 taps maximum |
| Recipe library size after 4 weeks | 15+ recipes |
| Weekly return rate | 70% of users plan a new week |
| App store rating target | 4.5 stars and above |

---

## 11. Out of Scope (Version 1.0)
- Grocery list generation
- Budget tracking
- Shopping mode
- Weekly reminders
- Recipe database or suggestions
- Calorie or nutrition tracking
- Social sharing of meal plans
- AI generated meal suggestions
- Multi-user or family sharing

---

## 12. Change Log

| Version | Date | Change |
|---|---|---|
| 1.0 | June 2026 | Initial PRD — app named Grocart |
| 2.0 | June 2026 | App renamed to Weekli — scope simplified to meal planning only |

---

*Weekli PRD — Version 2.0 — Prepared by Lisha Thomas — June 2026*
