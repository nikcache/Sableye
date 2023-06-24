@nik_cache

Detect is Sableye's component responsible for detecting the presence of configured inputs
from the user. This could involve deep learning and CNNs, so this will involve some complex
pytorch implementations. 

Component is responsible for:
    - - Taking normalized data from MeanLook and reshaping data to fit NN inputs later
    - - Building NN capable of recognizing
        - - hand gestures
        - - finger gestures
            - - might be a little more difficult depending on reliabiliy of MeanLook
    - - Detecting which partiucular gesture was made from a library of pre-configured gestures
        - - This should be able to be easy configured by the user
            - - Record yourself doing something a few times
                - - Use that as data
    - - Sending gesture prediction to NastyPlot, the component for automation

*FoulPlay is the component that's responsible for error handling of MeanLook