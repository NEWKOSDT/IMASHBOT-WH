FROM fusuf/whatsasena:latest

RUN git clone https://github.com/BOT-k2/IMASHBOT-WH /root/WhatsAsenaDuplicated
WORKDIR /root/WhatsAsenaDuplicated/
ENV TZ=Europe/Istanbul
RUN npm install supervisor https://github.com/BOT-k2/IMASHBOT-W
RUN yarn install https://github.com/BOT-k2/IMASHBOT-W
RUN git clone https://github.com/BOT-k2/IMASHBOT-W

CMD ["node", "bot.js"]
