# titlepage4956
### D Evangelista
Latex style for adding a cover page to EW495 and EW496 reports. This is needed because the template Word documents graft a title page onto IEEEtrans that normally doesn't have a title page. 

## How to get this package
Clone the repository into your `texmf` tree. 
```bash
git clone https://github.com/devangel77b/titlepage4956
```
On Ubuntu machines, your `texmf` is typically within your home directory (usually `/home/username/texmf`). The files should probably go within `~/texmf/tex/latex` somehwere). 

On Windows machines using Miktex I usually put the files in a `texmf` tree under `This PC > Documents` for example. 

## Examples
In the preamble of your report, include the following
```latex
\usepackage{titlepage4956}
\coursenumber{EW496}
\advisor{Assistant Professor D. J. Evangelista}
\coverpicture{\includegraphics[width=0.75\columnwidth]{\myroot/figures/es495-cover.png}}
```
Then, add this after ```\begin{document}```
```latex
\maketitlepage
```

## Contributors
D Evangelista

