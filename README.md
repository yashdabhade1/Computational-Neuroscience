## About the Project
This is a Jupyter notebook implementation of the Hodgkin-Huxley model, which describes the dynamics of the action potential in a neuron. The model consists of a set of ordinary differential equations that capture the flow of ions across the neuronal membrane.

## Requirements
To run the simulation, you will need the following packages:
This is an example of how to list things you need to use the software and how to install them.
* numpy
* matplotlib
* neuron

You can install them using pip:
  ```sh
  pip install numpy numpy
  pip install numpy matplotlib
  pip install numpy neuron
  ```
  
## Usage
You can then run the cells in the notebook by pressing Shift+Enter. The first cell contains the model equations and the second cell runs the simulation and generates a plot of the membrane potential as a function of time.

You can modify the simulation parameters by editing the constants in the second cell:

* **Cm**: membrane capacitance (in uF/cm^2)
* **gK**: maximum conductance of the potassium channel (in mS/cm^2)
* **gNa**: maximum conductance of the sodium channel (in mS/cm^2)
* **gl**: leak conductance (in mS/cm^2)
* **VK**: potassium reversal potential (in mV)
* **VNa**: sodium reversal potential (in mV)
* **VL**: leak reversal potential (in mV)
* **I**: external current (in uA/cm^2)

You can also change the duration and time step of the simulation by modifying the **tmin, tmax**, and **dt** variables.

## License
This code is released under the MIT License. See LICENSE.txt for details.
