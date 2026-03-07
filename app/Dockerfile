From node:18-alphine #Use node.js as the base image
WorkDir /app #Set working directory inside the conatiner
Copy package*.json ./ #Copy package.json and package-lock.json to the working directory
Run npm install #Install the dependencies
Copy . . #Copy the rest of the application code to the working directory
Expose 3000 #Expose port 3000 for the application
CMD ["node", "src/server.js"] #Command to run the application
