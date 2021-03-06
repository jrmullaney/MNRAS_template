# The MNRAS template and style file

The is the MNRAS template and style file used to prepare papers that are to be submitted to MNRAS, as provided by the CTAN website, but with some very minor modifications. The main motivation for maintaining this here is to keep a permanent record of this README, which outlines which extra latex packages need to be installed on top of BasicTex for this to compile.

## Getting started:

I prefer to not install the full texLive distribution, as it is HUGE! Instead, I install BasicTex, but this requires me to add additional packages as I see fit. For this I use the `tlmgr` package manager that comes with BasixTex.

The MNRAS style requires the following packages to be installed:
I already had `siunitx` and  `sectsty` packages installed prior to compiling the MNRAS template for the first time on a new machine. Next, I had to:
```
sudo tlmgr install kastrup
sudo tlmgr install newtx
sudo tlmgr install fontaxes
sudo tlmgr install tex-gyre
sudo tlmgr install txfonts
sudo tlmgr install boondox
```

After which, the template compiled correctly. If it complains, you can use the following to search for the package you need to install using:
```
tlmgr search --file <whatever> --global 
```

## The standard MNRAS caveat

This LaTeX package is provided free to the community in the hope that it
assists them in preparing papers for the journal Monthly Notices of the
Royal Astronomical Society.
The files are provided 'as-is' with no guarantee of their suitability,
freedom from errors or omissions, or compatibility with any software.
Neither The Royal Astronomical Society - nor James Mullaney - can provide user support for this package,
LaTeX, or for any other software.
Authors are free to use other styles or programmes if they wish.
Please see the journal instructions to authors for guidance.
This disclaimer is in addition to the No Warranty section of the licence.