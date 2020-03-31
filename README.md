# Overview

**Title:** Birdie Yellow  
**Category:** Web  
**Flag:** `libctf{1075f3d0-c51c-4ace-84f6-477dcebc75c0}`  
**Difficulty:** trivial

# Usage

The following will pull the latest 'elttam/ctf-birdie-yellow' image from DockerHub, run a new container named 'libctfso-birdie-yellow', and publish the vulnerable service on port 80:

```sh
docker run --rm \
  --publish 80:80 \
  --name libctfso-birdie-yellow \
  elttam/ctf-birdie-yellow:latest
```

# Build (Optional)

If you prefer to build the 'elttam/ctf-birdie-yellow' image yourself you can do so first with:

```sh
docker build ${PWD} \
  --tag elttam/ctf-birdie-yellow:latest
```
