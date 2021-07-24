release: npx prisma migrate deploy --schema=./prisma/schema.prisma
web: npx prisma generate --schema=./prisma/schema.prisma && tsc && node ./dist/server.js