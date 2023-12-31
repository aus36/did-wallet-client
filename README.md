# DID Wallet Progressive Web Application

## Description
This progressive web application gives users the ability to input their information about themselves or the organization they represent, and the website will use this information to return a generated DID document back to them in compliant did:web specification. The application will also generate a basic sigchain verifiable presentation (SCVP) for the user, and allows verification between a hosted did document and verifiable presentation.

### Technologies
- React
- GitHub Pages (Hosting)

### Installation
1. Clone the repository
2. Navigate to the directory using ```cd did-generator```
3. This project uses node version 16, so ensure that you have nvm installed and run ```nvm use 16```
4. In a terminal, navigate to ```src/client``` and run ```npm install```
6. Run ```npm start``` to run the client
7. Navigate to localhost:3000 in your browser to view the application, if the previous command doesn't automatically do it
8. The results will be displayed in the console of the browser after clicking "Submit"
