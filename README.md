# Blockly Visual PLC Programming Language VPL:

![](./assets/VisualPLC.JPG)

![](./assets/VisualPLC_BlocklyPLC_TwinCAT_read_variable_Number.JPG)

***
> [!NOTE]
> ### Setup the dev environment:
- OS: Windows

> ### Beckhoff TwinCAT Shell XAE and XAR:
> download Beckhoff TE1000-twincat-3-engineering:
> - https://www.beckhoff.com/es-es/products/automation/twincat/texxxx-twincat-3-engineering/te1000.html?

> install Beckhoff TwinCAT Shell or previously install visual studio 2017,2019 possible versions community, professional or enterprise and then install TE1000 TwinCAT Shell.

- Docker: Linux, Raspberry. (VM - virtual machine)
***
> [!TIP]
> open project TwinCAT TC3_BlocklyPLC.sln and download
***
> [!IMPORTANT]  
> You have to decide in which software and programming languages ​​to develop the project, for example Node.js+express.js or python, etc...
***
> [!WARNING]  
> first version:

> ### $\textcolor{yellow}{Backend:}$
> - [ ] operating problem I had to add a 1 sec wait time block after the Beckhoff TwinCAT PLC connect block
> - [ ] add Block read variable type string PLC, and logic_compare two strings.
> - [ ] add Block read variable type float PLC, and logic_compare two float.
> - [ ] connect port: 301 without PLC runtime, direct I/O

> - [ ] Blockly add MQTT
>      - https://github.com/runtimevic/mqtt-node
>      - https://github.com/runtimevic/mqtt-custom-dashboard-node-js
>      - https://github.com/Gr4vity4/mqttws31
>      - https://github.com/Gr4vity4/MQTT-BLOCKLY
>      - https://github.com/frangoteam/FUXA/blob/master/server/runtime/devices/mqtt/index.js

> - [ ] Blockly add Siemens PLC driver node-snap7...

> - [ ] Blockly motion TwinCAT with PLC.
> - [ ] Blockly motion TwinCAT direct without PLC.

> - [x] connect port: 851
> - [x] paralell process
> - [x] add more Blocks
> - [x] add Block read variable type number PLC and control, and logic
> - [x] add logic_compare and block Read_variableNumber TwinCAT
> - [x] write variable type float => write variable "GVL_Test.TestREAL" value number 12.5
> - [x] write variable type string=> write variable "GVL_Test.TestSTRING" "hello"
> - [x] add Block connect PLC Beckhoff TwinCAT, problem add block after block time 1seg.

> ### $\textcolor{yellow}{Frontend:}$
> - [ ] Select different themes..
> - [ ] Be able to observe the server log on the frontend or Logview file
> - [x] Database diferents programm.
> - [x] toolbox add icons center, zoom+. zoom--
>      - https://developers.google.com/blockly/guides/configure/web/zoom?hl=es-419 

> ### $\textcolor{yellow}{Docker\ Hub:}$
> - [ ] first version Docker image.
> - [ ] Git actions create Docker Hub.
***
> [!CAUTION]
> demo version
***
