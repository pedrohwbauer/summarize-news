# Problem
The phenomenon of clickbait. Sensational headlines are designed to attract readers' attention and generate clicks, often exaggerating or distorting the actual content of the article, causing misinformation.

# Solution
Having a list of news, in which each news item is identified not by the title, but by the summary of its content.
To create the prototype, a list of news was scraped from Google News and the "facebook/bart-large-cnn" language model was used to summarize each article's content.

Model link: https://huggingface.co/facebook/bart-large-cnn
