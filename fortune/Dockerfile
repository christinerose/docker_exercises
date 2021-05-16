# Very first created docker image
# A Docker file is a recipe of how to make an image
# Capture oft used commands to make recipe, so you don't have to type it in every time
# ... and so others can use it on their system
# Makes something repeatable

FROM ubuntu:latest
# (starter image)

RUN apt-get update
RUN apt-get install -y fortune-mod fortunes
# (commands to run)

CMD ["/usr/games/fortune"]
# (what program to run)


