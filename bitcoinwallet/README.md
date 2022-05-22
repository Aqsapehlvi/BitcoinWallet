# BTC Web Wallet

This is a Bitcoin Wallet Web User Interface depending on bitcoin core application and JsonRPC 1.0. This application can be used as a manager UI to your bitcoin node, hot or cold wallet management purposes with a bootstrap powered nice looking HTML UI. This project is intended to create a good UEX for secure bitcoin cold and hot wallet usage.


To run on MacOs and Linux:

Install Homebrew

    /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"

install Bitcoin core

    brew install bitcoin 
       
Install DotNet Core

    Make sure you have .NET SDK 6.0.1 or application will not work!


To run:

    dotnet restore
    dotnet build
    dotnet run

finally:

     Go to https://localhost:9999