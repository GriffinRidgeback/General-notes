# Hadoop Commands
Have to pay attention to the format of the commands; they are long, complicated, and are prone to misstyping and missing parameters.

# Using GitHub
Track work in .md files, issues in issuses tab.

# Fixing Java problems in R

Set LD_LIBRARY_PATH to

```
export LD_LIBRARY_PATH=$JAVA_HOME/jre/lib/server
```

Then
```
sudo ln -s $(/usr/libexec/java_home)/jre/lib/server/libjvm.dylib /usr/local/lib
sudo R CMD javareconf -n
install.packages("rJava",type='source')
```
