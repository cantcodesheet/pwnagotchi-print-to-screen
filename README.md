# pwnagotchi-print-to-screen
Sample code to show how to use a plugin to print directly to a Pwnagotchi screen.


Credit goes to:  hannadiamond
https://github.com/hannadiamond/pwnagotchi-plugins

It was their code that allowed me to figure out how to print text directly to the pwnagotchi screen as a lable and to the view area.

Setup

Copy over printp.py into your custom plugins directory

In your config.toml file add:

'''

main.plugins.printp.enabled = true
main.plugins.printp.t0_x_coord = 0
main.plugins.printp.t0_y_coord = 13  #places T0 label right above the name of pwnagotchi
main.plugins.printp.tn_x_coord = 65  #places Tn label adjacent/to the right of T0 label 
main.plugins.printp.tn_y_coord = 13  #places T0 label right above the name of pwnagotchi

'''

Restart your device to see your new stats!
