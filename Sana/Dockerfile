FROM Afx-Abu/Sana:test

RUN git clone https://github.com/Afx-Abu/Sana-Mwol/ /Abu/Sana
WORKDIR /Abu/Sana 
ENV TZ = Asia/Kolkata
RUN npm install supervisor -g
RUN yarn install --no-audit

CMD ["node", "Sana.js"]
