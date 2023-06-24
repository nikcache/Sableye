@nik_cache

FoulPlay is the error handling and logging component of Sableye. Nothing too complex, but 
very important to track and log errors such that bugs can be caught.

Component is responsible for:
    - - Error Logging and handling
    - - Garbage collection
        - - Deleting private information after use
            - - such as
                - - video recordings
                - - pictures
    - - End-to-End Tests which can test the entire flow through components
        - - MeanLook -> Detect -> NastyPlot
    