### Commit Message Format
Each commit message consists of a **header**, a **body** and a **footer**.  The header has a special
format that includes a **type**, a **scope** and a **subject**:

```
<type>(<scope>): <subject>
<BLANK LINE>
<body>
<BLANK LINE>
<footer>
```


### Type
Must be one of the following:

* **feat** (+ :rocket:  ): A new feature
* **fix** (+ :wrench: ): A bug fix
* **docs** (+ :memo: ): Documentation only changes
* **style** (+ :dress: ): Changes that do not affect the meaning of the code (white-space, formatting, missing
  semi-colons, etc)
* **refactor** (+ :zap: ): A code change that neither fixes a bug nor adds a feature
* **perf** (+ :runner: ): A code change that improves performance
* **test** (+ :eyes: ): Adding missing tests
* **chore** (+  :tea: ): Changes to the build process or auxiliary tools and libraries such as documentation
  generation
