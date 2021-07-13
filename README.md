Note: If you get an error message (on a linux machine) similar to:

`command not found: lume`

Check your path by running

`echo $PATH`

The colon delimited list should have user/local/.deno/bin:$PATH if not you can easily add it by running:

`export PATH="/Users/yourUserName/.deno/bin:$PATH"`

Now, after running `echo $PATH` you should see .deno/bin in your path list.

[![Netlify Status](https://api.netlify.com/api/v1/badges/f3875b26-d036-4c91-80ca-fc6959069c03/deploy-status)](https://app.netlify.com/sites/gallant-wilson-75585d/deploys)