# Installation
### LLVM
Downloading llvm on macOS:
```
brew install llvm
```

Add the `llvm-config` tool to your system's PATH environment variable.
Open up the `.zshrc` file
```
code ~/.zshrc
```
then add this:
```
export PATH="/opt/homebrew/opt/llvm/bin:$PATH"
```
then refresh:
```
source ~/.zshrc
```

Confirm that `llvm-config` works now via
```
llvm-config --cxxflags
```
### Bison
```
brew install bison
```
Add Bison to your path:
```
code ~/.zshrc
```
then add this:
```
export PATH="/opt/homebrew/opt/bison/bin:$PATH"
```
then refresh:
```
source ~/.zshrc
```

### Flex
```
brew install flex
```

Add Flex to your path:
```
code ~/.zshrc
```
then add this:
```
export PATH="/opt/homebrew/opt/flex/bin:$PATH"
```
then refresh:
```
source ~/.zshrc
```
