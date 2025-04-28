# npm-ci-sonar

NPM Continuous Integration SonarQube action

- checkout
- kt-actions/npm-run-script
  - setup node environment (kt-actions/setup-node-minmax, use cache)
  - install dependencies or restore from cache (uses cache)
  - run coverage tests (default: `npm run coverage`)
- sonarsource/sonarqube-scan-action
