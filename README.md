## Building for production 🏗

To build a static site for production, or test locally how it works, run the
following command:

    npm run build

The exported site will be written to `out` folder. The contents of this folder 
can be deployed by serverless deployment platform such as [Netlify](https://www.netlify.com).
You can start a local server serving the static files from the `out` folder, for
example by installing and running `http-server`:

    npm install http-server -g
    http-server out
