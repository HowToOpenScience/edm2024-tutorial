# Requirements for the Tutorial

## Pre-Survey

Please make sure to fill out the pre-survey as least one week prior to the conference start date: by July 1^st^, 2024. This may affect some aspects of the presented tutorial.

Link: [https://forms.gle/5S1qjpBZy7ADtXB57](https://forms.gle/5S1qjpBZy7ADtXB57)

## Visual Studio Code

## [Visual Studio Code (VSCode)][vsc]

Visual Studio Code is a rich text editor created by Microsoft commonly used for programming and integration. Users can build extensions for better support of a particular file. There are other rich text editors or IDEs used by other researcher; however, this tutorial will be centered around using VSCode.

VSCode is available under a [Microsoft Software License][vsc-terms]; however, it can be built manually under the [MIT License][vsc-license].


### Installation

You can download VSCode here: [https://code.visualstudio.com/download](https://code.visualstudio.com/download)

### Recommendations

We also recommend installing the following extensions for the tutorial. If you do not know how to install extensions, follow these instructions: [https://code.visualstudio.com/docs/editor/extension-marketplace](https://code.visualstudio.com/docs/editor/extension-marketplace)

> Name: Docker  
> Id: ms-azuretools.vscode-docker  
> Description: Makes it easy to create, manage, and debug containerized applications.  
> Version: 1.28.0  
> Publisher: Microsoft  
> VS Marketplace Link: [https://marketplace.visualstudio.com/items?itemName=ms-azuretools.vscode-docker](https://marketplace.visualstudio.com/items?itemName=ms-azuretools.vscode-docker)

> Name: Remote Development  
> Id: ms-vscode-remote.vscode-remote-extensionpack  
> Description: An extension pack that lets you open any folder in a container, on a remote machine, or in WSL and take advantage of VS Code's full feature set.  
> Version: 0.25.0  
> Publisher: Microsoft  
> VS Marketplace Link: [https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.vscode-remote-extensionpack](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.vscode-remote-extensionpack)

## Docker

Docker is a combination of open source projects used to create and manage applications. One of the core features of Docker is the development and distribution of containers: a snapshot of the current working environment, such as an OS. These are particularly useful to ship alongside existing materials such that the user is able to use your environment for reproducibility or replicability of the available research. We will be using Docker to create and distribute containers for the existing papers, so it is highly recommended to download and set up.

Docker is provided under the following [Terms of Service][docker-terms] with its consumed projects under the [Apache-2.0 License][docker-license] and others.

### Installation

You can download Docker through the Docker Desktop application: [https://docs.docker.com/desktop/](https://docs.docker.com/desktop/)

For Linux Users, if you wish to only install the engine, you may do so through the Docker Engine instructions: [https://docs.docker.com/engine/install/](https://docs.docker.com/engine/install/)

### Recommendations

While this will be reviewed in the tutorial, it is recommended to have a better sense of how permissions work within the containerized application and how it communicates with the host machine.

* Windows: [https://docs.docker.com/desktop/windows/permission-requirements/](https://docs.docker.com/desktop/windows/permission-requirements/)
* macOS: [https://docs.docker.com/desktop/mac/permission-requirements/](https://docs.docker.com/desktop/mac/permission-requirements/)

Linux users may also want to do some post-installation steps to have a better experience with the docker environment: [https://docs.docker.com/engine/install/linux-postinstall/](https://docs.docker.com/engine/install/linux-postinstall/)

[vsc]: https://code.visualstudio.com/
[vsc-terms]: https://code.visualstudio.com/License
[vsc-license]: https://github.com/microsoft/vscode/blob/main/LICENSE.txt

[docker]: https://www.docker.com
[docker-terms]: https://www.docker.com/legal/docker-terms-service
[docker-license]: https://www.docker.com/community/open-source
