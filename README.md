Filesync is a bash script for sycronizing files on a mobile computer with a backup host.  It uses [Unison](https://www.cis.upenn.edu/~bcpierce/unison/) for syncronization.

## Featured

* Detects home network and connects to the appropriate address.
* Checks for, and will not sycronize, if files have been accidentally deleted.
* Unison uses secure SSH connections.

## Getting Started

You will need [Unison](https://www.cis.upenn.edu/~bcpierce/unison/).

On Debian based Linux systems, you can install unison with this command:

```shell
sudo apt-get install unison
```

Sample unison configuration files are provided [here](unison_config_examples).


## License

[GPL v3.](https://opensource.org/licenses/gpl-license)
