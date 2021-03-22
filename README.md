# ReutersOptimization

About this project:

I developed a tool that automatically categorizes Reuters Newswire articles.

Final Report:

My detailed analysis is available in Reuters Final Report.pdf

Data source:

I used the TensorFlow/Keras's built in dataset. The python import code is as follows:

(data, labels), (_, _) = tf.keras.datasets.reuters.load_data(
                                      path='reuters.npz', num_words=None, skip_top=0, maxlen=None, test_split=0,
                                      seed=113, start_char=1, oov_char=2, index_from=3)
                                      
Note: Please download this repo. Some files cannot display properly on GitHub. 



