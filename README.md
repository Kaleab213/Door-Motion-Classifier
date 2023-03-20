# Door-Motion-Classifier
motion detection embedded machine learning model.

# Exported dataset for Kal / industrial-motion-classifier

To import this data into a new Edge Impulse project, either use:

* The Edge Impulse CLI (https://docs.edgeimpulse.com/docs/edge-impulse-cli/cli-overview), run with:

    edge-impulse-uploader --clean --info-file info.labels

* Or, via the Edge Impulse Studio. Go to **Data acquisition > Upload data**.

This project is all about detecting different types of movements in a door - including when it is already closed, opening, or being knocked on.
To do this, I have created three separate classes - "closed", "opening", and "knocking" - each of which is detected with high accuracy using the sensors. However, sometimes the door may move in an unexpected way, which can make it difficult to classify its movements accurately. That's why I have also created an "anomaly" class, which helps to classify any unpredictable movements.
I have used my phone as the data collection and deployment tool, since I cannot afford an Arduino microcontroller.
