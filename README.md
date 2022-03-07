## Useful VirtualBox CLIs 


## First VirtualBox has to be started in the host system

    $sudo virtualbox &

    - Make it as a service to start at bootup

## List ALL VMS

    $sudo vboxmanage list vms

## List Running VMS 

    $sudo vboxmanage list runningvms

## Start VM     [ vm_name: ubuntu]

    $sudo vboxmanage startvm ubuntu

## Shutdown VM  [ vm_name ubuntu ]

    $sudo vboxmanage controlvm ubuntu acpipowerbutton

## PowerOFF VM  [ vm_name: ubuntu]

    $sudo vboxmanage controlvm ubuntu poweroff

