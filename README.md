# Gemmantha-2b-it
Samantha-uncensored trained gemma:2b-instruct

# INFO
I ran out ouf compute time on colab and i think the weights got corrupted during download, feel free to finish training it

# Important setup

```
os.environ["KAGGLE_USERNAME"] = userdata.get('KAGGLE_USERNAME')
os.environ["KAGGLE_KEY"] = userdata.get('KAGGLE_KEY')
os.environ["KERAS_BACKEND"] = "jax"  # Or "torch" or "tensorflow".
os.environ["XLA_PYTHON_CLIENT_MEM_FRACTION"]="1.00"
```
