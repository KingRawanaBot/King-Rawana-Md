FROM fusuf/whatsasena:latest
##Queen Mizuki
RUN git clone https://github.com/KingRawanaBot/King-Rawana-Md /root/kingrawana
WORKDIR /root/kingrawana/
ENV TZ=Europe/Istanbul
RUN yarn add supervisor -g
RUN yarn install --no-audit

CMD ["node", "bot.js"]
