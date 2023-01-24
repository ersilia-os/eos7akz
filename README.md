# PredMS: human liver microsomal stability

PredMS classifies compounds as metabolically stable (≥50% remaining at 30 min) or unstable (<50% remaining at 30 min) in human liver microsomes (in vitro assay). The model was trained on an in-house dataset of 1917 compounds (1049 stable and 868 unstable), and validated on a external test dataset of 61 compounds.

## Identifiers

* EOS model ID: `eos7akz`
* Slug: `pred-ms`

## Characteristics

* Input: `Compound`
* Input Shape: `Single`
* Task: `Classification`
* Output: `Probability`
* Output Type: `Float`
* Output Shape: `Single`
* Interpretation: Probability of a compound being stable (>=0.5: Stable, <0.5: Unstable)

## References

* [Publication](https://academic.oup.com/bioinformatics/article/38/2/364/6369504)
* [Source Code](https://bitbucket.org/krictai/predms/src/master/)
* Ersilia contributor: [carcablop](https://github.com/carcablop)

## Citation

If you use this model, please cite the [original authors](https://academic.oup.com/bioinformatics/article/38/2/364/6369504) of the model and the [Ersilia Model Hub](https://github.com/ersilia-os/ersilia/blob/master/CITATION.cff).

## License

This package is licensed under a GPL-3.0 license. The model contained within this package is licensed under a None license.

Notice: Ersilia grants access to these models 'as is' provided by the original authors, please refer to the original code repository and/or publication if you use the model in your research.

## About Us

The [Ersilia Open Source Initiative](https://ersilia.io) is a Non Profit Organization ([1192266](https://register-of-charities.charitycommission.gov.uk/charity-search/-/charity-details/5170657/full-print)) with the mission is to equip labs, universities and clinics in LMIC with AI/ML tools for infectious disease research.

[Help us](https://www.ersilia.io/donate) achieve our mission!