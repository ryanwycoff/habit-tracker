# Habit Tracker - Complete Habits & Schedule Reference

## 📋 All Trackable Habits (30 Total)

### 🧗 Climbing (2 habits)
1. **Dead Hang (3 sets to failure)** - `deadhang`
2. **Climbing Training** - `climbing`

### 💪 Fitness (7 habits)
1. **Workout Complete** - `workout`
2. **Yoga Session** - `yoga`
3. **Wake Up & Hydrate** - `wakeup`
4. **Light Walk/Activity** - `walk`
5. **Stretching & Mobility** - `stretching`
6. **Foam Rolling** - `foam_rolling`
7. **Bedtime** - `bed`

### 🏌️ Recreation (4 habits)
1. **Golf Simulator** - `golf`
2. **Commute to Work** - `commute_work`
3. **Commute Home** - `commute_home`
4. **Relax/Free Time** - `relax`
5. **Errands/Shopping** - `errands`

### 💈 Grooming (5 habits)
1. **Beard Oil Application** - `beardoil`
2. **Microneedling Session** - `microneedling`
3. **Hair Styling** - `hairstyle`
4. **Manscaping (Scheduled Area)** - `manscaping`
5. **Shower** - `shower`
6. **Full Grooming Session** - `grooming_full`

### 🍽️ Nutrition (6 habits)
1. **Meal 1 - Breakfast** - `meal1`
2. **Meal 2 - Mid-Morning/Lunch** - `meal2`
3. **Meal 3 - Afternoon** - `meal3`
4. **Meal 4 - Post-Work** - `meal4`
5. **Meal 5 - Dinner** - `meal5`
6. **Meal Prep** - `meal_prep`

### 💊 Supplements (4 habits)
1. **Morning Supplements** - `supplements_am`
2. **Pre-Workout Supplements** - `supplements_pre`
3. **Post-Workout Supplements** - `supplements_post`
4. **Evening Supplements** - `supplements_pm`

---

## 🗓️ Schedule to Habit Mapping

Every schedule item now maps to a trackable habit. When you complete a habit, all related schedule items are marked complete.

### Schedule Text → Habit Mapping

| Schedule Text | Maps To Habit | Habit ID |
|--------------|---------------|----------|
| "Wake Up & Hydrate" | Wake Up & Hydrate | `wakeup` |
| "Dead Hang (3 sets)" | Dead Hang | `deadhang` |
| "Beard Oil..." | Beard Oil Application | `beardoil` |
| "Microneedling" | Microneedling Session | `microneedling` |
| "Pre-Workout Supplements" | Pre-Workout Supplements | `supplements_pre` |
| "Workout: ..." | Workout Complete | `workout` |
| "Climbing..." | Climbing Training | `climbing` |
| "Shower..." | Shower | `shower` |
| "Hair Styling" | Hair Styling | `hairstyle` |
| "Meal 1..." | Meal 1 - Breakfast | `meal1` |
| "Meal 2..." | Meal 2 | `meal2` |
| "Meal 3..." | Meal 3 | `meal3` |
| "Meal 4..." | Meal 4 | `meal4` |
| "Meal 5..." | Meal 5 | `meal5` |
| "Morning Supplements" | Morning Supplements | `supplements_am` |
| "Post-Workout..." | Post-Workout Supplements | `supplements_post` |
| "Evening Supplements" | Evening Supplements | `supplements_pm` |
| "Leave for Work..." | Commute to Work | `commute_work` |
| "Arrive Home" | Commute Home | `commute_home` |
| "Manscaping..." | Manscaping | `manscaping` |
| "Golf Simulator" | Golf Simulator | `golf` |
| "Yoga Session" | Yoga Session | `yoga` |
| "Relax..." / "Free Time" / "Hobby" | Relax/Free Time | `relax` |
| "Light Walk" / "Bike" | Light Walk/Activity | `walk` |
| "Stretching" / "Mobility" | Stretching & Mobility | `stretching` |
| "Foam Rolling" | Foam Rolling | `foam_rolling` |
| "Errands" / "Shopping" / "Activities" | Errands/Shopping | `errands` |
| "Meal Prep" | Meal Prep | `meal_prep` |
| "Full Grooming..." | Full Grooming Session | `grooming_full` |
| "Bed" | Bedtime | `bed` |

---

## ✨ Reactive UI Updates

All UI elements now update automatically without page refresh when you:

### ✅ **Edit a Habit**
**What updates:**
- Habit checklist (main view)
- Category badges update
- Calendar dots recalculate
- Stats bar updates
- Up Next / Overdue lists refresh

### ✅ **Edit Schedule**
**What updates:**
- Time Schedule view refreshes
- Up Next list shows new times
- Overdue detection uses new schedule
- Schedule view reflects changes immediately

### ✅ **Edit a Category**
**What updates:**
- All habit badges update with new name
- Habit editor dropdown shows new category
- No page refresh needed

### ✅ **Check Off a Habit**
**What updates:**
- Calendar dot turns black
- Stats bar increments
- Up Next / Overdue lists refresh
- Schedule view shows item as completed
- Completion percentage updates

### ✅ **Add Notes**
**What updates:**
- Auto-saves as you type
- Data persists immediately
- No manual save needed

---

## 🎯 Complete Tracking Workflow

### Morning Example (4:30 AM)
1. **Open app** → See overdue section (empty)
2. **See Up Next:**
   - ☐ 4:30 AM - Wake Up & Hydrate
   - ☐ 4:40 AM - Dead Hang
   - ☐ 4:50 AM - Beard Oil
3. **Check off Wake Up** → Disappears, next item moves up
4. **Check off Dead Hang** → Calendar dot updates, stats increment
5. **All happens instantly** - no refresh needed

### Schedule Edit Example
1. **Tap "Manage"**
2. **Edit Schedule** → Change "4:40 AM" to "4:45 AM"
3. **Close settings**
4. **Up Next automatically shows** "4:45 AM - Dead Hang"
5. **No refresh needed** - UI updated immediately

### Habit Edit Example
1. **Tap "Manage"**
2. **Edit Habits** → Rename "Workout Complete" to "Morning Workout"
3. **Close settings**
4. **Habit checklist shows** "Morning Workout"
5. **Schedule view shows** completed status correctly
6. **Everything synced** automatically

---

## 🔄 Technical Implementation

### Reactive Functions
All these functions now trigger automatic UI updates:

- `saveHabits()` → Refreshes calendar, habit list, stats, overview
- `saveSchedule()` → Refreshes habit list, overview
- `saveCategories()` → Refreshes habit list
- `updateHabitStatus()` → Refreshes calendar, schedule view
- `setData()` → Refreshes stats, overview

### Smart Detection
The system intelligently detects what needs updating:
- **Schedule view active?** → Also refresh that
- **Specific date selected?** → Update that date's habits
- **Today's date?** → Update overdue/up next
- **Any change?** → Recalculate stats

---

## 💡 Benefits

### For Users
✅ Instant feedback on actions
✅ No confusing "refresh needed" states
✅ Changes immediately visible everywhere
✅ Feels like a native app
✅ No data inconsistency

### For Data Integrity
✅ All views always show current data
✅ Calendar always matches habit status
✅ Schedule always reflects habit completion
✅ Stats always accurate

---

## 📱 Usage Tips

1. **Edit freely** - All changes take effect immediately
2. **Check from anywhere** - Overview, checklist, or schedule view
3. **Customize your schedule** - Times update across all views
4. **Rename habits** - Names update everywhere instantly
5. **Add new habits** - Immediately available for tracking

The system is now fully reactive with complete habit coverage!
