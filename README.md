# Protobuf-AddressBook-Py 
'protobuf-addressbook-py' – A simple address book application which serialises & retrieves contact detail data to and from file using a Protocol Buffer with Python (Protobuf 3.17.3 / Protoc 3.17.3 / Python3.9).

# Setup

brew install protobuf

brew install protoc

protoc --version

mkdir protobuf-addressbook-py

python -m venv venv

source ./venv/bin/activate

python -m pip install protobuf

vim addressbook.proto

see python ref (https://developers.google.com/protocol-buffers/docs/tutorials)

protoc -I=./ --python_out=./ ./addressbook.proto
