# 225-lab3-5
CI/CD pipeline Example with Linting on DEV deployment, and to PROD if no linting errors.  Will likely fail on the first run.  Rename robots1.txt to robots.txt to remove the linting error.

Lints the HTML before deploying to a DEV environment using the __ClusterIP with Ingress__. Changes the Dockerfile to Dockerfile.build in preparation for future steps. Then deploys to a PROD environment at the __LoadBalanced IP__.
