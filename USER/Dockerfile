FROM almalinux:9
RUN dnf install nginx -y
# root access required
RUN useradd roboshop

USER roboshop
CMD ["sleep", "100"]
