# UbuntuShellTweaks
A collection of tweaks and customizations for users transitioning to the Ubuntu shell, making their experience smoother and more intuitive.
# Ubuntu Shell Tweaks 🐧🚀

Making the transition to the Ubuntu shell? This repository aims to ease the switch by offering tweaks and customizations that will make your shell experience on Ubuntu more intuitive, especially if you're coming from a different OS like Windows.

## 📌 Featured Tweak: `cls` Alias for Ubuntu

If you've ever found yourself typing `cls` on Ubuntu (out of Windows habit) to clear the terminal and encountered an error, this tweak is for you.

### 🛠️ Setting Up the `cls` Alias on Ubuntu

1. Open your terminal.
2. Enter the command:
   
*******************
nano ~/.bashrc
*******************


4. Navigate to the end of the file.
5. Add the following line to create an alias for `cls`:
   
*******************
alias cls="clear"
*******************

6. Save with `Ctrl + O` and exit with `Ctrl + X`.

**Bonus**: For an organized `.bashrc`, add these lines:
****************************************************************
#Custom Aliases
#Add your aliases below

#Alias to clear the terminal (mimics Windows' cls)
alias cls="clear"

#End of Custom Aliases
****************************************************************



## 📝 Contributing

Got more tweaks to share? Feel free to make a pull request or open an issue to discuss potential additions!

## 📄 License

This project is open source and available under the [MIT License].
