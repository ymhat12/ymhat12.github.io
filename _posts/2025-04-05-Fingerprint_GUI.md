# Fingerprint Recognition GUI Interface

One of the tasks I was given was to implement a finger recognition algorithm via a GUI interface which would compare an enrolled fingerprint 
on a selection of enrolled fingerprints found within a database (template). This GUI has to give the ability to upload an image, enrol the 
image (fingerprint) with an associated name, and display the finger recognition comparision and accuracy measurement. 

## Method of Approach

1. The first aspect that was developed was the generalised GUI interface which was done through the use of tkinter.

2. The second step was to design an SQlite3 database capable of storing the template parameters of each fingerprint enrolment

3. Thirdly was to transfer the finger recogntiion code provided by Brian into the gui python file.

4. Lastly, Integrate all three to actively push each enrolled fingerprint through the processing to develop the comparitive data

Below is a screenshot of the GUI interface prior to fingerprint enrolment

![Image of Initial Fingerprint](/images/Fingerprint_Initial.png)


The below screenshot shows the GUI interface when the image is uploaded

![Image of Secondary Fingerprint](/images/Fingerprint_Second.png)


The below screenshow shows the GUI interface when the enrolment is complete

![Image of Final Fingerprint](/images/Fingerprint_Last.png)


