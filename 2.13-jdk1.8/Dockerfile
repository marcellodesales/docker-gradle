FROM marcellodesales/gradle:2.13

USER root

# https://stackoverflow.com/questions/40122152/how-to-remove-entrypoint-from-parent-image-on-dockerfile/40122359#40122359
# Children images would get cache invalidated when used in the Dockerfile
# Disabling as the parent image defines it
ENTRYPOINT []
