## Environment

- pyenv

```bash
// pyenv 설치
brew install pyenv
brew install pyenv-virtualenv

// 종속성 패키지
brew install openssl readline sqlite3 xz zlib

// python 설치
pyenv install 3.11

// 환경변수 추가
echo 'export PATH="$HOME/.pyenv/bin:$PATH"' >> ~/.zshrc
echo 'eval "$(pyenv init -)"' >> ~/.zshrc
echo 'eval "$(pyenv virtualenv-init -)"' >> ~/.zshrc
source ~/.zshrc

// pyenv 설치 확인
pyenv version

// 프로젝트 생성
pyenv virtualenv 3.11 llm-application
pyenv local llm-application




```

- python 3.11.9

