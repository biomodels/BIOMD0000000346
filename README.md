# BIOMD0000000346: FitzHugh1961_NerveMembrane

## Installation

Download this repository, and install with distutils

`python setup.py install`

Or, install using pip

`pip install git+https://github.com/biomodels/BIOMD0000000346.git`

To install a specific version (in this example, from the 2014-09-16 BioModels release)

`pip install git+https://github.com/biomodels/BIOMD0000000346.git@20140916`

## Usage

Importing the model package.

`import BIOMD0000000346 as model`

Get the SBML string from the model

`print model.sbmlString`

If [python-libsbml](https://pypi.python.org/pypi/python-libsbml) bindings are
installed, the libsbml.SBMLDocument object is also accessible

`model.sbml`


# Model Notes


This is the original model from Richard FitzHugh, which led the famous
FitzHugh–Nagumo model, still used for instance in computational neurosciences.  
**Impulses and Physiological States in Theoretical Models of Nerve Membrane**   
FitzHugh R _Biophysical Journal,_ 1961 July:1(6):445-466 [doi:10.1016/S0006-34
95(61)86902-6](http://dx.doi.org/10.1016/S0006-3495\(61\)86902-6) ,  
**Abstract:**   
Van der Pol's equation for a relaxation oscillator is generalized by the
addition of terms to produce a pair of non-linear differential equations with
either a stable singular point or a limit cycle. The resulting BVP model has
two variables of state, representing excitability and refractoriness, and
qualitatively resembles Bonhoeffer's theoretical model for the iron wire model
of nerve. This BVP model serves as a simple representative of a class of
excitable-oscillatory systems including the Hodgkin-Huxley (HH) model of the
squid giant axon. The BVP phase plane can be divided into regions
corresponding to the physiological states of nerve fiber (resting, active,
refractory, enhanced, depressed, etc.) to form a physiological state diagram,
with the help of which many physiological phenomena can be summarized. A
properly chosen projection from the 4-dimensional HH phase space onto a plane
produces a similar diagram which shows the underlying relationship between the
two models. Impulse trains occur in the BVP and HH models for a range of
constant applied currents which make the singular point representing the
resting state unstable.

This model originates from BioModels Database: A Database of Annotated
Published Models (http://www.ebi.ac.uk/biomodels/). It is copyright (c)
2005-2012 The BioModels.net Team.  
For more information see the [terms of
use](http://www.ebi.ac.uk/biomodels/legal.html) .  
To cite BioModels Database, please use: [Li C, Donizelli M, Rodriguez N,
Dharuri H, Endler L, Chelliah V, Li L, He E, Henry A, Stefan MI, Snoep JL,
Hucka M, Le Novère N, Laibe C (2010) BioModels Database: An enhanced, curated
and annotated resource for published quantitative kinetic models. BMC Syst
Biol., 4:92.](http://www.ncbi.nlm.nih.gov/pubmed/20587024)


