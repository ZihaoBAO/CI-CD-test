FROM node:18

WORKDIR /app

# 创建一个假 package.json，避免 npm 报错
RUN echo '{"scripts": {"start": "echo Backend running..."}}' > package.json

CMD ["npm", "start"]
