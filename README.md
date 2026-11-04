# Dishlog

A food-memory and discovery app for urban diners in India. This repo holds a clickable, mobile-first prototype.

**Core loop:** Discover → Save → Try → Log → Remember → Recommend

## Run it

It's a single static page with no build step and no dependencies.

- Open `index.html` in a browser, or
- serve the folder (`npx serve .` or `python3 -m http.server`) and open it on your phone.

Data is sample data, stored only in your browser (localStorage). Use **Profile → Reset sample data** to start over.

## What's in it

- **Diary:** photo grid, a timeline with a month calendar, and a map of your food spots
- **Log a dish:** in under a minute, with reaction, note, friends, and visibility per memory (Only me / Friends / Everyone)
- **Revisits:** a repeat visit never overwrites earlier ones
- **Discover:** a feed from friends, Explore, and follow requests
- **Saved:** want to try, then tried, plus collections
- **Game layer:** XP and levels, weekly streaks, badges, food passport, weekly quests, friends league
- **Privacy:** private or public profile, bulk visibility, preview as a friend or a stranger, export, delete

## Screenshots

Taken from the live prototype on a phone-sized screen, using the built-in sample data.

<p align="center"><img src="screenshots/01-landing.png" width="260" alt="Dishlog landing screen: Remember every dish. Discover what to try next."></p>

### Diary: photos, timeline and map

Every dish you've logged, as a photo grid, a month calendar, or a map of your food spots. "On this day" brings back an old memory.

<p align="center">
<img src="screenshots/02-diary-photos.png" width="260" alt="Diary photo grid with an On this day memory">
<img src="screenshots/05-timeline-calendar.png" width="260" alt="Timeline month calendar">
<img src="screenshots/06-map.png" width="260" alt="Map of food spots">
</p>

### Log a dish in under a minute

Only three things are required: the dish, the spot and how it was. Three one-tap reactions replace 5-star ratings.

<p align="center">
<img src="screenshots/03-log-a-dish.png" width="260" alt="New memory screen with photo, dish and food spot">
<img src="screenshots/07-three-reactions.png" width="260" alt="Three reactions: Loved it, It was fine, Not for me">
</p>

### Revisits never overwrite

"Had it again?" adds a new visit, and every earlier visit is kept in the dish's history.

<p align="center"><img src="screenshots/04-revisits-history.png" width="260" alt="Dish history showing visit 3 of a dish"></p>

### Privacy per memory

Memories are private by default. You choose who sees each one, set a default, change many at once, and preview your profile as a friend or a stranger.

<p align="center">
<img src="screenshots/12-visibility-per-memory.png" width="260" alt="Who can see this memory: Only me, Friends, Everyone">
<img src="screenshots/11-privacy-controls.png" width="260" alt="Privacy settings in the profile">
</p>

### Discover and Saved: from a friend's tip to a real meal

See what friends shared, save it as "Want to try", then tap "I tried it" to log it.

<p align="center">
<img src="screenshots/10-discover-feed.png" width="260" alt="A friend's post in Discover with a Want to try button">
<img src="screenshots/08-saved-to-tried.png" width="260" alt="Saved list with I tried it buttons and friend attribution">
</p>

### A quiet game layer

One level card on the Diary, with a weekly (not daily) streak. Badges, quests and the league are one tap away.

<p align="center"><img src="screenshots/09-level-card.png" width="260" alt="Level card with XP and a 3-week streak"></p>

## Files

- `index.html`: the whole app (HTML, CSS, JS)
- `img/mango.svg`, `img/jalebi.svg`: splash illustrations
- `food-art.js`: source for the dish illustrations (already inlined in `index.html`)
- `screenshots/`: images used in this README
