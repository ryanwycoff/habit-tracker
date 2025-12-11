# iPhone Installation & Usage Guide
## Habit Tracker - Complete Instructions

---

## 📱 INSTALLATION ON iPHONE

### Step 1: Transfer the File to Your iPhone

**Option A: AirDrop (Easiest)**
1. Save the `habit-tracker.html` file to your Mac/PC
2. Right-click the file and select "Share" → "AirDrop"
3. Select your iPhone from the AirDrop menu
4. On your iPhone, tap "Accept"
5. The file will open in Safari automatically

**Option B: Email**
1. Email the `habit-tracker.html` file to yourself
2. Open the email on your iPhone
3. Tap on the attached file to download it
4. It will open in Safari

**Option C: Cloud Storage**
1. Upload `habit-tracker.html` to iCloud Drive, Dropbox, or Google Drive
2. Open the cloud storage app on your iPhone
3. Navigate to the file and tap it
4. Select "Open in Safari" or "Open with Safari"

**Option D: Direct Download**
1. Host the file on a personal website or GitHub
2. Navigate to the URL in Safari on your iPhone
3. The page will load and work immediately

### Step 2: Add to Home Screen (Critical for Best Experience)

Once the file is open in Safari:

1. **Tap the Share button** (square with arrow pointing up) at the bottom of Safari
2. **Scroll down** and tap **"Add to Home Screen"**
3. **Name it** (e.g., "Habits" or "Tracker")
4. **Tap "Add"** in the top right

**What this does:**
- Creates an app icon on your home screen
- Opens in full-screen mode (no Safari bars)
- Feels like a native iPhone app
- Keeps your data separate from Safari browsing

### Step 3: Verify Installation

1. Go to your iPhone home screen
2. Find the new app icon
3. Tap it to open
4. You should see the full habit tracker interface

---

## 💾 WHERE YOUR DATA IS SAVED

### Storage Location

Your data is stored in **Safari's Local Storage** on your iPhone. Specifically:

```
iPhone → Settings → Safari → Website Data → [Your tracker domain]
```

### What This Means

**✅ PROS:**
- Data stays on YOUR device only (private and secure)
- No internet connection needed after initial load
- No login or account required
- Works completely offline
- No monthly fees or subscriptions
- Nobody can access your data

**⚠️ IMPORTANT NOTES:**
- Data is tied to Safari browser and the specific domain/file location
- Clearing Safari cache/website data WILL delete your tracker data
- Data does NOT sync between devices automatically
- If you delete the home screen icon, data remains (it's in Safari)
- If you clear Safari website data, you'll lose all tracking history

### Data Persistence

Your data will remain saved:
- ✅ After closing the app
- ✅ After restarting your iPhone
- ✅ After iOS updates
- ✅ Even if you delete the home screen icon (data is in Safari)

Your data will be LOST if you:
- ❌ Clear Safari website data (Settings → Safari → Clear History and Website Data)
- ❌ Reset all settings on iPhone
- ❌ Restore iPhone from non-backup
- ❌ Change the file location (must re-import data)

---

## 📊 USING THE HABIT TRACKER

### Main Interface Overview

**Top Section:**
- **Title Bar**: "Habit Tracker"
- **Stats Bar**: Month completion %, Current streak, Total habits completed

**Today's Overview (Real-time):**
- **⚠️ Overdue**: Shows habits you should have completed already today
  - Only appears if you have overdue items
  - Each item has a checkbox to quickly mark complete
  - Shows time and habit name
  - Updates in real-time as you complete items
- **Up Next**: Shows the next 3 upcoming habits from your schedule
  - Shows time and habit name
  - Quick checkbox to mark complete
  - Disappears when checked off
  - Shows "All caught up! 🎉" when nothing is scheduled

**Month Navigation:**
- **← Previous**: Go to previous month
- **Current Month**: Shows current month and year
- **Next →**: Go to next month

**Calendar:**
- Each day shows as a box
- **Today** has a black circle around the date
- **Selected day** has a black border
- **Completion dots** below each date (black = completed, gray = not done)

**Bottom Menu:**
- **Manage**: Edit habits, schedule, categories, and data
- **Export**: Download backup of all your data
- **Import**: Restore data from a backup file

### Daily Usage

#### 0. **Check Today's Overview** (New!)

Before you start your day, look at the overview section above the calendar:

**Overdue Section (⚠️):**
- Shows **top 3 most late** habits you should have completed
- Sorted by how late they are (most late first)
- Example at 10:00 AM:
  - "4:40 AM - Dead Hang" (5h 20m late) 
  - "4:50 AM - Beard Oil" (5h 10m late)
  - "5:05 AM - Workout" (4h 55m late)
- **Count badge** shows total overdue
  - If more than 3: "3 (+2 more)"
  - If 3 or less: Just the number
- Only appears if you have overdue items
- **Quick complete**: Tap checkbox to mark done instantly
- **Auto-replaces**: Complete one → Next overdue item appears
- Automatically updates as you complete habits
- Disappears when all overdue items are complete

**Up Next Section:**
- Shows your next 3 scheduled habits
- Updates automatically throughout the day
- Example at 6:00 AM shows:
  - "6:45 AM - Meal 1: Eggs & Oats"
  - "7:00 AM - Leave for Work"
  - "8:00 AM - Arrive at Work"
- **Quick complete**: Tap checkbox to mark done
- Refreshes to show next items as you complete
- Shows "All caught up! 🎉" when nothing is scheduled

**Why This is Useful:**
- See at a glance what you need to do NOW
- Quick check-offs without scrolling through full habit list
- Stay on schedule throughout the day
- Never forget time-sensitive habits
- Instant feedback on your progress
- **Prioritizes most late items** - focus on what's most overdue first
- **Auto-replaces completed items** - always shows your next 3 priorities

**How Overdue Priority Works:**
1. You have 8 overdue habits at 2:00 PM
2. App shows the 3 MOST late items (from earliest times)
3. Badge shows "3 (+5 more)"
4. You complete the most overdue item
5. 4th most late item automatically appears in the list
6. Badge updates to "3 (+4 more)"
7. Repeat until all caught up

**Example Flow:**
```
10:00 AM - 5 habits overdue from morning:
⚠️ Overdue (3 +2 more):
☐ 4:40 AM - Dead Hang           [Most late]
☐ 4:50 AM - Beard Oil
☐ 5:05 AM - Workout
[6:45 AM Meal 1 and 7:00 AM Commute waiting]

Complete Dead Hang →

⚠️ Overdue (3 +1 more):
☐ 4:50 AM - Beard Oil           [Now most late]
☐ 5:05 AM - Workout
☐ 6:45 AM - Meal 1              [Moved up automatically]
[7:00 AM Commute still waiting]
```

**How It Works:**
- Compares current time to your schedule
- Automatically categorizes habits as overdue or upcoming
- Updates every time you check something off
- Only shows trackable habits (meals, workouts, etc.)
- Ignores non-habit schedule items (like "Work Begins")

#### 1. **Select a Day**
- Tap any date in the calendar
- The day will highlight with a black border
- Habit checklist appears below

#### 2. **Two View Modes**

**Habit Checklist Mode** (Default)
- Shows all 18 habits as checkboxes
- Each habit has:
  - ☐ Checkbox (tap to mark complete)
  - Habit name
  - Category tag (black badge)
  - Notes field (for details)

**Time Schedule Mode**
- Tap "Time Schedule" button
- Shows your entire day timeline
- Each activity shows with its scheduled time
- Completed items appear grayed out
- Great for following your daily schedule

#### 3. **Check Off Habits**
- Tap the checkbox next to any habit
- It will turn black with a checkmark
- Automatically saves
- The calendar dots update immediately

#### 4. **Add Notes**
- Tap in the notes field below any habit
- Type details:
  - Workout weights/reps
  - Meal timing
  - Energy levels
  - Grooming areas completed
  - Any observations
- Notes save automatically as you type
- Notes are private to that specific day + habit

---

## 🔧 CRUD OPERATIONS (CREATE, READ, UPDATE, DELETE)

### Accessing the Management Menu

1. Tap **"Manage"** button at the bottom of the screen
2. The settings panel slides up
3. Four sections available:
   - Manage Categories
   - Edit Habits
   - Edit Schedule  
   - Data Management

### Managing Categories (Full CRUD)

Categories help organize your habits into groups. The default categories are:
- Climbing
- Fitness
- Recreation
- Grooming
- Nutrition
- Supplements

#### **VIEW ALL CATEGORIES**
- Scroll to "Manage Categories" section
- All categories listed with:
  - Category badge (black)
  - Category name (editable field)
  - Usage count (how many habits use this category)
  - Delete button

#### **EDIT CATEGORY NAME**
- Tap in the category name field
- Type new name
- Changes save automatically
- **IMPORTANT**: All habits using this category update automatically
- Example: Rename "Fitness" to "Exercise" → all fitness habits now show "Exercise"

#### **DELETE A CATEGORY**
- Tap "Delete" button next to category
- If habits use this category, you'll see:
  - Confirmation dialog
  - List of affected habits
  - Warning that they'll become "Uncategorized"
- Confirm deletion
- All affected habits automatically change to "Uncategorized"
- **NOTE**: "Uncategorized" category is automatically created if needed

#### **ADD NEW CATEGORY**
- Tap "+ Add New Category" button at bottom
- Enter category name in prompt
- New category appears in list
- Now available in habit editor dropdowns
- Examples of custom categories:
  - "Morning Routine"
  - "Evening Routine"
  - "Recovery"
  - "Mental Health"
  - "Hydration"

#### **DUPLICATE PROTECTION**
- Cannot create two categories with same name
- Case-insensitive (e.g., "fitness" = "Fitness")
- You'll get an error if you try

#### **CATEGORY BEST PRACTICES**
- Keep category names short (1-2 words)
- Use clear, distinct names
- Don't create too many (6-10 is ideal)
- Group related habits together
- Examples:
  - ✅ "Strength Training"
  - ✅ "Cardio"
  - ❌ "Strength Training and Weightlifting Activities"

### Managing Habits (Full CRUD)

#### **VIEW ALL HABITS**
- Scroll to "Edit Habits" section
- All habits listed with their names and categories

#### **EDIT HABIT NAME**
- Tap in the name field
- Type new name
- Changes save automatically
- Updates everywhere (calendar, checklist, etc.)

#### **EDIT HABIT CATEGORY**
- Tap the dropdown below the habit name
- Select new category:
  - Climbing
  - Fitness
  - Recreation
  - Grooming
  - Nutrition
  - Supplements
- Category tag updates throughout app

#### **DELETE A HABIT**
- Tap "Delete" button next to any habit
- Confirm deletion
- **WARNING**: This removes the habit from ALL dates in your history
- Historical data for that habit is lost

#### **ADD NEW HABIT**
- Tap "+ Add New Habit" button at bottom of habit list
- A new habit appears named "New Habit"
- Edit the name and category
- It will now appear in your daily checklist

### Managing Schedule (Full CRUD)

#### **SELECT DAY**
- Use the dropdown at top to choose which day to edit:
  - Monday through Sunday

#### **VIEW SCHEDULE**
- All scheduled items for that day appear
- Shows time and activity name

#### **EDIT TIME**
- Tap in the time field (left box)
- Type new time (e.g., "5:30 AM", "2:00 PM")
- Saves automatically

#### **EDIT ACTIVITY**
- Tap in the activity field (middle box)
- Type new activity description
- Saves automatically

#### **DELETE SCHEDULE ITEM**
- Tap "X" button on the right
- Item is immediately removed
- No confirmation prompt

#### **ADD SCHEDULE ITEM**
- Tap "+ Add Schedule Item" at bottom
- New item appears with default time "12:00 PM"
- Edit time and activity as needed

### Data Management Operations

#### **VIEW ALL DATA**
1. Tap "View Data" button
2. See all stored data in JSON format:
   - All habit completions
   - All notes
   - Custom habits
   - Custom schedule
   - Everything stored on your iPhone
3. Useful for verifying data or debugging
4. Tap "Close" to return

#### **EXPORT DATA (Backup)**
1. Tap "Export Data" button
2. A file named `habit-tracker-backup-[DATE].json` downloads
3. Options appear:
   - **Save to Files**: Saves to iCloud Drive or iPhone storage
   - **Share**: Send via AirDrop, email, Messages
   - **Copy**: Copy to clipboard
4. **HIGHLY RECOMMENDED**: Export weekly to prevent data loss

#### **IMPORT DATA (Restore)**
1. Tap "Import Data" button
2. File browser opens
3. Navigate to your backup `.json` file
4. Tap the file
5. Data is restored immediately
6. All previous data is OVERWRITTEN

#### **CLEAR ALL DATA**
1. Tap "Clear All Data" button
2. Confirmation dialog appears
3. Tap "Yes, Clear All" to confirm
4. **WARNING**: This deletes EVERYTHING:
   - All habit completions
   - All notes
   - All tracking history
5. Cannot be undone without a backup

---

## 📁 BACKUP STRATEGY (CRITICAL)

### Recommended Backup Schedule

**Weekly Exports:**
- Every Sunday after you finish tracking
- Creates weekly snapshots of progress

**Monthly Archives:**
- First day of each month
- Keep for long-term records

### How to Organize Backups

**On iCloud Drive:**
```
iCloud Drive/
  └── Habit Tracker Backups/
      ├── 2025-01/
      │   ├── habit-tracker-backup-2025-01-07.json
      │   ├── habit-tracker-backup-2025-01-14.json
      │   ├── habit-tracker-backup-2025-01-21.json
      │   └── habit-tracker-backup-2025-01-28.json
      └── 2025-02/
          └── [monthly backups]
```

### Quick Backup Process

1. Open habit tracker
2. Tap "Manage"
3. Tap "Export Data"
4. Tap "Save to Files"
5. Navigate to your backup folder
6. Tap "Save"
7. Tap "Done" to close settings

**Time required: 15 seconds**

---

## 🚨 TROUBLESHOOTING

### Problem: Data Disappeared

**Cause**: Safari website data was cleared

**Solution**:
1. Tap "Manage" → "Import Data"
2. Select your most recent backup file
3. All data will be restored

**Prevention**: Export data weekly!

### Problem: App Won't Open

**Solution**:
1. Open Safari manually
2. Go to your file location (Files app, email, etc.)
3. Tap the `habit-tracker.html` file
4. Re-add to home screen

### Problem: Changes Not Saving

**Solution**:
1. Make sure you're using Safari (not Chrome or other browsers)
2. Check iPhone storage isn't full (Settings → General → iPhone Storage)
3. Try closing and reopening the app

### Problem: Can't Find Backup File

**Solution**:
1. Open Files app
2. Tap "Browse" at bottom
3. Search for "habit-tracker-backup"
4. Check Downloads folder and iCloud Drive

### Problem: Export Button Not Working

**Solution**:
1. Tap "Manage" → "View Data" first to verify data exists
2. If data exists but export fails, screenshot the JSON data
3. Close app and try again
4. Worst case: manually copy data from "View Data" screen

---

## 💡 TIPS & BEST PRACTICES

### Daily Workflow

**Morning (before 7:00 AM):**
1. Open app
2. Check "Overdue" section - catch up on anything missed
3. Check "Up Next" - see what's coming (dead hang, workout, breakfast)
4. Quick tap checkboxes as you complete each activity
5. OR switch to "Time Schedule" view for full day overview

**Throughout Work Day:**
- Quick open during breaks to check off meals
- Glance at "Up Next" to see what's coming
- Add notes about energy levels or performance

**Evening (after 6:00 PM):**
- Check "Overdue" for anything you forgot
- Check off evening activities as you do them
- Use quick checkboxes in overview OR detailed habit list
- Add notes about grooming, golf, etc.
- Review completion dots on calendar

**Before Bed (9:30 PM):**
- Final check: did you get everything?
- If not, decide if you'll do it or skip it
- Add any forgotten notes
- Tomorrow: app automatically shows new schedule

### Notes Tips

**Good Notes Examples:**
- "Deadlift 225x8, felt strong"
- "Meal 2: ate at 12:00, very hungry"
- "Climbed V4 route, grip improving"
- "Chest/stomach manscaping, 20 minutes"
- "Golf sim: worked on driver, 280 yards avg"

**What to Track:**
- Workout performance (weight, reps, energy)
- Meal timing (when you ate, hunger levels)
- Grooming notes (which areas, how long)
- Energy levels (1-10 scale)
- Sleep quality (if it affected morning)

### Customization

**Adapt to Your Needs:**
- Week 1: Follow schedule exactly as written
- Week 2-4: Note patterns and what works/doesn't work
- Month 2: Edit schedule times based on real experience
- Ongoing: Add/remove habits as needed

**Don't Overthink It:**
- It's okay to miss habits sometimes
- The goal is progress, not perfection
- Use the data to improve, not judge yourself

---

## 🔒 PRIVACY & SECURITY

### Your Data is Private

- ✅ Stored ONLY on your iPhone
- ✅ NOT sent to any servers
- ✅ NOT accessible to anyone else
- ✅ NOT tracked or monitored
- ✅ Works completely offline

### Who Can See Your Data

- **Only you** (the iPhone owner)
- Nobody else unless you:
  - Let someone use your unlocked iPhone
  - Share your backup file with them
  - Export and send data to someone

### Protecting Sensitive Information

Since you're tracking personal grooming and body habits:

1. **Use iPhone passcode/Face ID** (Settings → Face ID & Passcode)
2. **Don't share backup files** publicly
3. **Be careful with screenshots** (contain your data)
4. **Name the home screen icon** something generic ("Tracker" not "Manscaping Log")

---

## 📞 REFERENCE QUICK GUIDE

### Daily Actions
- **Track habits**: Tap date → Check boxes → Add notes
- **View schedule**: Tap date → Tap "Time Schedule"
- **Check progress**: Look at calendar dots

### Weekly Actions
- **Export backup**: Manage → Export Data
- **Review week**: Look at completion patterns

### Monthly Actions
- **Archive backup**: Save to dated folder
- **Review stats**: Check month completion %
- **Adjust schedule**: Manage → Edit Schedule (if needed)

### As Needed Actions
- **Add category**: Manage → Manage Categories → + Add New Category
- **Edit category**: Manage → Manage Categories → Tap name field
- **Delete category**: Manage → Manage Categories → Delete button
- **Add habit**: Manage → Edit Habits → + Add New Habit
- **Edit schedule**: Manage → Edit Schedule → Select day
- **Restore data**: Manage → Import Data → Select backup file

---

## ✨ ADVANCED FEATURES

### Customizing Your Tracker

**Categories:**
- Start with 6 default categories
- Add custom categories for your needs
- Example: Add "Mental Health" for meditation, journaling
- Example: Add "Social" for relationship habits
- Rename existing categories to match your terminology
- Delete unused categories

**Habits:**
- 18 default habits included
- Add unlimited custom habits
- Examples:
  - "Meditation 10 minutes"
  - "Read 30 pages"
  - "Journal entry"
  - "Call family member"
  - "Practice instrument"

**Schedule:**
- Fully customizable for each day
- Add/remove/edit any time slot
- Example custom additions:
  - "7:30 AM - Meditation"
  - "9:00 PM - Journal reflection"
  - "10:00 AM - Break/Stretch"

### Multi-Device Usage (Requires Manual Sync)

Since data doesn't auto-sync between devices:

**Setup:**
1. Install tracker on multiple devices (iPhone, iPad, etc.)
2. Use same file on each device

**Syncing:**
1. Export from Device A
2. AirDrop to Device B
3. Import on Device B

**Recommended**: Pick one primary device (your iPhone) for daily tracking

### Long-term Data Analysis

After 3+ months:
1. Export all data
2. Open in text editor on computer
3. Search for patterns:
   - Days with highest completion
   - Which habits you skip most
   - Energy level correlations
   - Best performing workout days

### Integration with Other Apps

The tracker works standalone, but you can complement it with:
- **Apple Health**: Manual entry of workouts
- **MyFitnessPal**: Detailed nutrition tracking
- **Strong**: Detailed workout logging
- **Habit tracker**: Use this as your master dashboard

---

## 🎯 SUCCESS METRICS

### Track Your Progress

**Daily:**
- Did I complete 70%+ of habits? (Good day)
- Did I add helpful notes?

**Weekly:**  
- Current streak (shown in stats bar)
- Week completion percentage

**Monthly:**
- Month completion % (shown in stats bar)
- Compare to previous months
- Identify patterns and optimize

### Celebrate Wins

- **7-day streak**: You're building consistency!
- **80% month completion**: Excellent discipline
- **90+ total habits**: Strong momentum
- **3 months of data**: You have real insights now

---

## 📧 FINAL NOTES

This tracker is designed to be:
- **Simple**: No complicated setup
- **Private**: Your data, your device
- **Offline**: Works everywhere
- **Flexible**: Customize to your needs
- **Permanent**: Your data stays as long as you back it up

**Remember**: The tracker is a tool, not a judge. Use it to improve your habits, not to stress about perfection.

**Most Important**: Export backups regularly. Data can't be recovered if lost.

Good luck with your habit tracking journey!
