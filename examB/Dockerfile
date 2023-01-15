FROM node:12-alpine
RUN apk add --no-cache python2 g++ make git
RUN git clone https://github.com/docker/getting-started.git
WORKDIR /getting-started/app
RUN npm install
CMD ["node", "src/index.js"]
EXPOSE 3000

# A Dockerfile must begin with a FROM instruction. The FROM instruction initializes a new build stage 
# and sets the Base Image for subsequent instructions.
# FROM can appear multiple times within a single Dockerfile to create multiple images 

# The RUN instruction will execute any commands in a new layer on top of the current image and commit the results.

# The WORKDIR instruction sets the working directory for any RUN, CMD, ENTRYPOINT, COPY and ADD instructions that follow it in the Dockerfile. 
# If the WORKDIR doesn’t exist, it will be created even if it’s not used in any subsequent Dockerfile instruction.

# There can only be one CMD instruction in a Dockerfile.
# The main purpose of a CMD is to provide defaults for an executing container. 

# The EXPOSE instruction informs Docker that the container listens on the specified network ports at runtime

# I created this comment to check the pull request and merge branches.