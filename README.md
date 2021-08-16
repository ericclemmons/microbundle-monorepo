# Microbundle for Monorepos

A small reproduction of a bug where `import "./styles.css"` doesn't get externally generated to `dist/styles.css`.

## Getting Started

1. `yarn install`
1. `yarn workspace ui-react build`
1. Validate `ls -al packages/ui-react/dist/*.css` isn't empty