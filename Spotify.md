# B2C Case Study: Humanizing Music Discovery with Spotify "Orbit"

**Role:** Product Manager  
**Product Focus:** Music Discovery & Social Engagement  
**Platform:** Mobile App (iOS/Android)  

---

## 1. Executive Summary

**The Problem:** While Spotify’s algorithmic playlists (like Discover Weekly) are highly effective, many users experience "algorithmic fatigue." They feel stuck in a feedback loop of the same genres and miss the organic, human element of discovering music through friends or tastemakers.

**The Goal:** Increase user engagement, daily session length, and the discovery of long-tail artists by introducing a human-curated, social discovery mechanism.

**The Solution:** "Spotify Orbit" — A feature that anonymously matches users with "Music Twins" globally (users with >90% overlap in listening habits) and allows them to explore their twins' current heavy rotation and saved tracks.

---

## 2. User Personas & Pain Points

| Persona | Demographics | Primary Pain Point | Core Need |
| :--- | :--- | :--- | :--- |
| **"Stuck-in-a-Rut Ryan"** | 28, Millennial, Commuter | Skips through Discover Weekly because it feels repetitive. Defaults to his 5-year-old "Favorites" playlist. | Needs a fresh way to find music that feels trusted and exciting, not purely mathematical. |
| **"Tastemaker Tara"** | 21, Gen Z, College Student | Spends hours building niche playlists but feels they go unnoticed by her immediate friend group. | Needs an outlet to share her music taste with an audience that actually appreciates her specific vibe. |

**Key Research Insights (Hypothetical Data):**
* **58%** of users report listening to the exact same rotation of songs as they did 6 months ago.
* Playlists created by real users have a **3x higher save rate** than auto-generated mix playlists.
* Users frequently share screenshots of their listening stats to find common ground with others on platforms like X (Twitter) and TikTok.

---

## 3. Ideation & Brainstorming

To solve these pain points, three potential features were brainstormed:

1.  **Track Swipe ("Tinder for Music"):** A gamified discovery feed where users swipe right to save 15-second song previews to their library.
2.  **Spotify Orbit (Music Twins):** Anonymized global matchmaking that connects users with exact-match music tastes to share their current top tracks.
3.  **Local Geo-Drops:** An AR/Map feature allowing users to "drop" a song at a physical location (e.g., a coffee shop) for other nearby users to discover.

---

## 4. Prioritization Matrix (RICE Framework)

We used the RICE framework (Reach * Impact * Confidence / Effort) to evaluate these ideas and define our Minimum Viable Product (MVP).

| Feature | Reach | Impact | Confidence | Effort | RICE Score | Priority |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| **Track Swipe** | 8,000 | 3 | 70% (0.7) | 4 | 4,200 | #2 |
| **Spotify Orbit** | **6,000** | **4** | **80% (0.8)** | **3** | **6,400** | **#1 (Winner)** |
| **Local Geo-Drops**| 2,000 | 5 | 40% (0.4) | 5 | 800 | #3 |

**Decision:** We proceed with **Spotify Orbit**. It balances strong impact (leveraging human connection) with manageable effort (Spotify already possesses the backend data required for affinity matching via its taste profile systems). Local Geo-Drops is too high-effort for an MVP, and Track Swipe risks feeling too disconnected from Spotify's core UX.

---

## 5. The Solution: "Orbit" MVP

The MVP focuses on anonymity, curiosity, and frictionless discovery.

### Core User Stories
* *As a user, I want to be matched with someone who shares my exact niche music taste so I can see what they are listening to right now.*
* *As a user, I want the experience to be completely anonymous so I don't feel like my privacy is violated or that I'm entering a dating app.*
* *As a user, I want a one-tap button to save my Twin’s current heavy rotation as a playlist in my library.*

### Feature Walkthrough
1.  **The Match:** A new module appears on the Home feed: *"You have a Music Twin in Tokyo, Japan. You both listened to 45 hours of Shoegaze last month."*
2.  **The Orbit View:** Tapping the module opens a stylized, anonymous profile (e.g., "Twin #4092"). It displays their "On Repeat" tracks, recently created playlists, and top genres.
3.  **The Action:** Users can listen to previews, save individual tracks, or hit "Sync Twin Playlist" to automatically generate a dynamic playlist of their twin's favorites.

---

## 6. Go-to-Market (GTM) Strategy

* **Launch Timing:** Mid-year (July/August) to bridge the gap between major campaigns like Spotify Wrapped.
* **Growth Loop:** * *Trigger:* User discovers a new favorite band through their twin.
    * *Action:* User clicks "Share my Orbit Match," generating a visually striking graphic (similar to Wrapped) for Instagram Stories: *"My Spotify Twin in Brazil and I are keeping [Artist Name] in business."*
* **Marketing Channels:** Push notifications targeting users with declining engagement rates, and influencer partnerships focusing on the "Who is your music soulmate?" angle.

---

## 7. Success Metrics (KPIs)

We will track the success using the AARRR funnel:

| Funnel Stage | Metric | Goal |
| :--- | :--- | :--- |
| **Acquisition** | Feature Adoption Rate | 20% of Daily Active Users (DAU) click into their Orbit match in the first 30 days. |
| **Activation** | Track Save Rate | 30% of users who view a Twin's profile save at least one track to their library. |
| **Retention** | Orbit Return Rate | Users check their Orbit matches at least once a week. |
| **Business Impact** | Session Length Increase | Average session length increases by 5% for users who engage with Orbit. |

---

## 8. Risks & Mitigations

* **Risk:** Privacy concerns; users might feel "spied on" if their exact listening habits are shared with strangers.
    * **Mitigation:** Strict anonymity. No names, profile pictures, or exact locations (only country/city level). Users must actively opt-in to the Orbit ecosystem to participate.
* **Risk:** Poor matchmaking leading to irrelevant recommendations.
    * **Mitigation:** The matching algorithm will prioritize recent listening habits (last 30 days) over all-time listening history to ensure the current "vibe" matches.
