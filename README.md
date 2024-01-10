# internsctl
## Description
Introducing **Internsctl**, a versatile and efficient Linux command engineered to streamline system management. This command empowers users to effortlessly retrieve detailed file information, list users, create new users with customizable privileges, and set up 'sudo-only' users for enhanced security. Additionally, it provides comprehensive insights into system memory utilization and CPU information, delivering a holistic view of your system's performance. Simplify system administration and gain quick access to essential system details with **Internsctl**

## Installation

### 1. Clone the Repository

    git clone https://github.com/Sahil-Mahawer/Xenon_internsctl.git
    
### 2. Move Manual to the Man Pages Directory

    cp internsctl.1 /usr/share/man/man1/internsctl.1



### 3. Change to Man Pages Directory

    cd /usr/share/man/man1

### 4. Create Alias

    alias internsctl="./internsctl"

To make the alias permanent, you can add the above line to your shell configuration file (e.g., ~/.bashrc, ~/.bash_profile, or ~/.zshrc).

Now, you are ready to use internsctl!

    internsctl --version
    internsctl cpu getinfo
    internsctl memory getinfo
    internsctl user create <username>
Feel free to adjust the paths and instructions based on your specific setup and preferences.


## OUTPUT

     man internsctl
![Check Your Internet Connection](https://photos.app.goo.gl/BQF1WFUgXwwxPSKV7)
[Click to view if above image is not visible](https://photos.app.goo.gl/BQF1WFUgXwwxPSKV7)

    internsctl --version
![Check Your Internet Connection](https://photos.app.goo.gl/hymdFg2z1Ne9xzMA7)
[Click to view if above image is not visible](https://photos.app.goo.gl/hymdFg2z1Ne9xzMA7)

    internsctl cpu getinfo
![Check Your Internet Connection](https://photos.app.goo.gl/o9BRrddC5xY1hjBWA)
[Click to view if above image is not visible](https://photos.app.goo.gl/o9BRrddC5xY1hjBWA)

    internsctl memory getinfo
![Check Your Internet Connection](https://photos.app.goo.gl/UyyM6eDsFX25tGQVA)
[Click to view if above image is not visible](https://photos.app.goo.gl/UyyM6eDsFX25tGQVA)

    internsctl user create <<username>>
![Check Your Internet Connection](https://photos.app.goo.gl/tHn5K1UtwPohG3Un6)
[Click to view if above image is not visible](https://photos.app.goo.gl/tHn5K1UtwPohG3Un6)

    internsctl user list
![Check Your Internet Connection](https://photos.app.goo.gl/yfqdhf1qBg6C19LbA)
[Click to view if above image is not visible](https://photos.app.goo.gl/yfqdhf1qBg6C19LbA)

    internsctl user list --sudo-only
![Check Your Internet Connection](https://photos.app.goo.gl/QE6L3CpK2nLckjbb6)
[Click to view if above image is not visible](https://photos.app.goo.gl/QE6L3CpK2nLckjbb6)

    internsctl file getinfo <<file name>>
![Check Your Internet Connection](https://photos.app.goo.gl/geSrxKikPLNKWdzd7)
[Click to view if above image is not visible](https://photos.app.goo.gl/geSrxKikPLNKWdzd7)

    
 
    

