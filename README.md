## Dependencies

```bash
micromamba create -n jupyterlab python pytorch torchvision torchaudio "cuda-version>=12.8,<13" datasets transformers peft evaluate accelerate jupyterlab -c pytorch -c conda-forge -c nvidia -y
```
