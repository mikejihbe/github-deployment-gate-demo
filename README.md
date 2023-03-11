# Github Deployment Gate Demo

This is a sample application that demonstrates usage of the Sentry Github Deployment Gate integration application

# Setting up

```
# Copy the env file template to .env and fill it in
cp .env.tmpl .env

# Modify .env to have your real configuration
```

# Running the app locally

`node index.js`

# Build and run a container
````
docker build -t mikejihbe/github-deployment-gate-demo:v0.0.1
docker run -it -p 3000:3000 mikejihbe/github-deployment-gate-demo:v0.0.1
```