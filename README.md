# messages
Storing messages to use between different services

# How to generate:
Using gradle:

    ./gradlew clean build

For Python:
using pip (haven't tested):

    pip install grpcio
    pip install grpcio-tools
    python -m grpc_tools.protoc -I. --python_out=. --grpc_python_out=. src/main/proto/messages/drawgenertaor/*.proto