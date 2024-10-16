# CLIPCEIL (Neurips 2024)
CLIPCEIL: Boosting Domain Generalization for CLIP by Channel rEfinement and Image-text aLignment
<p align="center">
<img src=".\figs\overview.png" height = "320" alt="" align=center />
<br><br>
<b>Figure 1.</b> Overview of CLIPood.
</p>

## Get Started

1. Environment Installation

Clone the repository locally:

```
https://github.com/yuxi120407/CLIPCEIL.git
```

Install the required packages:

```
pip install -r requirements.txt
```
2. Prepare Data. Our datasets are built over [DomainBed](https://github.com/facebookresearch/DomainBed) For usage, one should clone the above repositorie, then download data following the instructions, and arrange the folder as:
```plain
|-- DomainBed/
    |-- domainbed/
        |-- data/
            |-- domain_net/
            |-- office_home/
            |-- ...  # other DomainBed datasets
        |-- ...
    |-- ...
|-- ...
```
