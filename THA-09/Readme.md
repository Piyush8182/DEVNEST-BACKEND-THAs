1. sequence matters a lot:
i.e. 1st we make a / route in the users.js route, then one step ahead and we give the /file route, next we give the /file/:name route.
The reason why / is at the last poistion is because it will be executed anytime the route hits /
