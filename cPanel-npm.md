Installing and set up `nvm` to manage Node.js versions on cPanel (via: ssh):

1. **Install `nvm`**:
   To install `nvm`, you can use the following command in your terminal:

  'curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.38.0/install.sh | bash'

   After running this command, close and reopen your terminal session, or run:

  'source ~/.bashrc'

   This will load `nvm` into your current shell session.

2. **Verify `nvm` Installation**:
   To verify that `nvm` has been installed correctly, you can run:

  'nvm --version'

   This should display the version of `nvm` installed.

3. **Install Node.js with `nvm`**:
   Once `nvm` is installed, you can use it to install Node.js versions. For example, to install Node.js version 14, you can run:

 'nvm install 14'

 After installing, you can switch to that version using:

  'nvm use 14'

4. **Setting Up `nvm` Automatically**:
   To ensure that `nvm` is available in every terminal session, you can add the following line to your shell profile configuration file (e.g., `~/.bashrc`, `~/.bash_profile`, `~/.zshrc`):

   'source ~/.nvm/nvm.sh'

After setting up `nvm`, you should be able to use it to manage Node.js versions without encountering the "nvm: command not found" error. If you're still having issues, double-check that you've followed the installation steps correctly and that the `nvm` script is being sourced in your shell configuration file.

5. **Validate Installation**

   'nvm --version'
   
   **or**

   'npm --version'
