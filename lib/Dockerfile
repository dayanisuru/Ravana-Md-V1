FROM quay.io/sampandey001/secktor
RUN git clone https://github.com/dayanisuru/Ravana-Md-V1 /root/dayanisuru
WORKDIR /root/dayanisuru/
RUN npm install npm@latest
RUN yarn install --network-concurrency 1
EXPOSE 8000
CMD ["npm", "start"]
