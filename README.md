# Ruby setup on MacOS (not necessary if you will use docker)

```
echo '# Install Ruby Gems to ~/gems' >> ~/.zshrc
echo 'export GEM_HOME=$HOME/gems' >> ~/.zshrc
echo 'export PATH=$HOME/gems/bin:$PATH' >> ~/.zshrc
source ~/.zshrc
```

# Run docker image on ```localhost:4000````
```
docker-compose up -d
```