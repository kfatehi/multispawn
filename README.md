multispawn
==========

pass one or more commands to spawn. a parallel "&amp;&amp;" 

--

sometimes i want to run two commands in parallel, so i want to have a tool like this:

```
multispawn -e "watchy -w src/client -- npm run build" -e "node-dev server.js"
```

and have `multispawn` run both of them in parallel for me
