# vscode-remote-graalvm
GraalVM development container for Visual Studio Code. Java, R, Python, Node, Ruby, WASM included.

## Setting up the development container

Follow these steps to open this sample in a container:

1. If this is your first time using a development container, please follow the [getting started steps](https://aka.ms/vscode-remote/containers/getting-started).

2. To use this repository, you can either open the repository in an isolated Docker volume:

    - Press <kbd>F1</kbd> and select the **Remote-Containers: Open Repository in Container** command
    - Then type: <code>yarncraft/vscode-remote-graalvm</code>
    - Choose the volume of preference
    - Wait for the container to start, and try things out!

   Or open a locally cloned copy of the code:

   - Clone this repository to your local filesystem.
   - Press <kbd>F1</kbd> and select the **Remote-Containers: Open Folder in Container...** command.
   - Select the cloned copy of this folder, wait for the container to start, and try things out!

## Get Started

Once you have this sample opened in a container, you'll be able to work with it like you would locally.

> **Note:** This container runs as a root user by default.

Some things to try:

1. **Java:**
   - Open `src/HelloWorld.java`.
   - You can press the <code>run-code</code> button to run the file
   - Or, you can open a terminal and write `javac src/HelloWorld.java && java HelloWorld`
   - Try adding some code and check out the language features.
2. **Java Native:** 
  - By default, GraalVM Native is installed
  - Open the src folder: `cd src`
  - Compile to Java Bytecode `javac HelloWorld.java`
  - Compile the Bytecode to a Native Image: `native-image HelloWorld`
  - Run the Native Image: `./HelloWorld`
3. **R**
   - Execute the script with `Rscript src/index.R`.
4. **Node**
   - Execute the script with `node src/index.js`.
   - Open up the browser and visit the website at `127.0.0.1:3000`
5. **Ruby**
   - Execute the script with `ruby src/index.rb`.
5. **Python**
   - Execute the script with `python src/index.py`.
