## 🧠 Reaserch Overview
This study looks at how men and women consume music differently and how this can affect music recommendation systems
(like what Spotify or YouTube suggests to you). It uses a huge music dataset called LFM-1b, which contains over 1 billion music listening events.

---

## 🔍 Main Goals of the Study
  - Understand how gender affects music listening behavior.
  - Test if current music recommendation systems (like collaborative filtering) treat genders differently.
  - Explore whether the recommendations are biased or fair.
  - Make artist recommendations separately for male and female listeners and compare the results.

---

## 📦 Dataset Used: LFM-1b
  - Source Last.fm (a music streaming platform).
  - Covers 120,000+ users with details like gender, age, country, music preferences.
  - Over 1 billion listening records from Jan 2013 – Aug 2014.
  
  Contains:
  - Artist and track metadata
  - User-artist listening counts
  - Time (when the music was played)
  - User profiles (gender, age, etc.)

⚙️ Methodology
 ## 1. Feature Analysis: Used machine learning models (like Random Forest, Logistic Regression) to predict gender based on listening habits.
       Found that men tend to:
       - Listen to more unique tracks
       - Repeat songs from favorite artists more
       Women tend to:
       - Explore a broader range of artists
       - Be slightly more engaged with artists
 ## 2. Temporal Patterns
      - People listen less during weekends, but those who do, listen a lot (especially on Sundays).
      - Both genders showed similar listening patterns by time of day (peaking in the evening).
      - Men and women had different listening routines across the week.
## 3. Music Preferences
     - Both genders showed a strong interest in novel music (less mainstream).
     - No major difference in listening to popular (mainstream) music.

---

## 🎧 Gender-Based Artist Recommendation
    Used collaborative filtering to recommend top 10 artists to:
    - Female users
    - Male users
    - All users

Findings:
    - Males and females had very different top 10 recommended artists.
    - The overall system favored male users’ preferences because there was more data about them.
    - This showed a clear bias: systems trained on male-heavy data tend to ignore female preferences.

---
 
## 📊 Performance Results
    - Male users had higher precision and recall (better recommendations).
    - Female users got less accurate suggestions, highlighting a data imbalance problem.

---

##📌 Key Takeaways
   - Gender significantly influences music listening behavior.
   - Current recommendation systems can be biased if the dataset isn't balanced.
   - More female data or gender-aware models are needed to make recommendations fair and personalized.
---

## 🔮 Future Work Suggestions
  - Use model-based filtering (e.g., matrix factorization, neural networks).
  - Try hybrid models (combine different recommendation strategies).
  - Compare with content-based

---
