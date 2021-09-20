FROM fusuf/whatsasena:latest

RUN git clone https://github.com/BOT-k2/IMASHBOT-WH /root/WhatsAsenaDuplicated
WORKDIR /root/WhatsAsenaDuplicated/
ENV TZ=Europe/Istanbul
RUN npm install supervisor https://github.com/IMASHBOT-W/IMASHBOT-WH
RUN yarn install https://github.com/IMASHBOT-W/IMASHBOT-WH
RUN git clone https://github.com/IMASHBOT-W/IMASHBOT-WH

CMD ["node", "bot.js"]
