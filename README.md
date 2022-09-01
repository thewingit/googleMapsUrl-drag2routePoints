# googleMapsUrl-drag2routePoints
Python script to convert Google Maps URL which contains manually "dragged" points to an URL in which the drag points will appear as route intermediate points.

This way one can generate a customized route using Google Maps on the PC (on Desktop Chrome, the feature of manually "dragging" route points is available), then use the Python script to convert the URL, and finally send the custom route to the mobile phone.

Use the provided Pyhton script and just change the urlIn variable by pasting the URL from Google Maps. You should get the modified URL printed on std output, with the drag points now appearing as intermediate route points. You may want to adjust the transport type (i.e. car, bike etc) back to what you originally set. 
