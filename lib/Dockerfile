FROM quay.io/sampandey001/secktor
RUN git clone https://github.com/vajirabot1/KING-VAJIRA /root/vajirabot1
WORKDIR /root/vajirabot1/
RUN npm install npm@latest
RUN npm install
EXPOSE 8000
CMD ["npm", "start"]
