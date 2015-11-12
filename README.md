# u-got-issues
> a tool that downloads and lists the n oldest issues from a GitHub project

## Installation

If [available in Hex](https://hex.pm/docs/publish), the package can be installed as:

  1. Add issues to your list of dependencies in `mix.exs`:

        def deps do
          [{:issues, "~> 0.0.1"}]
        end

  2. Ensure issues is started before your application:

        def application do
          [applications: [:issues]]
        end
