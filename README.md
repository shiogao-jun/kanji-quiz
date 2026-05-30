# kanji-quiz
While deepening my Japanese studies for my ultimate goal of moving to Tokyo, I faced a major roadblock with existing tools. Most available Kanji apps were either hidden behind expensive paywalls or limited to passive, inefficient flashcard memorization. Recognizing this gap, I designed and implemented my own interactive quiz system from scratch. 

By engineering a dynamic text-parsing algorithm that filters Onyomi (Kanji readings) and Kunyomi (native readings), I created a high-efficiency active-recall training environment tailored to my needs. This project reflects not only my technical initiative in building personalized educational software but also my relentless dedication and desperate earnestness to completely master the Japanese language for my future professional career.

#  Data Source & Structure

All Kanji data used in this project is sourced from the official Japanese educational curriculum guidelines.

* **Source:** [漢字辞典オンライン (Kanji Jiten Online)](https://kanji.jitenon.jp/cat/kyoiku)
* **Dataset:**
  * `G1_kanji.txt`: 1st Grade Elementary Kanji (80 characters)
  * `G2_kanji.txt`: 2nd Grade Elementary Kanji (160 characters)
  * `G3_kanji.txt`: 3nd Grade Elementary Kanji (200 characters)
* **Data Format:** The `.txt` files are parsed using a specific delimiter format.
  * `Kanji : Onyomi1, Onyomi2, Kunyomi1, Kunyomi2`
