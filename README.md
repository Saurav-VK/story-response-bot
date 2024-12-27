# story-response-bot
An NLP project using Deep Learning with TensorFlow and Keras. Employs LSTM Neural Networks to generate answers from input stories and queries, showcasing contextual understanding and language modeling.

2. Set Up the Environment
Ensure Python is installed (version 3.7 or above is recommended). Install the required libraries:
```bash
pip install tensorflow keras pickle-mixin

3. Input Format
Prepare your input data in the following format:
- A **story** and a **query** should be provided as a list in square brackets, separated by a comma.  
Example:
```python
input_data = ["Once upon a time, there was a brave knight.", "Who was brave?"]
```
