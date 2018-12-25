# Driverless

+ **Components**
     - Digital camera
     - Radar : checking the existence of nearby objects
     - Lidar(laser radar) : light detection and ranging, 3D digital model implementation
     - Sona
     - GPS(Global Positioning System)
     - IMU(Inertial Measurement Unit) : Complementing GPS inaccuracy
     - HD digital map
     - Occupancy grid
     - Actuator(artificial muscle) : drive by wire. For example, ECU, ABS, TUC etc
     - Software : Control engineering and AI
     
+ **Software Technology**
     - Controls engineering : controling the mechanical aspects
          + Low level controls(internal system tuning) : brake, accelerator etc
          + Mid level controls(providing artificial visual function) : occupancy grid, cone of uncertainty, short-term trajectory planner module
          + High level controls(etablishing long term strategy) : drive instruction, routing etc
     - Aritificial Intelligence(AI) : Neural network. CNN : At the low level, the features of the image are made up of simple lines and sculptures. As they go up to the higher dimensions, the features become more complex and abstract.
          + synaptic interface : the point where the neuron meets another neuron
          + neurotransmitter
          + synaptic plasticity : the connection between neurons can become stronger or weaker depending on time and experience. Core technology of deep learning
               - Threshold Logic Unit(TLU, McCulloch & Pitts, 1943) : the first artificial neuron, mathematical model
               - Biological model(Hebb, 1949) : postive, negative reinforcement assumption. Hebb's law. 
               - Perceptron(Rosenblatt, 1957) : Self-pattern recognition(synaptic weights). The resistance of wires connecting artificial neurons can function like chemical neurotransmitters.
                    + 1st layer : sensory unit(S unit). mimic the retina
                    + 2nd layer : association unit(A unit). imitate the dendrites of neurons in the visual system
                    + 3rd layer : output layer(R unit). reactive neurons in biological systems
               - Minsky & Papert(1969) : "Perceptron" cannot recognize XOR pattern. 
               - Werbos(1975) : improve perceptron to new form
                    + Artificial neurons are able to output not only 1 or 0 but also the value between them.
                    + Error backpropagation 
               - Neocognition(Fukushima, 1980) : Adopt the same technology as the modern type of deep-learning network
               - Unversal approximation theorem : The core concept of neural networks is theoretically valid. To obtain an approximation of all measurable functions with a certain degree of accuracy, neural networks require only one hidden layer of artificial neurons. There is no point in trying to develop a neural network consisting of two or more layers.
               - Fei-Fei Li(2003) : Caltech-101 ---> ImageNet
               - Nvidia(2006) : Release GeForce 8. The first GPU architecture product. 
               - ILSVRC(2012) : SuperVision team(AlexNet) adopts CNN to show a remarkable image classification success rate. CNN becomes the standard.
               - ILSVRC(2015) : MS Beijing team, 3.57 percent error rate(Resiudal Learning). It was the first time to exceed the human-level perception ability of 5 percent error rate.                 
     
+ **History**
     - Futurama(GM Marketing team, 1939)
     - Electronic highway(1958)
     - Automated highway(GM, 1960s)
     - V2X(Vihicle-to-Everything) : V2V(vehicle-to-vehicle) + V2I(vehicle-to-infra)

### Reference
[Driverless: Intelligent Cars and the Road Ahead, MIT press]()
