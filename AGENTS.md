# Repository agent guide

## Repository workflow and completion

This is the legacy Electron/React/Redux application. `browser/` contains UI/application logic, `locales/` translations, and Grunt/Webpack drive development and compilation. Use the checked-in Yarn classic lockfile and documented development toolchain: `yarn install --frozen-lockfile`, `yarn dev`, `yarn start`, `yarn compile`, `yarn lint`, and `yarn test` (AVA and Jest).

Follow `contributing.md`, code style, and the PR template. Use disposable notebook storage and synthetic notes so real user notes survive runtime checks. Bundle/unit success does not prove migrations or persistence; test changed storage behavior with fixtures. Preserve upstream contribution requirements rather than asserting legal acceptance for the user.

Continue the authorized change through relevant validation and repair of failures it causes; preserve unrelated work. Report checks actually run, commands only inspected, and exact missing prerequisites. Ask only when a material decision, missing authorization, or required input blocks progress; continue independent reversible work. Existing mandatory contribution and validation gates still apply.
