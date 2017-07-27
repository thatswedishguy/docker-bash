# docker-bash
A small bash function to easily run bash in a Docker container.

## Install
Put the `.bash_functions` file in your home directory.

Add the following to your `~/.bashrc` file;

```
if [ -f ~/.bash_functions ]; then
	. ~/.bash_functions
fi
```

Either run `source ~/.bashrc` or logout and log back in.

## Running
Execute `docker-bash <container-name>` to open a new bash inside your Docker container.

If you need to find your running Docker containers, run `docker ps`.
