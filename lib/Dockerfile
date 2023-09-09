FROM quay.io/sampandey001/secktor
RUN git clone https://github.com/chamindulak/CHAMIYA-MD /root/chamindulak
WORKDIR /root/chamindulak/
RUN npm install npm@latest
RUN npm install
EXPOSE 8000
CMD ["npm", "start"]
