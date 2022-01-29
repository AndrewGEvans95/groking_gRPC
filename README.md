Step 1:

```

$ python3 -m venv venv
$ source venv/bin/activate  # Linux/macOS only
(venv) $ python -m pip install -r requirements.txt

```

Step 2:

```

python -m grpc_tools.protoc -I protobufs --python_out=. \
         --grpc_python_out=. protobufs/recommendations.proto

```