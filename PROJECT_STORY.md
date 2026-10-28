## Inspiration

I play basketball at school. I attend a boarding school, and when we closed for the holidays, we were expected to go home and keep training so we could come back ready for next year's season competitions.

But when I got home, I faced a problem: there was no basketball court near me where I could train. The courts I could find were either very far away or I had to pay to use them, which can be costly. So I had the talent and the motivation, but nowhere to practise.

That experience made me think bigger. If this was happening to me, it is happening to many talented children and students. Some have no facility nearby. Others are training hard, but no scout will ever see them, because scouts mostly attend big tournaments and well-known schools. Their talent goes to waste — not because they are not good enough, but because nobody saw them.

So I created **TalantaLink**: a platform where talented students can be discovered by scouts, scouts can find talented students, and everyone can find the nearest place to train.

## What it does

**TalantaLink** ("Talanta" is Swahili for *talent*) connects three groups in one website:

- **Talented students** create an athlete profile — their sport, position, achievements, where they train, and their story — and apply to trials and scouting opportunities so scouts can discover them.
- **Scouts** search the Talent Directory by sport, position, age and area, review student profiles, and invite shortlisted students directly. Verified scouts are clearly badged so students can tell who is genuine.
- **Everyone** can use the Facility Finder to locate their nearest basketball court, football pitch, athletics track or training hall — showing distance, price (including free facilities), available amenities and best training times.
- **Coaches and academies** can post trials and opportunities, and the **My Journey dashboard** helps each user track their applications, saved opportunities, scout connections and profile status.

## How I built it

I built TalantaLink as a fast, mobile-first single-page web application using **HTML, CSS and vanilla JavaScript**. Listings, student profiles, scouts and facilities are rendered dynamically, with live search and filtering by sport and location. Applications, saved opportunities and profiles are stored using **localStorage**, so a user's journey is remembered on their device without needing an account.

I deliberately designed it with no login wall and a simple interface, because many young athletes use low-cost phones and limited data. The core flow I focused on is: **showcase your talent → get discovered by a scout → find a place to train → show up and shine.**

## Challenges I faced

- **Narrowing the idea:** I started with many sports problems, but I learned a hackathon project must solve one clear problem well. I narrowed it down to the student–scout–facility connection.
- **Trust and safety:** Young athletes can be targeted by fake "scouts." I addressed this with verified-scout badges, clearly marked community listings, and keeping contact inside the platform.
- **Facilities information:** Knowing a facility exists is not enough — people need distance, cost and training times. I designed the finder to sort by nearest first and show prices clearly, including free options for students who cannot pay.
- **Designing for real users:** Everything had to work in a few taps on a small phone screen, not just on a laptop.

## What I learned

I learned that talent is everywhere, but visibility is not. Technology cannot give someone talent — but it can make sure talent is seen, and that a student knows where to go and train. I also learned how to turn a personal frustration into a product: define the problem, choose the users, build the smallest useful version, and keep improving it based on the real experience of the people it is for.

## What's next for TalantaLink

- Onboard **real verified scouts, coaches, academies and facilities**, starting with school sports programs
- Add **video highlights** to student profiles so scouts can watch before inviting
- **SMS/WhatsApp notifications** for trial invitations and reminders
- Stronger **child-safety features**: verified accounts, parental consent and school endorsements
- A scout dashboard for managing shortlists and giving feedback to every applicant — so no student is left without an answer
