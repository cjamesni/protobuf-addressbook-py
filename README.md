# protobuf-addressbook-py 
'protobuf-addressbook-py' – A simple Address Book application which serialises & retrieves contact detail data to and from file using a Protocol Buffer with Python (Protobuf 3.17.3 / Protoc 3.17.3 / Python3.9).

# setup

brew install protobuf

brew install protoc

vim addressbook.proto

see ref https://developers.google.com/protocol-buffers

protoc -I=./ --python_out=./ ./addressbook.proto
