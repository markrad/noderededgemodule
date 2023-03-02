# Use node-red official containers
FROM nodered/node-red:3.0.1-18-minimal

WORKDIR /usr/src/node-red
USER node-red

# Install the dashboard extension
RUN npm install node-red-dashboard

# Install Azure IoT Edge Module nodes
RUN npm install node-red-contrib-azure-iot-edge-module
