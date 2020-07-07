# Ruby setup on MacOS if not using Docker
Necessary because gems cannot modify Ruby pre-installed files
```
echo '# Install Ruby Gems to ~/gems' >> ~/.zshrc
echo 'export GEM_HOME=$HOME/gems' >> ~/.zshrc
echo 'export PATH=$HOME/gems/bin:$PATH' >> ~/.zshrc
source ~/.zshrc
```

# Run docker image on ```localhost:4000```
```
docker-compose up -d
```