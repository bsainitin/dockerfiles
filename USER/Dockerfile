FROM almalinux:9
RUN dnf install nginx -y
RUN useradd nitin

# After executing All root privilage mandatory commands, Remove root privilage to container  

USER nitin
CMD ["sleep", "1000"]