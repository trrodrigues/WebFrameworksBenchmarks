```
wrk -t 2 -c 100 --latency -d 60s <URL>
```

## JSON Scores:
```
---------------------------------  --------
Spray: ..........................  55735.21
RestExpress: ....................  54036.10
Play Framework (spray): .........  44483.06
Clojure http-kit ................  38907.40
Play Framework: .................  38015.35
Node.js: ........................  25835.20

```

## Plain Text Scores:
```
---------------------------------  --------
Spray: ..........................  73857.30
Clojure http-kit ................  64745.66
Play Framework: .................  50746.09
Node.js: ........................  28926.99

```