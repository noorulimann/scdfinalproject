# frontend/Dockerfile
FROM node:18

WORKDIR /app

# Copy package.json and lock file first to install deps
COPY package*.json ./

# Install dependencies including react-scripts
RUN npm install

# Copy rest of the code
COPY . .

# Start the app
CMD ["npm", "start"]
