docker run -d `
  --name mongo `
  -p 27017:27017 `
  -v mongo-data:/data/db `
  mongo


docker start mongo
docker ps

mongodb://localhost:27017/nota
