FROM quay.io/loki-xer/jarvis-md:latest
RUN git clone https://github.com/Kiranxer/Secktor-Md /root/neeli-md/
WORKDIR /root/neeli-md/
RUN yarn install --network-concurrency 1
CMD ["npm", "start"]
