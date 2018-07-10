# Conversion VM

## Build steps

### Centos

1. Get Centos minimal installation image (no cloud one)

2. Create a VM locally with empty Volume and mounted installation image

3. Start it and append boot options to use kickstart script (press Tab in boot menu and append text bellow - shortened link to this repo centos ks file)

```
ks=http://goo.gl/K5MgPC
```

4. Wait until installation is done and VM reboots

5. Conversion VM is ready, you can make a snapshot or upload its Volume to OpenStack
