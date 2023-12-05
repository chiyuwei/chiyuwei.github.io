---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
---

### Are Large Language Models Good at Simulating Human Samples? A Topic Study.
- **Advised by**: Dr. Emilio Ferrara
- **Duration**: 2023.08 - Present
- **Details**:
  - Explore the capabilities of Large Language Models (LLMs) to simulate human behaviors, using prompts that include variables such as ideology, income, gender, age, race, etc.
  - Fine-tune Llama 2 model using data from diverse human surveys, aligning model-generated responses with actual human behavior. Utilize regression models to build the weight with the variables that best predict response differences between LLM and humans.
  - Our preliminary findings reveal the model’s effectiveness in simulating large group trends, though predicting individual behaviors accurately continues to be a challenge.

### Multimodal Partisan Sentiment Framing in Inflation News Coverage
- **Advised by**: Dr. Mohammad Soleymani
- **Duration**: 2023.05 - Present
- **Details**:
  - Conduct a comprehensive study on inflation-related video content by leveraging both facial and text analysis. The aim is to unveil inherent network narratives and biases, highlighting the contrasting stances of major media outlets on the topic.
  - Lead the video preprocessing using Pyannote-video and OpenFace 2 for accurate facial ex- pression analysis. Analyze video transcripts on sentiment interpretation with Whisper and LIWC. Conduct statistical tests on video clips to identify media biases.
  - Find that the sentiment derived from Action Units consistently aligns with results from text analysis, indicating biases in FOX News and MSNBC, while CNN maintains relative balance.

### Classification of Political Extremists and Moderate Users on Twitter
- **Advised by**: Dr. Emilio Ferrara
- **Duration**: 2023.03 - Present
- **Details**:
  - Introduced a novel methodology, False-Supervised Learning, aimed at classifying Twitter users based on political leanings and distinguishing between extremist and moderate stances.
  - Users are categorized as extremists or moderates based on ideological scores generated from URLs. BERT-based classifiers are then trained using various proportions of labeled data.
  - The most precise model in differentiating between moderate and extremist is selected as the optimal approach, which establishes a clearer threshold for distinguishing between them.

### Retrieving False Claims on Twitter during the Russia-Ukraine Conflict
- **Advised by**: Dr. Emilio Ferrara
- **Duration**: 2022.06 - 2023.03
- **Details**:
  - This paper is included in the Companion Proceedings of the ACM Web Conference 2023.
  - Collected and manually annotated 83 false claims circulated on Twitter during the initial weeks of the Russia-Ukraine Conflict. This task involved handling and categorizing 5,872 original tweets into four distinct classes: related, not related, support, and refute.
  - Designed and implemented a BERT-based automated pipeline capable of detecting and re- trieving tweets that discussed the verified false claims. This model achieved an F1-score of 80.57%. Further, the tweet retrieval model obtained a Top-3 accuracy of 96.35%.
  - Successfully demonstrated the practicality and effectiveness of the developed approach in retrieving false claims. The model showed consistent performance in real-world conditions.
