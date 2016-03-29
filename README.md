# SemIoT Homepage

## How to deploy on a local machine

### Pre-requested

```bash

# if you are using other shell than Bash - replace .bashrc entries with you shell .rc

cd
git clone git://github.com/sstephenson/rbenv.git .rbenv
echo 'export PATH="$HOME/.rbenv/bin:$PATH"' >> ~/.bashrc
echo 'eval "$(rbenv init -)"' >> ~/.bashrc

git clone git://github.com/sstephenson/ruby-build.git ~/.rbenv/plugins/ruby-build
echo 'export PATH="$HOME/.rbenv/plugins/ruby-build/bin:$PATH"' >> ~/.bashrc
source ~/.bashrc

rbenv install -v 2.2.3
rbenv global 2.2.3

```

### Launch
```bash
sudo gem install jekyll

jekyll serve --config _config.yml,_config.development.yml
```
Port 4000.
