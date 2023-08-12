# WORKSTATION

Work station with everithing you need to build php projects. Everithing is
preconfigured and adaptable to sircumstances in order to save time and go
directly to the develpment. Works with Vagrant, makes virutalization easier.

## Prerequisits

 - Vagrant
 - Virtual Box

## Install

```bash
vagrant up
vagrant provision
```

## Usage

```bash
import foobar

# mount the virtual machine
vagrant up

# enter to the virtual machine by ssh
vagrant ssh

# power off the virtual machine
vagrant halt
```
## Challanges

I moved my vagrant.d to an external hardrive for space reasons
The external harddrive works with NTFS
The ssh key can be used because the permissions
Because the partition NTFS the permissions can't be changed
I decided move the ssh key to the place it belongs ~/.vagrant.d
In vagrantfile the new path isn't recognized
I added this variable at the begining `#{ENV['HOME']}`

## Author

Marti Adrogue
 - Twitter:
 - Github:

## Contributing

Pull requests are welcome. For major changes, please open an issue first
to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License

Copyright (c) 2023 Marti Adrogue

This project is [MIT](https://choosealicense.com/licenses/mit/) license
