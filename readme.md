# Modules of Content

1. Install [Go programming language](https://go.dev/doc/install "Download and install - The Go Programming Language") in your operating system.

2. Intialize your own hugo mod

   ```shell
   hugo mod init <YOUR_OWN_GIT_REPOSITORY>
   # is you run the hugo new site <ISTE_NAME>
   ```

3. Intialize your own hugo mod

4. Add PaperMod in your `config.toml` file

   ```toml
   [module]
   [[module.imports]]
    path = 'github.com/hencter/content'
   ```

5. Update Module

   ```shell
   hugo mod get -u
   ```
