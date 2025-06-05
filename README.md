# IPL_dashboard

🏏 Inside IPL 2025: A Live Power BI Dashboard for Real-Time Cricket Data
A vibrant and immersive dashboard capturing the electrifying action of IPL 2025—integrating live data, custom visuals, and analysis across teams, players, and matches.

🎯 Short Description / Purpose
The Inside IPL 2025 Dashboard is a visually striking, interactive Power BI report that brings real-time IPL data to life. Built for cricket fans, analysts, content creators, and sports marketers, it offers live match updates, team details, historical records, and player statistics—all in one seamless visual story.

🧰 Tech Stack

The dashboard was built using the following tools and technologies:

• 📊 Power BI Desktop – Main platform for visual development.

• 🔄 Power Query Editor – For cleaning, reshaping, and transforming complex data sources.

• 🧠 DAX (Data Analysis Expressions) – Used for KPIs like win percentages, best strike rates, and custom indicators.

• 🌐 Live Web Data Extraction – Pulled IPL 2025 points tables and match results from Cricbuzz using Power BI’s built-in web connectors.

• 🔗 API Integration – Explored APIs on RapidAPI, though challenges like API key access limits and site restrictions were encountered.

• 🎨 Custom Visuals with HTML & CSS – Designed interactive player cards and stylized buttons directly inside Power BI using rich formatting.

• 📁 File Format – Developed in .pbix, shared through .png snapshots and .pbit templates.


📚 Data Source
Primary Source: [Cricbuzz IPL 2025 live updates] – scraped via web connector.
                [Espn IPL 2025 live updates] – scraped via web connector.
• Live Data:
Points Table (NRR, Wins/Losses, Ties)
Match Results (Teams, Scores, Winners)
Player Performances (Runs, Economy, Strike Rates)

• Secondary (Manual) Data:
Orange and Purple Cap Winners
Past IPL Champions
Team Rosters with Player Info

⚠️ Note: Power BI does not support direct scraping of JavaScript-rendered content (like dynamic tables). This was a major learning moment—highlighting the limits of BI tools when dealing with modern, script-heavy web architectures.

✨ Features / Highlights
• Business Problem
In India, cricket is religion—and IPL is its grandest festival. Yet, there’s no centralized, visually powerful tool where fans or analysts can explore live, team-specific, and historical IPL insights holistically.

Questions like:

Who is topping the points table right now?
Which player has the best strike rate this season?
What does each squad look like?
Who dominated last year’s edition?
…are hard to answer without switching between multiple sources.

• Goal of the Dashboard
To build a professional-grade, interactive dashboard that:

Fetches live IPL data and presents it in a consumable form

Celebrates cricket analytics through custom visuals and KPIs

Bridges fan curiosity with data science tools

Serves as a learning experiment to understand web scraping, API limits, and Power BI's rendering capabilities

• Walkthrough of Key Visuals
🔹 Page 1 – Home Page
• Player Visuals & Branding: Features iconic players like MS Dhoni, Shubman Gill, Virat Kohli, adding visual personality to the tool.
• Navigation Panel: Smooth transitions between Overview, Teams, and Records sections—designed using intuitive bookmarks and buttons.

🔹 Page 2 – Overview Page
• 📅 Recent Match Results: Updated cards with team logos, match scores, and outcomes (manually maintained due to JavaScript rendering issues in live data).
• 🧮 Player Stats Cards: Top performers like best economy, most fifties, highest strike rate—calculated using DAX and styled using HTML-inspired visuals.
• 📊 Live Points Table: Pulled via web scraping (Power BI web connector).

⚠️ Note: Faced timeouts and update errors due to heavy page load and rendering delays on Cricbuzz. Resolved using “Enable Load” management and manual refresh control.
• 👥 Squad Roster Table: Filterable by team and player role, enabling deep team-wise exploration.

🔹 Page 3 – Team & Player Page
• 🔘 Clickable Team Buttons: Takes user to filtered player tables based on selected team.
• 🧑‍✈️ Squad Details: Player names, age, nationality, and role displayed in a structured layout.
• 🎨 Custom Cards: Created using formatted text boxes and visuals to give a sleek, cricket-themed appearance.

🔹 Page 4 – Records Page
• 📈 Year-wise Orange & Purple Cap Winners: Tabulated with color-coded visuals for trend spotting.
• 🏆 Past IPL Champions: Timeline-style table capturing all seasons till 2024, helping users relive IPL legacy.

• Challenges & Learnings
• ⛔ Live Data Update Failures:

Cricbuzz’s heavy JavaScript prevented full data scraping

Power BI timed out during refresh

Realized limitations of scraping dynamic content

• 🔐 API Access Restrictions:

Tried integrating RapidAPI endpoints for match info

Most APIs required API keys with limited or paid access

Had to balance between web scraping and manual updates

• 💡 HTML & CSS in Power BI:

Innovated by simulating custom visuals like stat cards, player tables, and team grids

Gained design flexibility while staying within Power BI’s native constraints

• Business Impact & Insights
✅ Engaging Visual Storytelling: Makes IPL data fun and accessible—perfect for fans, influencers, and analysts.
✅ Marketing & Sponsorship Tool: Helps identify top players, in-form teams, and match highlights—valuable for sports marketing firms.
✅ Learning Showcase: Great student project to demonstrate real-world BI application, API handling, and Power BI design skills.
✅ Data-Driven Culture: Promotes analytical thinking in cricket fandom, encouraging more people to look beyond scores and into performance metrics.
