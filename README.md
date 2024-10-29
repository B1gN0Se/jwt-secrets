# jwt-secrets

JWT secrets that are useful for testing weak signing keys.

The way to run it is:

```sh
hashcat -a 0 -m 16500 eyJraWQiOiI1YmU0NzllZS04OTA1LTQyOWUtOWJjOS0zNTQ4OTE2MzhkZjgiLCJhbGciOiJIUzI1NiJ9.eyJpc3MiOiJwb3J0c3dpZ2dlciIsImV4cCI6MTczMDE3NDkxNSwic3ViIjoid2llbmVyIn0.UDjUF8_OzznLEESEgqDfuszQ16NrlgaL8Z6SsK-k2Lo jwt-secrets.list
```
