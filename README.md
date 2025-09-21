# Fashion_MNIST
Fashion MNIST Classification with Neural Networks
<html>
<head>
    <meta charset="UTF-8">
    <title>Fashion MNIST Classification Model</title>
</head>
<body>
    <h1>Fashion MNIST Classification Model</h1>

    <p>
        This repository contains my first AI/deep learning project using <strong>TensorFlow</strong> and <strong>Keras</strong> to classify images from the <strong>Fashion MNIST dataset</strong>. 
        The dataset consists of <strong>70,000 grayscale images</strong> (28×28 pixels) across <strong>10 categories</strong> including T-shirts, trousers, pullovers, coats, sandals, shirts, sneakers, bags, and ankle boots.
    </p>

    <h2>Project Highlights</h2>
    <ul>
        <li>Data preprocessing: normalization and one-hot encoding of labels</li>
        <li>Visualization: class-wise sample images and distribution plots</li>
        <li>Neural Network Architecture:
            <ul>
                <li>Input layer (28×28) → Flatten</li>
                <li>Two hidden dense layers with ReLU activation</li>
                <li>Output layer with Softmax activation for 10 classes</li>
            </ul>
        </li>
        <li>Model training with varying hyperparameters (epochs, batch size, learning rate)</li>
        <li>Evaluation: training/validation accuracy & loss plots, confusion matrix</li>
    </ul>

    <h2>Usage</h2>
    <ol>
        <li>Clone the repository</li>
        <li>Install required packages: <code>tensorflow</code>, <code>numpy</code>, <code>matplotlib</code>, <code>pandas</code>, <code>seaborn</code></li>
        <li>Run <code>fashion_mnist_model.ipynb</code> to train and evaluate the model</li>
    </ol>

    <h2>Goal</h2>
    <p>
        This project demonstrates <strong>basic image classification with deep learning</strong>, 
        and lays the foundation for more advanced architectures such as <strong>CNNs</strong>.
    </p>
</body>
</html>
