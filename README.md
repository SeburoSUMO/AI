# AI

For more information, read https://openai.com/blog/better-language-models/

Build GPT-2 in Docker (need Git and Docker installed):

```git clone https://github.com/openai/gpt-2.git```

```docker build --tag gpt-2 -f Dockerfile.cpu .```

To run GPT-2:

```docker run -it gpt-2 bash```

```sed -ie s/sort\(/contrib\.framework\.sort\(/g src/sample.py```

```python3 src/interactive_conditional_samples.py --top_k 40```

More info at https://github.com/openai/gpt-2/blob/master/DEVELOPERS.md
