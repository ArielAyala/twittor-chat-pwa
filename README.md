# Twittor:
A hero chat simulator. Using the characteristics of a PWA like:
- Location
- Camera
- PUSH notifications

It also has cache strategies using PouchDB and data synchronization when there is no connection.

Clone the project and remember that you must rebuild the node modules with the command:
```
npm install
```

Then, for run in production:
```
npm run start
```

For run in dev environment:
```
npm run dev
```

If you use docker run this for create an image from Dockerfile file that there is in the root project:
```
docker build -t pwatest .
```

Then run a container, run:
```
docker run -d -p 3000:3000 pwatest
```
