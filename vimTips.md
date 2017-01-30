The problem was git auto added ^M when cloning, solved by:

$ git config --global core.autocrlf input
