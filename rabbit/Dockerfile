FROM node:18-alpine

# Set working directory
WORKDIR /app

# Copy package files
COPY package*.json ./

# Install dependencies
RUN npm install

# Copy application code
COPY . .

# Expose port (optional, for documentation)
EXPOSE 3000

# Default command (can be overridden in docker-compose)
CMD ["node", "send.js"]