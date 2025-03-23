This is a keyd config that enables pressing CTRL + ALT instead of ALTGR to access the following symbols on a german keyboard: {}[]\~
It also remaps capslock to esc for use in neovim.

# 1. Install and enable keyd like described here: https://github.com/rvaiya/keyd
#
# 2. Use keyd -m and press any key on the keyboard you are using to get the ID of you specific keyboard
#
# 3. Copy this id to the line under [ids]. Now only this keyboard will be effected by the config.
#    If you break something you can fix your mistake by connecting an external keybaord, which wont be affected by this config.
#
# 4. Copy the contents of this file to /etc/keyd/default.conf
#
# 5. Reload keyd with sudo keyd reload
#
# 6. This process can be automated with an alias like this:
#    alias rekeyd='sudo cp ~/.config/keyd/keyd.conf /etc/keyd/default.conf && sudo systemctl restart keyd'
