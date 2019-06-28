FROM hashicorp/terraform:0.12.2

LABEL "com.github.actions.name"="terraform fmt"
LABEL "com.github.actions.description"="Validate terraform files are formatted"
LABEL "com.github.actions.icon"="terminal"
LABEL "com.github.actions.color"="blue"

LABEL "repository"="https://github.com/keiichi-hikita/terraform-ecl-github-actions"
LABEL "maintainer"="Keiichi Hikita <keiichi.hikita@gmail.com>"

COPY entrypoint.sh /entrypoint.sh
ENTRYPOINT ["/entrypoint.sh"]
