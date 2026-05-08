# 🌿 Sunday Reset

A personal weekly reset tool built to make healthy habits effortless and friction the default for everything else.

---

## What this is

A Sunday checklist designed around one principle: **make the right things easy, make the wrong things harder.**

Work through it once a week — meal prep done, fridge organised, environment set up, gym planned, and mindset ready. Start Monday with zero decisions to make.

---

## What it covers

| Phase | Focus | Time |
|---|---|---|
| 🍳 Kitchen prep | Batch cook meals and snacks for the week | ~35 mins |
| 🥗 Fridge setup | Portion, label and organise for grab-and-go | ~15 mins |
| 🚫 Remove friction | Make unplanned eating harder to act on | ~10 mins |
| 👟 Gym & movement | Remove every barrier to training and walking | ~5 mins |
| 🧠 Mind & week | Review, plan ahead, set intention | ~10 mins |

---

## The habit logic

Built around four evidence-based principles:

1. **Habit stacking** — attaching new behaviours to existing cues
2. **Temptation bundling** — pairing enjoyable things with habits being built
3. **Environment design** — making the right choice the path of least resistance
4. **Decision reduction** — every decision made on Sunday is one less made under pressure during the week

---

## Tech

Plain HTML, CSS and vanilla JavaScript. No frameworks, no dependencies, no accounts required. Runs in any browser and works offline once loaded.

State is persisted to `localStorage` — checklist progress saves for the current day, custom recipes save permanently.

---

## Live

🔗 [morgifable.github.io/sunday-reset](https://morgifable.github.io/sunday-reset)

---

## Changelog

### v3.0 — May 2026
**Fully dynamic weekly setup flow**
- App now opens with a setup screen every Sunday — choose your breakfast for the week and toggle each checklist item on or off before starting
- Breakfast selection is reactive: choosing a breakfast auto-adds its prep task to the checklist and shows only that recipe in the Breakfast tab
- Checklist is built dynamically from your selections — only the tasks you actually need appear, with an accurate time estimate
- Progress ring and motivational messages update based on the dynamic task count

**Custom recipe builder**
- Add your own breakfast recipes via a form in the Breakfast tab (name, protein, calories, ingredients, method)
- Add your own snack ideas via a form in the Snacks tab
- Custom recipes appear as options in the weekly breakfast picker
- Delete any custom recipe with the ✕ button
- All custom recipes persist permanently in localStorage

**Persistent state improvements**
- Checklist state (completed tasks, breakfast choice, active task list) saves to localStorage and restores on the same day
- Custom recipes survive page refreshes and browser closes
- "Reset for next Sunday" clears the week's state and returns to the setup screen

---

### v2.0 — May 2026
**Tabbed layout**
- Split into three tabs: Reset (checklist), Breakfast (recipes), Snacks (recipes)
- Breakfast tab shows only the selected breakfast for the week
- Snacks tab shows all available snack options with full recipes

**Content updates**
- Replaced turkey mince with chicken breast as anchor protein throughout
- Removed smoked salmon scramble and chicken feta frittata breakfast options
- Updated shakshuka to use weekly meal prep chicken — no separate protein needed
- Removed cottage cheese & raspberry bowl and protein shake from snacks
- Calorie target updated to 1,600–1,800 kcal range (target 1,700) with ±100 buffer
- Protein target updated to 125–145g range (target 135g)

---

### v1.0 — May 2026
**Initial release**
- Static Sunday checklist across 5 phases: kitchen prep, fridge setup, remove friction, gym & movement, mind & week
- Progress ring tracking 28 tasks
- Celebratory completion state
- localStorage persistence for same-day state
- Summary footer showing weekly wins

---

## To update

1. Fetch `https://morgifable.github.io/sunday-reset/` and request changes
2. Replace `index.html` content in the repo
3. Commit — live within ~60 seconds
