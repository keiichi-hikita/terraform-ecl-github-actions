FROM keiichihikita/terraform-ecl:latest

LABEL "com.github.actions.name"="terraform validate"
LABEL "com.github.actions.description"="Validate the terraform files in a directory"
LABEL "com.github.actions.icon"="alert-triangle"
LABEL "com.github.actions.color"="blue"

LABEL "repository"="https://github.com/keiichi-hikita/terraform-ecl-github-actions"
LABEL "maintainer"="Keiichi Hikita <keiichi.hikita@gmail.com>"

COPY entrypoint.sh /entrypoint.sh
ENTRYPOINT ["/entrypoint.sh"]
