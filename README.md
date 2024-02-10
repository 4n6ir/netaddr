# netaddr

##### Cloud Development Kit (CDK) v2

```python
        region = Stack.of(self).region

        netaddr = _lambda.LayerVersion.from_layer_version_arn(
            self, 'netaddr',
            layer_version_arn = 'arn:aws:lambda:'+region+':070176467818:layer:netaddr:4'
        )
```

##### AWS Lambda Layer for Python Library

 1. ```cd bundle```
 2. ```mkdir python```
 3. ```cd python```
 4. ```pip3 install netaddr -t .```
 5. ```cd ..```
 6. ```zip -r netaddr.zip .```
 7. ```rm -R python```
