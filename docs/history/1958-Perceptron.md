## **Frank Rosenblatt: The Perceptron (1958)**

### **What problem existed?**

By the late 1950s, computers were excellent at following rigid, "if-then" logical instructions (Symbolic AI). However, they were hopeless at "fuzzy" tasks that humans find easy—like recognizing a handwritten letter or distinguishing a circle from a square. You couldn't write enough rules to cover every possible variation of a hand-drawn shape. We needed a machine that could learn its own rules from examples.

### **What did this person actually do?**

At the Cornell Aeronautical Laboratory, Frank Rosenblatt created the **Perceptron**. It wasn't just code; it was a physical machine (the Mark I Perceptron) connected to a camera with  cadmium sulfide photocells. It was a mathematical model of a single neuron. It took multiple inputs, assigned them "weights," and if the sum of those weights hit a certain threshold, the neuron "fired." Crucially, it had a built-in feedback loop: if it guessed wrong, it would automatically adjust its own weights to get closer to the right answer next time.

### **Why did it unlock something?**

It was the first functional **Neural Network**. It proved that a machine could "learn" a classification task through trial and error without a human programmer explicitly defining the features of the object. It shifted the goal of AI from "encoding knowledge" to "simulating biology." The New York Times at the time called it "the embryo of an electronic computer that [the Navy] expects will be able to walk, talk, see, write, reproduce itself and be conscious of its existence."

### **What wouldn't exist without it?**

* **The "Connectionist" Movement:** The Perceptron is the direct ancestor of the "weights and biases" architecture used in every modern neural network.
* **The XOR Crisis & The AI Winter:** In 1969, Minsky and Papert proved a single-layer Perceptron couldn't solve a simple "Exclusive OR" (XOR) problem. This critique was so devastating it effectively shut down neural network research for over a decade—setting the stage for the **Backpropagation** breakthrough we discussed earlier, which solved the "hidden layer" problem.
* **Computer Vision:** Every time an AI "sees" an object today, it is using a vastly scaled-up version of the simple weighted-input system Rosenblatt pioneered in 1958.
