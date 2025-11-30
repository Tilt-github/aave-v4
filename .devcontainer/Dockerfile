FROM node
USER node
# Install Foundry
RUN curl -L https://foundry.paradigm.xyz | bash
ENV PATH="/home/node/.foundry/bin:${PATH}"
RUN /home/node/.foundry/bin/foundryup
