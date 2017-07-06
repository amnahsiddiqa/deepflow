# Deepflow
This code contains the neural network implementation from the nature communication manuscript NCOMMS-16-25447A.

## Running the code.
To reproduce the results from the publication, change the PATH2MXNET variable in generate_record_files.sh to your mxnet home folder and run:

```
sh generate_record_files.sh
```

Run the neural network training & prediction:

```
python3.4 run.py
```

## System Requirements
The results were generated with python3.4 on an Ubuntu 14.04 machine.
Additional dependencies:

* mxnet 0.10.0
* numpy 1.12.0
* cv2   3.2.0



