Model program for the paper: 

Sergey M. Korogod, Irina B. Kulagina
Geometry-induced features of current transfer in neuronal dendrites 
with tonically activated conductances.
Biol Cybern 1998 79:231-240

Running the mosinit.hoc program recreates all the figures of the 
paper. To compute and display a figure click on the corresponding 
item (e.g. "Fig.1." then "Fig.1. A, C" or "Fig.5." then "Fig.5. E-G" 
then "Asymmetric") of the "Article Results" menu window, operating 
similar to "NEURON Main Menu". This presentation was programmed by 
Valery I. Kukushka.

The models illustrate the biophysical basis for a universal estimate 
of effectiveness of the current transfer from distributed (multiple) 
tonic excitatory synaptic input along the dendritic paths with passive 
or active membrane properties. Introducing uniform steady synaptic 
conductivity in the dendritic membrane simulates such input. The figures 
show how the membrane properties and typical morphological 
heterogeneities  (change in diameter, branching) of dendrites determine 
the geometry-dependent pattern of the effectiveness, i.e. the 
contribution from various dendritic sites to the total current reaching 
the soma, during tonic excitation. For that the NEURON programs compute
and display the path profiles of the membrane voltage, total and partial
conductivities, total current per unit membrane area and the core
current increment per unit path length. The latter is the effectiveness 
estimate. Noteworthy are path profiles of the effective equilibrium 
potential of the total membrane current. It is the deviation of the 
membrane potential from the effective equilibrium level that determines 
the driving potential of the membrane current. Tonic dendritic 
depolarization was always the greatest on the distal tips and decayed 
toward the soma with unequal rates along asymmetrical paths (more 
depolarized were longer sister paths). Because of positive slope of the 
local steady current-voltage relation (linear, passive or non-linear, 
active) of the dendritic membrane in the whole range of voltages more 
depolarized dendritic sites made smaller contribution to the somatopetal 
core current.

Membrane mechanisms:

PasD.mod  - passive extrasynaptic and synaptic currents (models with 
passive dendrites)
PasS.mod  - passive synaptic current (models with active dendrites)
Hh1.mod  - sodium, potassium and leak currents of Hodgkin-Huxley type 
(models with active dendrites)
PasSA.mod: passive membrane current of the soma and axon (all models)

Passive axon was excluded from the models with branching dendrites (not 
indicated in the paper).

For further details see the paper or contact the authors at:
Laboratory of Biophysics and Bioelectronics, 
Dniepropetrovsk National University, 
49050 Dniepropetrovsk, Ukraine
Phone/FAX: +38056 776 91 24
E-mails: korogod@ff.dsu.dp.ua;  kulagina@ff.dsu.dp.ua;  valery@ff.dsu.dp.ua
