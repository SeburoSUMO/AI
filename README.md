# AI

```git clone https://github.com/openai/gpt-2.git```

```docker build --tag gpt-2 -f Dockerfile.cpu .```

```docker run -it gpt-2 bash```

```sed -ie s/sort\(/contrib\.framework\.sort\(/g src/sample.py```

```python3 src/interactive_conditional_samples.py --top_k 40```

More info at https://github.com/openai/gpt-2/blob/master/DEVELOPERS.md
