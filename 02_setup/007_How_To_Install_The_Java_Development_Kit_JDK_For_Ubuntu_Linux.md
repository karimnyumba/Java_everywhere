# How To Install The Java Development Kit (JDK) For Ubuntu Linux

The Java Development Kit (JDK) is a software development environment used for developing Java applications and applets. In this tutorial, we will show you how to install the Java Development Kit (JDK) on Ubuntu Linux.

## Prerequisites

Before you start with the installation, make sure you have the following:

- A running instance of Ubuntu Linux
- A user account with sudo privileges
- A terminal window / command line (Ctrl-Alt-T)

## Step 1: Update the system

First, it is always a good idea to update the system to the latest version. Open a terminal window and run the following commands:

```
sudo apt-get update
```

```
sudo apt-get upgrade
```


## Step 2: Install the Java Development Kit (JDK)

To install the JDK on Ubuntu Linux, follow these steps:

1. Open a terminal window.
2. Type the following command to install the OpenJDK package:

```
sudo apt-get install openjdk-11-jdk
```


3. Type `Y` and press `Enter` to confirm the installation.
4. The installation process will start and may take a few minutes to complete.

## Step 3: Verify the installation

To verify that the installation was successful, open a terminal window and type the following command:

```
java -version
```


If the installation was successful, the version of the JDK will be displayed in the terminal window.

## Conclusion

In this tutorial, we have shown you how to install the Java Development Kit (JDK) on Ubuntu Linux. You can now use the JDK to develop Java applications and applets on your Ubuntu Linux system.

