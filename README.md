hola- 👋 Hi, I’m @paco-thusday
quien te interesa?- 👀 I’m interested in Ricardo Quaresma ...
- 🌱 I’m currently learning ...
con quien piensas colaborar?- 💞️ I’m looking to collaborate on nadie  ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

// server.mjs
import { createServer } from 'node:http';

const server = createServer((req, res) => {
  res.writeHead(200, { 'Content-Type': 'text/plain' });
  res.end('Hello World!\n');
});

// starts a simple http server locally on port 3000
server.listen(3000, '127.0.0.1', () => {
  console.log('Listening on 127.0.0.1:3000');
});

// run with `node server.mjs`

<!---
paco-thusday/paco-thusday is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
