<div align="center">
  <h1>.github</h1>
  <p>Boring GitHub Actions & Workflows</p>

  <div>
    <a href="https://github.com/boringcodes/.github/commits" aria-label="Commitizen Friendly">
      <img src="https://img.shields.io/badge/commitizen-friendly-brightgreen.svg?style=flat-square">
    </a>
    <a href="https://github.com/boringcodes/.github/blob/master/LICENSE" aria-label="MIT License">
      <img src="https://img.shields.io/github/license/boringcodes/.github?color=brightgreen&style=flat-square">
    </a>
    <a href="https://github.com/boringcodes" aria-label="BoringCodes Verified">
      <img src="https://img.shields.io/badge/boringcodes-verified-brightgreen?style=flat-square">
    </a>
  </div>
</div>

## Features

Supported features:

- [x] **Workflows**
- [ ] **Actions**

Workflows grouped by steps:

- Test
  - [x] **lint-source.yml**: check code style & quality
  - [ ] **test.yml**: run unit test
- Build
  - [x] **build-source.yml**: build source
  - [x] **build-image.yml**: build Docker image
- Push
  - [x] **create-github-release.yml**: create GitHub Release
  - [x] **publish-npm.yml**: publish source to NPM Registry
  - [x] **push-dockerhub.yml**: push Docker image to DockerHub
- Deploy
  - [x] **deploy-cloudflare-workers.yml**: deploy source to CloudFlare Workers

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## Authors

[BoringCodes](https://github.com/boringcodes)

## License

[MIT](https://github.com/boringcodes/.github/blob/master/LICENSE)
