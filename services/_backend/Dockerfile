FROM cusspvz/node:0.12.7

ENV CHANGE_DATE="16-Dec-2015"

ADD backend /backend/

RUN npm install -g swagger
RUN cd /backend && npm install

ENTRYPOINT ["swagger", "project", "start", "/backend"]

EXPOSE 10010
