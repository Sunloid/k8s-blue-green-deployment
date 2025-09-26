# k8s-blue-green-deployment
## How it works inshort: 
- Blue and Green are both identical servers (initially)
- Blue has all the traffic and green is idle 
- Green is updated with the new version and after testing the traffic is slowly shifted from blue to green 
- Then blue is idle and it can be updated with ease 

This helps in updating applications with zero downtime. Making it more convienent for the user. 
One of the drawbacks is the fact that there would be 2 seperate servers running simultaneously and both need to updated one by one. 

