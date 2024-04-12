# Testing
This is the first testing repository
apiversion: v1
kind: pod
metadata:
  name: label-demo
  labels:
    environment: production
	app: nginx
spec:
  containers:
  - name: nginx
    image: nginx:1.14.2
	ports:
	- containerport: 80
