## How to build

This is configured to auto-build on every push in the scottyak/pdgl-competition-image Docker Hub repo,
so it shouldn't be necessary to build it yourself.
But in case that fails, here's how to do it from the command line:

    export IMAGE_NAME=scottyak00/pgdl-competition-image:$(date +%Y%m%d-%H%M%S)
    docker image build -t $IMAGE_NAME .
    docker image push $IMAGE_NAME 
