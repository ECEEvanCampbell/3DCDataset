# 3DCDataset
Dataset used in many works by Ulysse Côté-Allard et al.. All credit goes to the authors for the collection of this dataset. This repo just was created for ease of cloning the dataset. The dataset was originally collected in study [1], and subsequently used in study [2]. All studies that make use of this dataset should properly credit [1].

# Dataset Description
Ten bipolar EMG channels and a 9 axis IMU are used for this dataset.
EMG Signlas are filtered with analog anti-aliasing filter (low pass cutoff: 460 Hz). 
EMG signals are acquired at 1000 Hz.

Eleven motion classes were recorded (no motion, radial deviation, wrist flexion, ulnar deviation, wrist extension, supination, pronation, power grid, open hand, chuck grip, pinch grip).
Gestures were recorded for 5 seconds per elicitation, where a cycle was completed (each motion performed) in a continuous 55 seconds.
Four cycles were recorded in one session (4 repetitions of each gesture, 220 seconds continuous recording), followed by a 5 minute break, then another four cycles (4 more repetitions).

For analysis purposes, the first 4 repetitions are considered the "training" set and the last 4 repetitions are considered the "testing" set.




# References
[1]
@article{cote2019deep,
  title={Deep learning for electromyographic hand gesture signal classification using transfer learning},
  author={C{\^o}t{\'e}-Allard, Ulysse and Fall, Cheikh Latyr and Drouin, Alexandre and Campeau-Lecours, Alexandre and Gosselin, Cl{\'e}ment and Glette, Kyrre and Laviolette, Fran{\c{c}}ois and Gosselin, Benoit},
  journal={IEEE transactions on neural systems and rehabilitation engineering},
  volume={27},
  number={4},
  pages={760--771},
  year={2019},
  publisher={IEEE}
}

[2]
@article{cote2020interpreting,
  title={Interpreting deep learning features for myoelectric control: A comparison with handcrafted features},
  author={C{\^o}t{\'e}-Allard, Ulysse and Campbell, Evan and Phinyomark, Angkoon and Laviolette, Fran{\c{c}}ois and Gosselin, Benoit and Scheme, Erik},
  journal={Frontiers in Bioengineering and Biotechnology},
  volume={8},
  pages={158},
  year={2020},
  publisher={Frontiers Media SA}
}

