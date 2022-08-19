# head-counter
Python OpenCV headcounter using camera feed

On WebCamS.py put your camera location as follows and then run WebCamS.py
st_str = "rtspsrc location=rtsp://p786:123@"+ip+":554/onvif1  ! queue ! rtph264depay ! queue !  decodebin ! queue !  videoconvert ! queue ! appsink"

