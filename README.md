# DECO-classification-project
A group of high school student interns and I are working together to classify DECO app produced images. We use various different strategies in our algorithms to separate types of images. 

This script is used in conjuction to the plotBlobsH script (look here for it https://github.com/ibok/DECOEventType_beta). Once the plotBlobsH script is run, it outputs both a file for event classifications and a file for x and y centers of the "events" that the script finds. 

This script looks through duplicate coordinate values in the xandyCent.out file that plotBlobsH produces. If there are duplicate blob centers, then this script classifies the "event" as a hotspot. This is not an event, it is a camera sensor malfunction. 

The hotspotsclass.py script outputs any event_IDs with hotspots into hotspotsclass.out along with the not-rounded x and y coordinates. Look for this file in the folder you are in. 
