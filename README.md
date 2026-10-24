# 再次重逢的初恋 · Where we left off

Static interactive fiction. Root `index.html` and user-supplied `assets/dohoon.jpg`; deploy to Vercel as Other/static, with no build command, dependencies or API keys.

## Story
Eight stages span about six fictional weeks: reunion, apology, program broadcast, old keychain, fulfilled promises and a serious call, confession/time to consider/mutual reconciliation, new bracelet, and jointly handling speculation. Dates advance through player actions. Messages arrive individually; important responses are gated until replies finish.

Mom keeps the school-era gift. oo is a college friend who learns about the former relationship only when told. Both have optional multi-turn topics and free text. Mom's shipment and the serious call gate their corresponding scenes.

## Social play
- X starts private; Instagram starts public. Local profiles, photo/text posts, per-post audiences, likes, comments/replies, hiding and deletion are supported.
- 40 fictional world posts: 10 program, 10 later distracted/on-phone behavior, 12 matching-item speculation and 8 everyday posts. Threads contain 6–12 readable comments plus expandable replies.
- Discovery requires confirmed reconciliation, later fictional public footage and a still-public bracelet-visible photo. Self-only, friends-only, cropped photos and X private accounts cannot trigger it. Free text alone is never treated as evidence.
- The eligible Instagram photo receives a 25-comment simulated thread in a bottom drawer. Hiding/deleting stops further comparison posts but retains discussion already released.
- Two supplied TWS-related Instagram originals remain embedded with tracking parameters removed. Original text/media are loaded by Instagram and may be unavailable due to network/login/embed settings.

## Privacy and media
State stays in localStorage under `whereweleftoff.refined.1`. Refined story starts from reunion; the old `whereweleftoff.v2` key is not deleted. Name and previous local Instagram photos migrate, with migrated photos restricted to self-only. Photos are resized locally and never uploaded to GitHub, Vercel or real social networks.

Unlock code: `0000`, without an onscreen hint. Settings can change the player name. Romance, programs, props, conversations, calls and simulated social content are fictional; no association with artists/agencies. Calls use a portrait/text simulation without live connections or camera/microphone capture. Story prop illustrations are SVG.

Seven Apple Music preview tracks include older K-pop and TWS's plot twist, hey! hey!, Last Festival. Previews normally last about 30 seconds; complete songs use official external links. No full recordings are hosted.

## Verification
Both response branches across all eight stages and audience/discovery gates pass bounded local checks. In-app browser QA covers unlock/name entry, live replies, mother/shipping topic, publishing, comment submission/expansion/likes, audience changes, music controls and 320/390px plus desktop portrait sizing. Safari hardware, the real image picker and external Instagram rendering are not fully verified.