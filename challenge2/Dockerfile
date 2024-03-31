# Use the official Node.js 14 image as a parent image
FROM node:14

# Set the working directory in the container to /app
WORKDIR /app

# Copy the package.json and package-lock.json from your host to the current directory in the container
COPY package*.json ./

# Install any dependencies
RUN npm install

# Copy the rest of your working directory's contents into the container at /app
COPY . .

# Inform Docker that the container listens on the specified network ports at runtime.
EXPOSE 8080

# Define the command to run the app using CMD which defines your runtime
CMD ["node", "server.js"]
