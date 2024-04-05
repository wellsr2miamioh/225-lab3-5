# 225-lab3-5
CI/CD pipeline Example with Linting on DEV deployment, and to PROD if no linting errors.  Will likely fail on the first run.  Rename robots1.txt to robots.txt to remove the linting error.

Lints the HTML before deploying to a DEV environment using the __ClusterIP with Ingress__. Changes the Dockerfile to Dockerfile.build in preparation for future steps. Then deploys to a PROD environment at the __LoadBalanced IP__.

1) Create a new blank repository in your GitHub account using the lab name above.
2) Copy the URL of this repository and paste it into your repository.
3) View each file, and make changes where it is commented.
4) Run your pipeline.
5) Demonstrate your changes to the code in your video, and show the resulting web page.
