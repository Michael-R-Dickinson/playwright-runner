GET base 64 var:

```
SCRIPT_B64=$(base64 -i /Users/big_m/Documents/Code/FasTest/backend/testjs/tests/test.spec.js)
```

Write to file:

```
echo $SCRIPT_B64 | base64 -d > test.spec.js
```
