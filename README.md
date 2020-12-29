# Jai Development Vagrantfile

This is designed for bootstrapping a basic development box on Vagrant for use in Jai development.

## Set up
1. Download your own copy of the Jai compiler
1. Copy `Vagrantfile` to the base folder of the compiler (you can do a pull here, but... probably not a great idea)
1. You can just run `$ vagrant up` and the box should build, install some stuff, and link the compiler to `jai` make it easier
1. Your folder is not available at `/jai` on the guest box
1. Compile however you would normally, i.e. `jai helloworld.jai`
