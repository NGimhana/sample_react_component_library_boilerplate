## Installation

**Using NPM:**

Since this Plugin is not officially published yet please follow below steps for local testing.
1. Install Node Modules for web pack dependencies.
    ```
    npm install
    ```
    
1. In the root of your NPM package, do this to build.
    ```
    npm run build
    ```

2.  Install the Package into local node_modules.
    ```
    npm install . -g
    ```
3. Create a symlink package that points to your working directory.
    ```
    npm link
    ```
    
4. Local NPM Package installation. Use this command in relevant React project directory. This will link global node_module plugin directory to project's local node_modules directory.
    ```
    npm link oodt_fm_plugin_sample