### tool-validation
This repository is used to validate tools in accordance FDA Quality Systems
Regulation 820.70(i) Automated Processes.

### Supported Systems
**tool-validation** has been tested with cygwin, linix, linux (mint), mingw32,
and wsl.

### Prerequisites
#### Applications
1. [git client](https://git-scm.com/book/en/v2/Git-and-Other-Systems-Git-as-a-Client)
2. [Ruby](https://www.ruby-lang.org/en/downloads/)
3. [Rake](https://ruby.github.io/rake/)
4. [Bundler](https://bundler.io) 

#### Clone Repositories 
1. [amber](https://github.com/Traap/amber)
2. [autodoc](https://github.com/Traap/autodoc) 
3. [docbld](https://github.com/Traap/docbld) 
4. [tlc-article](https://github.com/Traap/tlc-article) 
5. [tool-validaition](https://github.com/Traap/tool-validation) 
6. [quicksort](https://github.com/Traap/quicksort) 

### Validating Git Command Line Client
1. Meet all perquisites
2. Create shell
3. Move to $HOME/git **Note**  I clone all repositories to $HOME/git
4. Run [amber](https://github.com/Traap/amber)

```bash
cd $HOME/git/tool-validation/git-client

amber --verbose --nodryrun --writer=LaTeX --plan=command-line

docbld
```

### Review the git-client-validation.pdf
Report moved to **_build/git-client-validation.pdf**


### Project Management
This repository uses a SCRUM framework adapted to standard GitHub tooling. 

Please refer to my [Lightweight Project Management](https://github.com/Traap/lpm)
for the project management strategy I use.
