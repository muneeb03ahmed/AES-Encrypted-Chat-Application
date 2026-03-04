# AES-Encrypted Chat Application

This is a real-time **AES-encrypted** chat application built using **React**, **Vite**, and **TailwindCSS**. It allows two users (Alice and Bob) to securely send and receive encrypted messages using **AES encryption**. The app demonstrates **end-to-end encryption**, **safe IV usage**, and **real-time chat** functionality using **TCP sockets**.

## Features
- **AES Encryption**: Messages are encrypted before sending and decrypted on the recipient’s end.
- **Secure Communication**: Only the intended recipient can decrypt the messages.
- **Real-time Chat**: Messages are exchanged between users using **TCP sockets**.
- **Toggle Ciphertext**: Option to view either the **plaintext** or **ciphertext**.

## Technologies Used
- **React**: Front-end library for building the user interface.
- **Vite**: Fast build tool for development.
- **TailwindCSS**: CSS framework for styling the application.
- **Node.js**: Server-side communication using TCP sockets.
- **AES Encryption**: For encrypting messages securely.
- **TCP Sockets**: For real-time messaging.

## Installation

### Prerequisites
- **Node.js** (version 18 or higher recommended)
- **npm** (comes with Node.js)

### Steps
1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/AES-Encrypted-Chat-Application.git
2. **Navigate to the project directory**:
   ```bash
   cd AES-Encrypted-Chat-Application
3. Install dependencies:
   ```bash
   npm install
4. Run the development server:
```bash
   npm start
```
***This will launch the application at http://localhost:8080***
### Usage
1. Alice and Bob can send encrypted messages to each other.
2. Messages are encrypted using AES before sending.
3. The ciphertext is displayed by default, but you can toggle between plaintext and ciphertext views.

### File Structure
src/: Contains all the application code (components, hooks, pages).
App.tsx: Main component that handles the chat interface.
index.tsx: Entry point of the application.
vite-env.d.ts: TypeScript definitions for Vite.
tailwind.config.ts: TailwindCSS configuration.

### Contributing
1. Fork the repository.
2. Create a new branch for your feature or bugfix.
3. Submit a pull request.

### License
This project is licensed under the MIT License.
