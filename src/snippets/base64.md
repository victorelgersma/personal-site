# Decode base64 encoded string

One place we encounter this is how information is stored in a cookie

You can use the following script to decode a string

```py
import base64
encoded_string = "YjJkNDM5MTUtZTU0ZC00NDg5LWI1YWEtODhiY2U1NzI5ZTM0OjE3Mzk1NDk3MjIwNDQ="
decoded_bytes = base64.b64decode(encoded_string)
decoded_string = decoded_bytes.decode('utf-8')
print(decoded_string)
```

or you can use a site