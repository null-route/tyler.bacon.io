# tyler.bacon.io [![Build Status](https://travis-ci.org/null-route/tyler.bacon.io.svg?branch=master)](https://travis-ci.org/null-route/tyler.bacon.io)

Code for my static website. Likely to undergo frequent revision. May contain useful elements, may not.

The actual [site](https://tyler.bacon.io) is hosted via AWS S3 (configured as a webserver) and distributed via CloudFront. Travis CI is configured to "build" the site with each update to the master branch and then upload the resulting artifacts to the S3 bucket. Continuous deployment is neat.
