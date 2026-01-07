FROM jenkins/jenkins:lts-jdk21

USER root

# Cài Docker CLI
RUN curl -fsSL https://get.docker.com | sh

# Cho user jenkins dùng được docker.sock
RUN usermod -aG docker jenkins

USER jenkins
