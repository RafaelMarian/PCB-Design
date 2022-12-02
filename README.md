# PCB-Design

For this project, I used OrCad Capture Cis and Layout extension from OrCad.
We divide the project into two parts, in the first part we create the circuit in Orcad, putting all the
components together and assigning their real-life parts.
When we finish this first step we also check if everything is ok by generating a document that contains all
the errors, if the error is zero we can move forward to generate the document with all the parts that we
need to build the circuit in real life.
In the next step, we build the Layout for our components, using a multi-layer Design. That means we have
the main layer, the top one, where all the components are installed, the thru-hole components and PCB
components. Also for the thru-hole components, we need another two layers, one for alimentation and
another one for ground. We use different types of alimentation like 12Vi and 5Vi, and different types of
grounds, because different components require different types of alimentation. In the last phase, we rout
all the components, connecting them to alimentation, also we do the electrical testing, signature and the
project it's done, and we can submit our design to manufacturing.
Our main components are Attiny2313 Microcontroller, Max485 which is a low-power transceiver for RS-485
and RS-422 communication, LM78 which is a Three-terminal positive voltage regulator and other
components that are creating our system.
