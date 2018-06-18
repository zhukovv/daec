# Deep Autoencoder for Speech Enhancement

### Prerequisites
`sudo pip3 install tensorflow scikit-learn scipy h5py numpy tqdm pysndfx librosa==0.5.1`

`sudo apt-get install sox`

### Getting Started

1. Download free dataset from [VoxForge](http://www.repository.voxforge1.org/downloads/SpeechCorpus/Trunk/Audio/Original/16kHz_16bit/) for clean data. Here I would recommed download cmu_us_awb_arctic.tgz
2. Unzip clean dataset to /DeepDenoisingAutoencoder/data/raw/clean/
3. Download free dataset from [ESC-50](https://github.com/karoldvl/ESC-50) for noise data.
4. Move ESC-50-master/audio to /DeepDenoisingAutoencoder/data/raw/noise/
5. Set parameters in python/main.py
6. Run python/main.py
