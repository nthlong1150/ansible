# Introduction
This repository provides Ansible playbooks for configuring Windows systems. The playbooks use tasks stored under `roles/set_windows` to perform typical setup operations such as configuring networking and installing features.

# Getting Started
1. Prepare an inventory. Copy `inventories/hosts_sample` to `inventories/hosts` and update it with the connection details for your Windows hosts.
2. Execute the playbook with:

```bash
ansible-playbook windows_setup.yml
```

# Build and Test
TODO: Describe and show how to build your code and run the tests. 

# Contribute
TODO: Explain how other users and developers can contribute to make your code better. 

If you want to learn more about creating good readme files then refer the following [guidelines](https://docs.microsoft.com/en-us/azure/devops/repos/git/create-a-readme?view=azure-devops). You can also seek inspiration from the below readme files:
- [ASP.NET Core](https://github.com/aspnet/Home)
- [Visual Studio Code](https://github.com/Microsoft/vscode)
- [Chakra Core](https://github.com/Microsoft/ChakraCore)