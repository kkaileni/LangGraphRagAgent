# LangGraphRagAgent
A Rag agent that analyzes company healthcare policy and website to answer questions , code is based on the freecodecamp tutorial : https://github.com/iamvaibhavmehra/LangGraph-Course-freeCodeCamp/tree/main 

Run Using after the setup below :

```zsh
python TestAgent.py
```

## Getting Started (zsh/Mac)

### Using pyenv and uv

#### 1. Clone the Repository

```zsh
git clone https://github.com/kkaileni/LangGraphRagAgent.git
cd LangGraphRagAgent
```

#### 2. Install pyenv (if not already installed)

```zsh
brew update
brew install pyenv
```

Add the following to your `~/.zshrc` if it's not already there:

```zsh
export PYENV_ROOT="$HOME/.pyenv"
export PATH="$PYENV_ROOT/bin:$PATH"
eval "$(pyenv init --path)"
eval "$(pyenv init -)"
```
Restart your terminal or source your `~/.zshrc`:

```zsh
source ~/.zshrc
```

#### 3. Install Python Version

```zsh
pyenv install 3.12.6
pyenv local 3.12.6
```

#### 4. Install uv

```zsh
pipx install uv           # Recommended, or:
pip install --user uv
```

If you don't have pipx, install it with:

```zsh
brew install pipx
pipx ensurepath
```

#### 5. Set Up Virtual Environment with uv

```zsh
uv venv .venv
source .venv/bin/activate
```

#### 6. Install Dependencies

```zsh
uv pip install -r requirements.txt
```

#### 7.  Set up Environment Variables

If you need API keys (such as for OpenAI), create a `.env` file in the root directory:

```zsh
echo "OPENAI_API_KEY=your_openai_key" > .env
# Add other variables as needed
```
