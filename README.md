Here is your Spotify Power BI project formatted to exactly match the example structure you provided:

1. Project Title / Headline

🎵 Spotify Analytics: 2023 Most Streamed Songs Dashboard

A dynamic, interactive data visualization tool built to explore top-performing Spotify tracks—focusing on audio features, release strategies, and streaming performance through an advanced, custom-built UI and API integration.

2. Short Description / Purpose

The Spotify Analytics Dashboard is a visually engaging and highly customized Power BI report designed to help users explore and compare the most streamed Spotify songs of 2023. This tool is intended for use by music industry analysts, marketing teams, artists, and data professionals who seek to understand what makes a track a "hit," analyze release timing trends, and explore the advanced technical limits of Power BI's UI/UX capabilities.

3. Tech Stack

The dashboard was built using the following tools and technologies:

 📊 Power BI Desktop – Main data visualization platform used for report creation.
 📂 Power Query – Data transformation layer used to clean and merge the core dataset with API-fetched image URLs.
 🧠 DAX (Data Analysis Expressions) – Used for calculated measures, custom HTML/SVG code generation, and dynamic conditional formatting.
 🐍 Python (via ChatGPT) – Leveraged to write and run scripts querying the Spotify Web API for missing data.
 🖌️ Deneb & Vega-Lite – Used to construct highly customized, non-standard visual elements by writing raw visualization grammar.
 🎨 PowerPoint – Used to design the custom "Glassmorphism" background interface and layouts.

4. Data Source

Source: Kaggle & Spotify Web API.
Core data on the most streamed Spotify songs of 2023, including track metadata, stream counts, and audio features (energy, danceability, acousticness, etc.). This static CSV was enriched using the Spotify Web API (via a Python script) to programmatically fetch the corresponding album cover image URLs for every track to be rendered inside the dashboard.

5. Features / Highlights

 Business Problem
Standard BI dashboards often fail to deliver the highly engaging, consumer-grade UI/UX required for media and entertainment analytics. Static datasets frequently lack rich media context (like album covers), making it difficult for stakeholders to connect with the raw data. Furthermore, answering key industry questions—such as What days of the week are best to release a track? or How does a top song compare to the annual average?—requires custom visual hierarchies that go beyond out-of-the-box charts.
 Goal of the Dashboard
To deliver an interactive, app-like visual tool that:
 Enables users to explore the audio features and streaming performance of 2023's top tracks.
 Supports decisions regarding music release strategies and marketing timing.
 Proves that Power BI can function as a fully customized, high-fidelity front-end developer canvas.


 Walkthrough of Key Visuals
 Dynamic Album Cover (HTML Visual): Uses custom DAX to inject image URLs into HTML/SVG code, rendering the selected track's album cover with a modern, rounded border directly in the report.
 Key KPIs (Top Metrics): Displays dynamically updating metrics for the most streamed song based on user selection, including Track Name, Artist, Release Date, and Total Streams.
 Top Song vs. Yearly Average (New Card Visual): Transparent KPI cards featuring custom conditional formatting (red/green text) to show exactly how much a top-performing track outperformed the yearly average.
 Audio Feature Trackers: Custom UI cards displaying song quantifiers like acousticness, danceability, liveliness, and valence.
 Tracks by Release Date (Deneb Heatmap): A custom Vega-Lite heatmap visualizing track release volumes across days of the week and months, establishing a clear view of release timing trends.
 Average Energy (Deneb Unit Chart): A bespoke unit chart gradient-mapped to Spotify's brand colors, displaying the average energy percentage of tracks within the selected parameters.


 Business Impact & Insights
 Release Strategy Optimization: Music labels and marketing teams can use the heatmap to identify peak days and months for track releases, maximizing visibility and streams.
 Performance Benchmarking: Quantifies exactly how much top-performing tracks outperform average streams, establishing clear baseline KPIs for industry "hits."
 Enhanced Stakeholder Adoption: By implementing a Glassmorphism UI and custom HTML components, the dashboard mimics a native web application, drastically increasing user engagement compared to traditional reporting.
 Automated Data Enrichment: Proves the viability of bridging static offline data with live online APIs (via Python) to enrich dashboards before data even hits the Power Query engine.



6. Screenshots / Demos

![Dashboard Preview](https://github.com/swabhimangandhale26-alt/Spotify-dahsboard/blob/main/Spotify%20Dashbaord.png)
