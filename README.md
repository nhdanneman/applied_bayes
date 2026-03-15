# Applied Bayesian Analysis Short Course
Welcome. This will be good, but casual. Promise.

## What is this, and who is it for?
Some text.

## Getting started
1. Clone the repo: https://github.com/nhdanneman/applied_bayes
2. Make sure you have Docker or colima on your machine
3. Set up the container by executing these things in the root directory
docker build -t bayes-course .
docker run --rm -it -p 8888:8888 -v "$(pwd)":/work bayes-course
4. Open the notebook environment in a browswer: http://localhost:8888/lab
5. You stop the environment with Ctrl+C in the terminal running the container
6. If you run the container again, you don't need to build it again.
docker run --rm -it -p 8888:8888 -v "$(pwd)":/work bayes-course


