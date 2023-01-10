# pymc3-tutorial-practice

# ToDo
`marginalized_gaussian_mixture_model.ipynb`
- [ ] `transform`の用途
```
mu = pm.Normal(
        "mu",
        mu=np.zeros_like(W),
        sigma=1.0,
        shape=W.size,
        transform=pm.transforms.ordered,
        testval=[1, 2, 3],
    )
```
