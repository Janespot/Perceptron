# Training a Perceptron
This is a JavaScript code to train an AI Perceptron

### Key point
- A **perceptron** is the smallest unit of a Neural Network
- To tune a perceptron:
  - Adjust the learning rate
    > index.js
    ```
    //Initial values
    const numPoints = 500;
    const learningRate = 0.00001;
    ```
  - Increase the number of training data i.e. `numPoints` variable in our case
    > index.js
    ```
    //Initial values
    const numPoints = 500;
    const learningRate = 0.00001;
    ```
  - Increase the number of training iterations i.e. the loop with `j` variable in our case
  - > index.js
    
    ```
    for (let j = 0; j <= 10; j++) {
      for (let i = 0; i < numPoints; i++) {
          ptron.train([xPoints[i], yPoints[i]], desired[i]);
      }
    }
    ```
