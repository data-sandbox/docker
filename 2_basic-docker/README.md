### Notes on how to build the image and run the container:
1. `cd` into the `2_basic-docker` directory containing all docker files
2. Build the image with `docker build . -t tagname`
3. Run the image and map the host's port 8000 to the container's port 5000 with `docker run --publish 8000:5000 tagname`
4. Open an new terminal and run `curl localhost:8000` to see the container response.