# TalantaLink — Devpost Submission Pack (v3)

## Project name
**TalantaLink**

## Tagline
Don't let talent go unseen. — Talented students showcase their ability, scouts discover the next generation, and everyone finds their nearest place to train.

## Elevator pitch (30 seconds)
> "Every year, talented children and students across Kenya quit sports — not because they lack ability, but because no scout ever saw them play. Scouts can only watch famous schools and big tournaments, so ability without connections goes to waste. TalantaLink fixes both sides: students create athlete profiles and apply to trials, scouts search talented students by sport, position and county and invite them directly — and everyone can find the nearest court, pitch or track to train at. No talent should go unseen."

## Full Devpost description (copy-paste ready)

### 💡 Inspiration
Scouts discover players at big tournaments and well-known schools. A gifted student anywhere else — however talented — is invisible, and their talent quietly goes to waste. At the same time, many young athletes don't even know where the nearest proper training facility is. We built TalantaLink so discovery is based on talent, not connections.

### 🏀 What it does
- **Talented students** create a public athlete profile (sport, position, achievements, where they train, their story) and apply to trials and scouting opportunities.
- **Scouts** search the Talent Directory by sport, position, age and county, review profiles, and invite shortlisted students directly. Verified scouts are badged so students know who is real.
- **Meet the Scouts** shows which verified scouts are currently looking for what (e.g. "U14–U18 guards", "girls 13–19, all positions"), and students submit their profiles to them.
- **Facility finder** shows the nearest basketball courts, football pitches, athletics tracks and halls — with prices, facilities, training times and distance from you.
- **Coaches/academies** post trials and opportunities in minutes.
- **My Journey dashboard** tracks applications, saved opportunities, scout connections and profile status (saved on-device).

### 🛠️ How we built it
A fast, mobile-first single-page web app (HTML, CSS, vanilla JavaScript) with dynamic search/filtering, profile creation, scout invitations, a nearest-facility finder, and localStorage persistence. No login wall; designed for low-cost Android phones.

### 🚧 Challenges
- Trust: fake "scouts" scam young athletes — solved in design with verified-scout badges and coach-confirmed listings.
- Designing for first-time internet users: everything in a few taps.
- Scope: cut accounts/payments from the MVP to perfect the core loop — showcase → get scouted → train → shine.

### 🏆 Accomplishments
- Full working loop in one demo: create a profile → get invited by a scout → apply to a trial → find a facility → track it all in My Journey.
- A two-sided marketplace: students find scouts AND scouts find students.
- A nearest-facility finder that sorts training venues by distance.

### 📚 What we learned
Sports discovery runs on "who you know" and "where you were seen." The real product is visibility: structured, searchable talent profiles + verified scouts + nearby facilities.

### 🔮 What's next
- Video highlights on profiles; scout review dashboards and shortlists
- SMS/WhatsApp invitations and trial reminders
- Safeguarding & parental consent flows for minors; partnerships with school games associations and federations
- Facility booking and coach-verified attendance

## 🎬 2-minute demo script
1. **(0:00) Hook:** "This is a talented student no scout has ever seen. In most of Kenya, her talent would go to waste. Watch this."
2. **(0:15) Student:** Create a player profile live (name, position, achievement, story).
3. **(0:40) Scout view:** Open the Talent Directory — filter Basketball + her county — her profile is there. Click "Invite to trial."
4. **(1:00) Meet the Scouts:** Submit her profile to a verified scout looking for her exact position.
5. **(1:20) Facilities:** Pick her location in the facility finder — nearest court appears first, with distance and price.
6. **(1:40) My Journey:** Show application + scout connection tracked.
7. **(1:50) Close:** "Talent is everywhere. Now scouts can see it. That's TalantaLink — don't let talent go unseen."

## ❓ Judge Q&A
- **Different from Facebook groups?** Searchable by sport/position/county, structured profiles, verified scouts — groups are none of these, and they expose children to scams.
- **How do scouts trust profiles?** Profiles are a shortlist tool, not a contract: scouts invite to trials and verify in person. Next phase adds coach/school endorsements and video.
- **Child safety?** Verified scouts, no public phone numbers for minors, parental consent in roadmap, invitations through the platform.
- **Revenue?** Premium scout/academy accounts, featured trials, federation & county partnerships. Free forever for students.
- **Why will scouts join?** One searchable pool of talent beats driving to 20 school tournaments. Free to start.

## ✅ Submission checklist
- [ ] Replace demo data with 3–5 REAL scouts/coaches/academies who agreed to be listed
- [ ] Record 2-min demo video (script above)
- [ ] Screenshots: Talent Directory, Meet the Scouts, Facility Finder
- [ ] Team names & roles on Devpost
- [ ] Test live link on a phone
