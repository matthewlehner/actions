FROM elixir:1.9-alpine

LABEL "repository"="https://github.com/matthewlehner/actions"
LABEL "homepage"="https://github.com/matthewlehner/actions/elixir"
LABEL "maintainer"="Matthew Lehner <matthew@mpl.io>"

LABEL "com.github.actions.name"="Elixir 1.9"
LABEL "com.github.actions.description"="An action for running Elixir commands"
LABEL "com.github.actions.icon"="code"
LABEL "com.github.actions.color"="purple"

RUN mix local.rebar --force
RUN mix local.hex --force

CMD ["iex"]