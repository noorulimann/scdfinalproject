# Use official Node.js image
FROM node:18
#1235
# Set working directory
WORKDIR /app

# Copy backend's package.json
COPY package*.json ./
#aaa
# Install backend dependencies
RUN npm install

# Copy backend files
COPY . .

# Expose backend port
EXPOSE 5000

# Start the backend server
CMD ["node", "server.js"]
