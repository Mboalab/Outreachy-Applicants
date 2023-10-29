# Noise Reduction Techniques

I did a lot of research on the concept of noise reduction and i discovered that four methods by which noise can either be cancelled, reduced or suppressed. Combination of these methods makes it more efficient and proficient. 
These methods are in dirrect affluence with mostly tweaking of frequencies, audio waveforms and signals.

1. Equalizing: Equalization lets you adjust an audio's frequency response to produce desired effects or make up for flaws in playback or recording equipment. It entails altering the amplitudes of particular frequency bands in order to influence the sound's overall tonal quality.

Equalizers are of two types and they are either hardware equalizers(analog and software hardware qwualizers) and also software equalizers(software plugins and built-in signals): the two types of equalizers are 

a. Graphic equalizers

b. Parametric equalizers

2. Filtering : filtering is used to extract or modify certain parts of a signal while attenuating others. Filtering is frequently used in audio and sound processing to modify an audio signal's frequency content.
Filtering= is of different types and they include low pass, high pass, band pass, band stop filter and shelving filter. Filtering has different software and hardware prodcucts that performs it.


3. Deep Learning: In the context of noise reduction Deep learning is one of the most proficient ways for developing software products. This is how deep learning works

 1. Deep Learning Models: Audio signals can be trained to reduce noise using deep learning models, such as recurrent neural networks (RNNs) and deep neural networks (DNNs). These models are intended to generate clean or denoised audio as the output from noisy audio input.

 2. Training Data: A dataset of noisy audio recordings and the clean versions that correspond to them is needed to train deep learning models for noise reduction. A broad range of noise levels and types should be covered by this dataset. The diversity of the training data can be increased by employing data augmentation techniques.

 3. Loss Function: The difference between the clean and denoised audio is measured by a loss function, which is minimized by the model during training. One popular loss function for this is mean squared error, or MSE.

 4. Training Procedure: The model gains the ability to recognize and eliminate noise patterns from the input audio during training. Backpropagation is used to modify the weights and biases of the model in order to minimize the loss.

Conclusion: After training, the model can be applied to denoise previously unknown audio data. It receives audio that is noisy as input and outputs denoised audio. This procedure takes place in real-time or almost real-time for uses such as video conferences, live audio streaming, and more.


4. Machine learning: nIt uses the signal of the audio. Noise cancellation and suppression are greatly aided by machine learning, especially supervised learning, which uses models and algorithms to improve the quality of signal or audio data.

In this case, machine learning is used as follows:

1. Training Data: A significant amount of training data is needed to create noise suppression models that work well. Both equivalent clean versions and noisy sounds (or signal) should be included in this dataset. To guarantee that the model can handle a variety of real-world settings, the training data spans a wide range of noise types, intensities, and scenarios.

2. Feature extraction is the process of taking out characteristics from signal or noisy audio data. The machine learning model needs these properties in order to recognize patterns of noise. Time-domain and frequency-domain properties are common features.

3. Supervised Learning: Algorithms for supervised learning are commonly used to train noise suppression models. Maps of noisy data to clean data are learned by these algorithms. Neural networks, support vector machines, decision trees, and other machine learning techniques can all be used.

4. Model Selection: The problem's complexity and the data at hand influence the machine learning model that is selected. Simple linear models, for instance, might work well for straightforward noise reduction tasks, but deep learning models are better suited for handling more complicated situations.

5. Hyperparameter tuning: To get the best results, hyperparameters including learning rates, batch sizes, and network topologies must be tuned. The quality of noise reduction can be greatly affected by this tuning procedure.

6. Evaluation: To make sure the trained model generalizes effectively to new examples, it is tested using validation data. The quality of the denoised audio is frequently evaluated using metrics such as signal-to-noise ratio (SNR) and perceptual evaluation of speech quality (PESQ).


Now in the end because this is a mobile application running on the stack of flutter(Dart) i think the best way to go about noise cancellation/suppression/reduction is to  use the deep learning or machine learning mode of noise cancellation because they most preodominantly work and are built as software products. 

This will generally entail that a machine learning algorithm for this is built and not the usage of a library online or any hardware product.
