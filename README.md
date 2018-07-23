# evnc: vnc server manager

This is a homebrew VNC server manager, for multiple users with an easy to set config file per user.

## Config file scheme

The config file needs to be in the user's home folder named `.evnc`.

Default appearence of the config file for now:
```
VNC_NUMBER={0-99};
VNC_RES_HOR={Number};
VNC_RES_VER={Number};
```

## Usage:
The main operation of the script is quite easy.
Each user should a configure file in his home directory called `.evnc` in accordance to the subsection above [here](#config-file-scheme).
Basic use:
```bash
evnc [status|start|stop|restart] [user list]
```
If no `USER LIST` is given the current user will be used.

# TODO:

- [x] Initial script
- [x] Alpha testing
- [x] Beta testing
- [ ] Done
