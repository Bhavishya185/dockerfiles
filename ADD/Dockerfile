FROM almalinux:9
RUN dnf install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html
ADD https://raw.githubusercontent.com/Bhavishya185/expense-ansible-roles-tf/refs/heads/main/roles/backend/meta/main.yaml /usr/share/nginx/html/index.html
CMD ["nginx", "-g", "daemon off;"]