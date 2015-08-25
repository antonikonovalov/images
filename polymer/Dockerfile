FROM node:0.12.7-onbuild

WORKDIR /var/cache/drone/src/src-tms.als.local/frontend/marketplace
ADD . /var/cache/drone/src/src-tms.als.local/frontend/marketplace
RUN npm install -g bower gulp
RUN npm install
RUN bower install --allow-root
