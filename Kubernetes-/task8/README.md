I used command "kubectl rollout undo deployment nginx-app -n app-a" to roll back and also changed the version in my yaml file and both of the ways work.
I used command " kubectl describe deployment nginx-app -n app-a" to check for the version of the nginx image.
