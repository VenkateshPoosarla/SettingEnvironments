# Setting Mac Developer Environment
  This installs brew on mac
  
     /usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
     
# Setting Python environment on mac
    curl -L https://github.com/pyenv/pyenv-installer/raw/master/bin/pyenv-installer | bash
    CFLAGS="-I$(brew --prefix openssl)/include -I$(xcrun --show-sdk-path)/usr/include" \
    LDFLAGS="-L$(brew --prefix openssl)/lib" \
    pyenv install 3.6.6
    
## REFERENCE
  https://hackernoon.com/reaching-python-development-nirvana-bb5692adf30c
