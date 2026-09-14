# :link: Installation Instructions #

## Java

### Windows

1. Install [JDK](https://www.oracle.com/java/technologies/javase/javase-jdk8-downloads.html)
2. Set the environment variables.
    
   ![1](https://hackmd.io/_uploads/r1NpRuWclx.jpg)
   ![2](https://hackmd.io/_uploads/BkEaROZcxe.jpg)
   ![3](https://hackmd.io/_uploads/rkVTCd-cee.jpg)
    
3. Verify the installation.
    ```
    java -version
    javac -version
    ```

### macOS
1. Install Homebrew (if it is not already installed).
   Open Terminal and run:
    ```
    /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
    brew doctor
    brew update
    ```


2. Install the JDK with Homebrew.
    ``` 
    brew install openjdk@21
    ```
3. Set the environment variables.
    ```
    sudo mkdir -p /Library/Java/JavaVirtualMachines
    sudo ln -sfn "$(brew --prefix)/opt/openjdk@21/libexec/openjdk.jdk" /Library/Java/JavaVirtualMachines/openjdk-21.jdk
    ```
4. Verify the installation.
    ```
    java -version
    javac -version
    ```


## IDE - VS Code

1. Download [VS Code](https://code.visualstudio.com/).

   Windows configuration:
   
     ![Screenshot 2026-08-31 4:22:53 PM](https://hackmd.io/_uploads/Bk5_8YW5el.jpg)

2. Install the required extension.

    ![Screenshot 2026-08-31 4:26:14 PM](https://hackmd.io/_uploads/HkiLvYbcex.png)

    

## Git

### Windows
- Install [Git](https://git-scm.com/).
![1](https://hackmd.io/_uploads/B1K7x9W5le.jpg)

### macOS
```
brew install git
```


## Supplementary 

- [GitHub Copilot](https://code.visualstudio.com/docs/copilot/overview)
- [GitHub Education](https://william8510.pixnet.net/blog/post/576720564)
- [Google Gemini Education](https://gemini.google/tw/students/?hl=zh-TW)
- [Google Antigravity](https://gemini.google/tw/students/?hl=zh-TW)




