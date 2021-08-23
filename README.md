# protobuf-addressbook-py 
'protobuf-addressbook-py' – A simple Address Book application which serialises & retrieves contact detail data to and from file using a Protocol Buffer with Python (Protobuf 3.17.3 / Protoc 3.17.3 / Python3.9).

# setup

brew install protobuf

brew install protoc

protoc --version

mkdir protobuf-addressbook-py

python -m venv venv

source ./venv/bin/activate

python -m pip install protobuf

vim addressbook.proto

see python ref https://developers.google.com/protocol-buffers/docs/tutorials

protoc -I=./ --python_out=./ ./addressbook.proto
