# EMG

The EMG signal file uploaded (raw1.xlsx) is a 4000 sample long signal, that is 4 sec long signal of Gastronemius Medialis. 

Begin with the file named RAW_SIGNAL: it deals with the evaluation and visualization of raw EMG signal

Then move on to Filtering file: This deals with usage of low pass, high pass and band pass filters to limit the EMG between the useful range of (20 to 450)Hz

Then move to Feature Engineering file: It deals with the cleaning, processing , windowing and extraction of features.


Filtering Range:
(20 to 450)Hz

Windowing:
100ms: Electromechanical Delay(EMD) ranges between 30 to 100 ms varying with respect to muscles.

EMD: Its the delay between initialization of EMG signal to the begininng of the actual motion. Understanding and windowing this time gap can help us understand the intension of motion.



