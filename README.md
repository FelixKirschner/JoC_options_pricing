[![INFORMS Journal on Computing Logo](https://INFORMSJoC.github.io/logos/INFORMS_Journal_on_Computing_Header.jpg)](https://pubsonline.informs.org/journal/ijoc)

# Options Pricing

This archive is distributed in association with the [INFORMS Journal on
Computing](https://pubsonline.informs.org/journal/ijoc) under the [MIT License](LICENSE).

The software and data in this repository are a snapshot of the software and data
that were used in the research reported on in the [paper] (change link) by Didier Henrion, Felix Kirschner, Etienne de Klerk, Milan Korda, Jean-Bernard Lasserre and Victor Magron.


## Cite

To cite this software, please cite the [paper](change link) using its DOI and the software itself, using the following DOI.

[![DOI](zenedo link)](zenedo link)

Below is the BibTex for citing this version of the code.

```
@article{OptionsPricing,
  author =        {Didier Henrion, Felix Kirschner, Etienne de Klerk, Milan Korda, Jean-Bernard Lasserre, Victor Magron},
  publisher =     {INFORMS Journal on Computing},
  title =         {{OptionsPricing} Version v1.0},
  year =          {2022},
  doi =           {zenedo link},
  url =           {githup link},
}  
```

## Description

The code presented here was used to obtain the bounds on option prices given in the referenced paper. 

## Building

The code is written in the [Julia programming language](https://julialang.org).

Be sure to make clean before building a different version of the code.

## Results

The results that are produced by the code may be found in Tables 1-8 in the paper. 

## Replicating

To replicate the results in [Figure 1](results/mult-test), do either

```
make mult-test
```
or
```
python test.py mult
```
To replicate the results in [Figure 2](results/sum-test), do either

```
make sum-test
```
or
```
python test.py sum
```

## Ongoing Development

This code is being developed on an on-going basis at the author's
[Github site](https://github.com/tkralphs/JoCTemplate).

## Support

For support in using this software, submit an
[issue](https://github.com/tkralphs/JoCTemplate/issues/new).
