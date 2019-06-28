FROM hashicorp/terraform:0.12.2

LABEL "com.github.actions.name"="terraform init"
LABEL "com.github.actions.description"="Run terraform init"
LABEL "com.github.actions.icon"="download"
LABEL "com.github.actions.color"="blue"

LABEL "repository"="https://github.com/keiichi-hikita/terraform-ecl-github-actions"
LABEL "maintainer"="Keiichi Hikita <keiichi.hikita@gmail.com>"

COPY entrypoint.sh /entrypoint.sh
ENTRYPOINT ["/entrypoint.sh"]
