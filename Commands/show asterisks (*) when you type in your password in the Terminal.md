We will open the “/etc/sudoers” file and change a setting to customize the length of the grace period. To begin, press Ctrl + Alt + T to open a Terminal window. Type the following command at the prompt and press Enter.

$ sudo visudo

Type your password when prompted and press Enter. Notice that no asterisks are displayed when you enter your password.

A file opens directly in the Terminal window using the Nano text editor. Use the arrow keys on your keyboard to move the cursor to the end of the following line:

Defaults         env_reset

Change the line by adding “,pwfeedback” to the end of the line.

Defaults                 env_reset,pwfeedback

You can also press Enter after “env_reset” to make a new line and type the following on the new line:

Defaults                 pwfeedback

NOTE: The space between “Defaults” and “pwfeedback” should be a tab.
