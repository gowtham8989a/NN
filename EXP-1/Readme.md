import tensorflow as tf 

vector_a = tf.constant([1, 2, 3], dtype=tf.float32) 
vector_b = tf.constant([4, 5, 6], dtype=tf.float32) 

result = tf.add(vector_a, vector_b) 
result1 = tf.multiply(vector_a, vector_b) 
result2 = tf.subtract(vector_a, vector_b) 
result3 = tf.divide(vector_a, vector_b) 

print("Result of vector addition:", result.numpy()) 
print("Result of vector multiply:", result1.numpy()) 
print("Result of vector subtract:", result2.numpy()) 
print("Result of vector divide:", result3.numpy())