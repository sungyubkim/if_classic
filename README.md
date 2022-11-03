# Influence Function (IF) for classical generative models

A brief notebook on Influence Function (IF) for classical generative models (e.g., $k$-NN, KDE, GMM)

# Training data

![Alt text](./figs/train.png)


# Results

| metric | $10$-NN | KDE | GMM |
|:---:|:---:|:---:|:---:|
| LL | ![Alt text](./figs/ll/kNN_10.png) | ![Alt text](./figs/ll/KDE.png) | ![Alt text](./figs/ll/GMM.png) | 
| Self-IF | ![Alt text](./figs/self_if/kNN_10.png) | ![Alt text](./figs/self_if/KDE.png) | ![Alt text](./figs/self_if/GMM.png) | 
| IF over (5,8) | ![Alt text](./figs/if/kNN_10.png) | ![Alt text](./figs/if/KDE.png) | ![Alt text](./figs/if/GMM.png) | 
