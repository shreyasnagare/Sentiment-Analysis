# Sentiment-Analysis

## Docker Hub Images
- https://hub.docker.com/repository/docker/shreyasnagare/sentiment-analysis-frontend
- https://hub.docker.com/repository/docker/shreyasnagare/sentiment-analysis-webapp
- https://hub.docker.com/repository/docker/shreyasnagare/sentiment-analysis-logic


## Steps
- Clone application on local machine.
- Install JDK and Maven.
- Build the JAR file for the web application.
- Push all three images to docker hub.
- Copy the tags to Google Container Registry.
- Create cluster in Google shell.
- Enable kubectl.
- Use images on Google Container Registry to create deployments
- Use the exposed port on the external IP (80, so no need to put the port) to reach the frontend of the application.
