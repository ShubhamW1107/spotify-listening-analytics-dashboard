# spotify-listening-analytics-dashboard
1️⃣ Headline<br>
A dynamic and interactive Power BI dashboard built to analyze Spotify streaming history — focusing on listening behavior trends, artist engagement, track performance, time-based patterns, and year-over-year growth insights.<br>
2️⃣ Purpose<br>
The Spotify Listening Analytics Dashboard is a comprehensive Power BI report designed to monitor and analyze personal music streaming behavior.<br>
This dashboard enables users and analysts to track KPIs such as total listening hours, unique artists, top tracks, monthly trends, and engagement distribution to uncover meaningful behavioral insights from raw streaming data.<br>
3️⃣ Tech Stack<br>
The dashboard was built using the following tools and technologies:<br>
* 📊 Power BI Desktop – Main data visualization platform used for report creation.
* 📂 Power Query – Data transformation and cleaning layer for reshaping and preparing the Spotify streaming dataset.
* 🧠 DAX (Data Analysis Expressions) – Used for calculated measures, time intelligence, dynamic KPIs, and YoY growth calculations.
* 📝 Data Modeling – Structured single-table model enhanced with derived columns (Year, Month, Hour, Day Name) to enable advanced time-based analysis.<br>
* 📁 File Format – .pbix for development and .png for dashboard previews.<br>
4️⃣ Data Source<br>
Source: Spotify Streaming History (Personal Data Export – CSV format).<br>
The dataset consists of detailed listening records including:<br>
* Track Name – Name of the song played
* Artist Name – Performing artist
* Album Name – Album associated with the track
* Timestamp – Date and time of playback
* ms_played – Duration of playback in milliseconds
* Platform – Listening device/source (if available)
* Shuffle/Skipped Indicators – Listening behavior attributes<br>
The dataset was transformed to create derived fields such as:<br>
* Listening Minutes & Hours
* Year, Month, Day Name
* Hour of Listening
* Play Frequency per Track
* Year-over-Year Metrics<br>
The data model enables cross-analysis between time, artists, albums, and tracks to generate behavioral insights.<br>
5️⃣ Features<br>
* Business Problem<br>
Music streaming platforms generate large volumes of behavioral data. However:<br>
Manual analysis of listening history is inefficient<br>
Listening trends across time are difficult to identify<br>
Top contributing artists and albums are not easily visible<br>
Engagement depth cannot be measured without aggregation<br>
Year-over-year growth insights require structured modeling<br>
Raw streaming logs alone do not provide actionable insight.<br>
* Goal of the Dashboard<br>
To build an interactive business intelligence solution that:<br>
Provides centralized visibility into listening KPIs<br>
Identifies top-performing artists, albums, and tracks<br>
Tracks listening trends month-over-month and year-over-year<br>
Highlights peak listening hours and daily engagement<br>
Analyzes track frequency vs listening duration (quadrant analysis)<br>
Supports behavioral insight generation through visual storytelling<br>
* Walkthrough of Key Visuals<br>
🔹 Key KPIs (Overview Dashboard)<br>
Total Streams<br>
Total Listening Time (Hours)<br>
Unique Artists<br>
Unique Tracks<br>
Average Listening Duration<br>
Year-over-Year Growth (%)<br>
Provides a high-level summary of overall streaming behavior.<br>
🔹 Time-Based Listening Analysis<br>
Monthly Listening Trend (Line Chart)<br>
Daily Listening Heatmap (Hour vs Day)<br>
Peak Listening Hours<br>
Year-wise Streaming Growth<br>
Helps identify when listening activity is highest and detects seasonal or long-term trends.<br>
🔹 Artist & Album Analysis<br>
Top 5 Artists by Play Count<br>
Top 5 Albums by Streams<br>
Artist Contribution Distribution (Donut Chart)<br>
Year-over-Year Artist Growth<br>
Enables identification of most engaged artists and evolving preferences over time.<br>
🔹 Track Performance & Engagement<br>
Top 10 Tracks by Frequency<br>
Average Listening Time vs Track Frequency (Scatter Plot – Quadrant Analysis)<br>
Track Repeat Behavior Analysis<br>
Listening Duration Distribution<br>
Supports deeper understanding of engagement intensity and listening habits.<br>
* Business Impact & Insights<br>
Behavioral Analysis: Identified peak listening hours and preferred days.<br>
Engagement Measurement: Determined high-frequency vs high-duration tracks.<br>
Trend Monitoring: Tracked monthly and yearly listening growth.<br>
Preference Discovery: Highlighted dominant artists and albums contributing to overall streams.<br>
Data Storytelling: Transformed raw playback logs into structured analytical insights.<br>
6️⃣ Screenshot of Dashboard<br>
<br>
![Spotify Dashboard](https://github.com/ShubhamW1107/spotify-listening-analytics-dashboard/blob/main/Spotify_Dashboard.jpg)<br>

