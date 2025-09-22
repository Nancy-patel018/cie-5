# Dockerfile for my-app
# Replace with your base image and build steps
# Use base image
FROM node:18-alpine

# Create app directory
WORKDIR /usr/src/app

# Copy files
COPY package*.json ./
RUN npm install
COPY . .

# Expose and run
EXPOSE 3000
CMD ["npm", "start"]
