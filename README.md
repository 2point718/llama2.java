## llama2.java

<p align="center">
  <img src="assets/llama_c.jpg" width="300" height="300" alt="Llama Java">
</p>

Implementation fork lives here <a href="https://github.com/renmat/llama2.java">https://github.com/renmat/llama2.java</a>

Export weights as npy files to be loaded in ND4J
```
for k, v in model.state_dict().items():
    numpy_weight = v.cpu().numpy()
    np.save(f"{k}.npy", numpy_weight)
```
## License

MIT
