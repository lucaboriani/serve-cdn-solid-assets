# asset gateway on solid pod

A variation of [this tutorial](https://developers.cloudflare.com/workers/tutorials/configure-your-cdn/)
using inrupt's solid pod instead of google cloud :)

instruction:

signup for a solid pod fillowing [these instructions] (https://docs.inrupt.com/pod-spaces/getting-started-pod-inrupt-com/)

signup/login into cloudflare

go to dashboard , workers and setup your subdomain


in the cli :

install wrangler: https://developers.cloudflare.com/workers/cli-wrangler/install-update/

then

`wrangler login`

to insert the name of the pod owner:

`wrangler secret put POD_OWNER`

and insert the name you 





