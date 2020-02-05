# eDDA
Electron-driven discrete dipole approximation (e-DDA) source code.

This code is based on [DDSCAT 7.1](http://ddscat.wikidot.com/) and originally developed by Bigelow and co-workers under the guidance of [Prof. Masiello](https://faculty.washington.edu/masiello/Masiello_Group_Website/Home.html) from University of Washington. See details at [ACS Nano 6 7497](https://pubs.acs.org/doi/abs/10.1021/nn302980u) and [ACS Nano 7 4511](https://pubs.acs.org/doi/abs/10.1021/nn401161n). Hu and co-workers made it more rubust in 2019, see [PRB](https://journals.aps.org/prb/accepted/e307cO75Ze81aa39655353a7bef9237196137f2fe.)

To compile it, simply do
```console
make veryclean; make all
```

Please refer to the DDSCAT [user manual](https://arxiv.org/pdf/1002.1505.pdf) for basic how-to. The electron beam information could be included in the parameter file as

```console
make veryclean; make all
```

If you have any questions about this code, please contact [Prof. Masiello](https://faculty.washington.edu/masiello/Masiello_Group_Website/Home.html).
