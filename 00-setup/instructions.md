```sh
python3 -m venv .venv
```


```sh
source .venv/bin/activate
```

```sh
python -m pip install --upgrade pip
```

```sh
python -m pip install uv
```

```sh
uv pip install huggingface-hub
```

```sh
hf auth login
```
- Need to provide auth token from Hugging Face.

```sh
hf jobs uv run --flavor a10g-small main.py --input_text "'The answer is 42'"
```

```sh
uv pip install openai fire dotenv
```

```sh
python inference_sample.py "The capital of France is " --model "Qwen/Qwen3-0.6B-Base" --max_tokens=1024
```