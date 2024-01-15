# spotify-song-duration-analysis

Research has shown that the average duration of mainstream songs has decreased over the years. In 2020, the average duration was 197 seconds or 3.2 minutes.

Why are mainstreams songs getting shorter? Is there possibly an economic incentive to create songs that are universally shorter in duration?

Online streaming platforms, like Spotify, generate their revenue from the amount of streams that a song accumulates indicating that there might be a positive relationship between duration and streams, and thus revenue.

Using a dataset acquired from Kaggle, this study aims to study that hypothesis.

---

**Data Source:**  Kaggle

Dataset encompasses songs released between 1986 and 2023 that are accessible on Spotify.

Data collection involves utilizing a function to send requests to Spotify’s API, retrieving various attributes, and storing them in an Excel file.

The dataset comprises over **34 variables**, which include **22 numerical variables related to characteristics** and **12 categorical variables** for artists, genre, and album type, among others. These variables fall into four types: float, integral, strings, and booleans.

![image](https://github.com/rsoetirto/spotify-song-duration-analysis/assets/109045573/7bf9f499-1ac9-4a91-81b5-f4012f6741ce)
![image](https://github.com/rsoetirto/spotify-song-duration-analysis/assets/109045573/917a0ed5-d5d2-4fef-b43c-44791d0f56d0)

---

**Analysis**

Average duration across the years (1986-2023) per the dataset

<img width="843" alt="Screenshot 2024-01-15 at 1 15 39 AM" src="https://github.com/rsoetirto/spotify-song-duration-analysis/assets/109045573/bfe26eab-4f13-4a51-8721-e04efc3fbcdf">


1. Correlation Analysis / Correlation Heatmap 
<img width="645" alt="Screenshot 2024-01-15 at 12 51 42 AM" src="https://github.com/rsoetirto/spotify-song-duration-analysis/assets/109045573/3260d4fb-99fd-4904-98a0-33bb49bc7b1b">

2. Simple Regression
<img width="861" alt="Screenshot 2024-01-15 at 12 51 32 AM" src="https://github.com/rsoetirto/spotify-song-duration-analysis/assets/109045573/79dc0640-288f-4bd4-a465-3f69adf80e43">

3. PCA Analysis
<img width="694" alt="Screenshot 2024-01-15 at 1 20 50 AM" src="https://github.com/rsoetirto/spotify-song-duration-analysis/assets/109045573/c78d0a4c-ddd5-4e60-a4c9-7a8c064e207a">


4. Multiple Regression
<img width="612" alt="Screenshot 2024-01-15 at 1 18 39 AM" src="https://github.com/rsoetirto/spotify-song-duration-analysis/assets/109045573/23aca931-0a05-4151-9d34-3f596487ef6b">

5. Time Series 
<img width="624" alt="Screenshot 2024-01-15 at 1 19 55 AM" src="https://github.com/rsoetirto/spotify-song-duration-analysis/assets/109045573/c227d12b-a8e3-4164-b4d0-01601b272d04">

---

**Conclusion**
This study's findings show that quantitative models may not capture a strong relationship between duration and amount of streams/popularity. This indicates that the descreasing trend in song duration might be influenced more by qualitative factors aside from streams alone.


   


