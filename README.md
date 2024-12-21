# RNN-- Simple Recurrent Neural Networks

Simple RNN: Processes sequence data, passing hidden states to the next timestep. Prone to vanishing gradient issues.

![image](https://github.com/user-attachments/assets/e99bbd8b-b069-482c-b6a3-db89f8da9d75)

Short-Term Memory: Simple RNNs are better at remembering recent information, but their ability to retain information from earlier parts of a sequence quickly diminishes. This is due to the "vanishing gradient problem."

Vanishing Gradient Problem: During backpropagation, gradients (signals that guide the learning process) can shrink exponentially as they flow through multiple layers of the network. This makes it difficult for the RNN to learn long-range dependencies because the gradients for earlier time steps become vanishingly small.

In essence, a simple RNN's memory is quite short-lived. It can effectively remember information from a few preceding words or time steps, but capturing dependencies across longer sequences is challenging.

![image](https://github.com/user-attachments/assets/23c35e9a-17ac-4d6b-b400-e4416e97574f)

Implementation:

Install Libraries

pip install tensorflow keras

Data preparation

![image](https://github.com/user-attachments/assets/1b137146-7932-4433-bb94-c3092c526bae)

RNN

![image](https://github.com/user-attachments/assets/561d7925-c3ed-46ce-8af0-6ae1925f1041)





