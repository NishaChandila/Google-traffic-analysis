# Spotify History Analysis

## "Every album has a story—let’s uncover what makes them stand out on Spotify."

Music is more than just sound; it's an experience shaped by the way listeners engage with their favorite albums. In this project, we analyze key metrics like playtime, skips, and trends over time to uncover patterns that reveal how certain albums dominate the charts while others struggle to gain traction.

Through detailed analysis and visualization, we highlight not just what people are listening to, but how they interact with their music. Whether it's understanding peak listening periods, identifying albums with high skip rates, or spotting trends across years, this project provides valuable insights to enhance engagement and optimize album promotion.

- Spotify History [Dataset](https://github.com/NishaChandila/Spotify-History-Analysis/blob/main/spotify_history.csv)
- Spotify History [Dashboard](https://github.com/NishaChandila/Spotify-History-Analysis/blob/main/Spotify-History-Dashboard.pdf)

---

## Data Structure
To analyze Spotify’s top albums, we used several important data points that reveal listening behaviors and trends:

![Dataste Preview](https://github.com/NishaChandila/project-assets/blob/main/Spotify-History-Dataset.PNG)

- **album_name** – The name of the album being played.
- **artist_name** – The artist behind the album.
- **ms_played** – The total time (in milliseconds) a track was played, indicating engagement.
- **platform** – The device or application used to stream the music (e.g., Android, Web Player).
- **reason_end** – The reason a track stopped playing (e.g., track finished, skipped).
- **reason_start** – The reason a track started playing (e.g., user clicked, autoplay).
- **shuffle** – Indicates whether the song was played on shuffle mode.
- **skipped** – Shows whether a track was skipped before completion.
- **spotify_track_uri** – A unique identifier for each track.
- **track_name** – The specific song title within an album.
- **ts (timestamp)** – The exact date and time the track was played, which helps track trends over time.

These columns helped us uncover insights into listening habits, playtime trends, and album performance across different platforms.

- Spotify History [Dataset](https://github.com/NishaChandila/Spotify-History-Analysis/blob/main/spotify_history.csv)

---

## Executive Summary

![Home](https://github.com/NishaChandila/project-assets/blob/main/Spotify-History-Dashboard1.PNG)

### Album Insights:
- **The New Abnormal (35.02%)** and **The Beatles (35%)** lead in playtime share, with **Imploding the Mirage** at **29.99%**.
- **The Beatles** has the highest skips (**2,062**), followed by **Past Masters (1,672)** and **Abbey Road (1,429)**, suggesting varied listener retention.
- Playtime trends from **2016 to 2024** show peaks in **2020** for *Imploding the Mirage* (**119M**) and *The New Abnormal* (**121M**), highlighting their breakout moments.

![Album](https://github.com/NishaChandila/project-assets/blob/main/Spotify-History-Dashboard2.PNG)

### Artist Insights:
- **The Beatles** dominate with **1.21B ms** of playtime but also lead in skips (**14K**), showing strong engagement but some drop-offs.
- **The Killers (1.06B)** and **John Mayer (0.73B)** follow, both having a steady listener base.
- Yearly trends reveal shifting artist popularity, with *The Beatles* peaking in **2017 (243M)** and *The Killers* reaching their high in **2020 (360M)**.

![Artist](https://github.com/NishaChandila/project-assets/blob/main/Spotify-History-Dashboard3.PNG)

### Platform Insights:
- **Android** leads in total playtime (**96.01%**) and skips (**140K**), while **Web Player** has the lowest engagement (**25M playtime**).
- **Cast to Device** accounts for only **3.99%** of playtime, presenting an opportunity to improve cross-platform listening.
- **Shuffle play** is highest on **Android (140K)**, indicating a preference for randomized listening on mobile.

![Platform](https://github.com/NishaChandila/project-assets/blob/main/Spotify-History-Dashboard4.PNG)

These insights help understand listening behaviors, optimize album promotion, and enhance engagement across different platforms.

- Spotify History [Dashboard](https://github.com/NishaChandila/Spotify-History-Analysis/blob/main/Spotify-History-Dashboard.pdf)

---

## Recommendations

With **7,907 unique albums, 4,112 artists, and 6 platforms**, understanding playtime trends and skip behavior can help improve listener engagement. While *The New Abnormal* and *The Beatles* dominate playtime, high skip rates suggest areas for improvement. Similarly, *Android* leads in streaming, but other platforms remain underutilized. Here are five key recommendations:

- **Promote Underrated Albums** – *Imploding the Mirage* (**29.99% playtime**) lags behind *The New Abnormal* (**35.02%**) and *The Beatles* (**35%**). Featuring it in playlists or recommendations could boost engagement.
- **Reduce Skip Rates for Top Artists** – *The Beatles* lead in playtime (**1.21B ms**) but also in skips (**14K**). Highlighting listener favorites or reordering tracks in playlists may improve retention.
- **Leverage Peak Year Trends** – *The Killers* peaked in **2020 (360M)**, while *The Beatles* peaked in **2017 (243M)**. Revisiting past marketing strategies could reignite interest.
- **Optimize Web Player Engagement** – With just **25M playtime**, *Web Player* sees minimal usage. Enhancing its interface or offering exclusive features could increase desktop streams.
- **Encourage Cross-Platform Listening** – *Cast to Device* accounts for only **3.99%** of playtime. Improving multi-device syncing or promoting smart speaker integration could enhance user experience.

- Spotify History [Dataset](https://github.com/NishaChandila/Spotify-History-Analysis/blob/main/spotify_history.csv)
- Spotify History [Dashboard](https://github.com/NishaChandila/Spotify-History-Analysis/blob/main/Spotify-History-Dashboard.pdf)
