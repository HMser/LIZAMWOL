FROM fusuf/whatsasena:latest

RUN git clone https://github.com/HMser/LIZAMWOL /root/WhatsAsenaDuplicated
WORKDIR /root/WhatsAsenaDuplicated/
ENV TZ=Asia/Kolkata
RUN npm install supervisor -g
RUN yarn install --no-audit
RUN git clone https://github.com/HMser/Media-1
RUN git clone https://github.com/Chunkindepadayali/media

CMD ["node", "bot.js"]
