# Changelog

## 1.0.0 (2025-01-03)


### Features

* add a new parmater ([fb4298e](https://github.com/web4er/personal-agent/commit/fb4298e26581482b0f9d0b0d77c6c2f0694a967f))
* add multi handler mechanism ([563d69e](https://github.com/web4er/personal-agent/commit/563d69e05699ed3ba9f245eba496272fb5af642c))
* added knip reporter ([ec83511](https://github.com/web4er/personal-agent/commit/ec835115e4c09802206bfa951c40a0d58c6f3ead))
* hello-world ([90122fb](https://github.com/web4er/personal-agent/commit/90122fba3960036bcedee67eced6c5562d0ba59e))
* only the gobal name is considered for automatic deployment with wrangler ([dbb9b22](https://github.com/web4er/personal-agent/commit/dbb9b22049cdd45bbda0230b61a5095d73771ff5))
* schema validation ([82c2f88](https://github.com/web4er/personal-agent/commit/82c2f8863f87a0755566b6b46c541fbafa879fab))
* ubiquibot-logger ([3123d9d](https://github.com/web4er/personal-agent/commit/3123d9db8a97d7cdbb6c8d187cb469ee85c7833d))
* updated eslint to use flat-config file ([42a961d](https://github.com/web4er/personal-agent/commit/42a961d46625337df49f97b60d3fb00637ef92dc))
* url is added to the manifest.json if the plugin is a worker ([02b5a17](https://github.com/web4er/personal-agent/commit/02b5a170ddd4b83eabd0aa0cb370fc6a8b940e7d))
* worker deploy and delete ([88c6ebf](https://github.com/web4er/personal-agent/commit/88c6ebff580937ef4c1910d1e261eee57f458fec))


### Bug Fixes

* check for PAT value before creating octokit ([e7e3d7f](https://github.com/web4er/personal-agent/commit/e7e3d7fba259b3e5d0636ff01d71c00f4fd394bb))
* correct if condition & update logs ([800a017](https://github.com/web4er/personal-agent/commit/800a01767d53e688a9b5d4e799ec23b56c573542))
* drop db for each test to avoid duplicates ([fb0f9a8](https://github.com/web4er/personal-agent/commit/fb0f9a822c9fc8367b930cfe50c10f1e89420c68))
* fixed import for typebox and updated gitignore ([82ffa47](https://github.com/web4er/personal-agent/commit/82ffa47cdaedf03c90b1893d69784c710d0cfe3b))
* ignore auto generated coverage dir by eslint ([2a75673](https://github.com/web4er/personal-agent/commit/2a756733f47a4f4b027205eb090a77b9cc7f9f62))
* keep original comment in quote instead of code markdown ([2105add](https://github.com/web4er/personal-agent/commit/2105add7a96296190fc1f8efaa3dffb21573ca23))
* log types and minors ([bf6084f](https://github.com/web4er/personal-agent/commit/bf6084f23077aa7bd34ec1fedd1bdfc808fe2982))
* missing comma ([0c401b6](https://github.com/web4er/personal-agent/commit/0c401b65ec76469c60ca484e730b44a5ec3e47d7))
* read env from process ([052c935](https://github.com/web4er/personal-agent/commit/052c935e527cf85e6ab545f1506a2de7c90c4f41))
* receive all kernel data and respond with comment ([48d18ef](https://github.com/web4er/personal-agent/commit/48d18ef6023816e63c0d3c9e715e7c5d6cafc8a0))
* remove authToken from plugin inputs ([13c8ca8](https://github.com/web4er/personal-agent/commit/13c8ca81dcaa7d8a43491da577b286da1a972f9c))
* remove db type ([58db88f](https://github.com/web4er/personal-agent/commit/58db88f64850e79d46787c75612d5a3390bd1597))
* remove personal agent reference in reply ([bd33051](https://github.com/web4er/personal-agent/commit/bd330518585cdec2e0d84f29b2dee86a9f8a4e49))
* remove ubq_bot token and commit_hash ([1cb6b52](https://github.com/web4er/personal-agent/commit/1cb6b52793ff97a82d1c259287cfc7c00c79cca0))
* remove workflow env ref ([6ae1914](https://github.com/web4er/personal-agent/commit/6ae19148cf52376a5580b1a097dc572c146a3a2c))
* run jest wf on Knip complete ([9909633](https://github.com/web4er/personal-agent/commit/9909633c08df8250af7caccddcfe81b0973c7a9a))
* running full formatting checks ([8f5ce45](https://github.com/web4er/personal-agent/commit/8f5ce45a11f0698cc3f5bcaba2e22f13c8c24426))
* set env as object ([2fc6645](https://github.com/web4er/personal-agent/commit/2fc6645fe1e82f5aa0bd460ca20af908ce878478))
* set helloHandler as sync func ([adf1e0b](https://github.com/web4er/personal-agent/commit/adf1e0b233378d6a9677fa9a94419af17f6325aa))
* truncate name to 63 characters to respect RFC 1035 ([dad0189](https://github.com/web4er/personal-agent/commit/dad01899fa71409a407f68b6f92de79768296e53))
* update missed rename ([e14dc6b](https://github.com/web4er/personal-agent/commit/e14dc6b2162bbbb9f0860cb023a1308eb9ffbbec))
* update missing handler message ([4a36e64](https://github.com/web4er/personal-agent/commit/4a36e6435a0604c77c0fc9d1bfd3527577448f88))
* update worker ([9de5740](https://github.com/web4er/personal-agent/commit/9de5740e024a337b0f27ad1febd099c513cfc62f))
* updated Jest test comment ([16344b7](https://github.com/web4er/personal-agent/commit/16344b78f4894875c011bb7f122173a1910b4472))
* use empty object as default env ([5d33096](https://github.com/web4er/personal-agent/commit/5d33096cc0581cc0e0bddf6ef3f305f3586000ce))
* use empty object for env of no var is passed ([255c89f](https://github.com/web4er/personal-agent/commit/255c89f41a63f036ce7b5d20fb5fa0489665a516))
* use github PAT to reply to command ([059df3d](https://github.com/web4er/personal-agent/commit/059df3db54c7632d29730b1e05d29aea535e0fca))
* use latest update-config workflow script ([61fec2a](https://github.com/web4er/personal-agent/commit/61fec2a2fe45d130114abf5b4d8ed34b0bb1fbb5))
* use PAT for octokit instance ([1f38895](https://github.com/web4er/personal-agent/commit/1f3889566895fb26846525a44d5a14aa79891c2e))
