ARG VARIANT="16-bullseye"
FROM mcr.microsoft.com/vscode/devcontainers/typescript-node:0-${VARIANT}

# [Optional] Uncomment this section to install additional OS packages.
# RUN apt-get update && export DEBIAN_FRONTEND=noninteractive \
#     && apt-get -y install --no-install-recommends <your-package-list-here>
RUN git clone https://github.com/GostarehNegar/tomcat-bot.git
CMD [ "bin/bash" ]