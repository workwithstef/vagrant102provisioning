bundle install

#### Provisions

shell 'provision' files are used to feed the software everything it needs at start up.

E.g. These are terminal commands that one would execute after initiating 'vagrant'. (written in the shell file)
```
sudo apt-get -y update

sudo apt-get -y install nginx

service nginx start

sudo apt-get -y install nodejs npm
```
Having the shell file and linking it using the following code below, would allow the code to automatically execute.

```
config.vm.provision "shell", path: "environment/provision.sh"
```
#### Rake Spec - tests assertions laid out in 'sample_spec.rb'
