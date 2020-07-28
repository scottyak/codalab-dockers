## How to build

    export IMAGE_NAME=scottyak00/pgdl-competition-image:$(date +%Y%m%d-%H%M%S)
    docker image build -t $IMAGE_NAME .
    docker image push $IMAGE_NAME 
