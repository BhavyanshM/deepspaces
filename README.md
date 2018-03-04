# Deep Spaces
## Inspiration
Students in college, employees in companies, workers at construction sites, airplanes at the airport - all of them require parking services of some form or the other. With the ever increasing number of vehicles all around us, the available parking slots in campuses have become successively difficult to find. Especially when there are scheduling and logistic time-constraints involved

## What it does
Deep Spaces uses a deep learning technique called Mask-RCNN to track cars (can be easily extended to other types of vehicles) in a campus parking lot, and instructs/informs them about available parking locations at the parking lots of any campus.

## How we built it
A trained Mask-RCNN was deployed using Keras and Tensorflow deep learning frameworks. This deep model was then fed with a stream of real-time video from a camera looking over a parking lot. The locations of the vehicles tracked by the MRCNN were used to build a notification and recording system for the availability and other statistics about the parking slots and the cars that have parked in those locations.

## Challenges we ran into
Setting up an applications with multiple Microservices and several other moving parts was a heck of a challenge to integrate together. HTTP requests needed to be directed and redirected to enable proper flow of data through the entire application system.

## Accomplishments that we're proud of
The Mask-RCNN works flawlessly and produces a clean mask over the pixels for any car located in a parking lot. The Google Maps API was used very efficiently to display the available and taken parking slots.

## What we learned
A great amount of Microservices Architecture, Android Programming using HTTP requests and using the Google Maps API for Javasctipt. NodeJS was used significantly to build the backend microservices.

## Author
Bhavyansh Mishra

## Contributors
Nathan Cooper
Keenal Shah
Wenwen Xu
