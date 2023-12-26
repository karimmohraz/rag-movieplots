# Explain Retrieval Augmented Generation (RAG)

<img src="images/RAG.png" alt="Retrieval Augmented Generation" width="40%" height="auto" class="blog-image">

## Automated Prompt Engineering
Programmatically add context info on lesser known movies to the LLM prompt. 

This can improve the answer considerably:
```
Question: Tell me about the movie "A Touch of Zen".
LLaMa2_7b answers by hallucinating:
"A Touch of Zen" is a 2001 Taiwanese film directed by Hou Hsiao-hsien ...

Using RAG the LLaMa2_7b returns the right answer:
Here\'s what I know about the movie "A Touch of Zen":\n\n* It was released in 1971, directed by King Hu.\n* The plot follows a well-meaning but unambitious scholar and painter named Gu who lives in a remote mountain village in Ming China during the 14th century AD.\n* The story is largely seen through Gu\'s eyes, with a focus on his clumsiness and ineffectualness.
```

## Movie Dataset
[Kaggle dataset](https://www.kaggle.com/datasets/jrobischon/wikipedia-movie-plots/) containing 35k movie plots

Download csv [here](https://www.kaggle.com/datasets/jrobischon/wikipedia-movie-plots/download?datasetVersionNumber=1)

<img src="images/data-card.png" alt="Retrieval Augmented Generation" width="50%" height="auto" class="blog-image">

## Watch the Youtube video
The jupyter notebook is demoed in this [video](https://www.youtube.com/watch?v=PoZxanevWa4).

## Local LLM
This demo leverages [GTP4ALL](https://gpt4all.io/index.html): A free-to-use, locally running, privacy-aware chatbot. No GPU or internet required.
