# baixar java
https://www.oracle.com/br/java/technologies/downloads/#java21

# Mudar versão atual
```
sudo update-alternatives --config java
sudo update-alternatives --config javac
```

# Mudar JAVA_HOME
```
nano ~/.bashrc
```

```
export JAVA_HOME=/usr/lib/jvm/(caminho jdk)
export PATH=$JAVA_HOME/bin:$PATH
```
