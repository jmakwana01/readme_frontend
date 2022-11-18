## Building the source

### Prerequisites

1. Make sure you have [Git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git) installed.
2. Make sure you have [Node.js version v16.16.0.](https://nodejs.org/en/download/) installed.
3. Clone the repository

    ```bash
    git clone https://github.com/ZeroCodeLabs-OU/app.git
    ```
    Change the directory:
    ```bash
    cd app
    ```
    
    ### Install dependecy from package-lock.json
    ```bash
    npm install
    ```
    ### Running locally
    ```bash
    npm run start
    ```
    Running app frontend locally on [http://localhost:9000/](http://localhost:9000/)
    ![image](https://user-images.githubusercontent.com/87368354/202694494-076577c1-42f3-4c0f-8585-de91d578e7f4.png)
    
    ### Creates a dist directory  with a production build of your app
     ```bash
    npm run build
    ```
    
