# Use an appropriate base image (e.g., Node.js)
FROM node:21

# Set the working directory
WORKDIR /app

# Copy package.json and install dependencies
COPY package.json ./
RUN npm install

# Copy the rest of the server files
COPY . .

# Expose the server port
EXPOSE 3001

# Start the server
CMD ["npm", "run", "start"]
