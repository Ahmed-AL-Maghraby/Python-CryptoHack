# Python-CryptoHack

## Convert To ASCII

```python
alpha = [99, 114, 121, 112, 116, 111, 123, 65, 83, 67, 73, 73, 95, 112, 114, 49, 110, 116, 52, 98, 108, 51, 125]

for c in alpha:
    print (chr(c),end='')
```

## Convert Hexa To ASCII

```py
data = "63727970746f7b596f755f77696c6c5f62655f776f726b696e675f776974685f6865785f737472696e67735f615f6c6f747d"
data2 = bytes.fromhex(data).decode('ASCII')
print (data2)
```


## Base64 Encode

```py
import base64
data = b'Hello, world!'
encoded = base64.b64encode(data)
print(encoded)
```

## Base64 Decode

```py
import base64
data = b'SGVsbG8sIHdvcmxkIQ=='
decoded = base64.b64decode(data)
print(decoded)
```
































