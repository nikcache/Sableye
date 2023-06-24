@nik_cache
MeanLook is Sableye's component thats responsible for Visual detection

Component is responsible for:
    - - Taking live input from a webcam
        - - Must be able to "handoff" if another application requests to use the webcam
    - - Real time detection of
        - - Hands
        - - Fingers
    - - Cleans and Filters the data to send to the next component, Detect
    - - Exported data from this module is shaped as the following
        - - Data model TBD
    - - Keeping all the other components alive as we want the latency to be minimal
        - - Note that latency minimizations will have to be made in each component as well

*FoulPlay is the component that's responsible for error handling of MeanLook
