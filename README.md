# Shakespearean Text Analysis

[Interactive App](https://rcchan5-shakespeare-text-analysis-wordcloud-jitlub.streamlit.app/)

## Overview

This repository contains the code and resources for an in-depth analysis of the works of William Shakespeare, widely regarded as one of the greatest playwrights and poets in history. The primary goal of this project is to apply modern text analysis techniques to Shakespeare's writings in order to uncover patterns in language use, identify recurring themes, and provide a deeper understanding of his literary style. By leveraging the power of computational tools, we aim to explore aspects of Shakespeare's vocabulary, word usage, and linguistic choices in a way that enhances both academic and casual appreciation of his works.

Through this project, you will explore insights into Shakespeare’s writing, such as:

- The most frequently used words in his works.
- The diversity of Shakespeare’s vocabulary across different plays.
- Trends and shifts in word usage over time.
- Thematic elements that are central to his works.

## Dataset

The analysis is based on a collection of Shakespeare's plays, which are stored in the `data` folder of this repository. The dataset contains the full text of a selection of his most famous plays, including *Hamlet*, *Macbeth*, *Romeo and Juliet*, and many others. These texts are in the public domain, allowing us to freely perform analyses on their content.

The dataset is carefully cleaned and pre-processed to ensure it is suitable for text analysis, with steps such as:

- Removing punctuation and non-textual elements.
- Converting the text to lowercase for consistency.
- Tokenizing the text into individual words and phrases for analysis.

This dataset forms the backbone of all analyses and visualizations in the project, providing a rich linguistic resource to explore Shakespeare's writing.

## Analysis

### Word Frequency Analysis

One of the core analyses conducted on Shakespeare's texts is word frequency analysis, which identifies the most common words used throughout his works. This analysis not only uncovers the most frequently occurring words but also allows us to explore several key insights, such as:

- **The Most Common Words**: By identifying the words that appear most frequently, we gain an understanding of the focal points of Shakespeare’s writing, including common function words and content words that may reflect key themes.
- **Vocabulary Richness**: A closer look at the diversity of vocabulary across different plays helps us understand how Shakespeare's word choices evolved over time and within different genres.
- **Thematic Exploration**: By analyzing word frequencies in conjunction with the themes of individual plays, we can gain insights into recurring motifs and ideas, such as love, power, death, and betrayal, which are often central to Shakespeare's works.

This analysis is performed using a combination of Python libraries such as NLTK and pandas, and the results are used to generate a word cloud that visually represents the most frequent words in Shakespeare’s plays. 

You can access the code and results of the word frequency analysis in the [Wordcloud.py script](https://github.com/RCChan5/Shakespeare-Text-Analysis/blob/main/Wordcloud.py).

## Visualization

To make the findings from this analysis more accessible and engaging, a front-end visualization was developed using the [Streamlit](https://streamlit.io/) framework. This interactive app allows users to explore the results of the text analysis in a visually appealing and intuitive way. The app includes several key features:

- **Word Cloud**: A dynamic, interactive word cloud that visually represents the most frequently used words in Shakespeare’s works. Users can interact with the word cloud to filter and explore words based on frequency and context.
- **Word Frequency Chart**: A chart displaying the frequency of specific words across different plays. This allows users to explore how certain words, such as "love" or "death", appear in different contexts throughout Shakespeare's works.
- **Entity Visualizations**: Interactive charts highlighting the most frequently mentioned characters and locations, as well as their relationships throughout the plays.

These visualizations are designed to make the analysis more accessible to a broader audience, whether they are researchers, students, or casual Shakespeare enthusiasts.

## Future Enhancements

While this project provides a solid foundation for analyzing Shakespeare's works, there are several potential enhancements for future work:

- **Exploration of Additional Plays**: The dataset can be expanded to include additional plays and sonnets, providing a broader view of Shakespeare's entire body of work.
- **Topic Modeling**: Using techniques like Latent Dirichlet Allocation (LDA), we can explore the hidden thematic structures within Shakespeare's works.
- **Character Network Analysis**: By analyzing the relationships between characters across different plays, we can visualize the networks of interaction in Shakespeare’s universe.

## Conclusion

This project serves as an introduction to the possibilities of text analysis applied to classic literature. By using modern computational tools, we can gain new insights into the language, themes, and emotional arcs of Shakespeare's plays. The goal is to not only enhance our understanding of Shakespeare’s work but also to provide a framework for performing similar analyses on other classic literary texts.

Feel free to explore the [interactive app](https://rcchan5-shakespeare-text-analysis-wordcloud-jitlub.streamlit.app/) to see the results of this analysis firsthand.
