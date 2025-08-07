# Movie-Pitch-Machine
CIS518 Big Data Analysis Final Group Project

Background: Using data from Reddit, fanfiction platforms, YouTube, and Spotify, we built a system that could identify trending themes, potential soundtracks, and even align casting ideas with audience sentiment.

Problem Definition: How can we use public online data to generate a compelling, emotionally resonant movie pitch that aligns with current trends in music, fan interest, and casting preferences?

Goals:
Identify trending music and emotional tone to guide soundtrack and story arc
Analyze fan casting sentiment to inform lead actors
Explore genre and storyline themes favored across fan forums
Combine all elements into a cohesive pitch that reflects audience demand

My focus on Storyline.

Technical:
This project pulled data from Reddit, AO3, YouTube, and Spotify using a variety of APIs and scraping tools. Key components included:
- NLP & Topic Modeling: Transformers (BERT), sentence-transformers, LDA (gensim), UMAP for dimensionality reduction, and clustering (KMeans)
- Cross-platform matching: Fuzzy matching via RapidFuzz for syncing track titles from YouTube/Spotify
- Machine Translation & Localization: fastText for language detection, deep-translator for YouTube & AO3 comment translation
- Visualization: Seaborn, matplotlib, wordcloud, pyLDAvis
- AI assistance: ChatGPT + Grok AI for debugging, design, and pipeline iteration
