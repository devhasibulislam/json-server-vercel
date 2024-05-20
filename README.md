## Deploy JSON Server to Vercel

A template to deploy [JSON Server](https://github.com/devhasibulislam/json-server-vercel) to [Vercel](https://vercel.com), allow you to run fake REST API online!

Demo from this repository:

1. https://json-server-vercell.vercel.app
2. https://json-server-vercell.vercel.app/profile
3. https://json-server-vercell.vercel.app/comments
4. https://json-server-vercell.vercel.app/api/posts

![Powered by Vercel](https://images.ctfassets.net/e5382hct74si/78Olo8EZRdUlcDUFQvnzG7/fa4cdb6dc04c40fceac194134788a0e2/1618983297-powered-by-vercel.svg)

### How to use

1. Click "**Use this template**" or clone this repository.
2. Update or use the default [`db.json`](./db.json) in the repository.
3. Sign Up or login into [Vercel](https://vercel.com).
4. From the Vercel dashboard, click "**+ New Project**" then "**Import**" your repository.
5. In the "**Configure Project**" screen, leave everything default and click "**Deploy**".
6. Wait until deployment is done, and your own JSON server is ready to serve!

## Default `db.json`

```json
{
  "posts": [{ "id": 1, "title": "Hello World", "author": "Hasibul Islam" }],
  "comments": [{ "id": 1, "body": "Initial invention of JSON", "postId": 1 }],
  "profile": { "name": "Hasibul Islam" }
}
```

You can find the example code in [`api/server.js`](./api/server.js).

## Reference

2. https://vercel.com
1. https://github.com/devhasibulislam/json-server-vercel
1. https://shadowsmith.com/how-to-deploy-an-express-api-to-vercel
