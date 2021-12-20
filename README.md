# Faces for Glass

WORK IN PROGRESS

This is a derivative work of the [Vision Quickstart](https://github.com/googlesamples/mlkit/tree/master/android/vision-quickstart),
modified for use on Google Glass, focusing entirely on the goal of recognising facial expressions.

I would like access to the software described [here](https://med.stanford.edu/news/all-news/2018/08/google-glass-helps-kids-with-autism-read-facial-expressions.html)
but it does not seem to be available, so I am making my own.

This is not a medical application, just a sample of coding for Google Glass.

## TODO
- Extract out the section of the code that performs facial recognision
- Extract a face for analysis by facial expression classification
- Perform offline facial detection eg https://youtu.be/T3yR9DZT2mQ
- Link each emotion to a colour and display overlayed on camera feed (debounce classification)

Training data: https://drive.google.com/file/d/1-ltonXDdaCc-iRyV79bPBxaWPpUn28wB/view
`label_to_text = {0:'anger', 1:'disgust', 2:'fear', 3:'happiness', 4: 'sadness', 5: 'surprise', 6: 'neutral'}`

