## Setting Up the Netflix Clone Application Using AWS and Docker 

Follow these steps to set up and run the Netflix clone application on your local machine:

### 1. Update Package List

Run the following commands to update the package list on your system:

```bash
sudo apt update
```

### 2. Install Required Packages

Install the necessary packages and dependencies for the application using the following command:

```bash
sudo apt install -y curl dirmngr apt-transport-https lsb-release ca-certificates
```

### 3. Install Node.js

Install Node.js, a JavaScript runtime, with the following commands:

```bash
curl -sL https://deb.nodesource.com/setup_12.x | sudo -E bash -
sudo apt install -y nodejs
```

### 4. Install Project Dependencies

Navigate to the project directory and install the project-specific dependencies:

```bash
npm install
```

### 5. Start the Application: Works

To start the Netflix clone application, use the following command:

```bash
npm start &
```

### 6. Optional & May Not Work: Serve the Built Application

If you want to serve the built version of the application, you can use the `serve` package. First, install it globally:

```bash
npm install -g serve
```

Then, serve the built application on port 4000:

```bash
serve -s build -l 4000
```

Now you should be able to access the Netflix clone application by opening your web browser and navigating to `http://localhost:4000`.

Enjoy exploring the Netflix clone!

Step 01:- Basic Requirement
* Go to AWS console and provision one Instance.
* Netflix-Project — (AMI- Ubuntu 22.04, Type- t2.medium)
<img width="956" alt="image" src="https://github.com/paulsantosh263/DevOps-Netflix-Clone-Project/assets/58592054/adce974e-d405-4e34-b335-2d62c40e6f5d">


<img width="944" alt="image" src="https://github.com/paulsantosh263/DevOps-Netflix-Clone-Project/assets/58592054/0c49f36b-1a9b-4996-b47a-ac78423b23dc">
Sucessfully Loged-In

<img width="953" alt="image" src="https://github.com/paulsantosh263/DevOps-Netflix-Clone-Project/assets/58592054/62722930-c3f8-4eb5-9364-05e2086c9195">


