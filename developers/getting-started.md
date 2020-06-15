# Getting Started Locally

Due to the nature of the `Simulator` project relying on the `SimulatorCore` project and the infancy 
of the project, the following steps should be taken to get a working simulator project up and 
running locally. Note that this assumes a Unix-like machine, such as Linux or MacOS.

```
$ git clone https://github.com/FRUK-Simulator/Simulator.git
$ git clone https://github.com/FRUK-Simulator/SimulatorCore.git

# IMPORTANT
# In Simulator, remove the dependency on @fruk/simulator-core from package.json

$ cd SimulatorCore
$ npm install && npm run build
$ npm link

$ cd ../Simulator
$ npm install && npm link @fruk/simulator-core
```

> [!NOTE|label:Work to be Done]
> Hopefully this process becomes easier or not needed as the project matures. Due to the priority 
> of features and the state of development, this setup process is still very manual. Please feel 
> free to contribute if you would like to make it more streamlined! 😃