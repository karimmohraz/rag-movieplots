# Explain Retrieval Augmented Generation (RAG)

<img src="images/RAG.png" alt="Retrieval Augmented Generation" width="40%" height="auto" class="blog-image">

## Automated Prompt Engineering
Programmatically add context info on lesser known movies to the LLM prompt. 

This can improve the answer considerably:
```
Question: Tell me about the movie "A Touch of Zen".
LLaMa2_7b answers by hallucinating:
A Touch of Zen" is a 2001 Taiwanese film directed by Hou Hsiao-hsien ...

Using RAG the LLaMa2_7b's answer becomes:

```

## Movie Dataset
[Kaggle dataset](https://www.kaggle.com/datasets/jrobischon/wikipedia-movie-plots/) containing 35k movie plots

<img src="images/data-card.png" alt="Retrieval Augmented Generation" width="50%" height="auto" class="blog-image">

## Watch the Youtube video
The jupyter notebook is demoed in this [video](https://www.youtube.com/watch?v=PoZxanevWa4).



