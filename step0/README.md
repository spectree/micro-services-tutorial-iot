# Step 0

![image](../docs/step0.png)

In this step we have a simple front end for our system. Lets start off by installing some dependencies and running it. Do the following:

1. `cd frontend/api`
2. `npm install`
3. `cd ../public`
4. `bower install`
5. `node index.js`

Point your browser to http://localhost:10001. You should see a chart. Simple!

## Challenge
Next we are going to start up our database. To do this we are going to take advantage of Docker. If you haven't done this already you can fetch this container by running:

```
docker pull tutum/influx
```

Documentation on how to start the container can be found here: https://hub.docker.com/r/tutum/influxdb/

Your challenge is to startup the influxDB container. Once you have it running successfully open your browser and check out the influx web interface.