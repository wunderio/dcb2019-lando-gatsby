# Gatsby project in a Lando environment

- run `lando start`
- run `lando develop`

Sites are available at:

- Gatsby: <https://gatsby.lndo.site/>
- GraphiQL: <https://gatsby.lndo.site/___graphql>

## Tools

- `lando develop` - use for `gatsby develop` command,
- `lando gatsby <command>` - use for other Gatsby commands.

## Build steps

- install Gatsby
- create a Gatsby project: `gatsby new gatsby-default-starter https://github.com/gatsbyjs/gatsby-starter-default`
- add `.lando.yml` to project root

Original Gatsby readme: [README-gatsby.md](README-gatsby.md)
