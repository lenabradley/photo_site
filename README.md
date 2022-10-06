photo site
----

Lektor-based static site for viewing photo collections and albums

# Initial Setup
* Setup python3 environment
* clone this repo
* Install Lektor https://www.getlektor.com/
* Install s3 plugin `lektor plugins add lektor-s3`
# Serve site locally
```bash
lektor serve
```
Site is now available at [http://localhost:5000/](http://localhost:5000/). Site will dynamically rebuild whenever files change

# Build static site
e.g. for publishing
```bash
lektor build
```

# Deploy to AWS S3
```bash
lektor deploy s3
```