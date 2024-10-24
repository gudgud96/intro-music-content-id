## Gentle Introduction to Music Content Recognition

Here I prepared two notebooks that showcase two different techniques to recognize music content:
- The first notebook uses audio fingerprinting based on matching peaks on a magnitude spectrogram, which is adapted from [Will Drevo](https://github.com/worldveil)'s [Dejavu](https://github.com/worldveil/dejavu) project. This method is good for recognising originals, with a certain level of robustness towards noise.
- The other one is a deep learning based cover song detection method, which is adapted from [Zhesong Yu](https://github.com/yzspku)'s [CQTNet](https://github.com/yzspku/CQTNet) project. This is a deep metric learning solution that outputs an embedding for a original/cover song, and minimizes their distance in a vector space. This method is good for recognising variants like covers and remixes.

Credits to both Will's and Zhesong's work for their inspiration when I was working on the topic of music content ID.
