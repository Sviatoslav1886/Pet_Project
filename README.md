# Pet_Project

### Briefly about each project:
1. [This assembly code](https://github.com/Sviatoslav1886/Pet_Project/blob/main/Arithmetic_expression_to_file.asm) calculates the expression F=(g+h)−(i+j) and performs file I/O operations using Linux system calls. The code first computes the sum of g and h, and the sum of i and j, then subtracts the latter from the former to obtain the result stored in F. It then opens a file specified by file_name, writes the value of F to this file, closes the file, and finally displays the value of F on the console followed by a newline character.
2. [This assembly code snippet](https://github.com/Sviatoslav1886/Pet_Project/blob/main/Arithmetic_%D0%BEperations.asm) demonstrates basic arithmetic operations (addition and subtraction) using x86 instructions. Specifically, it performs two operations: adding the values stored in memory locations B and C and then subtracting the value in memory location E from the result. The results are stored in variables A and D, respectively. The code uses Linux system calls (int 0x80) to output the results to the console. This example is useful for understanding low-level operations and system calls in assembly language, illustrating how to manipulate memory and perform arithmetic operations.
3. [This jupyter notebook](https://github.com/Sviatoslav1886/Pet_Project/blob/main/CNN.ipynb) contains a convolutional neural network (CNN) implemented in PyTorch for handwritten digit classification using the MNIST dataset. The code includes data loading, model definition, training, and testing procedures. The CNN architecture consists of two convolutional layers followed by max-pooling, batch normalization, and fully connected layers. The training loop computes loss, performs backpropagation, and updates the model's weights using stochastic gradient descent (SGD). The jupyter notebook also includes a function to predict handwritten digits using the trained model. Additionally, there's an example of predicting a custom image of a digit using OpenCV for preprocessing. The code demonstrates how to handle data loading, preprocessing, model training, evaluation, and inference for image classification tasks using PyTorch and popular computer vision libraries.
4. [This jupyter notebook](https://github.com/Sviatoslav1886/Pet_Project/blob/main/FFNN_diabetes.ipynb) contains a Python script demonstrating the implementation of a neural network for binary classification using PyTorch. The dataset used is the Pima Indians Diabetes Database, preprocessed using standard scaling and converted into PyTorch tensors. The script defines a custom Dataset class for data loading, a neural network model with fully connected layers and activation functions, and trains the model using stochastic gradient descent (SGD) with binary cross-entropy loss. The code showcases batch training with DataLoader, model definition, loss computation, and training loop over specified epochs, printing loss and accuracy metrics per epoch. This example serves as a practical illustration of building and training a neural network for binary classification tasks.
5. [This jupyter notebook](https://github.com/Sviatoslav1886/Pet_Project/blob/main/K_Means_Clustering.ipynb) analyzes a dataset of college information using pandas, seaborn, and scikit-learn. After loading and exploring the data, it visualizes relationships between variables through scatterplots, histograms, and cluster analysis using KMeans. The goal is to understand patterns and potentially classify colleges into private or non-private categories based on their characteristics. The script demonstrates data preprocessing, visualization, and basic machine learning clustering techniques, providing insights into college data and classification performance metrics like confusion matrix and classification report.
6. [This jupyter notebook](https://github.com/Sviatoslav1886/Pet_Project/blob/main/Learning_process.ipynb) demonstrates how to create and train a neural network for 3D data classification using the PyTorch library. First, it uses make_moons from sklearn.datasets to generate a test dataset stitched between two crescents. The data is then visualized using matplotlib. Next, the data is prepared for use in the neural network, namely converted into tensors. The neural network is created using the FeedForward class, which has a hidden layer with ReLU activation and an output layer with the softmax function for multi-class classification. After that, the optimizer and loss function are initialized and the model is trained for several epochs. During training, a graph is shown with the prediction accuracy at every thousand epochs, and the results are updated in real time.
7. [This x86 assembly code](https://github.com/Sviatoslav1886/Pet_Project/blob/main/ManagePersonalData.asm) for Linux creates a file named “result.txt”, writes the first name “Sviatoslav”, the last name “Beautiful” and a newline character (\n). Then it overwrites the last name with “Strong” and adds another newline character. The code uses Linux system calls to create a file, write to the file, and save changes to the file. This example demonstrates how to create and edit files.
8. [This code](https://github.com/Sviatoslav1886/Pet_Project/blob/main/Sentiment_Analysis_Project.ipynb) demonstrates the process of analyzing the sentiment of text movie reviews using NLTK (Natural Language Toolkit) and the VADER (Value Aware Dictionary and sEntiment Reasoner) method. First, it loads a dataset with movie reviews from the NLTK collection and performs data preprocessing, eliminating empty records. Next, it uses NLTK's SentimentIntensityAnalyzer to analyze the emotions of each review using the VADER method, which returns the components (negative, neutral, positive) and the total “compound” score for each review. After that, the overall sentiment score of each review is evaluated and categorized as “positive” or “negative” based on this score. Finally, the classification accuracy, classification report, and confusion matrix are output to evaluate the results of sentiment analysis of movie review texts.
9. [This x86 assembly code](https://github.com/Sviatoslav1886/Pet_Project/blob/main/Work_with_stack.asm) for Linux implements the calculation of the average value (arithmetic mean) of the elements of two arrays of integers. First, it declares two arrays array1 and array2 with the specified number of elements in each. After that, the average value for each of these arrays is calculated using the calc_average subroutine, which uses the stack to store local variables. After calculating the average values, the results are written to the file “results.txt” using the Linux system calls open, write, and displayed on the screen. The final result demonstrates how to work with the stack, arithmetic operations, and the use of system calls to interact with the file system and display.
10. [This code](https://github.com/Sviatoslav1886/Pet_Project/blob/main/tf_sentiment_model.ipynb) demonstrates the process of analyzing text tone with the BERT model using TensorFlow/Keras. First, the data is downloaded from Kaggle (train.tsv and test.tsv), after which it is processed and loaded into Pandas DataFrame objects. The text is transformed using the BERT tokenizer from the transformers library, and then converted to TensorFlow tensors (input_ids and attention_mask). The data is provided in Dataset format to train a BERT model with its own classification head. After the model is built, it is trained using the fit method, and after training, it is saved to disk for further use.
