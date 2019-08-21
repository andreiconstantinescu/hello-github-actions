FROM debian:9.5-slim

LABEL "com.github.actions.name"="Good news everyone!"
LABEL "com.github.actions.description"="Famous quote by the brilliant Professor Hubert J. Farnsworth."
LABEL "com.github.actions.icon"="mic"
LABEL "com.github.actions.color"="purple"

LABEL "repository"="https://github.com/andreiconstantinescu/hello-github-actions"
LABEL "homepage"="https://constantinescu.io"
LABEL "maintainer"="Andrei Constantinescu"

ADD entrypoint.sh /entrypoint.sh
ENTRYPOINT ["/entrypoint.sh"]