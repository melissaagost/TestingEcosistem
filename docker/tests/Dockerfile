FROM node:20-alpine
WORKDIR /tests
RUN npm i -g newman newman-reporter-allure
COPY tests ./tests
VOLUME ["/tests/allure-results"]
CMD ["newman","--version"]
