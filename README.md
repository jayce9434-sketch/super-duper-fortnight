# My Singing Dogs — V2.1 Seasonal & Island Overhaul (November 2026)

A **full GitHub Pages update**, replacing the previous V2 package. All existing V2 save slots use the same `my-singing-dogs-v1` localStorage key and remain compatible: do not reset your game. The supplied ZIP has **98 root-level files**, no folders and no build/CDN dependencies.

## New in this update

- **Springpup (Plant Island)**: April **15–22** inclusive, and each **Friday 3:00 PM–11:00 PM** Eastern. Breed **Bitbit (Tech) + Copperleaf (Plant Triple)** during an active window for a **12%** seasonal result; normal incubation is 3 hours. Springpup performs an original blooming-lyre part in Plant Island's complete song.
- **Autumnpup (Wind Island)**: October **1–13** inclusive, and each **Friday 11:00 PM–Saturday 8:00 AM** Eastern. Breed **Ripplet (Water) + Stormcaller (Wind Triple)** for a **12%** seasonal result; normal incubation is 3 hours. Autumnpup contributes a pan-flute melody to Wind Island's song.
- **All seasonal Rare forms use the same special odds**: Springpup, Jinglepup, and Autumnpup each use a **15% conditional Rare-form roll without torches**, gaining **+2 percentage points per lit torch on that island** up to **35% with all 10 lit torches**. Jinglepup's Rare egg still takes 3h30m and the Rare Ice Mythical egg still takes 4h.
- **Distinct Island artwork**: original new snowy/glacial Ice stage and airy floating-island Wind stage rather than overlays on the Plant image. Both are local background files.
- **Redesigned Rare sprites**: 20 major Rare assets were replaced or substantially reworked with different wings, crystal bodies, rock armor, mechanical speakers, harp designs and unique silhouettes. In particular, Rare Copperleaf is now a full clockwork-and-windmill redesign instead of a floating crown badge. Rare Jinglepup correctly uses its unique royal-winter art.
- **Castle construction timers**: Upgrades first deduct coins, then build over **30m, 45m, 1h, 1h30m or 2h30m** depending on tier. The new capacity becomes active only after clicking **Claim finished castle**. Progress saves and continues offline; gem completion costs 1 gem per remaining hour rounded up.
- **Gem Boutique**: opens from the gem counter or Market, offering faster bakery batches, gem-lit Wishing Torches, castle completion, treat/coin packs, double coin output for 2h and a permanent island night-glow atmosphere. Costs and active effects appear in-game; normal gem-uses (eggs, wheel, tickets) remain intact.
- **Rookie Gem Rewards**: six one-time beginner milestones (levels **1–10 only**) for 35 total gems: reaching level 5, breeding three times, feeding five times, collecting two bakery batches, discovering five dogs, and finishing the first castle upgrade. The ability to claim closes after level 10. Existing advanced saves don't receive starter rewards retroactively.
- **64 collection entries** (previously 62), 24 named species (previously 22), 3 islands, two added seasonal instrument stems, Rare and Mythical mechanics intact.

### Quality and device caveats

All in-game menus, saving, building, and mobile layout were exercised in Chromium with real rendered test screenshots. Seasonal song stems were verified as playable Ogg/Vorbis files of the correct island duration. Actual iPad Safari, online GitHub Pages publishing, long-term offline service-worker behavior, and whether every visual result matches personal preferences still require an on-device review. New Ice/Wind scene artwork is a distinctly stylized illustration; it is not the same rendering pipeline as the original painted Plant scenery.

---

# My Singing Dogs — The Expansion (v2.0)

A self-contained, original music/collection browser game made to publish to GitHub Pages. The creator's icy dog image is the icon and their tan-and-white dog image guided the custom canine artwork. This version replaces and extends v1 without needing accounts or external services.

## Publishing

Extract **every file directly into the root** of a GitHub repository. In repository Settings → Pages, choose **Deploy from a branch**, branch **main**, folder **/(root)**. Open the resulting GitHub Pages URL. No npm, libraries, CDNs, servers or build processes required. Do not place the files in a nested subfolder. This package contains fewer than 100 files.

## Three independent musical islands

- **Plant Island:** Wind, Stone, Tech. The Green Overture, 2:17, eight original synchronized main-dog tracks.
- **Ice Island:** Wind, Stone, Cold. Aurora Nocturne, 2:40, eight main-dog tracks, plus an exclusive winter seasonal performance.
- **Wind Island:** Wind, Stone, Water. Cloudborne Symphony, 2:28, eight new instrumental/harmony tracks including strings, low bass, flute, harp, brass and choir. The 64-bar score includes changing entries, featured solos, sustained notes and rests.
- Three bonus types (mechanical dog and two prize-exclusive performers) have supplementary synchronized instrument tracks on every island. Musical Rares retain their normal species' part. In-game dog animations follow the corresponding timed note events. Original synthesized/sampled music, not copied MSM audio.

## New progression and economy

- Unlock **Ice Island for 25,000 coins**, **Wind Island for 65,000 coins**. Prior v1 saves retain access to Ice.
- Castle capacities grow **10 → 16 → 24 → 32 → 48 → 64** per island; large upgrades cost serious coins. Coins also fund breeding, bakery batches, bakery construction, Wishing Torches and their lighting, Vaults, Song Monuments, expensive Howltron shells, and optional gem exchange.
- Build up to **three bakeries per island** and produce treats in **10-minute, 30-minute, 60-minute or 2-hour** batches. Ovens keep working while away; collect completed batches before starting new ones.
- Upgrade Coin Vaults to raise income and storage and Song Monuments to raise experience. Sell placed dogs for coins; storage holds prizes earned while the castle was full.
- Each island has its own nursery egg. Common singles take 15m; doubles 45m; triples 1h 45m; Mythicals 3h. Rares can require longer. **Rare Ice Mythical = 4h; Rare Ice Seasonal = 3h 30m.** No egg incubation exceeds four hours. Speeding costs **one gem per remaining hour, rounded up**, at most 4 gems per egg.

## Rares, Mythicals, Seasonals, Howltrons

- Every base species has its own **Rare visual variant** with custom crystal-and-gold adornments and extra earnings; these variants appear as separate collection entries.
- Double + Triple has **exactly 5% base Mythical chance**. Rares roll separately with 4% base chance. There is **no guaranteed-pity timer**. Each lit Wishing Torch adds **1.5 percentage points** to both probabilities, up to 10 lit torches. Torches cost coins to build, cost 3,500 coins to light, and stay lit four hours.
- **Jinglepup** is Ice-exclusive, including Rare Jinglepup. Breed **Frostle (Cold) + Glacierhorn (triple)** during **December 15–30**, or weekly from **Thursday 11 PM to Friday 8 AM Eastern Time**, for a 12% seasonal breed chance. **All Rare seasonals use a 15% Rare-form roll, increased by 2 percentage points per lit Wishing Torch on that island (35% with all 10 lit), conditional on the 12% seasonal breed result.** Without torches, a Rare seasonal is 1.8% per eligible breeding attempt (12% × 15%); with 10 lit, it is 4.2% (12% × 35%).
- Build dormant **Howltron** and **Rare Howltron** shells using coins. Activate one by permanently consuming **one of each of that island's eight base dogs of matching rarity**, INCLUDING its Mythical. The winter seasonal, game-prize exclusives, and the mechanical Howltron itself are not required. Both have organ parts and strong coin production.
- The **Paw Spin Wheel** has one free daily spin and costs **2 gems** for further spins; **Scratch Tickets** have one free daily ticket and cost **5 gems** for further tries. Prizes include coins, gems, treats, Rares, and distinct **Luckypaw** and **Scratchpaw** dog species that can **only** be won from their respective games. Free uses reset at midnight in **America/New_York**. Scratch the card with touch/mouse to reveal the prize.

## Save compatibility and data

Progress automatically saves to the same browser-local storage slot as v1. An older v1 save is migrated into v2 (existing dogs, coins, gems, achievements and collections retained). You can export a JSON backup from Settings and import it elsewhere. Local browser storage can be cleared by the browser or user; backups are strongly recommended.

## Art and performance limitations

All character sprites are transparent WebP. Rare outfits include decorative crystal crown, sparkling halos and jeweled collars, beyond a tint. Wind scenery is an original custom variant with open-sky windmills and streaming air details. Existing performance mouth elements are retained in a compact atlas to stay below 100 files. The animations are note-driven image layers, **not professional skeletal/frame-by-frame lip animation**. Instrument tracks are sampled from a General MIDI soundfont, **not studio-recorded dog vocals**.

## Security / access

This was intended as a private gift for the creator and Mason. Publishing with GitHub Pages **does not provide actual two-person access control**. Anyone who discovers the URL may open the site. Do not mistake a private repository, hidden link, or JavaScript password for access restriction. For genuine exclusivity, use hosting that supports authenticated authorization.

## Testing

Tested using Playwright with real Chromium rendering of the delivered HTML/CSS/JS and local assets intercepted through a local virtual host (this environment blocks direct navigation). Tests cover loading the app, new panels, species graphics and menus. More thorough scripted gameplay tests are included in the delivery screenshots. Live GitHub Pages deployment, service-worker installation on a real device, and physical iPad Safari were **not** verified here; no claim of flawless operation is made.


## V2 touch controls + starter gems patch
- New save files begin with **30 gems** instead of 18. Existing saves keep their earned/spent gems unchanged.
- Browser UI uses `touch-action: manipulation` to prevent double-tap zoom while retaining pinch zoom and scrolling.
- Game labels, dog art and buttons cannot be accidentally selected or invoke long-press copy/lookup menus on supported browsers. Text inputs remain editable.
- Special Rare seasonal breeding chance is **15%** base / **35%** with ten lit torches on that seasonal's island.
- Note: the iOS text-selection menu inside the ChatGPT app itself is outside the game's control.


## Illustrated Island Environment Repair
Ice and Wind environments now use detailed hand-painted artwork rather than stylized flat geometric graphics. Plant Island stays unchanged. Offline service worker cache identifier updated. No progression, save structure, prices, rarity odds, seasonal schedules, or audio changed.
