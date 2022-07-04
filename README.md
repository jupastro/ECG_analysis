# ECG_analysis

In this repository I've presented a little example on how to work with ECG recordings. In the colab notebook uploaded an example of the code as well as the pipeline followed can be observed. 
I've also uploaded a .html report extracted from the database generated.

The main topics that I've worked in have been:
* Database extraction from the .hea files
* Loading recording with the wtdb package
![Reading](example_of_recording_reading.png)
* Processing recordings sequentally by bandpass filtering, derivative filtering, squaring and integration
![Processing](example_steps.png)
* Detection of QRS complexes
![QRS_1](Example_of_QRS_detection.png)
![QRS_2](Example_of_QRS_detection_0.png)

* Extracting RR, QR , RS and QRS measurements and poincaré plots

![QRS_1](Example_poincaré_1.png)
![QRS_2](Example_poincaré_2.png)
* Report
[click here](DB_analysis.html)
* Future steps
![Happy Christmas](Christmas.png)
